# Merged Table(rowspan/colspan)
## Normal rowspan merged table1
<table>
    <thead>
        <tr>
            <th>Column1-1</th>
            <th>Column2-1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan='2'>row1 value1-1</td>
            <td>row1 value2-1</td>
        </tr>
        <tr>
            <td>row2 value1-1</td>
        </tr>
    </tbody>
</table>

## Normal colspan merged table2
<table>
    <thead>
        <tr>
            <th>Column1-2</th>
            <th>Column2-2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan='2'>row1 value1-2</td>
        </tr>
        <tr>
            <td>row2 value1-2</td>
            <td>row2 value2-2</td>
        </tr>
    </tbody>
</table>

## Normal rowspan and colspan merged table3
<table>
    <thead>
        <tr>
            <th>Column1-3</th>
            <th>Column2-3</th>
            <th>Column3-3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan='2' rowspan='2'>row1 value1-3</td>
            <td>row1 value1-3</td>
        </tr>
        <tr>
            <td>row2 value1-3</td>
        </tr>
    </tbody>
</table>

## Variance rowspan merged table4(missing rowspan)
<table>
    <thead>
        <tr>
            <th>Column1-4</th>
            <th>Column2-4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>row1 value1-4</td>
            <td>row1 value2-4</td>
        </tr>
        <tr>
            <td>row2 value1-4</td>
        </tr>
    </tbody>
</table>

## Variance colspan merged table5(different colspan)
<table>
    <thead>
        <tr>
            <th>Column1-5</th>
            <th>Column2-5</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan='3'>row1 value1-5</td>
        </tr>
        <tr>
            <td>row2 value1-5</td>
            <td>row2 value2-5</td>
        </tr>
    </tbody>
</table>

## Variance rowspan and colspan merged table6(different content)
<table>
    <thead>
        <tr>
            <th>Column1-6</th>
            <th>Column2-6</th>
            <th>Column3-6</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan='2' rowspan='2'>row1 value1-6-</td>
            <td>row1 value1-6</td>
        </tr>
        <tr>
            <td>row2 value1-6</td>
        </tr>
    </tbody>
</table>