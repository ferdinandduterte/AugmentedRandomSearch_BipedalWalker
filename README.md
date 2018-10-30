# AugmentedRandomSearch_BipedalWalker
Teaching BipedalWalker how to walk using Augmented Random Search Algorithm

![demo](https://github.com/ferdinandduterte/AugmentedRandomSearch_BipedalWalker/blob/master/AugmentedRandomSearch_BipedalWalker.gif)

## SETUP:
    1. `pip install gym` to install OpenAI gym environment
    2. To make the BipedalWalker working, install Box2D following this guide : https://github.com/pybox2d/pybox2d/blob/master/INSTALL.md
    3. To handle video esp video recording, install FFmpeg following this guide: https://github.com/adaptlearning/adapt_authoring/wiki/Installing-FFmpeg
    
## SETUP Problems: (You might experience this issues most especially Windows User)
    1. AttributeError: module '_Box2D' has no attribute 'RAND_LIMIT_swigconstant'
       Fix: `pip install box2d box2d-kengz`

## RUNNING:
    a. 'python AugmentedRandomSearch_BipedalWalker.py'
    b. 'python AugmentedRandomSearch_BipedalWalker.py --steps=2000' , where steps = number of trials before bipedal walker stops training
    
## CREDITS:
    - Codes from: https://github.com/colinskow/move37/tree/master/ars
