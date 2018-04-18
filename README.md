[![Artemis](https://u.imageresize.org/5f5779be-6ec1-4e6a-9703-20ba9c4f993f.png)](https://artemisai.tk/ "Artemis")
# [Artemis](https://artemisai.tk/ "Artemis")

Artemis is an artificially intelligent chatbot trained on the [Cornell Movie-Dialog Corpus dataset](http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html "Cornell Movie-Dialog Corpus dataset").

Check it out over [here](https:artemisai.tk "Artemis")!

# Quick Start

### Linux
1. *Clone this repository*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**user@somecomputer:~$** ```git clone https://github.com/siddhantvinchurkar/Artemis.git```

2. *Change the directory*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**user@somecomputer:~$** ```cd Artemis/```

3. *Make sure **[TensorFlow](https://www.tensorflow.org/ "TensorFlow")** is up and running*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**user@somecomputer:~$** ```source ~/tensorflow/bin/activate```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\* The path to the tensorflow directory may be different for you.

4. *Make sure you have all the required packages*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**(tensorflow)user@somecomputer:~$** ```pip install numpy scipy six```

5. *To test the bot out in the terminal use the following command →*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**(tensorflow)user@somecomputer:~$** ```python3 execute.py```

6. *To test the bot out in a browser use the following command →*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**(tensorflow)user@somecomputer:~$** ```python3 app.py```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;and then head over to [http://localhost:7000](http://localhost:7000 "localhost on port 7000")

**Pro Tip:**  *Use the following command to run the server in the background →*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**(tensorflow)user@somecomputer:~$** ```python3 app.py & disown```

# Training Artemis

If you're sitting in front of a powerful machine with [TensorFlow](https://www.tensorflow.org/ "TensorFlow") GPU installed, you can continue reading this section.

1. *Empty out the contents of the* ```working_dir/``` *directory.*

2. *If you don't want to use the [Cornell Movie-Dialog Corpus dataset](http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html "Cornell Movie-Dialog Corpus dataset") replace the contents of the* ```data/``` *directory with your own .enc and .dec files.*

3. *In the* ```seq2seq.ini``` *file, set* ```mode=train``` *and save it.*

4. *Run the following command →*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**(tensorflow)user@somecomputer:~$** ```python3 execute.py```

5. *If you're using the [Cornell Movie-Dialog Corpus dataset](http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html "Cornell Movie-Dialog Corpus dataset") to train the model on an [Nvidia Tesla K80](https://www.nvidia.com/en-us/data-center/tesla-k80/ "Nvidia Tesla K80"), about 10 hours of training should yield decent results.*

# Credits

* A cool thanks to [Suriyadeepan Ramamoorthy](https://github.com/suriyadeepan "Suriyadeepan Ramamoorthy") for writing a majority of this code.
* A shoutout to [Chris Fauerbach](https://github.com/chrisfauerbach "Chris Fauerbach") for the edits that make this code work on **[TensorFlow](https://www.tensorflow.org/ "TensorFlow") 1.7**.
* A bow to [Siraj Raval](https://github.com/llSourcell "Siraj Raval") for the amazing video on [YouTube](https://www.youtube.com/watch?v=SJDEOWLHYVo&feature=youtu.be) →

[![How to Make an Amazing Tensorflow Chatbot Easily](http://img.youtube.com/vi/SJDEOWLHYVo/0.jpg)](http://www.youtube.com/watch?v=SJDEOWLHYVo "How to Make an Amazing Tensorflow Chatbot Easily")
