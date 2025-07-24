# emotion-classification-svm
This project aims to test a Support Vector Machine (SVM) Classifier on multi-class emotion classification, using the EmoV-DB dataset. Various features are extracted from the audio data for training the classifier, including frequency-time domain and prosodic features.

The resulting performance was evaluated using several different metrics (weighted averages of precision, recall, F1 score, and overall accuracy). Confusion matrices and t-SNE graphs were used as well to visually assess the model's performance across different variations of the baseline dataset. 

Additionally, Seed Voice Conversion V1 was used on the dataset to see if emotions could be preserved and accurately assessed by the classifier post-conversion.

<b>For more information about the EmoV-DB dataset, head to the official repository:</b>
<br>[EmoV-DB](https://github.com/EmoV-DB/EmoV-DB)


<b>For more information about Seed Voice Conversion V1, head to the official repository:</b>
<br>[Seed-VC V1](https://github.com/Plachtaa/seed-vc)
