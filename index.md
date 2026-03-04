<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>专注空间 - Energy station</title>
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

        /* 标题样式 */
        h1 {
            color: #333;
            font-size: 2.5rem;
            margin-bottom: 30px;
            text-align: center;
        }

        /* 按钮容器 */
        .button-container {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }

        /* 功能按钮样式 */
        .func-btn {
            padding: 15px 30px;
            font-size: 1.2rem;
            border: none;
            border-radius: 8px;
            background-color: #409eff;
            color: white;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .func-btn:hover {
            background-color: #66b1ff;
            transform: scale(1.05);
        }

        .func-btn:active {
            transform: scale(0.98);
        }

        /* 响应式适配 */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            .func-btn {
                padding: 12px 24px;
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <h1>Zi-chu</h1>
    <div class="button-container">
        <button class="func-btn" onclick="alert('专注模式已开启！')">专注模式</button>
        <button class="func-btn" onclick="alert('休息模式已开启！')">休息模式</button>
        <button class="func-btn" onclick="alert('音乐模式已开启！')">音乐模式</button>
    </div>
</body>
</html>

