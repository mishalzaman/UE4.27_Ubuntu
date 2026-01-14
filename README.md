# UE4.27_Ubuntu


# 1. Create Project
First, launch the vanilla Editor to generate the initial .uproject file.

```
cd /mnt/data/UE4.27/Engine/Linux/
./UE4Editor
```

# 2a. Build Project (CLI)
To compile the C++ logic for the Editor, run the build script from the root of your project folder.

```
# Syntax: Build.sh <ProjectName>Editor Linux Development -project="<PathToUproject>"
/mnt/data/UE4.27/Engine/Build/BatchFiles/Linux/Build.sh testcppEditor Linux Development -project="$(pwd)/testcpp.uproject"
```

# 2b. Or Build Project (VS Code)
If you prefer building directly inside Visual Studio Code:

Open the project folder in VS Code.

Press Ctrl+Shift+B to open the Build Tasks.

Select the task:

ProjectNameEditor Linux Development Build (e.g., testcppEditor Linux Development Build)

# 4. Run Project
Launch the Unreal Editor with your specific project loaded.

```
/mnt/data/UE4.27/Engine/Binaries/Linux/UE4Editor ~/Documents/testcpp/testcpp.uproject
```

