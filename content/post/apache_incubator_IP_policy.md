+++
author = "张伟玲 谭中意"
title = "Apache基金会项目孵化过程中知识产权转移的讨论"
date = "2020-07-24"
description = "ASF项目孵化流程对知识产权授权与转移有完备的定义，本文从公开发表的资料和文档，并结合亲身经历的项目捐献和孵化过程中总结"
tags = [
    "ASF项目孵化流程", "知识产权转移"
]
+++

# Apache软件基金会项目孵化过程中知识产权转移的讨论

+ 作者：张伟玲 谭中意
+ 审核：姜宁 张亮

###   作者简介：
*张伟玲，多年大型互联网知识产权法律经验，擅长商标、开源、著作权等知识产权法律领域的合规制度建设、 培训和诉讼支持，在互联网信息网络传播/合规/品牌等领域有丰富实战经验。*

## 讨论背景：
自2002年Apache Software Foundation（**ASF**）开始孵化项目以来，ASF至今已经毕业了200多个顶级项目。在这些项目中，无论是个人捐赠还是企业捐赠的，都必须严格遵守其孵化流程和政策要求。尤其是近几年来，越来越多的国人发起的开源项目进入Apache基金会孵化，并有不断的项目毕业，Apache开源基金会在国内的影响力越来越大。而它作为一个国际范围内host项目最多的开源基金会，它的各种政策和流程也越来越为更多人熟悉。

![apache projects](../images/apache_incubator_IP_policy/apache_incubator_ip_1.png)


而其中最重要的一个流程---项目孵化，在知识产权方面也有很独特的政策。那么，作为项目所有者的您，在面对这些政策和可能会遇到各种文件时，是否有过困惑“我签署了什么？项目的知识产权还是我的吗？或者说我还剩些什么权利呢？…”，为了解决这些困惑，本文会对您可能遇到的问题进行初步讨论分析，当然本人是从公开发表的资料和文档，并结合亲身经历的项目捐献和孵化过程中总结，也有些认识不到位的地方，请多多讨论，有问题可跟本人微信号**weiweizhang0410**讨论，thanks

## 先说结论：
总的来说，捐献项目给Apache基金会，Apache基金会需要您的“版权授权 + 专利授权 + 商标转让”。

知识产权即人们常说的IP（Intellectual Property）,跟开源软件相关的主要有如下三项：版权（即Copyright），专利（即Patent），商标（即Trademark ）。根据Apache基金会的IP政策，个人或者公司捐献项目给它，该项目的专利和版权必须授权给它，商标必须要转让给它。

即它既要商标的所有权（owner），又要专利的使用授权，还要版权的使用授权。


## 具体解释：
开源项目要进入Apache基金会进行孵化，原有版权所有人必须要签署如下两个文件，一个是SGA（Software Grant Agreement），另外一个是CCLA/ICLA（公司或者个人贡献协议ICLA: Individual Contributor License Agreement，CCLA: Corporate Contributor License Agreement）。我们一起来看看这两个文件的内容。

先看看SGA（Software Grant Agreement），以下是协议原文信息：
![Apache SGA](../images/apache_incubator_IP_policy/apache_incubator_IP_2.png)

下面我们来仔细看下这篇文档的重点部分。

*“WHEREAS, Licensor owns or has sufficient rights to contribute the software source code and other related intellectual property as itemized on Exhibit A ("Software") under the terms of this agreement to the Foundation for use within Foundation software development projects ("Projects").*

首先，实务操作中需要签署人必须有足够的授权来贡献代码和相关的IP。默认规则下该签署人至少是该公司高级总监以上的职位。

然后看关键的部分：
***“Subject to the terms and conditions of this License, Licensor hereby grants to the Foundation:***

 ***a) a non-exclusive, worldwide, royalty-free, irrevocable
 copyright license to reproduce, prepare derivative works of,
 publicly display, publicly perform, distribute and sublicense,
 internally and externally, the Software and such derivative
 works, in source code and object code form; and***

 ***b) a non-exclusive, worldwide, royalty-free, irrevocable
 patent license under Licensed Patents to make, use, sell,
 offer to sell, import and otherwise transfer the Software
 in source code and object code form. "Licensed Patents" mean
 patent claims owned by Licensor which are necessarily
 infringed by the use or sale of the Software alone.***


许可人授予基金会如下权利:
- a） 以源代码和目标代码的形式在全球范围内复制、准备衍生作品、公开展示、公开表演、分发和再授权软件及其衍生作品的非排他性、免版税、不可撤销的版权许可；以及，
- b） 非排他性的、全球范围内的、免版税的、不可撤销的专利许可证，根据许可专利以源代码和目标代码的形式获得、使用、销售、许诺销售、进口和以其他方式转让该软件。”


我们再看下CCLA（Corporate Contributor License Agreement），原文相对较长，截取原文知识产权重点部分：

![Apache CLA1](../images/apache_incubator_IP_policy/apache_incubator_IP_3.png)
![Apache CLA2](../images/apache_incubator_IP_policy/apache_incubator_ip_4.png)

简单摘要如下：

*“感谢您对Apache软件基金会（“基金会”）的关注。为了阐明由任何个人或实体提供的贡献所授予的知识产权许可，基金会须具有由每个贡献者签署的“贡献者许可协议”（CLA），以表明同意以下许可条款。该许可证是为了保护您作为贡献者，以及保护基金会及其用户；它不会改变您将自己的贡献用于任何其他目的的权利。*
。。。。

   2.授予版权许可。在遵守本协议前提下，授予接收者永久的，全球的，非独占的，免费的，免版税，不可撤销的版权许可，以复制、公开展示、公开表演，再许可、分发您的作品以及此类的衍生作品。

   3.授予专利许可。在遵守本协议前提下，授予接收者永久的，全球的，非独占的，免费的，免版税，不可撤销的专利许可（本节所述除外）获得、使用，销售，许诺销售，进口和以其他方式转让作品。。。

综上所述，作为项目协议来说，这份两份许可是较简短的，但是从其内容来看却已经足以明晰ASF的需求和项目所有者的义务：
项目所有者作为软件权利人，需要授予ASF两项权利，即：版权和专利权。
也就是说在这个阶段，ASF所需要的是您的版权和专利的授权，是在全球范围的ASF可以免费复制、分发、再授权等的权利。

根据ASF孵化政策，项目毕业前需转让项目商标，该审核一般由ASF品牌管理负责部门进行审批，在该阶段审批，一般是出于若毕业后再更名，会需要来自技术团队的大量支持，因此，从ASF角度会要求尽早提起商标的转让审核。

经过上述初步分析来看，无论是签署的协议文件，还是孵化过程中的商标转让义务，ASF未要求项目所有者对于版权和专利的所有权的转让，作为项目所有者需要承担的义务主要为：版权授权 + 专利授权 + 商标转让。


##  发版说明：
可能有的同学要问，既然捐献过程中没有发生版权的转移，但是为什么Apache毕业项目的Copyright Owner都是Apache Foundation呢，例如看apache kafka（这是linkedin捐献给Apache基金会的项目），每个源码文件的license header都指向Notice文件。https://github.com/apache/kafka/blob/trunk/NOTICE

  	Apache Kafka
    Copyright 2020 The Apache Software Foundation.

	This product includes software developed at
	The Apache Software Foundation (https://www.apache.org/).

再看apache beam项目（这是google捐献给apache基金会的项目），每个源码文件的license header都指向notice文件，
https://github.com/apache/beam/blob/master/NOTICE
文件内容如下：

	Apache Beam
    Copyright 2016-2018 The Apache Software Foundation

	This product includes software developed at
	The Apache Software Foundation (http://www.apache.org/).

那是因为按照Apache基金会发版的要求，每个项目在发布软件版本的时候，是需要把源码中的每个文件的头部都加上Apache基金会指定的License Header，而这个License Header的内容统一指向该项目的NOTICE文件。（当然如果包含了其他第三方开源代码，需要按照该开源项目许可证的要求，在Header上保留源作者的版权申明的，详见https://www.apache.org/legal/src-headers.html#3party。）

    /*
     * Licensed to the Apache Software Foundation (ASF) under one or more
	 * contributor license agreements. See the NOTICE file distributed with
	 * this work for additional information regarding copyright ownership.
	 * The ASF licenses this file to You under the Apache License, Version 2.0
	 * (the "License"); you may not use this file except in compliance with
	 * the License. You may obtain a copy of the License at
	 *
	 *    http://www.apache.org/licenses/LICENSE-2.0

	 *
	 * Unless required by applicable law or agreed to in writing, software
	 * distributed under the License is distributed on an "AS IS" BASIS,
	 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	 * See the License for the specific language governing permissions and
	 * limitations under the License.
	 */

而该NOTICE文件一般内容都是指明当前的Copyright Owner是Apache基金会。但是在该NOTICE文件中，是可以保留一些之前版本的Copyright Owner的声明的。
例如Netbeans这个项目，它最早的Owner是Sun Microsystem，之后Sun被Oracle收购后，Copyright Owner变成Oracle，而之后Oracle把这个项目捐献给Apache基金会。为了保护各个Owner的知识产权，把各个时期的Copyright Owner都列了出来，所以现在的内容https://github.com/apache/netbeans/blob/master/NOTICE如下：

	Apache Netbeans
    Copyright 2017-2020 The Apache Software Foundation

	This product includes software developed at
	The Apache Software Foundation (http://www.apache.org/).

	The code is based on NetBeans, that has been kindly donated to the Apache
	Software Foundation by Oracle.

	The code was Copyright 1997-2016 Oracle and/or its affiliates.  The Initial
	Developer of the Original Software was Sun Microsystems, Inc. Portions
	Copyright 1997-2006 Sun Microsystems, Inc.

从上面的文件中能看出，该文件的Copyright 按照时间列出了前后几个，1997-2006 为Sun Microsystems，1997-2016 为Oracle，2017-2020为Apache foundation。

我们追溯ASF在2004年的董事会记录 发现，上述操作是基金会为了解决“用户在向ASF提供授权时，ASF文件中版权声明却归他人持有人时的不一致情况”，根据董事会方案：
“版权者的首选处理方式是删除此类声明，或将其放在单独的位置归档，以包含在每个项目的COPYRIGHT文件中，或在贡献中包含基金会的书面许可，以进行通知的删除或重新安置；被许可给ASF的文件应有版权声明，并进行适当修改，以反映贡献年份和原始发行的任何后续年份。”

因此，作为项目所有人的版权信息，有的会在NOTICE部分予以体现。但是Apache的发版和毕业政策都会约定最新版本的Copyright Owner声明是Apache基金会，虽然可以保留之前版本的Copyright说明。只有统一被授权方均为Apache基金会，该软件的用户基于对Apache基金会的品牌和信心，才会持续在该项目上进行投入，不担心出现该软件的主导公司未来的某一天把该软件闭源的情况。因为即使出现该软件主导方不再继续投入，或者另起炉灶的情况，Apache的知识产权制度保证了还有社区的其他人在继续维护。而该软件最新版本的Copyright Owner是Apache基金会，则在法律上减少了该社区在继续维护上的知识产权纠纷。

这是Apache开源基金会精心的知识产权政策的设计，为了保证它旗下的项目是一个可信赖的产品，因为知识产权问题已经理清，持续维护的问题也已经解决，所以Apache的项目才会如此受到欢迎，所以才会有更多的公司或者个人把项目捐献给Apache基金会。


## 总结：
综合上面的说明来看，当有新的项目需要经ASF孵化毕业，作为项目所有人需要承担的义务主要在于版权授权、专利授权和商标转让，版权原始权利并未转让，因此，在项目的实际操作中请记得根据ASF的官方格式保留自己的权利声明。
本文主要是基于实践操作和ASF官方规定作出的一些讨论，在您具体项目确定孵化或捐赠之前，请一定与您的律师进行个案的综合评估以保障您的权益哦。当然也欢迎微信联系跟本人共同沟通讨论。

### 参考资料：
+ ASF Contributor agreement http://www.apache.org/licenses/contributor-agreements.html
+ ASF SGA template http://www.apache.org/licenses/software-grant-template.pdf
+ ASF CCLA http://www.apache.org/licenses/cla-corporate.pdf
+ Apache 文件头说明 https://www.apache.org/legal/src-headers.html
+ ASF 2004 Board meeting 记录 https://www.apache.org/foundation/records/minutes/2004/board_minutes_2004_11_14.txt
