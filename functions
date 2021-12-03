import time
from os import system, name
from list_of_words import words_list
from random import choice

# clear output function 
def clear(): 
    # for windows
    if name == 'nt': 
        _ = system('cls') 
    # for mac and linux
    else: 
        _ = system('clear')

def word_selection(words_list):
  #Selects a random word among the list of words (e.g. list_of_words python file)
  selected_word = choice(words_list)
  return selected_word

def word_length(selected_word):
  #Returns the length of selected word
  len_word = len(selected_word)
  return len_word

def word_shape():
  #Returns the shape of selected word
  return "_"

def loading_game():
  # Loading game animation at game start
    for x in range(0, 4):
        clear()
        loading = "Loading game" + "." * x
        print(loading, end="\r")
        time.sleep(1)
        clear()
