**Find Element By Id**

    .//tr[@id="review")]

**Find Element By Class**

    .//tr[classid="review")]

**Find Element By Part of Id**

    .//tr[contains(@id,"review_")]


**Find Element By Text**

    .//button[contains(text(),'Complete')]


**Multiple Conditions AND**

    .//a[contains(text(),'Close') and @class='button-panel-link']

**Find Elements inside of other elements**

    .//div[@class="wrestinfo"]//h1[contains(text(),"AndrewRyan")]
