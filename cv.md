___
# Marina Yanysheva
#### *Frontend developer*
<img src="assests/photo.jpg" width="250">

___

#### Contact information:
**Location:** Tbilisi, Georgia  
**Phone:** +995 551 077 409  
**E-mail:** m.yanysheva@inbox.ru  
**Telegram:** @marikafikys  
[LinkedIn](https://www.linkedin.com/in/marina-yanysheva/)
[GitHub](https://github.com/marikafikys)
___

#### About Me:
After 6 years of experience in the power industry and relay protection, in 2021 I became interested in front-end development and am very happy to develop in this direction.
I want to serve the world by creating and maintaining optimally functional websites and applications as tools to achieve the mission and vision of companies.

At the moment I am open to everything that will allow me to gain experience and improve my knowledge in the field of web development.

I will be glad to cooperate! :)

___

#### Skills and Proficiency:
- HTML5
- CSS3
- JavaScript
- ReactJS
- Git, GitHub

___

#### Code example:
***RGB To Hex Conversion KATA from CODEWARS (5kyu):***
*The rgb function is incomplete. Complete it so that passing in RGB decimal values will result in a hexadecimal representation being returned. Valid decimal values for RGB are 0 - 255. Any values that fall out of that range must be rounded to the closest valid value. Note: Your answer should always be 6 characters long, the shorthand with 3 will not work here.*
```
function rgb(r, g, b){
	let hexstring = "";
	let rgb = [r, g, b];
	 rgb.forEach(num => {
		 let hexnumber = Math.min(Math.max(num, 0), 255).toString(16).toUpperCase();
		 hexnumber.length > 1 ? hexstring += hexnumber : hexstring += "0" + hexnumber;
	 });
	  return hexstring;  
 }
```
___
