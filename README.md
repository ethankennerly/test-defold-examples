# Test Defold Tutorial

This project tests that a Defold tutorial game can exist on a different server, build WebGL, and play sounds with Flash disabled.

The game is from Defold's examples, and copyright by them or the authors:

<https://github.com/defold/defold-examples>

With a click on a button, a click sound is played.

With FireFox disabling Flash, the click sound can be heard.

To confirm no clipping of the sound, I changed the sound to a slow jump sound by generating from BFXR.

<http://www.bfxr.net/>

I noticed Defold has a sound SWF file.  Apparently this is optional or not used.

How to host project outside of King's servers:

<https://forum.defold.com/t/howto-alternative-project-hosting/1309>

I had some commits, so I also merged the histories:

    git pull origin master --allow-unrelated-histories

<http://stackoverflow.com/questions/37937984/git-refusing-to-merge-unrelated-histories>

With Defold 1 editor it seems only one game is allowed per repo.
