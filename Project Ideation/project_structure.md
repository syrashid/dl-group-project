# Introduction / Background / Motivation
- Do movie posters clearly convey genre, is it learnable by a machine?
- This is important in an era of streaming where often the only thing you may look at is the poster before learning more
- This matters as it can give studios and designers insight into how to better design their posters to go with or go against conventional practices
- Now the question is how do we go about exploring this?


# Experimental Structure
- Explore current benchmarks (ML and Human)
-- If there are no human benchmarks, could pay someone like mechanical turk to do this, could add a cool dimension to our project

- Train our own models
-- Preprocess data
-- Can experiment with two different models
-- Should back justify why each model will work well or not
-- Should perform hypertuning for each model
-- Analyze results, plots plots plots
-- Comparison of the two models will provide a lot of rich insight for us to dig into, why one may outperform the other or not

- Visualize
-- Do a tsne to flatten and then use unsupervised learning to create groupings, labeling each grouping with the largest percentage of a genre could highlight interesting behaviour of what our model is seeing as well
-- Use things like Grad-CAM to better understand how our model is "seeing/focusing on" in each poster
-- Visualize activations and create plenty of these graphs
-- See what we can create ourselves through Generative Adversarial Networks


# Questions for us to Discuss
- How do we want to organize this large of a project?
-- My thought is that we can create a notebook for each of the traning model parts, at the end of each training and tuning we can extract the best model as I've done in the tarnsfer_learning_sandbox
-- Those models can be then fed into the 3 or 4 different notebooks we could have for each of the visualization tasks we have


# Rough Timeline
- Get all Experimentation / Heavy Lifting Done over the weekend
- Tune and finesse, the following monday and tuesday
- Write Write Write on wednesday and thursday
