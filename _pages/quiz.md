---
layout: page
permalink: /quiz/
title: Quiz
description: (Under construction!!) 
nav: true
nav_order: 6
---

<p>
These are indisputable things in the world that people often don't realize. (Jk. More like things that charecterize me 🤔) Ordered in life-significance (to me). If you are 100% with me, shoot me an email we should grab a coffee at some point. 
</p>

<hr/>
<div class="row">
    <div class="col-sm-4">
        <img class="img-responsive" src="https://cdn.cnn.com/cnnnext/dam/assets/180426115546-cola-wars-coke-pepsi.jpg" width="85%"/>
    </div>

    <div class="col-sm-8">
        <p>
        Question 1: Pepsi or Coke?
        </p>
        <button onclick="photo1()">Pepsi</button>
        <div id="answer1" style="display:none;">
            Pepsi, something tastes like toilet cleaner.
        </div>
        <button onclick="photo2()">Coke</button>
        <div id="answer2" style="display:none;">
            Yes, coke please.
        </div>
        <script>
            function photo1() {
              var x = document.getElementById("answer1");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
        <script>
            function photo2() {
              var x = document.getElementById("answer2");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
    </div>
</div>
<hr/>
<div class="row">
    <div class="col-sm-4">
        <img class="img-responsive" src="https://diffzi.com/wp-content/uploads/2018/11/Lays-vs.-Pringles.jpg" width="85%"/>
    </div>

    <div class="col-sm-8">
        <p>
        Question 2: Lays or Pringles?
        </p>
        <button onclick="Lays()">Lays</button>
        <div id="Lays" style="display:none;">
            When you buy Lays, you are just paying for the air inside.
        </div>
        <button onclick="Pringles()">Pringles</button>
        <div id="Pringles" style="display:none;">
            MasterPIECE.
        </div>
        <script>
            function Lays() {
              var x = document.getElementById("Lays");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
        <script>
            function Pringles() {
              var x = document.getElementById("Pringles");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
    </div>
</div>
<hr/>
<div class="row">
    <div class="col-sm-4">
        <img class="img-responsive" src="http://p9.itc.cn/q_70/images03/20200625/5877604ed4284b149ebddb76d8d84ac1.jpeg" width="85%"/>
    </div>

    <div class="col-sm-8">
        <p>
        Question 3: Zongzi with meat(肉粽) or Zongzi with sugar(甜粽)?
        </p>
        <button onclick="photo3()">Zongzi with meat(肉粽)</button>
        <div id="answer3" style="display:none;">
            Ok, not bad but also not great.
        </div>
        <button onclick="photo4()">Zongzi with sugar(甜粽)</button>
        <div id="answer4" style="display:none;">
            Yay! Zongzi, essentially, is a type of sweet desert :)
        </div>
        <script>
            function photo3() {
              var x = document.getElementById("answer3");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
        <script>
            function photo4() {
              var x = document.getElementById("answer4");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
    </div>
</div>
<hr/>
<div class="row">
    <div class="col-sm-4">
        <img class="img-responsive" src="https://cdn.britannica.com/86/166986-050-4CEFE5DE/cute-kitten-and-puppy-outdoors-in-grass.jpg" width="85%"/>
    </div>

    <div class="col-sm-8">
        <p>
        Question 4: Dog or cat?
        </p>
        <button onclick="Dog()">Dog</button>
        <div id="Dog" style="display:none;">
            Yes. Labrador. The best.
        </div>
        <button onclick="Cat()">Cat</button>
        <div id="Cat" style="display:none;">
            🐱
        </div>
        <script>
            function Dog() {
              var x = document.getElementById("Dog");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
        <script>
            function Cat() {
              var x = document.getElementById("Cat");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
    </div>
</div>
<hr/>
<div class="row">
    <div class="col-sm-4">
        <img class="img-responsive" src="https://media.licdn.com/dms/image/C4E12AQHUqdLSIYhFWQ/article-cover_image-shrink_600_2000/0/1520172015994?e=2147483647&v=beta&t=FtcUUgDliRSuBZGimArPTTcb1MVcHk5vLhQ-g4PSzH4" width="85%"/>
    </div>

    <div class="col-sm-8">
        <p>
        Question 5: Satisfied pig or dissatisfied Socrates?
        </p>
        <button onclick="photo5()">Satisfied pig</button>
        <div id="answer5" style="display:none;">
            An oink! An oink! 🐷
        </div>
        <button onclick="photo6()">Dissatisfied Socrates</button>
        <div id="answer6" style="display:none;">
            "Il n'ya qu'un héroïsme au monde：c'est de voir le monde tel qu'il est et de l'aimer."

            So yes, I'd rather be a dissatisfied Socrates.
        </div>
        <script>
            function photo5() {
              var x = document.getElementById("answer5");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
        <script>
            function photo6() {
              var x = document.getElementById("answer6");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
    </div>
</div>
<hr/>
<div class="row">
    <div class="col-sm-4">
        <img class="img-responsive" src="http://img.mp.itc.cn/upload/20170407/6ed9c11c35344c4387e4c67adac3b920_th.png" width="85%"/>
    </div>

    <div class="col-sm-8">
        <p>
        Question 6: Chongqing hotpot or Chengdu hotpot?
        </p>
        <button onclick="Hotpot()">Chengdu</button>
        <div id="Hotpot" style="display:none;">
            Click the other one I'll tell you.
        </div>
        <button onclick="Chongqing()">Chongqing</button>
        <div id="answer6" style="display:none;">
            There are many reasons that you should (always🤓) go with Chongqing hotpot. In short, check out this <a href="https://www.sohu.com/a/132630554_385445">article</a>.
        </div>
        <script>
            function Chengdu() {
              var x = document.getElementById("Chengdu");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
        <script>
            function Chongqing() {
              var x = document.getElementById("Chongqing");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
    </div>
</div>
<hr/>
<div class="row">
    <div class="col-sm-4">
        <img class="img-responsive" src="https://a4.espncdn.com/combiner/i?img=%2Fphoto%2F2022%2F1120%2Fr1093637_1296x729_16%2D9.jpg" width="85%"/>
    </div>

    <div class="col-sm-8">
        <p>
        Question 7: Who is the GOAT?
        </p>
        <button onclick="photo7()">Messi</button>
        <div id="answer7" style="display:none;">
            Messi is the only GOAT.
        </div>
        <button onclick="photo8()">Still Messi</button>
        <div id="answer8" style="display:none;">
            The one and the only. Period.
        </div>
        <script>
            function photo7() {
              var x = document.getElementById("answer7");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
        <script>
            function photo8() {
              var x = document.getElementById("answer8");
              if (x.style.display === "none") {
                x.style.display = "block";
              } else {
                x.style.display = "none";
              }
            }
        </script>
    </div>
</div>
<hr/>