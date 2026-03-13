iDRAC stuurt syslog berichten in RFC5424.
De standaard syslog collector van Wazuh accepteert dat niet.
Daarom laten we het binnenkomen via rsyslog naar file en ingesten we dan de file in wazuh
