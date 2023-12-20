<!DOCTYPE html>
<html>
<head>
    <title>雇员成本分析</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 10px; /* 顶部和底部保留10px的内边距 */
            color: #333;
        }

        .container {
            font-family: 'Arial', sans-serif;
            color: #333;
            width: 100%;
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            min-height: 23vh; /* 设置最小高度为视口高度 */
            position: relative; /* 设置相对定位 */
            bottom: 0; /* 粘附在底部 */
            transition: min-height 0.5s ease; /* 添加min-height属性的动画效果 */
            border-radius: 12px;
        }

        h1 {
            color: #27ae60;
            text-align: center;
        }

        p {
            margin: 10px 0;
            color: #555;
        }

        input[type='number'] {
            width: 100%;
            padding: 10px;
            margin: 5px 0 20px 0;
            border: 1px solid #ddd;
            box-shadow: 0px 0px 5px #aaa;
            border-radius: 4px;
        }

        button {
            background-color: #27ae60;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            box-shadow: 0px 0px 5px #aaa;
        }

        button:hover {
            background-color: #2ecc71;
        }

        #result1, #result2, #result3, #finalResult {
            display: none;
            background-color: #fff;
            padding: 10px;
            margin-top: 10px;
            border-left: 3px solid #27ae60;
            box-shadow: 0px 0px 5px #aaa;
        }

        @media screen and (max-width: 600px) {
            .container {
                padding: 10px;
            }

            input[type='number'] {
                margin-bottom: 10px;
            }

            button {
                margin-top: 10px;
            }
        }
    </style>
</head>
<body>
<h1 class="标题">雇员成本分析</h1>
<div class="container">
    <p class="薪资">请输入雇员基础月薪：</p>
    <input type="number" id="inputNumber">
    <p class="VT">请输入交通费单次成本：</p>
    <input type="number" id="vtCost" value="0">
    <button class="分析按钮" onclick="analyzeNumber()">分析</button>
    <p id="result1"></p>
    <p id="result2"></p>
    <p id="result3"></p>
    <p id="finalResult"></p>
</div>

<script>
    function analyzeNumber() {
        var number = parseFloat(document.getElementById('inputNumber').value);
        var vtCostPerInstance = parseFloat(document.getElementById('vtCost').value);
        var result1 = 0;
        var result2 = 0;
        var vtCost = 0;

        // 计算社保
        if (number < 1320.0) {
            result2 = number * 0.075;
        } else if (number >= 1320.01 && number < 2571.29) {
            result2 = number * 0.09 - 19.8;
        } else if (number >= 2571.30 && number < 3856.94) {
            result2 = number * 0.12 - 96.94;
        } else {
            result2 = number * 0.14 - 174.08;
        }

        // 计算个人所得税
        var adjustedNumber = number - result2;
        if (adjustedNumber <= 2112.0) {
            result1 = adjustedNumber * 0;
        } else if (adjustedNumber >= 2112.01 && adjustedNumber < 2826.65) {
            result1 = adjustedNumber * 0.075 - 158.4;
        } else if (adjustedNumber >= 2826.66 && adjustedNumber < 3751.05) {
            result1 = adjustedNumber * 0.15 - 370.4;
        } else if (adjustedNumber >= 3751.06 && adjustedNumber < 4664.68) {
            result1 = adjustedNumber * 0.225 - 651.73;
        } else {
            result1 = adjustedNumber * 0.275 - 884.96;
        }

        // 计算雇员VT成本
        vtCost = vtCostPerInstance * 22 * 2;
        if (vtCost > number * 0.06) {
            vtCost = number * 0.06;
        }
        // 计算最终数值
        var finalResult = number - result1 - result2 - vtCost;

        // 修改容器的min-height属性，添加动画效果
        document.querySelector('.container').style.minHeight = '70vh';

        // 显示结果，逐条弹出并添加0.2秒延迟
        setTimeout(function () {
            document.getElementById('result1').innerText = "雇员的个人所得税为： " + result1.toFixed(3);
            document.getElementById('result1').style.display = 'block';
        }, 100); // 0.2秒延迟

        setTimeout(function () {
            document.getElementById('result2').innerText = "雇员需要缴纳社保为： " + result2.toFixed(3);
            document.getElementById('result2').style.display = 'block';
        }, 180); // 0.4秒延迟

        setTimeout(function () {
            document.getElementById('result3').innerText = "雇员交通费成本为： " + vtCost.toFixed(3);
            document.getElementById('result3').style.display = 'block';
        }, 270); // 0.6秒延迟

        setTimeout(function () {
            document.getElementById('finalResult').innerText = "雇员税后净工资为： " + finalResult.toFixed(3);
            document.getElementById('finalResult').style.display = 'block';
        }, 360); // 0.8秒延迟
    }
</script>
</body>
</html>
