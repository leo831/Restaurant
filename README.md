# Restaurant
Project for a restaurant menu app, where users can add, edit and remove restaurants and menu items to their restaurants. 
Users can sign in using Facebook via Oauth2, and can only edit and delete their own data.
# Requirements
* vagrant
* python 2.7

# Instructions

* Clone this <code> repo git clone https://github.com/leo831/Restaurant</code> inside your vagrant folder.
* Change to the /Restaurant directory.
* In login.html and header.html your Facebook App ID.
* In <code> fb_client_secrets.json and client_secrets.json</code> include your Facebook App ID and App Secret Key.
* Start vagrant virtual machine with<code>vagrant up</code> and then <code>vagrant ssh</code> to use virtual machine.
* Run the following code on terminal: <code> cd /vagrant/Restaurant/ </code> to change directory to this project.
* Run the following code on terminal to populate DB: <code> python lotsofmenus.py</code>.
* Run the following code on terminal to run the server locally: <code>python project.py</code>.
