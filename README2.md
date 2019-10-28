MLB Statcast Data

This dataset contains information about every pitch thrown in a regular season Major League Baseball game since 2017. A Doppler radar sits behind home plate in every stadium, measuring numerous attributes of each pitch, including release velocity, vertical and horizontal release point, extension of the pitcher's release toward home plate, vertical and horizontal break of the pitch, the ball's spin rate on its way to home plate, and attributes of the resulting hit, including exit velocity, launch angle, and the expected weighted on-base avaerage (wOBA) of a ball struck at the specific velocity and angle. For this analysis, we will focus on four specific columns of data: "release_speed", "release_spin_rate", "pfx_x", and "pfx_z".  These columns give us the pitch velocity, spin rate in RPM, the horizontal movement of the pitch, and the vertical movement of the pitch relative to gravity, respectively.

Using these measures, let's see if we can predict a batter's likiehood of hitting the ball when he swings.