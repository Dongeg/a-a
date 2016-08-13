# a-a
区分a++和++a

    <!DOCTYPE HTML>
    <html>
    <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title>JS基础</title>
    <script type="text/javascript">
      var a=1;
      var sum1,sum2;
      sum1=a++; //a取自增前的值即1，然后再+1变成2
      sum2=++a; //a这一次自增前的值变成了2 ，先自增，再取值，为3
      document.write(sum1+"<br>");//sum1=1
      document.write(sum2);  //sum2=3
    </script>
    </head>
    <body>
    </body>
    </html>
    
a++ ： 把（a++）作为一个整体表达式，整个表达式的值是取自增前的值，然后自增<br>

++a : 也把（++a）作为一个整体表达式，先自增，整个表达式的值是取自增后的值<br>

