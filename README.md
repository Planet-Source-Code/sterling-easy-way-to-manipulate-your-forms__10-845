<div align="center">

## Easy way to manipulate your forms


</div>

### Description

This will show you how to control any element of any form.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Sterling](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sterling.md)
**Level**          |Beginner
**User Rating**    |4.2 (21 globes from 5 users)
**Compatibility**  |VB\.NET
**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__10-3.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/sterling-easy-way-to-manipulate-your-forms__10-845/archive/master.zip)





### Source Code

```
'This will show you how to control any element of any form.
'To my mind this is a most simple way to solve this problem!
'Important!!! The startup object must be "Strt" or "Main"
'Your project must contain three forms, named as Form1, Form2 and Form3
Public Class Strt
  Public Shared frm1 As New Form1()
  Public Shared frm2 As New Form2()
  Public Shared frm3 As New Form3()
  Shared Sub main()
    Application.Run(frm1)
  End Sub
End Class
'And then you may control your forms or any element as show below:
'Strt.frm2.Show()
'Strt.frm1.Height = 50
'Strt.frm3.Opacity = 75
'or if you form1 contain button1:
'Strt.frm1.button1.Text="Bla-bla"
'For example, your may put this code into Form1_Click event:
'Strt.frm2.Show()
'Strt.frm2.Height = 50
'Strt.frm3.Text = "Form Three"
'Strt.frm3.Show = 50
'Strt.frm1.width = 900
```

