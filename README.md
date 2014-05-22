Instructions
=====================

1: Application Preview
=========================

The project is an application on smartphones(android OS requiered)to help blind people race using boats.
1.1: Application Goasls:

*Easy and servicable register and login shell
*Show current boats place, velosity and gps coordinates live.
*Let the admin put more matzofim before starting the race, and they must appear on his screen during the race.
*Must produce KML file containing the path only or the set of matzofim the racers reached.

The application constructed with two elements in mind, the administrator and the user.
Administrator job is to setup the race prestart by opening an event for the players to login into and to make sure every player is in the correct event
while the user job is to actually log in the application using the given event the administrator set up.

1.2: Important Notes:

The application requires constant connectivity to the internet(via ISP or wireless) and the GPS must be turned on.
each player must register using unique ID and password and his given event number (by the administrator).
a player can be only be assigned to one event using specific id.


2: Preparation Stage:
========================

2.1: General Information:

First of all please check that the GPS and Internet are turned on and stable at all time.
Event number: a unique number to diffrinciate between racing. it means that a player can have event number 233 and another racer can have event number 124. they both wil be in different race than each other.
for them to be in the same race they must both be with the same event number.


2.2: For the Admin:

The admin needs to create an event by login to Admin mode using these settings.
user: Admin
password: Admin
event: 111

where event number is of your choosing. for the sake of simplicity I chose 111, but it can be any number.
Also he has to place predetermined matzofim on the map, only the admin can put matzofim on the map(up to 10), the players aren't be able to.


2.3: For the Player:

The player need to register using a name, password(need to be >=6 numbers) and event number that was given by the admin.
if you leave after registering you can always log in again using your registered information you filled in during registration.


3: Racing Example
=====================
After the application was installed on the racers and admin phones, and it was verified that the internet and GPS are both turned on.

The Admin starts by creating an instance. He has to enter his Application using Admin mode and putting matzofim on the map.

The players register on their own phones using the event number the Admin gave them those entering his instance.

The racers start rowing their boats and race to the nearest matzof when their boat radius reach the matzof radius a beep will be sound for them to be aware of their arrival to the matof, continuing on, they keeping up following the race trail to the next matzof untill all the matzofim are reached and than the race is over.

All the info of each player race trail, matzofim reached, their time and date are kept on a kml file that the Application generate in a click of a button. which can be easily opened and view via google earth program or site.



