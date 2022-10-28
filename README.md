# AGV-Ros-task

## Task 1
Task 1 was to code a simple subsciber and a publisher 

Open a new terminal and start roscore using 
```bash
roscore
```
Open another terminal and run the talker node using
```bash
rosrun begginer_tutorials talker.py
```

open another terminal and run the subsriber node using
```bash
rosrun begginer_tutorials listener.py
```

## Task 2

Open a new terminal and start roscore
```bash
roscore
```

open a new terminal and start the gaussian noise node using 
```bash
rosrun beginner_tutorials gaussianNoise.py
```

open a new terminal and start playing the bagfile using 
```bash
rosbag play <bagfile name>
```

open a new terminal 
```bash
rostopic echo /cmd_vel
```

open a new terminal 
```bash
rostopic echo /noise_add
```
