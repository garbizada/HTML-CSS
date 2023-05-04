# Frontend Mentor - QR code component solution
parte em HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="stylesheet" href="style.css">
  
  <title>Frontend Mentor | QR code component</title>
 
</head>
<body>
    <div class="container">
        <div class="card"> 
            <img src="images/image-qr-code.png" alt="QR code">
            <div class="text">
                <h2> Improve your front-end skills by building projects</h2>
                <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level

                </p>

            </div>
        </div>
    </div>



</body>
</html>


parte de css


@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Outfit:wght@400;700&display=swap');

*{
    margin: 0;
    padding: 0;
}

body{
    font-family:'Outfit', sans-serif ;
    background-color: hsl(212, 45%, 89%);
    min-height: 100vh;
    display: flex;
    align-items: center;
    font-size: 15px;
}

.container{
    max-width: 350px;
    margin: 0 auto;
}

.card{
    background-color: white;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    margin: 0rem 1rem;


}

.card > img{
    width: 100%;
    border-radius: 10px;

}

.text{
    padding: 22px 12px;
}

.text > h2{
    color: hsl(218, 44%, 22%);
    padding-bottom: 15px;
}

.text > p{
    color: hsl(220, 15%, 55%);
}