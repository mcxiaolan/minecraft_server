<head>
<link rel="stylesheet" href="https://unpkg.com/@waline/client@v2/dist/waline.css" />
</head>

# 支持我们的项目 (捐赠)
感谢支持我们，请在付款时展示你的名字或留下备注，留在[捐赠名单](#捐赠名单)~

- [支付宝收款码](/assets/img/alipay.jpg)
- [微信赞赏码](/assets/img/wechat_reward_qrcode.png)

# 捐赠名单
感谢你们的支持，以下名单不分先后顺序。

| 昵称 | 金额 | 日期 |
|:--:|:--:|:--:|
|测试|14¥|2023/8/9|

# 讨论

<div id="waline"></div>
  <script type="module">
    import { init } from 'https://unpkg.com/@waline/client@v2/dist/waline.mjs';
    init({
      el: '#waline',
      serverURL: 'https://waline.ltya.top',
      pageview: false,
      locale: {
      placeholder: '请勿恶意发送评论，使用可收信的邮箱能获得回复哦~',
      requiredMeta: ['nick','mail']
    }
      emoji: ['https://emoji.shojo.cn/bili/src/小黄脸']
      search: false
      imageUploader: false
    });
  </script>