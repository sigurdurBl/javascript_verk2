# javascript_verk2

1.)
  ECMAScript er forskriftarmálið sem er grundvöllur JavaScript
  
2.)
  Löggt ritað tungumál er forritunarmál sem þarf ekki að breyta breytu
3.)

4.)
 null er verkefni gildi. Það er hægt að úthluta breytu sem framsetning án gildis og 
 undefined er tegund sjálft (óskilgreint) en null er hlutur
 
 5.)
 === finnur strict equality  milli tveggja gilda. Bæði gerð og gildi sem þú ert að bera saman þarf að vera nákvæmlega það sama.
 ==  finnur loose equality og framkvæma tegundarþvingun. Þetta þýðir að við bera saman tvö gildi eftir að hafa breytt 
 þeim í sameiginlega gerð.
 6.)
 Let
 let x = 1;

if (x === 1) {
  let x = 2;

  console.log(x);
  // expected output: 2
}

console.log(x);
// expected output: 1
var
var x = 1;

if (x === 1) {
  var x = 2;

  console.log(x);
  // expected output: 2
}

console.log(x);
// expected output: 2
 7.)
  arrow function
 var materials = [
  'Hydrogen',
  'Helium',
  'Lithium',
  'Beryllium'
];
function  expression
console.log(materials.map(material => material.length));

function getRectArea(width, height) {
  return width * height;
}
console.log(getRectArea(3,4));
; 
function declarations
function calcRectArea(width, height) {
  return width * height;
}
console.log(calcRectArea(5, 6));
8.)
Það kemur í veg fyrir eða kastar villur þegar tiltölulega "óöruggar" aðgerðir eru gerðar, svo sem að fá aðgang að alþjóðlegu hlutanum

9.)
x er undefined
10.)
aalert(foo) kemur first  og gefur til baka 8 svo kemur hin function og hún er undefined
11.)
hún verður undefined ef ekki er set var eða let
12.)
þessi funtion sendir alert til notanda með hello world
13.)
varible scope getur verið annaðhvort alþjóðlegt eða staðbundið svigrúm. Hnattræn breytur er breytur sem lýst er í meginmáli frumkóðans, 
utan allra aðgerða, en staðbundin breytur er einn lýst innan líkama aðgerðar eða blokkar.
14.)
call stack er stafla gögn uppbygging sem geymir upplýsingar um virka subroutines tölvuforrit
