var input = "javascript is awesome";
var output = "";
for (var k = 0; k < input.length; k++) {
        if (input[k] === "a") { output += "4"; } 
            else if (input[k] === "e") { output += "5"; } 
            else if (input[k] === "i") { output += "1"; } 
            else if (input[k] === "o") { output += "0"; } 
        else { output += input[k] };
};
console.log(output);     
