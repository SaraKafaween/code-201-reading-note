# HTML & JavaScript

![html](https://th.bing.com/th/id/OIP.UGH-vmmPxDNGBx8n_H2esAHaE8?w=252&h=180&c=7&o=5&dpr=1.25&pid=1.7)

Examples of HTML objects that you interact with when using JavaScript are windows, text fields and images.

In the chart below, I have outlined the different tags used in HTML and the JavaScript that will accompany each when used together.

Two Choices
You have two choices when it comes to embedding JavaScript code in an HTML file:
![js](https://th.bing.com/th/id/R.73dade4a97aeba206ce59d07fdc94f04?rik=uzt%2b622xbiydBA&pid=ImgRaw&r=0)

You can use the <Script> and </Script> tag directly into the HTML page.
You can create an external file that has only JavaScript statements and contains a .js extension as opposed to an .html extension for an HTML document.
Example of JavaScript Directly Embedded in the HTML Document
<HTML>
<HEAD>
<SCRIPT LANGUAGE="JavaScript">
// JavaScript code goes here //
}

</SCRIPT>
</HEAD>
<BODY>

...Somewhere within your body you will refer to a value you assigned within your JavaScript, such as what to do when an image appears.

</BODY>
</HTML>

Example of JavaScript With an External, Separate JavaScript File
<HTML>
<HEAD>
<SCRIPT LANGUAGE="JavaScript" SRC="TheSeparateJSfile.js">
</SCRIPT>
</HEAD>
<BODY>