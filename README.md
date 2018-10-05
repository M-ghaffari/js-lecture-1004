# テクノロジー（藤原） 10/4課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```
var str = "Hello";
undefined
var nam = 123;
undefined
var flag = true;
undefined
s
VM1533:1 Uncaught ReferenceError: s is not defined
    at <anonymous>:1:1
(anonymous) @ VM1533:1
screen
Screen {availWidth: 360, availHeight: 640, width: 360, height: 640, colorDepth: 24, …}
var s = "Hello"
undefined
s
"Hello"
s.length
5
s.fixed
ƒ fixed() { [native code] }
s.fixed()
"<tt>Hello</tt>"
window.outerWidth
360
var list = ["JavaScript","HTML","CSS"];
undefined
console.log(0)
VM1908:1 0
undefined
console.log(list[0])
VM1935:1 JavaScript
undefined
console.log(list[1])
VM1944:1 HTML
undefined
console.log(list[4])
VM1954:1 undefined
undefined
console.log(list[3])
VM1966:1 undefined
undefined
console.log(list[0])
VM1974:1 JavaScript
undefined
console.log(list[2])
VM1983:1 CSS
undefined
var list2 = ["js":"ジャバスクリプト","HTML":"エイチティーエムエル","CSS":"シーエスエス"];
VM2090:1 Uncaught SyntaxError: Unexpected token :
var list2 = {"js":"ジャバスクリプト","HTML":"エイチティーエムエル","CSS":"シーエスエス"};
undefined
console.log(list2[2])
VM2126:1 undefined
undefined
console.log(list2[2]);
VM2130:1 undefined
undefined
console.log(list2[0]);
VM2138:1 undefined
undefined
console.log(list2["js"]);
VM2150:1 ジャバスクリプト
undefined
var str = "文字数数えて"
undefined
var str = "文字数数えて";
undefined
console.log(str.length);
VM2247:1 6
undefined
var date = new Date();
undefined
console.log(date.toLocaleString());
VM2400:1 2018/10/5 11:47:37
undefined
var str = navigator.platform+"/n"+navigator.userAgent+"/n";
undefined
window.alert(str);
undefined
```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```
