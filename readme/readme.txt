Created by: 

	Jeff Cowles (isuzufan@hotmail.com)

Description: 

	A colorful icon pack for the Cuda Text editor. Some icons are inclined +/- 6 degress to give it a fun feel. Icons come in 24px, 32px, 36px, and 48px. 
	
	Included are the GIMP (.xfc) files for each icon so you can create new icon packs with your own preferred colors. 
	
Credits: 

	I created all these icons myself, although I did base a few on the Cuda Text default icon pack. A couple more came from Google Images, but then I changed them a little to make them my own. 

Notes: 

	I set up the .xcf files so that you could change the colors to whatever you wanted and create your own color scheme. (BTW - ColorHexa.com is a great resource for choosing colors, imho.) All icon sizes are included in each file. 
	
	On the Layers tab you'll normally find two layers per icon size.  The "base" layer is what the icon looks like in its normal horizontal orientation, while the "rotated" layer is after I rotated the icon +/- 6 degrees. (There's nothing special about 6 degrees, it's just what I felt looked "just right".)
	
				On the Channels tab are all the selections I created. Basically, I custom created selections for each size of every icon and saved them as channels. Each .xfc file usually has separate channels for the different elements within an icon — the border and an accent color, for example. To activate a selection, right-click the channel and select Channel to Selection. Go to the Layers tab and you should see the selection. Fill the selection with your foreground color (ctrl + ,) or background color (ctrl + .).  In this way you can easily build an icon set using your own color scheme. 
	
	After you create a base, horizontal icon with all your colors, you can rotate it if you want. Just duplicate the base layer and use the rotate tool to the degree you like. 
	
	Below are some additional notes about each of the .xcf files.

case.xcf

	This icon accepts up to two colors but there is only one channel. This is because the letter "a" is a text layer and not a selection that I built. The only channel is the "arrow" channel.  
	
	Here's how to build this icon. First, create the letter "a" as a text layer using a color. I used Microsoft Sans Serif font but you can use whatever. The text sizes I used: the 48px icon = 60px text, the 36px icon = 45 px text, the 32px icon = 40px text, and the 24px icon = 30px text. 
	
	Then create a new layer and use the "arrow" channel to create the double-headed arrow in a different color. With only those two layers visible, create a new layer (Layer > New from Visible) and rename it as "XX base". Duplicate it again if you want to rotate it.  


comment.xcf

	This icon accepts up to two colors, so there are two channels. The "bubble" channel  represents the outer comment frame while the "lines" channel represents the two lines of text within.   


e_copy.xcf

	This icon accepts up to two colors, so there are two channels.  The "front" channel is the lower-right element, and the "back" element is the upper-left element. 


e_cut.xcf

	This is a one-color icon so there is only one channel. Since this icon already has diagonal elements in it, I didn't think it would look good if I also rotated it, so I left it horizontal.
	

e_paste.xcf

	This icon accepts up to two colors, so there are two channels. The "frame" channel represents the outer border of the clipboard, while the "accent" channel represents the page within. 


e_undo_redo.xcf

	Both the undo and redo icons are combined in this .xcf file, since one is just the horizontal mirror of the other. I didn't rotate these two icons, since I felt it would look strange. 
	
	These icons are only one color, so there's only one channel.  The channel is built around the undo icon only.  Once you activate it as the selection and fill it with whatever color, you should then duplicate that layer and flip it horizontally to create the redo icon. 


f_new.xcf

	This icon accepts up to two colors, so there are two channels. The "page" channel represents the main body of the icon, while the "accent" channel is the upper-right corner.


open.xcf

	This icon accepts up to two colors, but there are actually three channels: The "front" channel is for the foreground part of the folder icon and the "back" channel is for the background part of the icon. The spacer is just the front channel "grown" by 1-2 px. 
	
	Here's how to use these three channels. First make "back" the selection (right-click > Channel to Selection). Then right-click "spacer" and select Subtract from Selection. This should remove the bottom-right portion of the "back" selection. Create a new layer and fill your selection with your first color. Now go back to the Channels tab and make "front" the selection. Return to your new layer and fill the selection with your second color.  
	
	I decided not to rotate this icon since the two elements of this icon are already inclined relative to each other. 
	

f_save.xcf

	This icon accepts up to two colors, so there are two channels. The "body" channel is the main part of the diskette while the "accent" channel represents the little sliding door found on 3 1/4" disks. 


indent_unindent.xcf

	Like undo/redo above, both the indent icon and the unindent icon are combined in this .xcf file, since one is just the horizontal mirror of the other. I didn't rotate these icons because I felt it would look strange.  
	
	The icon accepts up to two colors, so there are two channels.  The "base" channel includes the arrow and the top and bottom bars, while the "accent" channel contains the two middle bars. 
	
	The channels are based on the indent icon.  Once you create a layer and fill each channel selection with your desired color, you can then duplicate the layer and flip it horizontally to create the unindent icon.


opt.xcf

	This icon accepts up to two colors, so there are two channels. The "box" channel is for the surrounding border box and the "check" channel is for the checkmark in the middle. 


unpri.xcf

	This icon is a single color with no accent colors.  Therefore, there is only channel. 
	
