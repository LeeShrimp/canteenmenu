When creating a new item on the menu follow these steps:

1. Find an image, cut away background if necessary and make it transparent.
2. Image must be 200px (w) X 150px (h)
3. Save as a .png as these support transparency 
4. Save image in appropriate folder for its category eg. Cold Food, Snacks
5. Label clearly and with no spaces. 
6. Copy this block of code and fill in its name, price and size if needed. 
   Name should be less than 28 characters (INCLUDING SPACES) to fit page properly
   
   **IF THERE IS NO IMAGE AVAILABLE PUT THIS AS IMAGE LINK -> ../img/placeholder.jpg	
	
		<div class="items">
                        <!--Name of item-->
                        <h3>**NAME OF ITEM**</h3>
                        <!--Link to image. Link goes inside of quote marks eg. src="here"-->
                        <img  class="item-img" src="../img/**FOLDER NAME HERE**/*IMAGE NAME HERE**" alt="**IF ITEM NAME DOES NOT FULLY FITIN ABOVE SLOT YOU CAN PUT A FULL DESRICPTION HERE**">
                        <!--Price and size-->
                        <p><strong>$0.00</strong> <em style="font-size: small">000ml</em></p>
    		</div>


7. Fill in the *FOLDER NAME HERE** & **IMAGE NAME HERE**
8. If item has no ml size then just delete the 000ml and it will show blankx

Extra notes:
-all link to images MUST stay within the " " marks
-links are case sensitive
-prices and size MUST stay within these > and < signs
-need to save the file after each change for it to take effect