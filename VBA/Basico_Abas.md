

'SELECIONAR VÁRIAS ABAS

	For Each aba in ThisWorkbook.Sheets
		If aba.Name <> "Instruções" Then
			aba.Select
			Range("H5").Value = "Minha Linda"
		End If
	Next



'SELECIONAR ABA 

	Worksheets("Sheet1").Activate



'SALVAR ARQUIVO 

	ThisWorkbook.Save
