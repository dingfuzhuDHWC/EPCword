<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>漫画导航站</title>
    <style>
        /* 全局样式重置 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft YaHei", sans-serif;
        }

        /* 页面主体样式 */
        body {
            background-color: #f5f5f5;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* 大标题样式 */
        .main-title {
            font-size: 48px;
            font-weight: bold;
            color: #000;
            margin-bottom: 50px;
            text-align: center;
        }

        /* 按钮容器 */
        .button-container {
            display: grid;
            /* 自适应列数：最小100px一列，最多自动分配 */
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 15px;
            width: 100%;
            max-width: 1200px;
        }

        /* 字母按钮样式 */
        .letter-btn {
            padding: 20px;
            font-size: 24px;
            font-weight: 600;
            background-color: #2c3e50;
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        /* 鼠标悬浮效果 */
        .letter-btn:hover {
            background-color: #34495e;
            transform: scale(1.05);
        }

        /* 点击效果 */
        .letter-btn:active {
            transform: scale(0.98);
        }
    </style>
</head>
<body>
    <!-- 大标题 -->
    <h1 class="main-title">漫画导航</h1>

    <!-- 字母按钮容器 -->
    <div class="button-container">
        <!-- A-Z 按钮，每个按钮跳转到对应的 Qx.html 页面 -->
        <button class="letter-btn" onclick="window.location.href='Qa.html'">A</button>
        <button class="letter-btn" onclick="window.location.href='Qb.html'">B</button>
        <button class="letter-btn" onclick="window.location.href='Qc.html'">C</button>
        <button class="letter-btn" onclick="window.location.href='Qd.html'">D</button>
        <button class="letter-btn" onclick="window.location.href='Qe.html'">E</button>
        <button class="letter-btn" onclick="window.location.href='Qf.html'">F</button>
        <button class="letter-btn" onclick="window.location.href='Qg.html'">G</button>
        <button class="letter-btn" onclick="window.location.href='Qh.html'">H</button>
        <button class="letter-btn" onclick="window.location.href='Qi.html'">I</button>
        <button class="letter-btn" onclick="window.location.href='Qj.html'">J</button>
        <button class="letter-btn" onclick="window.location.href='Qk.html'">K</button>
        <button class="letter-btn" onclick="window.location.href='Ql.html'">L</button>
        <button class="letter-btn" onclick="window.location.href='Qm.html'">M</button>
        <button class="letter-btn" onclick="window.location.href='Qn.html'">N</button>
        <button class="letter-btn" onclick="window.location.href='Qo.html'">O</button>
        <button class="letter-btn" onclick="window.location.href='Qp.html'">P</button>
        <button class="letter-btn" onclick="window.location.href='Qq.html'">Q</button>
        <button class="letter-btn" onclick="window.location.href='Qr.html'">R</button>
        <button class="letter-btn" onclick="window.location.href='Qs.html'">S</button>
        <button class="letter-btn" onclick="window.location.href='Qt.html'">T</button>
        <button class="letter-btn" onclick="window.location.href='Qu.html'">U</button>
        <button class="letter-btn" onclick="window.location.href='Qv.html'">V</button>
        <button class="letter-btn" onclick="window.location.href='Qw.html'">W</button>
        <button class="letter-btn" onclick="window.location.href='Qx.html'">X</button>
        <button class="letter-btn" onclick="window.location.href='Qy.html'">Y</button>
        <button class="letter-btn" onclick="window.location.href='Qz.html'">Z</button>
    </div>
</body>
</html>
