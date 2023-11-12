## Content.csv file
* Filter out all quotations
* Change "Type to "Content Type"
    * Good to be specific
* UserID column is not important 

## Reactions.csv file
* There are some missing values
     * Filter out Blank rows
* UserID column is not important

## Popular Categories files
   * The Datetime column needed to be separated
   * How did I do this?
      * Used the ***RIGHT*** and ***MID*** commands to separate the *Date* and *Time* into separate columns
         * The syntax for ***Right*** is *=RIGHT(col_name, start_num, end_num)*
         * The syntax for ***MID*** is *=MID(col_name, start_num, end_num)*
   * Wanted to see how many times each category was mentioned to determine which were more popular
        * Here are my results from most popular to least popular:
             1. food
             2. science
             3. animals
             4. culture
             5. travel
   * I also wanted to see what ***Content Type*** was more popular to use
        * Here are my results in order from most popular to least popular:
             1. photo
             2. GIF
             3. audio
             4. video
