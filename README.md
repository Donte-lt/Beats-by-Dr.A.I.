# Beats-by-Dr.A.I.
CS230 Spring22 Deep Learning project with Tracy Cai, Wilson Liang, and Donte Townes

For many people in the music industry, crafting lyrics can be a difficult feat, especially when attempting to fit within the expected tone, diction, and flow of a genre. It can also be noted that during the songwriting process the lack of ideas when starting to write lyrics for a song can make the songwriting process longer and more tedious. 
This project was deployed with the intention to aid in the crafting of song lyrics based upon an identified genre. The usage of our model would help to form ideas or lyrical motifs that tend to fit a genre in a quicker manner than traditional lyric generation, thus easing the songwriting process for many musical artists and further optimizing the songwriting process. 

Our intial model is based off HuggingFace's translation model that uses a pretrained seq2seq model to translate languages. We have tweaked this model to instead train on our data and generate the next lyrical phrase that is supposed to follow the phrase input. We currently have a very low accuracy due to training on 1 epoch, but will train for longer in subsequent models.
