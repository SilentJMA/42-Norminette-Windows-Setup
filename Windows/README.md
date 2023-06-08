# Norminette

The Norminette is a tool by 42 Network, to check that the source code respects the school’s norm.

# Installing instructions

### Windows11:

*Tested on Windows11*

## Installing Chocolatey:

First, ensure that you are using an administrative shell.

Run 

```bash
Get-ExecutionPolicy
```

If it returns Restricted, then run

```bash
Set-ExecutionPolicy AllSigned 
```
Or

```bash
Set-ExecutionPolicy Bypass -Scope Process
```
Now run the following command:

```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
<a href="https://chocolatey.org/install"> This is how you can install Chocolatey in your Windows machine</a>

## Installing Python using Chocolatey:

Open your command prompt as Administrator

```bash
choco install python3 --pre 
```

## Installing Norminette:

```bash
pip install --upgrade pip setuptools
pip install norminette
```

### If you want to install gcc

```bash
choco install mingw
```

### If you want to install make

```bash
choco install make
```
<br /><br />
