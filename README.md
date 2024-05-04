Certificate Display Website in HTML

I am creating a website to display my certificates i’ve obtained from veriose online course. The idea from this came from viewing a industry profesionals linkedin that elegantly hosted his certificates on AWS amazons 3s using bucket
because i didn’t feel like using google drive to host my certificates looked and fellt profesionall. Initalitly i started researching how to implement the same solution using bucket but due to the solution not being free 
I decided to explore alternatives that would allow me to host and display my certificates on a personal website using Github pages. First I found a HTML code to upload a pdf but this solution uses the Docs viewer from google 
that has the button for downloadning the certificate. The dowloading in itself is not a problem for me but rather the idea that theres a unecesary buttom showing makes it less clean and i want to keep it minemalistic.
So to solve this i will load the files as images instead of PDFs, creating a more streamlined and minimalist website. Since i m starting this project without previous knowledge about HTML I looked up a skeleton for HTML
create a file .HTML

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

...

</body>
</html>

 and than ive inserted the image tags to display the certificates on the page 


 <img src=" image_url.something " class="CENy8b" role="img">

 If you want to hoset a pdf use this instead.
 
 <iframe src=" pdf_url.something " style="width: 700px; height:  950px;" frameborder="0"></iframe>

 try different sizes for the pdf and see what works for you. thers also alternatives ways to define the frame size. 



2. Addin top navigation bar with CSS
   more info about how to do it https://www.w3schools.com/howto/howto_js_topnav.asp
   but before doing that read this https://www.w3schools.com/html/html_css.asp. Basicallly you "can't" mix html and css so you have to create a separate css file.
