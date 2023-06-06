# TCP/IP網路瑞士刀 超強網路指令工具 netcat


## 指令參數 nc -h
```
[v1.10-41.1]
connect to somewhere:	nc [-options] hostname port[s] [ports] ... 
listen for inbound:	nc -l -p port [-options] [hostname] [port]

options:
	-c shell commands	as `-e'; use /bin/sh to exec [dangerous!!]
	-e filename		program to exec after connect [dangerous!!]
	-b			      allow broadcasts
	-g gateway		source-routing hop point[s], up to 8
	-G num			  source-routing pointer: 4, 8, 12, ...
	-h			      this cruft
	-i secs			  delay interval for lines sent, ports scanned
  -k            set keepalive option on socket
	-l			      listen mode, for inbound connects
	-n			      numeric-only IP addresses, no DNS
	-o file			  hex dump of traffic
	-p port			  local port number
	-r			      randomize local and remote ports
	-q secs			  quit after EOF on stdin and delay of secs
	-s addr			  local source address
	-T tos			  set Type Of Service
	-t			      answer TELNET negotiation
	-u			      UDP mode
	-v			      verbose [use twice to be more verbose]
	-w secs			 timeout for connects and final net reads
	-C			     Send CRLF as line-ending
	-z			     zero-I/O mode [used for scanning]
  
port numbers can be individual or ranges: lo-hi [inclusive];
hyphens in port names must be backslash escaped (e.g. 'ftp\-data').

```

## 範例
- [How to Use Netcat Commands: Examples and Cheat Sheets](https://www.varonis.com/blog/netcat-commands)
- [TCP/IP 瑞士刀般的超強網路指令工具：netcat](https://ithelp.ithome.com.tw/articles/10135783)
- [強大的 netcat 功能與相對應的工具](https://ithelp.ithome.com.tw/articles/10136033)
- [神奇的指令：netcat](https://blog.miniasp.com/post/2008/07/11/A-magic-command-netcat)


printf "GET /index.html HTTP/1.0\r\nHost: info.cern.ch\r\n\r\n" | nc info.cern.ch 80
