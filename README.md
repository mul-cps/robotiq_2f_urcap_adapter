```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/mul-cps/robotiq_2f_urcap_adapter/noble-jazzy-amd64/ ./" | sudo tee /etc/apt/sources.list.d/mul-cps_robotiq_2f_urcap_adapter-noble-jazzy-amd64.list
echo "yaml https://github.com/mul-cps/robotiq_2f_urcap_adapter/raw/noble-jazzy-amd64/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-mul-cps_robotiq_2f_urcap_adapter-noble-jazzy-amd64.list
```
