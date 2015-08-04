# SeedProject.NET
This is just a basic folder structure for creating new repositories.

#### If you are using this repo as a base for a new one you should probably remove most of this README text. ;)

### Folder purposes
* doc
    * Any documentation relavant to the contents of the repository
* lib
    * Libraries necessary to build the projects within the repository
	* Most of these are likely from nuget
* src
    * The source code for this repository
	* The root of this folder should consist only of folders any sln's or .*proj files should be within appropriate solution or project folders.

### Dev Notes
* It is specific to .NET only in it's use of a visual studio style .gitignore and the nuget.config
* nuget.config attempts to direct nuget libraries to the lib folder