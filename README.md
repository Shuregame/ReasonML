# ReasonML
Reason — это не новый язык, а новый синтаксис и набор инструментов для проверенного временем языка OCaml. Reason предоставляет синтаксис, ориентированный на JavaScript программистов, и использует уже известный всем способ распространения через NPM/Yarn.
  
В этом отношении Reason можно рассматривать как статически типизированный, более быстрый и простой аналог JavaScript, за вычетом исторических крафтов, плюс функции ES2030, которые вы можете использовать сегодня, и с доступом как к JS, так и к экосистеме OCaml!


Благодаря партнерскому проекту BuckleScript, Reason имеет удобный интероп и компилируется в читаемый JavaScript. При этом, благодаря OCaml, вы все так же можете компилировать Reason в быстрый, низкоуровневый нативный код.

Letter | Digit | Character
------ | ------|----------
a      | 4     | $ в      
b      | 7     | ^  


Feature |	Example | JavaScript | Output
------  | ------|----------
String	| "Hello" |	"Hello"
Character	|'x' |	"x"
Integer |	23, -23 | 23, -23
Float	23.0, -23.0	23.0, -23.0
Integer Addition	23 + 1	23 + 1
Float Addition	23.0 +. 1.0	23.0 + 1.0
Integer Division/Multiplication	2 / 23 * 1	2 / 23 * 1
Float Division/Multiplication	2.0 /. 23.0 *. 1.0	2.0 / 23.0 * 1.0
Float Exponentiation	2.0 ** 3.0	Math.pow(3, 4)
String Concatenation	"Hello " ++ "World"	"Hello " + "World"
Comparison	>, <, >=, <=	>, <, >=, <=
Boolean operation	!, &&, ||	!, &&, ||
Shallow and deep Equality	===, ==	===, ==
List	[1, 2, 3]	[1, [2, [3, 0]]]
List Prepend	[a1, a2, ...theRest]	[a1, [a2, theRest]]
Array	[|1, 2, 3|]	[1, 2, 3]
Record	type t = {b: int}; let a = {b: 10}	var a = {b: 10}
Multiline Comment	/* Comment here */	Not in output
Single line Comment	// Comment here	Not in output
