# olegcaptcha
An approach to human verification using coordinates and color-value of strings

# Brief description 
  - Webpage randomly allocates coordinates to strings, as well randomly assigning two strings a visible color-value
  - If the user inputs the two visible strings in the manner instructed, they pass the verification 
  
<b>Code presented here uses a pre-defined set of possible strings with all logic presented client-side. It serves only as proof-of-concept. If you wish to implement this method as a practical form of Human verification, you must do the following:</b>
  - Define more possible strings such that brute-force methods become impractical. If this, implement a way to display a set number of said strings as to not upset the buffer OR Implement a method to generate a different set of possible strings for every instance of loading the page 
  - Handle the JS script logic server-side
  
<b>With the changes above, it is still NOT recommended to use this as a sole form of Human verification, except for cases where the limitations of client-side code execuition are well understood</b>  
