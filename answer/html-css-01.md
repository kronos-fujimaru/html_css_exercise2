### 解答例

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>HTML-CSS課題</title>
</head>
<body>
    <h1>計算プログラム</h1>
    <hr>
    <table>
        <tr>
            <td><input type="number" name="num1">&emsp;</td>
            <td width="50">
                <input type="radio" name="symbol" value="1" checked>＋<br>
                <input type="radio" name="symbol" value="2">ー<br>
                <input type="radio" name="symbol" value="3">×<br>
                <input type="radio" name="symbol" value="4">÷
            </td>
            <td><input type="number" name="num2"></td>
            <td>&emsp;<input type="submit" value="計算"></td>
        </tr>
    </table>
    <p><label>結果：</label><input type="text"></p>
</body>
<html>
```
