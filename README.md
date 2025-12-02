```bash
$ ssh cameron@rye.dev
Last login: Mon Dec  2 10:15:42 2025
Welcome to Camerons development environment

cameron@rye:~$ whoami
cameron

cameron@rye:~$ cat /etc/motd
🟢 AVAILABLE FOR HIRE - Senior Software Engineer
   TypeScript/React • .NET • AI/MCP Specialist

cameron@rye:~$ ls -la
total 48
drwxr-xr-x  8 cameron dev  4096 Dec  2 10:15 .
drwxr-xr-x  3 root    root 4096 Jan 19 2009 ..
-rw-r--r--  1 cameron dev   220 Dec  2 10:15 .profile
drwxr-xr-x  2 cameron dev  4096 Dec  2 10:15 projects/
drwxr-xr-x  2 cameron dev  4096 Dec  2 10:15 mcp-servers/
drwxr-xr-x  2 cameron dev  4096 Dec  2 10:15 libraries/
-rw-r--r--  1 cameron dev   157 Dec  2 10:15 README.txt

cameron@rye:~$ cat README.txt
Building tools that bridge forgotten protocols with future AI.
Specializing in Model Context Protocol servers and legacy internet archaeology.

cameron@rye:~$ ls mcp-servers/
activitypub-mcp/  atproto-mcp/  gopher-mcp/  openzim-mcp/

cameron@rye:~$ ls projects/
doskit/  circle-of-fifths/  em-spectrum-explorer/

cameron@rye:~$ ls libraries/
frostpane/  retro-floppy/

cameron@rye:~$ ps aux | grep cameron
cameron   1337  0.1  2.1  MCP server development
cameron   1991  0.0  1.2  fediverse bridge daemon
cameron   2025  0.2  3.4  atproto integration
cameron   8086  0.1  1.8  doskit.wasm --retro
cameron   3141  0.1  1.5  frostpane.css --glass
cameron   ∞     0.0  0.1  coffee.service --daemon

cameron@rye:~$ uptime
 10:15:42 up 15 years, 318 days,  1 user,  load average: 0.42, 0.15, 0.08

cameron@rye:~$ curl -s https://api.github.com/users/cameronrye | jq ".created_at"
"2009-01-19T23:55:56Z"

cameron@rye:~$ echo $CURRENT_FOCUS
"Teaching AI to speak forgotten internet protocols"

cameron@rye:~$ cat /etc/contact
Email: cameron@rye.dev
Web: https://rye.dev
Resume: https://cv.rye.dev
Mastodon: https://meron.io/@c
PGP: Available on request

cameron@rye:~$ fortune
"The best way to predict the future is to build the tools that create it."
                                                        -- cameron.exe

cameron@rye:~$ █
```
