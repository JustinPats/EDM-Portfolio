
## Final Lab Task 1 - Events Management DB ##

## Step 1: Create Database ##


Using MySQL workbench, we first create a database umder the name events_db. After that create a events_tbl : this table consist the events_id as the PRIMARY Key and event_name.


## Step 2: Create attendees_tbl ##

This table will hold the attendees_id as the PRIMARY Key and also the attendees_name.

<img src="https://github.com/JustinPats/EDM-Portfolio/blob/main/Final%20Lab%20Task%201/ImagesFT1/490992182_1063344948960560_8036789133497474912_n.png" align="center" height="350" width="600"/>

## Step 3: Create events_attendees_tbl ##
<img src="" align="center" height="350" width="600"/>
This table will links the events_tbl and attendees_tbl using a many-to-many relationship. 

It uses event_id and attendees_id as FOREIGN Keys.

## Step 4: Create events_sponsors_tbl ##

This links sponsors to events with events_id and and sponsor_name.
<img src="https://github.com/JustinPats/EDM-Portfolio/blob/main/Final%20Lab%20Task%201/ImagesFT1/490403235_1724010338193121_7015241856761683881_n.png" align="center" height="350" width="600"/>

## Here's the Screenshot for the EDR ( see screenshot)

<img src="https://github.com/JustinPats/EDM-Portfolio/blob/main/Final%20Lab%20Task%201/ImagesFT1/ERD.jpg" align="center" height="350" width="600"/>
