<template>
                <div class="cart-list-item">
                    <img src="img/DragonLiver.png" alt="Dragon Liver" class="product-image">
                    <div class="item-details-with-actions">
                        <div class="item-details">
                            <h2>Dragon Liver</h2>
                            <p class="price">$1500</p>
                            <p class="in-stock-status"> <i class="fa-solid fa-check"></i> In stock</p>
                        </div>
                        <div class="item-actions">
                            <div class="quantity-selector">
                                <button class="quantity-change-button">−</button>
                                <input type="text" class="quantity-input" value="3" aria-label="quantity">
                                <button class="quantity-change-button">+</button>
                            </div>
                            <button class="remove-item">✕</button>
                        </div>
                    </div>
                </div>
                <div class="cart-list-item">
                    <img src="img/GoldenSnitch.png" alt="Golden Snitch" class="product-image">
                    <div class="item-details-with-actions">
                        <div class="item-details">
                            <h2>Golden Snitch</h2>
                            <p class="price">$600</p>
                            <p class="in-stock-status"> <i class="fa-solid fa-check"></i> In stock</p>
                        </div>
                        <div class="item-actions">
                            <div class="quantity-selector">
                                <button class="quantity-change-button">−</button>
                                <input type="text" class="quantity-input" value="2" aria-label="quantity">
                                <button class="quantity-change-button">+</button>
                            </div>
                            <button class="remove-item">✕</button>
                        </div>
                    </div>
                </div>
                <div class="cart-list-item">
                    <img src="img/UnicornTailHair.png" alt="Unicorn Tail Hair" class="product-image">
                    <div class="item-details-with-actions">
                        <div class="item-details">
                            <h2>Unicorn Tail Hair</h2>
                            <p class="price">$1200</p>
                            <p class="on-backorder-status"> <i class="fa-solid fa-hourglass-half"></i> On backorder</p>
                        </div>
                        <div class="item-actions">
                            <div class="quantity-selector">
                                <button class="quantity-change-button">−</button>
                                <input type="text" class="quantity-input" value="1" aria-label="quantity">
                                <button class="quantity-change-button">+</button>
                            </div>
                            <button class="remove-item">✕</button>
                        </div>
                    </div>
                </div>
                <div class="cart-list-item">
                    <img src="img/Wand.jpg" alt="Wand" class="product-image">
                    <div class="item-details-with-actions">
                        <div class="item-details">
                            <h2>Wand</h2>
                            <p class="price">$2000</p>
                            <p class="in-stock-status"> <i class="fa-solid fa-check"></i> In stock</p>
                        </div>
                        <div class="item-actions">
                            <div class="quantity-selector">
                                <button class="quantity-change-button">−</button>
                                <input type="text" class="quantity-input" value="1" aria-label="quantity">
                                <button class="quantity-change-button">+</button>
                            </div>
                            <button class="remove-item">✕</button>
                        </div>
                    </div>
                </div>
                <div class="cart-list-item">
                    <img src="img/Nimbus2000.jpg" alt="Nimbus 2000" class="product-image">
                    <div class="item-details-with-actions">
                        <div class="item-details">
                            <h2>Nimbus 2000</h2>
                            <p class="price">$5000</p>
                            <p class="in-stock-status"> <i class="fa-solid fa-check"></i> In stock</p>
                        </div>
                        <div class="item-actions">
                            <div class="quantity-selector">
                                <button class="quantity-change-button">−</button>
                                <input type="text" class="quantity-input" value="1" aria-label="quantity">
                                <button class="quantity-change-button">+</button>
                            </div>
                            <button class="remove-item">✕</button>
                        </div>
                    </div>
                </div>
</template>

<script setup>
</script>

<style scoped>
/* Styles for the cart list item */
.cart-list-item {
  display: flex;
  align-items: center;
  background-color: #fff;
  margin-bottom: 10px;
  border-radius: 8px;
  padding: 10px;
}

.product-image {
  width: 100px;
  margin-right: 10px;
}

.item-details-with-actions {
  display: flex;
  flex-grow: 1;
  margin-left: 10px;
}

.item-details {
  flex-grow: 1;
}

.item-actions {
  display: flex;
  align-items: center;
}

.price {
  font-size: 0.9em;
  color: #666;
}

.in-stock-status {
  font-size: 0.9em;
  color: green;
}

.on-backorder-status {
  font-size: 0.9em;
  color: red;
}

.quantity-selector {
  display: flex;
  border: 1px solid #c1c1c1;
  border-radius: 8px;
  overflow: hidden;
  /* Ensures the children do not break the rounded corners */
}

.quantity-change-button {
  background-color: #ffffff;
  border: none;
  padding: 10px 12px;
  cursor: pointer;
  font-size: 1rem;
  transition: all 0.2s;
}

.quantity-input {
  border: none;
  text-align: center;
  width: 40px;
  padding: 10px;
  font-size: 1rem;
  transition: all 0.2s;
}

.quantity-input:focus {
  outline: none;
}

.remove-item {
  background: none;
  border: none;
  border-radius: 50%;
  cursor: pointer;
  font-size: 1.2em;
  margin-left: 20px;
}

.quantity-change-button:hover,
.quantity-change-button:focus,
.quantity-input:focus,
.remove-item:hover,
.remove-item:focus {
  background-color: #f2f2f2;
}
</style>
