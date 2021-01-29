# Indonesian Hate Speech Classification

Program akan melakukan klasifikasi terhadap tweet yang dianggap ujaran kebencian (Hate Speech) atau tidak (Non Hate Speech).

Dataset yang digunakan berasal dari repositori berikut [id-hatespeech-detection](https://github.com/ialfina/id-hatespeech-detection).

[Program pertama](https://github.com/GigasTaufan/Indonesian-Hate-Speech-Classification/blob/master/Hate_Speech_Classification.ipynb) menggunakan SVM Classifier, XGBoost, dan Neural Network. Dalam prosesnya menggunakan oversampling SMOTE.

[Program kedua](https://github.com/GigasTaufan/Indonesian-Hate-Speech-Classification/blob/master/Hate_Speech_Classification-2.ipynb) menggunakan SVM Classifier, XGBoost. Tidak seperti program pertama tidak menggunakan Neural Network, serta ditambah dengan penerapan Stratified KFold CV pada SCM Classifier. Tanpa menggunakan oversampling SMOTE.
