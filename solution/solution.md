## Пояснения к решению

Запускал сервер rasa командой rasa run --cors "*" --enable-api --log-file rasa_debug.log, если добавить --log-level DEBUG, то ошшибка
usage: rasa run [-h] [-v] [-vv] [--quiet] [--logging-config-file LOGGING_CONFIG_FILE] [-m MODEL] [--log-file LOG_FILE]
[--use-syslog] [--syslog-address SYSLOG_ADDRESS] [--syslog-port SYSLOG_PORT]
[--syslog-protocol SYSLOG_PROTOCOL] [--endpoints ENDPOINTS] [-i INTERFACE] [-p PORT] [-t AUTH_TOKEN]
[--cors [CORS ...]] [--enable-api] [--response-timeout RESPONSE_TIMEOUT]
[--request-timeout REQUEST_TIMEOUT] [--remote-storage REMOTE_STORAGE]
[--ssl-certificate SSL_CERTIFICATE] [--ssl-keyfile SSL_KEYFILE] [--ssl-ca-file SSL_CA_FILE]
[--ssl-password SSL_PASSWORD] [--credentials CREDENTIALS] [--connector CONNECTOR]
[--jwt-secret JWT_SECRET] [--jwt-method JWT_METHOD] [--jwt-private-key JWT_PRIVATE_KEY]
{actions} ... [model-as-positional-argument]
rasa run: error: argument {actions}: invalid choice: 'DEBUG' (choose from 'actions')