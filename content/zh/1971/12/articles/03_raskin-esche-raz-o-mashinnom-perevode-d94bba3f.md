---
id: 1971-12-raskin-esche-raz-o-mashinnom-perevode-d94bba3f
issue: kvant_1971_12
year: 1971
number: "12"
title: 再次关于机器翻译
authors:
  - Раскин В. В.
rubric: osnovnye-stati
page_first: 13
page_last: 17
page_labels: 11, 12, 13, 15
tag: CX3N
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 02c2b769c3915606b290b45d78b72a3c2edceeb85f3460f810da1fd0f98caa3b
prompt_sha256: draft-1
translated_from: content/ru/1971/12/articles/03_raskin-esche-raz-o-mashinnom-perevode-d94bba3f.md
source_content_sha256: 58775ade445f3e1a2048656f0904d9079c115d578cfc5e185854d7868e433b8d
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

再次关于机器翻译

我们已经写过关于机器翻译过程中出现的困难*)。由于他们的狡猾努力，机器总体上已经学会了应对其中的大多数。

然而，还有一个目标是将城市“置于”更严重的困难之中，我们在本文中对此进行了讨论。而它们都与神秘的“语义”一词有关。

语义学——研究词语意义的科学

第一个语义困难是同一个词可以表示不同的事物，并且在不同的语言中以不同的方式表示：赋予词的不同含义并不重合。俄语单词“table”最常需要翻译成英语“table”，但有时它的意思是“食物”（“food”），反过来英语“table”有时也应该翻译成俄语单词“table”。
此外，在所有语言中都存在所谓的同音异义词 - 拼写相同但含义不同的单词：
“把弓给我！” - 为了什么 - 为了射击还是为了喝汤？
此外，在不同的语言中，词语被赋予了不同的情感负载，并且具有不同的枚举意义使用能力。在俄语和许多其他欧洲语言中，“心”一词的意思是“orran”，大众意识认为它是主要的东西，并赋予感觉和体验的能力。
但在卡巴拉卡语（西非）中，这一功能是由“肝脏”一词执行的；在 Jejonob 语言（危地马拉玛雅语言的一种）中，表示腹腔的词就是在这个意义上使用的。想象一下

*) 参见«Kvant»第9号，1971年

⟦folio 12⟧

机器将卡巴拉语言翻译成俄语，并给出以下短语：“她的肝脏很好。”
下一个麻烦。在不同的语言中，赋予给定单词的“含义量”并不相同。我们以“兄弟”和“姐妹”的概念为例，将它们与“长辈”和“晚辈”的概念进行比较，我们得到下表：

| 概念 | 匈牙利 | 俄语 | 马来语 |
| :--- | :--- | :--- | :--- |
| 哥哥 | batya | 布拉姆 | sudara |
| 弟弟 | occs | | |
| 姐姐 | néne | sesstra | |
| 妹妹 | húg | | |

匈牙利语用一个单独的词表达这四个概念中的每一个，俄语一次“清理”这两个概念，马来语用一个词涵盖所有概念。将这些单词从匈牙利语翻译成马来语很容易，并且通常按照表格的单词方向向右。相反，如果您需要将马来语“sudara”一词翻译成匈牙利语怎么办？人工翻译将查看此处的上下文，并尝试找出该单词指定的人的性别和年龄，然后选择所需的匈牙利语对应词。但如何向机器教授这种困难的操作呢？

对于所有语言来说看似“相同”的单词（例如人称代词）可能具有“不寻常”的含义，从而使翻译变得困难。你现在就会看到这个。

任务1.哈努诺语（菲律宾语言之一）中有以下代词（并且只有它们）：

dah - 他们 tah - 我和我们
kuh - I tam - 我们（包括我）
mih - 我们（没有我） yah - 他，她
嗯 - 我们你 - 你

这些代词应根据其含义按照什么标准进行分类？俄语代词根据以下标准进行分类：数（该特征有两种含义：单数和复数）、性别（三种含义：阳性、阴性和中性）、pitso（三种含义）。

这些特征的系统不适合对哈努诺语的代词进行分类，因为给定的代词彼此没有区别（俄语“he”和“she”对应相同的代词“yah”）；至于人称和数字，哈努诺语比俄语捕捉到更多微妙的差异（例如，与一个俄语代词一起，第一人称复数有三个）。

在这种情况下，可以找到更适合分类的特征，满足给定代词的所有语义差异。

给定和e。选择这样的语义特征（并且它们的数量应该最少，并且每个特征恰好有两个含义），以便给定的代词代表所有可能的含义组合，并且不会重复任何两个组合。

⟦folio 13⟧

但这还不是全部。每种语言都有稳定的短语，这些短语并不完全代表组成它们的单词的单独含义，甚至根本不代表什么意思。这些就是所谓的措辞单位：“击败巴克利什”、“不要三思而后行”、“装傻”等等。

让我们想象一下，我们已经教会机器克服上述所有困难。我们来看一个英语短语：

«The President said that the article was red herring».
Happy, we are waiting for the translation.我们得到：

“总统说斯塔米亚是转移注意力的人。”
嗯……明白了吗？不好。但是询问任何翻译，他们会立即消除你的困惑，因为这句话实际上翻译成这样：
“总统说这个故事是鸭子（谎言，胡言乱语）。”
Immediately everything fell into place.因此，我们向机器添加了另一条规则（其中已经写了多少？！）：用“鸭子”一词替换短语“红鲱鱼”（甚至更好，因为鸭子不仅是报纸，而且是油炸的 - “谎言”或“废话”）。但措辞很多，真的可以每个字都写吗？
但懂得该语言的人可以轻松简单地翻译！

为了克服这些和其他语义（而不仅仅是语义）困难，为了正确选择目标语言中的等效单词，即为了执行翻译，机器必须记住单词的含义。美国语言学家 V. Yngve 是机器翻译领域最著名的专家之一，他写道：

“机器翻译工作遇到了语义障碍。我们必须意识到，只有当机器能够“理解”它所翻译的内容时，我们才能获得有针对性的自动翻译，这是一项非常艰巨的任务。”
为了让机器理解它正在翻译的内容，语言学家必须向它提供有关单词含义的信息，给出准确的、格式化的、清晰的语义记录，机器可以像字典和处理规则一样处理这些信息。现在的机器翻译需要语言学来记录这一点。但是……语言学家还不能为此哭泣。

正式研究语义复数的有趣尝试之一。 In this case, the approach is to highlight the so-called semantic plurals, that the meaning of each word is a combination of them (similar to how a natural number is decomposed into simple factors or a vector is specified by its coordinates).下面的问题说明了这个想法。

问题2.给定4组单词，每组单词分为两个子集a和b：
1a) 野兽、蠕虫、纤毛虫、草、姿势；
b) 桌子、地面、书本、平面、外套。
2a) 鲸鱼、燕子、鲈鱼、老虎、蚂蚁；
b) 妻子、初级工人、理发师、丈夫、收银员。
3a) 麻雀、飞机、Baba Yaga、面粉、火箭；
b) 预订、隧道、已经、好吧、电话。
4a) 狗、马、鸽子、驴、骡；
b) 熊、袋鼠、蛇、老虎、鲈鱼。

⟦folio 15⟧

| | 机器翻译 | 机器翻译 | 人工翻译 |
| :--- | :--- | :--- | :--- |
| “生的” | “后期编辑” | | |
| 准确性 | —16% | —5% | 0 |
| 速度 | —21% | —11% | 0 |
| 理解 | —25% | —23% | 0 |

The main difficulty that reduces all three parameters is unnatural syntactic structures and word order in “raw” machine translation, as well as many translation options for one word.现在稍微计算一下。让我们表示为

$$\mathcal{U}_\text{ч} = \mathcal{U}_\text{м} - N \cdot P \left( B_\text{м} - B_\text{ч} \right).$$

The finished translation is intended for specialists who spend time reading it, and time is money (salary!), so the formula includes the value $P$.我们用平均统计数据来计算$\mathcal{E}$和$N$的值。

由于“原始”翻译需要更长的时间来阅读，我们得到了一个令人惊奇的模式：

| $N$ | 1 | 10 | 15 | 17 | 18 | 20 | 80 | 175 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\mathcal{E}$ | 13,17 | 5,97 | 1,97 | 0,37 | —0,43 | —2,03 | —40,13 | —127,03 |
