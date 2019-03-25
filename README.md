# gigglygiraffe

File Names:
. index.html
. gigglygiraffe.CSS
. showMore.js

Section One:
  My project is just a basic informational site, the subject content of the page is predominantly giraffe related with a few extra links connected to related webpages(Giraffe Conservation Foundation, American Wildlife Foundation and SeaWorld!).  I intended for this site to be fun, simple and easy to navigate for the user.  I also developed this site with everyone in mind...including families! The link named Kids Zoo is exactly that, a cyber zoo for kids! Complete with pictures, videos and tons of fun facts.  Overall I enjoyed this experience and I'm please with the website I created.  I received tons of information, which was then applied to a hands on requirement, I enjoyed every minute  and  I can't wait to dive deeper into the field of Software Development.

Section Two:
  Three Custom CSS Styles I created are:
1. h1 {
  box-shadow: 5px 5px 5px 10px rgba(0, 0, 0, .5);
  background-image: url(https://static.vecteezy.com/system/resources/previews/000/092/728/large_2x/giraffe-print-vector.jpg);
  background-color: #EAEFBD;
  text-align: center;
  color: white;

  padding: 10px;
  border-radius: 25px;
  margin: 25px;
 }
***This rule directly effects all my h2 elements I used a back-ground image to apply giraffe print to the headers and I also used the box-shadow property to give the elements some flare. Overall I'm happy with the result and think it makes for a fun page.

2. blockquote {
  background-color: #EAEFBD;
  text-align: center;
  padding: 10px;
  border-radius: 25px;
  margin: 25px;
 }
***This is rule here is applied to a small bit of text in my blockquote element.  In this rule I'm demonstrating simple text control and alignment. Just an example of base knowledge in CSS.

3. button {
  background-image: url(https://static.vecteezy.com/system/resources/previews/000/092/728/large_2x/giraffe-print-vector.jpg);
	border-radius: .5px;
	padding: 0.5rem 0.5rem;
  text-align: center;
	color: white;
 }
***This rule here is simply to style the button on my page that fires the JavaScript function.  Just some text control and a background-image.
--------------------------------------------------------------------------------------------------------------------------------------------------

  The  custom class(es) I created are:
1.  .container {
  border-style: dotted;
  border-color: #EA9010;
  padding: 25px;
  margin: 25px;
 }
***This class affects all the content on my page, this block of code targets the class container. Just a little margin control and padding, I also added a border using the border-style property and gave it some color.


***All three of the CSS selectors below are directly related to my JavaScript function.  The styles below consist of some basic text and spacing control as well a border-style property.  The exciting part about this piece of code is the transition set-up, with these properties I can control the rate of speed in which my div shows more or shows less content.  It was a fun concept to work with and interesting to figure out how to make it more visually pleasing to the user.

2. #content {
  border-style: dotted;
  border-color: #EA9010;
  padding: 20px;
  margin: 20px;
  max-height: 500px;
  overflow: hidden;
  /*Transition Set-Up*/
  -webkit-transition: max-height 0.7s;
  -moz-transition: max-height 0.7s;
  transition: max-height 0.7s;
 }

3. #content.open {
    max-height: 1000px;

    /*Transition Open Set-Up*/
    -webkit-transition: max-height 0.7s;
    -moz-transition: max-height 0.7s;
    transition: max-height 0.7s;
 }

4. #show-more {
  background-image: url(https://static.vecteezy.com/system/resources/previews/000/092/728/large_2x/giraffe-print-vector.jpg);
  border-radius: .5px;
  padding: 0.5rem 0.5rem;
  text-align: center;
  color: white;
 }

Section Three:
  JavaScript functions I created are:

1. button.onclick = function() { };

***The JS function(.onclick) is used to target the content div to expand and shrink the text area.  To accomplish this I wrote an  if/else statement that targets a button and using the .onclick function, the statement says than when the button is clicked; expand the text area to 1000px and change the button text to "Show Less", else keep max-height of 500px.
