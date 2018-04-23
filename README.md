# Tegra-X1-Bootrom
it is a Tsgra X1 bootrom leaked by @q3k
And because hacking is easy; the Tegra X1 Bug.

Tegra X1 RCM forgets to limit wLength field of 8 byte long Setup Packet in some USB control transfers. Standard Endpoint Request GET_STATUS (0x00) can be used to do arbitrary memcpy from malicious RCM command and smash the Boot ROM stack before signature checks and after Boot ROM sends UID. Need USB connection and way to enter RCM (Switch needs volume up press and JoyCon pin shorted).

To:

ReSwitched

fail0verflow

SwitchBrew

BBB

Team Xecuter

Team SALT

Reminder: Real hackers hack in silence. You all suck.

"Game Over."

F8001BE1190CAED74BBDDAD78667877C84D1A128
