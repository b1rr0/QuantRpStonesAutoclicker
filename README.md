This app helps players progress through the game of finding stones. An example of work that was automated https://youtu.be/aOOujdYdk9c?t=296
=====================

![Image alt](https://github.com/b1rr0/QuantRpMasonAutoclicker/blob/master/images/gameScreen.png)
Open the game at 800 x 600  (in this respect the stones are larger).
Then launch the application and it will search for pictures of stones on the screen and automatically click on them.
=====================================================================================================================

![Image alt](https://github.com/b1rr0/QuantRpMasonAutoclicker/blob/master/images/onlineScreen.png)

The application also checks that you are not currently in the open world by the presence of these fields
=====================================================================================================================


How it works:
Every 0.5 seconds a screen is taken and all the points on the screens that were not there in the previous screen are found.
And an array is built with identical objects in 2 screenshots.
Where:
=
1 - same.
=
0 - different.
=
![Image alt](https://github.com/b1rr0/QuantRpMasonAutoclicker/blob/master/images/map.png)

Now it has come down to a problem about islands and finding the maximum island.
Next, hover the mouse and click on the maximum island.
=====================================================================================================================

To use:
run ApplicationMain.main().
=====================================================================================================================
