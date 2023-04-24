# First-personal-webdev-site
this is a basic website built using HTMl and CSS only with the use of the Bootstrap library. 

The header is flex container and styled using the 12 division method introduced in Bootstrap. Additionally I have used a anchor points
to allow for the Navbar to navigate you around the single page website. 
The navbar is using the position sticky to stay at the top whilst browsing the full length of the page. 

The About-me section is provided with a background image which is positioned using grid in a 1fr / 1fr and centered with a 100 vh and 
100vw size. In order to position on top of the background image I used Z-index to position the image in the background wiht a number of -1
and the text div was centered ont top with a z-index of 1. Because of the use of Z-index I realised that the stick nav0bar had to be given 
a higher z-index in order to be visible at all times. 

The history section simple section again using a container and a row and col <div> as specified in bootstrap docs. The text in this section
was created using chat gpt with the following prompts. 
1, can you write a short about me for a website. 
2, what additional information woudl you need from me to make it more personal. 
I then answered thte information request and was provided the short about me. 

The project section is a collection of three screenshots of previous small projects caried out in the last few weeks. I placed the images 
within the cards on the carousel. In order to get the carousel to work the JS <script> tag from GetBootstrap had to be added to the bottom of 
<body>

The footer section is a simple section with a my name and three SVGs that are provided from bootstrap. 

All styling form this site was created using only HTML, CSS and Bootstrap - Some JS elements are involved although they are there only 
because they are built in components of Bootstrap and no custom JS is yet in use on this site. 

Colorhunt was used to pick a color pallete with the following hex codes used. 
#F97B22
#FEE8B0
#9CA777
#7C9070

Further details will be added as the website develops and I add additional content. 
