# Term - 2 - Project - 3 : Localization with Particle Filters - Kidnapped Vehicle Project
Udacity Self-Driving Car Nanodegree - Kidnapped Vehicle Project

## Overview

This project implements a [Particle Filter](https://en.wikipedia.org/wiki/Particle_filter) applied to a [Kidnapped robot(car) problem](https://en.wikipedia.org/wiki/Kidnapped_robot_problem). A simulator is provided by Udacity ([it could be downloaded here](https://github.com/udacity/self-driving-car-sim/releases)). This simulator will generate noisy landmark observation from a car to the Particle Filter using [WebSocket](https://en.wikipedia.org/wiki/WebSocket). The Particle Filter uses the [uWebSockets](https://github.com/uNetworking/uWebSockets) WebSocket implementation to respond to this observation with the estimated car position. Udacity provides a seed project to start from on this project ([here](https://github.com/udacity/CarND-Kidnapped-Vehicle-Project)).

## Prerequisites

The project has the following dependencies (from Udacity's seed project):

- cmake >= 3.5
- make >= 4.1
- gcc/g++ >= 5.4
- Udacity's simulator.

For instructions on how to install these components on different operating systems, please, visit [Udacity's seed project](https://github.com/udacity/CarND-Extended-Kalman-Filter-Project). As this particular implementation was done on Linux Ubuntu, the rest of this documentation will be focused on Linux.

In order to install the necessary libraries, use the [install-xxxx.sh](./install-xxxx.sh) based on your operating system.

## Compiling and Executing the Project

These are the suggested steps:

1. Clone the repo and cd to it on a Terminal.
2. Clone this repo.
3. Make a build directory: `mkdir build && cd build`
4. Compile: `cmake .. && make`
5. Start the Simulator
6. Run it by the following command: 
   * `./particle_filter`
  

## Running the Filter

From the build directory, execute `./particle_filter`. The output should be:

```
Listening to port 4567
Connected!!!
```

## Optional Commands
In this project, Udacity's seed repo provides scripts to clean, compile and run it. These are the following commands you need to run from this repo directory

```
> ./clean.sh
> ./build.sh
> ./run.sh
```  
