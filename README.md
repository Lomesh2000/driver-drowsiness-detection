# Driver-Drowsiness-Detection

## Applications 🎯
This can be used by riders who tend to drive for a longer period of time that may lead to accidents

### Description 📌
A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy

### Packages used 🧗‍♂️
1)  `opencv-python`
2)  `tensorflow`
3)  `keras`
4)  `numpy`
5)  `flask`
6)  `numpy`   
7)  `pygame`

# Drowsiness Detection WebAPP
<img src="latest.gif" width="300" height="430">

# MODEL ARCHITECTURE
![](images-gifs/new_model.jpg.png)

# Algorithm 
Here we are keeping a score(with a variable `score`) for the closed and opened eye predicted frames by the model.
`score` variable is decreased by 1 when opened eyes are predicted and increased by 1 if closed eyes are predicted.
If model predicted five consecutive `drowsy`(or closed eyes) frames then it will raise an alarm and will give a warning 


### Execution 🐉
To run the code, type `python app.py`

```
python app.py
```

