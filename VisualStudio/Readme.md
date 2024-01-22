## Extentions
### SonarLint

SonarLint helps you detect and fix Bugs, Code Smells, and Security Vulnerabilities in-IDE.
It supports C#, VB.NET, C, C++, JS, and TS. The extension highlights coding flaws on the fly and provides clear guidance to fix issues before code is committed.

https://marketplace.visualstudio.com/items?itemName=SonarSource.SonarLintforVisualStudio2022

### File Icons
![image](https://user-images.githubusercontent.com/6838752/230880043-bab07aaa-780c-4445-8648-8fa10c9b445d.png)

https://marketplace.visualstudio.com/items?itemName=MadsKristensen.FileIcons


### MS build device/user specific settings

C:\Users\NikolajVindelbo\AppData\Local\Microsoft\MSBuild\Current\Imports\Microsoft.Common.props\ImportAfter

content of 
Custom.props:
<?xml version="1.0" encoding="utf-8"?>
<Project>
  <PropertyGroup>
    <TreatWarningsAsErrors>false</TreatWarningsAsErrors>
  </PropertyGroup>
</Project>
