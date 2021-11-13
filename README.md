# Questions-Game-ML
## 20 Questions Game using Machine Learning and decision tree model
ML program that play against the user and trying to guess which sports the user thought about. 

## Flow
- Reads data frov CSV file and arrange it.

![image](https://user-images.githubusercontent.com/70321869/141645091-c3b3430c-58d7-458a-a5e0-2430e06fa356.png)


- Create Decision-Tree model.

![image](https://user-images.githubusercontent.com/70321869/141645097-40cd91dd-71d2-496a-8437-210f0bba2278.png)

- Ask the user all kinds of questions.

![image](https://user-images.githubusercontent.com/70321869/141645110-d087df3c-41d2-4b2b-9ab1-a56f427ba838.png)

- Predict what the user tought about using the questions asked as the features of the model.

![image](https://user-images.githubusercontent.com/70321869/141645124-273dfa4f-380a-4324-bb8f-2894c5120600.png)

- Update the model, and save new data to the data base.

![image](https://user-images.githubusercontent.com/70321869/141645130-139f146c-796a-4c3e-8009-5389e07722bd.png)

### _All the flow of the program including the code itself is in the Game.ipynb file added_

## Tech
- The code was written in Python on Jupyter Notebook.
- Data arrangmant by Pandas.
- Decision Tree Model by Sklearn.
- Visualisation by Graphviz.

## Next version
- After get more data from users I will add the abilty to ask the user only the questions needed to determine the prediction. (traverse only the nodes exsists in the Desicion tree at the moment).
- Expend the program to every field(peoples, places and more) and not only for Sports.
To do so I will change the program to ask the users only the most 20's important features/questions and expend my questions data base to be much bigger than 20. 
Than the program will be stil limited to 20 questions but the structure of the questions would be nested.(Example:Does it in the kitchen?-> is it used for eat?-> is it spoon? and not just genral questions).

## Run it yourself!
- if you want to run it, download "Game.ipynb file", and the database included, run, and start playing.
