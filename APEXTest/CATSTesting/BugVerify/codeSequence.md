When our form loads, we can configure the ``BindingCollection``.  To do that we add some code to the ``Form_Load`` event.

10.  Add the following subroutine to the form's ``Load`` event:

```
Private Sub Form_Load()
With bndPublishers  .DataMember = "Publishers"  Set .DataSource = clsBoundClass 
 .Add txtPubID, "Text", "PubID"  .Add txtName, "Text", "Name"
  MsgBox "Number of items bound:  " &  .Count
End With
End Sub
``` 
What happens here? First, we set the ``DataMember`` property of the ``bndPublishers` BindingCollection``. Remember the ``GetDataMember`` procedure in our class? Well, ``GetDataMember`` sets the source of the data for the class. We must provide a unique string because a class might have several ``DataMembers``. Here, again, we are only interested in one – the one that refers to the ``Publishers`` table.

Next, the ``DataSource`` of the ``BindingCollection`` is hooked up to our class, ``clsBoundClass``, which we set as a data provider. Now we can add items to be bound. We are adding our two text boxes to the ``BindingCollection`` using its ``Add`` method.  The general syntax of the Add method looks like this:

```object.Add(object, PropertyName, DataField, DataFormat, Key)```
The table shows the options for the ``bindingCollection``'s ``Add`` method:

Parameter	Required/Optional	Description
Object	Required	The control or other data consumer which will be bound. Here we use the names of the two text boxes for each ``Add``.
PropertyName	Required	The property of the data consumer to which the data field will be bound. We want the ``Text`` property of the textboxes to be bound.
DataField	Required	The column of the data source that will be bound to the property specified in the PropertyName argument. We insert the data field from the Publishers database that we wish to be bound to the text box.
DataFormat	Optional	A ``DataFormat`` object or a reference to a ``DataFormat`` variable that will be used to format the bound property.
Key	Optional	A unique string that identifies the member of the collection.
So we are simply initializing our ``BindingCollection``, then adding the text boxes to the collection. You could add as many as you wish. Again, we wanted to concentrate on the code so we stuck with only two. Next, we interrogate the ``Count`` property of the collection and display this in a message box. When we run our program, we should see two bound items (i.e. both of the text boxes we inserted using the ``Add`` method).