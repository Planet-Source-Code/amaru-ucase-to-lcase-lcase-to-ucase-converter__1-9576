<div align="center">

## UCase to LCase & LCase to UCase Converter


</div>

### Description

THIS VERY COOL FUNCTION TAKES A NORMAL STRING AND CONVERT EVERY CHARACTER IN IT FROM UCase TO LCase OR FROM LCase TO UCase... CHECK IT OUT!! AND VOTE IF YOU FIND IT USEFUL
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[amaru](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/amaru.md)
**Level**          |Intermediate
**User Rating**    |3.6 (18 globes from 5 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/amaru-ucase-to-lcase-lcase-to-ucase-converter__1-9576/archive/master.zip)





### Source Code

```

Public Function Convert(orgStr As String) As String
For Counter = 1 To Len(orgStr)
X = Mid(orgStr, Counter, 1)
If X = LCase(X) Then
  X = UCase(X)
Else
  X = LCase(X)
End If
Convert = Convert & X
Next
End Function
```

