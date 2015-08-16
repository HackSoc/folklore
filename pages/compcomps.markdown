---
title: Computing Science Computing History
related:
- compserv
- computing
- compsci
- vuft
---

(Mainly by [Pete Fenelon][])

Initially obtained PDP-11s for research, later acquired VAXes. Student
users moved off Computing Service machine for academic year 1986-7.

State of the art in 86-7:

minster
~ Vax 11/780 for STRC (software tech. research centre)
~ main mail gateway.

novice
~ staff Vax 11/780

abbot
~ MSc in IP Vax 11/750

bishop
~ Undergraduate VAX 11/750

exarch
~ Undergraduate (lab) HLH Orion

funstar
~ Functional Programming Group HLH Orion

deacon
~ research PDP-11/34

bodicca
~ research GEC 63/30

canon
~ Research Vax

farmer
~ Research Vax

prior
~ Research Vax

johann
~ Student Sun 3/160 fileserver

A number of client suns originally named after J S Bach's kids

SoftEng Staff Sun 3/280 fileserver

A number of client Suns with various names.

Most staff had terminals (Visual 200 or VT100, though some had Atari
520STs on which there'd been an attempt to port Pike's Blit/layers
software and others had various micros).

Undergraduate terminals were 20 Visual 200s (VT52 clones) in V/044,
plus an assortment of elderly devices in the labs. MSc students used
BBC Micros with a temrinal emulator eprom in X/A block.

Exarch became funstar in 1987-88, bishop became the lab machine,
minster became the main u/g Vax whilst remaining the dep't mail and
news gateway.

For AY1987-88 the U/G terminals moved to V/058 and increased in number
to 28.

Student usernames were of the form PeterF, IanR, etc. Potential
clashes were solved by subsequent arrivals having more of their
surnames left in. Electronics students used to initially be taught
Pascal by Comp Sci, but used "reversed" usernames: PFrench IPayton,
etc.)

There was an amusing confusion early in my first term when I saw Pete
French trying to log in as PeterF instead of PFrench.... :)

Staff usernames were the usual mixture of initials, forenames,
surnames, nicknames and whatever else people wanted.

The staff meanwhile moved onto a network of Sun-3 fileservers and
workstations. Servers were:

SoftEng
~ basically replaced minster

Perspex
~ initially used for ASPECT work

Numbers
~ originally for number-crunching and FP users

Terminal
~ Timesharing for terminal users

Software
~ mixture of file service and terminal usage.

Workstations were numbered systematically-ish as sunNN or sunNNN.

To this were later added the imaginatively-named

Server6
~
Server7
~ both of which were mainly used by the realtime and high integrity
  groups.

A Torch TripleX was used as an X.25 gateway on the staff side.

For AY1988-9 the Vax maintenance contract became too expensive to
justify keeping the students on them, so two shiny new HLH Orions were
purchased, imaginatively named Orion1 (undergrad) and Orion2
(MSc).These ran a 4.2-alike Unix and were based around the Fairchild
Clipper. The Visual 200s were replaced by DEC VT220s and migrated to
the labs.

Student usernames changed to initials suffixed by a hyphen and letters
starting at a for the first student to arrive with a particular
set... e.g. pf-a, pf-b, etc.

HLH rapidly lost interest in building and supporting computers and
became an Apple dealer. The Orions were incredibly buggy, though fast
for their time.

Before the next major round of purchases, there was the Great
Renumbering when all the machines were given addresses in York's Class
B -- previously, they'd used arbitrary IP addresses.

The next major round of purchases in the early 90s saw the arrival of
the "BM" concept. This was aimed at replacing all character terminals
in the Department with bitmapped screens; however, Sun or similar
equipment was perceived as being too expensive. Hence, inspired by the
ideas of Plan9, it was decided to create a simple environment for
providing a diskless workstation with a bitmapped, windowed display
and local editing etc. talking to a more powerful "compute server" for
little more than the cost of a terminal.

A large number of 386/16s were purchased, with (for the time) a good
spec -- 4Mb of RAM, Tseng ET4000 video cards driving Interquad
non-interlaced monitors, NE2000 ethernet cards.

As compute/file servers, four IBM RS6000s were purchased after a
competition that also included DEC and Sun. These were:

Server1
~ general staff server

Dcs1
~ high-integrity group server

Student1
~ main student server

tinbox
~ realtime group "baby" mainly for number crunching

Orbit, the locally-produced operating system, included ideas from
Plan9 and later research versions of Unix.

It never really obtained a foothold with the staff.

A number of Sparcs had also appeared in the HCI and High Integrity groups.

With the adoption of JIPS, the Torch TripleX was no longer required
and a reshuffle of Sun servers took place, the upshot of which was
that Terminal was no more,. minster became a sun3 and johann became a
more powerful one. I forget which box went where.

During the early 90s, the Sun fileservers started to become less
reliable and some users began to demand local disk and a machine which
could at least boot itself -- combined with the arrival of more
powerful PCs a number of users began to buy high-spec x86 boxes; most
of the kit bought as "BMs" continued to be used either as fast
terminals or had windows and a number of TCP/IP installed on them.

The next major change in computer science was the replacement of
ageing and by now unreliable Sun-3 kit with SGI hardware in 1994. A
Challenge S fileserver and a large number of Indy workstations
replaced the Sun3 fileservers and workstations for most of the
department's staff. In the meantime, the High Integrity and Realtime
groups had largely gon down the route of Sparcs, Macs and high-spec
PCs. MSc students switched to a Novell Netware network for most of
their work.

Undergraduate usernames started to be brought into line with Computing
Service ones.

With the arrival of the SGIs the shape of the network started to
change. Previously, there had been a "backbone" linking the
fileservers together, with a separate "serving ether" for each
machine's diskless clients. With one main fileserver replacing many ,
the serving ethers became more geographically based. FDDI to the
Computing Service was installed, as was a very smart 3Com hub.

The HISE group by this point had its RS6000 plus two Sparc-10/51s, one
of which continues to host most of the department's WWW pages :)

Charles Forsyth's interest in Plan9 saw a plan9 network arrive, with
several important functions (dns, ftp, "official" www) moved over to
this, as well as general file/compute service for a number of
staff. The undergraduate PCs switched to plan9 from Orbit, though
could also connect to a Novell/Windows service. The U/G fileserver
Student1 was replaced by a Challenge/S (Atlas).

[Pete Fenelon]: pete.fenelon@info-com.com
