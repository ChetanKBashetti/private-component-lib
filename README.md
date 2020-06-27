# private-component-lib

# Usage 

step 1 : npm i cb-add-two-num // install paceage cb-add-two-num

step 2 : const sum = require("cb-add-two-num"); //Import in any component usining require
 
step 3 : export default function addNumbers() {
          return (
                {sum.default(10, 100)} // 2 arguments 10,20
          );
         }
