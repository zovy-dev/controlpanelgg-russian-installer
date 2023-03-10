<h1 align=center>ControlPanel установщик</h1>

Это скрипт установки для [ControlPanel](https://controlpanel.gg/)<br>
Этот скрипт не связан с официальным проектом.

<h1 align="center">Функции</h1>

- Автоматическая установка ControlPanel (зависимости, база данных, cronjob, nginx).
- Автоматическая настройка UFW (брандмауэр для Ubuntu/Debian).
- (Необязательно) автоматическая настройка Let's Encrypt.
- (Необязательно) Автоматическое обновление панели до более новой версии.

<h1 align="center">Support</h1>

<h1 align=center>Поддерживаемые установки</h1>

Список поддерживаемых настроек установки для панели (установки, поддерживаемые этим скриптом установки).

<h1 align="center">Системы, поддерживаемые скриптом</h1></br>

|  Операционная система    |  Version       | ✔️ \| ❌    |
| :---                  |     :---       | :---:      |
| Debian                | 9              | ✔️         |
|                       | 10             | ✔️         |
|                       | 11             | ✔️         |
| Ubuntu                | 18             | ✔️         |
|                       | 20             | ✔️         |
|                       | 22             | ✔️         |
| CentOS                | 7              | ✔️         |
|                       | 8              | ✔️         |


<h1 align="center">How to use</h1>

Just run the following command as root user.

```bash
bash <(curl -s https://raw.githubusercontent.com/Ferks-FK/ControlPanel-Installer/development/install.sh)
```

<h1 align="center">Attention!</h1>

*Do not run the command using sudo.*

**Example:** ```$ sudo bash <(curl -s...```

*You must be logged into your system as root to use the command.*

**Example:** ```# bash <(curl -s...```


<h1 align="center">Development</h1>

This script was created and is being maintained by [Ferks - FK](https://github.com/Ferks-FK).

<h1 align="center">Extra informations</h1>

If you have any ideas, or suggestions, feel free to say so in the [Support Group](https://discord.gg/buDBbSGJmQ).
