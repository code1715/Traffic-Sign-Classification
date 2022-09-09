# Traffic-Sign-Classification
Traffic sign classifier based on CNN with 97% accuracy.

## Classes
0 : Speed Limit 70
1 : Speed Limit 50
2 : Speed Limit 100
3 : No Entry
4 : Speed Limit 80
5 : Speed Limit 120
6 : RedSignal
7 : Speed Limit 30
8 : Turn Left
9 : Stop
10 : GreenSignal
11 : Road Work
12 : Right Curve Ahead
13 : Speed Limit 60
14 : Go Straight
15 : No Over Taking
16 : Danger Ahead
17 : Give Way
18 : Go Right or Straight
19 : Pedestrian
20 : Right Sharp Curve
21 : Left Sharp Curve
22 : Turn Right
23 : Snow Warning Sign
24 : No Over Taking Trucks
25 : Left Curve Ahead
26 : No Waiting
27 : Traffic Signals Ahead
28 : Slippery Road
29 : Huddle Road
30 : Deer Zone
31 : End of Right Road (Go straight)
32 : No Stopping
33 : Truck Sign
34 : Go Left or Straight
35 : Cycle Zone
36 : RoundAbout
37 : YellowSignal

## Loaded Data Example
![download](https://user-images.githubusercontent.com/47561855/189391679-c8ee6b4d-a10b-4ac4-81c3-2a965d2f934c.png)

## Model's Architecture
![download](https://user-images.githubusercontent.com/47561855/189391875-8d251819-6f15-4294-b92a-d49303e63370.png)

Optimizer: Adam; Activation functions: ReLu, SoftMax; Loss function: Categorical crossentropy.

## Confusion matrix
![download](https://user-images.githubusercontent.com/47561855/189392556-3c932cd4-0c39-424c-ad7e-94c142b68644.png)
## Training and Validation Accuracy/Loss
![download](https://user-images.githubusercontent.com/47561855/189392592-b9590a10-a056-4def-8628-8c0b28087111.png)
