# Contact Data Separator

Ek simple website jisme aap mixed contact data paste karte ho, aur JavaScript use **Name**, **Phone** aur **Email** me alag-alag variables me separate kar deta hai.

Bana hai sirf **HTML + CSS + JavaScript** se. Koi library nahi chahiye.

---

## Website kya karti hai?

Input (mixed data):

```
Rahul Sharma, 9876543210, rahul.sharma@gmail.com
Priya Singh | priya.singh@yahoo.com | +91 98765 43211
Name: Amit Kumar  Phone: 98123-45678  Email: amit@outlook.com
```

Output (JavaScript variables me):

```js
let contacts = [
    { name: "Rahul Sharma", phone: "9876543210", email: "rahul.sharma@gmail.com" },
    { name: "Priya Singh", phone: "+91 9876543211", email: "priya.singh@yahoo.com" },
    { name: "Amit Kumar", phone: "9812345678", email: "amit@outlook.com" }
];

let names  = ["Rahul Sharma", "Priya Singh", "Amit Kumar"];
let phones = ["9876543210", "+91 9876543211", "9812345678"];
let emails = ["rahul.sharma@gmail.com", "priya.singh@yahoo.com", "amit@outlook.com"];
```

Features:

