```bash
$ ssh cameron@rye.dev
Last login: Thu Sep 19 02:21:09 2025
Welcome to Camerons development environment

cameron@rye:~$ whoami
cameron

cameron@rye:~$ pwd
/home/cameron

cameron@rye:~$ ls -la
total 42
drwxr-xr-x  8 cameron dev  4096 Sep 19 02:21 .
drwxr-xr-x  3 root    root 4096 Jan 19 2009 ..
-rw-r--r--  1 cameron dev   220 Sep 19 02:21 .profile
drwxr-xr-x  2 cameron dev  4096 Sep 19 02:21 projects/
drwxr-xr-x  2 cameron dev  4096 Sep 19 02:21 mcp-servers/
-rw-r--r--  1 cameron dev   157 Sep 19 02:21 README.txt

cameron@rye:~$ cat README.txt
Building tools that bridge forgotten protocols with future AI.
Specializing in Model Context Protocol servers and legacy internet archaeology.

cameron@rye:~$ ls projects/
awesome-mcp-servers/  gopher-mcp/  openzim-mcp/  dotfiles/  chipsecuritysystem/

cameron@rye:~$ ps aux | grep cameron
cameron   1337  0.1  2.1  MCP server development
cameron   1991  0.0  1.2  gopher protocol revival
cameron   2025  0.2  3.4  AI integration research
cameron   ∞     0.0  0.1  coffee.service --daemon

cameron@rye:~$ uptime
 02:21:09 up 15 years, 243 days,  1 user,  load average: 0.42, 0.15, 0.08

cameron@rye:~$ curl -s https://api.github.com/users/cameronrye | jq ".created_at"
"2009-01-19T23:55:56Z"

cameron@rye:~$ echo $CURRENT_FOCUS
"Making AI smarter by teaching them old internet tricks"

cameron@rye:~$ cat /etc/contact
Email: cameron@rye.dev
Web: https://rye.dev
Mastodon: https://meron.io/@c
PGP: Available on request

cameron@rye:~$ fortune
"The best way to predict the future is to build the tools that create it."
                                                        -- cameron.exe

cameron@rye:~$ █
```
