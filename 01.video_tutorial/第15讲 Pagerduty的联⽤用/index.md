


第⼗十五讲：Pagerduty的联⽤用


第15讲 内容

• pagerduty 注册新账号

• pagerduty 创建新的service

• pagerduty 报警信息的设置



• pagerduty 注册新账号 （免费试⽤14天）

https://signup.pagerduty.com/accounts/new

Sign up.


It’s completely free. No credit card required.


image

image

Your Full Name dami

Email

dami@sina.com image Mobile Phone (optional)

555-555-5555 image

Password

image

h ·

image

image

Organization Name admi

Site Address


image

https:// admi .pagerduty.com

You will log in at this address. Pick a name using only letters, numbers, and dashes.


By clicking ”Start Your Trial” below, you accept the Terms of Service.


川


[ Start Yoimageal


image


注册账号中的各种预设置 ⼀路跳过即可


image


我们新注册的pagerduty账号 默认14天的免费试⽤时间

期间对于接收报警的数量 是有⼀定限制的 不


image

• pagerduty 创建新的service


image


点击 配置中的 services选项


image


之后 我们来新建⼀个 service


image


image


之后 我们把 ⽣成的这个 new service ’s interation key 复制到 我

们grafana平台的 notification_channel中（12讲中 有讲过 如何 加载这个key）


就完成了 grafana+pagerduty的连接

• pagerduty 报警信息的设置


做好了 grafana+pagerduty的连接

最后 我们⾃然就需要 设置⼀下pagerduty给咱们⽤户 发送报警 信息


回到pagerduty的主页⾯后 找到 设置⾥的 users选项卡


image


image


image

点击这个


image


在这⾥ 我们给账号 设置⼀个 ⽤于接收报警的 三项设置信息


image


电话 / 短信 / 邮箱

之后 我们就可以正式开始使⽤了 另外 在企业中使⽤的时候

我们需要在这⾥ 把所有需要接受报警信息的 员⼯⼿机号 邮箱

地址 同时都设置上


这样⼀来 每⼀次发送报警 所有被加⼊的员⼯就都会收到了

第⼗五讲结束


image



image


image

