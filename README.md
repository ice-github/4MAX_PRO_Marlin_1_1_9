# Anycubic 4Max Pro Marlin 1.1.9 by davidramiro and alfrank, na0ki

https://drucktipps3d.de/forum/topic/anycubic-4max-pro-marlin-1-1-9-firmware-ai3m-basierend/?fbclid=IwAR2NWjZ8RARm2QpHTSNuO7hDn6Lr9Tce17_3R0D_kxf1R3-p1S5AHzcp0_I

## Before installing custom firmware
- Save your config on EEPROM just in case
- M503

## How to install
- Use Arduino IDE

## How to use BL-touch/3D-touch

### Check your motherboard version

### Is GUI calibration available?

### Calibration

## How to use Auto Poweroff
- To avoid damaging Hotend, must use M109 becore M81  
- M109 R80 //Cooling Hotend to 80c and wait for
- M81 //power off

## How to change Light brightness
- M355 S1 P128 //half brightness power

## FAQ

## License

Marlin is published under the [GPLv3 license](https://github.com/MarlinFirmware/Marlin/blob/1.0.x/COPYING.md) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

## Disclaimer

```
/*
* Flashing a custom firmware happens at your own risk.
*
* THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS
* AND CONTRIBUTORS “AS IS” AND ANY EXPRESS OR IMPLIED
* WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
* WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
* PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL
* THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
* ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
* CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
* PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS
* OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
* HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER
* IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE
* OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
* SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
*/
```
