In this project, let's build a Cash Withdrawal app by applying the concepts we have learned till now.

Refer to the image below:

![image](https://github.com/bukka5sandhya/React-Js-CashWithdrawal-/assets/133884532/04837a16-3a7d-4544-94a5-67a510cca30e)

https://assets.ccbp.in/frontend/content/react-js/cash-withdrawal-output-v2.gif

Design Files

Click to view

Extra Small (Size < 576px) and Small (Size >= 576px)

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)

Set Up Instructions

Click to view

Download dependencies by running npm install

Start up the app using npm start

Completion Instructions

Functionality to be added

The app must have the following functionalities

Initially, the balance should be 2000 rupees

When a denomination is clicked, then the respective value should be deducted from the balance available

The CashWithdrawal component receives the denominationsList as a prop. It consists of a list of denomination objects with the following properties in each denomination object

Key	Data Type

id	Number

value	Number

Components Structure

![image](https://github.com/bukka5sandhya/React-Js-CashWithdrawal-/assets/133884532/ba8dafa4-dc8e-4c84-808d-064039fb652c)

Implementation Files

Use these files to complete the implementation:

src/components/CashWithdrawal/index.js

src/components/CashWithdrawal/index.css

src/components/DenominationItem/index.js

src/components/DenominationItem/index.css

Quick Tips

Click to view

The string method slice() extracts a section of a string and returns it as a new string, without modifying the original string

const text = "The quick brown fox";
console.log(text.slice(0, 3)); // The
console.log(text.slice(2, 3)); // e

You can use the cursor CSS property to specify the mouse cursor to be displayed when pointing over an element

  cursor: pointer;

![image](https://github.com/bukka5sandhya/React-Js-CashWithdrawal-/assets/133884532/8ca9796d-986a-41a1-9db2-697c42184e6c)

You can use the below outline CSS property for buttons and input elements to remove the highlighting when the elements are clicked

 outline: none;

Resources

Colors

Hex: #150b3e

Hex: #c7d2fe

Hex: #7c3aed

Hex: #d4d2db

Hex: #585076

Hex: #382f5a

Hex: #c4c4c4

Font-families

Roboto

Things to Keep in Mind

All components you implement should go in the src/components directory.

Don't change the component folder names as those are the files being imported into the tests.

Do not remove the pre-filled code

Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
  
