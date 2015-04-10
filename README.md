annoy-a-tron
============

I have a co-worker. We'll call him Brian.

Brian likes to mess with people: practical jokes, sarcastic remarks, playing
dumb, whatever. Luckily for those of us who are subjected to his grief, Brian
leaves his computer unlocked when he walks away from it. Unluckily for Brian,
he works with programmers.

One day, while Brian was out to lunch, we wrote a script to annoy Brian at
random intervals, and installed it on his computer. This was fun for a while,
but now it's time to step it up. It's time to add the the ability to change
the prank without having to touch his computer, and it's time to get people
outside these walls involved. Thus, this repo.


How it works
------------

Every few minutes, Brian's computer will check this repository for the latest
version of the script. If the script has changed, it'll download the new
hotness and start running that instead. The technical details of how that's
done are left as an exercise to the reader.


How you can help
----------------

Fork this repo, add a script that does something annoying, and issue a Pull
Request. The annoying thing your script does needs to have only a small chance
(3-5%) of occurring because this script will be run every minute. Some things
that we've had Brian's computer do so far:

* Say "Ooo, right there"
* Announce a randomly-generated time
* Play a random system alert sound
* Say "System Updates Available"
* Open an image

If you'd like to see what we've done in the past, just dig through the repo and
model your script on one of those.


Miscellaneous notes
-------------------

1. Brian uses OS X, so any contribution should work on a stock, non-developer OS X
install.
2. Scripts can be in any language (provided that language is available on
a stock OS X system), but should stick to that language's standard library
3. If you shell out to anything in your script, please ensure that utility is
installed on the system by default.
4. Scripts should include a shebang line, and should be executable.
5. Scripts should be entirely self-contained.
6. Any script that is destructive, racist, sexist, homophobic, transphobic, or
deemed by me to be shitty will be rejected.


LICENSE
-------

Consider this repo a public service for anyone that has a co-worker like Brian.
Hopefully your Brian also leaves his/her computer unlocked.
