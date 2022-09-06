Distance measuring
==================

Why is measuring distance important?
------------------------------------
Welcome to the distance measuring module! The ability to measure the distance between a robot and the objects in its surrounding environment is crucial. This information allows the robot to avoid collisions and determine its current location. 

Self driving vehicles
^^^^^^^^^^^^^^^^^^^^^
Distance measuring is a fundamental feature of Tesla's Autopilot software for self-driving cars. Autonomous driving is a complex task and requires an incredible amount of information on its surrounding obstacles to avoid a collision. Measuring the forward distance to an obstacle allows the vehicle to maintain a healthy distance. Measuring sideway distance determines whether it is safe to merge highway lanes. While parking, measuring backward distance informs whether it is safe to continue backing up. 

Tesla uses radars, a system using radio waves, for long-range sensing. A device, known as a transmitter, produces electromangetic radio waves, which reflects back after hitting an object. Another device, known as a receiver, captures this reflected wave to calculate the distance of the object based on the wave's travel time and speed. 

Marine echolocation
^^^^^^^^^^^^^^^^^^^
Measuring distances isn't only important on land; it is important 20,000 leagues under the sea as well!
Submarines use sonar, a system using sound, to navigate in the murky waters, measure distances from nearby objects, and detect notable presences in its surrounding environment, such as sunken ships.  

Similar to radars, sonar detects objects by transmitting ultrasonic waves and captures the reflected echoes. Based on the travel speed and time of the wave, the distance to the object can be calculated. 

Animal echolocation
^^^^^^^^^^^^^^^^^^^
While the integration of these distance-measuring sensors into technology is impressive, animals do it better! 

Bats navigate through dark caves and find food through echolocation by emitting high frequency sound waves using their mouths. They listen to the echo of the sound waves boucing back from the environment with their highly sensitive ears, allowing them to determine the size, shape, and texture of objects.

Similar to bats, whales also use echolocation to navigate underwater and locate food. They emit high frequency clicking sounds using their nasal passages.

Different techniques for measuring distance
-------------------------------------------
So, what are some ways that allows you to measure distances?

Mechanical sensors
^^^^^^^^^^^^^^^^^^
If you touch it, then you know it's there. This is a very naive, but still valid way to approach distance measurement. The obstructing object could active a mechanical switch upon contact, signaling its precense. A bumber sensor would be a good example in this use case. 

Reflective sensors
^^^^^^^^^^^^^^^^^^^^^^^^^
Lidar (Light Detection and Ranging), Sonar (Sound navigation and ranging), and Radar (Radio Detection and Ranging) all follow the same principle. A transmitter emits light, sound, or radio vawes, which bounces back from an obstructing object, resulting in echoes. A receiver captures these echos, allowing for the calculation of distance based on the travel time of the wave.

Using your rangefinder
----------------------
Let's prevent our robot from running into walls, and program our very own range finder!

Programming a robot to stop before hitting an object
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Programming a robot to turn around if too close to an object
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Using random turns
^^^^^^^^^^^^^^^^^^

The inertia problem
^^^^^^^^^^^^^^^^^^^

Using proportional control to stop the robot
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Using the rangefinder to follow a wall
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^