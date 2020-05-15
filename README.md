# Detecting Human with Concealed Gun by Learning from YouTube's CCTV Videos

## ABSTRACT

    Nowadays, there are a lot of efforts to use intelligent algorithms to detect gun related incidents in CCTV. However, this approach cannot prevent the gun incidents before they happen. So, we present here an algorithm and the system which can detect people with concealed gun in order to early alarm before the incident happens.
    We develop the algorithm by first collecting videos of gun incidents from YouTube.com. We then prepare the dataset by dividing a video into 2 parts: the concealed gun part and the label part. After that, we use PoseFlow to track individual and train different learning algorithms on the dataset. The experiment shows that Random Forest outperforms Support Vector Machine, Decision Tree, Logistic Regression by having 77%, Accuracy, 76% Recall, 63% Precision and 69% F1-Score. 
    For the system we develop API which detects concealed gun based on Random Forest algorithm. In order to demonstrate and debug the system, we also develop the Web Application that take a video as an input and output probabilities of having concealed gun for all people in the video. Moreover, when a subject with concealed gun is detected, the system sends Line notification to the pre-configured user.
#### Keyword : Action Detection, Human Detection, Concealed Gun, Pose Analysis, Computer Vision
