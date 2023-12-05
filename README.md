# final-project-python-mushroom

It can be challenging to determine whether a mushroom is edible or toxic without specialized knowledge. Indeed, it is crucial to assess the toxicity of mushrooms before consuming them.
Currently, there is a list of 140,000 documented mushroom species, making it difficult to recognize each variety. Distinguishing between toxic and non-toxic mushrooms can be a risky task, so it is 
the responsibility of our project to address this. During our initial research, we stopped at simple existing datasets on sites like Kaggle and others. However, none of these datasets contained images of mushrooms, 
so we had to adapt and look to another solution And that's how our research led us to the website : mushroom world.

**How can one determine the toxicity or edibility of a mushroom based on a simple photo of its physical characteristics ?**

We aim to help users visually distinguish the differences and similarities between an edible mushroom and a toxic one by a binary method. 
The application will provide a toxicity percentage for the collected mushroom.

The diferent steps in our project : 

1. find a dataset of mushroom in "Mushroom world"
2. scrap information about species, edibility (binary classify as 0=eadible and 1=poisonous) and the link to the images
3. Jason
4. convert the images to base 64 and encode it to put in a list and a dataframe
5. CNN

The problems in our project :

1.with our dataset, we only had 6000 images so we had to modify theses images by the zoom, rotation and create more and more of images to have a better result with our IA during the CNN. 
