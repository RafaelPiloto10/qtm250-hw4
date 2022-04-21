# Google Cloud Speech-to-Text API

## Speech-to-Text API Overview:

![ speech-to-text transcript Google API ](https://i.imgur.com/RNFxm6V.png)

Google's machine learning Speech-to-Text API accurately converts speech into text using an API powered by Google’s AI technologies.
It applies Google's most advanced deep learning neural network algorithms for automatic speech recognition (ASR) and enables experimentation,
creation and management of custom resources.

## What We Are Trying to Discover:

We are interested in the correctness of speech-to-text results for people with different backgrounds and accents in English.
We hypothesize that speech-to-text is less efficient for people who have accents.

- Hamlet1.wav:
  - Recorded with an Indian accent
- Hamlet2.wav:
  - Recorded with an Asian accent
- Hamlet2.wav:
  - Recorded with an Asian accent

# Results

![Percent of errors across non-native English speakers transcribed by speech-to-text transcript Google API ](https://i.imgur.com/5qxIyra.png)

According to a survey done in 2020 on the accuracy of speech-to-text transcript APIs,
Amazon had an accuracy of 73%, Microsoft had an accuracy of 78% accurate, and Google came in first at 79%.
Using the highly accurate Google speech-to-text transcript API, we are interested in testing its efficiency for
non-native English speakers with different accents. We hypothesize that the speech-to-text accuracy is lower for
non-native English speakers and positively correlated with the number of years spent learning English. The results
show that the errors made by the recruited participants are mostly lower than the literature average of Google API
speech-to-text transcript, at 10.5%, 22,9%,17.4% compared to the reported 21%. These results refute our hypothesis
and shows that Google API speech-to-text transcript service is not less accurate among non-native speakers. Interestingly,
we found no correlation between the number of years spent learning English and the accuracy of the transcript. However, with
the limited number of participants, selection bias of the participants, and potential confounded variables in the reported years
spent learning English, these findings need to be replicated with a larger sample size under a more controlled survey setting for
statistically meaningful interpretation.
