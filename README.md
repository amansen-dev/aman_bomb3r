# aman-Bomb3r

Made with Love in IN By Aman

## For Windows 10/8.x/7

> Use windows [releases](https://github.com/amansen-dev/aman_bomb3r/releases) (windows release is not up-to date)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/installing/) to install bomb3r.

```bash
git clone https://github.com/amansen-dev/aman_Bomb3r.git
cd aman_Bomb3r
pip3 install -r requirements.txt
```

## Usage

```bash
python3 bomber.py <TARGET>
```

where TARGET is target mobile number.

## Options

```
usage: bomber.py [-h] [--sms SMS] [--threads THREADS] TARGET

positional arguments:
  TARGET                    Target mobile number without country code (default:+91)

optional arguments:
  -h, --help                show this help message and exit
  --sms SMS, -S SMS         Number of sms to target (default: 10)
  --country COUNTRY, -c COUNTRY
                        Country code without (+) sign (default: 91)
  --threads THREADS, -T THREADS
                            Number of threads (default: 10)
  --proxy, -p           Use proxy for bombing (It is advisable to use this
                          option if you are bombing more than 50 sms)
  --verbose, -v         Verbose
  --verify, -V          To verify all providers are working or not
```

## Changelog

```
    -- Mar, 2020
      - added more configs
      - fixed some bugs
      
    -- Nov, 2019
      - multiple country option
      - more api for india
      - proxy feature to avoid ip blocking
      - new verbose and verify option
```

## License

This project is licensed under the [GNU General Public License v3.0](https://github.com/amansen-dev/aman-Bomb3r/blob/master/LICENSE

