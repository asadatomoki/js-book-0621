# 6/21 課題 学んだ記録

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
【var examinationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65 ,81, 63, 45
];
undefinedfunction calculateTotal(scores) {
    var total = 0;
    for (var index = 0; index < scores. length; index++) {
        total += scores[index];
    }
    return total;
}
function calculAverage(scores) {
    return calculateTotal(scores) / scores.length;
}
undefinedvar informationExaminationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    50, 65, 81, 63, 45
];var englishExaminationScores = [
    60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
    51, 51, 68, 68, 45, 64, 49, 60, 59, 55,
    52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
    50, 55, 63, 50, 50
];
undefinedvar examinationScores = [[
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65 ,81, 63, 45
], [
    60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
    51, 51, 68, 68, 45, 64, 49, 60, 59, 55,
    52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
    50, 55, 63, 50, 50,
    ]];
undefinedexaminationScores[0];    // 情報のテスト結果
examinationScores[1];    //英語のテスト結果
examinationScores[0][0]; //出席番号１番の学生の情報のテスト結果
59var information = 0;
var english = 1;
examinationScores[information];
examinationScores[english];
examinationScores[information][0]; //
59var INFORMATION = 0;
var ENGLISH = 1;
examinationScores[INFORMATION];
examinationScores[ENGLISH];
examinationScores[INFORMATION][0]; //
59var examinationScores = {
    information : [
        59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
        36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
        68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
        57, 65, 81, 63, 45
],
english : [
    60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
    51, 51, 68, 68, 45, 64, 49, 60, 59, 55,
    52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
    50, 55, 63, 50, 50,
]};
examinationScores.information;  //
examinationScores.english;  //
(35) [60, 69, 56, 65, 61, 43, 65, 52, 59, 61, 51, 51, 68, 68, 45, 64, 49, 60, 59, 55, 52, 60, 59, 48, 56, 55, 67, 63, 54, 36, 50, 55, 63, 50, 50]】
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

【なんとなくわかった】

### 疑問・分からないこと（もしあれば）

【ここに書く（なければ省略可）】

--------------------------------------

以下、教科書の自分で読んだ・実行した箇所について書く。

## 5-1-4 (p.108)

### Consoleの実行ログ

```
【【var examinationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65 ,81, 63, 45
];
undefinedfunction calculateTotal(scores) {
    var total = 0;
    for (var index = 0; index < scores. length; index++) {
        total += scores[index];
    }
    return total;
}
function calculAverage(scores) {
    return calculateTotal(scores) / scores.length;
}
undefinedvar informationExaminationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    50, 65, 81, 63, 45
];var englishExaminationScores = [
    60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
    51, 51, 68, 68, 45, 64, 49, 60, 59, 55,
    52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
    50, 55, 63, 50, 50
];
undefinedvar examinationScores = [[
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
    68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
    57, 65 ,81, 63, 45
], [
    60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
    51, 51, 68, 68, 45, 64, 49, 60, 59, 55,
    52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
    50, 55, 63, 50, 50,
    ]];
undefinedexaminationScores[0];    // 情報のテスト結果
examinationScores[1];    //英語のテスト結果
examinationScores[0][0]; //出席番号１番の学生の情報のテスト結果
59var information = 0;
var english = 1;
examinationScores[information];
examinationScores[english];
examinationScores[information][0]; //
59var INFORMATION = 0;
var ENGLISH = 1;
examinationScores[INFORMATION];
examinationScores[ENGLISH];
examinationScores[INFORMATION][0]; //
59var examinationScores = {
    information : [
        59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
        36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
        68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
        57, 65, 81, 63, 45
],
english : [
    60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
    51, 51, 68, 68, 45, 64, 49, 60, 59, 55,
    52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
    50, 55, 63, 50, 50,
]};
examinationScores.information;  //
examinationScores.english;  //
(35) [60, 69, 56, 65, 61, 43, 65, 52, 59, 61, 51, 51, 68, 68, 45, 64, 49, 60, 59, 55, 52, 60, 59, 48, 56, 55, 67, 63, 54, 36, 50, 55, 63, 50, 50]】
】
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

【関数の事が少しわかった】

### 疑問・分からないこと（もしあれば）

【ここに書く（なければ省略可）】
