---
id: df55ow6mkzy3shjh4vm4l2y
title: Powering Down
desc: ''
updated: 1672697565046
created: 1672697341143
---
## Preparing Q-Exactive Orbitrap-MS for a power outage
(from an email from a Thermo-Fisher site engineer)
 
Customer’s routinely vent (shutdown/start back up) their QE’s to service them (the lab may want to perform customer maintenance, clean the S-Lens and Exit Lens while it’s being vented).
 
There is a procedure in the QE Operating manual for shutdown/startup and maintenance.
 
To power down:
 
1. Turn the green electronics service switch to Service position (this turns the power off internally to all circuits boards expect power to the vacuum system, turbos and vacuum pump)
2. Turn the white breaker switch down to the off position (this turns off the power to everything in the QE including vacuum system)
3. After 5 minutes you can turn off the nitrogen supply to the QE (this is because the QE uses the nitrogen supply to vent the system back to atmospheric pressure, if one had a nitrogen Dewar as the N2 supply then after venting a full N2 Dewar will empty out in about 24 hours I left on while it’s venting. If I recall the lab may have a N2 generator so it will keep generating while the QE is vented.
 
To power up:
 
1. Turn N2 gas supply back on.
2. Turn on the white breaker switch (this supplies power to the vacuum system, the Power LED on the front of QE should be lit green).
3. After 15 minutes turn the green electronics switch to Operating position (the PC should start connecting to the QE in a couple minutes, other LEDs on the front panel should be on)
4. Open the Tune program, go down to Vacuum to start a 12 hour overnight bake out. (The goal is to get the UHV vacuum below 5e-10 torr)

The company policy is for all customers to contact DRS which is our technical support group for all and any inquires (tech support, part numbers, schedule on-site service, etc.) at 800-532-4752