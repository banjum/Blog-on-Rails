Blog-on-Rails
=============

A blog based web application created using Ruby on Rails framework

Incrementally developed a fully-functional web application from scratch. 
The web application supports blogging, and includes a database on the back end, 
an appropriately configured middleware, 
along with the code for displaying blog posts and comments in a user's browser. 
That is, it is an example of a "full stack" web application.

#### Code provides good working examples of:
* ActiveRecord Design Pattern
* Relational Database
* Model View Controller Design Pattern
* Rails Classes and Inheritance
* Rails Objects, Collections, Blocks and Iterators
* RACK middleware (HTTP request response)
* CSS with Rails framework
* JQuery and AJAX with Rails framework


## Installation Instructions
In	this	section	I	will	detail	the	most	important	software	products	and	tools	that	I	
have used for this project.		

* RVM	(Ruby	Version	Manager)	– A	command-line	tool	that	allows	you	to	
install,	manage	and	work	with	multiple	Ruby	programming	language	
versions.		You	should	install	this	first,	and	then	use	it	to	install	the	latest	
stable	version	of	Ruby.		To	check	to	see	if	you	have	RVM	installed,	at	the	
command	prompt in	a	terminal	window,	type:

> rvm	–v

If	you	type	the	following	command:

> rvm	list	known

You	will	see	a	list	of	the	Ruby	versions	you	have	installed.
A	list	of	all	rvm	commands	is	provided	by	typing:

> rvm	help

* Ruby	– As	mentioned	above,	after	installing	RVM,	use	it	to	install	the	Ruby	
programming	language.		Generally,	this	is	accomplished	typing	the	following	
command	in	your	terminal	window:

> rvm	install	ruby

This should	install	the	latest	stable	version	of	Ruby.		You	can	use	the	previous	
command	to	list	the	Ruby	version	you	have	installed,	and	you	can	also	see	the	
current	default	version	you	are	using	by	typing:

> ruby	–v

* Ruby	on	Rails	(Rails)	– Rails	is	a	Ruby	software package	(library).		In	Ruby,	it	
is	common	to	use	the	RubyGems	package	management,	and	the	package	
themselves	are	then	referred	to	as	Gems.		To	learn	more	about	Gems,	see:	
http://guides.rubygems.org

To	install	the	Rails	gem,	at	your	command	prompt, type:

> gem	install	rails

This	should	install	the	latest	stable	release	of	Rails.		To	check	the	version	you	
have	installed	type:

> rails


###Other	Options

If	you	having	difficulties	setting	up	your	development	environment	from	scratch,
there	are	at	least	two other	options:

* Use	a	virtual	machine – this	involves	first	installing	a	virtualization	system	
on	your	computer	that	will	allow	you	to	run	other	operating	systems	within	that	environment.		Two	of	the	leading	vendors	of	virtualization	systems	are	
VMware	and	VirtualBox,	the	latter	is	free	works	very	well.		Once	you	have	
installed	the	virtualization	system,	you	can	download	a	Linux	virtual	machine	
that	has	RVM,	Ruby	and	Rails	pre-installed	from:

https://bitnami.com/stack/ruby/virtual-machine

* Use	a	hosted	development	environment – Nitrous.io provides	a	hosted	
development	environment	that	you	can	access	from	your	web	browser,	i.e.,	
you	will	be	using	a	Rails	environment	hosted	in	the	cloud.		If	all	else	fails,	use	
this!	For	installation	instructions,	visit:

http://railsapps.github.io/rubyonrails-nitrous-io.html
