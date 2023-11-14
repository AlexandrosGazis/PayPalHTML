# "PayPal client ID - PayPal Standard Checkout SDK Client-Side Integration
This code demonstrates how to implement the PayPal Standard Checkout SDK client-side code using HTML.

**Prerequisites**
To use this code, you will need the following:

1. A PayPal developer account
2. A PayPal sandbox account

**Instructions**
1. Create a PayPal developer account and a PayPal sandbox account if you don't already have them.
2. Create a PayPal application for customers' checkout.
3. Note your PayPal client ID.
4. Save the attached .html file.
5. Open the .html file in a text editor.
6. Change the client ID on line 7 to your PayPal sandbox client ID.
7. Save the .html file.
8. Open the .html file in a web browser.

**Code Explanation**

The code in the .html file creates three PayPal buttons:

1. €10.00: This button allows customers to purchase a product for €10.00.
2. €100.00: This button allows customers to purchase a product for €100.00.
3. €1000.00: This button allows customers to purchase a product for €1000.00.
   
When a customer clicks on a price button, the selectPrice() function is called. This function removes any existing PayPal button container and creates a new one. It then renders the PayPal button in the new container.

The PayPal button uses the createOrder() function to create an order. The purchase_units property of the order object specifies the price of the product.

The PayPal button uses the onApprove() function to capture the payment. The details parameter of the onApprove() function contains information about the payment, such as the payer's name.

The PayPal button uses the onError() function to handle any errors that occur during the payment process.



**Troubleshooting**
If you are having trouble getting the code to work, please check the following:
Make **sure** that you have **changed the client ID on line 7 to your PayPal sandbox client ID**.
![image](https://github.com/AlexandrosGazis/PayPalHTML/assets/38253545/eb682845-05dd-486e-838d-947581dae9b1)

Make sure that you have JavaScript enabled in your web browser.


**Application Screenshots**

![image](https://github.com/AlexandrosGazis/PayPalHTML/assets/38253545/f064f4be-9d58-481a-84ef-60d90f028ec5)

![image](https://github.com/AlexandrosGazis/PayPalHTML/assets/38253545/d72f4d7f-8fb2-4ad5-a08c-d7874c79759d)




![image](https://github.com/AlexandrosGazis/PayPalHTML/assets/38253545/9999af5f-92a6-4604-ac2a-5cd820dcb84d)
![image](https://github.com/AlexandrosGazis/PayPalHTML/assets/38253545/09566db9-b543-401f-9c2b-2a7fbf13d076)
