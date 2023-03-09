# Veeam-Rep-Stat

Модуль для просмотра и мониторинга пространства репозиториев Veeam, и их доступности. По умолчанию, для получения списка репозиториев применяется модуль **Veeam.Backup.PowerShell**

**Ключи:** \
`Veeam-Rep-Stat -UseList` использовать список путей из файла (не использовать модуль Veeam) \
`Veeam-Rep-Stat -UseList -Path ".\Veeam-Rep-List.txt"` указать путь к списку (в примере, путь по умолчанию) \
`Veeam-Rep-Stat -SizeRepository` выводит общий и доступный размер раздела с репозиторием \
`Veeam-Rep-Stat -SizeDirectory` выводит список дочерних каталогов с заданиями и их размер

![Image alt](https://github.com/Lifailon/Veeam-Rep-Stat/blob/rsa/Screen/Example-1.0.jpg)
