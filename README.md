# rosin_diagnosis_experiments

## Install

```
mkdir -p catkin_ws/src
cd catkin_ws/src
catkin_init_workspace
git clone https://github.com/ipa-nhg/rosin_diagnosis_experiments --recursive
cd ..
rosdep install --from-path src/ -i -y
catkin build (or catkin_make)
source devel/setup.bash
```

## Execute

```
roslaunch rosin_diagnosis monitor.launch
```

