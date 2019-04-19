# rupees-to-words
NPM module to convert rupees into words

# Description:
  Module that changes the amount to string. Paisa also handled.
  
# Usage
CMD: npm i rupees-to-words

import convertor from 'rupees-to-words';

const words = convertor(1234.12);<br>
//OUTPUT -> One Thousand Two Hundred Thirty Four Rupees  and  Twelve Paisa<br>
<br>
const words = convertor(123000);<br>
//OUTPUT -> One Lakh Twenty Three Thousand  Rupees<br>
<br>
const words = convertor(9999.01);<br>
//OUTPUT -> Nine Thousand Nine Hundred Ninety Nine Rupees  and  One Paisa<br>
<br>
const words = convertor(10000.99);<br>
//OUTPUT -> Ten Thousand  Rupees  and  Ninety Nine Paisa<br>
