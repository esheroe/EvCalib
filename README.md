# Velocity-Correlation-Calibration

We have made the spatial-temporal calibration section of the paper available as open-source, along with a simple example to aid the reader in comprehending the concept of CCA. Furthermore, we have shared code for conducting real-world data experiments.

## 1. Prerequisites

- numpy==1.21.2
- scipy==1.10.1
- matplotlib==3.5.3

```shell
pip3 install -r requirements.txt
```

## 2. Usage

- We provide a simple example for reference:

  ```shell
  python3 simple_example.py
  ```

- Real data experiment:

  ```shell
  python3 real_data_experiments.py
  ```

  In real data, our data format is as follows:
  
  ```
  vel_x, vel_y, vel_z, timestamp
  ```
  
  Note: The real velocity data we provide has been preliminarily time-aligned using brute force search methods.


## 3. Citation

If our work inspires your research or some part of the codes are useful for your work, please cite our paper: [Spatio-Temporal Calibration for Omni-Directional Vehicle-Mounted Event Cameras](https://arxiv.org/abs/2307.06810)


```latex
@ARTICLE{10404026,
  author={Li, Xiao and Zhou, Yi and Guo, Ruibin and Peng, Xin and Zhou, Zongtan and Lu, Huimin},
  journal={IEEE Robotics and Automation Letters}, 
  title={Spatio-Temporal Calibration for Omni-Directional Vehicle-Mounted Event Cameras}, 
  year={2024},
  volume={9},
  number={3},
  pages={2311-2318},
  keywords={Calibration;Cameras;Correlation;Trajectory;Sensors;Robot vision systems;Task analysis;Calibration and identification;SLAM;event-based vision},
  doi={10.1109/LRA.2024.3355765}}
```


## 4. Contact

If you have any questions or opinions, feel free to raise them by creating an 'issue' in this repository, or contact us via lx852357@outlook.com or eeyzhou@hnu.edu.cn



