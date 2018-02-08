# VinNumChallenge

The problem domain is something seemingly simple: 
Deal with Denati motor recalls. 
The following cars have the following issues:   
The Hyper Elon Sport vehicles have an issue with the underbody aluminum reference plates. This is a €3000 fix. Any cars built in Germany or Houston are seen to have this problem. 
The James Bond Galore is having issues with the archanoid valves, a cost of €9.99 for each one. There are four valves on each car.

Task: Create a search bar that allows Denati Car Owners to search by VIN number and see if their car is one of the ones that need to be recall. If their car is listed in the database, print a message to the user saying something like the following: 

	“The Denati Company has had a recall on several cars and yours is one of them. It appears that you own the James Bond Galore, and you are entitled to 4 new archanoid valves, each at a cost of €9.99. If you are in the US, this is the equivalent of (converted price here)” 
At the end you’ll want something that looks like this: https://www.bugatti.com/ownership/recalls/




VIN Number breakdown: 
1st Character
For Denati, there are 4 countries where the cars were built:
	1 - Australia
2 - Italy
3 - Germany
4 - USA

2rd and 3rd 
The Denati manufacturer code is DN.

4th, 5th, 6th, 7th character
	HE80 - Is the Hyper Elon 80, the one having problems
	JB70 - is the James Bond Galore, the one having problems

8th character
	For all Denati vehicles the 8th character is a Z

9th 
Character for Denati is Z

10th character
	Denati has been making Hyper Elon and James Bond cars for 5 years
	2013 - B
	2014 - C
	2015 - D - This was the year of the Hyper Elon vehicle that was having trouble.
	2016 - E - This was the year of the James Bond vehicle that was having trouble
	2017 - F

11th character
	A - Perth
	B - Sydney

A - Venice
B - Rome

A - Hamburg
B - Berlin

A - Indianapolis
B - Houston

12, 13, 14, 15, 16, 17
Serial numbers are a random string of six integers
