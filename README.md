# T_Compiler
## Compiler for a programming language having syntax in telugu speaking language

Download T_Compiler from https://drive.google.com/file/d/1AgPjfF6wAnX9wDO18OjtM2-_qtPdY3BV/view?usp=sharing

This was compiler built from scratch, without any tools. 

## Below are the supported features
 - Integers are supported with keyword sankhya
 - classes are supported with keyword samuham
 - int arrays are supported
 -No strings, sorry


Example program

          
          sankhya iseven(sankhya num){
            ayite(  num % 2 == 0  ) appudu{   // if statement
               tirigi (1); // return statement
            } lekapote{ // else block
              tirigi (0);    
            };
          };

          prarambham{  // main
            sankhya count;  // int variable declaration 
            count = iseven(2);
            mudrinchu(count);  // print
          };
          
