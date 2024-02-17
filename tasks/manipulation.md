## Description

| Task      | Description                                                  | Level                                            |
| --------- | ------------------------------------------------------------ | ------------------------------------------------ |
| Lift      | The robot arm must lift a small cube.                        | :star:                                           |
| Can       | The robot must place a coke can from a large bin into a smaller target bin. | :star::star:                                     |
| Square    | The robot must pick a square nut and place it on a rod.      | :star::star::star:                               |
| Transport | Two robot arms must transfer a hammer from a closed container on a shelf to a target bin on another shelf. | :star::star::star::star:                         |
| Tool Hang | A robot arm must assemble a frame consisting of a base piece and hook piece by inserting the hook into the base, and hang a wrench on the hook. | :star::star::star::star::star:                   |
| Push-T    | A robot push a T shaped block (gray) to a fixed target (red) with a circular end-effector (blue)s. | :star::star::star::star::star:                   |
| BlockPush | This task tests the policy’s ability to model multimodal action distributions by pushing two blocks into two squares in any order. | :star::star::star::star::star::star:             |
| Kitchen   | the Franka Kitchen environment contains 7 objects for interaction and comes with a human demonstration dataset of 566 demonstrations, each completing 4 tasks in arbitrary order. | :star::star::star::star::star::star::star::star: |

<div align="center">
  Table2. Task Description.
</div>



## Summary

| Task      | Src                                                          | #Rob | #Obj | #ActD | #PH  | #MH  | Steps | Img? | HiPrec |
| --------- | ------------------------------------------------------------ | ---- | ---- | ----- | ---- | ---- | ----- | ---- | ------ |
| Lift      | [Robomimic](https://github.com/whaleRobot/Robot-Learning/blob/master/codes/manipulation/Robomimic.md) | 1    | 1    | 7     | 200  | 300  | 400   | Yes  | No     |
| Can       | Robomimic                                                    | 1    | 1    | 7     | 200  | 300  | 400   | Yes  | No     |
| Square    | Robomimic                                                    | 1    | 1    | 7     | 200  | 300  | 400   | Yes  | Yes    |
| Transport | Robomimic                                                    | 2    | 3    | 14    | 200  | 300  | 700   | Yes  | No     |
| ToolHang  | Robomimic                                                    | 1    | 2    | 7     | 200  | 0    | 700   | Yes  | Yes    |
| Push-T    | [IBC](https://arxiv.org/abs/2109.00137)                      | 1    | 1    | 2     | 200  | 0    | 300   | Yes  | Yes    |
| BlockPush | [BeT](https://arxiv.org/abs/2206.11251)                      | 1    | 2    | 2     | 0    | 0    | 350   | No   | No     |
| Kitchen   | [Relay Policy](https://relay-policy-learning.github.io)      | 1    | 7    | 9     | 656  | 0    | 280   | No   | No     |

<div>
  Table2. Task Summary.# Rob: number of robots, #Obj: number of objects, ActD: action dimension, PH: proficient-human demonstration, MH: multi-human demonstration, Steps: max number of rollout steps, HiPrec: whether the task has a high precision requirement.
</div>

