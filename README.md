# Mongo DB Shell Important Commands

show dbs
//  Displays all the databases present

db.<database_name>.save(<element_name>)
e.g. db.employees.save(a)
//  Saves the document in the database

show collections
//  Displays list of all the collections in the installation

db.<collection_name>.find()
e.g. db.employees.find()
//  Queries the specified collection

db.<collection_name>.remove(<query>)
e.g. db.employees.remove({lastName: "Rai"})
//  Removes documents from the collection

db.<collection_name>.update(<query>,<object>)
e.g. db.employees.update({firstName: "Anshuman"},{firstName: "Aditya"})
//  Updates the specified document in the collection with the document passed as second argument to the function 

