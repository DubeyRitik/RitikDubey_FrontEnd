<h1>Based on the code below answer the following queries: </h1>

<h2>1. Explain what the simple List component does. </h2>
Ans. The simple list component returns an unordered list with list items having props such as onClickHandler, text, index and isSelected.

<h2>2. What problems / warnings are there with code? </h2>
Ans. One problem I can find is that the isSelected prop of SingleListItem is boolean so it should not take selectedIndex as value, rather true or false, depending upon selectedIndex is equal to index or not.




