---
layout: post
title:  "JWT and Node Authentication"
date:   2014-06-08 21:01:31
categories: authentication
---

<img src="http://photos-g.ak.instagram.com/hphotos-ak-xpa1/10424467_346667108815462_478798941_n.jpg" width="200" height="200" alt="Mapping Authentication on The White Board">

<p>We started this week with a look at authentication. We covered the JSON Web Token (JWT) approach to authentication. I learned to exchange a valid login and password for a token instead of supplying the username and password with every request.</p>

<p>It is also more secure to send a token with an API call. A JWT is encoded as a JSON object and signed or encrypted. We looked at using the JWT Simple module to handle the encoding and decoding of tokens.</p>

<p>I also discovered how helpful Nodejs authentication is with the Express framework. It reduces the total code needed by almost two-thirds. I can easily see myself using Node.js, Express and Passport.</p>

