In this repository, I implemented the PitchNet, a pitch classification neural network mentioned in this <a href="https://technology.mlblogs.com/@sam.sharpe">article</a> written by a data scientist from the MLB. The PitchNet is implemented using the Keras functional API and achieves a 95% accuracy on a 9-class classfication task.

The data is scraped from the baseball website <a href="https://baseballsavant.mlb.com/">Savant</a>, and includes all pitch-by-pitch data from 2014 to 2019.

The neural network takes three continuous input: the release speed, horizontal movement, and vertical movement of a pitch, and one categorical input: the pitcher's ID, which is fed into an embedding layer.

You can view the notebook [here](https://github.com/bynchang/MLB-PitchNet-Keras/blob/master/pitchnet.ipynb).
