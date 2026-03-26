
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>白色极简 · 摘星星</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #ffffff;
            font-family: system-ui, -apple-system, 'Segoe UI', 'Roboto', 'Helvetica Neue', Helvetica, 'Noto Sans', sans-serif;
            color: #111111;
            line-height: 1.5;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 3rem 1.5rem;
        }

        /* 极简容器，最大宽度保证阅读舒适 */
        .story-container {
            max-width: 720px;
            width: 100%;
            margin: 0 auto;
        }

        /* 抬头区域：加大加粗 */
        .hero-title {
            margin-bottom: 2.2rem;
            text-align: left;
            border-bottom: 1px solid #efefef;
            padding-bottom: 1.2rem;
        }

        .hero-title .quote-large {
            font-size: 2.4rem;      /* 加大 */
            font-weight: 800;        /* 加粗 */
            letter-spacing: -0.01em;
            color: #000000;
            line-height: 1.2;
            font-style: normal;
        }

        /* 日期区块：日期字体加粗 */
        .datetime-block {
            margin-bottom: 2rem;
            text-align: left;
        }

        .main-date {
            font-size: 1.4rem;      /* 日期字体适中但加粗 */
            font-weight: 700;        /* 加粗 */
            color: #1a1a1a;
            line-height: 1.3;
            letter-spacing: -0.2px;
        }

        /* 叙事文本：干净，清晰留白 */
        .story-text {
            font-size: 1.05rem;
            color: #2c2c2c;
            margin-bottom: 3rem;
            white-space: pre-line;
        }

        .story-text p {
            margin-bottom: 1.25rem;
        }

        /* 文中粗体强调（如时间地点）保留原有样式但更克制 */
        .story-text strong {
            font-weight: 600;
            color: #000000;
        }

        /* 按钮容器：居中 */
        .button-wrapper {
            display: flex;
            justify-content: center;
            margin-top: 1rem;
            margin-bottom: 1rem;
        }

        .enter-button {
            display: inline-block;
            background-color: #ffffff;
            border: 1px solid #1f1f1f;
            padding: 0.85rem 2.4rem;
            font-size: 1rem;
            font-weight: 500;
            font-family: inherit;
            color: #1f1f1f;
            text-decoration: none;
            border-radius: 40px;
            transition: all 0.2s ease;
            cursor: pointer;
            text-align: center;
            letter-spacing: 0.3px;
            background: #fff;
        }

        .enter-button:hover {
            background-color: #f5f5f5;
            border-color: #000000;
            color: #000;
        }

        .enter-button:active {
            transform: scale(0.97);
        }

        /* 手机端适配：抬头略微缩小但仍保持加大加粗观感 */
        @media (max-width: 550px) {
            body {
                padding: 2rem 1.2rem;
            }
            .hero-title .quote-large {
                font-size: 1.9rem;
            }
            .main-date {
                font-size: 1.2rem;
            }
            .story-text {
                font-size: 1rem;
            }
            .enter-button {
                padding: 0.7rem 1.8rem;
                font-size: 0.95rem;
            }
        }

        /* 极简脚注仅用于平衡，不影响主体 */
        .air-footer {
            text-align: center;
            font-size: 0.7rem;
            color: #d4d4d4;
            margin-top: 2.5rem;
            letter-spacing: 0.3px;
        }
        a {
            text-decoration: none;
        }
    </style>
</head>
<body>
<div class="story-container">
    <!-- 抬头：【下次回来我帮你们摘星星】加大 + 加粗 -->
    <div class="hero-title">
        <div class="quote-large">下次回来我帮你们摘星星</div>
    </div>

    <!-- 日期：2025年3月18日，上午10:23，字体加粗 -->
    <div class="datetime-block">
        <div class="main-date">2025年3月18日，上午10:23</div>
    </div>

    <!-- 正文内容完全按照用户提供，保留所有段落与换行 -->
    <div class="story-text">
        <p>深蓝科技的电话打到林慧芬手机上时，她正在阳台收衣服。</p>
        <p>“阿姨，晚晴今天没来开会，电话也打不通，您能联系上她吗？”</p>
        <p>林慧芬放下衣服，拨了女儿的号码。关机。又拨。还是关机。</p>
        <p>她站在阳台上，三月的风吹过来，她忽然觉得有点冷。</p>
        <p><strong>刑侦支队 · 上午10:40</strong></p>
        <p>周远在接待室见到了林慧芬。她坐在椅子上，手里攥着一部老人机，屏幕还亮着——十几个未接电话，全是打给苏晚晴的。</p>
        <p>“最后一次联系是什么时候？”周远问。</p>
        <p>“3月17日，微信联系的。周警官，她不会出什么事吧？”</p>
        <p>“我们先去她住的地方看看。”</p>
        <p><strong>时光里公寓 ，上午11:35</strong></p>
        <p>物业调出了17日凌晨的监控。</p>
        <p>画面里，苏晚晴穿着米白色大衣，独自走进电梯。凌晨2:17，她走出电梯，消失在走廊尽头。</p>
        <p>1703室门外，门紧闭着。开锁师傅上前，锁芯转动的声音在走廊里格外清晰。</p>
        <p>周远转头看向门口的林慧芬。她没有哭，只是站在门槛外，一动不动。</p>
        <p>他深吸一口气。</p>
    </div>

    <!-- 底部居中按钮：点击进入1703 跳转到 https://github.com/chenner001/1703/blob/main/1703%E5%AE%A4.html -->
    <div class="button-wrapper">
        <a href="https://github.com/chenner001/1703/blob/main/1703%E5%AE%A4.html" class="enter-button" target="_blank" rel="noopener noreferrer">点击进入1703</a>
    </div>
</div>
<!-- 极简留白脚注，不干扰主要内容 -->
<div class="air-footer"></div>
</body>
</html>
