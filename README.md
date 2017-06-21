![Image](https://i.imgur.com/1h1ZaQp.png)
# 1 VAC Ban On Record

This happened on the 6/6/17 to AimTux, Inuria, Chods etc. users. This fork of AimTux-Fuzion changes the Injector from the GNU Debugger (which is _unconfirmed_ detected) to Hotpatcher (which is undetected at the time of writing this). Please keep in mind that I don't have experience with C(++) or CMake/Make. The code edited by me is most likely bad written and shouldn't be used as good example, but **it works**.

# Installation

### Dependencies

**Ubuntu / Debian-based**: `sudo apt-get install cmake g++ gdb git libsdl2-dev zlib1g-dev liblua5.3 libxdo-dev patchelf`
**Arch**: `sudo pacman -S base-devel cmake gdb git sdl2 lua xdotool patchelf`

##### Hotpatcher

**Ubuntu / Debian-based / everything Non-Arch**:

```bash
git clone --recursive https://github.com/vikasnkumar/hotpatch
cd hotpatch
cmake .
make
make test
sudo make install
```

**Arch**:
```zsh
yaourt -S hotpatch
```

### Installing

```bash
git clone --recursive https://github.com/Marc3842h/Fuzion-Hotpatcher
cd Fuzion-Hotpatcher
cmake .
make
# Open CS:GO #
./load
```
  
# Testing

This has been tested with a **brand new account** on both **VAC-secured official Casual & Matchmaking server(s)** and [the account](https://steamcommunity.com/profiles/76561198393440661/) **didn't receive a untrusted ban**. The account will atleast play 2 games per day with this fork, so if it gets banned, this fork is _detected_.

# Important

`uload` and `rload` have been disabled by my because I'm not sure how to unload/reload AimTux with HotPatcher. Just close CS:GO (and reopen it) to unload/reload.  
  
Hotpatcher can be detected like every other injector by VAC. **Please don't make this repository to known** and don't fork, copy or star it.
The expected detection time is ~1 month. **Don't submit this repository or forks of commits of this repository as Pull Request to Fuzion, AimTuxOfficial and bigger AimTux Forks.**.
Well, I can't stop you but its for your own sake of not getting detected.

# Other injectors

**I don't suggest buying other injectors** because:

1. You're buying a injector for a free cheat
2. Nobody knows if its really GDB that got detected
3. Your paid injector can also be detected at anytime

# Thanks to

* [Original AimTux](https://github.com/AimTuxOfficial/AimTux)
* [AimTux-Fuzion](https://github.com/LWSS/Fuzion)
* [Hotpatcher](https://github.com/vikasnkumar/hotpatch)
* [Gitter](https://gitter.im/AimTuxOfficial/Lobby)
