Deep Q Network to train a Cart Pole - v1. 

### Problem
The problem was to balance a cart using Deep Q Network Learning. The state parameters are the 4 tuple: 
- Cart position
- Cart velocity
- Pole angle
- Pole velocity (angular)

The actions are only of two kinds, involving pushing or pulling the cart. 

The objective is to keep the pole straight and apart from falling for as long as possible. Each time we keep this pole stable, we get +1 reward. The problem is considered solved if the average of 100 trials is more than 475.
