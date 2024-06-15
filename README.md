<div align="center">
    <img src="https://github.com/Fish-Snap/fishsnap-ml/assets/65043099/363b4cca-4a5b-40d0-968a-41be24a9adf9" alt="Fish Snap - Machine Learning">
</div>

# (C241-PS013) Fish Snap - Machine Learning

<div align="justify">
  Indonesia is a maritime country and an archipelago, so it is very possible that Indonesia's livelihood is largely in the field of fisheries. There are many types of fish in Indonesia, especially marine fish.
  Because of the many types of fish, Indonesian people, especially teenagers, still do not know in depth about fisheries in Indonesia.
  To overcome this challenge and encourage interest, as well as educate the younger generation in the field of fisheries, we propose the creation of a mobile application in the field of fisheries.
  We propose to create an application that can classify fish, help the community in recommending the use of fish, and help generate income for fishermen or fish traders. Our focus is to educate the public and help fisheries practitioners.
  Our goal is to create an interactive program that can be easily accessed by everyone.
</div>
<hr style="border:1px>

### Function Dependencies

| Library | Version |
|---------|---------|
| Tensorflow | ```2.8.0``` |
| pyyaml | ```5.3.0``` |
| Roboflow | ```1.1.30``` |
| Pandas | ```2.0.3``` |
| Matplotlib | ```3.7.1``` |

<hr style="border:1px>
### Transfer Learning SSD MobileNetV2 FPNLite

<div align="justify">
    SSD MobileNetV2 FPNLite from TensorFlow Model Zoo is a machine learning method in which a SSD (Single Shot MultiBox Detector) pre-training model that uses MobileNetV2 architecture with the addition of FPNLite (Feature Pyramid Network) is adapted for object detection. In this context, SSD is an object detection algorithm that enables fast and efficient object detection, while MobileNetV2 is a lightweight neural network designed for resource-constrained devices. FPNLite, as a modification of Feature Pyramid Network, improves the model's ability to detect objects at various scales. By using pre-trained models from TensorFlow Model Zoo, users can speed up the process of developing their object detection models by utilizing pre-learned knowledge, reduce the need for large training data and computation time, and improve detection accuracy on their specific tasks.
</div>
<hr style="border:1px>

### Dataset

<div align="justify">
We augmented the dataset using Roboflow to increase its diversity. The dataset was then divided into a training set and a testing set. The training set is used to train the MobileNetV2 FPNLite SSD model, while the testing set is used to evaluate its performance.
</div><br/>

| Name Fish | Scientific Name |
|---------|---------|
| Ikan Bawal Hitam | Parastromateus niger |
| Ikan Cipa-Cipa |  Atropus armatus|
| Ikan Kembung | Rastrelliger faughni |
| Ikan Kenyar | Stripped bonito |
| Ikan Kuwe | Caranx ignobilis |
| Ikan Salem | Elagatis bipinnulata |
| Ikan Sebelah | Pardachirus marmoratus |
| Ikan Selar Bulat | Alepes djaba |
| Ikan Tenggiri Papan | Scomberomorus guttatus |
| Ikan Tuna | Thunnus albacares |

<hr style="border:1px>
## The equipment that we used

<div align="center">
  <img src="https://github.com/Fish-Snap/fishsnap-ml/assets/65043099/460357b9-43ee-4b0a-9449-8b7da13a849d" width="80px">
  <img src="https://github.com/Fish-Snap/fishsnap-ml/assets/65043099/0b4d9a33-a766-4fbe-8535-234b04779e67" width="70px">
</div> 
