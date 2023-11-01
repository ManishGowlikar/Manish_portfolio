<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Manish portfolio </title>
    <link rel="icon" type="image/x-icon" href="/images/favicon.ico">

    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="./style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
      .navbar a {
          position: relative;
          display: inline-block;
          text-decoration: none;
          color: #000;
          padding: 10px 15px;
          margin: 0 5px;
      }

      .navbar a::after {
          content: '';
          position: absolute;
          left: 0;
          bottom: 0;
          height: 2px;
          width: 90%;
          background-color: #E91E63;
          transform: scaleX(0);
          transition: transform 0.3s;
          transform-origin: right;
      }

      .navbar a:hover::after {
          transform: scaleX(1);
          transform-origin: left;
      }
      
  </style>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

   
</head>
<body>
     <header class="header sticky">
        <a href="#" class="logo"> <i style="font-size:25px; font-weight: bolder; color:rgb(233, 30, 99);"> Manish.</i><span class="animate" style="--i:1;"></span></a>
<div class="bx bx-menu" id="menu-icon"><span class="animate" style="--i:2;"></span></div>
       <nav class="navbar" style="color: white; font-weight: bolder;">
        <a href="#home" class="active">Home</a>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#footers">Contact</a>

         <span class="active-nav"></span>
         <span class="animate" style="--i:2;"></span>
       </nav>

     </header>

     <section class="home show-animate" id="home">
        <div class="home-content">
        <h1>Hi, I am <span style="color: yellow;">Manish </span> From Hyderabad<span class="animate" style="--i:2;"></span></h1>
        <div class="text-animate">
        <h3 data-text='Frontend Developer'>Angluar Developer</h3>
        <span class="animate" style="--i:3;"></span>
        </div>
        <p>
         Self-motivated and hardworking fresher seeking for an opportunity to work in a challenging environment to prove my skills and utilize my knowledge & intelligence in the growth of the organization.
         <span class="animate" style="--i:4;"></span> </p>
        <div class="btn-box">
        <a href="./manish resume.pdf" download="Gowlikar Manish Resume" class="btn">Resume  <i class='bx bxs-download'></i></a>
        <a href="tel:+918919662746" class="btn">Contact Me</a>
        <span class="animate" style="--i:5;"></span>
        </div>
        </div>
       <div class="home-sci">
         <a href="#"><i class="bx bxl-facebook"></i></a>
         <a href="#"> <i class="bx bxl-twitter"></i></a>
         <a href="#"><i  class="bx bxl-linkedin" ></i></a>
         <span class="animate" style="--i:6;"></span>
        
       </div>
<div class="home-imgHover">

</div>
<span class="animate home-img" style="--i:7;"></span>

        </section>

        <section class="about" id="about">
          <h2 class="heading" >About <span style="color:#E91E63;">Me</span><span class="animate scroll" style="--i:1;"></span></h2>
           
                <div class="about-img ">
                  
                  <img src="./MANISH PHOTO  (2).jpg" alt="" width="30px" height="215px">
                  <span class="circle-spin"></span>
                  <span class="animate scroll" style="--i:2;"></span>
                </div>
                
                <div class="about-content">
                  <h3 id="element" style="color: #E91E63; --i:3;"><span class="animate scroll" style="--i:3;"></span></h3>
                  <p> 
                    Expert in developing interactive websites using Angular , Java Script , CSS  ,bootstrap and, Html

                    </p>
                    <div class="btn-box btns">
                        <a href="#" class="btn">Read More</a>
                        <span class="animate scroll" style="--i:5;"></span>
                    </div>




                </div>

        </section>



            <section class="education" id="education">
              <h2 class="heading">
                My <span>Journey</span><span class="animate scroll" style="--i:1;"></span> </h2>

                <div class="education-row">
                  <div class="education-column">
                    <h3 class="title">Education<span class="animate scroll" style="--i:2;"></span></h3>

                          <div class="education-box">
                            <div class="education-content">
                              <div class="content">
                                <div class="year"><i class="bx bxs-calendar"></i>2016-2017</div>
                              <h3>JUNIOR SECONDARY (10th)</h3>
                              
                              <ul style="padding:10px;">
                                <li>School Name:SVR Educational Academy</li>
                                <li>Passing Year: 2017</li>
                                <li>Marks obtained:70%</li>
                                <li>Hyderabad,Telangana.</li>
                            </ul>

                              <span class="animate scroll" style="--i:3;"></span>
                              </div>
                            </div>





                            <div class="education-content">
                              <div class="content">
                                <div class="year"><i class="bx bxs-calendar"></i>2018-2019</div>
                              <h3>SENIOR SECONDARY (11th,12th)</h3>
                               
                              
                              <ul style="padding:10px;">
                                <li>College Name:NRI Junior College

                                </li>
                                <li>Passing Year: 2019</li>
                                <li>Marks obtained:70%</li>
                                <li>Srnagar,Hyderabad.</li>
                            </ul>

                              </div>
                            </div>



                            
                            <div class="education-content">
                              <div class="content">
                                <div class="year"><i class="bx bxs-calendar"></i>2020-2022</div>
                              <h3>Degree (1th,2th,3th)</h3>

                              <ul style="padding:10px;">
                                <li>College Name:Rukmini College of commerce
                                </li>
                                <li>Passing Year: 2022</li>
                                <li>Marks obtained:80%</li>
                                <li>Ameerpet,Telangana.</li>

                            </ul>

                              
                              </div>
                            </div>




                            <span class="animate scroll" style="--i:3;"></span>

                            
                          </div>

 

                  </div>


                  <!-- -------------------------------------------------------------------colunend------------------------------- -->

                  <div class="education-column">
                    <h3 class="title">Projects<span class="animate scroll" style="--i:2;"></span></h3>

                          <div class="education-box">
                            <div class="education-content">
                              <div class="content">
                                <div class="year"><i class='bx bxl-product-hunt'></i>ONLINE SHOPPING WEBSITE
                                </div>
                               
                              <p style="font-size: 12px; margin-bottom: 9px;"> I have created a online shopping website using JSON data by Fetch API method from HTML , CSS , Java Script ,Bootstrap & Angular.I have used fake store API data and have done
                                the presentation of products along with there pictures prices of the products and their relevant
                                description.

                              </p>
                              <div style="display: flex; justify-content: space-evenly; padding: 5px;"> 
                            <h2 style="margin-top: 5px;">Click here to view the Project</h2>      <i class='bx bxs-hand-right' style="margin-top: 5px; font-size: 35px;"></i>
                            <div class="btn-box btns">
                              <a href="./formelement.html" class="btn">Project 1</a>
                              <span class="animate scroll" style="--i:5;"></span>
                          </div>
                        </div>
                              <span class="animate scroll" style="--i:3;"></span>
                              </div>
                            </div>





                            <div class="education-content">
                              <div class="content">
                                <div class="year"><i class='bx bxl-product-hunt'></i>LOAN EMI CALCULATOR
                                </div>
                               
                              <p style="font-size: 12px; margin-bottom: 9px;"> Personal Loan EMI Calculator: I have created Personal Loan EMI Calculator using
                                HTML CSS Java Script Bootstrap in this project user have to give the details like Amount, number of
                                years and Interest Rate then click on calculate button it will calculate the amount and show the result

                              </p>
                              <div style="display: flex; justify-content: space-evenly; padding: 5px;"> 
                            <h2 style="margin-top: 5px;">Click here to view the Project</h2>    <i class='bx bxs-hand-right' style="margin-top: 5px; font-size: 35px;"></i>
                            <div class="btn-box btns">
                              <a href="./Emi calculator.html" class="btn">Project 2</a>
                              <span class="animate scroll" style="--i:5;"></span>
                          </div>
                        </div>
                              <span class="animate scroll" style="--i:3;"></span>
                              </div>
                            </div>


                            
 

                  </div>

                            <span class="animate scroll" style="--i:6;"></span>
                </div>
              </h2>
            </section>


            <section class="skills" id="skills">
              <h2 class="heading"> My <span>Skills </span><span class="animate scroll" style="--i:1;"></span>  </h2>
                  <div class="skills-row">
                    <div class="skills-column" >
                      <h3 class="title">
                        Coding Skills </span><span class="animate scroll" style="--i:2;"></span></h3>
                   <div class="skills-box">
                    <div class="skills-content">
                      <div class="progress">
                        <h3>HTML <span>90%</span></h3>
                        <div class="bar"><span></span> </div>
                      </div>
                      <div class="progress">
                        <h3>CSS <span>80%</span></h3>
                        <div class="bar"><span></span> </div>
                      </div>
                      <div class="progress">
                        <h3>JavaScript <span>65%</span></h3>
                        <div class="bar"><span></span> </div>
                      </div>
                      <div class="progress">
                        <h3>Angluar <span>75%</span></h3>
                        <div class="bar"><span></span> </div>
                      </div>

                    </div>
                  </span><span class="animate scroll" style="--i:3;"></span>

                   </div>



                    </div>
<!-- 
                    <div class="skills-column">
                      <h3 class="title">
                        Professional Skills</span><span class="animate scroll" style="--i:5;"></span>
                      </h3>
                   <div class="skills-box">
                    <div class="skills-content">
                      <div class="progress">
                        <h3>bootstrap  <span>95%</span></h3>
                        <div class="bar"><span></span> </div>
                      </div>
                      <div class="progress">
                        <h3>web Development <span>67%</span></h3>
                        <div class="bar"><span></span> </div>
                      </div>
                      <div class="progress">
                        <h3>JavaScript <span>65%</span></h3>
                        <div class="bar"><span></span> </div>
                      </div>
                      <div class="progress">
                        <h3>Angluar <span>75%</span></h3>
                        <div class="bar"><span></span> </div>
                      </div>


                    </div> -->
                    
                  <span class="animate scroll" style="--i:6;"></span>
                   </div>

 
                    </div>






                  </div>




            </section>

            <!-- -------------------------------------------------------------------- -->

            <section >
              <h2 style="display: flex; justify-content: center; align-items: center; font-size: 60px;">Contact Me</h2>
            
            <div style="padding: 25px;">  
              <i class='bx bxs-phone-call'  style="font-size: 45px;"></i><button style="background-color: #E91E63; padding: 10px; border-radius: 5px ; width: 200px;" ><a href="tel:+918919662746" style="text-decoration: none; color: aliceblue; font-weight: bolder;">Contact Me</a></button>
            </div>
            <div style="padding: 25px;">  
              <i class='bx bxs-envelope' style="font-size: 45px;"></i><button style="background-color: #E91E63; padding: 10px; border-radius: 5px ;width: 200px;" ><a href="mailto:2023g.manish@gmail.com" style="text-decoration: none; color: aliceblue; font-weight: bolder;">Email</a></button>
            </div>
  
            <h2 style="display: flex; justify-content: center; align-items: center; font-size: 60px;">Training certificate</h2>

           <div style="padding: 15px; "> <h3>Web Developer </h3></div>

           <button style="background-color: #E91E63; padding: 10px; border-radius: 5px ; width: 200px;" ><a href="../manish ui.pdf" download="Manish ui certificate" style="text-decoration: none; color: aliceblue; font-weight: bolder;">View certificate</a></button>

           <div style="padding: 15px;"> <h3> Angular</h3>  </div>
           <button style="background-color: #E91E63; padding: 10px; border-radius: 5px ; width: 200px;" ><a href="./anuglar manish.pdf" download="Manish Angular certificate" style="text-decoration: none; color: aliceblue; font-weight: bolder;">View certificate</a></button>
            </section>
            
            <footer class="footer" id="footers">
              <div style="font-size: 15px;">
                <p>Copyright &copy; 2023 by Manish | All Rights Reserved</p>
                <span class="animate scroll" style="--i:1;"></span> 
              </div>

             <div class="footer-iconTop">
              <a href="#"><i class="bx bx-up-arrow-alt"></i></a>
              <span class="animate scroll" style="--i:3;"></span> 
             </div>



            </footer>


       <script src="./script.js"></script>
       
</body>
</html> 
