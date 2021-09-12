<!DOCTYPE html>
<html lang="en">
<head>
    <title>OLIN BUSINESS SCHOOL</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
      *{
        margin: 0;
        padding: 0;
      }
       #header{
           background-color: rgb(61, 4, 4);
           height: 80px;
       }
       .brand{
        width:30%;
        height: 80px;
        float:left;
       }
       .brand h2{
        color: #fff;
        text-align: center;
        line-height:80px;
       }
       .navbar{
        width:70%;
        height: 80px;
        float:right;
        text-align: center;
        line-height: 80px;
       }
       .navbar a{
           color: #fff;
           font-size: 20px;
           font-weight: 300px;
           text-decoration: none;
           margin-right: 80px;
       } 
       h4{
           color:red;
           font-style: italic;
           text-align: center;
           line-height: 2;
       }
       h3{
           color: rgb(15, 1, 1);
           font-style: italic;
           text-align: center;
           line-height: 3;
       }
     #main tr td img{
         
         width:350px;
         height:400px;
         border-radius:50%;
         margin-top: 8%;
        }
        #main{
            text-align: center;
        }
        #main tr td p{
            line-height:1.5;
            font-size: 17px;
            font-style: italic;
            letter-spacing: 1px;
            color: rgb(15, 1, 1);

        }
        #main h2{
            line-height: 2;
            font-size: 25px;
        }
        .main2 td img{
            width: 200px;
            height:200px;
            border-radius:50%;
            margin-top: 70px;
            margin-left: 83px;
        }
        #footer{
            height:150px;
            line-height: 90%;
            background-color: rgb(15, 1, 1);
            top: 90%;
            position: relative;
        }
        #footer .para-footer p{
            color: silver;
            font-size: 15px;
            text-align:center;
            line-height: 1.3;
        }
        .footer-icon {
            font-size: 25px;
            text-align: center;
            line-height: ;
        }
        .footer-icon i{
            color: silver;
            margin-right: 20px;
            line-height:3;
        }
   </style>
</head>
<body>
    <div>
        <div id="header">
            <div class="brand">
               <h2>OLIN BUSINESS SCHOOL</h2>
            </div>
            <div class="navbar">
               <a href="#">Careers</a>
               <a href="#">Blog</a>
               <a href="#"> About</a>
               <a href="#"> Events</a>
            </div>
        </div>
        <div id="main">
            <table style="width:100%">
            <tr>
              <td style="width:60%;">
                <h4>OLIN BUSINESS SCHOOL!!!!</h4>
                <h2>Resources & Initiatives</h2>
                        <p style="width: 100%;">We want WashU Olin students to stay connected—to courses, classmates, instructors and the school. That’s why we created learn.WashU, a next gen, proprietary learning management system without parallel. From specially designed class sessions to robust communication tools to lifelong learning opportunities, you’ll remain engaged and continue to grow long after you leave your student days behind you.
                          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt mollitia hic ducimus velit voluptates sunt facilis harum facere, fugiat atque sit magni ullam, quasi dolore? Repudiandae a alias repellat ipsa.
                        </p>
              </td>
              <td style="50%"><img src="https://images.pexels.com/photos/2422294/pexels-photo-2422294.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="image1"></td>
            </tr>
            </table>
        </div>
        <hr>
        <div class="main2">
            <table style="width:100%;">
                <tr>
                    <td><img src="https://images.pexels.com/photos/1438081/pexels-photo-1438081.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt=""><h3>BUSINESS SCHOOL</h3></td>
                    <td><img src="https://images.pexels.com/photos/2422294/pexels-photo-2422294.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt=""><h3>BUSINESS SCHOOL</h3></td>
                    <td><img src="https://images.pexels.com/photos/1850021/pexels-photo-1850021.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt=""><h3>BUSINESS SCHOOL</h3></td>
                    <td><img src="https://images.pexels.com/photos/1699414/pexels-photo-1699414.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt=""><h3>BUSINESS SCHOOL</h3></td>
                </tr>
            </table>
        </div>
        <div id="footer">
            <div class="footer-icon">
                <span><a href="#"><i class="fa fa-university" aria-hidden="true"></i></a></span>
                <span><a href="#"><i class="fab fa-facebook"></i></a></span>
                <span><a href="#"><i class="fab fa-instagram "></i></a></span>
                <span><a href="#"><i class="fab fa-twitter-square "></i></a></span>
            </div>
            <div class="para-footer">
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non sapiente dicta error <br> hic accusamus ducimus numquam cumque corporis deserunt tempore!</p>
            </div>
        </div>
    </div>
</body>
</html>






curl -u pratiksha3112 https://api.github.com/user/repos -d '{"name" : "pratiksha3112.github.io"}'
