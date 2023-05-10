# Adapter-Tuning for Empathy Prediction

For this project we have used Adapter-Tuning for Empathy Prediction
We have used two methods EmotionStack and EpitomeFusion


## EmotionStack

[EmotionStack_EMP.ipynb](./EmotionStack_EMP.ipynb): This code is used to predict the Empathy and Distress scores using EmotionStack approach. By changing prediction_task parameter in the code you candeside for Empathy or Distress. 

[EmotionStack_EMO.ipynb](./EmotionStack_EMO.ipynb): This code is used to predict the Emotion using EmotionStack approach.

## EpitomeFusion

[Train_Empathy_Adapters.ipynb](./Train_Empathy_Adapters.ipynb): The code here is to create of three different aspects for interpretation, Emotional and Exploration. In which you can change adapter name to generate aspects for others.

[EpitomeFusion.ipynb](./EpitomeFusion.ipynb): Code for predicting the emotion labels at essay level using the EpitomeFusion approach.

[aug_data_file.ipynb](./aug_data_file.ipynb): This file is to create augmented data I have used valid set of 270 sentences and created replacing nouns , verbs and both.

[Empathy_Distress_Inference.ipynb](./Empathy_Distress_Inference.ipynb): In this file I have checked the performance of my model with robustness. 

[Empaty-Disstress-Score-Prediction.ipynb](./Empaty-Disstress-Score-Prediction.ipynb): In this I have trained the multilingual model.

[one_short_with_eng.ipynb](./one_short_with_eng.ipynb): To check preformance of my multilingual model (which is trained with only english data) with some language texts.

[one_short_with_multi.ipynb](./one_short_with_multi.ipynb): To check preformance of my multilingual model (which is trained with hindi telugu and english data) with some language texts.

[case_test.ipynb](./case_test.ipynb): In this I have taken some five texts from valid set and done some changes and seen how the prediction score is changing for them.