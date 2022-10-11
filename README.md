# stanford_projects

## Image-Based Music Generation using Invertible MIDI-to-Image Conversions

**Abstract:** There have been many attempts at generating music using various deep genera- tive models. Although some of these attempts have been relatively successful, image generation models significantly outperform music generation models in their respective tasks. We leverage these impressive advances in image generation to achieve higher quality music generation. Using a dataset consisting of classical musical instrument digital interface (MIDI) files, we map each file to a visual representation, and feed the resulting images to StyleGAN2, WassersteinGAN, and PixelCNN++. The given model then generates new images based on the learned distribution of the MIDI image representations. Finally, we convert the generated images back to their musical MIDI form. We find that PixelCNN++ significantly outperforms the other models in the Melody, Harmony, and Rhythm of the resulting MIDI files. We also find that this technique outperforms traditional music generation models such as Music Transformer.

## Reformed QANet - Optimizing the Spatial Complexity of QANet

**Abstract:** The feed-forward QANet architecture replaced the bidirectional LSTMs of traditional Q&A models’ encoder components with convolution + self-attention to increase the speed of the model without sacrificing accuracy. We achieved scores of 64.5 EM/67.9 F1 on the dev set and 61.64 EM/65.30 F1 on the test set. While the parallel nature of QANet’s CNN architecture allows for a significant speed boost, it entails GPU memory requirements to reap those benefits. We preform an ablation study to measure changes to spatial complexity, speed, and performance on the QANet architecture, replacing the self attention and feed-forward layer with LSH attention, reversible residual networks, and an entire reformer. We found that implementing LSH attention successfully decreased memory usage while maintaining reasonable performance. While the other modifications did not quite maintain the original QANet model’s EM and FI scores, they significantly improved memory complexity.

## GPT-3 scores in the top 7% of students in the United States on the ACT Reading Section

**Abstract:** This paper investigates the ability of available GPT-3 models to take the ACT Reading section and the affects of finetuning GPT-3 with a dataset of 440 ACT Reading section questions. We found that using just one-shot prompts with the most powerful off-the-shelf version of GPT-3, which was recently finetuned to better follow directions, is able to achieve a remarkable average scale score on the ACT Reading section of 33.66 out of 36 over 3 test exams, which means it answered 112 out of 120 questions correctly (placing it in the top 93-96% of students in the US). In addition, we find that finetuning can drastically improve task-specific performance, evidenced by our custom finetuned GPT-3 model achieving the best zero-shot performance of a scale score of 30.66 over the same three tests.

## Approximating Soil Organic Carbon (SOC) using Remote Sensing and Machine Learning

**Abstract:** Globally, soils have the potential to sequester 1.85 gigatons of carbon per year. With rising CO2 emissions and climate change, it is critical to leverage soils as carbon sinks. To implement and monitor practices that increase the carbon sequestration ability of soils, we need to measure soil organic carbon (SOC) which currently involves significant manual labor and high lab costs. This paper investigates the application of machine learning to satellite imagery (Remote Sensing) to approximate the amount of soil organic carbon, which would significantly decrease the cost of measurement. We examine the use and limitation of three different leading soil characterization datasets, combined with data from Landsat 7, Sentinel-1, and Sentinel-2. In addition, we investigate the use of various spectral indices and features to improve model performance. Our best model achieved an R$^2$ of 0.534 on an unseen test set.

## Simulated Autonomous Vehicle Parking: Examining Model-Based and Model-Free Reinforcement Learning Methods

**Abstract:** We present various approaches for autonomous vehicle parking using model-based and model-free reinforcement learning methods. The vehicle autonomously explores a parking lot through turning maneuvers. The car observes an x-coordinate, y-coordinate, x-velocity, y-velocity, cos (heading angle) and sin (heading angle) at every step. Our reward dynamics model then guides learning by calculating weighted L1 p-norm between the state and the goal. We use a random baseline and Lookahead with Rollout, Forward Search, Monte Carlo Tree Search, and Soft Actor-Critic (SAC) as our other methods. We then used four metrics to compare these methods: the maximum reward received, the sum of the reward received, the agent’s success ratio, and the mean number of steps taken to park in successful scenarios. Altogether, this paper successfully applies reinforcement learning techniques to train a car in a simulated environment.
