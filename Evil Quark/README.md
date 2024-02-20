Evil quark
=

I don't wanna waste my server resources if things can be done at client side.

### Connection: https://evil-quark.ctf.teamquark.com/

### Note: wrap up your flag in quarkCTF{}

### Author: Harsh Patil


## Solution

Used the image given in the challenge to extract the flag.

```bash
$ exiftool bBQ36nHtgEkYbmLC66T6h5Ar.png
```

The flag is base64 encoded in title section of the exifdata.

`quarkCTF{mu5t_d35tr0y_3v1l_qu4rk}`
