<code>This repo clone was made because I was looking the page http://diveintomark.org/archives/2003/06/12/how_to_consume_rss_safely but the domain registration had expired and the links to the page all over the web were broken. Finally I found a backup of the content and made this fork as a mirror of http://diveintomark.org/archives/</code>

- - - - - - - - - - - -
[Here is the mirror of http://diveintomark.org/archives.html](http://ljv5555.github.io/diveintomark/archives.html)
- - - - - - - - - - - -
[Here is a mirror of http://diveintomark.org/archives/2003/06/12/how_to_consume_rss_safely](http://ljv5555.github.io/diveintomark/archive-html/2b3143a43f07a6cbf9dc0ccca3bc870e44872618.html)

- - - - - - - - - - - -

# Dive Into Mark

This is an archive of [Dive Into Mark.](http://diveintomark.org/)

There are two parts to this archive: the Google Reader Atom scrape, and
the Web Archive HTML scrape.

The Google Reader Atom scrape is the first archive of the site that was
created for hosting. It's in the `gr-atom` directory in files numbered
`1.xml` thru `17.xml`. They're in valid Atom format, copied from the
Google Reader API, complete with Google's additions to the format. It
only goes back to "Every exit", an entry dated 2004-10-18, because
that's the oldest post Google Reader has in its archive.

The Web Archive HTML scrape is more complete, but harder to work with.
(I hope to convert it to Atom format for better machine-readability
soon.) It *should* include all the posts (less one). The post HTML files
are in the `archive-html` directory, with almost-random (SHA1 hashes of
Web Archive URLs) names. To look up a URL and see which file contains a
particular post, see `archive.manifest`, which maps hashes to URLs, in a
line-based tab-delimited format. You can also consult `archives.html`,
the file this list of posts was generated from, to get an idea of what's
here. The HTML scrape is missing one post: "Grading on a curve", which
is the last post ever made to the Dive Into Mark blog. I can't find this
complete in the Web Archive. (If you manage to find it, please let me
know!)

Thanks to Mark Pilgrim for writing such an eloquent weblog for so many
years.
