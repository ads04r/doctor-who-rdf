BBC Doctor Who Linked Data
==========================

A long time ago, the BBC had proper linked open data about all of their shows.
To me, the most interesting part of this was the complete history of Doctor
Who episodes, right back to 1963 when the show was first broadcast. So I
downloaded a copy of all this data and set a cron script to check when new
episodes were released.

Over time, the BBC's linked open data site began to fall into disrepair
and the programmes data in RDF was eventually removed, although you can still
get the data in JSON format from the BBC website. So I updated my script
to convert the JSON data into the old RDF format, and kept updating the
BBC's data with new episodes of Doctor Who, committing my copy to this
very repository. I've been doing this for a very long time.

Why release 1.0 now?
--------------------

Because I'm stopping. Well, sort of. I'm still keeping the data and updating
it, but it's no longer a proper archive because it will contain my
additions and URI system. When production moved to Bad Wolf around the time
of the 60th anniversary, the BBC completely reorganised the Doctor Who
back catalogue. The unique ID numbers (and therefore the URIs, although
they haven't resolved for years) all changed, and the BBC now considers
Doctor Who to be three different shows: 1963-1996, 2005-2022 and
2023-present. The benefit of this from a viewer perspective is that all
the (non-missing) old episodes are now on iPlayer to stream for free in
the UK, so it's really not a bad thing at all, even if there are now
technically three series known as "series 1".

So as the series is changing, and this dataset is changing, I thought
doing a release of the data as it was at the end of Jodie Whittaker's
final series would be a good way to preserve the data as it was,
while still allowing me to do cool things with it in the future.
