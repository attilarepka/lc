lc -- language confluxer (http://www.ruf.rice.edu/~pound/revised-lc)

- Written by Christopher Pound (pound@rice.edu), July 1993.
- Loren Miller suggested I make sure lc starts by picking a
  letter pair that was at the beginning of a data word, Oct 95.
- Cleaned it up a little bit, March 95; more, September 01

The datafile should be a bunch of words from some language
with minimal punctuation or garbage (# starts a comment!!!!).  Try 
mixing and matching words from different languages to get just 
the balance you like.  The output of course needs some editing.

If you happen to have a unix-style command line, run it as 
"lc -[number of words you want] datafile" or "lc -s [datafile]"
to see the distribution produced by the words in your dataset.
Format your output further using either my "prop" script or
the "pr" command.  Try "lc -50 datafile | prop" or maybe
"lc -392 datafile | pr -7"
