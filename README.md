# LARAVEL MULTIROLE APPLICATION
### Framework Programming Course
<p>Venia Sollery Aliyya Hasna - 5025201161</p>

---
 **What entities/models are involved in the application?**

The entities that are involved in this project are `User` and `Product`

<img src="/public/images/Screenshot 2023-06-07 110426.png" width="80%" height="80%" />

Above is the models that are used in the code.

-----

**Application use cases. Format: *Role type* can perform *a feature***

As a use case, three roles are made which are `Admin`, `Seller`, and `Buyer`. These three role type have different feature.

The table below gives information about the features each roles have.

| Role Type   | feature  |
| ----------- | ----------- |
| Admin       | role-list, role-create, role-edit, role-delete, product-list, product-create, product-edit, product-delete |
| Seller      | role-list, product-list, product-create, product-edit, product-delete,       |
| Buyer       | product-list        |

Below is the list of users that are assigned to different roles.

 <img src="/public/images/users-list.png" width="80%" height="80%" />

     ADMIN ROLE
     
 <img src="/public/images/admin-roles.png" width="80%" height="80%" />
 
 As an example,the user is logged in as `Admin` since the role `Admin` can list, create, edit, and delete roles, of course it can access the role management page.
 
 <img src="/public/images/admin-access-roles.png" width="80%" height="80%" />
 
      SELLER ROLE
      
<img src="/public/images/seller.png" width="80%" height="80%" />  

Below is an interface when the role `Seller` tries to access role management page. the user is logged in as `Seller` since the role only have a feauture to list role the Show button will only be available.

<img src="/public/images/seller-acces-roles.png" width="80%" height="80%" /> 

     BUYER ROLE
     
<img src="/public/images/buyer.png" width="80%" height="80%" />

As an example the user is logged in as `Buyer`, that means it can only list products. Here is an example when `Buyer` tries to acces roles management page.

<img src="/public/images/seller-access-roles.png" width="80%" height="80%" />

It will give a 403 status code.

But `Buyer` are able to list products. Below is an example:

<img src="/public/images/Screenshot 2023-06-07 111133.png" width="80%" height="80%" />


     
-----

***Controllers, Middleware, and additional libraries used* and their respective functions**

-----
**DB, external interfaces: database table structure used.**
