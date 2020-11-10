# robotics2-lab6

### For this task I added two hidden layers decreasing the number of units by two at each layer. The higher number of units did not significantly improved the accuracy. 
### reluLayer was found to be an optimal activation layer(tanh did not show better results)
```
    fullyConnectedLayer(512)
    reluLayer
    fullyConnectedLayer(256)
    reluLayer
    fullyConnectedLayer(128)
    reluLayer
    fullyConnectedLayer(numClasses)  
    regressionLayer
```
### Number of epochs was increased to 20
### Final error: 0.0362
