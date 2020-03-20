# Application1
First App
import json

data = json.load(open("D:\Desktop\python\Application1\data.json"))

def translate(word):
    return data[word]

word = input("Enter the word: ")

print(translate(word))
