# Internet Software Development Group Project

## Project Structure: 
*place_holder.txt was only added so the directory would push to github,
after you pull the file layout structure you can delete them*
    
        .
        ├── docs 
        │   ├── page_images 
        │   │   └──  // .png files of our project's pages for turning in 
        │   │ ...
        │   └── // Documentation files
        │
        ├── node_modules
        │   │   // If we use NodeJS for the server side instead of XAMPP, This folder will contain all         
        │   │      the NodeJS dependencies required. When you type 'npm install' into the Webstorm   
        │   │      terminal on WebStorm, the node dependencies will get installed here. Don't commit it ti  
        │   └──    The repo because they're generally heavy in terms of space.     
        │   
        ├── www   ( might rename? just one commonly used that I found )
        │   │
        │   ├── Assets
        │   │   │
        │   │   ├── Audio
        │   │   │   └ // app audio ( .mp4 files )
        │   │   ├── Fonts     
        │   │   │   └ // app fonts ( .ttf/ .woff files )
        │   │   └── Images
        │   │       └ // images used in app ( **reduced** .jpg/ .png files )
        │   │   
        │   ├── Data  
        │   │   └ // app information (.JSON Files) 
        │   │
        │   ├── JavaScript ( Might separate this directory into more sub directories ) 
        │   │   │ 
        │   │   └ // Scripts ( .js files )
        │   │   
        │   ├── Libs  ( A lot of examples show JS files in here )
        │   │   │
        │   │   └ // 3rd party Libraries and general purpose files
        │   │
        │   ├── StyleSheets ( .css/ .scss files )
        │   │   │   
        │   │   ├── Base  
        │   │   │   └ // .css files for resets, variables, mixin, and utility classes      
        │   │   ├── Layout
        │   │   │   └ // All CSS files that handle layout, such as container and grid system
        │   │   ├── Components  
        │   │   │   └ // .css for anything reusable, such as buttons, navbars, etc..  
        │   │   │        
        │   │   └── main.css        ( primary .css file, should import the CSS files above )
        │   │     
        │   └── Views       ( .html files )
        │       │
        │       ├── Pages       
        │       │   ├── checkout.html               ( checkout page )
        │       │   ├── shippinginfo.html           ( shipping information page )
        │       │   ├── userinfo.html               ( user information page )
        │       │   ├── shoppingcart.html           ( shopping cart page )
        │       │   ├── ...
        │       │   └── // Layout of website pages
        │       │   
        │       └── Templates 
        │           │
        │           └ // possible template layouts we find and use 
        │
        ├── src
        │   │
        │   └── // if we need directory for back-end files? ( will look into way later )
        │
        ├── .gitignore
        │
        ├── _config.yml  // Jekyll use 
        │
        ├── index.html   // website entry point                
        │
        ├── LICENSE 
        │
        ├── robots.txt    // talks to search engines and crawlers
        │
        └── README.md
         
## Current Page Images (9-13-2019)
###### User Information:
------
![User Information](https://github.com/TrevorMcDougald/InternetSoftwareDev3320/blob/Trevors-Branch/docs/page_images/checkout_page_9-13-2019.PNG) 
###### Shipping Information:
------
![Shipping Information](https://github.com/TrevorMcDougald/InternetSoftwareDev3320/blob/Trevors-Branch/docs/page_images/shipping_information_page_9-13-2019.PNG) 
###### Shopping Cart:
------
![Shopping Cart](https://github.com/TrevorMcDougald/InternetSoftwareDev3320/blob/Trevors-Branch/docs/page_images/shopping_cart_page_9-13-2019.PNG) 
###### Checkout:
------
![Checkout](https://github.com/TrevorMcDougald/InternetSoftwareDev3320/blob/Trevors-Branch/docs/page_images/user_information_page_9-13-2019.PNG) 

