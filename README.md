# Adapter-Tuning for Empathy Prediction

For this project we have used Adapter-Tuning for Empathy Prediction
We have used two methods EmotionStack and EpitomeFusion


## EmotionStack

[EmotionStack_EMP.ipynb](./EmotionStack_EMP.ipynb): This code is used to predict the Empathy and Distress scores using EmotionStack approach. By changing prediction_task parameter in the code you candeside for Empathy or Distress. 

[EmotionStack_EMO.ipynb](./EmotionStack_EMO.ipynb): This code is used to predict the Emotion using EmotionStack approach.

## EpitomeFusion

[Train_Empathy_Adapters.ipynb](./Train_Empathy_Adapters.ipynb): The code here is to create of three different aspects for interpretation, Emotional and Exploration. In which you can change adapter name to generate aspects for others.

[EpitomeFusion.ipynb](./EpitomeFusion.ipynb): Code for predicting the emotion labels at essay level using the EpitomeFusion approach.

[aug_data_file.ipynb](./aug_data_file.ipynb): This file is to create augmented data I have used valid set of 270 sentences and   dataset by replacing created replacing nouns , verbs and both. Also done swaping saved them in [aug_data](./aug_data/).

[tranlate_data.ipynb](./tranlate_data.ipynb): This file is to create Translate data I have used valid set of 270 sentences and created some languages translated datasets. Saved them in [t_data](./t_data/)

[Empathy_Distress_Inference.ipynb](./Empathy_Distress_Inference.ipynb): In this file I have checked the performance of my model with robustness. 

[Empaty-Disstress-Score-Prediction.ipynb](./Empaty-Disstress-Score-Prediction.ipynb): In this I have trained the multilingual model. Saved model size is arround 1 gb and there are 4 models. So I didn't upload them. 
I have created 4 of them by changing data set from only englist to dataset of (hindi telugu and english) which is [data](./t_data/final_data_some_lang.tsv). and task Empathy or Distress.

[one_short_with_eng.ipynb](./one_short_with_eng.ipynb): To check preformance of my multilingual model (which is trained with only english data) with some language texts.

[one_short_with_multi.ipynb](./one_short_with_multi.ipynb): To check preformance of my multilingual model (which is trained with hindi telugu and english data) with some language texts.

[case_test.ipynb](./case_test.ipynb): In this I have taken some five texts from valid set and done some changes and seen how the prediction score is changing for them.