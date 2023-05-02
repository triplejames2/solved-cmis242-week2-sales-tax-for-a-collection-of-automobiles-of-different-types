Download Link: https://assignmentchef.com/product/solved-cmis242-week2-sales-tax-for-a-collection-of-automobiles-of-different-types
<br>
The second programming project involves writing a program that computes the sales tax for a collection of automobiles of different types. This program consists of four classes. The first class is the <sub>Automobile</sub> class, which contains the automobile’s make and model, and purchase price, which is specified in whole dollars. It should have three methods:

<ol>

 <li>A constructor that allows the make and purchase price to be initialized.</li>

 <li>A method named <sub>salesTax</sub> that returns the base sales tax computed as 5% of the sales price.</li>

 <li>A <sub>toString</sub> method that returns a string containing the make and model of the automobile, the sales price, and the sales tax, appropriately labeled.</li>

</ol>

The <sub>Automobile</sub> class has two subclasses. The first is <sub>Electric</sub>. It has an additional instance variable that contains its weight in pounds stored as an integer. It should have the same three methods:

<ol>

 <li>A constructor that allows the automobile’s make and model, purchase price and weight to be initialized.</li>

 <li>An overridden method <sub>salesTax</sub> that returns the total sales tax. The sales tax for an electric automobile consists of the base sales tax of 5% that applies to all automobiles minus a discount. If the weight is less than 3000 pounds the discount is $200. Otherwise it is $150.</li>

 <li>An overridden <sub>toString</sub> method that returns a string containing the make and model of the automobile, the sales price, sales tax and the weight, appropriately labeled.</li>

</ol>

The second subclass is <sub>Hybrid</sub>. It has an additional instance variable that contains the number of miles per gallon stored as an integer. It should have the same three methods:

<ol>

 <li>A constructor that allows the automobile’s make and model, purchase price and miles per gallon to be initialized.</li>

 <li>An overridden method <sub>salesTax</sub> that returns the total sales tax The sales tax for a hybrid automobile consists of the base sales tax of 5% minus a discount. If the number of miles per gallon is less than 40, the discount is $100. Otherwise there is an additional discount of $2 for every mile per gallon in excess of 40.</li>

 <li>An overridden <sub>toString</sub> method that returns a string containing the make and model of the automobile, the sales price, sales tax and the number of miles per gallon, appropriately labeled.</li>

</ol>

No additional public methods should be included in any of the above three classes.

Finally there should be a fourth class named <sub>Project2</sub> that contains the main method. It should generate the GUI shown below:

After entering the information about the make and model, its sales price and the type of the automobile, clicking the <em>Compute Sales Tax</em> button should display the sales tax in the text field to its right. In addition, the object should be stored in an array of type <sub>Automobile</sub>. That array should allow space for up to the last five automobiles entered.

If non integer values are entering in any of the fields that require integers, an error message should be displayed in a <sub>JOptionPane</sub> window.

Clicking the <em>Clear Fields</em> button should clear all text fields.

Clicking the <em>Display Report</em> button should produce a report on the console that includes the information about all the automobiles currently stored in the array. An example of the report that should be displayed is shown below:

Make and Model: Toyota Prius

Sales Price: 30000

Sales Tax: 1390.00

Hybrid Vehicle

MPG: 45

Make and Model: Ford Fusion

Sales Price: 21000

Sales Tax: 1050.00

Be sure to follow good programming style, which means making all instance variables private, naming all constants and avoiding the duplication of code. Furthermore you must select enough different kinds of automobiles to completely test the program.


