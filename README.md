# HTML-Meta-Tags The Complete Reference
#### A collection of complete  HTML meta tags for the developers

****


## Basic HTML Meta Tags

###charset	
	
This tag is used to define the charset
	
	Example: 
		<meta charset='UTF-8'>
	


###keywords

This tag is used specify the keywords for the search engines to identify the content 

	Example:
		<meta name='keywords' content='programming meta tags complete reference'>


### description

This tag is used to give  brief description about the page, google(search engine(s)) uses this well enough 
to show the page in searched results pretty. 

	Example:
		<meta name='description' content='pretty nice overview of the page in few words'>

### subject 

This is subject of the website 
	
	Example: 
		<meta name="subject" content="Website's subject">

### copyright

Shows copyrights holder of the content 

	Example:
		<meta name="copyright" content="copyright holder">

### language 

Explains in which language your website is, this tag declares language 
in which document is being indexed. 



	Example: 
		<meta name="language" content="EN">
		<meta name="language" content="spanish">


### robots 

	
*POSSIBLE VALUES:*
	* index
	* noindex
	* follow
	* nofollow

 	Using this tag you can tell the search engines like google and yahoo whether 
	you want you pages to be indexed or not. You can use robots.txt instead or both

*Examples:*
	
	<meta name="robots" content="index, follow">
	<meta name="robots" content="NOINDEX, FOLLOW">
	<meta name="robots" content="noindex, nofollow"> 
	<meta name="robots" content="all"/>
        <meta name="robots" content="noodp,nooydir" id="robots">


### revised 

*Example:*
	
	<meta name='revised' content='Sunday, June 18th, 2015, 5:15 pm'>

### abstract 

This tag is used to describe the page in abstract 

	<meta name='abstract' content='About meta tags'>

### topic 

*Example:*
	
	<meta name='topic' content='Meta Tags'>

### summary 

This tag is used to give the brief summary about the page 

*Example:*

	<meta name='summary' content=''> 

### Classification

This tag is used to describe in which the page/site comes under

*Exmaple:*

	<meta name="Classification" content="Portal">


### author

This tag is used to specify the author 

*Example:*

	<meta name="author" content="name <user@email.com>">

### Designer 

*Example:*

	<meta name="designer" content="">

### reply-to 

This tag is used to specify the email address of the person who
is responsible for the web site. Usually the webmaster email address

*Example:*

	<meta name="reply-to" content="webmaster@domain.com">



### revist-after 

It tells the sipder/crawler that, come back after this much time to 
index this page again

*Example:*
	
	<meta name="revisit-after" content="7 days">





## Windows

### msapplication-TileColor

*Example* 
	<meta name="msapplication-TileColor" content="#2c4762"/>

### msapplication-TileImage 

	<meta name="msapplication-TileImage" content="http://domain.com/image/path"/>




## Advanced

### x-dns-prefetch-control 

*Example*
	 <meta http-equiv="x-dns-prefetch-control" content="off"/>

*Who is using*
	tumblr.com


# SITE SPECIFIC 

## PINTEREST (pinterest.com)

### p:domain_verify

	This tag is used to verify pinterest account

*Example*
	<meta name="p:domain_verify" content="d238andi" />




## External Resources 

* [WHATWG META tags reference](https://wiki.whatwg.org/wiki/MetaExtensions)
	
