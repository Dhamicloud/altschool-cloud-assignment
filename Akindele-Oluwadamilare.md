step 1 : Create a user using the useradd command
<img src="assets/image/create-user.png">

step 2 : Set an expiry date for usermod -e 
<img src="assets/image/expiry-date.png">

step 3 : prompt user to change password upon login using chage --lastday 0 command
<img src="assets/image/prompt-user.png">

step 4 : attach a user to teh group altschool using usermod -aG altschool
<img src="assets/image/attach-user.png">

step 5 : create a user without home directory using useradd --no-create-home
<img src="assets/image/no-home-dir.png">

step 6 : allow altschool group to be able to run only cat command on /etc/
<img src="assets/image/allow-cat-only.png">