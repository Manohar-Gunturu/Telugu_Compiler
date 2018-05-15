# T_Compiler
## Compiler for a programming language having keywords in telugu speaking language

Download T_Compiler from https://drive.google.com/open?id=1Yl7MMT7QWp_ij6s2qr77JY45PAMpGYOv

Open cmd and navigate to T_compiler.exe folder, and then just run t_compiler in cmd.  

![alt text](https://raw.githubusercontent.com/Manohar-Gunturu/Telugu_Compiler/master/sample.png)


## This was built from scratch, without any tools.

## Below are the supported features
 - Integers are supported with keyword sankhya
 - classes are supported with keyword samuham
 - int arrays are supported
 - No strings, sorry
 - 0 is treated as false, and 1 as true



Example program

## To check if a number is even or odd
          
          sankhya iseven(sankhya num){
            ayite(  num % 2 == 0  ) appudu{   // if statement
               tirigi (1); // return statement
            } lekapote{ // else block
              tirigi (0);    
            };
          };

          prarambham{  // main
            sankhya count;  // int variable declaration 
            chaduvu(count); //read value from command prompt
            count = iseven(count);
            mudrinchu(count);  // print
          };
          

## array example to find maximum.

           prarambham{  // main
             sankhya arr[5]; 
             sankhya max;  
             arr[0] = 2; 
             arr[1] = 20; arr[2] = 23;   
             arr[3] = 28; arr[4] = 24;   
             max = 0; 
             //for loop
             phalitanga(sankhya i = 0; i<5; i = i + 1){
                //if statement
                ayite(  arr[i] > max  ) appudu{   
                     max = arr[i];
                 } lekapote{ };
             };

             mudrinchu(max);
           };
          

## Program to find student with maximum marks

             //class declaration
             samuham Object{
               //only definitions are allowed here
               sankhya id;
               sankhya marks;
             };

             //function def
             sankhya findMax(Object o1, Object o2){
                ayite(  o1.marks > o2.marks  ) appudu{   
                        tirigi (o1.id); 
                 } lekapote{ 
                       tirigi (o2.id);    
                 };
             };


             prarambham{  // main
                sankhya max_marks_id;
                Object b1; Object b2;
                b1.id = 1;
                b1.marks = 89;
                b2.id = 2;
                b2.marks = 9;
                max_marks_id = findMax(b1,b2); 
                mudrinchu(max_marks_id);
             };


