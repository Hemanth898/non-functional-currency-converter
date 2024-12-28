# non-functional-currency-converter

HTML code


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currency Converter</title>
    <link rel="stylesheet"  href="style.css"></link>
</head>
<body>
    <div class="container">
        <h2>Currency Converter</h2>
        <form>
            <div class="amount">
                <p>Enter amount</p>
                <input type="text" id="amount" placeholder="Enter amount"/>
            </div>
            
            <div class="dropdown">
                <div>
                    <p>From</p>
                    <div class="select-container">
                        <img src="https://flagsapi.com/IN/shiny/64.png">
                        <select id="from">
                            <option value="INR">INR</option>
                            <option value="EUR">EUR</option>
                            <option  value="USD">USD</option>
                            <option value="JPY">JPY</option>
                            <option value="GBP">GBP</option>
                            <option value="AUD">AUD</option>
                            <option value="CAD">CAD</option>
                            <option value="CHF">CHF</option>
                            <option value="CNY">CNY</option>
                            <option value="SEK">SEK</option>
                        
        
                        </select>
                    </div>
                </div>


                

         
              
            <div class="to">
                <div>
                    <p>To</p>
                    <div class="select-container">
                        <img src="https://flagsapi.com/US/shiny/64.png">
                        <select id="from">
                            <option value="INR">INR</option>
                            <option value="EUR">EUR</option>
                            <option selected value="USD">USD</option>
                            <option value="JPY">JPY</option>
                            <option value="GBP">GBP</option>
                            <option value="AUD">AUD</option>
                            <option value="CAD">CAD</option>
                            <option value="CHF">CHF</option>
                            <option value="CNY">CNY</option>
                            <option value="SEK">SEK</option>
                        
        
                        </select>
                    </div>
                </div>
            
            </div>
            
            </div>
            
         
            <div class="msg">1USD = 80INR</div>
            <button>Get Exchange Rate</button>
        
        </form>

    </div>
</body>
</html>



CSS CODE

*{
    margin: 0;
    padding: 0;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: bisque;
}
.container{
    background-color: whitesmoke;
    padding: 2rem;
    border-radius: 3rem;
    height: 50vh;
    width: 45vh;
}

form{
    margin: 2rem 0 2rem 0;
}

form select,button,input{
    width: 100%;
    border: none;

}

form input{
    border: 1px solid blue;
    font-size: 2dvi;
    height: 2rem;
    border-radius: 2rem;
    padding-left: 0.7rem;
}
.dropdown {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 2rem;
}
.select-container img {
        width: 1rem;
}
.select-container{
    display: flex;
    width: 6rem;
    background-color: none;
    border-radius: 1rem;
    background-color:none;
}

.select-container select{
    font-size: 1.5rem;
    width: auto;
    border-radius: 3rem;
    border-color:8px solid black;
}

.msg{
    margin:2rem 0 2rem 0;
}

form button{
    height: 4rem;
    background-color: aquamarine;
    color: blue;
    border-radius: 2rem;
    font-size: 1.25rem;
    cursor: pointer;
}
 
