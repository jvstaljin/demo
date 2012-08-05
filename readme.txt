
=== Getting Started ===

The first thing you want to do is copy the _s directory and change the name to something else. Like, say, megatherium. Then you'll need to do a three-step find and replace on the name in all the templates.

1. Search for _s inside single quotations to capture the text domain.
2. Search for _s_ for to capture all the function names
3. Search for _s with a space before it to replace all the occurrences of it in comments. (You'd replace this with the capitalized version of your theme name.)

or ...

Search for:'_s'
Replace with:'megatherium'
Search for:_s_
Replace with:megatherium_
Search for: _s
Replace with: Megatherium

Then, update the stylesheet header in style.css and the links in footer.php with your own information. Next, update or delete this readme.

Now you're ready to go! The next step is easy to say but harder to do: make an awesome WordPress theme. :)

Good luck!