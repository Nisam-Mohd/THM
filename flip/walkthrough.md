#what i did

The challenge uses admin and sUp3rPaSs1 as uname and passwd,
so i change username admin to adMin with passwd sUp3rPaSs1,
it gives me a cipher in hex
i take the 3rd hex value [99] from the given cipher
then on cyber chef 
   input : 99 
   recipe:
      From Hex : Auto
      XOR      : M - utf-8
      To Hex
  Output : d4

then again
 
  input : d4
  recipe: 
    >  From Hex : Auto
    >  XOR      : m - utf-8
    >  To Hex   : 
  output: b9

replace the 'b9' at the place of 99 

https://youtu.be/Sw5v17YaftI


