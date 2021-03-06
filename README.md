# Back-end Test for candidates

We expect the candidate create a Web API based on the following requisites.

## Web API Technical Requisites

The usage of the following are demanded
- Language Python 3

The usage of the following are considered a plus
- Django
- Flask or Django REST Framework
- Docker

## WEB API Main Tasks
> 1. Create the following unauthenticated service endpoints
>  * `/signin` - *POST* - receiving an user name and a password
>  * `/signup` - *POST* - receiving an user full display name, an user name, a password and e-mail address. Upon save time, add the current date and time to the database.
> 2. Create the following authenticated service endpoints
>  * `/products` - *POST* - insert a new product to the product table with the following fields: id, name, description, price, creation date
>  * `/products/{id}` - *DELETE* - delete a product sending a product id
>  * `/products/{id}` - *PUT* - update all passed fields in its appropriate record
>  * `/orders` - *POST* - inserts an order receiving an user id and a list of products id with the current price and quantity
>  * `/orders` - *GET* - returns all orders from the logged user. The search must accept optional filters by price range and date interval of creation date
>  * `/orders/{orderId}` - *GET* - returns details from a specific order. Details are the total value of the order and a list of products with their individual quantity and the price.
>  * `/orders/search` - *GET or POST* - return orders filtered by a interval of price and interval of creation date

## Services Requisites
- All endpoints must have automated tests that will prove the requisites are implemented
- Use as many design patterns and best practices as you see fit
- Use async methods anywhere you find it is needed

## Running and Executing Requisites
- Make your project running with the minimum needed interactions will be considered important in the analysis of your performance.
- Make it as easy as possible
- The ideal scenario will be to clone your repository and execute it through a single command such as `./INSTALL` or `./RUN`

## Documentation Requisites
- It can be done in portuguese although being in english will also be considered a plus
- Should be easy to read and understand the usage (from a client developer's perspective) of your services
- It should be easy to undertand how to execute your tests

## Last Requisites
- You can use your Github, GitLab or BitBucket to deliver this test
- You can fork from here to get started
- Try to keep your commits to a reasonable atomic capacity (We want to be able to understand your line of thinking. Do not be afraid to make really small commits.)
- Use as much best practices you see fit to address the commits and/or branch naming
- Publishing the API and the client in the cloud will be considered a PLUS


Feel free to ask us any question.
*Nicholas Drabowski* - **nicholas@portaltelemedicina.com.br** or *Luiz Roberto Lethang Rodolpho* - **luiz@portaltelemedicina.com.br**

You have 5 days counting from tomorrow to finish and deliver us the address of your github repository. Please, let us know if you need more time.



*Thank you for giving us this opportunity to get to know you and your work.*
