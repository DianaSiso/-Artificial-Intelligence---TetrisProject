# ia-tetris
**Projecto de Inteligência Artificial 2021 - Tetris**

## Warning

The code is prepared to run with lookahead equal to 4, 3, 2 or 1, changing the value as the speed increases. 
Lookahead with a value of 4 does not compensate, while look ahead with a value of 3 compensates up to a certain speed value. However, we decided that in the final version we will keep a constant lookahead of value 2. 
If you want to check the program's performance with lookahead of different values, just uncomment lines 20, 129, 130, 131 and 132. 
Keep in mind that using different lookahead values allows for better results. 

```python
# limit = 3

if counter_pieces == limit:
	counter_pieces = 0
#   if gameSpeed==28:
#         limit=2
#   elif gameSpeed==50:
#         limit=1       
```

###### lookahead: number of pieces that are analyzed. 

-----------------------------------------------------------------------------------------------------------

## How to install

Make sure you are running Python 3.7 or higher

`$ pip install -r requirements.txt`

*Tip: you might want to create a virtualenv first*

## How to play

open 3 terminals:

`$ python3 server.py`

`$ python3 viewer.py`

`$ python3 client.py`

to play using the sample client make sure the client pygame window has focus

### Keys

Directions: arrows

## Debug Installation

Make sure pygame is properly installed:

python -m pygame.examples.aliens

# Tested on:
- OSX Big Sur 11.6

