#Editable Angular Tree Table
Absolutely this is a stronger tree table demo of [angular data table(it's just to show data by tree)](https://github.com/swimlane/angular-data-table),
besides it could gracefully add or remove branch,I improve the function to add and to remove,it is 
clear as you see in the demo.

![looking](dataTable.png "looking")
###require##
* angular.js
* dataTable.js
* dataTable.css
* material.css

###change of source##
Our require is for users to add or remove the branch of the tree table,but
after you push new data into the data-source,the view of the data-table could not change in the 
original edition,the 'two-way' binding isn't working,and the plugin doesn't offer a docs as the
original author say 'docs coming soon in the meantime, 'View Source' is your friend!'

I change a line source of dataTable.js,it could work magicly.if you are interested in it,please 
ctrl+f "杜宽" in this js file.

The remove function I write is a easy recursion,enjoy it.

*it's my pleasure to know your confusion*