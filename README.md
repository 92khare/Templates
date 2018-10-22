# Templates
This repository contains templates
/*function generatePyramid() {
    console.log("hello");
    var rows = 6;
    var output=" ";
    for (var i = 1; i <=rows; i++) {
        
        for (var j = i; j <rows; j++) {
            output+=" ";
    
        }
        for(var z=1;z<(i*2);z++){
            if(z%2==0){
                output+=" ";
               
            }else{
            output+="*";
            
        }
        
        
        //document.write("\n");
    }
    console.log("\n");
    
        
        
        
    }
    console.log(output);
    
}  */

function generatePyramid() {
    console.log("hello");
    var rows = 6;
    var output='';
    for (var i = 1; i <=rows; i++) {
        
        for (var j = i; j <rows; j++) {
            output+=' ';
    
        }
        for(var z=1;z<(i*2);z++){
            if(z%2==0){
                output+=' ';
               
            }else{
            output+='*';   
        }
        //document.write("\n");
    }
    console.log(output);
    output='';
    //console.log("\n");   
    }
    
    
} 
function stars(n){
    var str = '';
    for(var i=1; i<=n; i++){
        for(var k=1; k<=n-i; k++){
            str += "\t";
        }
        for(var j=1; j<=i; j++){
            str += "*\t\t";
        }
        console.log(str);
        str = "";
    }
}

//console.log(stars(6));
console.log(generatePyramid());

