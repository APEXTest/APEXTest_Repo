#test

* Use the Value property of an rdoColumn to extract data from a specified column.

* Use the Type and Size property settings to determine the data type and size of the data.

* Use the Updatable property to see if the column can be changed.

* Use the SourceColumn and SourceTable property settings to locate the original source of the data.

* Use the OrdinalPosition property to get presentation order of the rdoColumn objects in an rdoColumns collection.

* Use the Attributes and Required property settings to determine optional characteristics and if Nulls are permitted in the column.

* Use the AllowZeroLength property to determine how zero-length strings are handled.

* Use the BatchConflictValue, and OriginalValue properties to resolve optimistic batch update conflicts.

* Use the KeyColumn to determine if this column is part of the primary key.

* Use the Status property to determine if the column has been modified.

* Use the AppendChunk, ColumnSize, and GetChunk methods to manipulate columns that require the use of these methods, as determined by the ChunkRequired property.

When you need to reference data from an rdoResultset column, you can refer to the Value property of an rdoColumn object by:

* Referencing the Name property setting using this syntax:
```
' Refers to the Au_Fname column rdoColumns("Au_Fname")
rs.rdoColumns("Au_Fname")
```
-Or-
```
' Refers to the Au_Fname column 
rs.rdoColumns!Au_Lname
```

* Referencing its ordinal position in the rdoColumns collection using this syntax:
```
rs.rdoColumns(0)
```

The rdoTable object's rdoColumns collection contains specifications for the data columns. You can use the rdoColumn object of an rdoTable object to map a base table's column structure. However, you cannot directly alter the structure of a database table using RDO properties and methods. You can, however, use data definition language (DDL) action queries to modify database schema.

When the rdoColumn object is accessed as part of an rdoResultset object, data from the current row is visible in the rdoColumn object's Value property. To manipulate data in the rdoResultset, you don't usually reference the rdoColumns collection directly. Instead, use syntax that references the rdoColumns collection as the default collection of the rdoResultset.

```
dim rs As rdoResultset
Set rs = cn.OpenResultset("Select * from Authors" _
   & "Where Au_Lname = 'White'",rdOpenForwardOnly)
debug.print rs!Au_Fname   
   'Refers to rdoRecordset object's rdoColumns collection. 
```

<img src="./reference-files/images/flower.jpg" alt="ExternalLink" data-linktype="relative-path" title="">




