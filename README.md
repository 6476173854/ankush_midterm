<!DOCTYPE html>
<html>
<head>
    <title>Midterm</title>
    <style>
        header {
    position: relative;
    text-align-last: auto;
    top: 2opx;
    margin-left: auto;
    margin-right: auto;
}

header img {
    width: 100%;
    height: auto;
    size: 100px;
    position:centre;
    text-align: center;
}

 h1 {
    position: absolute;
    color: rgb(231, 125, 125);
    font-size: 24px;
    text-align: center;
}

/* CSS for article */
article img {
    float: left;
    margin-right: 20px;
}

/* CSS for facts */
.facts {
    background-color: #f0f0f0;
    padding: 10px;
}

/* CSS for form */
form {
    margin-top: 20px;
}

label {
    display: block;
    margin-bottom: 5px;
}
footer{
    background-color: aqua;
}

.menu{
    font-size: 22px;
    padding-top: 11px;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 800;
    color: #a12626;
    text-align: center;  
}
.menu li {
    border-style: solid;
    border-width: 0px 3px 0px 0px;
    border-color: #ffe4da;
    display: inline-block;
    width: 30%;
}

.menu li:last-child{
    border-width: 0px;
}

    </style>
</head>
<body>
    <header>
        <img src="images/download.jpg" alt="Header Image">
    </header>
        <h1>AMAZON</h1>
         <div class="menu">
            <ul>
            <li>Home</li>
            <li>Story</li>  
            <li>Contact</li>
       </ul>
    </div>


    <article>
        <img src="images/download.jpg" alt="Article Image">
        <p>In 1994 Jeff Bezos, a former Wall Street hedge fund executive, incorporated Amazon.com, choosing the name primarily because it began with the first letter of the alphabet and because of its association with the vast South American river. On the basis of research he had conducted, Bezos concluded that books would be the most logical product initially to sell online. Amazon.com was not the first company to do so; Computer Literacy, a Silicon Valley bookstore, began selling books from its inventory to its technically astute customers in 1991. However, the promise of Amazon.com was to deliver any book to any reader anywhere..</p>
    </article>

    <section class="facts">
        <h2>Facts about amazon</h2>
        <ol>
            <li> : Something interesting they give to consumer</li>
            <li> : A to z items</li>
            <li> : best website ever</li>
        </ol>
    </section>

    <form>
        <label for="input1">Your name:</label>
        <input type="text" id="input1" name="Your name"><br>

        <label for="input2">Your email:</label>
        <input type="text" id="input2" name="Your email"><br>

        <label for="input3">Your message:</label>
        <input type="text" id="input3" name="your message"><br>

        <input type="submit" value="Submit">
        <input type="cancel" value="cancel">
    </form>
  
</body>
<footer>@2023 BY ANKUSH</footer>
</html>
