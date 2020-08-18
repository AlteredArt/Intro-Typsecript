# Intro-Typsecript
version -tsc --version
create some js code in a .ts file
-tsc index.ts
This creates an index.js file (deafults to es3 which doesnt have async or await)
writing async function in typescript compiles down to nasty code
this diluets the index.js
so touch a tsconfig.json file
-touch tsconfig.json
run tsc after congifuring config file
-tsc