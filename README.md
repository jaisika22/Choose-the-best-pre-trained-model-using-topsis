# Choose-the-best-pre-trained-model-using-topsis
### Model : Text Sentence Similarity
### Link to finding pre-trained models : https://huggingface.co/models

## Models used:
1. sentence-transformers/all-MiniLM-L6-v2
2. sentence-transformers/all-mpnet-base-v2
3. allganize/msmarco-distilbert-cos-v5_en-ko-ja_v1.2
4. DangFutures/fine_bge_fed
5. zoukagh/bethiz-bert-similarity-sentences2
6. LazarusNLP/all-indobert-base-v2
   
## Parameters considered:
1. Cosine_similarity
2. Euclidean_distance
3. Manhattan_distance
4. Minkowski_distance
5. Correlation_coefficient

## After implementing TOPSIS:
You can see topsis score in your dataframe

![image](https://github.com/jaisika22/Choose-the-best-pre-trained-model-using-topsis/assets/107528387/d423d660-b00d-476b-bb43-56cc027dc093)

You can see topsis rank in your dataframe

![image](https://github.com/jaisika22/Choose-the-best-pre-trained-model-using-topsis/assets/107528387/69327d5a-466f-4272-a39c-048ce4217c00)

## Representation of Topsis score and rank of various models:

Visualization of score

![image](https://github.com/jaisika22/Choose-the-best-pre-trained-model-using-topsis/assets/107528387/4f93a4ad-5bb0-4f6f-86d5-20f9b9695e13)

Visualization of rank

![image](https://github.com/jaisika22/Choose-the-best-pre-trained-model-using-topsis/assets/107528387/0f51c120-9a1c-457a-9431-95707959bf39)
