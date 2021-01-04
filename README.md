# Flask DB Webapp

Click on the link below to view the current version of the webapp running on an AWS EC2 instance.

http://ec2-3-15-210-85.us-east-2.compute.amazonaws.com:8080/

To run the webapp locally, download the repository files and install all tools listed in requirements.txt

## Description

This webapp is a simulation of a database for a fictional restaurant that serves different cuisines. For any given day, the restaurant serves one cuisine and has a specific Menu for that cuisine. Chefs are added to the database based on cuisine experience and are scheduled for shifts accordingly (shifts on days where the chef has experience in the day's cuisine). Ingredients for all Menu Items can also be managed using an inventory that keeps count of the current stock for each ingredient item. A Menu Item Ingredients table also exists to list all ingredients for each Menu Item, to ensure that there are enough ingredients to prepare every Menu Item for any given day's cuisine.
