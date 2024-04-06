# Test account from Nate for 360&5

* Part 1. Modification of product page

- Create a new product on the Shopify backend with multiple variants. Upload placeholder product images to the new product.
- Modify the product image gallery on the product page using GlideJS library
- The product image gallery should look like ### [Thirsty Website](https://www.thirsty.com.sg/collections/beer/products/kona-big-wave-golden-ale-can?preview_theme_id=120722686015)
- Change the add to cart button on the product page to "Preorder" when a product is tagged with preorder on the backend. When the variant is changed, the button should still remain as “Preorder”.
- Add 2 new controls under Customise Theme > Theme Settings > Colors to change the background color and text color of the add to cart button on the product page

* Part 2. Creation of new template

Create a new page under Online Store > Pages
Create a new page template ### [page.test.liquid] in the theme codes, and assign the template to the page
On the new page template, it should look like [Whimsical.com](https://whimsical.com/8vHyJ87aQ3HGUdS4xf7zuj)

* Part 3. Javascript Test

This is done outside Shopify. This is done using a static HTML file.
Please download the HTML file from [Dropbox](https://www.dropbox.com/s/pmg4w2ecclxesh4/candidate-test.html?dl=0)
Create a page like in the attached video [Video](https://www.dropbox.com/s/pm7x5wfabxjm18w/Screen%20Recording%202023-04-25%20at%2012.47.50%20PM.mov?dl=0)

There is a sports variable in the <script> that has an array of objects.
The object contains the information of the sport.

Follow the instruction below:

1. Add radio buttons for user to select a sport. The question is "What do you want to do for sport activity today?"
2. A box for each sport
3. On selecting the radio button, change the background color of the box to bg_color of selected sport.
4. Animate "box Me" to move to selected sport box.
5. Display the selected sport name below the box.
6. Display list of equipments for the selected sport below the selected sport name text.

In this file, you will find jQuery and Vue script that's commented.
You have to do it using vanilla javascript and jquery.
If you can do it using Vue JS, it is a plus.

We need 3 HTML files in total. 

1 using vanilla JS
1 using jquery
1 using Vue
