# SEassignment


# Requierments for part 1:
1. Create	a	JSP	page	named	Register.jsp,	this	will	contain	register form	with	first	name,	last	
name,	username, password	and	confirm	password	fields (make	sure	both password	
fields to be	of	type	password).
2. Add	a	link	to	login	page	in	register	page.
3. Write	code	to	verify	and	save	new	user	to	database(MySQL). Redirect	user	to	Login	page	
after	a	successful	register,	or	back	to	register	page	with	error	message	after	a	failed	
register.
• userName	must	be	unique
• passwords	must	be	encrypted	with	one-way	encryption	algorithms,	such	as	sha1,	
sha256	etc.
4. System	need	to show	different	error	messages	on	Register.jsp, if	any	of	the	inputs	are	
invalid	or	form	is	left	blank	on	submit.	There	are	three types	of	error	messages:	
• userName	already	exists
• password	and	confirm	password	fields	don’t match
• Any	of	the	fields	are	left	blank.
• all	fields	are	required
5. Modify	your	login	code	in	assignment	1,	you need	to	read	user	information	from	
database.
6. Modify	your	login	page,	add	a	link	to	register	page.
7. Add	a	logout	button	in	welcome	pages,	when	user	click	it,	log	the	user out	(invalidate the	user’s	session)
8. Implement	session	control	on	all	pages
• Before	login,	user	should	only	be	able	to	go	to	login	or	register	page.	All	requests	
to	other	pages	should	be	redirected	to	login	page.
• Once	a	user	logged	in	as	provider,	he/she	shouldn’t	be	able	to	go	to	customer’s	
welcome	page,	and	vice	versa.	If	such	request	received,	user	should	be	redirect	
to	appropriate	welcome	page.
• Once	a	user	logged	in,	he/she	shouldn’t	be	able	to	go	to	login	page.	If	such	
request	received,	user	should	be	redirected	to	appropriate	welcome	page.


# Requierments for part 2:
1. A	new	user	can	register	with	first	name,	last	name,	user	name	(should	be	unique)	
password	and	confirm	password.
2. A	user	can	login	into	system	with	correct	username	and	password
3. After	login,	a	user	can	click	a	button	to	logout	of	the	system,	the	user	can’t	access	the	
system	unless	login again.
4. After	login,	a user	can	create	numerical	questions,	with	a	question	description	(a	short	
paragraph	of	text),	a	hint	(a	short	paragraph	of	text)	and	a	correct	answer	(a	number)
5. After	login,	a user	can	create	multi-choice	questions,	with	a	question	description	(a	
short	paragraph	of	text),	4	choices	(short	paragraphs	of	text),	a	hint	(a	short	paragraph	
of	text)	and	a	correct	answer	(A,	B,	C	or	D)
6. After	login,	a	user	can	view	a	list	of	all	available	questions,	there	should	be	a	check	mark	
displayed	next to	each	of	the	questions	the	user	has	answered	correctly.
7. After	login,	a	user	can	choose	one	of	the	question	to	answer,	by	enter	his/her	
choice/number	into	a	text	field	and	click	submit.	The	system	will	give	the	user	a	
feedback.	If	user	chose/entered	a	correct	answer,	display	a	congratulation	message	and	
a	link	to	go	back	to	question	list.	If	the	user	chose/entered	a	wrong	answer,	display	the	
same	question	page,	and	display	a	hint	with	the	question.	Empty	answer	is	not	allowed,	
an	error	message	should	be	displayed	if	user	didn’t	enter	anything	and	click	the	submit	
button.
8. After	login,	in	the	question	list	page,	user	can	click	a	‘clear	history’	button	permanently	
clear	the	user’s	history	of	answered	questions.	There	should	be	no	check	marks	next	to	
any	questions.
