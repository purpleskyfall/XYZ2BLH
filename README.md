# XYZ2BLH

Convert cartesian coordinate system to geodetic system, or vice versa.

This project contains two scripts:

- blh2xyz.py: convert geodetic coordinate system to cartesian system,
- xyz2blh.py: convert cartesian coordinate system to geodetic system.
- xyz2neu.py: convert cartesian coordinate system to topocentric system.

## Usage

### blh2xyz

Run command by:

```sh
$ python blh2xyz.py -lat latitude -lon longitude -hgt height
```

or type:

```sh
$ python blh2xyz.py -h
```

for usage infomation.

### xyz2blh

Run command by:

```sh
$ python xyz2blh.py -x val -y val -z val
```

or type:

```sh
$ python xyz2blh.py -h
```

for usage infomation.

### xyz2neu

Run command by:

```sh
$ python xyz2neu.py -x0 <x0> -y0 <y0> -z0 <z0> -x val -y val -z val
```

or type:

```sh
$ python xyz2neu.py -h
```

for usage infomation.

## License

Released under MIT, see LICENSE for more details.
