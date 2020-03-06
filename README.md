# vanputer
A Rasperry Pi sensor collection for all you vanlifers :-)

I'm currently in the process of converting a Sprinter LWB into a home for my girlfriend and I for the next few years, and being a software developer I saw it as a chance to collect some real world data.

So while the van build is in progress I'd like to use this repo for my own notes and so I can share ideas with others.

My experience is 30 years of writing software from 6502 and z80 assembler to my current favourite NodeJS, and so that's the tool I'll be using.

I have zero experience with Raspberry Pi (and don't currently own one) and zero experience with Linux. But, I also have zero experience of turning an empty panel van into a home but I'm still doing that :-)

## What is it?
Imagine a little computer running in your van, using your mobile internet when it can (and frugally, and configurably) to phone home to your OWN or a provider's server, where all your data is stored and potentially shared with friends and family (perhaps not GPS, that needs to lag a week or so).

This little, low power, computer can do anything a desktop or laptop can (more or less) but in this instance all it will do is collect and log data, and provide you with a way to view that data.

So you'll browse to it's web site and you'll see all the data on whatever sensors you have set up.

It could do much much more but for me, for now, I just want the little data collector...and the fun project too for those long winter days spent in Morocco...

## What I'd like it to do
* If no Internet then store all data locally and sync when can
* If no Internet wait a predetermined time and then start scanning for available open networks, then use the VPN
* All data sent to server to be encrypted (how, if it's OS?)
* Log GPS and send home every n seconds - homebrew GPS tracker
* Daylight times
* sunshine times (can we differentiate between direct and shady?)
* rain
* Humidity outside, inside the van, inside the insulation
* Water usage
* Water temperature
* Time spent cooking (gas to stove)
* Time spent shower/washing up (gas to hot water heater)
* Air pressure
* Temperature outisde, inside the van, inside the insulaton
* Time fans were running
* Power generated throgh solar
* Van direction/orientaton
* Tilt and yaw (if that's right) of the van (for consideration in solar generation)
* Power generated through driving
* Power used for inverter (maybe an alarm if we detect no 240 usage but inverter on and everyone asleep or out) 
* Power used (for everything)
* Gas usage
* All kinds of alarms (bad gases)
* Could record various cameras
* Collision detection
* Anything we can get from the OBD2? (Yeah, I reckon so)
* Send text when panicking
* Things I can't imagine yet

## But whhhhhhhhhhhhhhyyyyyy?
I don't go near this stuff in my job and it looks like fun to me, it might look like just more typing like I do at work but it's not, it has elements of fun that I don't get with my day job (which is also a lot of fun)

Also, I'd like to disprove or prove some theories and a little device like this might help, or maybe not mine but someone else can take what I do and build on it and do truly wonderous things.

Questions like;
* What impact does vapour barrier have (Yup, it's going in my van)
* How much power does a 320w panel on the roof of a van generate and what are the variables
* How much power is really lost through an inverter
* How much power do two remote workers living in a van use?
* Same for gas?
* How long does a/this vanlifer linger in one place (3 days, or weeks?)
* What are the best places to linger? :-)
* How much diesel used to go how far

Hopefully, with what I'd like to do, we'll be able to answer those questions fairly easily because, with it being open for anyone to use or contribute to, we should see lots of different configurations of vans from lots of different people (Yes, I am an optimist).

I'm not planning to make money from this, it's just because I am curious and it seems like a fun project.

That's it, that's the sum of all my thoughts on it for now.

Thank you for reading, and please do get in touch if you have a similar project you think might be a better use of my time (I really don't wish to invent the wheel here) and if it fits I'm in!

Also, please let me know of any ideas you might have about how I might achieve this little project (esp. hardware).

:-)
