# Chocolatey

[Official Website](https://chocolatey.org/)

The Package Manager for Windows

Modern Software Automation


### Установка [Chocolatey](https://chocolatey.org/install)

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
### Установка Visual Studio Code
```
choco install vscode -y
```
### Установка Google Chrome
```
choco install googlechrome -y
```
### Установка WinRAR
```
choco install winrar -y
```
### Установка Visual C++ Redistributable Runtimes All-in-One
```
choco install vcredist-all -y
```
### Установка K-Lite Codec Pack Full
```
choco install k-litecodecpackfull -y
```

### Установка Classic Shell
```
choco install classic-shell -y
```
### Установка CCleaner
```
choco install ccleaner -y
```
### Установка Windows Terminal
```
choco install microsoft-windows-terminal -y
```
### Установка FlowLauncher
```
choco install flow-launcher -y
```

## Прочие полезные команды

### Справка
```
choco help
```

### Список установленных программ

```
choco list
```

### Обновление установленного пакета
```
choco update имя_пакета
```

### Установка графического интерфейса для Chocolatey
```
choco install chocolateygui -y
```