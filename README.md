# HTML in-class  exercise

Now that you have a sense of how HTML works, you can try it out for yourself. We will be working in the prestigious world of online advertising today, trying to sell some exercise equipment from the 1800's. 

You will be using the "mechanical_exercise.html" document to start. There is nothing special about this document. It is just a plain text document with the extension ".html". 

#### 1. Open *mechanical_exercise.html* in a web browser

You can see there is some text there, but it looks a little planer than most webpages. 

#### 2. Open it in Brackets

You should see the same plane text. This is actually the beauty of HTML. At its heart its just text. We will now use our new knowledge of HTML tags to give that text some context and meaning.

#### 3. Create headings

In HTML headings are defined in a numbered hierarchy: *&lt;h1&gt;* to *&lt;h6&gt;* with *&lt;h1&gt;* being the most important heading on the page, and consequently the biggest.

* **Make "Mechanical exercise" the most important heading on the page.**
* **Make "A means of cure." the second most important heading.**
* **Make "Hours:" the next most important heading.**
* **Make "Gentlemen" and "Ladies" both the the fourth most important headings**

Remember that tags should surround the text they "mark" with opening an closing tags. Save the document and use the lightning bolt icon in brackets (upper left) to view the live preview of the page.

#### 4. Create paragraphs

For normal text the *&lt;p&gt;* tag or paragraph helps group text.

* **Make the three lines starting with "Also useful in promoting..." and ending in "both in London and the Provinces." each into its own paragraph with *&lt;p&gt;* tags.**
* **Make the time periods under "Gentlemen" and "Ladies" both paragraphs, as well as "Inspection of the machines..." and the address at the end.**

#### 5. Nested tags

Now that we have tags most everything on the page. Lets add some tags to emphasize certain content. Paragraph and heading tags are known as *block* tags. Which means they create a block or box around their content. In our simple page this means a newline with some space between it and the next element. You can also create inline elements, which can surround an element without moving it to a new line.

* **Use the *&lt;strong&gt;* tag to make the word "free" in the "Inspection of the machines..." paragraph stand out.**

#### 6. Add a link

* **Use an anchor tag to create a link from the final line ("Zander Institution, 7, Soho Square, W.C
") to [this Google Map](https://www.google.com/maps/place/7+Soho+Square,+Soho,+London+W1D+3QB,+UK/@51.5156278,-0.1356578,17z/data=!3m1!4b1!4m2!3m1!1s0x48761b2cc7d02d9f:0x705118394b7a3bad) of that address.**

*Remember that when linking to another website in HTML. You must include the full url including "http://" at the beginning.*

#### 7. Mark the ailments as a list.

HTML has tags for both ordered(numbered) and unordered(bulleted) lists. The series of ailments near the top is perfect for an unordered list. 

* **Research how to use an *&lt;ol&gt;* tag to make a bulleted list at http://www.w3schools.com/tags/**
* **Mark the series of ailments near the top of the page as a list**

*http://www.w3schools.com is a great reference for this course with both tutorials and definitions for HTML, CSS and JavaScript terms.*


#### 8. Insert an image.

We have defined the heirarchy of most of the text on the page. Now lets add an image to show off our fancy exercise equipment.

* **Add an image tag with the src set to "engraving.jpg" just below the paragraph ending "... both in London and the Provinces." **
* **Add an "alt" attribute to the image tag that gives a short description of the image.**

---
##Bonus tasks

If you have time, research (http://www.w3schools.com/tags/) the following items and add them to the page. If you get stuck or aren't sure the point of all these tags, don't worry. We will talk more about them next week.

* **Add a *&lt;!DOCTYPE &gt;* tag to the document**
* **Add a *&lt;html&gt;* tag**
* **Add a *&lt;body&gt;* tag**
* **Add *&lt;head&gt;* and *&lt;title&gt;* tags**
