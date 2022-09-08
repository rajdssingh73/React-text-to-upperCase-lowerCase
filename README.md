# csb-q9vinl
// Changing to upperCase & LowerCase using React useState 
Deployed link - https://csb-q9vinl.netlify.app/

Approach
1- Created a textarea in which user can enter the value.
2- Created a buttons to convert the texts to lower case & toUpperCase
3- Assigned onclick event attributes to both buttons.
4- In textarea handleChange function which (triggered by the input element).
5- define & import useState from react & assign the input text value.
6- Set the text (setText) to (event.target.value) because as every onChange function returns events.
7 - Define both handleUpClick & handleClick functions & set the respective value's like
7 a- handleUpClick will handle newText = text.toUpperCase() & then setText using - setText(newText);
7 b- Similar for handleClick,newText = text.toLowerCase()
