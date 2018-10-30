# AugmentedRandomSearch_BipedalWalker
Teaching BipedalWalker how to walk using Augmented Random Search Algorithm

![demo](https://image.ibb.co/c2c9F5/ezgif_com_resize.gif)

## SETUP:
    1. `pip install gym` to install OpenAI gym environment
    2. To make the BipedalWalker working, install Box2D following this guide : https://github.com/pybox2d/pybox2d/blob/master/INSTALL.md
    3. To handle video esp video recording, install FFmpeg following this guide: https://github.com/adaptlearning/adapt_authoring/wiki/Installing-FFmpeg
    
## SETUP Problems: (You might experience this issues most especially Windows User)
    1. AttributeError: module '_Box2D' has no attribute 'RAND_LIMIT_swigconstant'
       Fix: `pip install box2d box2d-kengz`

## STEP:
    1. python AugmentedRandomSearch_BipedalWalker.py
    
## CREDITS:
    - Codes from: https://github.com/colinskow/move37/tree/master/ars
