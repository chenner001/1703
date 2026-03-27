
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>下次回来我给你们摘星星</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #ffffff;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Roboto, "Noto Sans", sans-serif;
            color: #111;
            line-height: 1.6;
            padding: 2rem 1.5rem;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .story-container {
            max-width: 780px;
            width: 100%;
            margin: 0 auto;
        }

        .title {
            font-size: 2.2rem;
            font-weight: 500;
            margin-bottom: 2rem;
            text-align: center;
            letter-spacing: 1px;
            color: #111;
            line-height: 1.3;
        }

        .content {
            margin-bottom: 3rem;
        }

        p {
            margin-bottom: 1.2rem;
            text-align: justify;
            font-size: 1rem;
            color: #222;
        }

        .btn-container {
            display: flex;
            justify-content: center;
            margin-top: 2rem;
            margin-bottom: 1rem;
        }

        .enter-btn {
            background: transparent;
            border: 1px solid #111;
            color: #111;
            padding: 10px 32px;
            font-size: 1rem;
            font-weight: 500;
            border-radius: 40px;
            cursor: pointer;
            transition: all 0.2s ease;
            text-decoration: none;
            display: inline-block;
            font-family: inherit;
        }

        .enter-btn:hover {
            background: #f5f5f5;
            border-color: #555;
            transform: scale(0.98);
        }

        @media (max-width: 600px) {
            body {
                padding: 1.5rem;
            }
            .title {
                font-size: 1.6rem;
            }
            p {
                font-size: 0.92rem;
            }
            .enter-btn {
                padding: 8px 28px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
<div class="story-container">
    <div class="title">下次回来我给你们摘星星</div>
    <div class="content">
        <p>2025年3月18日，上午10:23</p>
        <p>深蓝科技的电话打到林慧芬手机上时，她正在阳台收衣服。</p>
        <p>“阿姨，我这里是晚晴的公司，晚晴离职了但还有些东西没收拾，电话也打不通，您能联系上她吗？”</p>
        <p>林慧芬放下衣服，拨了女儿的号码。关机。又拨。还是关机。</p>
        <p>她站在阳台上，三月的风吹过来，她忽然觉得有点冷。</p>
        <p>刑侦支队 · 上午10:40</p>
        <p>周远在接待室见到了林慧芬。她坐在椅子上，手里攥着一部老人机，屏幕还亮着——十几个未接电话，全是打给苏晚晴的。</p>
        <p>“最后一次联系是什么时候？”周远问。</p>
        <p>“3月17日，微信联系的。周警官，她不会出什么事吧？”</p>
        <p>“我们先去她住的地方看看。”</p>
        <p>时光里公寓 ，上午11:35</p>
        <p>物业调出了17日凌晨的监控。</p>
        <p>画面里，苏晚晴穿着米白色大衣，独自走进电梯。凌晨2:17，她走出电梯，消失在走廊尽头。</p>
        <p>1703室门外，门紧闭着。开锁师傅上前，锁芯转动的声音在走廊里格外清晰。</p>
        <p>周远转头看向门口的林慧芬。她没有哭，只是站在门槛外，一动不动。</p>
        <p>他深吸一口气。</p>
    </div>
    <div class="btn-container">
        <button id="enterRoomBtn" class="enter-btn">点击进入1703</button>
    </div>
</div>

<script>
    document.getElementById('enterRoomBtn').addEventListener('click', function() {
        window.open('1703终版.html', '_blank');
    });
</script>
</body>
</html>
