<html>
    <head>
        <title>constructor</title>
    </head>
    <body>
        <h1>demo on constructor function</h1>
        <script>
            function Book(a,b,c,d)
            {
               this.name = a;
               this.year = b;
               this.author = c;
               this.price = d;
            }
           const firstBook = new Book("C prog",2021,"DR",400);
           const secondBook = new Book("HTML",2022,"tim",500);
           document.write('${firstBook.name} ==> ${firstBook.price}<br>');
           document.write('${secondBook.name} ==>${secondBook.price}<br>');
        </script>
    </body>
</html>
