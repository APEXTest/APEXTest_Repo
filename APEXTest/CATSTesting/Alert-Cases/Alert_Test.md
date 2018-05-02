# This is a test for alert

## alert with bold text inside
> [!IMPORTANT]
> After installing the Resource Kit-Tools in Lync Server&nbsp;2013, you must install <STRONG>PsExec.exe</STRONG> and copy <STRONG>PsExec.exe</STRONG> to the following path: \<STRONG>Program Files\ Microsoft Lync Server 2013\Persistent Chat Server Resource Kit\ChatStressTool</STRONG>. If you do not copy <STRONG>PsExec.exe</STRONG>, the Beständiger Chat Stress Tool will throw an error exception, and not perform correctly. Make sure that you meet this prerequisite requirement prior to running the tool. For details about installing <STRONG>PsExec.exe</STRONG>, see <A href="http://go.microsoft.com/fwlink/p/?linkid=282246">http://go.microsoft.com/fwlink/p/?LinkId=282246</A>.

## normal alert
> [!NOTE]
> alert note message

##alert via HTML(table)
### mtps table
<div class="alert">
<div class="mtps-table">
<p>Note</p>
<p> I am message</p>
</div>
</div>



## alert via HTML(div)
### note
<div class="alert">
<p>note</p>
<p> I am message</p>
</div>

### Note (p Tag)
<div class="alert">
<p>Note</p>
<p> I am message</p>
</div>

### Note (strong Tag)
<div class="alert">
<strong>Note</strong>
<p>I am message</p>
</div>

### Note (strong Tag)
<div class="alert">
<strong>Note</strong>
<p>I am message</p>
</div>

### Note (class=NOTE alert)
<div class="NOTE alert">
<p>Note</p>
<p>I am message</p>
</div>

### C++ Note (class = NOTE alert)
<div class="NOTE alert">
<p>C++ Note</p>
<p> I am message</p>
</div>

## alert type note:
> [!NOTE:]
> alert note message

## alert in table
<table>
<thead>
<tr>
<th>Normal table</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>XML table with MD alert</td>
<td> 
> [!WARNING]
> Sample Warning Message
</td>
</tr>
<tr>
<td>XML table with XML alert</td>
<td>
  <alert class="important"> <para>Important content</para> </alert>
</td>
</tr>
<tr>
<td>Other way</td>
<td>
<div class="alert">
<strong>Note</strong>  Right-click to display a context menu if selection or app bar commands are not appropriate UI behaviors. But we strongly recommend that you use the app bar for all command behaviors.
</div>
</td>
</tr>
</tbody>
</table>



