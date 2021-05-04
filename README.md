# NLP-Encoder-Decoder-Attention-RNN  

This code implement a sequence-to-sequence model, specifically an encoder-decoder with attention, using recurrent neural networks.  

How to run:  

1. Open google colab in the browser, click File -> Upload Notebook -> choose S2S_Enc_Dec_Att_RNN.ipynb  
2. Click runtime -> Run all  
3. In block 4: upload train.txt and test.txt  
4. In block 10: we start training the model, it takes 15-20 minutes per epoch. If you do not have time, skip it.   
5. If you skip step 4, make sure to do this step. In block 13, upload the pretrained model S2S_RNN.encoder and S2S_RNN.decoder in the folder.  
6. Then you are able to run generate() and bleu()  
