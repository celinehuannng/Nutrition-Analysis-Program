# Nutrition Analysis Program

Creator: Celine Huang (Student Number: 1006746327)

Course: INF1340 Programming for Data Science

Course Instructor: Professor Maher Elshakankiri


## Table of Contents
- [Explanation of the Program](#explanation-of-the-program)
- [How to Run the Program](#how-to-run-the-program)
- [Sample Input and Output](#sample-input-and-output)
- [Dataset](#dataset)
 
## Explanation of the Program 
Hello! :smile: This module provides a numerical analysis program designed for calculating and analyzing nutrition datasets.
The purpose is to provide assistance in dietary planning and to showcase patterns and trends in nutritional data.
The program features an input function for reading a dataset and output function for writing the results. 
Additionally, it also includes 8 separate defined functions: largest_value(), smallest_value(), nutrient_ratios(), mode(), median(), mean(), total_amount(), and standard_deviation(), that either process, calculate, or interpret the nutritional data. 

## How to Run the Program
When the program first runs, it will prompt the user to enter the name of the input file, which is FOOD-DATA-GROUP1,2,3,4 or 5. Afterwards, the user will then be prompted to input action commands (+, -, @, *, &, ? , $ , ! ,^, or /") to call a specific function to apply to the dataset. For instance, if the user inputs the plus sign "+", they will be prompted to enter a nutrient category from the dataset and the program will find its largest values and their corresponding foods. Once the user is satisfied with the amount of outputs that they have from the various functions that they called, they can input the carrot sign ("^") in which they will be prompted to enter the name of the output file ("specific_nutrition_info.txt"). The program will continue to run until the user enters a forward slash (/) to end the program. 

## Sample Input and Output

#### Input
Enter the file name FOOD-DATA-GROUP1,2,3,4, or 5.csv: FOOD-DATA-GROUP5.csv

actions:+

Enter the nutrition category:Fat

actions:-

Enter the nutrition category:Protein

actions:!

Enter the nutrition category:Calcium

actions:*

Enter the nutrition category:Vitamin C

actions:@

Please enter the key nutrients in pairs as suggested
1. Calcium and Magnesium
2. Potassium and Sodium
3. Zinc and Copper
4. Iron and Copper

Enter the first key nutrient (Calcium/Potassium/Zinc/Iron):Calcium

Enter the second key nutrient (Magnesium/Sodium/Copper/Copper):Magnesium

Enter the food (ex. different types of oil, bread, butter):vienna bread

actions:^

Enter the output file name specific_nutrition_info.txt:specific_nutrition_info.txt

actions:/

#### Output

Largest value of Fat:218.0, Food: ['menhaden fish oil', 'nutmeg butter oil', 'sheanut oil', 'babassu oil', 'tomatoseed oil']

Smallest value of Protein:0.0, Food: ['hazelnut oil', 'menhaden fish oil', 'cod liver fish oil', 'sardine oil', 'cupu assu oil', 'lard', 'lard vegetable oil', 'shortening', 'cottonseed oil', 'soy margarine', 'salmon fish oil', 'nutmeg butter oil', 'sour cream shoprite', 'ucuhuba butter oil', 'chicken fat', 'herring fish oil', 'bacon grease', 'turkey fat', 'beef tallow', 'goose fat', 'duck fat', 'mutton tallow', 'grapeseed oil', 'sheanut oil', 'almond oil', 'sunflower oil', 'canola oil', 'babassu oil', 'teaseed oil', 'avocado oil', 'vegetable palm kernel oil', 'coconut oil', 'safflower oil', 'vegetable oil', 'apricot kernel oil', 'peanut oil', 'poppyseed oil', 'tomatoseed oil', 'wheat germ oil', 'sesame oil', 'corn granola oil', 'cocoa butter oil', 'olive oil', 'palm kernel oil', 'mustard oil', 'rice bran oil', 'fusilli cucina', 'whole wheat bread natures own', 'high protein bread dr zaks', 'butter toastbrot ja', 'pain au chocolat de la boulangerie', 'gatto di patate home made', 'vivaldi potatoes sainsburys', 'baked chips lays', 'coleslaw dressing reduced fat', 'sorghum syrup', 'corn syrup light', 'pancake syrup', 'vinegar oil dressing', 'vinegar', 'worcestershire sauce', 'mayonnaise hellmanns', 'canadian maple syrup', 'tomato ketchup mp', 'mayonnaise dressing', 'corn syrup dark', 'cider vinegar', 'molasses', 'chow mein stir fry master foods', 'grenadine', 'soybean oil', 'soybean lecithin oil', 'soy oil']

The standard deviation of Calcium is: 84

The mode of Vitamin C is: 0

The ratio for Calcium and Magnesium of vienna bread is 1.57

Results have been written to specific_nutrition_info.txt

Program has ended

## Dataset
Utsav Dey. (2024). Food Nutrition Dataset [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/8820139




