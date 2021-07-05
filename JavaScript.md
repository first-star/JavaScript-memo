# JavaScript memo

```javascript
console.log("Line 1\nLine 2"); // Line 1 改行 Line 2と出力する。 \はoption + ¥で入力
console.log("This is"          // 行末まで "も;も無視してコメント
,"a pen.");                    // 行末までコメント
console.log( "One"            /* この記号で始まるコメントは...
複数行にわたってコメントとみなされ,
次の行にあるコメントの終了記号までが、
コメントになる */ , "Line.");
```
<br>

```javascript
// program02_03.js: 変数、代入、データ型
var x, y, z;
x=100;
y=23;
z=x+y;
// x + y は数値計算となり 123 になる
console.log("x=",x," y=",y,"z=",z);
x="abc";
y="de";
z=x+y;
// x + y は文字の結合になり "abcde" になる
console.log("x=",x," y=",y," z=",z);
x="100";
y="23";
z=x+y;
// x + y は文字の結合になり "10023" になる
console.log("x=",x," y=",y," z=",z);
```
**出力結果**
```
x= 100  y= 23 z= 123
program02_03.js:7
x= abc  y= de  z= abcde
program02_03.js:12
x= 100  y= 23  z= 10023
```
<br>

