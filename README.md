# gazebo_models

## usage

- model PATH registration
```
cd models
export GAZEBO_MODEL_PATH=`pwd`:$GAZEBO_MODEL_PATH
```

It's convenient if the model PATH are automatically added to your bash session every time a new shell is launched:
```
echo "GAZEBO_MODEL_PATH=`{Absolute path to /models}`:$GAZEBO_MODEL_PATH" >> ~/.bashrc
```
