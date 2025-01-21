const trimText = str => str.trim();
const toLowerCase = str => str.toLowerCase();

function cleanText(str) {
    return toLowerCase(trimText(str));
}

console.log(cleanText("   Javascript!  ")); // javascript!


** for this fuction to unerstand we have to read from bottom right of this code. here the text is Javascript with some white spaces. so the text is Javascript.  **

here 4 function are used. They are:
1. trimText - Trims whitespace from a string.
2. cleanText - Trims whitespace and converts to lowercase (corrected version provided).
3. toLowerCase - Converts a string to lowercase.
4. console.log