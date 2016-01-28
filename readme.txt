EDDN Nuernberg, Germany
-----------------------
Copyright (C) 2007 Franknfly

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Please consider donating to x-plane.org
---------------------------------------
"Those who are regulars to x-plane.org will be aware of the fact that financing
 the site is an unresolved issue. To help somewhat towards meeting the growing 
 cost of maintaining the site, I've decided to offer this scenery as 
 donationware. If you like the scenery, please consider a donation to 
 x-plane.org. You can do so at the x-plane.org store at 
 http://store.x-plane.org/."


Converted from x-plane to FlightGear by radi with kind permission
using the xplane2fg and fgopt packages

http://wiki.flightgear.org/Howto:_Convert_objects_from_X-Plane
http://www.flightgear.org/forums/viewtopic.php?f=5&t=10625

- replaced static aircraft and service vehicles with FlightGear's static aircraft


Installation
------------
just copy to folder Objects in data/Scenery
and copy folder Airports in data/Scenery


TODO
----
- some more service vehicles (vans, cars)
- better lights
- maybe replace trees with shared models

Conversation with Franknfly, original author of EDDN for X-Plane
----------------------------------------------------------------
Sent 14 April 2011 - 02:39 PM
Hi Franknfly,

I found your awesome EDDN scenery on x-plane.org, and kindly ask you if you
would consider donating the scenery (or parts thereof) to the FlightGear
community.

FlightGear is a free and open source flight simulator licensed under the terms
of the GNU Public License (GPL), see www.flightgear.org. I enjoy it a lot,
and started developing some scenery tools for it. Recently I implemented an
automatic way of converting X-Plane scenery to FlightGear's file format.
(http://wiki.flightge...ts_from_X-Plane)

Your EDDN 1.1 (2007, downloaded somewhen last year) scenery served as a test case, and turned out great in my local copy of FlightGear. (I only found out just now that you have released another version in February...)

I for one, and certainly the FlightGear community too, would be very grateful
if you would consider releasing the converted scenery (whichever version) or parts thereof under the terms of the GPL. This would allow us to include it in the official
FlightGear scenery. Of course I would (have to) exclude objects that you
don't hold a copyright of (probably those mentioned under "4. Credits" in the
readme file?). And of course we would acknowledge you as the original author.

In case you're not familiar with the GPL: In short, it allows derivative works
(including commercial use), as long as the source code remains free of
charge, and the derivative work itself is again distributed as GPL'd
software. This ensures nobody takes unreasonable profit from other people's
efforts, and the source code remains accessable for everyone.

Should you disagree with any of the GPL terms, I would like to ask if you want
to suggest any other license for distribution.

Thank you very much for your scenery work and for taking the time to read
this.

Best regards,

Thomas Albrecht

PS. Considering your email address, chances are that we're both native German
speakers. If so, you may of course also answer in German ;)

---
Sent 20 April 2011 - 12:38 PM
Hallo Thomas,

Du kannst EDDN gerne für FlightGear konvertieren. GPL ist ok. Alle Gebäudeobjekte stammen von mir. Von Dritten übernommen sind Servicefahrzeung und statische Flugzeuge. Die bitte entfernen/ersetzen.

Beste Grüße,
Mike

---
Sent 26 April 2011 - 03:27 PM

Hey Mike,

super, vielen Dank! Servicefahrzeuge und statische Flugzeuge werde ich ersetzen.

Wie gesagt war mir, bis ich Dir die Mail schrieb, gar nicht bewusst, dass es auch EDDN 2.0 geben würde. Ohne diese Version je gesehen zu haben -- dürfte ich auch v2.0 konvertieren und bei Erfolg als GPL ins zentrale FlightGear-Repository stellen?

Auf jeden Fall ist "selbst" EDDN 1.1 eine Augenweide und wäre eine große Bereicherung für FlightGear.

Viele Grüße,
Tom

---
Sent 29 April 2011 - 10:21 AM

Ja, klar. Schick mir bei Gelegenheit mal nen Screenshot von EDDN in FG.

Beste Grüße,
Mike


---- content of original readme.txt (from the x-plane package) follows ----
Project EDDN 
**********************************************
Release 2.0 for X-Plane (V 8.50 and higher) - new features
**********************************************

1. Docks
Docks at Gates 09, 11 and 13 are animated now. As pointed out in the instructions for Release 1.0 below, you will need Marginal's autogate plugin. ACFs need to have the door location indicated in the STANDARD>VIEWPOINT screen in Plane Maker.

2. Forests
Sorry, no options anymore. I've gotten rid of the forest facade, which never looked good from the air, and put some forest to the north and east of the airport to give you the right feel while taxiing and cover the faulty default city textures to the north and east of EDDN. If you want more extensive forests, use AlPilotX's European Forest Scenery available at X-plane.org.

3. Static scenery
EDDN 2.0 contains more planes than previous versions and also ground service vehicles. X-OpenScenery is required for EDDN 2.0 to work. Get it at X-plane.org. Ground vehicles are largely adapted from Beber's Airport collection 1.0. I've also added the fuel depot at the western end of the runway.


**********************************************
Release 1.1 for X-Plane (V 8.60) - new features
**********************************************
- airport in 8.50 format (nicely curved taxiways, a full set of taxilines and lighting, taxi signs). Thanks to Marginal for developing APT2BGL;
- northern parking lots with cars (from x-plane library) and street lights added;
- roads and characteristic roundabout added;
- forest border fine tuned to fit CORINE data better;
- LOD set to a more generous setting to make airport appear sooner with default distance settings in the rendering menue.

***********************************************
Release 1.0 for X-Plane (V 8.60)
***********************************************
1. How to install
This scenery has been tested with X-plane 8.60. It should also run with 8.50 (but not 8.40 and below because the package contains named lights). To install, just move the folder "d_eddn_overlay" to "custom scenery" in your x-plane directory.

2. Docks
The docks at the main terminal are equipped with DGSs. To make these functional you will need to download and install Marginal's autogate plugin. You can get it at http://marginal.org.uk/x-planescenery/index.html. Read the instructions there for how to use it. Gates 9, 11 and 13 serve different size planes; they have been optimised for the AVRO RJ70 (http://xplane.andreasbenjamin.com/index.php), B737-800 (http://x-plane.benedikt-stratmann.de) and A340-600 repectively. The docks themselves are static and in docked position, which means that you will "scrape along" the docks when parking. Once you are in the parking position indicated by the DGS, you plane should be reasonably docked.

2. Forests
One of the characteristics of EDDN is the fact that it is surrounded by forest, the "Nuernberger Reichswald", to the north and east. These forests are part of this scenery. If for some reason you don't want forests, there are two options: either you can get rid of them completely or you can keep a two-dimensional "tree margin", which will give you the impression of forests when taxiing but will look a little strange once you are airborne especially since the ground texture to the north and east of EDDN shows buildings rather than forest. Here is how to change your forest settings:
- in your Custom Scenery folder go to d_eddn_overlay\Earth nav data\+40+010
- delete the file +49+011.dsf
- make a copy of the option you want ("full forest" is the default)
- rename the copied file to +49+011.dsf
- Start the sim and fly.

Hint: You can try different options with the sim running. Just follow the above steps. Then go to the rendering options menue in X-plane and change the option for forest density or number of roads or number of objects. When hitting the return key, the sim will reload the dsf-files currently in use.

3. This is Donationware
Those who are regulars to x-plane.org will be aware of the fact that financing the site is an unresolved issue. To help somewhat towards meeting the growing cost of maintaining the site, I've decided to offer this scenery as donationware. If you like the scenery, please consider a donation to x-plane.org. You can do so at the x-plane.org store at http://store.x-plane.org/.

4. Credits
Static aircraft are courtesy of Jochen Haink.
DGS equipment is courtesy of Jonathan Harris
Fence and tree textures are courtesy of Austin Meyer

5. Contact
In case of questions, problems, etc. you can contact me at franknfly@web.de.

(c) by Franknfly 2007
