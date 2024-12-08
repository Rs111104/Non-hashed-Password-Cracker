# Non-hashed-Password-Cracker
This is a tool that I chose to develop as my Principles of Computer Security final project - It is designed to convey the risks of not hashing and allowing users to create weak passwords by showing that passwords can be modeled. 

# The Problem
One of the biggest obstacles that attackers face when attempting to crack passwords is time. There is a large number of password combinations, and even if an attacker had a list of every password in the world, searching through that list for a single password could take much more time than it is worth. What if, however, an attacker had previous knowledge about a service or system with passwords, for example, the number of characters recommended for users or special character requirements. With this knowledge, an attacker could effectively eliminate some passwords from their search if they had a list that was grouped or ordered in some strategic way. To take this a step further, if an attacker could determine the number of tries it would take to find any password despite not knowing what the actual password was, they could essentially gain a significant advantage in regards to cracking it. The possibility of this advantage introduces one of the main problems for password holders and admins, that is, making sure that passwords have long search times and are hard to guess. To some extent, making passwords longer or requiring them to contain special characters affects the search time in favor of password holders. Unfortunately, tools like the password cracker developed for this project produce predictive time/try estimates that can steer an attacker in the right direction, thereby putting password holders at risk if they do not have appropriate security measures in place. 
