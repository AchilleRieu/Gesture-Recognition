# Gesture-Recognition

This repository purpose is to test and evaluate the use of pose estimation for sports scoring such as rhythmic gymnastics.

## Short introduction of rhythmic gymnastics scoring

In France, as in many other countries, rhythmic gymnastics scoring is typically based on a combination of difficulty and execution. Here's a general overview of how scoring works:

1) Difficulty Score: Each routine is assigned a difficulty score based on the complexity and variety of elements performed, such as leaps, jumps, balances, rotations, and apparatus handling. Judges assess the routine's difficulty level according to the official Code of Points set by the International Gymnastics Federation (FIG). The more difficult and intricate the routine, the higher the difficulty score.

2) Execution Score: Judges evaluate the execution of each element within the routine. They consider factors such as technique, precision, artistry, fluidity, and synchronization with the music. Deductions are made for mistakes, imperfections, lack of control, and other errors.

3) Artistry and Presentation: Additionally, there may be components of the score dedicated to artistry, expression, choreography, and overall presentation. This aspect often involves subjective judgment based on the gymnast's interpretation of the music, expression, and emotional engagement with the audience.

4) Penalties: Penalties may be applied for rule violations, such as stepping out of bounds or using improper apparatus technique.

5) Total Score: The difficulty score and execution score are combined to calculate the gymnast's total score. The highest and lowest scores from the panel of judges are typically discarded, and the remaining scores are averaged to determine the final score.

In this project, we are going to focus on the difficuly score and execution score.

## Project description

The project can be slit in several steps :

1) Pose estimation
2) Movement classification (Difficuly score)
3) Posture correction (Execution Score)

### Pose estimation

During this step, a model is going to predict the position of the athlete from 2D pictures.

A quick search on pose estimation models give us the following papers.
MoveNet and PoseNet are implemented within the Tensorflow library [1].
We will use those model for the first tests.

I would then be interesting to look for better models.
For example : MMPose, ViTPose, PCT, OmniPose, AlphaPose, YOLO-NAS, OpenPose [2], [3], [4]

### Movement classification 

This step purpose is to classifiy the movement 



References:

[1] https://www.tensorflow.org/lite/examples/pose_estimation/overview?hl=en

[2] https://paperswithcode.com/task/pose-estimation

[3] https://www.reasonfieldlab.com/post/human-pose-estimation-2023-guide

[4] https://pallawi-ds.medium.com/which-human-pose-estimation-model-should-you-pick-to-realise-your-ideas-for-a-video-analytics-6ca754cc1f4e
