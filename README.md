# olegcaptcha
An approach to human verification using coordinates and color-value of strings

# brief description 
  - webpage randomly allocates coordinates to strings, as well randomly assigning two strings a visible color-value
  - if the user inputs the two visible strings in the manner instructed, they pass the verification 
  
<b>Code presented here uses a pre-defined set of possible strings and serves only as proof-of-concept. If you wish to implement this method as an actual form of Human verification, do one of the following:</b>
  - Define more possible strings such that brute-force methods become impractical. If this, implement a way to display a set number of said strings as to not upset the buffer
  - Implement a method to generate a different set of possible strings for every instance of loading the page 
