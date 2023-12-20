# Datasets

## Datasets for Robotics

| Dataset                                                      | #Modal | #Tasks | #Skills | Format                                    | Domains      | Areas              |
| ------------------------------------------------------------ | ------ | ------ | ------- | ----------------------------------------- | ------------ | ------------------ |
| [MIME](https://sites.google.com/view/mimedataset)            |        |        |         |                                           |              |                    |
| [Robo Turk](https://roboturk.stanford.edu/)                  |        |        |         |                                           |              |                    |
| [RoboNet](https://www.robonet.wiki/)                         |        |        |         |                                           |              |                    |
| [BridgeData](https://sites.google.com/view/bridgedata)       |        |        |         |                                           |              |                    |
| [BC-Z](https://sites.google.com/view/bc-z/home)              |        |        |         |                                           |              |                    |
| [RoboSet](https://robopen.github.io/)                        |        |        |         |                                           |              |                    |
| [BridgeData V2](https://rail-berkeley.github.io/bridgedata/) |        |        |         |                                           |              |                    |
| [**RH20T**](https://rh20t.github.io/)                        | Multi  | 147    | 42      | <Human Demonstration, Robot Manipulation> | manipulation | Imitation Learning |

<div align="center">Table 1: Information of Dataset</div>



| Dataset                                                      | #Traj | #Skills | #Robots | Human Demo | Contact Rich | Depth Sensing | Camera Calib | Force Sensing |
| ------------------------------------------------------------ | ----- | ------- | ------- | ---------- | ------------ | ------------- | ------------ | ------------- |
| [MIME](https://sites.google.com/view/mimedataset)            | 8.30k | 12      | 1       | Y          | N            | Y             | N            | N             |
| [Robo Turk](https://roboturk.stanford.edu/)                  | 2.10k | 2       | 1       | N          | N            | N             | N            | N             |
| [RoboNet](https://www.robonet.wiki/)                         | 162k  | N/A     | 7       | N          | N            | N             | N            | N             |
| [BridgeData](https://sites.google.com/view/bridgedata)       | 7.20k | 4       | 1       | N          | N            | Y*            | N            | N             |
| [BC-Z](https://sites.google.com/view/bc-z/home)              | 26.0k | 3       | 1       | Y          | N            | N             | N            | N             |
| [RoboSet](https://robopen.github.io/)                        | 98.5k | 12      | 1       | N          | Y            | Y             | N            | N             |
| [BridgeData V2](https://rail-berkeley.github.io/bridgedata/) | 60.1k | 13      | 1       | N          | Y            | Y*            | N            | N             |
| [**RH20T**](https://rh20t.github.io/)                        | 110k  | 42      | 4       | Y          | Y            | Y             | Y            | Y             |

<div align="center">Table 1: Information of Datase."Y*"indicates that only a portion of the images are paired with depth sensing</div>



## Datasets for Offline RL

| Dataset                                               | Tasks: #Traj                                                 | Domains                                                      | Simulators                              |
| ----------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------- |
| [D4RL](https://sites.google.com/view/d4rl-anonymous/) | Maze2D: $7\times 10^6$<br />AntMaze: $6\times 10^6$<br />Gym-Mujoco: $12\times 10^6$<br />Adroit: $7\times10^6$<br />Flow: $4\times 10^6$<br />FrankaKitchen: $3\times10^5$<br />CARLA: $3\times 10^6$ | 1.  manipulation<br />2. locomotion<br />3. autonomous<br />4.  traffic | 1. Gym<br />2. Flow<br />3. CARLA<br /> |



## Reference

[1] Sharma P, Mohan L, Pinto L, et al. Multiple interactions made easy (mime): Large scale demonstrations data for imitation[C]//Conference on robot learning. PMLR, 2018: 906-915.

[2] Mandlekar A, Zhu Y, Garg A, et al. Roboturk: A crowdsourcing platform for robotic skill learning through imitation[C]//Conference on Robot Learning. PMLR, 2018: 879-893.

[3] Dasari S, Ebert F, Tian S, et al. Robonet: Large-scale multi-robot learning[J]. arXiv preprint arXiv:1910.11215, 2019.

[4] Ebert F, Yang Y, Schmeckpeper K, et al. Bridge data: Boosting generalization of robotic skills with cross-domain datasets[J]. arXiv preprint arXiv:2109.13396, 2021.

[5] Jang E, Irpan A, Khansari M, et al. Bc-z: Zero-shot task generalization with robotic imitation learning[C]//Conference on Robot Learning. PMLR, 2022: 991-1002.

[6] Walke H R, Black K, Zhao T Z, et al. Bridgedata v2: A dataset for robot learning at scale[C]//Conference on Robot Learning. PMLR, 2023: 1723-1736.

[7] Bharadhwaj H, Vakil J, Sharma M, et al. Roboagent: Generalization and efficiency in robot manipulation via semantic augmentations and action chunking[J]. arXiv preprint arXiv:2309.01918, 2023.

[8] Fang H S, Fang H, Tang Z, et al. RH20T: A Comprehensive Robotic Dataset for Learning Diverse Skills in One-Shot[C]//Towards Generalist Robots: Learning Paradigms for Scalable Skill Acquisition@ CoRL2023. 2023.

[9] Fu J, Kumar A, Nachum O, et al. D4rl: Datasets for deep data-driven reinforcement learning[J]. arXiv preprint arXiv:2004.07219, 2020.

