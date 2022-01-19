<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>payment page</title>
       <link rel="stylesheet" href="../style/style.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Dongle:wght@300;400&family=Merriweather:ital,wght@0,300;0,700;0,900;1,700&family=Poppins:wght@100;200&display=swap" rel="stylesheet">
    </head>

    <body>
        <div class="container">
            <h1>Confirm Your payment</h1>
        <!--   <h2>You should to pay $1000 </h2>      --> 
            <div class="first-row">
                <div class="owner">
                    <h3>Owner</h3>
                    <div class="input-field">
                        <input type="text">
                    </div>                  
                </div>           
                <div class="cvv">
                    <h3>cvv</h3>
                    <div class="input-field">
                       <input type="password">
                    </div>
                </div>
            </div>

            <div class="second-row">
                <div class="card-number">
                    <h3>card-number</h3>
                    <div class="input-field">
                        <input type="text">
                    </div>                  
                </div>
            </div>

            <div class="third-row">
                    <h3>card-number</h3>
                    <div class="selection">
                        <div class="date">
                            <select name="months" id="months">
                                <option value="Jan">Jan</option>
                                <option value="Feb">Feb</option>
                                <option value="Mar">Mar</option>
                                <option value="Apr">Apr</option>
                                <option value="May">May</option>
                                <option value="Jun">Jun</option>
                                <option value="Jul">Jul</option>
                                <option value="Aug">Aug</option>
                                <option value="Sep">Sep</option>
                                <option value="Oct">Oct</option>
                                <option value="Nov">Nov</option>
                                <option value="Dec">Dec</option>                           
                            </select>
                            <select name="years" id="years">
                                <option value="2021">2021</option>
                                <option value="2020">2020</option>
                                <option value="2019">2019</option>
                                <option value="2018">2018</option>
                                <option value="2017">2017</option>
                            </select>                          
                        </div>

                        <div class="cards">
                            <img src="../img/paypal.png" alt="">
                            <img src="../img/mastercard.png" alt="">
                            
                        </div>
                    </div>
            </div>
            <a href="">Confirm</a>
        </div>
    </body>
</html>
