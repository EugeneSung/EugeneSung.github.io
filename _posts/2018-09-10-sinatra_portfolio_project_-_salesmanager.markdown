---
layout: post
title:      "Sinatra Portfolio Project - SalesManager"
date:       2018-09-11 02:15:57 +0000
permalink:  sinatra_portfolio_project_-_salesmanager
---

 My best friend started Jewelry import business last month. He told me there is a sales managing app that costs about $10,000 plus a couple of hundred dollars maintenance fee every month. I looked it up and realized I would be able to make one since its format is not that complicated. If there is an app for managing sales and inventory, it will help small business owners who cannot afford to buy an expensive app. Even if that is not the case, at least my friend will be happy and make a good use of it. That was where I started. 
 
 My first plan was to build a simple app, so I tried reducing unnecessary columns and routes as much as I could. However, it was  not possible because such app should have multi routes and database tables. Even though I reduced the size, this project is still big and complicated.
Now, this app has 5 models, 5 DB tables, 5 controllers and lots of view files because all of models must have CRUD routes. The toughest part for me was joining DB. 
* 	User (salesman) has many clients
* User and Client has many orders
* Order has many items and Item has many orders
   *     So, I create OrderItem model and table

Although building this app was not easy, I still thoroughly enjoyed the process since I was building an app that I wanted to make. Even though I used all of my knowledge and skills to build this app, I will have to spend more time and energy to improve it.  
 I hope to refactor this app after learning Rails. I am looking forward to learning about it in depth.

