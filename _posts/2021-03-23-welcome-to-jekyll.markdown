---
layout: post
title:  "Building a cloud data analytics platform"
date:   2021-03-23 21:03:36 +0530
categories: Cloud Data 
---
This post is about building data platforms

```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
	key_id: 'KEY_ID',
	secret: 'name'
});

// capture request
rzp.capture(payment_id, cost)
	.then(function (data) {
		return 2;
	})
```
