# CLOCK-
This is basic clock made with html css and javascript
<!doctype html>
<html lang="en">
  <head>
      <!-- script for cloack -->
      <script>
          setInterval(() => {
              
          
          a=new Date();
          let date=a.toLocaleDateString();
          let clock =a.getHours() +':'+ a.getMinutes()+':'+a.getSeconds()
         document.getElementById('time').innerText= clock 
         document.getElementById('Datee').innerHTML=date

        }, 1000);

      </script>



    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title>claock.html</title>
  </head>
  <body>
    <div class="jumbotron">
      <div class="container">
        <h1 class="display-4">Current Time is:   <span id="time"></span></h1>
        <h1 class="display-4">Current Date is:   <span id="Datee"></span></h1>
      
        <p class="lead">This is current time and date for more countries time-zone click below </p>
      </div>
    
    </div>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>

