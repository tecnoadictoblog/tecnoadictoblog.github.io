# Configuración Pandora FMS

### Configuración correo SMTP corporativo

`more /etc/pandora/pandora_server.conf`

**Parametros importantes**
log_file /var/log/pandora/pandora_server.log
verbosity 3
>verbosity 10 para tener el máximo de detalles en pandora_server.log
>
mta_address 192.168.0.55
mta_port 25
mta_user alarmas-pandora
mta_pass mi-password-123
\# mta_auth MTA Auth system (if needed, it supports LOGIN, PLAIN, CRAM-MD5, DIGEST-MD)
mta_auth LOGIN
mta_from Pandora FMS <alarmas-pandora@puertoreal.es>
\# SMTP encryption protocol (none, ssl, starttls)
mta_encryption none

Tras cualquier cambio reiniciar el servicio de Pandora
`/etc/init.d/pandora_server restart`

Para buscar una palabra en cualquier fichero:
`grep -rnw '/path/to/somewhere/' -e 'pattern'`



