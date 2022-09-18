### 1. Adding clothes to the bag

#### Preconditions

- Website https://www.wrangler.com is opened.
- All possible popups are closed in such way, that any of the categories in the header (New/Men/Women/etc.) is clickable.

#### Test Steps

| ID                 | Test Step Description                            | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Click the _Kids_ category (in the Header)        | Page with kids clothes is opened                                                                                                                                                                                                       |
| 2                  | Click on any picture of clothes                  | Personal clothes page is opened                                                                                                                                                                                                        |  
| 3                  | Click on other clothes color (if there is such)  | Another clothes color is selected, picture with corresponding color is rendered                                                                                                                                                        | 
| 4                  | Select size/other properties of the clothes      | When all possible properties are selected, the __Add to bag__ button becomes active                                                                                                                                                    | 
| 5                  | Click the _Add to bag_ button                    | __Added to bag__ popup is opened. Title, id, properties and total price are displayed here. _Added to bag_ title is displayed. __View cart & checkout__ and __Continue shopping__ buttons are displayed. Clothes are added to the bag. |

### 2. Buying clothes from the bag

#### Preconditions

- Website https://www.wrangler.com is opened.
- At least one clothing is added to the bag.
- All possible popups are closed in such way, that cart in the header is clickable

#### Test Steps

| ID                 | Test Step Description                                               | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Hover on the cart in the header                                     | __My bag__ with ESTIMATED SUBTOTAL is displayed                                                                                                                                                                                        |
| 2                  | Click on the cart in the header                                     | _Shopping bag_ page is opened                                                                                                                                                                                                          |  
| 3                  | Change amount of items in the bag                                   | __Total__ is recalculated according to the amount of items                                                                                                                                                                             | 
| 4                  | Click on the _Checkout_                                             | _Checkout_ page is opened                                                                                                                                                                                                              | 
| 5                  | Fill in the __asdfasdf.com__ email                                  | Please enter a valid email address tooltip is displayed                                                                                                                                                                                |
| 6                  | Fill in correct data and click __Continue to billing__              | _Shipping_ page is opened                                                                                                                                                                                                              |
| 7                  | Enter credit cart credentials, check data and click __Place order__ | Order is made                                                                                                                                                                                                                          | 


