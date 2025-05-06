# secure-password

This script checks if a given password has been compromised by querying the Have I Been Pwned (HIBP) API, which provides information on passwords that have been leaked in data breaches. The script takes one or more password arguments as input, converts each password to its SHA-1 hash, and then queries the HIBP API with the first five characters of the hash to retrieve a list of matching hashes. If the password's hash is found in the list, it returns the count of times it has been leaked, otherwise it indicates that the password was not found in the database.
