# gametheory
Using Combinatorial Optimization and Game Theory concepts to build a general AI game bot
Using Neuroevolution and RL to train an agent, with learnt policies being represented dynamically in a memory storage.

In contemporary RL, policy search methods can be broken down into gradient-based methods, also known as policy gradient methods, and methods that do not rely on the gradient. Gradient-free methods include evolutionary algorithms. ES and GA are similar terms referring to this very approach. 

This project is likely to end up being the virtual agent that the [ROSCOG](https://github.com/blackvitriol/ROSCOG) project aims.
For neuroevolutionary approach with implicit environment representations, see: (https://github.com/blackvitriol/Genetic_Programming)

Collecting resources:
- http://deap.readthedocs.io/en/master/
- https://github.com/glample/Arnold/blob/master/README.md
- https://github.com/SerpentAI/SerpentAI

**Environment:**
Using MuJoCo: Modeling, Simulation and Visualization of Multi-Joint Dynamics with Contact
This is a physics engine to be used in conjunction with dm_control ***'The DeepMind Control Suite and Control Package"***

Work on :
- Desktop games (including browser games).
- OpenAI bots that are being rendered

Before running: 
Get a key from MuJoCu's website and place it in the bin folder, then follow:
https://github.com/deepmind/dm_control

`
export LD_LIBRARY_PATH=~/.mujoco/mjpro150/bin
sudo apt install mesa-utils
ldd $(which glxinfo) | grep libGL.so
LD_PRELOAD=/usr/lib/x86_64-linux-gnu/libGLEW.so.1.13:/usr/lib/nvidia-384/libGL.so.
`

Platform: Ubuntu 16.04
