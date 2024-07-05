```javascript
/* 
use functions to do stuff like scss but make it simpler and/or more flexible(if it cant be simple at least make it easy to use and well documented)

stuff i usually use scss for:
- generating classes in a range or from an array with the help of maths and logic
- pseudoclasses like :hover, :focus, :active etc and pseudo elements like ::before, ::after
- decoupling logic using imports and exports
- this is almost legitimately all I need; but I can bypass the strange rules of scss; i could probably do a lot with functions returning strings from template literals, and basic logic/maths; i just need to ensure that I dont over abstract/decouple the logic; and as for compiling, all i need to use is fs and it will be simple; then after that I can just use gulp to run the command to compile, and then compile the minified file from the dist folder using clean-css or whatever its called.
*/
```