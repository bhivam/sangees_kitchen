## Planning



#### Backend
  - Mobile authentication through firebase seems easiest
  - Checkout if AWS, Azure, or Firebase is best for serverless functions. Price-wise especially. 
  - For database, leaning towards firebase but will see. 
  - Backend needs to store orders into database and display that into a google sheets
    - At some point, wean off google sheets and try to display more things on a dashboard which provides a custom experience. Don't want to allow use of the google sheets anyways.


#### User POV
- Login to app
- Land on the ordering screen
  - This will have a menu list with the day of the week in bold. and then all the menu items listed under. 
    - Menu will by dynamic. There will be a period of time which will be specified by admin where each day can be live on the menu. Past that time and before pick up (6pm), you can make a tentative order which will have to be accepted or declined by the merchant. 
    - If between weeks and menu is not released yet, display: Menu in the works! or some message like that. 
  - You can quick add/subtract one thing to your cart at the time with plus/minus icons or you can click on the menu item and then a pop up will come up asking what quantity you would like.
  - There will be a cart icon in the top right with a small bubble indicating how many things have been added so far.
    - When you click on the cart you can see an order summary and then click to place order, either with cash or through Zelle (will have to figure this out).
    - Option for a reciept sent to your whatsapp or email.

#### Admin POV
- Don't know if I want Admin panel to be a separate app or if it should be integrated into the app where I create a special admin account that mom would have to do something special to log into. 
- Dashboard to see data
  - There will be a lot of interesting data, like pricing trends and stuff like that which can be visualized and analyzed. 
- Needs to be a menu creation system
  - Select a particular week in the future and then create a menu for each day of that week.
    - Options to select which days the menu will have. 
    - Creating title, description and picture (optionally). 
        - Picture will need to have some dynamic sizing stuff or an in-app cropping tool.
  - Editing menu
    - This feature should exit but it needs to be controlled carefully. You should not be able to edit menus after a particular point/only if no orders or placed. Or there might be a system where if an item is edited it will notify whoever ordered it that the description of one of the items they ordered has been changed, so they can opt for a refund.
