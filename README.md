# Energy-and-Solar

On this page I will describe our energy and solar setup.

## Leisure Battery
Our leisure battery is a 280Ah LiFePO4 from Bulltron and it is sitting under the drivers seat, where the original batteries have been.
</br>
</br>
<img width="400" alt="Battery" src="https://github.com/Naaf3/Energy-and-Solar/blob/main/pictures/Battery.jpg"/>

## Energy Metering
Close to the battery is the Victron SmartShunt 500A <a href="https://www.victronenergy.de/battery-monitors/smart-battery-shunt">(for more infos visit the Victron homepage)</a>.
</br>
</br>
<img width="400" alt="SmartShunt" src="https://github.com/Naaf3/Energy-and-Solar/blob/main/pictures/SmartShunt.jpg"/>

Q: Why do we need a SmartShunt, when the battery management system (BMS) also gives us information about the state of charge (SoC) of the leisure battery?
A: Because of the accuracy of this informations from the BMS and the SmartShunt talks to the Victron SmartSolar. Furthermore the SmartShunt also monitors the starter battery of the van.

## Starter Battery
The starter battery in modern vans is often not fully charged by the alternator. That's because of the fact that the automobil companies want or have to keep the vans inside the regulations for fuel efficency and exhaust levels. Combined with the fact, that everytime we open a door of our vans, some components of the cars system wake up, boot and for that need energy, the battery can drop down to a critical SoC. That means in our case, that parking the car for some weeks, the battery loses power and it is harder to start the engine. One winter we even couldn't start the engine anymore.

Our solution for that was to install the Standby Charger Pro from Votronic <a href="https://www.votronic.de/standby-charger/">(for more infos visit the Votronic homepage)</a>

The standby charger tops up the starter battery to a certain level and does not drain the leisure battery under a certain level. Since we installed the standby charger the start-stop-function worked again. It didn't work for the last couple of years, because the starter batterie's SoC was too low.

## Solar System
