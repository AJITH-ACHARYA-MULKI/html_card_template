# html_card_template
simple html card template where user can easily access information from the card.
<!DOCTYPE html>
<html>
<head>
  <title></title>
  <style type="text/css">
   html ,body{
    }
    .contents{
      border-radius: 13px;
      background:linear-gradient(-45deg,#651FFF 50%,#00FFFF 50%);

    }
    .child-tree{
      width: 70%;
    }
    .child{
      padding: 10px;
      overflow: auto;
    }

 .card {
  display: grid;
  width: 260px;
  float: left;
  grid-template-columns: 100%;
  grid-template-rows: 178px 151px 58px;
  grid-template-areas: "image" "text" "stats";
  border-radius: 18px;
  background: white;
  box-shadow: 5px 5px 15px rgba(0,0,0,0.9);
  font-family: roboto;
  text-align: center;
  margin-top:20px;
  transition: 0.5s ease;
  cursor: pointer;
  margin: 35px;
 

}
.card-image {
  grid-area: image;
  background: url(bg.jpg);
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
  background-size: cover;
}

.card-text {
  grid-area: text;
  margin: 25px;
}
.card-text p {
  color: grey;
  font-size:15px;
  font-weight: 300;
}
.card-text h2 {
  margin-top:0px;
  font-size:28px;
}
.card-stats {
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
  background: rgb(255, 7, 110);
}
.card-stats .border {
  border-left: 1px solid rgb(172, 26, 87);
  border-right: 1px solid rgb(172, 26, 87);
}
.card:hover {
  transform: scale(1.10);
  box-shadow: 5px 5px 15px rgba(0,0,0,0.6);
}




  </style>
</head>
<body>
  <div class="root">
    <center>
      <div class="contents">
      <div class="child">
        <div class="img1">
          <img src="bg.jpg" height="500px" width="87%" style="border-radius: 13px;">
        </div>
      </div>
      <div class="child-tree">
      <div class="child">
        
        <div class="card">
            <div class="card-image"></div>
            <div class="card-text">
            
            <p>Add some introduction or details of this card here.</p>
            </div>
            <div class="card-stats">
            <h2>JUMADI</h2>
            </div>
          </div>
        
            <div class="card">
            <div class="card-image"></div>
            <div class="card-text">
            <h2>Post Two</h2>
            <p>Add some introduction or details of this card here.</p>
            </div>
            <div class="card-stats">
            <h2>PANJURLI</h2>
            </div>
          </div>


          <div class="card">
            <div class="card-image"></div>
            <div class="card-text">
            <h2>Post Two</h2>
            <p>Add some introduction or details of this card here.</p>
            </div>
            <div class="card-stats">
            <h2>GULIGA</h2>
            </div>
          </div>
        
        <div class="card">
            <div class="card-image"></div>
            <div class="card-text">
            <h2>Post Two</h2>
            <p>Add some introduction or details of this card here.</p>
            </div>
            <div class="card-stats">
            <h2>JUMADI</h2>
            </div>
          </div>
        
            <div class="card">
            <div class="card-image"></div>
            <div class="card-text">
            <h2>Post Two</h2>
            <p>Add some introduction or details of this card here.</p>
            </div>
            <div class="card-stats">
            <h2>JUMADI</h2>
            </div>
          </div>


          <div class="card">
            <div class="card-image"></div>
            <div class="card-text">
            <h2>Post Two</h2>
            <p>Add some introduction or details of this card here.</p>
            </div>
            <div class="card-stats">
            <h2>JUMADI</h2>
            </div>
          </div>

        <div class="card">
            <div class="card-image"></div>
            <div class="card-text">
            <h2>Post Two</h2>
            <p>Add some introduction or details of this card here.</p>
            </div>
            <div class="card-stats">
            <h2>JUMADI</h2>
            </div>
          </div>
        
            <div class="card">
            <div class="card-image"></div>
            <div class="card-text">
            <h2>Post Two</h2>
            <p>Add some introduction or details of this card here.</p>
            </div>
            <div class="card-stats">
            <h2>JUMADI</h2>
            </div>
          </div>


          <div class="card">
            <div class="card-image"></div>
            <div class="card-text">
            <h2>Post Two</h2>
            <p>Add some introduction or details of this card here.</p>
            </div>
            <div class="card-stats">
            <h2>JUMADI</h2>
            </div>
          </div>

      </div>
    </div>

    </div>  
    </center>
  </div>

  <a href="adminhome.php"><img src="#"></a>
</body>
</html>
