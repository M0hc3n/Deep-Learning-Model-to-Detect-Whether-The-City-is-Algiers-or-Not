# Deep-Learning-Model-to-Detect-Whether-The-City-is-Algiers-or-Not
This is a simple Deep neural network trained to solve a binary classification problem, which is deciding whether some picture represent the city of Algiers or not.


## Data :
The data used was gathered using <a href="https://chrome.google.com/webstore/detail/download-all-images/ifipmflagepipjokmbdecpmjbibjnakm">Download All Images Extention</a>
The result can be found in /data folder. 

## Training:
The model used has 3 blocks of convolutional layers and Max pooling layers, The two final layers are a flatten layer and a dense one. The last layer has one unit whose objective function is Sigmoid (between 0 and 1).

The resulting plots can be found on the code file.

## Manual Testing:
When we feed the model with two pictures (one of Algiers and one of not) that can be found in /test. The result is like so:<br>

### First test:
![algiers](https://user-images.githubusercontent.com/101293365/220639911-ff1f111b-f384-44c5-8c04-3dae2cca14e7.jpg) <br><br>
The above picture is a picture of Algiers, we can see that the model has correctly predicted it <br><br>
<img width="275" alt="Screenshot 2023-02-22 145336" src="https://user-images.githubusercontent.com/101293365/220640345-e1d2ed2c-818d-48b0-873c-ad5e4580bcc9.png">
<br>

### Second test:
![not_algiers](https://user-images.githubusercontent.com/101293365/220640657-06259163-b334-46f7-9e1b-da12721c9ec2.jpg)<br><br>
The above picture is not a picture of Algiers, but rather of Constantine. We can see that the model has correctly predicted it <br><br>

<img width="263" alt="Screenshot 2023-02-22 145351" src="https://user-images.githubusercontent.com/101293365/220640786-a20e6d08-260f-4ad3-9183-4dcf332ff88f.png">
<br>
