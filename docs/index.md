---
hide:
  - toc
---
# bert-vits2和vits对比合成效果展示
#### 以下测试文本均采用标日上册第19课课文，确保测试文本不在训练集内，保证对比的可靠性
#### 其中bert-vits2使用的最新发布版本2.1.0，微调跑了3万步，vits同样跑了3万步

|  角色(训练语料日语10分钟)   | 测试文本  |   vits合成语音   |   bert-vits2-合成语音 |
|:----------------------------:|:---------:|:----------------:|:---------------------:|
| 慧慧（为美好世界献上祝福） | その 品物に 触らないで ください。 请不要碰那个货物！| <audio controls><source src="./audio/huihui_1.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_1.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） | あっ,すみません。 啊，对不起。 | <audio controls><source src="./audio/huihui_7.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_7.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） | 李さん,いっしょに食事に行きませんか?  李小姐，一起去吃饭么？| <audio controls><source src="./audio/huihui_8.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_8.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） | すみません.今日は早く帰って,レポートをか書かなければなりません. 对不起。今天我得早点回去写报告。| <audio controls><source src="./audio/huihui_9.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_9.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） | 先生,もう薬を飲まなくてもいいですか?  大夫，可以不吃药了吗?| <audio controls><source src="./audio/huihui_10.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_10.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） |  水郷の町といえば「江南古鎮」がいちばんだ。江南とは長江下流の南岸,古鎮とは古い町の意味である。鳥鎮,周荘,西塘,同里,朱家角などを指し,城を持たない水上都市として,明から清の時代にかけて大きく発展した。| <audio controls><source src="./audio/huihui_11_vits.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/huihui_11_bert.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） |  運河に沿って続く古鎮の風景は,1年を通じてそれぞれに魅力があるが,初春の風景はひときわすばらしい。水郷ならではの景色と素朴な暮らしが見られる。| <audio controls><source src="./audio/huihui_12_vits.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/huihui_12_bert.wav" type="audio/mpeg"></audio> |