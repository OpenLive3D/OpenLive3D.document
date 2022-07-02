# How to set Mouth Config?

Note: Make sure to have enough light to your face. The light will affect the facial landmark extraction result.


## Set Mouth Open Ratio `open ratio`

By observing the real-time `mouth open` parameters, you can set `MOUTH_RATIO` to the scale you desire.

By setting a larger open ratio (higher than 4), the mouth will be fully open most of the time.

It is recommended to set the ratio to be around `2` to `4` so that the VTuber won't need to open the mouth too much to make the 3D model fully open the mouth.


## Set Mouth Stablize Ratio `stablize ratio`

By observing the real-time `mouth open` parameters, you can set `MOUTH_STABLIZE_RATIO`.

Note that the `mouth open` parameters is the smoothed result. The smoothing ratio is the `stablize ratio` that we are setting now.

When the value is small (close to 0), mouth moves faster. When the value is large (close to 1), mouth stops moving.

The recommended value is around `0.1` so that the mouth will not glitch while still move fast enough to capture the movement of speaking.


----

[BACK TO DOCUMENT FRONTPAGE](/)
