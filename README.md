# Index-Fund-Using-Integer-Programming
Project as part of Optimization-I coursework in UT Austin's MS Business Analytics Program.

In	this	project,	we	created	an	Index	fund	with	'm' stocks	to	track	the	NASDAQ-100	index.	We	did	this	in	multiple	steps.	First,	we	formulated	an integer	program	that	picked	exactly	m out	of	n	stocks	for	our	portfolio.	This	integer	program	took	as	input	a	‘similarity	matrix’.	The	individual	elements	of this	matrix represented the	similarity	between	stock	i	and	j. 

Next,	we	solved a	linear	program	to	decide	how	many	of	each	chosen	stock	to	buy	for	our portfolio and	
finally	evaluated	how	well	your	index	fund	does	as	compared	to	the	NASDAQ-100	index,	out	of	sample. You	
will	examine	the	performance	for	several	values	of	m.

Then we tried to reformulate this problem as a Mixed Integer Programming Problem and solved it. This was an extremely slow process as Gurobi took hours to run. We set a time limit of 10 hours for the program to run for the total 10 m values. The solution obtained via this methodology was more optimal than the previous method.

