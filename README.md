# Z-Wave-Smart-Home-Maker-Challenge
Project involving: Raspberry Pi 3 as developmental environment for Z/IP Gateway and the Z-Ware middleware.

Rough questions:
Z-wave certified products fall under: all controllers, computer controller interfaces, energy meters, fan control, handheld controller, HVAC, Installer Tools, Locks, Network Devices, Security Add-Ons, Sensors, Water & Irrigation, All Lighting Devices, Dimming Lighting Devices, Entertainment Controller, Gateway Controller, Hospitality, Infrared Devices, Lighting Accessories, Motor Control, On/Off Switches/Devices, Security Systems, Thermostats, and Window Covering.

Signifying, what are the chances that this can reliably become accessible? How common are they?
Sensors for example can last up to 2 years on included battery, but require Z-wave remote or supported Z-wave hub.

Another concern: reading battery voltage through battery/battery holder -will the requests drain the battery? If off, it can turn on -but will most likely turn off again to preserve battery. A long delay from sending a request, recieving response, waiting for it to turn back on may be frustrating for the end user or not expedient.

check: http://forum.z-wavepublic.com/t/zip-gateway-and-a-couple-of-nodes-waking-up-but-not-working-correctly/169
note: individual wants to check battery, struggles -finds best way to send wake up notification is by disabling the mailbox treating it as a read only.

2 Distributors available Global/US for Z-Wave Development Kit or Module. Only promise they give for the lengthy certification process is getting 70% of the market share in smart homes. Is it worth it? Staples has pulled out. Lowe's/Amazon haven't. Other big name active is GE.

Theoretically, you can locate an item through intermediary nodes. Question is how to designate nodes for end user to orient where moved object has gone?

Goal: Send email/notification that battery has been disconnected from charger or is low on charge.
