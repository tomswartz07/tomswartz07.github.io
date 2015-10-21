---
layout: post
title: Quadcopter Parts List, or, "How to pick your parts"
keywords: multicopter, drone, quadcopter build, quadcopter, parts
---

I recently gave a talk at [TechLancaster](http://techlancaster.com) regarding
the news, controversies, and science behind quadcopters and RC models in general.

The most common question was, "What parts should I get?" The hobby can be very
daunting at first, believe me, and it's easy to get overwhelmed by all of the
possibilities.

I've decided the easiest way to help answer this question is to do a small writeup
on what to look for when purchasing parts for a quadcopter.

> So, let's get started!

The following components are available practically everywhere. So I won't go
into detail into each component, just offer general specifications. I'd
recommend purchasing your entire/the bulk of your order from Hobbyking,
MyRCMart, Ebay, or Amazon. All carry most to all of the components.

If you're ordering from HobbyKing, be sure to check the US East warehouse.
If you order from their international or US West warehouse, it will take
upwards of 3 weeks for the order to arrive.

I have general info here, but I'll list exactly the part I got.
I purchased many of my parts from Amazon because my credit card gave me 'points'
towards purchases. I figured I simply couldn't pass up a chance for a 'free' quadcopter!


#### $20 Frame

The frame is one of the key parts of your build. It determines it's flight
character, as well as how cool it looks. Obviously, the cool factor is the most
important part of your build.

Pretty much any 330-500mm frame should work. Pick any one you like. The 450
size ones have standard arms, so finding replacements is easy. Searching "450
frame" or "HJ 450 frame" should offer plenty of results (especially on
eBay). Don't worry about quality, they are all pretty much identical. There
are lots of variants out there, like the "Reptile" (TBS discovery clones) that
are nice for FPV.

I prefer frames that have a built-in *power distribution board*, meaning;
the frame has a circuit board built in, cutting down on the clutter and wiring
mess.

I got: [Generic F450 frame](http://www.amazon.com/gp/product/B00I0OO1V2?psc=1&redirect=true&ref_=oh_aui_detailpage_o00_s00)


#### $20 Flight Controller

Get the KK2.1 or the KK Hardcase (with programmer). Both are great controllers.
There are other options available, with more features, like the Naza/Lite and
the APM, but the KK is a great starting point. It has an easy to read screen and
settings can be easily adjusted with the 4 interface buttons.

The great thing about building your own quadcopter is that you can easily upgrade
parts later. If you start with a basic KK2.1 controller and find that you're getting
so awesome at flying, and you need **MOAR POWA**, you can easily swap in a new FC.

I got: [KK2.1.5 with plastic case](http://www.amazon.com/gp/product/B00Q2KJXBY?psc=1&redirect=true&ref_=oh_aui_detailpage_o09_s00)


#### $50 Motors / Propellers

2212 (or 2214/5/6) motors at 900-1000kv are perfect for this build. You might be
able to stretch to 800-1200kv, but that is not optimal.

There are lots of options here, so pick what you like, you can't go wrong.
One of the best options are the threaded "phantom replacement motors" like
the LDPower 2212 and MarsPower 2212 that are available on Ebay.
Hobbyking stocks similar Multistar 2212 motors.

If you are using these motors, you'll want 1045 or 9443 "DJI-style" props
with a keyed hub. (5-6 pairs, a set comes with 2 pairs) This makes it harder
for the props to come off mid flight. Another option for threaded motors are
the "self tightening phantom props". If you would like to go with standard
motors, the NTM, Sunnysky, or Emax motors are good bets (these are $16 a piece).

Some manufacturers use a different system to name their motors, so you'll
have to search by the motors external diameter (so search 2826 instead of 2212,
Turnigy/RCX 2826 would be comparable to a Sunnysky 2212). You'll have to pick
up prop adapters sized to your motors' shaft size as well (usually 3 or
3.5mm)

Pick up a few sets (maybe 5-6 pairs) of standard CW/CCW 1045 prop to go
with these. As you're testing things out, you'll be breaking a lot of props.
Don't worry, you can get them in bulk for super cheap.

If you'd prefer a plug/play build, make sure the motors have bullet connectors.
Otherwise get ready to fire up your soldering iron. :)

I got: [Marspower 2212 motors at 1000KV](http://www.amazon.com/gp/product/B00S12CRNM?psc=1&redirect=true&ref_=oh_aui_detailpage_o01_s00)


#### $50 ESCs

The only things to look for in ESCs are SimonK, 3S, and 20A (and a 5v BEC, not
OPTO). Your ESCs have to be SimonK or BLHeli, support 3S, and be at least 20A (30
amps works too, but any more is overkill).

All the listed specs are necessary for decent performance.
ESCs like this are available on eBay "20A SimonK ESC", and I particularly
like the EMAX ones. Hobbyking's Afro 20 and 30A are nice (pre-installed
bullet connectors), and MyRCMart's RCX 20A SimonK ones are pretty good too.

Just make sure that your ESCs have a built in 5V BEC, not OPTO - this is
necessary to provide power to the FC, and without it, you'll
need and external 3A 5V Battery Elimination Circuit.

Just the same as the motors, make sure they have bullet connectors, or be ready to solder.

I got: [Mr. RC 30A ESCs with SimonK Firmware](http://www.amazon.com/gp/product/B00S12CRNM?psc=1&redirect=true&ref_=oh_aui_detailpage_o01_s00) (they came with the motors)

#### $60 Batteries

There are a few things to keep in mind: the 'S' and 'C' values.

The 'S' value indicates how many cells in *S*eries are in the pack. Each cell is
3.7 Volts. The more you have in series, the higher the voltage. A 3S battery will
have 3x3.7 Volts, meaning it's a 12 Volt pack.

The C value indicates how fast it can drain the battery, it's *C*apacitence.
This C value is multiplied by the storage value to give you a usable number.
As an example: a 20C battery with 2000mAh can output 20(C)x2(Amps)=40 peak Amps.

Batteries for your 450 will vary in size. Generally 3S 2200mAh-4000mAh 25C are
a good bet for these quads. Increasing the C rating past 30C will have little
effect on performance.

Remember that the heavier the quad, the more sluggish it will be while flying.
This can be great for aerial video, where quick jumpy movements are not desireable.

2200mah is great for light flying (about 10 mins).
You'll want a 4000mah for longer flight times (around 20 mins).

Adding on equipment like cameras/FPV stuff/gimbals will drop your flight time by 5-10
mins. Every ounce of weight counts!

Also remember to pick up a LiPo low voltage alarm. These are great for
checking the voltage of your packs and alert you when to land.

Buy at least 3 batteries, each should be around $15-$30 or so.

I got: [Turnigy 2200mAh 3S 30C](http://www.amazon.com/gp/product/B00T9JQZEI?psc=1&redirect=true&ref_=oh_aui_detailpage_o07_s00)
A great little battery checker can be had for about [$6 on Amazon](http://www.amazon.com/gp/product/B003Y6E6IE?psc=1&redirect=true&ref_=oh_aui_detailpage_o09_s00)


#### $30 Charger (remember to get a power supply too if it doesn't come with one!)

The Turnigy Accucel-6 is a great beginner charger.

The Imax B6AC is another nice charger.
The B6AC is commonly cloned, so watch out for prices under $20 if you
don't want a fake one. Most people don't have a problem with cloned equipment,
but I'd rather spend $10 more and make sure that the charger (which could destroy
and burn your lipos) is working properly.

Another option is a Hitec X4 Eighty DC, a great device if you can spend a
little more cash- it charges 4 of my batteries at once, and usually within 15 minutes.

HobbyKing also sells several similar chargers under the name "Quattro"

I got: [IMax B6AC](https://www.hobbyking.com/hobbyking/store/uh_viewItem.asp?idProduct=76462)


#### $50 Transmitter

The important thing to know about transmitters are the types of 'Modes'; the two
most common are Mode 1 and Mode 2. These Modes dictate which stick is throttle
and which is pitch/roll. The most common setup is Mode 2, with the throttle stick
on the left, and pitch/roll controls on the right stick.

The Turnigy 9X is a great starter model. It has 9 channels so there's plenty of
room to expand and grow.

Get the Orange T-6 or the DX6i if you can find them.
The T-6 is available on Hobbyking, and the DX6i can be found used
on Ebay or RCGroups for around $70.

Spektrum is also cheap, inexpensive, and very reliable.

6 channels is more than sufficient for any beginner and even experts rarely
use more than 2 three positions switches in addition to the 4 gimbal channels.

Other options include the Turnigy 9x/r and 9xrPro.
These are awesome radios, and have open-source documentation on them, but you
might need to purchase and additional Turnigy/FrSky/Spektrum module.

The Taranis radio is regarded by most as the best multirotor radio, but it's
got too many switches and knobs for me. It is a wonderful radio for those
who have the time to understand it, but it has lots of options, and personally,
I'm afraid I'll make a mistake and screw something up.

The new Spektrum DX6 is also a really attractive radio at its price point. The
Taranis, 9XR Pro, DX8, and DX6 all have telemetry, and also (excepting the DX8)
have voice alerts.

I got: [Turnigy 9X Mode 2](https://www.hobbyking.com/hobbyking/store/__19673__Turnigy_9X_9Ch_Transmitter_w_Module_8ch_Receiver_Mode_2_v2_Firmware_US_Warehouse_.html)

#### $7 Receiver

6 channel LemonRXs and the Orange RXs are both awesome park-fly RXs that are light,
durable, and well-tested by the community.

The Turnigy 9X comes with a receiver, so you can omit this if it comes in a kit.

Receivers are cheap enough ($8) that it probably wouldn't hurt to have an extra one handy.
Doing so allows you to experiment with other parts and servos and geeky things
without having to take apart your current device.

## ++ Extras ++

You might need a 3.5mm power distribution board/squid to hook up the ESCs.
Check if the HJ/F450 frame has power distribution built in. If it does,
then you're golden.

Grab some [male-to-male servo cables](https://www.hobbyking.com/hobbyking/store/__67066__HobbyKing_Super_Clean_RC_Male_to_Male_Extension_set_100mm_AR_Warehouse_.html) to connect your RX to your FC.
You'll need about 10 to 15 individual cables.

Pick up some zipties, velcro, and tape.

300mm battery straps are great to keep your battery from flying away.

Get at least 20 pairs of 3.5mm bullet connectors if your ESCs/Motors don't
have them built in. The Bullet Connectors aren't necessary and add weight, but
they're nice for troubleshooting the motors.
I prefer to solder my connections directly to save weight, but bullet connectors
make it easy to swap parts in and out.

Maybe some landing gear if you plan on expanding to aerial video or if you just
don't like your quad lying in the grass.

You might need some 3mm nylon standoffs/hardware to mount your FC. Or you can
use velcro :)

Lipo Alarm to alert you to a low voltage on your battery The KK2.1 has a built
in alarm, but a cheap one is handy for checking many batteries at once.


## ++ OPTIONAL ++

#### $100-$200 FPV Setup

For those looking for a brand-name FPV setup, the Predator V2 system is great,
you should be able to catch a Predator V2 Fatshark system for around $200 on the
RCG classifieds. For those who don't mind fiddling a little bit, Hobbyking has
their Quanum FPV set, which is around $100, which is awesome as well. Goggles
vs Monitor is a huge debate that will probably never end. Goggles are best for
immersive experiences, while monitors are best if you like the added safety of
being able to maintain Line Of Sight of your craft. Goggles are far easier to see,
while visibility in monitors can be improved by adding a sunshade.

I purchased a cheap 900MHz kit from HobbyKing. At the time, it was only $50; but
it seems to have become a bit more expensive recently.
Whatever kit you get, make sure that it's a different frequency than your transmitter.

I got: [Generic 900MHz Tx/Rx Kit](https://www.hobbyking.com/hobbyking/store/__21327__900MHZ_200mW_Tx_Rx_1_3_inch_CCD_Camera_NTSC_520TVL.html)


#### $100-$200 Aerial Video Stabilization

Gimbals help stabilize your video by keeping the camera level in relation to the
ground.

There are two types of gimbals.
The first kind are "two axis"; which compensate for the pitch and roll of your copter.
Three Axis gimbals are slightly more expensive, but also compensate for yaw, or the turning of your
copter.

Most gimbals can make use of the 5th/6th channels on your transmitter to move the
camera manually.

Make sure to pick up some landing gear if you plan to
mount your gimbal beneath your quad.

A good bet is the Tarot Go-Pro Gimbal. Hobbyking also sells several variations.

No-brand gimbals on Ebay are inexpensive (around $20), but are sometimes known
to be quite fiddly. It can be a gamble.


#### $100 Camera

Lots of options here. Pick something with decent resolution and color
reproduction.
There are some very nice knockoff GoPro clones, some as cheap as $30.
If you want to record video as well as transmit FPV, a great device is
a Mobius camera.


## Wrap up

All in all, that's all you need to get rolling with a multicopter.

I hope you've found this guide to be helpful!
