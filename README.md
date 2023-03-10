ycalc
========
"ycalc is an X-window calculator, with much more functions than the standard xcalc and is heavily influenced by TI-59." - Ulf Nordquist (author)


About
--------
In the year 1989, Ulf Nordquist began work on this fine xcalc replacement.
It enjoyed several years of feature improvements, and gained support for Linux
in 1994 to complement the original HPUX (pronounced H-pux) platform.  It is
open-source under the GPLv2, placing it amongst the earliest pioneers in
copyleft licenses!

I personally found this little calculator to be indispensable for bit hacking
back in the day.  And every time I've not had it available in recent years
I would lament its absence from our modern distributions.  Assuming the
worst for ycalc, a finality of bitrot and 404s, I had given up, until today...

While clearing out an old computer of mine I found an i386 linux build of ycalc.
To my complete surprise it still ran on my spiffy new x64 Linux machine.
Feeling inspired, I found the source code on Wayback Machine and have placed it
here for the world to enjoy again.

This program, that began life 34 years ago, builds and runs in 2023
with just a couple cosmetic changes.  Think about that...  We live in an age of
package lock files, rampant upstream library deprecations and compatibility regressions of all types.   Most modern projects start to fester after just a few months if not properly maintained, yet ycalc still runs and builds decades later!

I hope we can all take some inspiration from this great calculator of old.
It is a wonderful open-source contribution to the world by Ulf Nordquist,
that I will happily be reincorporating into my workflows for years to come!


PS: Props to Linus who didn't "break user-space" after all these years!


Building
--------
Brace yourself...
```shell
make
./ycalc
```
