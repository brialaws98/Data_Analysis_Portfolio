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
