# Login-Signup-page
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap project</title>
    <link rel="stylesheet" href="stylee.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
</head>

<body>
    
    <!-- py-paddding y axes -->
    <section class="login py-5 bg-light">
        <div class="container">
            <div class="row g-0">
                <div class="col-lg-5">
                    <img src="https://www.travelandleisure.com/thmb/9gQ91EXCiDndvOcJ2XxJqy5hDw0=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/TAL-aurora-borealis-iceland-summer-AUGSPACE0822-c3b7723dafc049278b59895c186cf926.jpg" alt="">
                </div>
                <div class="col-lg-7 text-center py-5">
                    <h1 class="animate__animated animate__flash">Welcome Here !!!!</h1>

                    <form>
                        <div class="form-row py-2 pt-5">
                            <div class="offset-1 col-lg-10">
                                <input type="text" class="inp px-3" placeholder="Username">
                            </div>
                        </div>

                        <div class="form-row py-2">
                            <div class="offset-1 col-lg-10">
                                <input type="password" class="inp px-3" placeholder="Password">
                            </div>
                        </div>

                        <div class="form-row py-2">
                            <div class="offset-1 col-lg-10">
                                <button type="button" class="btn1">Signup</button>
                            </div>   
                        </div>
                    </form>

                    <p>Or login with</p>
                    <span><i class="fa fa-facebook"></i></span>
                    <span><i class="fa fa-google"></i></span>
                    <span><i class="fa fa-instagram"></i></span>
                    <span><i class="fa fa-twitter"></i></span>
                    <span><i class="fa fa-envelope"></i></span>
                 
                </div>
            </div>
            <!-- lg-largest -->
        </div>
    </section>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>
    
</body>

</html>

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
 }
.row{
     background-color: white;
     border-radius: 30px;
     box-shadow: 12px 12px 27px;
     width: auto;
     height: 37.5rem;
 }
img{
     width: 130%;
     height: 37.5rem;
     border-top-left-radius: 290px;
     border-bottom-right-radius: 290px;
     border-top-right-radius: 30px;
     border-bottom-left-radius: 30px;
 }
.login h1{
    font-size: 3rem;
    font-weight: 300;
 }
.inp{
    height: 50px;
    width: 55%;
    outline: none;
    border-radius: 60px;
    box-shadow: -26px -19px 30px -19px rgba(0, 0, 0, 0.45);
    background: radial-gradient(circle, rgba(103,178,241,1) 9%, rgba(150,233,148,1) 61%);
 }
 
.btn1{
     width: 200px;
     height: 40px;
     border: none;
     border-radius: 60px;
     background-color: #0a9e97;
     color: white;
 }
.btn1:hover{
     background-color:#27bb94 ;
     transition: linear 0.5s;
 }

.fa-facebook{
    padding: 10px;
    font-size: 30px;
    display: flex;
    color: #3b5998 ;

}

.fa-facebook:hover{
    background-color: #3b5998;
    color: white;
 }
 .fa-google{
     padding: 10px;
     font-size: 30px;
 }
 .fa-google:hover{
     background-color: #DB4437;
     color: white;
  }
 .fa-instagram{
     padding: 10px;
     font-size: 30px;
 }
 .fa-instagram:hover{
     color: white;
     background-color: rgb(214,41,118);
  }
 .fa-twitter{
     padding: 10px;
     font-size: 30px;
 }
 .fa-twitter:hover{
     color: white;
     background-color:  #00acee;
  }
 .fa-envelope{
     padding: 10px;
     font-size: 30px;
 }
 .fa-envelope:hover{
     color: white;
     background-color: #e2a564;
  }
  p{
     padding-top: 25px;
     color: rgb(3, 39, 41);
     font-size: 1.10rem;
     font-weight: 480;
  }
  p:hover{
   cursor: pointer;
   text-decoration: underline;
   font-weight: 550;
 }


