Font:
Try
Dim dlg As FontDialog = New FontDialog
dlg.Font =TextBox1.Font
If dlg.ShowDialog = System.Windows.Forms.DialogResult.OK Then
TextBox1.Font = dlg.Font
End If
Catch ex As Exception : End Try
========================================­==
Color : 
Try
Dim dlg As ColorDialog = New ColorDialog
dlg.Color =TextBox1.ForeColor
If dlg.ShowDialog = System.Windows.Forms.DialogResult.OK Then
TextBox1.ForeColor = dlg.Color
End If
Catch ex As Exception : End Try
========================================­==
Copy:
TextBox1.Copy()
========================================­==
Cut:
TextBox1.Cut()
========================================­==
Paste:
TextBox1.Paste()
========================================­==
Exit :
End
=====================================
Select All:
TextBox1.SelectAll()
====================================
msgbox "اكتب اي شي هنا"
كود ABOUT
