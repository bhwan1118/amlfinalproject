# Applied Machine Learning Final Project
**by Zeheng Wang and Benjamin Hwang**

### Motivation ###

Exploring ways to search for relevant images given a natural language query. For instance, if a user types "dog jumping to catch frisbee," your system will rank-order the most relevant images from a large database.

Example Training Image:

![image](https://github.com/bhwan1118/amlfinalproject/blob/master/Sample%20Training%20Image.jpg)

Relevant Training Description:

> *The skateboarder is putting on a show using the picnic table as his stage.
A skateboarder pulling tricks on top of a picnic table.
A man riding on a skateboard on top of a table.
A skate boarder doing a trick on a picnic table.
A person is riding a skateboard on a picnic table with a crowd watching.*

### Learning Goal/Objective ###

For this project we wanted to explore and experiment with relevant techniques learned throughout the semester in our Applied Machine Learning Course with the ultimate goal of better understanding how different pre-processing methodologies and training models affect performance. The metric used to benchmark our scores is the Mean Average Precision at 20 (MAP@20) which measures how accurately an image (in our application) is ranked out of 20 in terms of relevance.

## Results ##

Overall we were able to achieve a final MAP@20 score of 0.31002 on a private test set scored by our professor. This translates to an our image rankings being off on average by about 3 positions. While we wished to see better results, we were generally pleased with the outcome given the limited amount of time allotted.


For more detailed information please see our write up here: 

[Final Paper](https://github.com/bhwan1118/amlfinalproject/blob/master/FA19_AML_Final.pdf)




