# nagios_check_uptime
Ensure uptime is not too high.

## Compatability
Only tested on Ubuntu 14.04.
Most likely works with all Debian based systems.

## Install

```sh
git clone https://github.com/hyperized/nagio_check_uptime.git
cd check_uptime
chmod +x check_uptime
```

## Usage
```
./check_uptime -h
Usage: ./check_uptime -w <warning value in days> -c <critical value in days>
Example: ./check_uptime -w 30 -c 90
UPTIME CRITICAL: Uptime is 373 days | uptime=373;30;90;
```

## License
MIT
