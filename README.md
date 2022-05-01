# Core Code "Readme Dante"

### Interpreted And Compiled Programming Languages 

- Compiled Languages
It is a language that is converted into binary code, when the programmer sends the code to the machine it is transformed into machine code. The language is rebuilt once the programmer is "done" testing the code.

- Interpreted Languages
The interpreted language is converted line by line in real time, without the need for an extra compilation or conversion step.


### Is Java compiled or interpreted, or both? 
- JAVA It is a language that is compiled into a program called BYTECODE, and then passed through a visual machine that interprets it to finally pass it to the CPU. Also called JUST IN TIME, this method is used to improve the performance of the interpreted programs.


### Pseudocode Currency Converter 
START 
DOLLAR <-- GET 
BITCOIN <-- GET  
TOTAL <-- DOLLAR * BITCOIN
 PRINT “Write amount of dollars to convert” 
READ DOLLAR
 PRINT " Enter the price of bitcoin"
READ BITCOIN
PRINT “the total bitcoin would be“, TOTAL
END

### Your date of birth in the matrix? 
- 11011   01   1101001


### Print special numbers:

        //ciclo for
        for(numero = 0; numero <= 200; numero +=2){
        document.write(numero + ",");
        }

        //ciclo while
        let numeros = 0;
        while(numeros <= 101){
            document.write(numeros + ",");
            numeros += 2;
        }

        //ciclo do while
        var num = 0;
        do {
            if(num % 2 ==0)console.log(num);
        }while (num + ",")

### Bad Code
- because the variable was already assigned with the false value and it is not necessary to assign that value again, but rather it is necessary to make a comparison

        var cond = false;
        if (cond == false) {
          document.write('The cond variable is true');
        } else {
          document.write('The cond variable is false');
        }

### Bad code 2

        var n = 100;
        
        if (n == 100) {
          console.log('This is a special number!');
        }
        else if (n < 1000 && n % 10 == 0) {
          console.log('This number is almost special');
  
        } else {
          console.log('Just a regular number');
        }
  
WEEK 2
-------------

### Multiply
        
        function multiply(a, b){
        return a * b
        }
        
### ASCII Total

### ASCII Value 

        function getChar(c){
           return String.fromCharCode(c);
        }
### Binary Addition 
        function addBinary(a,b) {
          return (a + b).toString(2);
        }
        
### Student's Final Grade
     function finalGrade(exam, projects) {
      if (exam > 90 || projects > 10) return 100;
      else if (exam > 75 && projects >= 5) return 90;
      else if (exam > 50 && projects >= 2) return 75;
      else return 0; }


