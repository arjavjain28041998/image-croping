# README

The setups steps expect following tools installed on the system.

    • Ruby 2.4.2
    • Rails 5.7.0

 Create database.yml file
Copy the sample database.yml file and edit the database configuration as required.
cp config/database.yml  or  config/database.yml

Create the database
Run the following commands to create the database.
    • bundle exec rake db:create
    • rails db:migrate


Migrate the database
Run the following commands to migrate the database.
bundle exec rake db:migrate

 Start the Rails server
You can start the rails server using the command given below.
bundle exec rails s
And now you can visit the site with the URL http://localhost:3000


Home Page 


/home/ongraph/Pictures/Screenshot from 2021-07-05 19-52-11.png![Screenshot from 2021-07-05 19-52-11](https://user-images.githubusercontent.com/81669250/124486434-3a3b5a80-ddcb-11eb-8be9-7b4700c81a39.png)

Crop Image Page

/home/ongraph/Pictures/Screenshot from 2021-07-05 19-53-11.png![Screenshot from 2021-07-05 19-53-11](https://user-images.githubusercontent.com/81669250/124486581-5fc86400-ddcb-11eb-842b-9c54e15b674b.png)

