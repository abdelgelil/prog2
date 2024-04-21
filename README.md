# prog2
The project is a simple E-Commerce system that models different types of products and
their interactions with customers. The project consists of the following classes:

1. Product: This is the superclass that represents a generic product.
Attributes:
 productId: positive integer 
 name: String
 price: positive float 
Methods: Setters and getters for the attributes.

2. ElectronicProduct: This is a subclass of Product that represents electronic products.
Attributes:
 brand: String
 warrantyPeriod: positive integer 
Methods: Setters and getters for the attributes.

3. BookProduct: This is a subclass of Product that represents book products
Attributes:
 author: String
 publisher: String
Methods: Setters and getters for the attributes.

4. ClothingProduct: This is a subclass of Product that represents clothing products.
Attributes:
 size: String
 fabric: String
Methods: Setters and getters for the attributes.4. BookProduct: This is a subclass of Product that represents book products.

5. BookProduct: This is a subclass of Product that represents book products
Attributes:
 author: String
 publisher: String
Methods: Setters and getters for the attributes.

6. Customer: This class represents a customer.
Attributes:
 customerId: positive integer 
 name: String
 address: String
Methods: Setters and getters for the attributes.

7. Cart: This class represents a shopping cart.
Attributes:
 customerId: positive integer 
 nProducts: positive integer which represents the number of products 
 products: an array of Product objects of size nProducts.
Methods: Setters and getters for the attributes, addProduct, removeProduct, calculatePrice and
placeOrder.

8. Order: This class represents an order placed by a customer.
Attributes:
 customerId: positive integer
 orderId: positive integer 
 products: an array of Product objects of size nProducts.
 totalPrice: positive float 
Methods: printOrderInfo.

9. EcommerceSystem: This class serves as the entry point for the project. It contains the main method
and demonstrates the usage of the other classes that creates products and takes order from the user
