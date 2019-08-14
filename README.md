# rosin_diagnosis_experiments

## rosin_diagnosis - based on [model_based_diagnosis](http://www.ist.tugraz.at/ais-wiki/model_based_diagnosis)

### Install

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

### Execute

```
roslaunch rosin_diagnosis monitor.launch
```

## rosin_cob_monioring - based on [cob_monitoring](https://github.com/ipa320/cob_command_tools/tree/indigo_dev/cob_monitoring)

### Install

```
mkdir -p catkin_ws/src
cd catkin_ws/src
catkin_init_workspace
git clone https://github.com/ipa-nhg/rosin_diagnosis_experiments
cd ..
rosdep install --from-path src/ -i -y
catkin build (or catkin_make)
source devel/setup.bash
```

### Execute

```
roslaunch rosin_cob_monitoring monitor.launch
```
