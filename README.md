# computer_science_for_ba
## Assignment for the course computer science for business analytics of Erasmus University of Rotterdam.
Tamar de Haas 619082th@eur.nl

### Assignment explanation
The task was to make a scalable solution for duplicate detection using LSH. After LSH I chose to do classification using Logistic Regression with. oversampling of the minority class of the train set, because the train set was very imbalenced.

### Structure of the code
1. The packeges needed for the code are imported. 
2. The JSON file with the data is imported and changed to a pandes DataFrame type. 
3. Preprosessing of the data. 
4. All functions used, except the one for bootstrapping. 
5. Running LSH for different number of bands and making plots of the pair completeness pair quality and F1*. 
6. Classification using bootstrap method with 5 bootstraps function. 
7. Running the bootstrap function 5 times, for b=50 and b=25. 

I made the code in python notebook.
Run the code from top to bottom. 
In the code more comments are added to read the code better. 
