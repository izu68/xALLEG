	 ____   ____.______  .___    .___    ._______._____  
	 \   \_/   /:      \ |   |   |   |   : .____/:_ ___\ 
	  \___ ___/ |   .   ||   |   |   |   | : _/\ |   |___
	  /   _   \ |   :   ||   |/\ |   |/\ |   /  \|   /  |
	 /___/ \___\|___|   ||   /  \|   /  \|_.: __/|. __  |
	                |___||______/|______/   :/    :/ |. |
	                                              :   :/ 
	                                                  :  
                                                     
			a precompiled version
		 of the allegro library, modified for
		      cross compilation with the 
		    i586-pc-msdosdjgpp-gcc compiler


			    WHAT TO EXPECT:			

	Expect a working, ready to go installation of allegro to
	plug into your DJGPP cross compilation environment. 

	Simply clone this repository into your DJGPP prefix
	folder and you are ready to go. Don't forget to compile
	with the -std=gnu89 flag, as the structure of the
	library is not compatible with modern C dialects. And
	also don't forget to link with -lalleg, of course.

				CREDIT:

	This repo wouldn't be possible without the work of
	msikma-who made all the modifications necessary to make
	cross compilable Allegro programs possible-and without the
	original authors of the Allegro library. Huge props to them!

			        LICENSE:

	Allegro 4.2.2 is giftware licensed, my and msikma's
	modifications are public domain.

