

# Moonshotwebsite
TODO
	!!!!! MOST IMPORTANT - PLEASE GOD DO THIS: https://forums.adobe.com/message/8961654#8961654 - Make it human readable
    Fix screen width
    Set HTML obj background color to black
    Do animation and set Form to hidden and display
    Think about doing my changes IN Muse: https://forums.adobe.com/thread/1397267

TO FIX

	???? Should I removed max-width from #page and u118_align_to_page ????
		https://www.visionpointmarketing.com/blog/entry/maximum-page-width-in-fluid-responsive-design
		It had to do with the "Muse Breakpoints"
		From reading the blog I say get rid of em

	Top left logo is fixed.. so if scroll left it moves becuase fixed position.. but if remove
		form and fix screen width it should be fine?

	CONTACT button is fixed position as well.. way off to the right. This should all be % I believe to by dynamic
		CONTACT should prob be under the "bp_infinity" div.. ITs id is u543

	MUSE is great but exports a metric fuck ton of assets (JS/CSS) you don't need and it does it in
		way that is not "human readable". It actually is but that's a CS term for it just being a pain
		in the ass. For ex, to show you or document changes I made I have to use some tool like the ones
		below which still dont work that well.
			To fix human readable part do this - https://forums.adobe.com/message/8961654#8961654
			The extra assets are so small its prob fine actually

	!!!!!!!! Didn't import SVGs correctly:
		https://forums.adobe.com/thread/2149991
		https://helpx.adobe.com/muse/how-to/add-svg-graphics.html
		https://books.google.com/books?id=y62JDAAAQBAJ&pg=PT286&lpg=PT286&dq=adobe+muse+image+pasted_svg&source=bl&ots=86Zwr-Gtyz&sig=3NvAj0DmuQkxt-jwzMB2M1crb_c&hl=en&sa=X&ved=0ahUKEwj367vyg6PTAhUqr1QKHXlhC7cQ6AEIODAC#v=onepage&q=adobe%20muse%20image%20pasted_svg&f=false
			Download book if interested?
			To see what I am talking about look at:
				https://github.com/moonshotcreative/Moonshotwebsite/tree/master/images

				You will see a ton of png files. They converted ur SVG to PNG in multiple sizes.. Works but not the best


QUESTIONS



NOTES

	The new term for dynamic positioning of html is REACTIVE DESIGN

	Edit website in Chrome http://stackoverflow.com/questions/6843495/how-to-save-css-changes-of-styles-panel-of-chrome-developer-tools

	vimdiff Moonshotwebsite/css/index.css oldMoonshineSite/css/index.css

	wdiff -1n Moonshotwebsite/css/index.css oldMoonshineSite/css/index.css | sed -e 's/^/  /;/{+/s/^ /|/;s/{+//g;s/+}//g'


	wdiff -n -w $'\033[30;41m' -x $'\033[0m' -y $'\033[30;42m' -z $'\033[0m' Moonshotwebsite/css/index.css oldMoonshineSite/css/index.css | sed -e 's/^/  /;/{+/s/^ /|/;s/{+//g;s/+}//g'


	wdiff -n -w $'\033[30;41m' -x $'\033[0m' -y $'\033[30;42m' -z $'\033[0m' Moonshotwebsite/css/index.css oldMoonshineSite/css/index.css | sed -e 's/^/  /;/{+/s/^ /|/;s/{+//g;s/+}//g'







	#u1334-4,.html{
		background-color:black;,
		overflow-x: hidden;

	body{
		verflow-x: hidden;

	#u1680   - FORM ID
		float: right;


	Contact button:
		@media (min-width: 961px), print
		index.css?crc=3920385933:1
		#u543
			top: 50%;    # was like 900
			right: 1%;


		id of form is u1680
		Contact img: pasted svg 566404x67_poster_.png


		LOOK Into math for positioning:

		  <img class="svg svg_mar temp_no_img_src" id="u541" data-orig-src="images/pasted-svg-566404x67.svg?crc=43813589" onload="this.style.height=(this.offsetWidth*42/138)+'px'" alt="" data-mu-svgfallback="images/pasted%20svg%20566404x67_poster_.png?crc=200935016" data-image-width="138" data-image-height="42" src="images/blank.gif?crc=4208392903"/>

		 Y Posotino is this.offsetWidth*42/138. height of this image/contacts is 139 I think 42 is percentage down the page, relative positioing





NOTE FOR JAREN:
	ABA is Applied Behaviorial Analysic - Same shit Char did - Kids had great results/ couldnt tell
	CURTIS - CHECK IMGS - Even Text for form looks like rendered as img

	I found a bunch of links and put them under TO FIX







