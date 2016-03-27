on OSX:

nvram -p:

lazarus:~ fredbloggs$ nvram -p
nvramrc	
scroll-lock	true
boot-command	mac-boot
pci-probe-mask	-1
skip-netboot?	false
diag-device	enet
boot-screen	screen
default-subnet-mask	
boot-device	sata/k2-sata@0/@0:3,\\:tbxi
real-size	-1
logger-size	-1
auto-boot?	true
default-gateway-ip	
use-generic?	false
boot-volume	3
screen-#rows	40
selftest-#megs	0
default-mac-address?	false
logger-base	-1
little-endian?	false
ram-size	0x10000000
EFIBluetoothDelay	%0b%b8
boot-file	
default-server-ip	
output-device	screen
virt-base	-1
boot-script	
boot-last-label	Linux
use-nvramrc?	false
prev-lang:kbd	en:15
screen-#columns	100
input-device	keyboard
real-base	-1
mouse-device	mouse
oem-banner?	false
oem-banner	
fcode-debug?	false
default-router-ip	
real-mode?	false
aapl,tdm-units	
console-screen	screen
default-client-ip	
virt-size	-1
diag-file	,diags
oem-logo	
load-base	0x800000
output-device-1	/ipc
platform-uuid	%00%00%00%00%00%00%10%00%80%00%00%11$%e5%ee%d2
diag-switch?	false
gmt-offset	0
boot-once	
input-device-1	/ipc
boot-args	
oem-logo?	false

-----

boot device for on-disk OSX: sata/k2-sata@0/@0:3,\\:tbxi

