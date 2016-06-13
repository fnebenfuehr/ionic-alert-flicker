## run
1. git clone
2. npm install .
3. ionic emulate ios

## reproduce
click on select => the screen flickers

## explaination
the class `disable-scroll` is added to the body tag while the popup is open, I beleave this is related with this issue...