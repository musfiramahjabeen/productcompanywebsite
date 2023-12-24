## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### Home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeConnections</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <header>

        <input type="checkbox" name="" id="toggler">
        <label for="toggler" class="fas fa-bars"></label>
        <a href="#" class="logo">CodeConnections<span>.</span></a>
        <nav class="navbar">
            <a href="#home">home</a>
            <a href="#about">about</a>
            <a href="#products">products</a>
            <a href="#review">review</a>
            <a href="#contact">contact</a>
        </nav>

        <div class="icons">
            <a href="#" class="fas fa-heart"></a>
            <a href="#" class="fas fa-shopping-cart"></a>
            <a href="#" class="fas fa-user"></a>
        </div>
    </header>

<section class="home" id="home">
    <div class="content">
        <h3>CodeConnections</h3>
        <span>power yourself</span>
        <p>Choose from over 210,000 online video courses with new additions published every month</p>
        <a href="#" class="btn">Purchase Now</a>
    </div>
</section>
  </body>
</html>

```
### Home.css
```
:root{
    --pink : #e84393;
}

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Verdana, Geneva, Tahoma , sans-serif;
    outline: none; border: none;
    text-decoration: none;
    text-transform: capitalize;
    transition: .2s linear;
    
}

html{
    font-size: 62.5%;
    scroll-behavior: smooth;
    scroll-padding-top: 6rem;
    overflow-x: hidden ;
    background: url(pawel-czerwinski-LS0CWcXo1dw-unsplash.jpg);
}

section{
    padding: 2rem 9%;
}

.heading{
    text-align: center ;
    font-size: 4rem;
    color: #333;
    padding: 1rem;
    margin: 2rem 0;
    background : rgba(255, 51, 153, .05);

}

.heading span{
    color: var(--pink);
}
.btn{
    display: inline-block;
    margin-top: 1rem;
    border-radius: 5rem;
    background: #333;
    color: #fff;
    padding: .9rem 3.5rem;
    cursor: pointer;
    font-size: 1.7rem;
}

.btn:hover{
    background: var(--pink);
}
header{
    position: fixed;
    top: 0; left: 0; right: 0;
    background: #fff;
    padding: 2rem 9%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    z-index: 1000;
    box-shadow: 0 .5rem 1rem rgba(0,0,0,.1);
}

header .logo{
    font-size: 3rem;
    color: #333;
    font-weight: bolder;
}

header .logo span{
    color: var(--pink);
}

header .navbar a{
    font-size: 2rem;
    padding: 0 1.5rem;
    color: #666;

}

header .navbar a:hover{
    color: var(--pink);
}

header .icons a{
    font-size: 2.5rem ;
    color: #333;
    margin-left: 1.5rem;

}

header .icons a:hover{
    color: var(--pink);
}

header #toggler{
    display: none;
}

header .fa-bars{
    font-size: 3rem;
    color: #333;
    border-radius: .5rem;
    padding: .5rem 1.5rem;
    cursor: pointer;
    border: .1rem solid rgba(0,0,0,.3);
    display: none;

}

.home{
    display: flex;
    align-items: center;
    min-height: 100vh;
    background: url() no-repeat;
    background-size: cover;
    background-position: center;

}


.home  .content h3{

    font-size: 6rem;
    color: #333;
    text-align: left;
}

.home  .content span{
    font-size: 50 rem;
    color: var(--pink);
    padding: rem 0;
    line-height: 1.5;
}

.home  .content p{
    font-size: 1.5rem;
    color: #999;
    padding: 1rem 0;
    line-height: 1.5;
}
```
### About.html
```
<!DOCTYPE html>
<html lang="en">
  <body>
   <section class="about" id="about">
    <h1 class="heading"> <span> about </span> us </h1>

<div class="row">
    <div class="video-container">
          <video src="The Power of Computer Science.mp4" loop autoplay muted></video>
          <h3>CodeConnections</h3>
     </div>
<div class="content">
<h3 class=>why choose us?</h3>
<p>We help organizations of all types and sizes prepare for the path ahead — wherever it leads. Our curated collection of business and technical courses help companies, governments, and nonprofits go further by placing learning at the center of their strategies.</p>
<a href="#" class="btn">learn more</a>
</div>

</div>
</section>


<section class="icons-container">
    <div class="icons">
        <img src="work wth us.png" alt="">
        <div class="info">
            <h3>Work with us</h3>
            <span>we’re all learners and instructors. We live out our values every day to create a culture that is diverse, inclusive, and committed to helping employees thrive.</span>
        </div>
    </div>

    <div class="icons">
        <img src="research.png" alt="">
        <div class="info">
            <h3>See our research</h3>
            <span>We’re committed to improving lives through learning. Dig into our original research to learn about the forces that are shaping the modern workplace.</span>
        </div>
    </div>
    
    <div class="icons">
        <img src="read-our-blog.jpg" alt="">
        <div class="info">
            <h3>Read our blog</h3>
            <span>Want to know what we’ve been up to lately? Check out the CodeConnections blog to get the scoop on the latest news, ideas and projects, and more.</span>
        </div>
    </div>
</section>
  </body>
</html>
```
### About.css
```
.about .row{
    display:flex;
    align-items: center;
    gap: 2rem;
    flex-wrap: wrap;
    padding: 2rem 0;
    padding-bottom: 3rem;
}

.about .row .video-container{
    flex: 1 1 40rem;
    position: relative;
}

.about .row .video-container video{
    width: 100%;
    border: 1.5rem solid #fff;
    border-radius: .5rem;
    box-shadow: 0 .5rem 1rem rgba(0,0,0,.1);
    height: 100%;
    object-fit: cover;
}

.about .row .video-container h3{
    position: absolute; 
    top: 50%; transform: translateY(-50%);
    font-size: 3rem;
    color: white;
    opacity: 50%;
    background: none;
    width: 100%;
    padding: 1rem 2rem;
    text-align: right; 
    mix-blend-mode: screen;
}

.about .row .content{
    flex: 1 1 40rem;
}



.about .row .content h3{
    font-size: 5rem;
    color: #333;
    text-align: left;


}



.about .row .content p{
    font-size: 1.5rem;
    color: rgba(0,0,0,.3);
    padding: .5rem 0;
    padding-top: 1rem;
    line-height: 1.5rem   ;
}


.icons-container{
    background: #eee;
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
    padding-top: 5rem;
    padding-bottom: 5rem;
}


.icons-container .icons{
    background:black;
    border: .1rem solid rgba(0,0,0,.1);
    padding: 2rem;
    display: flex;
    align-items: center;
    flex: 1 1 25rem;
}

.icons-container .icons img{
    height: 5rem;
    margin-right: 2rem;
}

.icons-container .icons h3{
    color: whitesmoke;
    padding-bottom: .5rem;
    font-size: 1.5rem;

}


.icons-container .icons span{
    color: whitesmoke;
    padding-bottom: .5rem;
    font-size: 1.3rem;
    
}

```
### Products.html
```
<!DOCTYPE html>
<html lang="en">
  <body>
   <section class="products" id="products">
    <h1 class="heading"> latest <span>products</span> </h1> 

    <div  class="box-container">
        <div class="box">
           <span class="discount"></span> 
           <div class="image">
            <img src="java script.jpeg" alt="">
            <div class="icons">
                <a href="#" class="fas fa-heart"></a>
                <a href="#" class="cart-btn">add to cart</a>
                <a href="#" class="fas fa-share"></a>
            </div>
           </div>
           <div class="content">
            <h3>The Complete JavaScript Course 2024: From Zero to Expert!</h3>
            <div class="price">$12.99 <span>$15.99</span></div>
           </div>
        </div>



        <div class="box">
            <span class="discount"></span> 
            <div class="image">
             <img src="learn python.png" alt="">
             <div class="icons">
                 <a href="#" class="fas fa-heart"></a>
                 <a href="#" class="cart-btn">add to cart</a>
                 <a href="#" class="fas fa-share"></a>
             </div>
            </div>
            <div class="content">
             <h3>The Complete Python Bootcamp From Zero to Hero in Python</h3>
             <div class="price">$9.99 <span>$15.99</span></div>
            </div>
         </div>


         <div class="box">
            <span class="discount"></span> 
            <div class="image">
             <img src="c programming.jpg" alt="">
             <div class="icons">
                 <a href="#" class="fas fa-heart"></a>
                 <a href="#" class="cart-btn">add to cart</a>
                 <a href="#" class="fas fa-share"></a>
             </div>
            </div>
            <div class="content">
             <h3>C Programming For Beginners - Master the C Language</h3>
             <div class="price">$11.99 <span>$19.99</span></div>
            </div>
         </div>

         <div class="box">
            <span class="discount"></span> 
            <div class="image">
             <img src="webdeveloper.jpg" alt="">
             <div class="icons">
                 <a href="#" class="fas fa-heart"></a>
                 <a href="#" class="cart-btn">add to cart</a>
                 <a href="#" class="fas fa-share"></a>
             </div>
            </div>
            <div class="content">
             <h3>The Web Developer Bootcamp 2023</h3>
             <div class="price">$21.99 <span>$46.99</span></div>
            </div>
         </div>

         <div class="box">
            <span class="discount"></span> 
            <div class="image">
             <img src="ethical-hacking.png" alt="">
             <div class="icons">
                 <a href="#" class="fas fa-heart"></a>
                 <a href="#" class="cart-btn">add to cart</a>
                 <a href="#" class="fas fa-share"></a>
             </div>
            </div>
            <div class="content">
             <h3>Learn Ethical Hacking From Scratch</h3>
             <div class="price">$15.99 <span>$32.99</span></div>
            </div>
         </div>



         <div class="box">
            <span class="discount"></span> 
            <div class="image">
             <img src="maxresdefault.jpg" alt="">
             <div class="icons">
                 <a href="#" class="fas fa-heart"></a>
                 <a href="#" class="cart-btn">add to cart</a>
                 <a href="#" class="fas fa-share"></a>
             </div>
            </div>
            <div class="content">
             <h3>Ultimate AWS Certified Developer Associate 2023 NEW DVA-C02
            </h3>
             <div class="price">$12.99 <span>$15.99</span></div>
            </div>
         </div>



         <div class="box">
            <span class="discount"></span> 
            <div class="image">
             <img src="ai.jpg" alt="">
             <div class="icons">
                 <a href="#" class="fas fa-heart"></a>
                 <a href="#" class="cart-btn">add to cart</a>
                 <a href="#" class="fas fa-share"></a>
             </div>
            </div>
            <div class="content">
             <h3>Artificial Intelligence A-Z 2023: Build 5 AI (incl. ChatGPT)</h3>
             <div class="price">$12.99 <span>$15.99</span></div>
            </div>
         </div>


         <div class="box">
            <span class="discount"></span> 
            <div class="image">
             <img src="web design.jpg" alt="">
             <div class="icons">
                 <a href="#" class="fas fa-heart"></a>
                 <a href="#" class="cart-btn">add to cart</a>
                 <a href="#" class="fas fa-share"></a>
             </div>
            </div>
            <div class="content">
             <h3>Web Design for Beginners: Real World Coding in HTML & CSS</h3>
             <div class="price">$0 <span>$15.99</span></div>
            </div>
         </div>
    </div>
</section>

  </body>
</html>

```
### Products.css
```
.products .box-container{
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem; ;
}


.products .box-container .box{
    flex: 1 1 30rem;
    box-shadow: 0.5rem 1.5rem rgba(0,0,0,.1);
    border-radius: .5rem;
    border: .1rem solid rgba(0,0,0,.1);
    position: relative;
}

.products .box-container .box .discount{
    position: absolute;
    top: 1rem; left: 1rem;
    padding:.7rem 1rem ;
    font-size: 2rem;
    color: var(--pink);
    background: rgba(255, 51, 153, .05);
    z-index: 1;
    border-radius: .5rem;
}


.products .box-container  .box  .image{
    position: relative;
    text-align: center;
    padding-top: 2rem;
    overflow:hidden ;



}



.products .box-container  .box  .image img{

height: 25rem;


}

.products .box-container  .box:hover  .image img{

    transform: scale(1.1);
    }


.products .box-container .box .image .icons{
    position: absolute;
    bottom: -7rem; left: 0; right: 0;
    display: flex;
}


.products .box-container .box .image .icons a{
     height: 5rem;
     line-height: 5rem;
     font-size: 2rem;
     width: 50%;
     background: var(--pink);
     color: #fff;


}

.products .box-container .box:hover .image .icons{
     bottom: 0;
}





.products .box-container .box .image .icons .cart-btn{

    border-left: .1rem solid #fff7;
    border-right: .1rem solid #fff7;
    width: 100%;

}

.products .box-container .box .image .icons a:hover{
    background: #333;

}


.products .box-container .box .content{
    padding: 2rem;
    text-align: center;

}


.products .box-container .box .content h3{
    font-size: 2.5rem;
    color: #333;
}


.products .box-container .box .content .price{
    font-size: 2.5rem;
    color: var(--pink);
    font-weight: bolder;
    padding-top: 1rem;
}

.products .box-container .box .content .price  span{
    font-size: 1.5rem;
    color: #999
    font-weight: lighter;
    text-decoration : line-through;
}
```
### Review.html
```
<!DOCTYPE html>
<html lang="en">
  <body>
<section class="review" id="review">

<h1 class="heading"> customer's <span>review</span>  </h1>

<div class="box-container">

<div class="box">

<div class="stars">

    <i class="fas fa-star"></i>
    <i class="fas fa-star"></i>
    <i class="fas fa-star"></i>
    <i class="fas fa-star"></i>
    


</div>
<p>CodeConnections fit us like a glove. Their team curates fresh, up-to-date courses from their marketplace and makes them available to customers. In total, it was a big success, I would get emails about what a fantastic resource it was. It’s truly the best solution for our employees and their careers.
    There are some incredible courses on Udemy, particularly some of the bootcamp courses in software and web development that have been better than my expensive university education.  The great thing is you can focus on learning the skills you actually enjoy doing.
</p>
<div class="user">
<img src="varun.jpeg"  alt="">

<div class="user-info">
    <h3>Varun Patil</h3>
    <span>Senior Manager HR </span>
</div>

</div>

<span class="fas fa-quote-right"></span>
</div>





<div class="box">

    <div class="stars">
    
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
    
    
    </div>
    <p>I have purchased a couple of the courses from CodeConnections during this last year and have had no issue’s at all. The course’s has been easily accessed and the content excellent.
        I can highly recommend this company to meet your needs.
        I honestly have no idea why there are so many negative comments.I have completed a few specific courses and I am very satisfied with the teachers and content.Easy to use, great courses.You get what you pay for.I am impressed and keep impressing.My main reason for enrolling is to further my own knowledge. CodeConnections!!
    
    </p>
    <div class="user">
    <img src="QWERTY.jpg"  alt="">
    
    <div class="user-info">
        <h3>Alfred Riche</h3>
        <span>Executive Manager</span>
    </div>
    
    </div>
    
    <span class="fas fa-quote-right"></span>
    </div>







    <div class="box">

        <div class="stars">
        
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
            <i class="fas fa-star"></i>
        
        
        </div>
        <p>"A WEB LEARNING BOOK"
            a sincere thanks to this learning site... from a free learning session to , with certificates . listening, reading and understanding will never be boring. i highly recommend these topics
            *energy protection and boundaries>
            *how to speak to anyone and be fearless>.I love the selection of classes and the instructors often update their courses. Some instructors are better than others, but that's to be expected.Don't understand why it has a low rating.Looking forward to taking more courses. CodeConnections rocks!!</p>
        <div class="user">
        <img src="download.jpeg"  alt="">
        
        <div class="user-info">
            <h3>Luz Romero</h3>
            <span>Developer</span>
        </div>
        
        </div>
        
        <span class="fas fa-quote-right"></span>
        </div>



        <div class="box">

            <div class="stars">
            
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
            
            
            </div>
            <p>I don`t understand why the website have so many bad reviews. I have used Udemy for the past few years and what I can say is that the company have very good courses for the price. This website is not to get a qualification but upgrading your skills. I bought courses at a great discount. I recommend every user to check first the rating of the teachers before buying the course and also to wait when the discount windows are open to get the courses at a very low price. Recommend the platform.Some Instructors Are Better Than Others, But That's Expected</p>
            <div class="user">
            <img src="nick.webp"  alt="">
            
            <div class="user-info">
                <h3>Christy Nick</h3>
                <span>happy customer</span>
            </div>
            
            </div>
            
            <span class="fas fa-quote-right"></span>
            </div>





            <div class="box">

                <div class="stars">
                
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
    
                
                
                </div>
                <p>Great platform and educators. The value of the courses are okay in my opinion. Way less than going back to in person school and convinient.

                    I had taken 3 different courses by 3 different teachers so far, and their curriculum are way better that what I expected. I even had questions after the class and the teacher was responsive and explained to me further about the topic I didn't understand. I get that it's not for everyone, you need to have a lot of discipline to be self-taught, and I think Udemy does a great job making it more accessible.
                    I Bought Courses At A Great Discount.
                    </p>
                <div class="user">
                <img src="SANDEEP.jpg"  alt="">
                
                <div class="user-info">
                    <h3>Sandeep </h3>
                    <span>Freelancer</span>
                </div>
                
                </div>
                
                <span class="fas fa-quote-right"></span>
                </div>









                <div class="box">

                    <div class="stars">
                    
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>

                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    
                    
                    </div>
                    <p>I have been a long-time learner with Udemy and it's served me well. Whenever I feel like I want to learn something new, I always check their site. Not only do they run frequent sales which make the courses more affordable, but they have a great variety. I also love the feedback from instructors. It's helpful to have some guidance if you need it. Currently learning belly dance and Pilates.</p>
                    <div class="user">
                    <img src="profile.png"  alt="">
                    
                    <div class="user-info">
                        <h3>Saravanan</h3>
                        <span>Student </span>
                    </div>
                    
                    </div>
                    
                    <span class="fas fa-quote-right"></span>
                    </div>


                    <div class="box">

                        <div class="stars">
                        
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>

                        
                        
                        </div>
                        <p>The fading star
                            Not only the quality of the courses dropped but also the instructors become very rude and disrespectful.
                            
                            Unfortunately, the legendary tutors there either left CodeConnections and joined other learning websites. I say it's time to leave Udemy wish I could refund all the new courses I got recently.
                            CodeConnections lost a customer forever. I am done with them. They are definitely running a scam there.
                            </p>
                        <div class="user">
                        <img src="profile.png"  alt="">
                        
                        <div class="user-info">
                            <h3>Shabaz ahmed</h3>
                            <span>Educator</span>
                        </div>
                        
                        </div>
                        
                        <span class="fas fa-quote-right"></span>
                        </div>







        <div class="box">

            <div class="stars">
            
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
            
            
            </div>
            <p>The courses overall are varied in quality and the user needs to do a bit of research before purchasing. I've had a good experience with 2 courses on CodeConnections itself.

                Make sure you the time to go through any demo content provided for the course.
                C'mon!! I'd give it more stars, but they only give you 5.Cheap courses, no monthly fees.Just everything in one nice little place. Plus you get certifiacates of completion</p>
            <div class="user">
            <img src="sandeep.jpeg"  alt="">
            
            <div class="user-info">
                <h3>john doe</h3>
                <span>happy customer</span>
            </div>
            
            </div>
            
            <span class="fas fa-quote-right"></span>
            </div>

</div>

</section>
</body>
</html>
```
### Review.css
```
.review .box-container{
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;

}

.review .box-container .box{
    flex: 1 1 30rem;
    box-shadow: 0 .5rem 1.5rem rgba(0,0,0,.1);
    border-radius: .5rem;
    padding: 3rem 2rem;
    position: relative;
    border: .1rem solid rgba(0,0,0,.1);

}

.review .box-container .box .fa-quote-right{
    position: absolute;
    bottom: 3rem; right: 3rem;
    font-size: 6rem;
    color: #eee;



}


.review .box-container .box .stars i{
       color: var(--pink);
       font-size: 2rem;
}


.review .box-container .box p{
    color: #999;
    font-size: 1.5rem;
    line-height: 1.5;
    padding-top: 2rem;
}






.review .box-container .box .user{
           display: flex;
           align-items: center;
           padding-top: 2rem;


}


.review .box-container .box .user img{
     height: 6rem;
     width: 6rem;
     border-radius: 50%;
     object-fit: cover;
     margin-right: 1rem;


}



.review .box-container .box .user h3{
    font-size: 2rem;
    color: #333;
}

.review .box-container .box .user span{
    font-size: 1.5rem;
    color: #333;
}
```
### Contact.html
```
  <!DOCTYPE html>
<html lang="en">
  <body>
<section class="contact" id="contact">

    <h1 class="heading"> <span> contact </span> us </h1>
    <div class="row">
        <form action="">
            <input type="text" class="box" placeholder="name">
            <input type="email" class="box" placeholder="email">
            <input type="number" class="box" placeholder="number">
            <textarea name="" class="box" placeholder="message"  cols="30"  rows="10" ></textarea>
            <input type="submit" value="send message" class="btn">
        </form> 

    <div class="image">
        <img style="width: 250px;height: 250px;"   src="pic 31.jpg" alt="">
        <h3>Saravanan</h3>
    </div>


    </div>
    
</section>



<section class="footer">

     <div class="box-container">

           <div class="box">

                 <h3>quick links</h3>
                 <a href="#">home</a>
                 <a href="#">about</a>
                 <a href="#">products</a>
                 <a href="#">review</a>
                 <a href="#">contact</a>
           </div>



           <div class="box">

            <h3>extra links</h3>
            <a href="#">my account</a>
            <a href="#">my order</a>
            <a href="#">my favorite</a>

      </div>

      <div class="box">

        <h3>locations</h3>
        <a href="#">india</a>
        <a href="#">USA</a>
        <a href="#">japan</a>
        <a href="#">france</a>
  </div>

  <div class="box">

    <h3>contact info</h3>
    <a href="#">+91-7694833736</a>
    <a href="#">CodeConnections/query/portal.org</a>
    <a href="#">mumbai , india -400001</a>
    
</div>


     </div>


<div class="credit"> created by <span> ms MUSFIRA MAHJABEEN </span> all rights reserved </div>




</section>


</body>
</html>

```
### Contact.css
```
.contact .row{
    display: flex;
    flex-wrap: wrap-reverse;
    gap: 1.5rem;
    align-items: center;

}

.contact .row form{
    flex: 1 1 40rem;
    padding: 2rem 2.5rem;
    box-shadow: 0 .5rem 1rem rgba(0,0,0,.1);
    border: 1rem solid rgba(0,0,0,.1);
    background: #fff;
    border-radius: .5rem;
}


.contact .row image{
    flex: 1 1 40rem;
}

.contact .row image img{
    width: 100%;
}

.contact .row form .box{
    padding: 1rem;
    font-size: 1.7rem;
    color: #333;
    text-transform: none;
    border: .1rem solid rgba(0,0,0,.1);
    border-radius: .5rem ;
    margin: .7rem 0;
    width: 100%;
}

.contact .row form .box:focus{
    border-color: var(--pink);
}

.contact .row form textarea{
    height: 15rem;
    resize: none;
}



.footer .box-container{
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
}


.footer .box-container .box{
    flex: 1 1 25rem;
}

.footer .box-container .box h3{
    color: #333;
    font-size: 2.5rem;
    padding:1rem 0;
}


.footer .box-container .box a{
    display: block;
    font-size: 1.5rem;
    color: #666;
    padding:1rem 0;
    text-align: center;
}

.footer .box-container .box a:hover{
    color: var(--pink);
    text-decoration: underline;

}


.footer .box-container .box  img{

    margin-top: 1rem;
    size-adjust: 50%;
    height: 145px;
    width: 130px;
}

.footer .credit{
    text-align: center;
    padding:1.5rem ;
    margin-top: 1.5rem;
    padding-top: 2.5rem;
    font-size: 2rem;
    color: #333;
    border-top: .1rem solid rgba(0,0,0,.1);
}


.footer .credit span{

    color: var(--pink);
    
}


h3{
    font-size: 3rem;
    text-align: center;
    font-family: Arial;
}



```
## OUTPUT:

### Home Page:
![Screenshot 2023-12-24 143126](https://github.com/musfiramahjabeen/productcompanywebsite/assets/138971008/d8fa0e6a-8c33-4734-9c02-3fbbb623651d)


### About Page:
![Screenshot 2023-12-24 143150](https://github.com/musfiramahjabeen/productcompanywebsite/assets/138971008/3355693c-56fe-405f-b018-07fe9d786e9a)




### Product Page:

![Screenshot 2023-12-24 143225](https://github.com/musfiramahjabeen/productcompanywebsite/assets/138971008/a9ce640b-1663-4980-8243-57e952d9d8f7)

![Screenshot 2023-12-24 143244](https://github.com/musfiramahjabeen/productcompanywebsite/assets/138971008/0339d5e4-36f8-4bc2-a477-902faf52cd4c)



### Review Page:
![Screenshot 2023-12-24 143304](https://github.com/musfiramahjabeen/productcompanywebsite/assets/138971008/9340fe57-c3fd-4fcd-ae24-0a3abafcfd73)

### Contact Page:
![Screenshot 2023-12-24 143324](https://github.com/musfiramahjabeen/productcompanywebsite/assets/138971008/a814204a-9709-42b7-a3c0-379e79c1526c)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
