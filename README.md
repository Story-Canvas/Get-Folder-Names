# *Simple Administration PowerShell Scripts*
## Script: Get Folder Names 

**Description:**
A simple folder name gathering script inside a directory (does not dig into subdirectories).

**Customizable:**
```powershell
$directoryPath = "C:\temp\"
```
- C:\temp\: Change this to your desired directory path. 

---

**Output:**
- Uses Out-GridView to easily copy the results and paste into an excel worksheet. (Change this to a .csv output if preferred)
