# LibraryDocumentationSystem
The Library Documentation System is a Python program designed to manage and organize information about documentaries and their respective copies in a library. The system consists of two classes: Documentaire and Exemplaire. Here's an overview of each class:

# Documentaire Class:

Attributes:

_count: A class variable to keep track of the total number of documentaries.
_code: An automatically assigned unique code for each documentary.
_titre: The title of the documentary.
_date: The date of the documentary.
Methods:

__init__(self, titre, date): Initializes a new documentary with a title and date.
Getcode(self): Retrieves the unique code of the documentary.
setcode(self, code): Sets a new code for the documentary.
Gettitre(self): Retrieves the title of the documentary.
settitre(self, titre): Sets a new title for the documentary.
Getdate(self): Retrieves the date of the documentary.
setdate(self, date): Sets a new date for the documentary.
Getcount(self): Retrieves the total count of documentaries.
ToString(self): Generates a string representation of the documentary.
Equals(self, doc1): Checks if two documentaries are equal based on their codes.


# Exemplaire Class (Inherits from Documentaire):

Additional Attributes:

__numero: The unique number assigned to each copy of a documentary.
__dateach: The date of purchase for a copy.
Methods:

__init__(self, titre, date, dateach, numero=12345): Initializes a new copy of a documentary with a title, date, purchase date, and an optional predefined number.
Getnumero(self): Retrieves the unique number of the copy.
setnumero(self, numero): Sets a new number for the copy.
Getdateach(self): Retrieves the purchase date of the copy.
setdateach(self, dateach): Sets a new purchase date for the copy.
ToString(self): Generates a string representation of the copy, including documentary information.
Equals(self, ex1): Checks if two copies are equal based on their numbers.
This program is designed to facilitate the management of documentary information within a library, allowing for easy retrieval and modification of documentary and copy details.





