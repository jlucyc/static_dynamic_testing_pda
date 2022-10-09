### Testing task 1:
# at least six errors 
<!-- copy and paste it into another ap and run it to see what the errors could be -->
# Carry out static testing on the code below.
# Comment on any errors that you see below.
#carry out testing on card game.py use the test code and failing test to help correct
# save it in your repo and send the git hub link 
#static is comment on the error and dynamic is acutally changing it 

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1: # should be two ==
      return True
    else #missing :
      return False
   

  dif highest_card(self, card1 card2): # should be def not dif
  if card1.value > card2.value:
    return card  #should be card1
  else:
    return card2
  


def cards_total(self, cards): #should be (self, cards) 
  total                       # total = 0 here
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
#this function should be indented in line with the others above.
