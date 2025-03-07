# Intelligent-Systems
## Overview
A NTOU-NCE Master's course. There are three projects which use three different intelligent system theories, including fuzzy theory, evolutionary algorithm and backpropagation neural networks. These projects are not completed by Matlab toolbox, instead, by my own programming skill.
>

## Mind Map
![](https://github.com/tailer954/Intelligent-Systems/blob/master/%E6%99%BA%E6%85%A7%E5%9E%8B%E7%B3%BB%E7%B5%B1%E6%A6%82%E8%AB%96.png)
>

## Course Content
- Fuzzy theory
- Evolutionary algorithm
- Backpropagation neural networks (BPNN)
- Mixed systems
>

## Project 01 : Fuzzy theory
- Goal :    
Complete fuzzy control of a microwave oven. This microwave oven has interesting features. The sensors which mounted on this microwave oven can detect temp and weight. Using fuzzy theory, it can automatically compute, get the moderate power and operation time, and heat the food according to the calculation results. These features can reduce the time when we use it to heat food. We just push a button, and the food would be heated correctly. According to the fuzzy rules and membership functions, using COG to defuzzy, and depending on the defuzzification, plot two charts.
>
- Fuzzy Rules :   
R^1: If temp is low and weight is heavy. Then op-time is long and power is high.  
R^2: If temp is low and weight is medium. Then op-time is medium and power is high.  
R^3: If temp is low and weight is light. Then op-time is short and power is high.  
R^4: If temp is medium and weight is heavy. Then op-time is long and power is medium.  
R^5: If temp is medium and weight is medium. Then op-time is medium and power is medium.  
R^6: If temp is medium and weight is light. Then op-time is short and power is medium.  
R^7: If temp is high and weight is heavy. Then op-time is long and power is low.  
R^8: If temp is high and weight is medium. Then op-time is medium and power is low.  
R^9: If temp is high and weight is light. Then op-time is short and power is low.  

>
- Result : ![](https://github.com/tailer954/Intelligent-Systems/blob/master/Fuzzy%20System/Result.PNG)
>

## Project 02 : Evolutionary algorithm
- Goal :    
A function : f(x) = -15*sin^2⁡(2x)-(x-2)^2+160. Find the x such that f(x) is global maximum instead of local maximum. The x domain is from minus ten to plus ten. Set up the population sizes are 10, cross over rate is 0.8, and mutation rate is 0.01. In addition, the population precision is 10 bits when using binary code genetic algorithm.
>
- Function of this Problem :    
![](https://github.com/tailer954/Intelligent-Systems/blob/master/Evolutionary%20Computation/Function%20of%20this%20Problem.png)
>
- Result :    
![](https://github.com/tailer954/Intelligent-Systems/blob/master/Evolutionary%20Computation/Result.png)
>


## Project 03 :  Backpropagation neural networks (BPNN)
>
- Goal :    
A function is f(x, y) = 5*sin(πx^2 )*sin(2πy)+1. The value of x and y are between -0.8 and 0.7. According to the coordinate points of this function, use backpropagation neural network to train an approximate nonlinear function model.
>
- Function of this Problem :    
![](https://github.com/tailer954/Intelligent-Systems/blob/master/Neural%20Networks/Function%20of%20this%20Problem.png)
>
- Result : ![](https://github.com/tailer954/Intelligent-Systems/blob/master/Neural%20Networks/Result.PNG)
>
