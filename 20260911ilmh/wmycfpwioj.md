# 北京大学与上海交通大学：预测化疗反应的生物标志物！可评估卵巢癌疗效、治疗耐药

> 更新时间：2026-09-11 (UTC+8)

导读：卵巢癌(OC)是一种侵袭性妇科肿瘤，通常诊断为广泛转移和腹水。在此，我们描绘了OC生态系统的单细胞景观，包括五个肿瘤相关部位，包括网膜转移和恶性腹水。

近日，北京大学团队、上海交通大学团队联合其他国内学者在《Nature Cancer》上发表题为“Single-cell analyses implicate ascites in remodeling the ecosystems of primary and metastatic tumors in ovarian cancer”的研究论文。研究数据揭示了腹水富集记忆T细胞作为肿瘤浸润耗尽CD8+ T细胞和T辅助1样细胞池的潜在作用。此外，肿瘤富集的巨噬细胞更倾向于单核细胞来源的个体发生，而腹水中的巨噬细胞更多地来自胚胎起源。此外，研究鉴定了恶性腹水中的MAIT和树突状细胞，以及原发肿瘤中的两个内皮亚群作为铂基化疗反应的预测性生物标志物。总之，此研究提供了女性恶性腹水生态系统的全局视图，为其与肿瘤组织的联系提供了有价值的见解，并为卵巢癌疗效评估和治疗耐药的潜在标志物铺平了道路。

**研究背景**

 01

卵巢癌(OC)是一种异质性疾病，是最致命的妇科恶性肿瘤，占女性癌症死亡人数的5% 。OC是一种异质性疾病，由不同的组织学亚型、分子生物学和微环境特征组成，影响其治疗反应和临床结果。在所有OC类型中，高级别浆液性OC (high-grade serous OC, HGSOC)是最常见的组织学亚型，占OC患者的70%以上。一旦确诊，超过75%的HGSOC患者病情进展为晚期，且伴有广泛转移和腹水。据报道，由于网膜和腹膜循环的脂肪结构，卵巢癌倾向于转移到网膜。虽然化疗加贝伐单抗治疗延长了5年生存期，但总体获益仍然有限。此外，免疫检查点抑制剂等免疫疗法在临床试验中仅显示出10%的客观反应率，并且由于肿瘤浸润淋巴细胞(til)的比例和质量不同，OC亚型通常对免疫治疗表现出不同的反应。因此，有必要对肿瘤微环境(tumor microenvironment, TME)进行表征，其中包含多种在疾病进展和治疗反应中发挥重要作用的细胞成分。

单细胞mRNA测序(scRNA-seq)是表征多种恶性肿瘤中不同细胞群的细胞特征和动态关系的有力工具。例如，先前的原发性卵巢肿瘤单细胞图谱显示GZMK+ CD8+效应记忆(TEM) T细胞亚群是功能失调前的效应记忆细胞。此外，另一项OC研究定义了具有最大表达水平GZMK的干细胞样组织驻留记忆T细胞群体，这些细胞将发育为耗尽T (TEX)细胞;然而，由于以往研究中样本组织有限，这些记忆T细胞的来源尚不清楚。除了原发肿瘤外，网膜转移和恶性腹水在卵巢癌研究中同样重要。例如，腹水生态系统中癌症相关成纤维细胞分泌的白细胞介素(IL)-6可刺激恶性细胞中的JAK-STAT信号，导致预后不良和对化疗产生耐药性。但以往对OC腹水的单细胞分析主要集中在恶性细胞和其他CD45−细胞上，对OC腹水的免疫环境以及恶性腹水如何影响OC的免疫状态知之甚少。因此，需要一个涉及多部位组织的高分辨率细胞景观来表征不同OC部位的综合TME，特别是网膜转移和腹水。

在此，研究团队通过scRNA-seq，通过比较5个肿瘤相关部位的独特细胞组成，包括原发性卵巢肿瘤(Pri.OT)、网膜转移(Met.Ome)、腹水、盆腔淋巴结(PLN)和外周血(PB)，描绘了OC TME的全面景观。通过基于T细胞受体(TCR)的谱系追踪和轨迹推断，揭示了T细胞从腹水到肿瘤组织的潜在动态特征。研究团队描述了腹水和肿瘤组织中巨噬细胞的功能状态和个体发生，并强调了DES+间皮细胞是重编程OC腹水的重要免疫调节剂。此外，研究团队揭示了不同的细胞成分与铂基化疗的临床反应之间的关联，这可能作为治疗效果的指标。总之，研究团队的发现提供了对恶性腹水功能的见解，并将为指导其他治疗策略的发展提供重要的资源。

**研究过程**

 02

多位点scRNA-seq的高分辨率OC景观

为了阐明卵巢癌细胞组成的复杂性，研究人员利用scRNA-seq分析了PB、PLN、Pri、OT、匹配Met的未分类细胞和14例晚期OC患者的部分和恶性腹水。这些患者表现出五种不同的组织学亚型，对铂类化疗的反应不同。研究团队总共将223,363个高质量的单细胞编目为5个主要的细胞系，通过规范标记表达进行注释。

通过5个位点的scRNA序列分析晚期卵巢癌的景观

T细胞在OC中的动态关系

鉴于HGSOC是最常见的OC亚型，研究团队在随后的TME特定细胞区室分析中重点关注HGSOC。研究团队首先关注的是OC中T细胞群的内在特性和潜在功能。通过无监督聚类，确定了5个CD4+簇，5个CD8+簇和2个非常规簇。常规T细胞簇进一步分为初始(TN)，中枢记忆(TCM)，效应记忆(TEM)，效应(Teff)，调节性(Treg)， T辅助1 (TH1)-like和耗尽(TEX) T细胞簇，它们表现出不同的组织偏好模式。TN细胞(T01和T06)富含PB和PLN，保持静止状态。与先前的研究一致，大多数免疫抑制的FOXP3+ Treg (T03)细胞和HAVCR2+耗尽的CD8+细胞(T10)主要富集在两个肿瘤部位。流式细胞术分析还表明，肿瘤部位的Treg和PD-1+ T细胞比腹水中的比例更高，进一步证明肿瘤组织与恶性腹水相比具有更强的免疫抑制状态。此外，CXCL13+ TH1样细胞(T05)也富集于肿瘤部位，而CD4+ANXA1+ TCM (T02)和CX3CR1+ Teff细胞(T04和T09)主要见于血液和腹水。具体来说，研究人员发现了两个CD8+ TEM簇占据CD8+ T细胞的很大比例，其中T07 ANXA2+ TEM富集于肿瘤部位，T08 GZMK+ TEM富集于腹水。基于有限的差异表达基因，观察到肿瘤富集的ANXA2+ TEM细胞编码效应分子(如GNLY, GZMB和TNFSF10)的基因表达水平升高，表明肿瘤内TEM细胞固有的抗肿瘤效应潜力。相比之下，富含腹水的GZMK+ TEM细胞EOMES和TCF7的表达更高，这是祖细胞TEX细胞中的关键转录因子基因，这表明GZMK+ TEM细胞更有可能转运到TEX细胞。

HGSOC中T细胞簇的特征及CD8+ T细胞的动态

**研究成果**

 03

尽管使用了以铂为基础的化疗并改善了生存率，但大多数晚期OC患者由于化疗耐药性而复发。在此，研究人员将scRNA-seq应用于14例化疗敏感性不同的OC患者的5种组织类型，系统剖析TME的复杂性以及5种组织之间的联系。我们的分析显示，腹水衍生的GZMK+ TEM，类似于之前报道的肿瘤中“预耗尽”的CD8+ T细胞，可能是肿瘤浸润性TEX细胞的主要来源。这些发现表明，腹水来源的记忆T细胞可以迁移到肿瘤部位，作为TILs的另一个重要细胞库。据报道，预先耗尽的GZMK+ T亚群被认为是预先激活的T细胞，在基于免疫检查点的治疗后，会在反应性肺癌和黑色素瘤中积累。研究团队怀疑加速腹水来源的GZMK+ TEM细胞向肿瘤部位的迁移可能是一种潜在的治疗OC的策略。此外，研究人员确定腹水中MAIT细胞的比例作为化疗反应的潜在预测指标。因此，研究人员对腹水富集T细胞的研究启发我们重新思考恶性腹水在塑造肿瘤微环境中的功能。未来的研究将需要充分了解这些腹水T细胞的功能作用。

在此，研究人员发现cDC在OC中表现出特定的腹水富集分布模式。假设腹水中存在的cDC可能是肿瘤组织中LAMP3+ DC的潜在来源，正如在T细胞中发现的那样，这需要额外的体内谱系追踪验证。此外，研究表明巨噬细胞在肿瘤TME中具有高度异质性。研究人员发现不同来源和表型的巨噬细胞共存于卵巢肿瘤和腹水中，其中TeM在免疫调节中起作用，而AeM更具有促炎作用。据报道，肿瘤组织中的RTM在肺癌和卵巢肿瘤大网膜中提供了促瘤性生态位。数据还显示了富腹水RTM的肿瘤调节和单核细胞募集的潜在功能。

最终确定了在肿瘤进展中发挥重要作用的特定基质细胞群，如腹水中的DES+间皮细胞和肿瘤部位的IL13RA1+内皮细胞。研究结果表明，腹水富集的DES+ MCs可以通过CXCL12-CXCR4募集T细胞和巨噬细胞，帮助重塑腹水的微环境。趋化因子CXCL12已知由CAF表达，并与受体CXCR4结合，介导肿瘤中免疫细胞的募集。此外，IL13RA1+内皮细胞表现出参与血管生成的尖端样特征，并在铂耐药患者中显著富集。导航尖端细胞通常在血管发芽过程中起主导作用，这可能促进肿瘤的进展，并意味着更糟糕的预后。这些观察结果表明，IL13RA1+尖端样内皮细胞的丰度可能激活血管生成并进一步影响化疗耐药性。

总之，研究人员描绘了OC微环境的综合图谱，并揭示了腹水与两个肿瘤部位之间的联系。这些**工作为帮助重塑OC TME的生物学因素提供了额外的见解，并确定了特定的细胞亚群，这些细胞亚群可能作为化疗和长期生存预后标志物的潜在预测标志物，以及克服铂耐药和免疫抑制的新治疗靶点或策略。**

热门·直播/活动

 上海｜08月03日

▶ 2023细胞与基因治疗产品的GMP质量体系管理创新沙龙

 三亚｜08月10-11日

▶ 类器官和细胞产业高峰论坛

 上海｜10月20-22日

▶ 第五届上海国际癌症大会-临床转化篇

点击对应文字 查看详情

## 相关阅读

- [肾虚十大危害有哪些](https://github.com/jksx3jm2r0/parenting-daily-tips/blob/main/20260910arnc/kmihsfpbth.md)
- [国内做试管婴儿可以找朋友供-卵又供-精自怀吗？](https://github.com/aatdlcl043/kids-nutrition-notes/blob/main/20260911jbgi/dxtpqezijy.md)
- [有甲亢可以做三代试管吗？有家族性遗传病能做试管吗](https://github.com/h5z4rt20ta/baby-care-journal/blob/main/20260910urvx/rltzrbefja.md)
- [贵州三代试管包成功价格表，试管费用因人而异！](https://github.com/ddk2koak3u/mommy-baby-notes/blob/main/20260910rtyh/maiyhizait.md)
- [太原第三代试管代生子成功率高吗附费用明细](https://github.com/s4be62o8zt/child-care-essays/blob/main/20260910jqpt/yjfmmzripi.md)
- [男性输精管堵塞应该如何治疗？](https://github.com/w8h9bes5n2/newborn-parenting-log/blob/main/20260911hrun/xrjrknkibu.md)
- [格鲁吉亚试管婴儿一次成功价格多少(格鲁吉亚试管婴儿多少钱)](https://github.com/w4nejibsgs/pregnancy-care-hub/blob/main/20260910qzfv/rdbatoobjp.md)
- [东莞试管助孕机构服务流程，每一步都清晰可见](https://github.com/z4addypged/new-parent-notes/blob/main/20260911tqpy/gunercjace.md)
- [广州试管二代成功率高吗](https://github.com/na1l60kg9l/baby-growth-journal/blob/main/20260911eosr/vvnmxziryo.md)
- [心脏重症监护室：守护生命的战场](https://github.com/uvuw5du4om/baby-feeding-guide/blob/main/20260911hvmz/gjlqowdujr.md)
- [感冒会影响精子活力吗](https://github.com/vjd2jnnrxj/baby-care-essays/blob/main/20260911hmmm/jhkmhasdxl.md)
- [【微感动】《好战友，亲兄弟》，边防军人夫妻现场倾情演唱自创歌曲](https://github.com/fwqeo9xwuk/parenting-faq-hub/blob/main/20260911oxhb/dxvhoespel.md)
- [深圳医院多少钱三代试管婴儿？深圳医院怎么样三代试管婴儿？](https://github.com/s4vv96li6k/pregnancy-care-hub/blob/main/20260910tjjt/ygycpsjxlu.md)
- [孕妈球迷安度世界杯攻略](https://github.com/wgeyt0fbiv/maternal-care-journal/blob/main/20260911azxl/fepjlkogcw.md)

## 推荐站点

- [['https://www.mymydz.cn/115102914171.html', '48岁大龄女自然绝经两年做供卵试管对身体有影响吗？,50万包成功代孕男孩']](https://www.mymydz.cn/115102914171.html)
- [['https://www.hflrwzhs.cn/151.html', '2026落户新策：非婚生子女及同性伴侣子女上户口最新流程详解']](https://www.hflrwzhs.cn/151.html)
- [['https://www.zhangruiqing.cn/217141630573.html', '借卵价格']](https://www.zhangruiqing.cn/217141630573.html)
- [['https://www.chengyanghg.cn/334.html', '如何选择可靠供卵机构与试管技术指南']](https://www.chengyanghg.cn/334.html)
- [['https://www.sdxxy.cn/20250509-443.html', '宫颈粘连做代生高龄试管成功率高不，伊春不抛弃不放弃']](https://www.sdxxy.cn/20250509-443.html)
- [['https://www.monpun.com/6359707286059.html', '解析广州试管婴儿的费用明细及整体花费']](https://www.monpun.com/6359707286059.html)
- [['https://www.qumengru.com/229660548090.html', '如何提高精子质量？']](https://www.qumengru.com/229660548090.html)
- [['https://www.bjwdzxkj.cn/3674005658783.html', '代生费用详细表_代怀费用多少,试管婴儿移植一次具体费用，试管移植要多少钱一次']](https://www.bjwdzxkj.cn/3674005658783.html)
- [['https://www.xnnpbhdz.cn/28170151306951.html', None]](https://www.xnnpbhdz.cn/28170151306951.html)
- [['https://www.liangzimayi.com/2.html', '武汉不孕不育治疗多少钱？专业解读与温暖陪伴']](https://www.liangzimayi.com/2.html)
- [['https://www.syldezdhkj.cn/24810482644373.html', '湖南代生男孩靠谱机构成功率比较好的医院流程，2026好评助孕生子机构推荐']](https://www.syldezdhkj.cn/24810482644373.html)
- [['https://www.jszgyh.com/106424171010.html', '阴道炎症与试管受孕风险：感染原因探究']](https://www.jszgyh.com/106424171010.html)
- [['https://www.afa2019.com/127641115570.html', '2026年南京三代试管比较好的医院有哪几家？']](https://www.afa2019.com/127641115570.html)
- [['https://www.lianhuahushengqun.cn/111635921409.html', '代怀双胞胎：抑止子宫肌瘤的针多少钱一针？抑止子宫肌瘤的针剂']](https://www.lianhuahushengqun.cn/111635921409.html)
- [['https://www.wahuobao.com/14.html', '曲阜不孕不育难题的解决之道：试管代怀服务的探索']](https://www.wahuobao.com/14.html)
- [['https://www.sjzgwfjwzhs.cn/30056664937438.html', '组织学与胚胎学——卵泡红蓝铅笔画图,代孕试管公司']](https://www.sjzgwfjwzhs.cn/30056664937438.html)
- [['https://www.3899234.com/20250927-5.html', '代怀孕花费&东莞第三代试管贵不贵']](https://www.3899234.com/20250927-5.html)
- [['https://www.cheguangfu.cn/222.html', '拮抗剂方案是什么药？深度解析试管促排中的常用抑制剂']](https://www.cheguangfu.cn/222.html)
- [['https://www.apkbwvg.cn/danshenshiguanfangan/130.html', '第三代试管婴儿遗传病筛查适用人群详解']](https://www.apkbwvg.cn/danshenshiguanfangan/130.html)
- [['https://www.weywjei.cn/20250826-176.html', '同性群体的生育突围：辅助生殖如何帮助拉拉/基友通过科技拥有血缘后代']](https://www.weywjei.cn/20250826-176.html)
- [['https://www.xcktgpm.cn/20250823-174.html', '乐宝得与果纳芬促排效果差异及试管助孕医院选择指南']](https://www.xcktgpm.cn/20250823-174.html)
- [['https://www.ewdboe.cn/437080766570.html', '湖南借卵三代试管医院名单：辅助生殖助孕与男孩选择的考量']](https://www.ewdboe.cn/437080766570.html)
- [['https://www.haojiezhishi.cn/105.html', '试管婴儿反复失败怎么办(5AA囊胚移植着床*率是多少)']](https://www.haojiezhishi.cn/105.html)

*本文整理自母婴健康资讯，仅供科普参考。*
