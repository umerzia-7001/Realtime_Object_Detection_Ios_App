## Three seperate apps . 

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
## object_detection ;
Ios app which uses camera to detect objects in real time . It is made using COCO daatsets and can recognise upto 80 objects . 
## cats_vs_dogs :
Binary classifier ios app which detects whether given image is of dog or cat.
##  image_classification :
classifier model made using mobileNet which recognizes 1000 classes

## Following steps required to deploy any AI model on handheld device / embedded systems 
  - Making a model ( either Keras hdf5 format or binary model)
  - optimizing and testing model in the woekspace 
  - converting model in tflite format 
  - optimizarion wrt latency, space etx can be done before converting 
  - additional apis such as apiNN /. multiple threads can be utilized for better performance

## Ruuning apps ->
```
function test() {
  console.log("pip in");
}
```
