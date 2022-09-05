# React Stripe.js 

![donut-shop](https://user-images.githubusercontent.com/59585336/74299251-111fb300-4d1a-11ea-932b-a6e7b33f6ea8.gif)

### Some Learning 

client secret is a piece of info that is used to securely complete the payment instead of storing the entire PaymentIntent object. 


const paymentMethodReq = stripe.createPaymentMethod({ 
type: "card", 
card: cardElement,
billing_details: billingDetails 
}) 


![alt text](https://github.com/taroserigano/Super_SimpleReact__Stripe_Practice/blob/main/tm1.png)


const confirmeCartPayment = stripe.confirmCardPayment(clientSecret, 
{ paymentmethod: paymentMethodReq.paymentMethod.id 
}) 




![alt text](https://github.com/taroserigano/Super_SimpleReact__Stripe_Practice/blob/main/tmp2.png)
