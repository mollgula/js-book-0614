# 6/14 課題 学んだ記録

自身が学んだ記録を作りましょう。

- 関数(`function` で始まるコード)は全て function.js に書きます
- その他をREADME.md（このファイル）に書いていきます
    - 書き方は README-example.md (同じフォルダに同梱) を参考にしてください
- 書き方は自身でアレンジしてもかまいません


--------------------------------------

## 授業スライドの説明（4時間目～5時間目）

説明の中で実行したログ、分かったこと、疑問などがあればここに書く。

### Consoleの実行ログ

```
function sum() {
  var total = 0;
  for (var counter = 1; counter <= 10; counter++) {
      total += counter;
  }
window.alert(total);
}
undefined

function sum(rangeTo) {
  var total = 0;
  for (var counter = 1; counter <= rangeto; counter++) {
      total += counter;
  }
window.alert(total);
}
undefined

function sum(rangeFrom, rangeTo) {
  var total = 0;
  for (var counter = rangeFrom; counter <= rangeto; counter++) {
      total += counter;
  }
window.alert(total);
}
undefined

sum(2, 5)

function sum(rangeFrom, rangeTo) {
  var total = 0;
  for (var counter = 2; counter <= 5; counter++) {
      total += counter;
  }
window.alert(total);
}
undefined

sum(2, 5)
undefined

function sum(rangeFrom, rangeTo = 10) {
  var total = 0;
  for (var counter = rangeFrom; counter <= rangeto; counter++) {
      total += counter;
  }
window.alert(total);
}
undefined
function sum(rangeFrom = 1, rangeTo) {  //エラー
}
undefined

function sum(rangeFrom, rangeTo) {
  var total = 0;
  for (var counter = rangeFrom; counter <= rangeto; counter++) {
      total += counter;
  }
window.alert(total);
}
undefined

function sum(rangeFrom, rangeTo) {
  let total = 0;
  for (var counter = rangeFrom; counter <= rangeto; counter++) {
      total += counter;
  }
window.alert(total);
}
undefined

if (window.innerWidth < 1000) {
    window.alert('狭いです');
} else {
    window.alert('広いです');
}
undefined

var examinationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36 ,48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65, 81, 63, 45
  ]; 
undefined

function calculateTaxIncluding(scores) {
    var total = 0;
    for (var index = 0, index = scores.length; index++)
    {

      results.push(prices[index] * 1.08);
    }
    return results;
}

function calculateTaxIncluding(scores) {
    var total = 0;
    for (var index = 0, index = scores.length; index++) {
      total = scores[index];
}
    return total; 
}
function calculateAverege(scores) {
  return calculateTotal(scores) / scores.length;


}

var examinationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36 ,48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65, 81, 63, 45
  ]; 

undefined
var informationExaminExaminationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36 ,48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65, 81, 63, 45
  ]; 

var englishExaminationScores = [
    60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
    51, 51, 68, 68, 45, 64, 69, 60, 59, 55,
    52, 60, 59, 48, 56, 55, 67, 63, 54, 37
  ]; 

undefined

var informationExaminExaminationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36 ,48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65, 81, 63, 45
  ]; 

var englishExaminationScores = [
    60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
    51, 51, 68, 68, 45, 64, 69, 60, 59, 55,
    52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
    50, 55, 63,
  ]]; 

  examinationScores[0];
examinationScores[1];
examinationScores[0];


59
examinationScores[0];
examinationScores[1];
examinationScores[0][0];


undefined

var infomation = 0;
var english = 1;

var INFORMATION = 0;
var ENGLISH = 1;
examinaionScores[INFORMATION];
examinaionScores[ENGLISH];
examinaionScores[INFORMATION][0]; //出席番号1番の学生の情報のテスト結果

var examinationScores = {
  information : [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36 ,48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65, 81, 63, 45
  ], 

english : [
    60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
    51, 51, 68, 68, 45, 64, 69, 60, 59, 55,
    52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
    50, 55, 63, 50, 50,
  ]}; 
examinationScores.information;
examinationScores.english;

     
(35) [60, 69, 56, 65, 61, 43, 65, 52, 59, 61, 51, 51, 68, 68, 45, 64, 69, 60, 59, 55, 52, 60, 59, 48, 56, 55, 67, 63, 54, 36, 50, 55, 63, 50, 50]

function score(informationScore, englishScore) {
    return { information : informationScore, english : englishScore };
}



var examinationScores = [
  score(59, 60), score(84, 69), score(77, 56), score(53, 65),
  score(41, 61), score(20, 43), score(42, 65), score(53, 52),
  score(55, 59), score(54, 61), score(36, 51), score(48, 51),
  score(64, 68), score(70, 68), score(45, 45), score(54, 64),
  score(42, 49), score(50, 60), score(49, 69), score(53, 55),
  score(68, 52), score(60, 60), score(66, 59), score(53, 55),
  score(52, 56), score(55, 55), score(82, 67), score(61, 63),
  score(51, 54), score(43, 36), score(57, 50), score(65, 55),
  score(81, 63), score(63, 50), score(45, 50),
];


undefined

examinationScores[0];
examinationScores[0];.information;
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

【ここに書く】

### 疑問・分からないこと（もしあれば）

【ここに書く（なければ省略可）】

--------------------------------------

以下、教科書の自分で読んだ・実行した箇所について書く。

## 4-x ○○ (p.xx)

### Consoleの実行ログ

```
【ここに書く】
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

【ここに書く】

### 疑問・分からないこと（もしあれば）

【ここに書く（なければ省略可）】
