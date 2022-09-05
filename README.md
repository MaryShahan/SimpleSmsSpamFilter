# SimpleSmsSpamFilter

We'll create a spam filter using natural language processing techniques, list comprehensions, "for" loops, "if" statements and a bit of Pandas & nltk.

Pandas is a Python library to analyze data

NLTK is a leading platform for building Python programs to work with human language data. 

DataSet including Spam and Non Spam SMS: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
This is a Comma Separated Values (CSV) file which is a plain text file that contains a list of data.

-------------
>>> import nltk
>>> sentence = """At eight o'clock on Thursday morning
... Arthur didn't feel very good."""

>>> tokens = nltk.word_tokenize(sentence)
>>> print(tokens)

['At', 'eight', "o'clock", 'on', 'Thursday', 'morning',
'Arthur', 'did', "n't", 'feel', 'very', 'good', '.']

-------------
>>> x= "My Name Is Mary"
>>> print(x.lower()) 
    my name is mary

>>> my_list = ["Mary","Minnie","Alex"]
>>> for char in my_list:
>>>print(char.lower()) 

mary , minnie , alex

>>> my_list2 = [print(char.lower()) for char in my_list]

mary, minnie, alex

-------------
The apply() method in pandas, allows you to apply a function along one of the axis of the DataFrame,


    
    
