Bump It!
=============

Little ruby script for automating the tedious process in your software developing process when going from alpha to beta and simultaneously starting a new alpha.

Example Situation
-----------------

You are in your ```develop``` branch and the current version is a 0.6 alpha. The last feature planned for the 0.6 version is commited so it's time to go beta! Now you have create a new branch ```release-0.6```, update the version file with "0.6 beta", commit this and tag the whole thing with ```0.6-beta```. Back in develop merge the release branch back and edit the version file again but this time it's "0.7-alpha". Comit, add tag and never forget to push it with all the tags.

With Bump It! it's just a matter of call ```bumpit``` ... the rest is automagic.

Installation
------------

Add the path where the bumpit script is located to your system's path environment variable. And ruby must be available on your system ... obviously :-)

Disclaimer
----------

Be aware that you run the script at your own risk and while it has been written with the intention of minimising the potential for unintended consequences, the owners, hosting providers and contributers cannot be held responsible for any misuse or script problems.
