This is the BackEnd build in Laravel for a Client VUEJS application. 
It is a basic combo between factory and graphql for getting the data and storing them into the db. 
It has two models and no controllers since the storing of the data happens and gets managed with GraphQl which is definetely interesting.
I would say you do a composer install. 
Go to database folder and find there graphql folder with all the models. Ive left some addiotional working that i did while i was changing stuff around so that you can check it out and get back to it if you need to get additional info on how i tested them in the graphql-playground

With composer install you get not just graphql but also Lighthouse and Telescope to check the queries and play with the data that gets returned from getting, posting, editing, and deleting data.
