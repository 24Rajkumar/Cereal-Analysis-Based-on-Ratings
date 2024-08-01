# Cereal-Analysis-Based-on-Ratings
CEREAL ANALYSIS BASED ON RATINGS BY USING MACHINE LEARNING A customer wants to buy some food items with high dietary benefits so that he wants to know which food item has high dietary benefits. It is so difficult to choose an item .Usually a customer expects to consume dietary cereals with high proteins, fiber and low sugars, fats. Predicting a brand with high dietary cereals became a big issue.

The project objective is to find the high dietary food that is predicted on the basis of rating of the food.

1.To find which quantities are showing more impact on the rating of food.

2.To show the food which is impacting less on the rating of food?

We use machine learning algorithms to predict the food with a high beneficiary diet. The model can predict the rating of the food more accurately by giving the inputs which are the cereals and ingredients present in the food. Thus a customer can get high dietary food by the rating of the food given to it from the cereals and ingredients present. The rating is predicted using the neural networks model. We can make a summary table based on the above observation: Cereal Least content Highest content Fat All-Bran_with_Extra_Fiber 100%_Natural_Bran Calories All-Bran_with_Extra_Fiber Mueslix_Crispy Protein Cap'n'Crunch Cheerios Carbo Quaker_Oatmeal Rice_Chex Vitamin 100%_Natural_Bran Just_Right_Crunchy__Nugget Fiber Cap'n'Crunch All-Bran_with_Extra_Fiber Potassium Almond_Delight All-Bran_with_Extra_Fiber Sugars Quaker_Oatmeal Golden_Crisp Rating Cap'n'Crunch All-Bran_with_Extra_Fiber

Conclusion: It is interesting to see here that the highest rating if for the Cereal with the least content of Fat and Calories not with the highest amount of protein and vitamin.

Analysis : Finding cereals considered Good based on factors

Calories vs Protein vs Sugar

We see not a lot of cereals fall are in the area with high protein, low calories and low sugar content. The only cereal (row 4) is “All-Bran_with_extra_fiber”.

Sugar vs Sodium

From this Graph of Sugar vs Sodium content , the left down corner represents the cereals with low sodium and Sugar content and can be considered Good. These are Quaker Oatmeal, Puffed Rice,Great_Grains_Pecan, Maypo,Cream of wheat, All-bran_with_extra-Fiber.

The right top portion of this graph represents the cereals with high Sugar and sodium content and should be avoided specially by people with high blood pressure, kideney disease and diabetic patients

Analysis of the factors affecting the Rating

Further to this, we can use simple regression analysis to see which factor is most important in deciding the ratings. Calories vs Rating
The scatter plot shows that there is statistically good relationship between the calories and rating although it is not strictly linear. As the Calories content increases the rating decreases. Thus it supports our previous observation that the highest rating is for the cereal with the least calorie content. However, by identifying the points we find that the two cereals puffed Rice and puffed wheat although having least calorie content doesn’t have very good rating. It would be interesting to find the reason whether this because of the low content of protein or vitamins in these cereal or less advertisements and popularity.
By identifying the row number for these cereals from the scatter plot we extract other attributes of these three cereals and compare to see although having the same calorie content what factors make the “ All-Bran_with_extra_Fiber“ have the much higher rating compared to “Puffed_Wheat” and “Puffed_Rice”.
