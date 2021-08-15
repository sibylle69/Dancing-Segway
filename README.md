# Dancing-Segway

Auto-balancing and beat-dancing segway coded on a PyBench using Micropython. Second year solo project in electronics.

Several steps have been taken to gradually increase the complexity of the project. First, the segway was programmed to **read a dance file** and execute the corresponding movements while the segway was held with stabilizers. Then, a beat detector was added so that the segway was able to dance in rhythm with a music. Finally, a **PID control algorithm** was implemented and tuned, and the stabilizers were removed once self-balancing was achieved. The combination of the auto-balance and beat-dancing features was reached by using the pitch angle as the set-pont variable and by controlling the motors to maintain the pitch angle to be zero or at the vertical position. The final outcome was fully working and very engaging.
