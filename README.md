# NBAprediction
NBA money line prediction model utilizing neural networks. This model is a binary classification nueral network using the Pytorch library using 2021-2022 NBA game data and advanced team stats. The object of the model is to predict the winner of individual games with the application of sports betting (moneyline). The model predicted the correct outcome in 67% of instances in the valudation set. 

Next steps: The next steps would be to forward test the set against 2022-2023 data and compare the model performance against odds of major sports books to see if the model has predictive value vis-a-vis sports books. The methodology for a test like this would be to convert the betting odds to probabilities and compare those to the probabilities our model generates. If the delta between these values is sufficently large at a preset threshold we will make the decision to bet on the game. If this strategy is profitable over the course of a season. We can use the model going forward.



|sports_book_implied_probability -  model_implied_probability | > threshhold_rate
