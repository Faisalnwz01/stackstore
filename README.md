[![Stories in Ready](https://badge.waffle.io/gschoff/stackstore.png?label=ready&title=Ready)](https://waffle.io/gschoff/stackstore)
# StackStore- A fully functional E-commerce website
![Badge of Honor](https://img.shields.io/badge/Built%20at-Fullstack-green.svg?style=flat-square)
> E-commerce website that includes all aspects of shopping online; include shopping by category, checkout with Stripe, a recommendation engine, and fully built shopping cart.

## Table of Contents

- [Examples](#examples)
- [Usage](#usage)
- [Installation](#installation)
- [Roadmap](#roadmap)
- [Contributors](#contributors)
- [License](#license)



```html
• Used Stripe API to make the checkout and payment a seamless process.

• Built on Mean Stack, includes a MongoDB for database to store all products with completely built schemas.

• Has complete user and admin side, user can view and purchase items and admin can post, delete and update items.
```

## Usage

1.  Make sure that you have MongoDB installed correctly and running on your machine

    ```bash
    mongod
    ```
2. Serve the application with `grunt`

    ```bash
    grunt serve
    ```
     
### Testing
To run the test suite, run the following command:

```bash
grunt test
```

## Installation

1. Clone the repository

	```bash
	git clone https://github.com/Faisalnwz01/stackstore
	```
2.	Install dependencies

	```bash
	npm install    # installs node packages
	bower install  # installs bower dependencies
	```

__Note:__ If you encounter errors in the installation process for npm, it is recommended that you try running the install command with `sudo`



#### Features

-	A fully built E-commerce website that includes Checkout And payment with Strip.
-	Built with Google's Material design in mind.
-	Has both user side and a Admin side; on user side users can view item, add to cart, and checkout out. On the admin side Admin can view placed orders, delete orders, update status of orders, Add new items, delete items, and change the roles of users.
-	Built in data validation to secure A users personal information.
-	Built in data validation to secure items; so the Cart can't be abused.


### Roadmap
- Plan to work more on Recommendation engine.

#### Known bugs

- Syntax highlighting doesn't work in safari
- A bug with adding more item on Admin side, process is not as fluid as We want it to be.

## Contributors
* __Faisal Nawaz__ - Project Lead [LinkedIn](https://www.linkedin.com/in/faisalnwz) | [GitHub](https://github.com/faisalnwz01)
* __Grant Chapman Schoffelen__ - Project Lead  [LinkedIn](https://www.linkedin.com/profile/view?id=365808666) | [GitHub](https://github.com/GrantSchoffelen)
* __Christian Kara__ - Project Lead [LinkedIn](https://www.linkedin.com/in/christianKara) | [GitHub](https://github.com/cifer9)
* __Arcadius Kazimierski__ - Project Lead [LinkedIn](https://www.linkedin.com/in/Arcadiusk) | [GitHub](https://github.com/Arcadiusk)
## License

This projected is licensed under the terms of the [MIT license](/LICENSE)


