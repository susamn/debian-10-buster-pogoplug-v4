# debian-10-buster-pogoplug-v4

## Introduction
If you have an old Pogoplug v4 and want to install debian 10 on it, use this image.

## Usage

### Put them together
```
cat d10pv4-part-* > os.tgz
```

### Unzip
```
tar zxvf os.tgz
```

### Intall to an SD
Use an image writer to write the image onto a sd and intall in the Pogoplug

### Login information
After boot you can login with `root` user without password
```
ssh root@host
```
