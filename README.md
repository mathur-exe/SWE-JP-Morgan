# SWE JP Morgan
 
### Creating virtualenv
```
python -m virtualenv .venv
Set-ExecutionPolicy Unrestricted -Scope Process
.\.venv\Scripts\activate.ps1
```

### Creating a patch file
```
cd <directory_name>
git format-patch -1 HEAD
```