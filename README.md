## Vision-based Lane Keeping Module

### Requirement
- Python 3
- ROS
- Vision Sensor (from ``SVL`` or ``Real Camera``)
- Actuator (from ``SVL`` or ``Real Car``)

### Installation
```
pip3 install opencv-python
```

### Usage
```
roslaunch rosbridge_server rosbridge_websocket.launch
SVLsimulator run simulation
python3 CubetownBase.py
python3 lkas.py
roslaunch twist_filter twist_filter.launch
```

### Demo
![lkas_success](https://user-images.githubusercontent.com/44594966/150334917-fb741128-8fbb-4e73-944e-353a8ca5f5d3.gif)
