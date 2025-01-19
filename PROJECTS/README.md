## TO CREATE A NEW PROJECT
Create a new folder for each project you make inside the PROJECTS folder.
Make sure you are inside PROJECTS folder (terminal should show /PROJECTS at the end), run this command, changing ProjectName to whatever you want:
```bash
dotnet new console -n "ProjectName"
dotnet sln add ProjectName/ProjectName.csproj
```

You can check if the project was added to the solution successfully with 
```bash
dotnet sln list
```

Then go into it and open the Codespace on the folder itself (this is necessary for the debugger to work)
```bash
cd ProjectName
code .
```

Then build and run the project so it is ready to go.
```bash
dotnet build
dotnet run --project ProjectName.csproj
```

You can now debug your project with F5 or by pressing the Play button on the top right!!

I recommend you bookmark the main Codespace (the one that opens PROJECTS) to make it easier to go back to it.
