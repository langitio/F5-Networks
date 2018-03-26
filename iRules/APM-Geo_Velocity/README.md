# iRule Geo Velocity by Paolo Di Liberto (F5 Italy)


This irule uses APM + ASM. It is called Geo-Velocity and User-Scoring. It allows to control where the user connects from and if this user is changing location to fast.
Then the irule controls via ASM how many violation this user did.

Over the threshold, the user will be prompted for an OTP via a Per-Request Policy.

<img align="center" src="VPE-Part1.png">
<img align="center" src="VPE-Part2.png">

<img align="center" src="Per-Req VPE.png">