---
# required metadata
title: You can create tables by assembling a list of words and dividing them with hyphens | Microsoft Docs
ms.prod: .net
ms.technology: 
---

Using tables in your content
---
You can create tables by assembling a list || of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

## Normal table
| 1_Normal table | Description          |
| ------------- | ----------- |
| 1_Help      | Display the help window.|
| Close     | _Closes_ a window     |


## table with cell missing
2_Cell missing  | Second Header
------------- | -------------
2_Content Cell  | Content Cell
  | 
Content Cell  | Content Cell
Content Cell  | Content Cell


## table with cell missing
| 3_table with cell missing | Description          |row3|
| ------------- | ----------- |---------|
| 3_Help      | Display the help window.|
| Close     | _Closes_ a window     |

##Table with cell missing
<table>
<thead>
<tr>
<th>Normal table</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>1_Help</td>
<td>Display the help window.</td>
</tr>
<tr>
<td>Close</td>
</tr>
</tbody>
</table>

## table with empty row

| 4_empty row | Description          |
| ------------- | ----------- |
|      | 4_Display the help window.|
|      | _Closes_ a window     |
|      |    |

## table with empty row(by desighed)

|  |           |
| ------------- | ----------- |
| 5_The first row is empty      | Display the help window.|
| Close     | _Closes_ a window     |


## table with empty column

|   | 6_Empty column  | Right Aligned |
| :------------ |:---------------:| -----:|
|       | 6_some wordy text | $1600 |
|       | centered        |   $12 |
|  | are neat        |    $1 |


## table with empty column

| 6_Empty column  |   |  |
| :------------ |:---------------:| -----:|
|  6_some wordy text     |  |  |
| are neat |         |    |

## table with empty Row and column

| 6_Empty column  |   |  |
| :------------ |:---------------:| -----:|
|  6_some wordy text     |  |  |
|      |         |    |
| are neat |         |    |

## table with only image(s) in entire row or column

| ![smile](Images\flower.jpg) | Only images on Row/Column |
| ------------- | ----------- |
| ![smile](Images\flower.jpg)  | 7_Display the help window. |
| ![smile](Images\flower.jpg)  | _Closes_ a window        |
| ![smile](Images\flower.jpg)    | ![smile](Images\flower.jpg)   |



## Table is wider than main content
|Table is wider than main content|Related links|Description|
|---------------------|-------------|-----------|
|8_ProjectDesignerpageqwqqqqqqqqqqqqqqqqqqqqqqqqqsdfssdsdffsdfqqqqqqqqqqqqqqqqqqqqqq|Related links|Description|

## Html syntax table
<table width='1880px'>
<tr>
 <th width='200'>
 aa
 </th>
  <th width='880'>
 aa
 </th>
  <th width='500'>
 aa
 </th>
  <th width='500'>
 aa
 </th>
</tr>
<tr>
 <td>
 bb
 </td>
 <td>
 bb
 </td>
 <td>
 bb
 </td>
 <td>
 bb
 </td>
</tr>
</table>

