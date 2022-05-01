# ros2 installation nodes
linke: https://docs.ros.org/en/galactic/Installation/Ubuntu-Development-Setup.html


### installation
````bash
python3 -m pip install -U \
  flake8-blind-except \
  flake8-builtins \
  flake8-class-newline \
  flake8-comprehensions \
  flake8-deprecated \
  flake8-docstrings \
  flake8-import-order \
  flake8-quotes \
  pytest-repeat \
  pytest-rerunfailures \
  pytest \
  setuptools \
  catkin_pkg \
  empy \
  lark \
  pyqt5 \
  numpy
````

### compile
skip QT5 python packages
````bash
colcon build --symlink-install --packages-skip-by-dep python_qt_binding
````
