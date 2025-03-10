# Websites_Layout
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Page Title</title>
   <style>
    *{
      box-sizing: border-box;
    }
    body{
        font-family: Arial, Helvetica, sans-serif;
    }
    header{
      background-color: #666;
      text-align: center;
      padding: 30px;
      font-size: 35px;
      color: white;
    }
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      overflow: hidden;
      background-color: #333333;
    }
    nav ul li {
      float: left;
    }
    nav ul li a {
      display: block;
      color: white;
      text-align: center;
      padding: 16px;
      text-decoration: none;
    }
    nav ul li a:hover {
      background-color: #111111;
      color: red;
    }
    aside{
      float: left;
      width: 30%;
      height: 300px;
      padding: 20px;
      background-color: #ccc;
    }
    aside ul{
      list-style-type: none;
      
    }
    aside ul li{
      margin: 10px;
    }
    aside ul a{
      text-decoration: none;
      padding: 35px 0;
    }
    aside ul li a:hover{
      color: red;
    }
    main{
      float: left;
      width: 70%;
      padding: 20px;
      background-color: #f1f1f1;
    }
    
    section{
      content: "";
      display: table;
      clear: both;
    }
    footer{
      background-color: #777;
      text-align: center;
      padding: 10px;
      font-size: 35px;
      color: white;
    }
   </style>
   <script>
   </script>
    
  </head>
  <body>
    <header>
      <h2>Header</h2>
    </header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#news">News</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#about">About</a></li>
      </ul>
    </nav>
    <section>
      <aside>
        <ul>
          <li><a href="#">Option 1</a></li>
          <li><a href="#">Option 2</a></li>
          <li><a href="#">Option 3</a></li>
        </ul>
      </aside>
      <main>
        <article>
          <h1>Option 1</h1>
          <p>
            <pre>
              Lorem Ipsum is simply dummy text of the printing and typesetting industry.
              Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
              when an unknown printer took a galley of type and scrambled it to make a type specimen book.
              It has survived not only five centuries, but also the leap into electronic typesetting,
              remaining essentially unchanged. It was popularised in the 1960s with the release of
              Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing
              software like Aldus PageMaker including versions of Lorem Ipsum.
            </pre>
          </p>
        </article>
        <article>
          <h1>Option 2</h1>
          <p>
            <pre>
              Lorem Ipsum is simply dummy text of the printing and typesetting industry.
              Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
              when an unknown printer took a galley of type and scrambled it to make a type specimen book.
              It has survived not only five centuries, but also the leap into electronic typesetting,
              remaining essentially unchanged. It was popularised in the 1960s with the release of
              Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing
              software like Aldus PageMaker including versions of Lorem Ipsum.
            </pre>
          </p>
        </article>
        <article>
          <h1>Option 3</h1>
          <p>
            <pre>
              Lorem Ipsum is simply dummy text of the printing and typesetting industry.
              Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
              when an unknown printer took a galley of type and scrambled it to make a type specimen book.
              It has survived not only five centuries, but also the leap into electronic typesetting,
              remaining essentially unchanged. It was popularised in the 1960s with the release of
              Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing
              software like Aldus PageMaker including versions of Lorem Ipsum.
            </pre>
          </p>
        </article>
      </main>
    </section>
    <footer>Footer</footer>
  </body>
</html>
