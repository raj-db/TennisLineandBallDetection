# TennisProject
Tennis analysis using deep learning and machine learning.

![](pics/hard.gif)
![](pics/grass.gif)
![](pics/clay.gif)

### Ball detection
TrackNet was used for detecting tennis ball during the game. 

### Bounce detection
CatBoostRegressor was used to predict ball's bounces during the game based on ball trajectory detected in the previous step. 

### Court detection
It was used neural network for detection 14 points of tennis court. F
### How to run
Prepare a video file with resolution 1280x720
1. Clone the repository 
2. Run `pip install -r requirements.txt` to install packages required
3. Run `python main.py <args>`

   

