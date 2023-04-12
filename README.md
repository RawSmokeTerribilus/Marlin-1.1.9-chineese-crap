# Marlin-1.1.9-chineese-crap
This is a Tunned Marlin for my old reprap 3D printer, based in ramps and prusa 2 alike, those machines are so generic that as far as you are using hot bed and ramps 1.4 it should work. However, it has been tunned for my specific setup.


Marlin 3D Printer Firmware


Marlin is the world's most popular open source firmware for Replicating Rapid Prototyper (RepRap) machines, commonly referred to as "3D printers." Marlin Firmware is highly efficient, running even on modest 16MHz embedded AVR processors. While Marlin 1.1 only supports ATmega AVR (Arduino, etc.) and AT90USB (Teensy++ 2.0), Marlin 2.0 also adds support for several ARM processors, including the SAM3X8E (Arduino Due), NXP LPC1768/LPC1769 ARM Cortex-M3 (Re-Arm, MKS SBASE, Smoothieboard), and ARM Cortex-M4 (Teensy 3.5/3.6, STM32F1/4/7).

A monumental amount of talent and effort goes into Marlin production, and thanks are due to many volunteers around the world. We work closely with the community, contributors, vendors, host and library developers, etc. to improve the quality, configurability, and compatibility of Marlin Firmware with a huge variety of boards. For the final 1.1 release we focused on code quality, performance, stability, and overall user experience. Several new features were added, many of which require no extra hardware.

Documentation
Visit marlinfw.org for complete documentation on configuration, installation, features, and the many G-codes that Marlin supports. We will continue to expand the site to include in-depth articles, tutorials, and how-to videos on all of Marlin's features.
See the Releases page for Release Notes on all current and previous versions of Marlin.
Check out the RepRap.org Marlin Page for an overview of Marlin and its role in the RepRap project.
Marlin 1.1.x
The 1.1.x branch is home to all tagged releases of Marlin 1.1.

Marlin 1.1.9 is the final release of the AVR-only flat version of Marlin Firmware, so there will be no further 1.1.x releases. However bugfix-1.1.x will continue to receive patches for critical bugs, so be sure to test it (or bugfix-2.0.x) before reporting any bugs you find in 1.1.9.

Marlin 2.0.x
Marlin 2.0 is the future, featuring a much-improved hierarchical file structure and full 32-bit support via a Hardware Access Layer (HAL). Marlin 2.0 continues to work with Arduino IDE for the platforms it supports, and the excellent PlatformIO IDE is recommended for the next generation of ARM-based boards. If you're looking for the very best that Marlin has to offer and aren't bothered by a few rough edges, give version 2.0 a try!

Contributing to Marlin
Click on the Issue Queue and Pull Requests links above at any time to see what we're currently working on.

To submit patches and new features for Marlin 2.0 check out the bugfix-2.0.x branch, add your commits, and submit a Pull Request back to the bugfix-2.0.x branch. Once 2.0.x has been certified for a critical mass of common 32-bit boards, it will become the next major release and will be the basis for all future major and minor releases.

Note that our "bugfix" branches always contain the latest patches and new code. These patches may not be widely tested. As always, when using "nightly" builds of Marlin, proceed with full caution.

Marlin Resources
Marlin Home Page - The Marlin Documentation Project. Help us expand this site!
@MarlinFirmware on Twitter - Follow for news, release alerts, and tips & tricks. (Maintained by @thinkyhead.)
Marlin User Support
Looking for help? Our GitHub Issue Queue is only for development-related issues, feature requests, and bug reports. But there are several places where you can get help from experienced users:

RepRap.org Marlin Forum
"Marlin Firmware" Facebook Group
Tom's 3D Forums
Marlin on Discord
Credits
Marlin Admins:

Erik van der Zalm [@ErikZalm]
Scott Lahteine [@thinkyhead]
Roxanne Neufeld [@Roxy-3D]
Bob Kuhn [@Bob-the-Kuhn]
Notable contributors:

Alberto Cotronei [@MagoKimbra]
Andreas Hardtung [@AnHardt]
Bernhard Kubicek [@bkubicek]
Bob Cousins [@bobc]
Chris Palmer [@nophead]
Chris Pepper [@p3p]
David Braam [@daid]
Éduardo Tagle [@ejtagle]
Edward Patel [@epatel]
Ernesto Martinez [@emartinez167]
F. Malpartida [@fmalpartida]
Giuliano Zaro [@GMagician]
Jochen Groppe [@CONSULitAS]
João Brazio [@jbrazio]
Kai [@Kaibob2]
Luc Van Daele[@LVD-AC]
Nico Tonnhofer [@Wurstnase]
Petr Zahradnik [@clexpert]
Thomas Moore [@tcm0116]
[@alexxy]
[@android444]
[@benlye]
[@bgort]
[@Grogyan]
[@marcio-ao]
[@maverikou]
[@oysteinkrog]
[@p3p]
[@paclema]
[@paulusjacobus]
[@psavva]
[@Tannoo]
[@teemuatlut]
...and you!
License
Marlin is published under the GPL license because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.

Travis Build Status
Flattr Scott Lahteine - Flattr Scott Lahteine
Flattr Erik van der Zalm - Flattr Erik van der Zalm
