## FAC week 9 - build Amazon

This is a BIG project. It's going to be great!

### Payments
You want to work on payments - cool. Payments will come up as a requirement in so many of your projects, it's probably a good call to wrap your head around it sooner rather than later. With payments, you'll need to show a fair bit of patience and read the documentation very carefully.

### User perspective
If you're shopping on Amazon, you want to be able to browse for items. Some kind of search functionality would be useful. You also want a shopping cart. It would be pretty useful if you could read and write reviews.

### Vender perspective
So, you want to go for the vender option. This means content creation: Writing a description, setting a price, uploading an image maybe.

### Minimal requirements
- user should be able to register
- user should be able to login
- user should be able to logout
- user should be able to scroll over a list of items regardless of them being logged in or not

### Stretch goals
- user should be able to reset their password if they forgot it
- user should be able to login with facebook or google
- a registered user should be able to create an item to sell and put a price against it
- user should be able to buy an item and pay for it

### Resources
- [awesome react](https://github.com/enaqx/awesome-react) long list of good resources
- [load data via AJAX](https://facebook.github.io/react/tips/initial-ajax.html)
- [routing system](https://github.com/reactjs/react-router) being able to navigate between pages in react
- [redux](http://redux.js.org/) redux for better decoupling your code
- [testing react](https://facebook.github.io/react/docs/test-utils.html)
- [bes testing react](https://github.com/besarthoxhaj/testing-react) bes **experiments** in testing react
- [facebook getting started](https://facebook.github.io/react/docs/getting-started.html)
- [dwyl repo](https://github.com/dwyl/learn-react) dwyl repo on react resources

### Problems
Here some problem you will encounter during development. 

#### Authenticate HTTP requests
With react you are gonna use lots of AJAX calls. You may want to find a way to allow some requests and block others.

#### Database schema
Redis is a great NoSQL database, however normal SQL relational database are useful too, Postgres can be a good choice and [knex](https://github.com/tgriesser/knex) is small wrapper around it.

Good luck!
