
||-------Railway Ticket Booking System using system calls in c-------||

Run create.sh to create essential files for the database:
    $./create.sh 
    
    It will delete the previous directory and create a new directory with name db
    	db will contain three .dat file:-
    		1. db_user.dat
    		2. db_booking.dat
    		3. db_train.dat

Run run.sh to create executable file of server and client:
    $./run.sh
    
    It will create two executable files:-
    	1. server
    	2. client

Run the server:
    $./server

Run the client:
    $./client

First sign up and create one admin account.
The secret pin for admin account is "secret".

Remember the login id as we require login id to login and not the username.

Now login into admin account
	Admin can do following things:
	1->User related
		1. Add users(customer/agent)
		2. View all users
		3. Modify user's username and password
		4. Delete users(customer/agent)
	2->Train related
		1. Add trains
		2. View all trains
		3. Modify train's name and total number of seats
		4. Delete trains

We can create customers/agents explicitily also and login to book ticket.

The functionality of user(customer/agent) are mostly same only difference is agent account can have more than one simultaneous login whereas more than one customer cannot login to the same  customer account simultaneously. 

Once you login as a user
	User can do the following things:
	1. Book tickets
	2. View previously booked tickets
	3. Update previous bookings
	4. Cancel previously booked tickets
	
Apart from this:->
	Here we are using port 8010.
	You can change the port of server and client.
	You can also change ip address in client.c under variable name server_ip.


