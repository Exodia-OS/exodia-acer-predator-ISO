# exodia-predator-ISO
Predator (for Acer Predator Laptops) Edition source ISO

### before building download Exodia Music
```bash
git clone https://github.com/Exodia-OS/exodia-music.git

```
### copy Music dir to `exodia-predator/airootfs/etc/skel/`

### how to build 

~~~bash

mkdir {work,out} 

sudo ./makeExodiaISO -v -w work -o out exodia-predator 

~~~
