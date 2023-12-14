---
hide:
  - toc
---
####  都是跑了40万步的结果
####  训练时候，去掉了音频小于100条的说话人，大于100条音频的说话人，会被切割成多个100条音频的说话人
####  简单来说，就是每个说话人都是100条音频进行训练，目的是为了在微调时候，微调也是100条，可以保持训练和微调的一致，看看能不能带来效果的提升
|  角色  | 测试文本  |   原神  |   原神+xmla |
|:----------------------------:|:---------:|:----------------:|:---------------------:|
| 甘雨 | 如今听到许诺这么说，他心头一紧：“你喜欢他？”“其实我跟他更多的是亲情，”许诺说，“我们从小一块长大，知根知底，现在又是合伙人，如果非要找个人结婚的话，他是一个不错的选择。”李晏清差点脱口而出，我们也认识很久了，我也是一个不错的选择。但他理智还在，她跟他认识再久，也比不上与她青梅竹马的师兄。| <audio controls><source src="./audio/1.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/1_clean.wav" type="audio/mpeg"></audio> |
| 甘雨 | 望着测验魔石碑上面闪亮得甚至有些刺眼的五个大字，少年面无表情，唇角有着一抹自嘲，紧握的手掌，因为大力，而导致略微尖锐的指甲深深的刺进了掌心之中，带来一阵阵钻心的疼痛。| <audio controls><source src="./audio/2.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/2_clean.wav" type="audio/mpeg"></audio> |
| 甘雨 | 周围传来的不屑嘲笑以及惋惜轻叹，落在那如木桩待在原地的少年耳中，恍如一根根利刺狠狠的扎在心脏一般，让得少年呼吸微微急促。| <audio controls><source src="./audio/3.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/3_clean.wav" type="audio/mpeg"></audio> |
| 可莉 | 在那一片投射着被柳树枝叶切割而开的明亮光斑的空地中，数百道身影静静盘坐，这是一群略显青涩的少年少女，而此时，他们都是面目认真的微闭着双目，鼻息间的呼吸，呈现一种极有节奏之感，而随着呼吸的吐纳，他们的周身，仿佛是有着肉眼难辨的细微光芒出现。| <audio controls><source src="./audio/4.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/4_clean.wav" type="audio/mpeg"></audio> |
| 可莉| 石台下，一些少年突然悄悄的睁开眼睛，他们望着石台上那少年周身的光芒，皆是忍不住的舔舔嘴，脸庞上露出了一些羡慕钦佩之色，而后那股安静便是被他们的窃窃私语声开始打破。| <audio controls><source src="./audio/5.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/5_clean.wav" type="audio/mpeg"></audio> |
| 可莉 | 众多少年少女面面相觑，这事情在北灵院甚至整个北灵境也不算什么秘密，他们在对此感到遗憾的同时，又相当的好奇，他们很想知道，究竟是因为什么原因，这个出色得让同样有着几分傲气的他们都信服的牧哥，竟然会被那“灵路”主动的驱逐出来。| <audio controls><source src="./audio/6.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/6_clean.wav" type="audio/mpeg"></audio> |