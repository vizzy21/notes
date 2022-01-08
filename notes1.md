# python notes
\\So this will be the own made notes from free code camp\\
1) so basic print option : print(""); ( Basic python program )
  How to draw a shape in py 
  print("    /")
  print("   /")
  print("  /")
  print("\//")
  so we can basically print anything inside this print statement
   print("this is vishal here printing text");
  !ok so just in case you want to change the name vishal to something else ..and think that its a very big program having the name lots of  times.. you cant go n  change your name manually at every place so thats where variables come in
  
  ## Variables
Will be used all most all the time
  
  variables are used to store the data 
  in the above case the syntax would be if i want to store my name in a variable called character_name
  character_name = "vishal"
   example : 
character_name = "inamul"
print("so this is " + character_name + " here")
so the output would be 
so this is inamul here

// so if we update in one position.. it gets updated throughout the program"
  
  ### Different types of data u could store in a variable
 1. You dont need to specify the datatype in python .This includes int,float,boolean,string;
 2. ex : age = 50 , rate = 826.90 , name = "vizzy"
 
 ### All things that could be done by a string
1.\n : pushes it to the next line
 ex : print("Giraffe \n man")}
      output : Giraffe
                man
2. so if we wanna print giraffe "Man" with man double quotes , the compiler will get confused because of it..so we need to specify 
ex: print("Giraffe \"Man\"")
      output : Giraffe "Man"
 
3. Store the thing u want to print in a variable and print the variable instead
ex: character = viz
    print(character)
    output : viz
4. we can add anything we want to the given string using + symbol
ex : ex: character = viz
    print(character + "is cool")
    output : viz is cool
5: Functions that could be useful [.()]
 suppose phrase = "LOL" is the given string
 phrase.upper() //Changes all the letters in phrase to uppercase
 phrase.lower() //Changes all the letters in phrase to lowercase
 phrase.isupper() // to check upper returns  true or false
 phrase.islower() 
   can also be used togother to check if its changed correctly to upper or lower case and reutrn a true or a flase value
   ex : phrase = "viz"
        print(phrase.upper().isupper())
        output:TRUE
       !how to find the number of characters in a string??
        pass the string inside len function
 print(len(phrase)) 
 output : 3
        !how too fnd what element is present at what location
        print(phrase[2]) // remember string starts with 0 in python
        
For example we want to find the element stored at a given particular index ..say i wanna know whats stored in index 2 ..so i pass the letter a and wanna find a
passing a value inside a fucnction for it to perform any work is called as parameters of a function

phrase = "im a programmer"
print(phrase.index(a))
so the output will be 3 causethe counting starts from zero index in a string or array

So now you wanna replace a particular letter in a string ..its a big program.. you cant manually go to each and every place and replace right so we have a replace fun
syntax : variable name.replace("","") // 1st:what letter u wanna replace 2nd: what u wanna replace it with
phrase = "im a programmer"
print(phrase.replace("im", "maybe"))
output : maybe a programmer
these were the main string operations that'll be used

   

 
