# API_ML_AI_201909
## 项目名称：留忆电子毕业纪念册
## 所有人：陈淑铧


# 产品定位
本产品是一个为应届毕业生提供纪念校园生活和同学感情的平台。

# 价值宣言
本产品旨在通过运用人工智能的部分功能（图像识别、语音识别、自然语言处理、人脸识别）来实现更好的信息录入效果。

# 价值主张

**一句话** 用户可以和其他用户同时协作，编辑属于他们的毕业纪念册。

**一分钟** 用户出于对学校生活的不舍和怀念，通常都会使用拍照拍视频的方法把这些时光记录下来。当他们对某个班际或者某个群体有很深的感情时，一般都会选择使用一个专题去记录。而纪念册应运而生，在过去，人们通常都是使用纸质版的纪念册，有的是一整个本子订好的，只能一个人一个人地填写。有的是活页夹类型的，可以让不同的人同时填写。但是纸质版的纪念册缺少了照片的上传功能，即便是有也是要将照片冲洗出来，有可能尺寸还会不合适。当使用电子纪念册时，你可以任意上传你想要的照片和调整尺寸的大小。日后翻起来时，用户还可以通过人脸识别找出同学的身份信息，极大地方便了用户的使用。

# 用户痛点

- 针对性

目前市场上多数电子毕业纪念册是以视频为主，下载软件之后可能要求用户开通会员才能获得视频清晰度。再加上信息更新不及时，维护成本高；欣赏不方便，分享难上加难；而留忆电子毕业纪念册不仅仅有视频，还提供文字，照片等功能，在分享和保存上也会进一步加强和改进。

- 便捷性

留忆电子纪念册可以和身边的同学同时进行一个班级或者是团体的纪念册制作，协作的方式能让用户的需求被更好地满足。

# 用户需求

- 显性需求

1、对校园生活和同学之间趣事的记录

2、制作纪念册要尽可能地方便简单

3、识别出照片中的人是谁（通过人脸识别，图像识别实现）

4、语音留言可以转化为文字（通过录音文件识别、机器翻译实现）


- 隐形需求

1、不需要很高的花费


# 核心价值--最小完成项

- 自然语言处理-智能文本分类：完成根据资料对同学进行分类

- 语音合成：完成文字留言向语音留言的转变

# 本产品主要运用的AI功能如下

- [阿里云-图像识别-图像识别](https://ai.aliyun.com/image?spm=5176.233916.1243091.14.bc0d18f0674QKb)

- [阿里云-人脸识别-人脸识别](https://ai.aliyun.com/face?spm=5176.233916.1243091.13.bc0d18f0674QKb)

- [阿里云-智能语音交互-录音文件识别](https://ai.aliyun.com/nls/filetrans?spm=5176.233916.1243091.7.bc0d18f0674QKb)

- [阿里云-机器翻译-机器翻译](https://ai.aliyun.com/alimt?spm=5176.233916.1243091.47.bc0d18f0674QKb)


# 人工智能概率性
- 人脸识别

在用户使用这个功能的过程中，可能会出现表情相似的两个人识别错误的情况，这个犯错误的概率要控制在5%以内才能满足用户的基本需求。这种概率被用户接收的最低标准是在使用这个功能时连续出错的次数不能超过三次。能够超出用户预期的标准是用户挑了一个比较难识别的人脸进行人脸识别时，能够被准确识别出来。这些判断决定对产品研发的投入策略：产品研发时要考虑到人的五官，表情和情绪的差值范围，以免识别的错误率提高。

- 录音文件识别、机器翻译

用户使用录音文件识别的过程中，如果录入的人说话不清晰，或者是需要机器翻译成别的语言时会出错，这个容错率要在5%以内才能满足用户的基本需求。这种概率被用户接收的最低标准是在使用这个功能时翻译成文字和其他语言文字时的要注意内容是否符合。能够超出用户预期的标准是用户讲了一段很快的话或者是用方言输入时，能够被较为准确地翻译出来。这些判断决定对产品研发的投入策略：产品研发时要考虑到录入的语言和语速，降低产品识别的错误率。

# 产品架构
![产品架构图](https://gitee.com/NFUNM008/what/raw/master/%E7%BA%AA%E5%BF%B5%E5%86%8CAPP%E4%BA%A7%E5%93%81%E6%9E%B6%E6%9E%84.png)

# API调用展示
**人脸识别API调用展示**
![人脸识别API调用展示](cnblogs.com/jingsupo/archive/2018/11/23/10008593.html)

**录音文件识别和机器翻译API调用展示**
![录音文件识别和机器翻译API调用展示](https://gitee.com/NFUNM008/what/raw/master/%E5%BD%95%E9%9F%B3%E6%96%87%E4%BB%B6%E8%AF%86%E5%88%AB%E5%92%8C%E6%9C%BA%E5%99%A8%E7%BF%BB%E8%AF%91.png)


# API的使用价格
**图像识别**
![图像识别价格1](https://gitee.com/NFUNM008/what/raw/master/%E5%9B%BE%E5%83%8F%E8%AF%86%E5%88%AB%E4%BB%B7%E6%A0%BC1.png)
![图像识别价格2](https://gitee.com/NFUNM008/what/raw/master/%E5%9B%BE%E5%83%8F%E8%AF%86%E5%88%AB%E4%BB%B7%E6%A0%BC2.png)

**人脸识别**
![人脸识别价格](https://gitee.com/NFUNM008/what/raw/master/%E4%BA%BA%E8%84%B8%E8%AF%86%E5%88%AB%E4%BB%B7%E6%A0%BC.png)

**录音文件识别**
![录音文件识别价格1](https://gitee.com/NFUNM008/what/raw/master/%E5%BD%95%E9%9F%B3%E6%96%87%E4%BB%B6%E8%AF%86%E5%88%AB1.png)
![录音文件识别价格2](https://gitee.com/NFUNM008/what/raw/master/%E5%BD%95%E9%9F%B3%E6%96%87%E4%BB%B6%E8%AF%86%E5%88%AB2.png)

**机器翻译**
![机器翻译价格](https://gitee.com/NFUNM008/what/raw/master/%E6%9C%BA%E5%99%A8%E7%BF%BB%E8%AF%91%E4%BB%B7%E6%A0%BC.png)


# 目标用户
#### - 对制作电子纪念册有需求的应届毕业生

#### - 想要制作电子纪念册的非应届毕业生

#### - 给学生制作电子纪念册的老师

# 内容范围
#### 图片上传
用户可以通过一次多张上传所需要的图片，图片要求符合法律法规。

#### 个人资料填写
用户在编辑页填写自己的个人资料

#### 协作
可容纳50人同时编辑电子毕业纪念册

#### 留言
用户可选择文字留言或者是语音留言**使用了阿里云的录音文件识别、机器翻译人工智能API**

#### 人脸识别寻找好友
通过**阿里云的人脸识别**功能，快速找到在同一个电子纪念册中出现过这个用户的图片。

# 市场
目前市面上已有的电子毕业纪念册多以视频软件为主，且视频像素清晰度不高

# 运营

**前期推广**
通过线上线下投放广告，针对应届毕业生，特别是大学毕业生投放，让他们可以利用这个软件对自己身边的同学好友留一个纪念

**后期运营**
用户进入稳定期后，我们可以根据不同的时间点或者是节假日推出一些特定的纪念册模板或贴着，吸引用户继续使用我们的软件。

# 清单
**本产品所用到的AI功能Python代码如下：**

- [阿里云-图像识别-图像识别](https://help.aliyun.com/knowledge_detail/53540.html?spm=a2c4g.11186623.6.550.6a756fadvQL0EN)

- [阿里云-人脸识别-人脸识别](https://help.aliyun.com/document_detail/118565.html?spm=a2c4g.11186623.6.558.7a107798bQkDyu)

- [阿里云-智能语音交互-录音文件识别](https://help.aliyun.com/document_detail/94062.html?spm=a2c4g.11186623.6.588.29d82d95Npp0oB)

- [阿里云-机器翻译-机器翻译](https://ai.aliyun.com/alimt?spm=5176.233916.1243091.47.bc0d18f0674QKb)
