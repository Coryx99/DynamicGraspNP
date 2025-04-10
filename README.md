# Dynamic Grasp of Rigid Bodies Using a Trajectory-Based Explicit Reference Governor

The videos in the `videos/` directory illustrate the validation of the proposed control framework. They correspond to the evaluation scenarios presented in the paper (see Section V):

| **Case**                        | **Description**                                                                                                                                                   | **Video File**      |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|
| **Case 1: No Constraints**      | The stabilizing control law is executed without any constraint enforcement. The system successfully reaches the desired configuration, but joint velocity and acceleration limits are violated, leading to object slippage and detachment. | `videos/CASE_1.mp4` |
| **Case 2: Only Robot Constraints** | Only the robot’s constraints (joint limits, velocity bounds, and actuator saturation) are enforced. The reference trajectory is successfully tracked, but significant slippage is observed as the object nears the tray's boundary. | `videos/CASE_2.mp4` |
| **Case 3: Full Constraints**    | Both the system constraints and the non-sliding constraint (friction cone) are actively enforced. This prevents object slippage and maintains stable contact throughout the maneuver.             | `videos/CASE_3.mp4 |

<!-- ▶️ A supplementary YouTube playlist of these cases is available [here](https://youtube.com/playlist?list=PLtp-nqaUclZNtt_kPpngbQ8GJ30u-u-5j&si=zA2FKwNum7QzDjcC). --->
<!--- Mohayad Omer, Bryan Convens, Kelly Merckaert, Bram Vanderborght, and Greet Van de Perre --->
