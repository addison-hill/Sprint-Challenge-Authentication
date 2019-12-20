## What is the purpose of using sessions?

Its a way to store data such as authentication across requests.

## What does bcrypt do to help us store passwords in a secure manner.

It hashes a password into a long string, and they is split up into 3 fields. Bcrypt algorithm, the cost factor or how many iterations, and then the salt and cipher text.

## What does bcrypt do to slow down attackers?

It hashes the password multiple times (however many times you want it to) the more iterations the harder it is to hack.

## What are the three parts of the JSON Web Token?

The header, the payload, and the signature
