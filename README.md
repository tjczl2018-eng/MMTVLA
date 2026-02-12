# MMTVLA

This repository provides the QUARD-CoT dataset and validation videos of MMTVLA in both simulation environments and on the Unitree Go2 real robot, and the MMTVLA code will be released soon.

QUARD-CoT Dataset: https://huggingface.co/datasets/cenzl/QUARD_CoT

# Simulation Video

<img src="video/sim/go_to.gif" width="720">
<img src="video/sim/unload.gif" width="720">
<img src="video/sim/crawl.gif" width="720">
<img src="video/sim/go_through_rectangle.gif" width="720">
<img src="video/sim/go_avoid.gif" width="720">
<img src="video/sim/go_through_triangle.gif" width="720">
<img src="video/sim/distinguish.gif" width="720">

# Sim2Real Video

We evaluate MMTVLA in real-world scenarios using the Unitree Go2 quadruped robot platform and the official sdk.

### Go to a position in front of the red ball.

<img src="video/real/go_to.gif" width="720">

### Recognize the letter B and walk to the sign displaying the letter B.

<img src="video/real/distinguish.gif" width="720">

### Go through the square passage.

<img src="video/real/go_through.gif" width="720">

### Go through the triangular passage.

<img src="video/real/go_through2.gif" width="720">

### Avoid the chair and locate the green sphere, then move toward it.

<img src="video/real/avoid.gif" width="720">

### Unload the item into the yellow tray.

<img src="video/real/unload.gif" width="720">
