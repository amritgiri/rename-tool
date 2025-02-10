# rename-tool
A tool to rename bunch of files inside a folder having same extension within a second on a count basis.
# Install
You can download the `.deb` and then run command
```
sudo dpkg -i rename-tool-1.0.deb
```
You can clone the repository
```
git clone https://github.com/amritgiri/rename-tool.git
cd rename-tool
chmod +x rename-tool
```

# Usage
```
Usage: rename-tool -d <directory>
Options:
 -d             Specify the Directory containing files to rename
 -v             Enable verbose mode to show renaming process
 -h             Display this help message
 --version      Show the tool's version.
```

# Example
```
./rename-tool -d /path/to/directory
```

If you downloaded `.deb` package then do
```
rename-tool -d /path/to/directory
```

# How does it work?

The tool will first check if the directory provided is valid or not. If it is, then it will just recursively rename the files inside the directory.

If the directory is not available or not provided then it throws an error.

# Uninstall 
```
sudo apt remove rename-tool
```