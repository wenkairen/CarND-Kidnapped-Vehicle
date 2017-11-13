# CarND-Kidnapped-Vehicle
self-driving second term 

Code description:

The Particle Filter is implemented in src/particle_filter.cpp:

Initialization: Particle initialization is implemented at ParticleFilter::init from line 24 to line 62.

Prediction: The prediction step is implemented at ParticleFilter::prediction from line 64 to line 100.

Weight's update: This is the more important operation in my opinion. It is implemented at ParticleFilter::updateWeights from line 138 to line 217.

Almost the rest of the magic happens on src/main.cpp. The event handler declared at line 49 parse the received message and call the above described Particle Filter methods.
