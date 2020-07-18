# bert-mrcp
simple code for bert [BERT](https://github.com/google-research/bert) language model in Java.

Steps to follow

```
Put 2 sentences in pyscrips/sentences.txt
run tokencreater.py (python tokencreater.py)
mvn -q compile exec:java (in main folder)

```

$ ./run.sh 
Sent1 =  "On June 10 , the ship 's owners had published an advertisement on the Internet , offering the explosives for sale ."

----------------------------------------
Sent2 =  "They had published an advertisement on the Internet on June 10 , offering the cargo for sale , he added ."

WARNING:tensorflow:From /Users/nidhi/Desktop/ipsoft/pyscrips/tokenization.py:126: The name tf.gfile.GFile is deprecated. Please use tf.io.gfile.GFile instead.

/Users/nidhi/Desktop/ipsoft

Java TensorFlow Version = 1.15.0
2020-07-18 16:13:17.125962: I tensorflow/cc/saved_model/reader.cc:31] Reading SavedModel from: /Users/nidhi/Desktop/ipsoft/pbmodelfile
2020-07-18 16:13:17.146668: I tensorflow/cc/saved_model/reader.cc:54] Reading meta graph with tags { serve }
2020-07-18 16:13:17.171712: I tensorflow/core/platform/cpu_feature_guard.cc:142] Your CPU supports instructions that this TensorFlow binary was not compiled to use: AVX2 FMA
2020-07-18 16:13:17.186628: I tensorflow/compiler/xla/service/service.cc:168] XLA service 0x7facb77c2c20 initialized for platform Host (this does not guarantee that XLA will be used). Devices:
2020-07-18 16:13:17.186663: I tensorflow/compiler/xla/service/service.cc:176]   StreamExecutor device (0): Host, Default Version
2020-07-18 16:13:17.247789: I tensorflow/cc/saved_model/loader.cc:202] Restoring SavedModel bundle.
2020-07-18 16:13:17.736776: I tensorflow/cc/saved_model/loader.cc:151] Running initialization op on SavedModel bundle at path: /Users/nidhi/Desktop/ipsoft/pbmodelfile
2020-07-18 16:13:17.830400: I tensorflow/cc/saved_model/loader.cc:311] SavedModel load for tags { serve }; Status: success. Took 704431 microseconds.


Given senetences are simmilar with probability - 0.90365493




## Issues
If you find issue please let me know at nidhi81194@gmail.com
