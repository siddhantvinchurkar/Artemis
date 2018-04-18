![Artemis](https://u.imageresize.org/5f5779be-6ec1-4e6a-9703-20ba9c4f993f.png "Artemis")
# Artemis

Artemis is an artificially intelligent chatbot trained on the [Cornell Movie-Dialog Corpus dataset](http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html "Cornell Movie-Dialog Corpus dataset").

Check it out over [here](https:artemisai.tk)!

# Quick Start

### Linux
1. *Clone this repository*

&nbsp;&nbsp;&nbsp;**user@somecomputer:~$** ```git clone https://github.com/siddhantvinchurkar/Artemis.git```

2. *Change the directory*

&nbsp;&nbsp;&nbsp;**user@somecomputer:~$** ```cd Artemis/```

3. *Make sure **[TensorFlow](https://www.tensorflow.org/)** is up and running*

&nbsp;&nbsp;&nbsp;**user@somecomputer:~$** ```source ~/tensorflow/bin/activate```

&nbsp;&nbsp;&nbsp;\* The path to the tensorflow directory may be different for you.

4. *Make sure you have all the required packages*

&nbsp;&nbsp;&nbsp;**(tensorflow)user@somecomputer:~$** ```pip install numpy scipy six```

5. *To test the bot out in the terminal use the following command →*

&nbsp;&nbsp;&nbsp;**(tensorflow)user@somecomputer:~$** ```python3 execute.py```

6. *To test the bot out in a browser use the following command →*

&nbsp;&nbsp;&nbsp;**(tensorflow)user@somecomputer:~$** ```python3 app.py```

&nbsp;&nbsp;&nbsp;and then head over to [http://localhost:7000](http://localhost:7000)

__***Pro Tip: ***__ Use the following command to run the server in the background →

&nbsp;&nbsp;&nbsp;**(tensorflow)user@somecomputer:~$** ```python3 app.py & disown```
