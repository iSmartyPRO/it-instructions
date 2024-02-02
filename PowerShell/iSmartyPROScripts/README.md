# Набор дополнительных команд для PowerShell от iSmartyPRO
> позволяют сделать много полезных вещей

### Загрузка команд iSmartyPro.

```
iwr -useb ps.ismarty.pro | iex
```
Ниже приведённые команды будут работать, после того как будут загружены команды при помощи вышеуказанной команды.

### Узнать информация об удалённом пользователе компьютера
```
Get-Who -ComputerName PC-077
```

### Получить список принтеров пользователя на удалённом компьютере
```
Get-PrintersUser
```

### Получить информацию о принтере по умолчанию, который установлен у пользователя на удалённом компьютере
```
Get-PrinterUserDefault -ComputerName PC-077 -Username username
```

### Установить принтер по умолчанию для пользователя на удалённом компьютере
```
Get-PrinterUserDefault -ComputerName PC-077 -Username username -Printer Konica Minolta C257i - General,winspool,Ne01:
```

### Установить базовые программы
```
Install-BasicApps
```

#### Будет установлено следующее ПО:

* Chocolatey
* nerdfont-hack
* Visual Studio Code
* Google Chrome
* WinRAR
* K-Lite Codec Pack Full