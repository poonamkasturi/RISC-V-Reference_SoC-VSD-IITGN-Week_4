# RISC-V-Reference_SoC-VSD-IITGN-Week_4
 CMOS Circuit Design (sky130-style) 

Download collatorals from
https://github.com/kunalg123/sky130CircuitDesignWorkshop/

installation steps that worked for ngspice with graphics viewer enabled

```
sudo apt-get update
sudo apt-get install build-essential libx11-dev libxaw7-dev libxt-dev libreadline-dev
```
---
```
git clone https://git.code.sf.net/p/ngspice/ngspice
cd ngspice
./autogen.sh
mkdir release
cd release
../configure --with-x --enable-xspice
make -j$(nproc)
sudo make install
```
---

This ensures:
- --with-x enables X11 graphics
- --enable-xspice adds extended simulation support
---




