# Knowledge-Distillation-FER

Knowledge Distillation (KD) aims to achieve mask-invariant feature vectors so that the model focuses on non-occluded regions of the face. Our approach accomplishes this by learning in concert the correct expression recognition for masked and non-masked faces and how to push the embedding vectors of masked images and corresponding non-masked images closer. It does this through embedding-level KD. KD teaches the student model to neglect non-expression related information introduced by the mask by making the student model process masked images in a manner that produces an embedding like the non-masked embedding produced by the teacher model. <br/>
  
  ## Methodology
  ![Picture2](https://user-images.githubusercontent.com/64302305/172061740-c99419e5-0361-405f-81f8-6d37c28ef20e.jpg)

## Results
![Screenshot 2022-06-05 223333](https://user-images.githubusercontent.com/64302305/172061773-b8228373-f21d-47a8-b668-c800b2fe3486.jpg)

## GradCAM
|![Screenshot 2022-06-05 223443](https://user-images.githubusercontent.com/64302305/172061929-fabfdf30-f88f-4212-afdb-18ada586ef6c.jpg)|
|:--:| 
| *Without KD* |
|![Screenshot 2022-06-05 223508](https://user-images.githubusercontent.com/64302305/172061887-33746d57-07b3-4521-8f1d-3c41ad080f22.jpg)|
| *With KD* |
