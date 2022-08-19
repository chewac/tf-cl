# tf-cl
## tensorflow object classification from webcam with go

 What it does:

 This example uses the Tensorflow (https://www.tensorflow.org/) deep learning framework
 to classify whatever is in front of the camera.

 Download the Tensorflow "Inception" model and descriptions file from:
 https://storage.googleapis.com/download.tensorflow.org/models/inception5h.zip

 Extract the tensorflow_inception_graph.pb model file from the .zip file.

 Also extract the imagenet_comp_graph_label_strings.txt file with the descriptions.

 How to run:

 		go run ./cmd/tf-classifier/main.go 0 ~/Downloads/tensorflow_inception_graph.pb ~/Downloads/imagenet_comp_graph_label_strings.txt opencv cpu
		go run main.go 0 tensorflow_inception_graph.pb imagenet_comp_graph_label_strings.txt opencv cpu   (if downloaded files are in the same folder as main.go)
    
![Clipboard08](https://user-images.githubusercontent.com/38920548/185663018-d2660f65-17b1-4673-ad04-7aed53d2502d.png)
![Clipboard01](https://user-images.githubusercontent.com/38920548/185663029-7b322a64-f898-41f1-a3cf-b611105cdc93.png)
![Clipboard04](https://user-images.githubusercontent.com/38920548/185663035-1703f237-3111-429e-bc53-eef0f1fc20e3.png)
![Clipboard05](https://user-images.githubusercontent.com/38920548/185663038-792be4f6-a6cc-4d2e-921f-f4a8949f85b9.png)
![Clipboard06](https://user-images.githubusercontent.com/38920548/185663048-159edb84-450e-47b6-bb6a-3492c1338d91.png)
![Clipboard07](https://user-images.githubusercontent.com/38920548/185663059-6c6406d4-bcb5-4292-a6e0-5b3a737ddd17.png)
