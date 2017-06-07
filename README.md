![Image](https://i.imgur.com/1h1ZaQp.png)
# 1 VAC Ban On Record

This happened on the 6/6/17 to AimTux, Inuria, Chods etc. Users. This fork of AimTux Fuzion changes the Injector from `gdb` (GNU Debugger) to Hotpatcher. Please keep in mind that I don't have experience with C(++) or CMake/Make. The code edited by me is most likely bad written and shouldn't be used as good example, but **if it works, it works**.

This version of Fuzion requires the `hotpatcher` dependency.  
You can install it on Arch with the following command:
```zsh
$ sudo pacman -S hotpatcher
```

The rest of downloading and installation is the same like the original AimTux Fuzion.  
  
This has been tested with a **brand new account** on a **VAC-secured official Casual server** and [the account](https://steamcommunity.com/profiles/76561198393440661/) **didn't receive a untrusted ban** (tested on Wed. 7/6/17; one day after the VAC wave).

# Important

Don't use the **uload, rload or update** scripts. The only script that has been updated to Hotpatcher was **load**. Every other script still contains `gdb` code, which will give you a VAC ban.  
  
Valve can detect hotpatcher as Injector. Please keep this in mind and don't make this repository to known, so that Valve won't fix it fast.
