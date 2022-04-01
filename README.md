# Practica3 Primitive Datatype

  
### Task 1 : Use 'Get-Help' to find out more information about 5 cmdlets

`Get-Help Out-GridView`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20Grid.png)

`Get-Help Get-AppBackgroundTask`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20Get-AppBackGround.png)

`Get-Help Get-BCStatus`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20Get-BCStatus.png)

`Get-Help Get-ChildItem`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20Get-ChildItem.png)

`Get-Help New-Event`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20New-Event.png)

### Task 2 : Use “Get-Help” with the “–Example” parameter for the 5 cmdlets you discovered more about in task 1.

`Get-Help Out-GridView -Example`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20Out-GridView%20-Example.png)

`Get-Help Get-AppBackgroundTask -Example`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20Get-AppBackgroundTask%20-Example.png)

`Get-Help Get-BCStatus -Example`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20Get-BCStatus%20-Example.png)

`Get-Help Get-ChildItem -Example`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20Get-ChildItem%20-Example.png)

`Get-Help New-Event -Example`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Help%20New-Event%20-Example.png)


### Task 3: Create a new text file named “TestFile.txt” under C:\Maximo\PowerShell\Workshop1\%USERNAME%

`New-Item -Path C:\Maximo\PowerShell\Workshop1\%USERNAME% -Name PoweShell -ItemType Directory`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Crear%20directorio%20Actividad%203.png)

`New-Item -Path C:\Maximo\PowerShell\Workshop1\%USERNAME% -Name TestFile.txt -ItemType File`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/crear%20archivo%20actividad%203.png)

### Task 4 : Populate the text file you created in task 3 with all three datatypes we’ve covered: “Boolean”, “String” and “Int”

`Add-Content -Path .\Maximo\PowerShell\Workshop1\%USERNAME%\TestFile.txt -Value False`

`Add-Content -Path .\Maximo\PowerShell\Workshop1\%USERNAME%\TestFile.txt -Value 'Hi'`

`Add-Content -Path .\Maximo\PowerShell\Workshop1\%USERNAME%\TestFile.txt -Value 300`

`ii .\Maximo\PowerShell\Workshop1\%USERNAME%\TestFile.txt`

![]()

### Task 5 : Read from the text file and use “Get-Member” to findthe datatype returned


### Task 6 : Overwrite all data within the text file that you created in task 3.

`Set-Content -Path .\Maximo\PowerShell\Workshop1\%USERNAME%\TestFile.txt -Value "New content"`

`Get-Content -Path .\Maximo\PowerShell\Workshop1\%USERNAME%\TestFile.txt`

  
![]()

### Task 7 : Format the data returned by a cmdlet into a list

![]()

### Task 8 : Pipe “Get-Command” into “Out-GridView”

`Get-Command | Out-GridView`

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Get-Command.png)

### Task 9 : Pipe the 5 cmdlets you discovered in task 1 into “Out-GridView”

### Task 10 : Find the official PowerShell documentation library from Microsoft

https://docs.microsoft.com/en-us/powershell/

![](https://github.com/MelissaRodriguezHernandez/Practica3PrimitiveDatatype/blob/main/Img/Web%20PowerShell%20Documentation.png)
  

