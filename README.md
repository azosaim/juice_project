## Juice Project Submission

In this exploratory project I used Pandas to generate a table populated with information pulled from the Nutritionix API. I struggled, and was unable to create the application due to issues with my code, but enjoyed the puzzle. Dozens of StackOverflow tabs, Youtube tutorials and documentation dives later, I can confidently say I'm stumped. I'll now walk you through my attempt, and explain my approach. 

The project started off with an API pull, hindered by the inability to make a request that could sucessfully pull all 60 items. I was only able to gather 50 before hitting multiple request limit errors. Unfamiliar with Flask, I spent a lot of time trying to teach myself how to use it before opting for Pandas and Requests in the interest of time. I read in the Juicey Juice data, converted the JSON to a DF and cleaned up the columns without too much issue. I then backed up my DF, and began experimenting. 

## Total Number of Products
The website lists 60 products, but my API pull only generated 50. 

## Finding Calories per fl oz
This request stumped me -- the products in the JSON I pulled from the API did not have a standard volume measurment (i.e. "box" or "bottle" being used for some products), and I wasn't entirely sure how to calculate this without that. I did create a total calories column, that I then would've used to figure this question out. 

## Ingredients Index
I started by removing the parens surrounding sub-ingredients using a simple str replace. Attempting to explode the 'ingredients' column resulted in a couple of messy df or errors, and I was unable to get them to play nicely. I even went so far as to open this file in Excel to see if there was a manual way I could do this, but quickly realized the brute force approach would take hours.

## Final Thoughts
I certainly wish I could've had the opportunity to create the no-code app, but my data simply wouldn't work with the product. No amount of slicing, dicing and obscure Google searches could help me, but I did enjoy wrestling with this puzzle. If possible, I would love to know how your team would've solved this project -- I'm super curious and pretty invested in getting it to work at this point, I have to scratch the itch to solve this difficult question.

Thank you so much for this opportunity, I really appreciated it. 

Mia Soza 
