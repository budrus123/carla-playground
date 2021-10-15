# carla-playground
Playground containing code for CARLA Simulator

![](images/waypoint-prjection.gif)

## CONTENTS OF THIS FILE

* [Introduction](#intro)
* [Simulation Cases](#cases)
* [Requirements](#requirements)
* [Usage](#usage)

## INTRODUCTION<a name="intro"></a>
The following project is designed to showcase useful pieces of code
that can interact with **<a href="https://carla.org/" target="_blank">CARLA</a>** (Open-source simulator for autonomous driving research). The following codes are provided on this playground:
1. Show waypoints for a certain route that the car is following. Located in the file called `show-route-path.py`

## Simulation Cases<a name="cases"></a>
The following codes are provided on this playground:
1. Show waypoints for a certain route that the car is following. Located in the file called `show-route-path.py`. This code is a Simple python code that uses CARLA to
spawn a vehicle and show projections of the path/route
the vehicle is taking. The vehicle is running in autopilot
mode, so this basically shows the way points within a certain
radius of the cars location. The output is as shown in the gif below:

![](images/waypoint-prjection.gif)

## Requirements<a name="requirements"></a>
1. Latest CARLA simulator installed (tested on 0.9.12). Link for this release - <a href="https://github.com/carla-simulator/carla/releases/tag/0.9.12/" target="_blank">CARLA 0.9.12 Release</a>
2. Python 3.7
3. Additional requirements required by the CARLA installation


## Usage<a name="usage"></a>
> **Running the CARLA server**
```sh
$ CarlaUE4.exe -carla-server
```

> **Running the client side for Showing the route path**
```sh
$ python show-route-path.py
```
