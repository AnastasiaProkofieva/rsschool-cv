## **Anastasiia Prokofieva** 
#### *Junior PHP developer*
______________________________________________________________________________________________________________________________
####  **Contacts**
*Skype*: anastasiya_skypik    
*E-mail*: anastasia.beetroot@gmail.com    
*GitHub* : github.com/AnastasiaProkofieva    
*Discord*: Anastasia_P#5121   
______________________________________________________________________________________________________________________________
####  **Profile**
Motivated junior PHP developer has completed courses, looking for an internship, ready for further improvement of his knowledge and skills
________________________________________________________________________________________________________________________________
####  **Skills**
* PHP
* Symphony
* Docker, Vagrant
* MySQL
* Git
__________________________________________________________________________________________________________________________________
####  **Code Examples**
```php
if (!empty($_GET['sort'])) {
   switch ($_GET['sort']) {
        case 'id':
            if (!empty($_GET['order']) && $_GET['order'] == 'desc') {
                krsort($users);
            } else {
                ksort($users);
            }
            $users = array_values($users);
            break;
        case 'name':
        case 'surname':
        case 'age':
            usort($users, 'sortFieldsAnother');
            break;
    }
}
```
________________________________________________________________________________________________________________________________________
####  **Projects**
 1. **Bookstore**
    - *Description*: Bookstore(Pages are as follows: catalog, card of one book,cart). Admin panel makes the possibility to edit, delete a book, view a list of 
  books and orders. Also customers are able to leave comments and view them.
    - *Stack*: MySQL, PHP, Docker, HTML, CSS.
    - *Code*: [link to project](https://github.com/AnastasiaProkofieva/bookstore)
 
 2. **Shop (Electro store)**
    - *Description*:  website for goods sale(Main page with a list of products on sale ( is formed in the admin panel); Authorization/Authentication for site clients; The product page consists of: product image, product descriptions, add to cart button; Cart page includes a list of all products in the user s shopping cart and order button what creates an order and sends an email; CMS. Admin panel makes possibility to create, edit, delete a product, view a list of products).
    - *Stack*: MySQL, PHP, Docker, HTML, CSS, Symphony.
    - *Code*: [link to project]( https://github.com/AnastasiaProkofieva/Shop/tree/master)
______________________________________________________________________________________________________________________________________
####  **Education**
* **Back-End (PHP, Symphony), Beetroot Academy/Odessa** (*April 2020 - August 2020*).
* **Frontend Basic, Hillel /Odessa** (*January 2018 - March 2018*)
__________________________________________________________________________________________________________________________________________
####  **Languages**
* **English**: Intermediate
* **Russian**: Native
* **Ukrainian**: : Upper-Intermediate



