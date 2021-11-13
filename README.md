# Questions-Game-ML
## 20 Questions Game using Machine Learning and decision tree model
ML program that plays against the user and tries to guess which sports the user thought about.
every session the program learns new information from the user input and improves itself for the next rounds.

<a href="https://github.com/yoavta/Questions-Game-ML/blob/main/Game.ipynb">Link To Notebook</a>


## Tech
- The code was written in Python on Jupyter Notebook.
- Data arrangmant by Pandas.
- Decision Tree Model by Sklearn.
- Visualisation by Graphviz.

## Next version
- After getting more data from users I will add the ability to ask the user only the questions needed to determine the prediction. (traverse only the nodes that exist in the Decision-tree at the moment).

- Expend the program to every field(peoples, places, and more) and not only for Sports.
To do so I will change the program to ask the users only the most 20's important features/questions and expand my questions database to be much bigger than 20. 
Then the program will be still limited to 20 questions but the structure of the questions would be nested. (Example: Does it in the kitchen?-> is it used for eating?-> is it spoon? and not just general questions).

## Flow
- Reads data from CSV file and arrange it.

![image](https://user-images.githubusercontent.com/70321869/141645091-c3b3430c-58d7-458a-a5e0-2430e06fa356.png)


- Create a Decision-Tree model.

![image](https://user-images.githubusercontent.com/70321869/141645097-40cd91dd-71d2-496a-8437-210f0bba2278.png)

- Ask the user all kinds of questions.

![image](https://user-images.githubusercontent.com/70321869/141645110-d087df3c-41d2-4b2b-9ab1-a56f427ba838.png)

- Predict what the user thought  about using the questions asked as the features of the model.

![image](https://user-images.githubusercontent.com/70321869/141645124-273dfa4f-380a-4324-bb8f-2894c5120600.png)

- Update the model, and save new data to the database.
- 
![image](https://user-images.githubusercontent.com/70321869/141645130-139f146c-796a-4c3e-8009-5389e07722bd.png)

### _All the flow of the program including the code itself is in the_ <a href="https://github.com/yoavta/Questions-Game-ML/blob/main/Game.ipynb">Game.ipynb file</a> _added_



## Run it yourself!
- if you want to run it, download "Game.ipynb file", and the database included, run, and start playing.
