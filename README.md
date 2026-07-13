**Plant Diseases Classification Model**

This is an image classification model that detects disease in plants by their leaves. It uses Jetson Inference and ResNet.

Run with this command:

NET=project/final_project
DATASET=project/plant_diseases
imagenet.py --model=$NET/final_project.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/INPUTFILENAME.JPG OUTPUTFILENAME.JPG

https://drive.google.com/file/d/1GQLZmMqYM3znhr8KFTVQlsAdn8KRG1xz/view?usp=sharing
