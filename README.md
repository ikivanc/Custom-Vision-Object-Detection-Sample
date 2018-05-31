# Custom Vision Object Detection
Custom Vision Services has new features, Object Detection, In this sample you'll be able to use custom vision services to detect objects in your photos.

For these photos I've used [VoTT Photo Tagging tool](https://github.com/Microsoft/VoTT)

![](screenshots/objectdetectionpipeline.png)

In order to run this notebook you need to install custom vision api

```pip install azure-cognitiveservices-vision-customvision```

This jupyter notebook helps you to upload all your photos with ROIs(Region of Interest) to apply end to end object detection pipeline.

After trained model you'll be able to predict your objects.
![](screenshots/objectdetection.png)

