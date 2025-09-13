# goit-js-hw-01

-----TASK-01-----

A station for selling repair droids is ready to launch, the only thing left is
to write the software for the sales department.

Declare a function makeTransaction, which expects two parameters whose values
will be provided during the function call:

quantity — the first parameter, a number representing the quantity of ordered
droids

pricePerDroid — the second parameter, a number representing the cost of one
droid

Extend the function code so that it returns a string with a message about the
purchase of repair droids: "You ordered <quantity> droids worth <totalPrice>
credits!", where:

<quantity> is the number of ordered droids

<totalPrice> is the total cost of the order, i.e., the cost of all ordered
droids

The console will output the results of its execution.
console.log(makeTransaction(5, 3000)); // "You ordered 5 droids worth 15000
credits!" console.log(makeTransaction(3, 1000)); // "You ordered 3 droids worth
3000 credits!" console.log(makeTransaction(10, 500)); // "You ordered 10 droids
worth 5000 credits!"

-----TASK-02-----

Declare a function getShippingMessage, which expects three parameters whose
values will be provided during the function call:

country — the first parameter, a string containing the delivery country

price — the second parameter, a number representing the total cost of the goods

deliveryFee — the third parameter, a number representing the delivery cost of
the goods

Extend the function code so that it returns a string with a message about the
delivery of the goods to the user’s country: "Shipping to <country> will cost
<totalPrice> credits", where:

<country> is the delivery country

<totalPrice> is the total order cost, including the price of the goods and the
delivery fee

Take the code below and insert it after your function declaration to test its
correctness. The console will output the results of its execution.

console.log(getShippingMessage("Australia", 120, 50)); // "Shipping to Australia
will cost 170 credits" console.log(getShippingMessage("Germany", 80, 20)); //
"Shipping to Germany will cost 100 credits"
console.log(getShippingMessage("Sweden", 100, 20)); // "Shipping to Sweden will
cost 120 credits"

-----TASK-03-----

Declare a function getElementWidth, which expects three parameters whose values
will be provided during the function call:

content — the first parameter, the content width

padding — the second parameter, the horizontal padding value for each side

border — the third parameter, the border thickness value for each side

The values of all parameters will be strings in the format Npx, where N is any
number, integer or fractional.

Extend the function code so that it returns a number — the total width of the
element. When calculating the total width, take into account that the value of
box-sizing is equal to border-box.

Take the code below and insert it after your function declaration to test its
correctness. The console will output the results of its execution.

console.log(getElementWidth("50px", "8px", "4px")); // 74
console.log(getElementWidth("60px", "12px", "8.5px")); // 101
console.log(getElementWidth("200px", "0px", "0px")); // 200
