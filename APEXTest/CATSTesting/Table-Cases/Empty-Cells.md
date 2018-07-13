# Table Cases: Empty cells testing

## Normal table
| Normal table | Description          |
| ------------- | ----------- |
| 1_Help      | Display the help window.|
| Close     | _Closes_ a window     |

## Empty cells

### Empty cell on top Right corner of table
<table>
<thead>
<tr>
<th>Empty Cell</th>
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
<td>Close1</td>
<td>Close2</td>
</tr>
</tbody>
</table> 

### Empty cell on bottom right corner of table

<table>
<thead>
<tr>
<th>Empty Cell</th>
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

### Table with colspan(error)
<table>
 <tr>
 <th><p><br>0</p></th>
 <th><p><br>1</p></th>
 <th><p><br>2</p></th>
 <th><p><br>3</p></th>
 <th><p><br>4</p></th>
 <th><p><br>5</p></th>
 <th><p><br>6</p></th>
 <th><p><br>7</p></th>
 <th><p><br>8</p></th>
 <th><p><br>9</p></th>
 <th><p>1<br>0</p></th>
 <th><p><br>1</p></th>
 <th><p><br>2</p></th>
 <th><p><br>3</p></th>
 <th><p><br>4</p></th>
 <th><p><br>5</p></th>
 <th><p><br>6</p></th>
 <th><p><br>7</p></th>
 <th><p><br>8</p></th>
 <th><p><br>9</p></th>
 <th><p>2<br>0</p></th>
 <th><p><br>1</p></th>
 <th><p><br>2</p></th>
 <th><p><br>3</p></th>
 <th><p><br>4</p></th>
 <th><p><br>5</p></th>
 <th><p><br>6</p></th>
 <th><p><br>7</p></th>
 <th><p><br>8</p></th>
 <th><p><br>9</p></th>
 <th><p>3<br>0</p></th>
 <th><p><br>1</p></th>
 </tr>
 <tr>
 <td colspan="8">
 <p>backgroundRepeatStart</p>
 </td>
 <td colspan="8">
 <p>backgroundRepeatValue</p>
 </td>
 </tr>
</table>

### Table with colspan(correct)
<table>
 <tr>
 <th><p><br>0</p></th>
 <th><p><br>1</p></th>
 <th><p><br>2</p></th>
 <th><p><br>3</p></th>
 <th><p><br>4</p></th>
 <th><p><br>5</p></th>
 <th><p><br>6</p></th>
 <th><p><br>7</p></th>
 <th><p><br>8</p></th>
 <th><p><br>9</p></th>
 <th><p>1<br>0</p></th>
 <th><p><br>1</p></th>
 <th><p><br>2</p></th>
 <th><p><br>3</p></th>
 <th><p><br>4</p></th>
 <th><p><br>5</p></th>
 <th><p><br>6</p></th>
 <th><p><br>7</p></th>
 <th><p><br>8</p></th>
 <th><p><br>9</p></th>
 <th><p>2<br>0</p></th>
 <th><p><br>1</p></th>
 <th><p><br>2</p></th>
 <th><p><br>3</p></th>
 <th><p><br>4</p></th>
 <th><p><br>5</p></th>
 <th><p><br>6</p></th>
 <th><p><br>7</p></th>
 <th><p><br>8</p></th>
 <th><p><br>9</p></th>
 <th><p>3<br>0</p></th>
 <th><p><br>1</p></th>
 </tr>
 <tr>
 <td colspan="16">
 <p>backgroundRepeatStart</p>
 </td>
 <td colspan="16">
 <p>backgroundRepeatValue</p>
 </td>
 </tr>
</table>
