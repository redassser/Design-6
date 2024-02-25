### [<- Return](../../)

# Lab 5

`service mosquitto status`:

```bash
● mosquitto.service - Mosquitto MQTT Broker
     Loaded: loaded (/lib/systemd/system/mosquitto.service; enabled; vendor preset: enabled)
     Active: active (running) since Sat 2024-02-24 23:41:05 EST; 1min 1s ago
       Docs: man:mosquitto.conf(5)
             man:mosquitto(8)
    Process: 1797 ExecStartPre=/bin/mkdir -m 740 -p /var/log/mosquitto (code=exited, status=0/SUCCESS)
    Process: 1798 ExecStartPre=/bin/chown mosquitto /var/log/mosquitto (code=exited, status=0/SUCCESS)
    Process: 1799 ExecStartPre=/bin/mkdir -m 740 -p /run/mosquitto (code=exited, status=0/SUCCESS)
    Process: 1800 ExecStartPre=/bin/chown mosquitto /run/mosquitto (code=exited, status=0/SUCCESS)
   Main PID: 1801 (mosquitto)
      Tasks: 1 (limit: 1614)
        CPU: 76ms
     CGroup: /system.slice/mosquitto.service
             └─1801 /usr/sbin/mosquitto -c /etc/mosquitto/mosquitto.conf

Feb 24 23:41:04 rpi systemd[1]: Starting Mosquitto MQTT Broker...
Feb 24 23:41:05 rpi systemd[1]: Started Mosquitto MQTT Broker.
```

The two terminals through ssh:

[image]
