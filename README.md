# Armed-unarmed-person-detection-with-YOLOv8n
Roboflow platformundan almış olduğum hazır veri seti ile YOLOv8 modelini kullanarak webcamden alınan görüntü üzerinde silahlı ve silahsız insan tespiti yaptım. 

(I used a pre-made dataset from the Roboflow platform and the YOLOv8 model to detect armed and unarmed individuals in real-time using a webcam.)

1. Mount Google Drive and define root directory which contains the path of the project in Google Drive. The arrangement may need to be adjusted according to the path of your own project.
<img src="mount.png" width="auto">

2. Install ultralytics and load pre-trained model. You can choose your model version according to your needs, I preferred the YOLOv8n model because of its speed then train the model.
<img src="resim_2024-08-14_185939440.png" width="auto">
You need to configure your YAML file according to the paths of the training, test, and validation data in your project. For example;
<img src="[resim_2024-08-14_185939440.png](https://github.com/bensubayir/Armed---unarmed-person-detection-with-YOLOv8n/blob/main/data.yaml)" width="auto">
