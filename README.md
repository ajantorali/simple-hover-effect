# simple-hover-effect
can use only for practice (HTML/CSS)



HTML Code: 
 <div class="box">
        <div class="card">
            <img src="img/form in lap.png" alt="">
            <div class="content">
               <h1>Jibannagar IT Park</h1>
                <p>Lorem ipsum dolor sit amet.</p>
            </div>
        </div>
 </div>





CSS Code:
.card{
    overflow: hidden;
    margin: 50px auto;
    width: 300px;
    box-sizing: border-box;
    position: relative;
    background-color:  greenyellow;
    border: 2px solid black;
}
img{
    width: 100%;
}

.content{
    transition: 0.5s;
    width: 100%;
    height: 100%;
    top: 0%;
    left: -300px;
    background: rgba(0, 0, 0, .8);
    position: absolute;
    background-color: indianred;
    text-align: center;
}
.card:hover .content{
    left: 0;
}

