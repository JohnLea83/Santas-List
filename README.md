# Santas-List
Final group project

My team and I built an online Letter To Santa app. For the kids' side, they are able to fill out a letter to Santa that contains both pre-generated sections as well as an area for them to create on their own. 
 
They login using credentials set up solely by their parents. Once they are done with the letter, they are able to enter in up to 15 items that they want for Christmas. 

Once they submit their letter and list, we used SendGrid to sent the parents an email notification that their child's or children's list is available. 

On the parent's side of the site, they are able to create their account using name, email, and password. They are then able to add their children to the site using a first name and password only. 

All of this information is stored in protected databases, and is only accessed when logins are triggered, or when a completed christmas list is viewed. Once their children complete their list, and the parents have received the email, they are able to login and view what is essentially a gift registry. 

They can give their login to family and/or friends, and the items can be marked as purchased, the items can be removed completely individually if need be, and comments can be made on each item if someone has questions.

To build the app, we used HTML, LESS, Typescript, Bootstrap, and AngularjS, with some CSS animations and a Canvas sprinkled in on the frontend. On the backend, MySQL, Express, and Node.js, with Passport for authorization. 

We built the app to scale up from tablet, although time constraints prevented us from completing scalability with some of the frontend pieces. We also had planned to implement an Amazon API so that the items the child entered would be populated on the parent's side along with photos of the item and a link to the item's amazon page. This, too, was dropped due to time. 
