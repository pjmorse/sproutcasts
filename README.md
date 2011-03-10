Sproutcasts is a [SproutCore][1] application for browsing, viewing, and discussing the Sproutcasts series of webcasts (about--wait for it--SproutCore.) We plan to serve it from [SproutCasts.com][2].

As the webcasts are developed, we hope to use the site application itself for demonstrations where applicable. We also welcome forks and pull requests from viewers interested in helping us improve the site and both learn about and teach others about SproutCore.

_Back End_

When the Sproutcasts app moves away from fixtures as a data store, we intend to use a Rails-based REST service for the back end. For obvious security reasons, we intend to retain control of the deploy process for the SproutCore app, and therefore when the Rails back end is complete, we do not intend to keep that code in a public repository.

_Developing SproutCasts_

Once you've cloned this repository, you'll find an `.rvmrc` file for Ruby 1.9.2 and a `sproutcasts` gemset. Once you've trusted the `.rvmrc`, you may need to install (or upgrade) your 1.9.2 series Ruby in RVM. Then you can create the `sproutcasts` gemset:

<pre>
  rvm gemset create sproutcasts
  cd ..
  cd sproutcasts
  rvm gemset import sproutcasts.gems
</pre>

[1]: http://sproutcore.com "SproutCore"
[2]: http://sproutcasts.com "SproutCasts"