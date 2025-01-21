<!DOCTYPE html> 
<html lang="ar" dir="rtl"> 
 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>متجر Tiger</title> 
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet"> 
    <!-- إضافة المكون components=buttons لتفعيل زر الدفع --> 
    <script src="https://www.paypal.com/sdk/js?client-id=AYT_BnD9gpFhWIS2OZ2kiu1zqzRrTntb7o-tDt4J3me7nvKE85X1aBq_sOi7RPungeet4H-wSk84LsGB_ID&currency=USD&components=buttons"></script> 
 
    <style> 
        /* CSS Reset */ 
         
        * { 
            margin: 0; 
            padding: 0; 
            box-sizing: border-box; 
        } 
         
        body { 
            font-family: 'Arial', sans-serif; 
            background-color: #121212; 
            color: #fff; 
        } 
         
        header { 
            background-color: #1e1e1e; 
            padding: 10px 20px; 
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
        } 
         
        header .logo { 
            font-size: 24px; 
            font-weight: bold; 
            color: #9d00ff; 
        } 
         
        header nav a { 
            color: #fff; 
            margin: 0 10px; 
            text-decoration: none; 
            font-size: 18px; 
        } 
         
        header nav a:hover { 
            color: #9d00ff; 
        } 
         
        .container { 
            padding: 20px; 
        } 
         
        .product { 
            background-color: #1e1e1e; 
            border-radius: 8px; 
            padding: 15px; 
            margin: 10px; 
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            text-align: center; 
        } 
         
        .product img { 
            width: 100px; 
            height: 100px; 
            object-fit: cover; 
        } 
         
        .product h3 { 
            margin: 10px 0; 
            color: #9d00ff; 
        } 
         
        .product p { 
            margin: 5px 0; 
        } 
         
        .product .buy-now { 
            background-color: #9d00ff; 
            border: none; 
            color: #fff; 
            padding: 10px 20px; 
            border-radius: 5px; 
            cursor: pointer; 
            margin-top: 10px; 
        } 
         
        .product .buy-now:hover { 
            background-color: #7700cc; 
        } 
         
        .paypal-button-container { 
            display: none; 
            margin-top: 10px; 
        } 
         
        .grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); 
            gap: 20px; 
        } 
         
        h1 { 
            text-decoration-line: overline; 
            text-decoration-color: blueviolet; 
        } 
         
        footer { 
            background-color: #1e1e1e; 
            padding: 10px; 
            text-align: center; 
            margin-top: 20px; 
        } 
         
        footer p { 
            font-size: 14px; 
        } 
    </style> 
</head> 
 
<body> 
    <header> 
        <div class="logo">Tiger Store</div> 
        <nav> 
            <a href="#home">الرئيسية</a> 
            <a href="#products">المنتجات</a> 
            <a href="#categories">التصنيفات</a> 
            <a href="#contact">التواصل</a> 
        </nav> 
    </header> 
 
    <div id="home" class="container"> 
        <h1>مرحبًا بكم في متجر Tiger</h1> 
 
        <br> 
        <p style="font-size: 20px; font-weight: bold; color: #9d00ff; "> 
            هنا نبيع الليرتات وجميع أنواع الإفكتات بأفضل جودة ممكنة وأفضل سعر 
        </p> 
    </div> 

 
    <div id="products " class="container "> 
        <h1 style="color:#ffffffff ">المنتجات</h1> 
        <br> 
        <p style="font-size: 20px; font-weight: bold; color: #9d00ff; "> 
            اولا الافكتات 
        </p> 
        <div class="grid "> 
            <!-- المنتجات هنا --> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 1</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button>
<div class="paypal-button-container" id="paypal-button-1"></div>

            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 2</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 3</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 4</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 5</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 6</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 7</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 8</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 9</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 10</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 11</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 12</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 13</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 14</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 15</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 16</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 17</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 18</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 19</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 20</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 21</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 22</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 23</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 24</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 25</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 26</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 27</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 28</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 29</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 30</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 31</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 32</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 33</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 34</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 
            <div class="product">
                <img src="Tiger (1).png" alt="منتج"> 
                <h3>Effect 35</h3> 
                <p>السعر: 12$</p> 
                <button class="buy-now" data-price="12.00" data-id="paypal-button-1">شراء الآن</button> 
                <div class="paypal-button-container" id="paypal-button-1"></div> 
            </div> 

            <!-- أضف بقية المنتجات بنفس الشكل --> 
        </div> 
    </div> 
 
    <div id="categories " class="container "> 
        <h1 style="color:#ffffffff ">الليرتات</h1> 
        <br> 
        <p style="font-size: 20px; font-weight: bold; color: #9d00ff; "> 
            التصنيفات
        </p> 


    <footer> 
        <p>© Tiger Store 2025</p> 
    </footer> 
 
    <script> 
        document.querySelectorAll('.buy-now').forEach(button => {
    button.addEventListener('click', function() {
        const price = this.getAttribute('data-price');
        const containerId = this.getAttribute('data-id');
        document.getElementById(containerId).style.display = 'block';

        paypal.Buttons({
            createOrder: (data, actions) => {
                return actions.order.create({
                    purchase_units: [{
                        amount: { value: price }
                    }]
                });
            },
            onApprove: (data, actions) => {
                return actions.order.capture().then(details => {
                    alert('تم الشراء بنجاح بواسطة ' + details.payer.name.given_name);
                });
            }
        }).render(`#${containerId}`);
    });
});

    </script> 
</body> 
 
</html>
