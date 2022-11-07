# QA - Test Player

## Introductions
Use this sample Flutter app: https://github.com/flutter/gallery
Write the end to end UI tests and expectations for a scenario where the user is adding some items to the shopping cart. An example flow would be:

## Requirements
● Opening the Shrine Gallery <br>
● Adding the Walter henley (white) shirt to cart after going to the Clothing filter <br>
● Adding the Shrug bag after using the Accessories filter <br>
● Checking the total of the shopping cart <br>
● Clearing the shopping cart <br>


# Result QA Test Player
### Full Name : Veronica Herning DW (Veve)
### Date : 7 November 2022
### Applied Position : QA Engineer <br></br>

| Test Case ID | Test Scenario | Test Steps (Steps) | Expected Results | Actual Results | Pass / Fail |
| --- | --- | --- | --- | --- | --- |
| 001 | Verify user directed to homepage menu on Shrine Gallery | <ul><li>GIVEN user already open flutter galery on apps</li><li>WHEN user input valid username and valid password <li> AND click on submit button</li> | THEN user directed to homepage menu on Shrine Gallery | As Expected | PASS |
| 002 | Verify adding the Walter henley (white) shirt to cart after going to the Clothing filter | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user click on top left sidebar menu <li>AND select Clothing filter <li>AND swipe to the right/scroll until find the Walter henley (white) shirt image <li>AND user click on the add to cart icon (on the image)</li> | THEN the Walter henley (white) shirt automation adding into shopping cart | As Expected | PASS |
| 003 | Verify adding the Shrug bag after using the Accessories filter | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user click on top left sidebar menu <li>AND select Accessories filter <li>AND swipe to the right/scroll until find the Shrug bag image <li>AND user click on the add to cart icon (on the image)</ul> | THEN the Shrug bag automation adding into shopping cart | As Expected | PASS |
| 004 | Verify adding the Blue stone mug to cart after going to the Home filter| <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user click on top left sidebar menu <li>AND select Home filter</li><li>AND swipe to the right/scroll until find the Blue stone mug image <li>AND user click on the add to cart icon (on the image)</ul> | THEN the Blue stone mug automation adding into shopping cart | As Expected | PASS |
| 005 | Verify adding items on All filter menu| <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user click on top left sidebar menu <li>AND select All filter menu</li><li>AND swipe to the right/scroll until find items image <li>AND user click on the add to cart icon (on the image)</ul> | THEN the selected items automation adding into shopping cart | As Expected | PASS |
| 006 | Verify show shopping cart section in every page | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user changed to all menu/clothing menu/home menu </ul> | THEN show shopping cart section in every page | As Expected | PASS |
| 007 | Verify user can click icon shopping cart on image multiple times | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user want to adding items more than once/multiple times </ul> | THEN user can click icon shopping cart on image multiple times | PASS |
| 008 | Verify successfully open pop up shopping cart section by click on shopping cart icon | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user already adding items to shopping cart <li> AND click on shopping cart icon </ul> | THEN successfully open pop up shopping cart section by click on shopping cart icon | PASS |
| 009 | Verify successfully open pop up shopping cart section by click on image item that already on shopping cart section | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user already adding items to shopping cart <li> AND click on image item that already on shopping cart section </ul> | THEN successfully open pop up shopping cart section by click on image item that already on shopping cart section | PASS |
| 010 | Verify show total price breakdown details on shopping cart | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user already adding items to shopping cart <li> AND click on image item that already on shopping cart section </ul> | THEN show total price breakdown details on shopping cart | PASS |
| 011 | Verify show shopping cart when no items added | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user directly click on shopping cart icon without adding any items to shopping cart </ul> | THEN show shopping cart when no items added (total and amount on price breakdown is 0 | PASS |
| 012 | Verify close pop up shopping cart section by click on close button (arrow icon) | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user already adding any items to shopping cart </ul> | THEN close pop up shopping cart section by click on close button (arrow icon) | PASS |
| 013 | Verify close pop up shopping cart section by click on outside section cart | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user already adding any items to shopping cart </ul> | THEN close pop up shopping cart section by click on outside section cart | PASS |
| 014 | Verify successfully user can add amount items on shopping cart| <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user already adding any items to shopping cart <li> AND click on image items for many times </ul> | THEN successfully user can add amount items on shopping cart | PASS |
| 015 | Verify successfully user can reduce amount items on shopping cart| <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user already adding any items to shopping cart <li> AND click on minus (-) icon </ul> | THEN successfully user can reduce amount items on shopping cart | PASS |
| 016 | Verify total price auto reduce automatically when amount items reduce| <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user already adding any items to shopping cart <li> AND click on minus (-) icon </ul> | THEN total price auto reduce automatically when amount items reduce | PASS |
| 017 | Verify automatically closed shopping cart section after click on clear cart button | <ul><li>GIVEN user already login and directed on homepage menu on Shrine Gallery</li><li>WHEN user already adding any items to shopping cart <li> AND click on clear cart button </ul> | THEN automatically closed shopping cart section after click on clear cart button | PASS |
| 018 | Verify show the total items of the shopping cart | <ul><li>GIVEN user already adding some items into shopping cart page before</li><li>WHEN click on shopping cart icon</li></ul> | THEN show the total items of the shopping cart| As Expected | PASS |
| 019 | Verify successfully can click on search button | <ul><li>GIVEN user already on homepage</li><li>WHEN click on search button</li></ul> | THEN successfully can click on search button | As Expected | PASS |
| 020 | Verify successfully can click on search button | <ul><li>GIVEN user already on homepage</li><li>WHEN click on search button</li></ul> | THEN successfully can click on search button | As Expected | PASS |
| 021 | Verify show item on clothing filter menu just showing clothing items | <ul><li>GIVEN user already on homepage</li><li>WHEN click on filter menu to clothing filter </li></ul> | THEN show item on clothing filter menu just showing clothing (not show other category) | As Expected | PASS |
| 022 | Verify show item on accessories filter menu just showing accessories items | <ul><li>GIVEN user already on homepage</li><li>WHEN click on filter menu to accessories filter </li></ul> | THEN show item on accessories filter menu just showing accessories (not show other category) | As Expected | PASS |
| 023 | Verify show item on home filter menu just showing home items | <ul><li>GIVEN user already on homepage</li><li>WHEN click on filter menu to home filter </li></ul> | THEN show item on home filter menu just showing home items (not show other category) | As Expected | PASS |
| 024 | Verify item name is showing on under item image | <ul><li>GIVEN user already on homepage</li><li>WHEN user swipe right/scroll down on homepage </li></ul> | THEN item name is showing on under item image | As Expected | PASS |
| 025 | Verify price per item is showing on under item name| <ul><li>GIVEN user already on homepage</li><li>WHEN user swipe right/scroll down on homepage </li></ul> | THEN price per item is showing on under item name | As Expected | PASS |
| 026 | Verify show price per item is using euro symbol (not IDR)| <ul><li>GIVEN user already on homepage</li><li>WHEN user swipe right/scroll down on homepage </li></ul> | THEN show price per item is using euro symbol (not IDR) | As Expected | PASS |
| 027 | Verify show total amount price per items on the right side in shopping cart| <ul><li>GIVEN user already on homepage</li><li>WHEN user already adding one item or more into shopping cart </li></ul> | THEN show total amount price per items on the right side in shopping cart | As Expected | PASS |
| 028 | Verify successfully user can click on back button | <ul><li>GIVEN user already on homepage</li><li>WHEN user already adding one item or more into shopping cart <li> AND user click on back button on the left bottom side menu </li></ul> | THEN Verify successfully user can click on back button | As Expected | PASS |
| 029 | Verify user can click on sort button | <ul><li>GIVEN user already on homepage</li><li>WHEN user want to sort the items </ul> | THEN user can click on sort button | As Expected | PASS |
| 030 | Verify clearing the shopping cart by click on clear basket on footer button | <ul><li>GIVEN user already on shopping cart page</li><li>WHEN user click on clear basket footer button</li>| THEN all items should be deleted/successfully clearing the shopping cart by click on clear basket on footer button | As Expected | PASS |
| 031 | Verify clearing the shopping cart by click on minus button/(-) icon| <ul><li>GIVEN user already on shopping cart page</li><li>WHEN user click on minus button in front of item name/(-) icon until the items is dissapear</li>| THEN the items will directly dissapear/deleted on shooping cart | As Expected | PASS |
| 032 | Verify user successfully can login without fill username| <ul><li>GIVEN user open the flutter gallery on mobile/apps</li><li>WHEN user only fill the password <li> AND click submit button </ul> | THEN user successfully can login without fill username| As Expected | PASS |
| 033 | Verify user successfully can login without fill password| <ul><li>GIVEN user open the flutter gallery on mobile/apps</li><li>WHEN user only fill the username <li> AND click submit button </ul> | THEN user successfully can login without fill password| As Expected | PASS |
| 034 | Verify user successfully can login without fill username & password| <ul><li>GIVEN user open the flutter gallery on mobile/apps</li><li>WHEN user not fill the username & password (fill blank) <li> AND click submit button </ul> | THEN user successfully can login without fill username & password (fill blank)| As Expected | PASS |