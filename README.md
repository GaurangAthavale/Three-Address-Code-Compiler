# Three-Address-Code-Compiler
Contains code for if-else and while loop and for loop generation in Three Address Code format.

Before running this, ensure that prettytable module is installed or else you can run
```
pip install prettytable
```

[Source code for while loop](For_Loop/for.py)<br>
[Source code for for loop](While_Loop/while.py)


### Output

#### While loop

<img src="img/while.png">

#### For loop

<table>
    <th>
        Without "while" intermediate
    </th>
    <th>
        With "while" intermediate
    </th>
<tr>
    <td>
        <img src="img/for.png">
    </td>
    <td>
        <img src="img/for_with_intermediate.png">
    </td>
</tr>
</table>
