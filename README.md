To download the dataset, please go to corresponding [Kaggle Dataset page](https://www.kaggle.com/ciplab/real-and-fake-face-detection).

# Real and Fake Face Detection
**[Computational Intelligence and Photography Lab][1]**  
Department of Computer Science, Yonsei University

![Data Samples][2]

## Fake Face Photos by Photoshop Experts

### Introduction
When using social networks, have you ever encountered a 'fake identity'? 
Anyone can create a fake profile image using image editing tools, or even using deep learning based generators.
 If you are interested in making the world wide web a better place by recognizing such fake faces, you should check this dataset. 

### What's Inside and Why
Our dataset contains expert-generated high-quality photoshopped face images.
The images are composite of different faces, separated by eyes, nose, mouth, or whole face.
You may wonder why we need these expensive images other than images automatically generated by computers.
Say we want to train a classifier for real and fake face images. 
In case of generative models like [Generative Adversarial Networks][3] (GAN), it is very easy to generate fake face images.
Then, a classifier can be trained using those images, and they do great job discriminating real and generated face images.
We can easily assume that the classifier learns some kind of pattern between images generated by GANs.
However, those patterns can be futile in front of human experts, since exquisite counterfeits by experts are created in completely different process. 
Thus we had to create our own dataset with expert level fake face photos.

### Directory and File Information
Inside the parent directory, `training_real`/`training_fake` contains real/fake face photos, respectively.
In case of fake photos, we have three groups; easy, mid, and hard (these groups are separated subjectively, so we do not recommend using them as explicit categories).
Also, you can use the filenames of fake images to see which part of faces are replaced (refer to the image below).
![Filename description.][4]


  [1]: https://sites.google.com/site/seonjookim/
  [2]: https://github.com/minostauros/Real-and-Fake-Face-Detection/raw/master/samples.jpg
  [3]: https://arxiv.org/abs/1406.2661
  [4]: https://github.com/minostauros/Real-and-Fake-Face-Detection/raw/master/filename_description.jpg
