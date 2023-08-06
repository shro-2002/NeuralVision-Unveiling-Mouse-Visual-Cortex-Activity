# SENSORIUM 2023 Competition

![plot](figures/competition.png)
SENSORIUM is a competition on predicting large scale mouse primary visual cortex activity. We will provide large scale datasets of neuronal activity in the visual cortex of mice. Participants will train models on pairs of natural stimuli and recorded neuronal responses, and submit the predicted responses to a set of test images for which responses are withheld. 

## My Participation Overview
I am thrilled to have participated in the SENSORIUM 2023 Competition! This competition is all about predicting large-scale mouse primary visual cortex activity. Throughout the competition, I worked with extensive datasets of neuronal activity in the visual cortex of mice. My task was to train models using pairs of natural stimuli and recorded neuronal responses, and then submit the predicted responses for a set of test images whose responses were withheld.

For comprehensive details about the competition, I referred to the [SENSORIUM Competition Website](http://sensorium-competition.net/).

## My Journey and Achievements
- **Submission Date:** 6 August 2023
- **Final Rank:** 
- 
- **Submission Files:** I successfully submitted the following prediction files:
  - `predictions_live_main.parquet.brotli`: Predicted responses for the live test set in the main track.
  - `predictions_final_main.parquet.brotli`: Predicted responses for the final test set in the main track.
  - `predictions_final_ood.parquet.brotli`: Predicted responses for the final test set in the out-of-distribution (OOD) track.

## My Submission Format
Each of my submission files adheres to the specified format, containing the following columns:
- `mouse`: Session name
- `trial_indices`: Trial indices (e.g., '1.npy')
- `prediction`: A list of lists with dimensions `(number_of_neurons, n_frames)`, where `n_frames` represents the frames for the video.
- `neuron_ids`: Order of neurons in my predictions.

To create these files, I followed the provided example code using pandas.

## Acknowledgments
I want to express my gratitude to the competition organizers for creating such an exciting and challenging event. Participating in the SENSORIUM 2023 Competition has been a rewarding experience that has enhanced my skills and knowledge in neural prediction and analysis.

## Contact
If you have any questions or need further information about my participation or submission, feel free to contact me directly. I also appreciate the efforts of the competition organizers, and if you're interested in future editions, be sure to check the [SENSORIUM Competition Website](http://sensorium-competition.net/) for updates.

Thank you for joining me on this journey through the SENSORIUM 2023 Competition!
