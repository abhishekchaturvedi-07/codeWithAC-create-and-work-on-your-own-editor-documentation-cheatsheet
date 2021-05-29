## OBJECTIVE: 
**CREATING A CODE EDITOR LIKE CODEPEN/CODESANDBOX/... FOR MYSELF(https://github.com/abhishekchaturvedi-07), TO FEEL GOOD TO WORK ON MY OWN CODE EDITOR, WHERE I CAN CREATE SOME DOCUMENT OR CHEATSHEET AFTER MY TRIAL WORK AND THEN CAN DIRECTLY APPLY THE CODE IN MY PRODUCTION LEVEL CODE TO OPTIMIZE IT IN A BETTER WAY. THIS WILL WORK SAME AS SOME ONLINE EDITOR TOOLS,I WAS ALWAYS WONDERED HOW THEY WORK, NOW I UNDERSTAND THE MEHANSM BEHIND THE SCENE AND STARTING TO IMPLEMENT IT FOR MY OWN. BEFORE WORKING ON THIS I ALREADY WORKED ON THE BASICS OF THE ONLINE TRANSPILER AND DYANAMIC UPDATION OF DEPENDENCIES FROM NPM, SO WILL HELP ME CREATING THIS AWESOME APPLICATION**
"Challanges":
Code will be provided to Preview as a string, Have to execute it safely
##Code might have advance js syntax in it like jsx that the browser cant execute 
###code might have import statement for other js or css file . have to deal with those imports before execution
"PRE - REQUISTIES" :
##Understanding of Transpiler (Babel - babljs.io)
##Understanding of JS Modules (common JS and ES module)
###Understanding of Bundler (WEBPACK/ESBUILD - https://esbuild.github.io/)
###Understanding of finding dependency from NPM
Understanding of UNPKG(solution for CORS issue from npm registry - unpkg.com, dont download it just unkg it)
**ESBUILD --> onResolve(multiple) + onLoad (filters+namespace)**