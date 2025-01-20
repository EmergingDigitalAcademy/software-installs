# Install Postgres.app

Follow the instructions on [postgresapp.com](https://postgresapp.com/) to download and install Postgres.app.

Make sure to move the Postgres.app file to your Applications folder!

## Postico (Database Client GUI app) Overview

At this point we will have a Postgres server program running on our local computer. We’re now going to install a graphical Client so we can have a fancy way to interact with our new server software. If this doesn’t work, please read to the end of the instructions to try these things before asking questions! We have solutions for several common problems.

### Install Postico 2 (for newer MacOs v. 10.15 or later)

1. Go to: [Postico 2](https://eggerapps.at/postico2/)
2. Download
3. Unzip and move to your Applications folder
4. Open (double-click Postico icon)

First thing we need to do is establish a connection to our server. Postico allows you to save many different connections. For now, we just need one to connect to the database server on our local computer.

### Create New Favorite

>> Make sure your database server is running -- see Starting/Stopping

1. Select New Server
   ![New Server](https://github.com/user-attachments/assets/6822cd3d-54d5-4d93-81a8-2b430a2e03dc)


1. Click New Favorite

![Favorite Connections](images/postico-favorites.png)

![Add Connection](images/postico-add-connection.png)


2. Fill in this form as follows:

- **Nickname** can be anything. For now use `Localhost` or `Local`
- **Host** Needs to be `localhost` as this runs on our local computer
- **Port** Leave at the default of `5432`
- **User** This needs to be the user account name that installed Postgres. The default should be good.
    - You can find your username in your terminal:
![Add Connection](images/terminal-username.png)
- **Password** If you followed the above installation of Postgres, this can be left blank
- **Database** By default, Postgres creates a database called whatever your username is. Here `lukeschlangen` is Luke Schlangen's username.

## ERRORS? 

Don't stress it! Bring your error, and we'll figure it out together in class.
