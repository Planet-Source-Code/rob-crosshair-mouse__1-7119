<div align="center">

## Crosshair Mouse


</div>

### Description

What i did was Make the Code Much Shorter, Went from 25 Lines of Code, to 9 Lines of code..

ORIGINALY DONE BY: thuggish_187
 
### More Info
 
Just Paste it thats all


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Rob](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/rob.md)
**Level**          |Beginner
**User Rating**    |4.3 (30 globes from 7 users)
**Compatibility**  |VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Games](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/games__1-38.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/rob-crosshair-mouse__1-7119/archive/master.zip)





### Source Code

```
Private Sub Form_Load()
 Me.ScaleMode = 3 'Pixel Mode
 Me.MousePointer = 2 'Set Mouse Pointer to Cross
End Sub
Private Sub Form_MouseMove(Button As Integer, _ Shift As Integer, X As Single, Y As Single)
 Cls
 Me.Circle (X, Y), 25 'Draw Circle
 Me.Line (0, Y)-(Me.Width, Y)
 Me.Line (X, 0)-(X, Me.Height)
 Me.CurrentX = X + 35
 Me.CurrentY = Y - 25
 Me.Print "X: " & X & " Y: " & Y
End Sub
```

