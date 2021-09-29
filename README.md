COMERCIO

1. Create folder Structure
 1. create root folder as -----
 2. add frontend and backend folder
 3. create src folder in frontend
 4. run npm init in frontend folder
 5. run npm install -D live-server
 6. add start command in .json as live-server src --verbose
 8. run nom start

2. Website design
 1. create style.css
 2. link style.css to index.html
 3. create div.grid-container
 4. create header, main and footer
 5. style html, body
 6. style grid-container, header, main and footer

3. Create static home screen
 1. create ul.products
 2. create li
 3. create div.product
 4. add .product-image, .product-name, product-brand, .product-price
 5. style ul.products and internal divs
 6. duplicate 2 times to show 3 products

4. Render dinamic home screen
 1. create data.js
 2. export an array of 6 products
 3. create screens/HomeScreen.js
 4. export HomeScreen as an object with render() method
 5. implement render()
 6. import data.js
 7. return products mapped to li's insude an ul
 8. create app.js
 9. link it to index.html
 10. set main id to main-container
 11. create router() function
 12. set main-container innerHTML to HomeScreen.render()
 13. set load event of window to router() function

