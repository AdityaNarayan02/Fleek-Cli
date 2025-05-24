# Fleek-Cli
We are going to run Fleek lightning Cli

## System Requirements
- 4 Core CPU
- At least 32GB Ram 
- A Linux based system(wsl,Ubuntu etc)




# **Pre-Requirements 🛠**

# **Install node.js & npm**

* node.js

```
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
```

```
sudo apt install -y nodejs
```

* npm

```
sudo apt install nodejs npm
```



# **Install fleek CLI**

```
sudo npm install -g @fleek-platform/cli
```

* Verify the Installation with

```
fleek
```




# **Login**

```
fleek login
```



* Run the above command to get the login page link:

* Login with your Wallet and Email (both)

* After login, open the above link again to sign 

* Back to Terminal & u could see a success message

# **Create a project**


```
fleek projects create
```

* This will promt u to enter a project name: Enter anything u like:


* 🔺🔺 If u see somethink like that (check ss given below), than dont do anythink, just do next process of `Set up a simple page`


# **Set up a simple page**


  * Create a New Directory

```
mkdir ~/fleek-quick-start
```

  * Navigate to it

```
cd ~/fleek-quick-start
```

  * Create a simple html page inside `~/fleek-quick-start`

```
echo "Hello world" > index.html
```




# **Setup a Fleek site**

```
fleek sites init
```

  * This will promt u to do many thinks, just follow the CLI instructions

  * You’ll have to enter a name for the new site.

  * This will Promt `✔ Please specify the directory containing the site files to be uploaded` just enter `.`     (a dot)

  * This will promt `✔ Would you like to include the optional "build" command?` just enter `no`

  * This will promt `✔ Select a format for saving the site's configuration:`     just select  `JSON (fleek.config.json)` & Enter

  * Check the below given SCREENSHOT for more clarification

 

# **Deploy the Fleek site**

```
fleek sites deploy
```



Done!⚕



