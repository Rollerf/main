# Light control
## Introduction
This project is a simple light control using a telegram bot for controll it remotely.

## Requirements
* ESP32
* Telegram bot
* 6 Relay

## PINOUT
| Name                | Name in board | GPIO/IDE Arduino name |
|---------------------|---------------|-----------------------|
| Row 1               | IO26          | 26                    |
| Row 2               | TCK           | 13                    |
| Row 3               | IO33          | 33                    |
| Row 4               | TMS           | 14                    |
| Row 5               | IO17          | 17                    |
| Row 6               | IO16          | 16                    |

## Bot commands
Go to @BotFather and put /setcommands in chat. Then select your bot an paste this list:

set_all_on - Enciende todas las luces
set_all_off - Apagar todas las luces
set_on_row_3 - Enciende fila 3
get_estado_luces - Obtiene el estado de todas las luces
get_all_commands - Obtiene todos los comandos
