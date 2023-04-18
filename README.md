
# AddressBookApplicationGUI -> See [Wiki page](https://github.com/ArthurHandy/AddressBookApplicationGUI/wiki) for additional information.
Address Book GUI App made in Java that reads in data using oracle database. Users can add, remove, and find entries. Every contact has a first name, last name, street address, city, state, zipcode, phone, and email. 

GUI contains these features:

* `Display Button`: Updates entries and clears any JList selection.

* `New Button`: Allows user to add new entries. New frame will open up asking for: First Name, Last Name, Street, City, State, Zip Code, Phone, and Email. Add button is disabled until all the entries are filled in.

* `Remove Button`: Allows user to remove old/new entries. Remove is disabled until an entry is selected.

* `Find Button`: Allows user to find any portion of the last name. 

* `Scrollable Area`: Place to display the current list of AddressEntries.

* `Database`: Entries are read from oracle database, and if an entry is added or removed, the database will update.

## Prerequisites
Oracle Instant Client (OCI) packages: [OCI download](https://www.oracle.com/database/technologies/instant-client/downloads.html)
* `Basic Package`
* `SQL*Plus Package`
* `JDBC Supplement`

How to connect to Oracle with OCI: [Oracle](https://www.jetbrains.com/help/idea/how-to-connect-to-oracle-with-oci.html#creating-the-oracle-oci-connection)

## Installing
Clone the repository 

`https://github.com/ArthurHandy/Addres-Book-GUI-Application-with-Database.git`

# Built With
[IntelliJ IDEA](https://www.jetbrains.com/idea/) - IDE

[Java](https://www.java.com/en/) - Programming language used

[Oracle](https://www.jetbrains.com/help/idea/oracle.html) - Database
