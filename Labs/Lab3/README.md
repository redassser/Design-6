### [<- Return](../../)

# Lab 3

SSHed into the raspberry pi and used `pip install` to install pytz, jdcal, astral, and geopy.

`python3 julian.py`:

```bash
Calendar Date: 2024-02-24
Julian Date: 2460364.5
Modified Julian Date: 60364.0
```

`python3 date_example.py`:

```bash
Date: 2024-02-24
Date: 02-24-24
Day of Week: Saturday
Month: February
Year: 2024
176 days after the first day of classes
-72 days before the last day of classes
```

`python3 datetime_example.py`:

```bash
2024-02-24 11:26:26.202557
2024-02-24 11:26:26.202847
2024-02-24 16:26:26.202896
1708791986.2029357
Sat Feb 24 11:26:26 2024
2024-02-24 11:26:26.203091
2024-02-24 16:26:26.203130
```

`python3 time_example.py`:

```bash
Sat Feb 24 11:27:23 2024
Sat Feb 24 11:27:33 2024
Sat Feb 24 11:27:43 2024
^C
```

`python3 sun.py "New York"`:

```bash
Information for New York/USA

Timezone: US/Eastern
Latitude: 40.72; Longitude: -74.00

Dawn:    2024-02-24 06:10:08.107572-05:00
Sunrise: 2024-02-24 06:38:18.309402-05:00
Noon:    2024-02-24 12:09:20-05:00
Sunset:  2024-02-24 17:40:46.086625-05:00
Dusk:    2024-02-24 18:08:58.159835-05:00
```

`python3 moon.py`:

```bash
2024-02-24 Moon Phase: 14
2024-02-25 Moon Phase: 14
2024-02-26 Moon Phase: 15
2024-02-27 Moon Phase: 16
2024-02-28 Moon Phase: 17
2024-02-29 Moon Phase: 18
2024-03-01 Moon Phase: 19
2024-03-02 Moon Phase: 19
2024-03-03 Moon Phase: 20
2024-03-04 Moon Phase: 21
2024-03-05 Moon Phase: 22
2024-03-06 Moon Phase: 23
2024-03-07 Moon Phase: 24
2024-03-08 Moon Phase: 25
2024-03-09 Moon Phase: 26
2024-03-10 Moon Phase: 0
2024-03-11 Moon Phase: 1
2024-03-12 Moon Phase: 2
2024-03-13 Moon Phase: 3
2024-03-14 Moon Phase: 4
2024-03-15 Moon Phase: 5
2024-03-16 Moon Phase: 6
2024-03-17 Moon Phase: 7
2024-03-18 Moon Phase: 8
2024-03-19 Moon Phase: 9
2024-03-20 Moon Phase: 9
2024-03-21 Moon Phase: 10
2024-03-22 Moon Phase: 11
2024-03-23 Moon Phase: 12
2024-03-24 Moon Phase: 13
```

`python3 coordinates.py "Samuel C. Williams Library"`:

```bash
Samuel C. Williams Library, Field House Road, Hoboken, Hudson County, New Jersey, 07030, United States
(40.74480675, -74.02532861159351)
```

`python3 address.py "40.74480675, -74.02532861159351"`:

```bash
Samuel C. Williams Library, Field House Road, Hoboken, Hudson County, New Jersey, 07030, United States
(40.74480675, -74.02532861159351)
```

`python3 cpu.py`:

```bash
The number of physical cores =  4
The number of logical CPUs =  4
The utilization per second as a percentage for each CPU
[0.0, 0.0, 0.0, 0.0]
[1.0, 0.0, 0.0, 0.0]
[0.0, 0.0, 0.0, 1.0]
[0.0, 0.0, 5.1, 0.0]
[0.0, 0.0, 28.4, 0.0]
[0.0, 1.0, 28.4, 1.0]
[0.0, 0.0, 9.4, 0.0]
[0.0, 0.0, 0.0, 0.0]
[0.0, 2.0, 0.0, 0.0]
[0.0, 0.0, 0.0, 0.0]
```

`python3 battery.py`:

```bash
None
```

`python3 documentstats.py document.txt`:

```bash
Word Count: 1343
Top Ten Words: [('our', 26), ('their', 20), ('has', 20), ('he', 19), ('them', 15), ('these', 13), ('have', 11), ('we', 11), ('us', 11), ('people', 10)]
```
