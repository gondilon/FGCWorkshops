# FGCWorkshops
Program for automatically assigning early registrants to their workshopss.
How it works: After early registration FGC staff generates a list of participants and their assigned workshops, along with the list of workshops with the workshop number and the capacity. The goal is to have everyone assigned to either their first or second choice workshop. This program takes that list and checks each workshop to see if it is over-enrolled. If it is, people are randomly removed from the workshop until it is at the capacity. Those people are then assigned to their second choice workshop if there is space. IF there is not space in the first or second choice for that person, they are put into another list for the FGC staff to assign manually. (If you want you could try and write logic to randomly knock out first choices who have space in their second choice to make space.)

Changes that I did not finish:
Check that second choice assignments are working by printing full list.  
make dataframe that collects all of the ones where first and second choice is full.
