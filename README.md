# Machine-Learning-Deep
홍익대학교 기계학습심화 수업 기말 프로젝트
# Topic : Generating Synthetic Medical Images by Using GAN to Improve CNN Performance in White Blood Cell Classification
## Data
https://data.mendeley.com/datasets/snkd93bnjr/1
### Number of images per class
basophil          1219 
eosinophil       3118    
lymphocyte     1215 
monocyte        1412
neutrophil        3330
Total.               10294

## Purpose
- Deep learning is actively applied in the medical field
- Challenges in learning due to lack of high-quality data
- GANs are widely used as a solution
의료 이미지 분석을 위해서는 고해상도 이미지가 많이 필요한데 현재 의료 영상에서 고해상도 이미지를 얻는 건 어렵고 비용이 많이 든다.
따라서 딥러닝 기반 super resolution, GAN 등을 이용해 의료 고해상도의 이미지 데이터를 얻는다.

## Model
- optimizer : Adam
- loss function : binary cross entropy
![image](https://github.com/user-attachments/assets/a04b1660-3e3c-4025-9470-d3818d39b2bc)

# Results : 1200 epoch
![image](https://github.com/user-attachments/assets/5ae883f7-c0d6-4d1d-bd9a-4f0d934edae9)
