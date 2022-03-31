# Practica3 Primitive Datatype

  
### Task 1 : Use 'Get-Help' to find out more information about 5 cmdlets

### Task 2 : Use “Get-Help” with the “–Example” parameter for the 5 cmdlets you discovered more about in task 1.

### Task 3: Create a new text file named “TestFile.txt” under C:\Maximo\PowerShell\Workshop1\%USERNAME%

`New-Item -Path C:\Maximo\PowerShell\Workshop1\%USERNAME% -Name PoweShell -ItemType Directory`

![]()

`New-Item -Path C:\Maximo\PowerShell\Workshop1\%USERNAME% -Name TestFile.txt -ItemType File`

![]()

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

### Task 8 : Pipe “Get-Command” into “Out-GridView”

### Task 9 : Pipe the 5 cmdlets you discovered in task 1 into “Out-GridView”

### Task 10 : Find the official PowerShell documentation library fromMicrosoft
  

