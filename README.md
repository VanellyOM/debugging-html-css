# Debugging results.

## HTML Errors and Warnings

- Warning: This document appears to be written in English. Consider adding lang="en" (or variant) to the html start tag.
From line 1, column 16; to line 2, column 6
<!--<html>-->
<html lang="en">

- Error: Element meta is missing one or more of the following attributes: charset, content, http-equiv, itemprop, name, property.
From line 5, column 5; to line 5, column 10
<!-- <meta> -->
<meta charset="UTF-8">


- Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.
From line 6, column 5; to line 6, column 76
<!-- <meta name="viewport" content="width=device-width, initial-scale=1.0" /> -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

- Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images. 
From line 19, column 7; to line 19, column 46 
<!-- <img src="easter-bunny-150-profile.png"> -->
<img src="easter-bunny-150-profile.png" alt="Profile picture of the Easter Bunny">

- Error: Element p not allowed as child of element h3 in this context. (Suppressing further errors from this subtree.)
From line 60, column 13; to line 60, column 15
* <!-- <h3>Enough Content -->
  <h3>Enough Content</h3>

* <!-- <p>You need enough content to thoroghly populate your page. The content should cause the page to be long enough to need to scroll. Keep copy/pasting content from Wikipedia until you have enough content to scroll. You will use this page later to embellish it with styles, color, formatting and layouts.</p> -->
  <p>You need enough content to thoroughly populate your page. The content should cause the page to be long enough to need to scroll. Keep copy/pasting content from Wikipedia until you have enough content to scroll. You will use this page later to embellish it with styles, color, formatting and layouts.</p>  

---------------------

## CSS Errors and Warnings
### STYLE.CSS

* <!-- color: #B2; --> 
color: #B2D732;

* <!-- font-size: 5 vw; -->
font-size: 5vw;

* <!-- line-height: 1.35me; -->
line-height: 1.35em;


<!-- 
.error {
	color: #FE27122;
} -->
.error {
	color: #FE2712;
}

<!-- text-decoration: all;} -->
text-decoration: underline;


### LAYOUT.CSS

<!-- 
  dt {
    font-weight: bold;
  }

  dd {
    padding: 0 10px;
  }
} -->

}
aside dt {
    font-weight: bold;
  }

aside dd {
    padding: 0 10px;
  }
