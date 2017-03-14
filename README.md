# SeedProject.NET
This is just a basic folder structure for creating new repositories.  
A nice alternative is Project Scaffold: https://github.com/fsprojects/ProjectScaffold

#### If you are using this repo as a base for a new one you should probably remove most of this README text. ;)

### Folder purposes
* doc
    * Any documentation relavant to the contents of the repository
* lib
    * Build Dependencies
	* These should not be from NuGet
* packages
    * NuGet packages
        * I know, I know, these shouldn't be checked in, sometimes a project is messed up enough that this is necessary during cleanup...
* src
    * The source code for this repository
	* The root of this folder should consist only of folders any sln's or .*proj files should be within appropriate solution or project folders.
* data
    * The data projects and files for this repository
	* Data projects (e.g. *.sqlproj) should be stored in directories, data files (e.g. *.json, *.xml) may be stored in the root of this folder.

### Dev Notes
* It is specific to .NET only in it's use of a visual studio style .gitignore and the nuget.config
* nuget.config attempts to direct nuget libraries to the packages folder
