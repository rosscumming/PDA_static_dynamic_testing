### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby

class CardGame

#naming convention using _ should be used instead 'check_for_ace
  def checkforAce(card)
    if card.value = 1 #this is assigning '1' instead of comparing - needs to use == instead 
      return true
    else
      return false
    end
  end





#def is mispelled as dif
  dif highest_card(card1 card2) #there is no comma between parameters
  if card1.value > card2.value
    return card  #return in if statement missing '1'
  else
    return card2
  end
end
#there is an extra 'end' which isn't needed
end

def self.cards_total(cards)  #parameter should have * to allow multiple card entries
  total   #total is not set to  total = 0
  for card in cards
    total += card.value
    return "You have a total of" + total  #this return statement should be outside of the loop
  end
end

#there is no closing end tag for the class
```


