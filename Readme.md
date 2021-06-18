#Txt2Png

**Purpose:** Convert Powershell to a Png file, use PngStub to download and execute.

Having seen the Powershell/Payloads as PNG files that get decoded then executed, seemd like a fun thing to write a dirty script to do with powershell. The code is slow, ugly and unfriendly. Little to Zero practical use but was fun to make.

___

**Usage:**
> - .\Txt2Png.ps1 mypowershellcode.ps1 out.png
> - Upload out.png to some site
> - via Powershell run [Convert]::ToBase64String([System.Text.Encoding]::Unicode.GetBytes('URLtoPNG'))
> - Put Base64 String into PngStub.ps1
> - Find way to execute PngStub.ps1 remotely.
___

**Example Png Image**
![Useless example](/test.txt.png)

**P.S:** *This code is not supporse to be user-friendly to read, and no there is no good reason for it, other than wanting to make some ugly code.*