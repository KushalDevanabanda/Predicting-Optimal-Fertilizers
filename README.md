# Predicting Optimal Fertilizers - A Kaggle Competition
The Playground Series is a collection of beginner-friendly Kaggle competitions designed to help individuals practice and enhance their data science and machine learning skills. These competitions feature synthetic, tabular datasets that are ideal for learning and experimentation.

I have participated in the sixth competition of this series, where the objective is to select the best fertilizer for different weather, soil conditions and crops. This is a multi‑class classification challenge with several fertilizer categories to predict. This competition was great in order to learn about applying classical ML methods on a large-scale, well-defined problem. Even though the data was synthetic but it was realistic, mimicking agriculture scenarios to enhance domain understanding. The community was incredibly supportive, generously sharing their insights and results, which helped me improve my models significantly.

**Final Result**: **82** out of **2648**. Public score: **0.38304**, Private score: **0.38308**.

You can find the final submission in the link given here: https://www.kaggle.com/code/kushaldevanabanda/test-20

You can find the competition details in the link given here: https://www.kaggle.com/competitions/playground-series-s5e6/overview

To tackle this multi-class classification challenge, I experimented with multiple machine learning models like XGBoost and other tree-based methods. I created multiple results by changing the parameters. After evaluating their performance, I combined the predictions from my best models with selected high-performing public solutions shared by the Kaggle community.

Using an ensemble strategy, I aggregated the outputs to create a robust final submission. This blend of personal experimentation and community-driven insights significantly boosted the performance of my final submitted solution. I would like to thank the Kaggle community for all their support and for helping me achieve a higher result.

**Missed Opportunities**

While I explored a variety of classical machine learning models and ensemble techniques, I did not experiment with deep learning approaches such as kNN, which could have potentially improved performance. Additionally, I didn’t explore automated feature selection or advanced data augmentation techniques, which might have further boosted model robustness.

**Approaches that did not work for me**
1. Creating new features such as combining nitrogen, potassium, and phosphorus values or generating interaction features like crop_type × soil_type did not lead to performance improvements. In fact, these additions negatively impacted the model's accuracy and resulted in poorer outcomes.
2. Creating a single script to train multiple models and perform stacking in one go did not yield good results. Instead, training individual models separately and then combining their predictions through a dedicated stacking pipeline proved to be more effective.

**Key Takeaways**
1. Ensembling works: Combining multiple models, especially through stacking, significantly improved performance over individual models.
2. Community collaboration is powerful: Leveraging publicly shared solutions and blending them with personal models was highly effective.
4. Feature engineering needs caution: Not all new features are helpful—some combinations degrade model performance.
5. Deep learning is worth exploring: Skipping neural networks may have limited further gains, incorporating them could be a future step.
6. Pipeline design matters: Building and testing models independently before stacking led to better control and results than trying to automate everything in a single run.

I have attached the final files to this GitHub repository. The zip file contains all the models and results that I have used in the competition. I hope my work proves helpful in generating new ideas and methods of approach, and helps in any way possible.

Huge thanks to the organizers of the Playground Series for creating such a supportive and engaging environment. These competitions provide a fantastic opportunity to learn, experiment, and grow in the field of data science. I'm grateful for the chance to participate and improve through hands-on practice.
