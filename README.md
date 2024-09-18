# Classification and Clustering of Anuran Frog Species
### 23-2 통계학 세미나 기말 프로젝트    
***
데이터 출처 : https://archive.ics.uci.edu/dataset/406/anuran+calls+mfccs

## Visualization
### 1. PCA
<center>
  <img src="https://github.com/user-attachments/assets/2844cfa8-143d-4ac6-b126-a8011df6cf75" width="300" height="300">
  <img src="https://github.com/user-attachments/assets/267c624a-10fc-4ed6-89f7-e0f2c5af1d4b" width="300" height="300">
</center>
<br>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Comp1 ~ Comp4 : 76%
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Comp1 ~ Comp8 : 91%

### 2. RandomForest result tour
<img src="https://github.com/user-attachments/assets/a058e2d0-b089-4312-8524-d7c4ceac5294" width="300" height="300">
<br>
- Species 분류 예측값 시각화<br>
- 점들이 삼각형들의 코너에 많이 분포할수록 예측력 높음

### 3. LDA
<img src="https://github.com/user-attachments/assets/91f02dac-50c0-4f44-966d-69c9bccdd845" width="400" height="280">

### 4. SVM
<img src="https://github.com/user-attachments/assets/ddccff29-3b53-4584-a186-72763984b5dc" width="300" height="300">
<br>
- x 표시 : SVM boundary

### 5. Clustering
<img src="https://github.com/user-attachments/assets/f4e7648e-8b5e-4ce4-9c41-f6fc7b3a2acb" width="300" height="300">
<img src="https://github.com/user-attachments/assets/101b6daf-7464-436b-9642-f0b949fb6738" width="300" height="300">
<br>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp True cluster
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Mclust
<br>
<img src="https://github.com/user-attachments/assets/1a6386cb-e0fe-41b3-aca6-f1ad234f39e1" width="300" height="300">
<img src="https://github.com/user-attachments/assets/e0913c26-fbf4-45c2-b860-ef4d61e9cd19" width="300" height="300">
<br>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Hierarchical
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Kmeans
<br><br>
- Genus와 Family에 대해서도 동일하게 진행
