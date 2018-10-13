---
layout: page
title: Contact Me
permalink: /contact/
---

<head>
   <style>

    /* When moving the mouse over the submit button, add a darker green color */
	input[type=email], select, textarea {
    	width: 300px;
	}
    /* Style inputs with type="text", select elements and textareas */
	input[type=text], select, textarea {
   		width: 100%; /* Full width */
   		height: 150px;
   		padding: 12px; /* Some padding */  
    	border: 1px solid #ccc; /* Gray border */
    	border-radius: 4px; /* Rounded borders */
    	box-sizing: border-box; /* Make sure that padding and width stays in place */
    	margin-top: 6px; /* Add a top margin */
    	margin-bottom: 6px; /* Bottom margin */
    	resize: vertical /* Allow the user to vertically resize the textarea (not horizontally) */
	}

	/* Style the submit button with a specific background color etc */
	input[type=submit] {
    	background-color: #4CAF50;
    	color: white;
    	padding: 12px 20px;
    	border: none;
    	border-radius: 4px;
    	cursor: pointer;
	}

	/* When moving the mouse over the submit button, add a darker green color */
	input[type=submit]:hover {
   		background-color: #45a049;
	}

	/* Add a background color and some padding around the form */
	.container {
   		border-radius: 5px;
    	background-color: #f2f2f2;
    	padding: 20px;
	}
   </style>
  </head>

<h4>Phone:</h4> +1 778 302 6768

<h4>Send me a message below!</h4>

<form method="POST" action="https://formspree.io/osman.hajiyev@gmail.com">
  <input type="email" name="email" placeholder="Your email">
  <textarea name="message" placeholder="Your message"></textarea>
  <button type="submit">Send</button>
</form>