<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Boutique en Ligne</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Ma Boutique en Ligne</h1>
        <div class="products">
            <div class="product">
                <img src="product1.jpg" alt="Product 1">
                <h2>Produit 1</h2>
                <p>Description du Produit 1</p>
                <p>Prix: $19.99</p>
                <button class="add-to-cart" data-name="Produit 1" data-price="19.99">Ajouter au Panier</button>
            </div>
            <div class="product">
                <img src="product2.jpg" alt="Product 2">
                <h2>Produit 2</h2>
                <p>Description du Produit 2</p>
                <p>Prix: $24.99</p>
                <button class="add-to-cart" data-name="Produit 2" data-price="24.99">Ajouter au Panier</button>
            </div>
        </div>
        <div class="cart">
            <h2>Panier</h2>
            <ul class="cart-items"></ul>
            <p class="total">Total: $<span>0.00</span></p>
            <button class="checkout">Passer la Commande</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
