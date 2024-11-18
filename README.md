# xget
linux cli commande

works like xkill: when you run the command, a graphical selector appears, and if you click on one of the open applications, the command retrieves information from the selected application and displays it in the terminal.

put the file in /usr/bin/xget and make it executable

```bash
mv xget /usr/bin/xget
```

```bash
sudo chmod +x /usr/bin/xget
```

here's an example using phpstorm:

```bash
xget

PID : 5225
Application name : phpstorm
Executable path : /snap/phpstorm/443/bin/phpstorm
Path from which : /snap/bin/phpstorm
User : user
Group : user
CPU usage : 23.5%
Memory usage : 3.33GB (21.7%)
```
