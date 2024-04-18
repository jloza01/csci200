# Workflow Outline
##  *Exploring the question if machine learning models can create new pokemon based on the images given. 

1. **Exploratory Data Analysis (EDA)**
  - I will check for missing and duplicate data (although there shouldn't be any)
  - I will look at the images and see the information that is attached to it
2. **Data Cleaning**
  - All 809 Images are pretty clean,same size, all have white backgrounds and have the pokemons

  - Because the dataset is small I will need to create more images using the images I have (possibly just varying colors, contrasts, zooming in to the pictures, rotating, etc) to enlarge the dataset
3. **Model Selection**
  - I would like to use a Generative Adversarial Network (GAN), Variational Autoencoder (VAE),
  and a Convolutional Neural Network (CNN) to work with my data set. These all work well for image generation which is cool
4. **Model Training**
  - I would split the data into train/
5. **Model Evaluation**
  - In order to evaluate the model we will look at the images generated at each epoch to see it's progress.
  - I will attempt to optimize the GAN model by tuning either adding layers, changing loss functions in the layers, and changing learning rate. 
  - There is not a good way to measure accuracy for this specific model except for just looking at the final images that the data comes up with and comparing to the pictures given

* For the purpose of time for the class I will only focus on this for the remainder of the semester then add on when necessary

Outside Scope Ideas:
- With the images given, create a model to see what type of pokémon would be, given that it is also fairly accurate with the other data.
- Make a model to see how data would be clustered especially when  (new pokémon included)