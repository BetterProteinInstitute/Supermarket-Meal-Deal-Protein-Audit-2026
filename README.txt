SUPERMARKET MEAL DEAL PROTEIN AUDIT 2026


-- OVERVIEW --
This GitHub repository contains the data collected and analysed by Macdonald & Macdonald, 2026.

The file titled 'Meal deal paper data - raw' contains the raw data collected from the meal deal items included in the study. More information about how this data collected can be found below.

The file titled 'Meal deal paper data - lightly cleaned' contains the raw data collected from the meal deal items included in the study, but which had been lightly cleaned. More infomration about how this data was cleaned can be found below.

The file titled 'Meal deal paper data - lightly cleaned - overview' contains the an overview of various pieces of the cleaned data. This includes the average protein content of a vegan and a non-vegan meal deal (weighted by supermarket and by item), the total number of products across all supermarkets and all categories, the number of mains, sides, and drinks, by supermarket as well as their totals, the average protein content of items' and supermarkets' mains, sides, and drinks, and also the ranking of the top 10% of the mains.


-- RAW DATA COLLECTION --
The audit sought to identify the meal deal items that each of the six supermarkets under study offered. 

While some supermarkets offered 'Premium meal deal's, others did not, and so it was decided that only 'Standard' meal deals at each supermarket would be included in this study to keep this uniform across all supermarkets. 

Some supermarkets also offered additional types of meal deals, such as the Waitrose 'Ready To Cook Meal Deal for 2'. These were also excluded to ensure that what was compared across supermakrets was of the same type: standard meal deals inlcuding items that did not require heating, defrosting, cooking or other similar proceesses.

For five out of the six supermarkets, meal deal items were already categorised into either 'Mains', 'Snacks' or 'Sides', and'Drinks'.

Asda's products, however, were not categorised in this way. Instead, all products were shown on the same page without indication as to the category they belonged to. Therefore, this categorisation of products into 'Mains', 'Snacks', and 'Drinks' was done manually by the researchers. Therefore, it should be recognised that this could have introduced a margin of error. Where the researchers were unsure about whether an item belonged in one category or the other, they would add a selection of items to the online 'basket' to see if this combination triggered the meal deal discount.

The protein content of each product item was identified by the researchers. They found each product's protein conrenr on the product page on the relevant supermarket's website.

In some instances, the protein content was not shown, and so the researcher put 'Unknown' in this product's cell in the data spreadsheet.

In some instances, such as the 'Deliciously Ella 50g Cacao & Almond Energy Snack Bar' from Sainsburys’, the product name included the statment that the product is 50 g. However, the mass on the packet and the weight per pack displayed on the back-of-packed label was 40g. In instances like this, the weight stated on the back of the packet was used. Similarly, in some other instances, the quantity of protein the item allegedly contained was included in the name of the item, or displayed on the packaging on the front of the item (as shown by the item's image on the supermarket website). In these instances, the protein value on the back of the packet was used in instances where these numbers differed. It should be noted that in some instances, the weight of the item may not match the weight listed on the back of the packet when the back of the packet stated one serving to be less than the weight of the item. In these instances, the mass of the item was used given that in a meal deal, the person buying the item would be buying the whole item as opposed to what the label states to be one serving worth. 

In some instances, the protein content of an item was listed as less than a particular value, such as '<0.5 g'. In these instances, the value included in the data speeadsheet was input as '<0.5' and this would be dealt with in the light cleaning of data stage. In cases where a product label stated that a product has, for example, '<0.5 g' protein per 100 g and the item was 500 g, the value inputted into the data spreadsheet was '<2.5 g' (0.5 * 5). In some instances, such as for Sainsbury's 'Tropicana Multivitamin Boost Fruit Juice 300ml', the two columns listed on the back of the packet's nutritional table were 'per 100 ml' and 'per 150 ml', and the protein content for the 'per 100 ml' was '<0.5 g', and the protein content for the '150 ml' was '0.6 g', the more definitive value of '0.6 g' was used (and multiplied by two to calculate to protein value per item, since the item was 300 ml.

In some instances, an items protein content was listed as 'negligible amount'. In these cases, the phrase 'negligible amount' was inputted into the item's cell in the data spreadsheet and dealt with in the light cleaning of data stage.

In some instances, the nutritional information on the back of a packet had two columns that both said, for example, 'per 100 ml' but had different values for the protein content in each column. In these cases, when it was obvious that one protein content was, for example, three times the value of the other, and the item's weight was 300 ml, it was assumed that the protein value that was three times greater was actually the protein value for the product as opposed to 100 ml. 

All values in the data are coloured green, apart from on two occasions. 

The first exception was for fruit. Fruit represented a unique challenge given different individual items' varied weight - despite being of the same type. Furthermore, the difference in weight of different fruit types could be significant e.g. a loose piece of fruit could range between 100 - 200 g, but since this didn't lead to a significant difference in protein value given the low protein content per 100g, every piece of fruit was listed as having a protein value of 2 grams of protein per item. This value was on the highest end of the ranges of actual protein contents when sampling some fruit products, but we selected this higher end estimate given that our findings critique low protein values, and therefore this enabled us to better stress test our hypothesis. The cases where this 2 grams of protein value was used is indicated in the data spreadsheet as it is coloured purple.

The second exception was for waters, sodas, fruit-flavoured drinks (not juices), energy drinks, iced tea, and coconut water. All of these products had protein contents of 0-1 g. Accordingly the researchers were comfortable that a generic score of 0.5 gram per product would be appropriate for representing any of these drink products. The cases where this 0.5 grams of protein value was used is indicated in the data spreadsheet as it is coloured pink.


-- DATA CLEANING PROTOCOL --
Any values that included a '<', such as '<0.5' were cleaned by removing the '<' and reducing the value by 0.1.

Any values that were listed as having a 'negligible amount' of protein per item were replaced with a value of 0.

Any values that were 'unknown' were removed entirely from the data set.

Duplicate products within one supermarket's list of items were removed.

All items were checked to see if they were in the wrong categroy. There was one occurrence of this: Tesco had one item that should have been in the 'Side' category instead in the 'Mains' column. Therefore, this was moved to the correct category.
