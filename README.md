<div align="center">

## Set Datagrid Column Width


</div>

### Description

This is a simple example of how to dynamically set the column width in a DataGrid control. I spent hours trying to find something that seemed to me should have been a simple help example. I hope I can save somebody some time.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Mike M\. Mitchell](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mike-m-mitchell.md)
**Level**          |Beginner
**User Rating**    |4.1 (58 globes from 14 users)
**Compatibility**  |VB\.NET
**Category**       |[Algorithims](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/algorithims__10-29.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mike-m-mitchell-set-datagrid-column-width__10-534/archive/master.zip)





### Source Code

```
Dim myGridTableStyle As DataGridTableStyle = New DataGridTableStyle()
    'Map the style to the dataset table. In this case I only use one table
    ' in my query.
    myGridTableStyle.MappingName = "Insured"
    grdQuotes.TableStyles.Add(myGridTableStyle)
    myGridTableStyle.GridColumnStyles(0).Width = 0
    myGridTableStyle.GridColumnStyles(1).Width = 250
    myGridTableStyle.GridColumnStyles(2).Width = 250
```

