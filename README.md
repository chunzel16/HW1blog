# HW1blog
[Demo](https:l)
The first homework request me to learn HTML and CSS, use git bash.


## 1: Setup
I took this course last year, so I already have git in my computer, but I sign up a new account for GitHub. 

At first, I create a file named README
```
git init
git add README.md 
git commit -m "First commit."
```
Then, I got a remote control for pushing something to my GitHub

```
git remote add origin https://github.com/chunzel16/chunzel16.github.io.git
git remote -v 
origin  https://github.com/chunzel16/chunzel16.github.io.git (fetch)
origin  https://github.com/chunzel16/chunzel16.github.io.git (push)
```
Then I can push my file to website


## Website
I used the Bootstarp template. I think this template is simple and easy to understand
```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
      <link rel="stylesheet" type="text/css" href="style.css">

    <title>Shoes</title>
  </head>
    <body>
    <div class="container" id="banner">
        <h1>Foot need shoes</h1>
    </div>
            
    <div id="first">
        <nav class="navbar navbar-default">
            <div class="container">
                <ul class="nav navbar-nav">
                    <li class="active"><a href="./index.html">HomePage</a></li>
                    <li><a href="./Nike.html">Nike</a></li>
                    <li><a href="./Vans.html">Vans</a></li>
                    <li><a href="./Contact.html">Contact</a></li>
                </ul>
            </div>
        </nav>
    </div>
        <div class="pagebackground">    
        <div class="container">
            <div class="content">
               <h2>Let's enter the world of shoes.</h2>
                   <p>Shoes are indispensable in our life. Put on your new shoes and go for a walk.</p>
            </div>
        </div>
    </div> 
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>
```
I want to design a simple webpage for shoes, because I like shoes, like Air Jordan and Vans. I decide to find some photos from Google, 
and then, put it on my page. At first, Air Jordan.

```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
      <link rel="stylesheet" type="text/css" href="style.css">

    <title>Shoes</title>
  </head>
    <body>
    <div class="container" id="banner">
        <h1>Foot need shoes</h1>
    </div>
            
    <div id="first">
        <nav class="navbar navbar-default">
            <div class="container">
                <ul class="nav navbar-nav">
                    <li class="active"><a href="./index.html">HomePage</a></li>
                    <li><a href="./Nike.html">Nike</a></li>
                    <li><a href="./Vans.html">Vans</a></li>
                    <li><a href="./Contact.html">Contact</a></li>
                </ul>
            </div>
        </nav>
    </div>
        <div class="pagebackground">    
        <div class="container">
            <div class="content">
               <h2>Aj shoes are nice</h2>
                  <div class="row">
                        <div class="col-md-6">
                            <img class="img-responsive" src="images/chicago.jpg" alt="Witch">
                        </div>

                        <div class="col-md-6">
                            <img class="img-responsive" src="images/bred.jpg" alt="Suburban" >
                        </div>
                    </div> 
            </div>
        </div>
    </div> 
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>
```

The "Vans" page. I also put two photos on my page

```

        <div class="pagebackground">    
        <div class="container">
            <div class="content">
               <h2>Welcome</h2>
                   <h2>I also like Vans</h2>
                  <div class="row">
                        <div class="col-md-6">
                            <img class="img-responsive" src="images/vans1.jpg" alt="Witch">
                        </div>

                        <div class="col-md-6">
                            <img class="img-responsive" src="images/vans2.jpeg" alt="Suburban" >
                        </div>
         
```
On the last page, I want to show my contact form in table.

```
<table class="table table-striped">
                   <tbody>
                       <tr>
                           <td>WeChat</td>
                           <td>lcz843869035</td>
                       </tr>
                       <tr>
                           <td>Email</td>
                           <td>cliu16@wou.edu</td>
                       </tr>
                       <tr>
                           <td>PhoneNumber</td>
                           <td>15042295553</td>
                       </tr>
                       
                   </tbody>
               </table>
```

I set each repository to GitHub page mode, and each repository has its own domain name, which makes it easy for me to link.
I try my best to finish this homework, I think I need spend more time to study program. By the way, I use Brackets for coding!
