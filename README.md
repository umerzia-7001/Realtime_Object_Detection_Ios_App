## ReadME

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

It is an android app which will run  a binary classifier on android (knowledge extendable to ios or raspberry )
TensorFlowLite can be used to convert TF / Keras model in a flatbuffer file which is a optimized and light weight model tat can be used on devices or embedded systems 

### Following steps required to deploy any AI model on handheld device / embedded systems 
  - Making a model ( either Keras hdf5 format or binary model)
  - optimizing and testing model in the woekspace 
  - converting model in tflite format 
  - optimizarion wrt latency, space etx can be done before converting 
  - additional apis such as apiNN can be utilized for better performance
