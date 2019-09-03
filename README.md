# Optical-Character-Recognition
Bluid a Text recognizer that can read a document and convert to digital text


The project is sub divided into three parts

1) Character Recognition
    The dataset we will be using for this task will be EMNIST, which thanks Cohen and et al it is labelled.

    Here we experimented with 3 different architecture lenet, resnet and a custom cnn architecture

2) Line Recognition

    we will build a Line Text Recognizer. Given a image of line of words, the task will be to output what characters are present in the    line.
    We will use sliding window of CNN and LSTM along with CTC loss function which helps us a lot here


3) Line Detection in document

   The objective is to design a line detector. Given a paragraph image the model must be able to detect each line. What do you mean by detect? We will preprocess the paragraph dataset such that each pixel corresponds to either of the 3 classes i.e. 0 if it belongs to background, 1 if it belongs to odd numbered line and 2 if it belongs to even numbered line.

