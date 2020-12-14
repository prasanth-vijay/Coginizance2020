# Task 6

>## **Armstrong numbers**


>Pseudo code for armstrong numbers 

Start

* _Declare_ 

    * num as integer
    * temp
    * result as integer
    * r as integer

<!-- strong -->
**OUTPUT** "enter the number that is num"

**INPUT** user inputs the number
* _READ_

    * result = 0
    * temp = num
    
* Create a _while loop_ for the condition _number < 1000_
* Inside the while loop , 
        
    

       *  r= temp % 10
       *  result = result + (r)^3 
       *  temp = temp/10
* Create a _while loop_ for the condition _number > 1000_
* Inside the while loop ,
       
       *  r= temp % 10
       *  result = result + (r)^4 
       *  temp = temp/10


* Create a _if loop_ 
      
      * if result == num is true , then give the number is _a Armstrong number_ as  _output_
      * if result == num is false , then give the number is _not a Armstrong number_ as _output_

  End