# UE4.27_Ubuntu

## 1. Run the Editor
```
cd /mnt/data/UE4.27/Engine/Linux/
./UE4Editor
```

Create a new project

## 2. Build it
```
/mnt/data/UE4.27/Engine/Build/BatchFiles/Linux/Build.sh testcppEditor Linux Development -project="$(pwd)/testcpp.uproject"
```

## 3. Visual Code
Open the build options (Ctrl+Shift+B) and select the one with _ProjectNameEditor Linux Development Build_

## 4. Run the Project
Finally run the project with
```
/mnt/data/UE4.27/Engine/Binaries/Linux/UE4Editor ~/Documents/testcpp/testcpp.uproject
```
