# Mushroom Toxicity
### Team: Aaron Robertson, Beverly Thompson and Essi Monneus

## Background
As eating healthy is on the rise, everyone is trying to be as natural as possible; even growing their own food. Mushroom starter kits are even available on the market. How do we know if we can safely enjoy our fabulous fungi? Machine learning can be used to help classify typical characteristics that can help determine which are the most dangerous and should be avoided.

## Project Tasks
In this project, we were tasked with demystifying ML (Machine Learning). First we needed to find a problem that was worth solving, analyzing or visualizing; in our case, we chose the topic of mushroom toxicity. We would need to use a machine learning library such as Scikit-Learn to help with this process. To add to this, we would need to use at least two other tools. Below is a list of the tools we utilized:  
* Python Pandas
* Python Matplotlib
* Python Seaborn
* HTML/CSS/Bootstrap
* JavaScript Plotly
* JavaScript D3.js
* Jupyter Notebook

Finally, we would need to host our application using Heroku or a tool of our choice. We chose right here on Github using Github Pages. 

## Our Proposal/Presentation
You can find our proposal based on the above background [here](Proposal.md).

We also have a [slideshow](https://docs.google.com/presentation/d/10ECGgO3wZVm5tsjuCCfcwhFFtnVVg3l6xVniVA0MjBk/edit?usp=sharing) that highlights what we did along with our findings, difficulties encountered, and how we would work to enhance this project in the future.

## Future Enhancements
Speaking of future enhancements, here are some features we would like to implement in the future given more time:
* Mushroom Image Scanner: Is my mushroom edible or poisonous?
    * We would like to add a feature that collects images of mushrooms utilizing the scientific name. We would then collect data that compares the scientific name to its corresponding common name and any statistics about each mushroom. The images would then be utilized to train machine learning models to identify the scientific name of a mushroom image presented before displaying information about that mushroom. Example information would include displaying the common name  and whether it is edible or not.
* Machine Learning Improvements
    * Currently, two of the models we used for machine learning came out with identical results. In the future, we would investigate the Random Forest and K-Nearest Neighbor models to determine the cause of these identical scores.
* Sunburst Chart Popovers
    * We would enhance the sunburst chart by adding a feature where if you click on a genera or species, a popover would come on screen providing a link to MycoBank or any other hub providing more information on the mushroom. 

## Data Resources
* [Kaggle Dataset](https://www.kaggle.com/uciml/mushroom-classification)
* [2021 Mushroom Classification Publication](https://onlinelibrary.wiley.com/doi/full/10.1111/1541-4337.12708)
