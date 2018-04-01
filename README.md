# MvcAngular

## Generator
Download the following package and extract the files into a folder that is listed in the system Path environmental variable.
https://github.com/JackYumCha/MvcAngular/releases/tag/MvcAngular.Kernel

## Asp.Net Setup
The asp.net project should add reference to this nuget package:
https://www.nuget.org/packages/MvcAngular.Generator/1.0.0
Angular and AngularType attributes should be added to controllers and frontend types respectively.

## Angular Setup
In the scripts sections of the Angular project, add the following codes:
```
"api": "mvcng -s \"..\\RelativePathToSourceProject\" -p \"..\\RelativePathToSourceProject\\SourceProject.csproj\" -t src\\app\\services\\mvc-api -a \"AssemblyName1;AssemblyName2\" "
```
The Asseembly names should be separated by semi comma ';'.
