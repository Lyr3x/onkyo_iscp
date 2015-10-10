# onkyo_iscp

This program is used to send eISCP commands to an onkyo AVR

## Commands
You can find all possible commands in the `eiscp-commands.yaml` config file and send them with the following structure:

`./onkyo-iscp <HOST> <CMD> <VALUE>`

e.g.: 

This command will change the powerstatus to standby <br>
`./onkyo-iscp 192.168.1.10 PWR 00`
