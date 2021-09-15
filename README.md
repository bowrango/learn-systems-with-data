# Matt and Davis do cool shit 

We should do some fluid sims with varying initial conditions and pass the data to a SINDy model. We also have the double pendulum code we can use, I've messed around with it some in [3]. But in general, [1] designs a custom autoencoder to discover a coordinate transformation into a reduced space where the system dynamics may be sparsely represented; nonlinear pendulum example outlined in Section 4.3. Brunton's Youtube series on SINDy really emphasizes how to formulate these problems. So I think it just comes down to logistics. 

MATLAB sources for Dynamic Mode Decompisition (DMD) and SINDy algorithms are made available in [2]. I naturally would not mind using MATLAB, but I am sure we can find Python implementations somewhere. 

Honestly, there is too much cool shit to explore. It will be exciting to leverage your CFD background for data-driven system discovery, while apply ML techniques. SINDy is formulated as a regression problem, so this will make a great project for the both of us. 

# References 

[1] https://arxiv.org/pdf/1904.02107.pdf

[2] https://faculty.washington.edu/kutz/page26/

[3] https://github.com/bowrango/symbolic-reg