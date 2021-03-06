# CMT

## Video Background Music Generation with Controllable Music Transformer

在本工作中，作者解决了视频背景音乐生成的任务。以往的一些作品虽然实现了有效的音乐生成，但却无法针对特定的视频生成优美的音乐，也没有考虑到视频音乐的节奏一致性。为了生成与给定视频匹配的背景音乐，首先建立视频和背景音乐之间的节奏关系。特别地，将视频中的定时、动作速度和动作显著性分别与音乐中的节拍、模拟音符密度和模拟音符强度联系起来。然后提出CMT，一个可控的音乐转换器，使上述节奏特征的局部控制，以及音乐类型和用户指定的使用乐器的全局控制。客观和主观的评价表明，生成的背景音乐与输入视频达到了满意的兼容性，同时音乐质量令人印象深刻。

paper is here:
  > https://dl.acm.org/doi/pdf/10.1145/3474085.3475195
