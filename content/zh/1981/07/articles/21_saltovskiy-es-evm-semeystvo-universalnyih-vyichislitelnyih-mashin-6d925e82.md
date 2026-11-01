---
id: 1981-7-saltovskiy-es-evm-semeystvo-universalnyih-vyichislitelnyih-mashin-6d925e82
issue: kvant_1981_7
year: 1981
number: "7"
title: ES Computers - 通用计算机系列
authors:
  - Салтовский А. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 55
page_labels: 51-53
tag: U4AA
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 8323e80fff241bcfd95838f34037eba5873986f7ab2e76c9708b6326d87118b4
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/21_saltovskiy-es-evm-semeystvo-universalnyih-vyichislitelnyih-mashin-6d925e82.md
source_content_sha256: ab3ac8c67b985195a5ca9ab2cea4dcc1ed01eab580d747253680a239eb30e513
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 51⟧

A·萨尔托夫斯基

ES计算机家族
普遍的
计算
汽车

目前，大型计算机通常是家庭设计和制造的。家族中的每个成员都具有整个家族相同的基本技术特征，但在性能上却不同于其“亲戚”。

在苏联和社会经济国家，最广泛使用的通用计算机家族是EC系列（统一系统）。该系列的十大型号计算机，性能各异，在程序和数据的使用上是兼容的。该系列拥有广泛的外围设备，几乎用于该系列的所有机器。所有机器都具有相同的设计和技术构造原理。

设计该系列时设定的主要目标是覆盖尽可能多的计算机应用领域。因此，机器的成本及其制造成本与解决问题的速度、解决问题的重要性和复杂性是同等对应的。单一软件系列可以实现相同的目的，但如今其成本超过了硬件成本。在这种情况下，拥有一个通用的输入输出接口至关重要——通道和外部设备之间通信的一组标准化技术和软件手段，这使得能够以标准形式组织它们之间的信息交换；这允许在一台计算机上使用多种外部设备。

家庭构成

自1969年CMEA各国就计算机技术领域合作达成协议以来，在相对较短的时间内，开发了第一阶段的EC计算机模型——Row-1——，并自1973年开始开发该系列更先进的模型——Row-2。

今天的家庭构成是这样的：

小型计算机：
型号 - EC-1010、EC-1020、EC-1021；
速度 - 每秒 10÷100,000 次操作；
RAM 容量 - 64÷512 KB；

中型计算机：
型号 - EC-1022、EC-1030、EC-1032、EC-1033、EC-1035、EC-1040、EC-1045、EC-1055；
速度 - 每秒 80÷500,000 次操作；
RAM 容量 - 128-2048 KB；

大型计算机：
型号 - EC-1050、EC-1052、EC-1060、EC-1065；
速度 - 每秒 50 万 ÷ 300 万次操作；
RAM 容量 - 512÷8192 KB。

外部设备统一

现代计算机中使用的信息输入和输出设备数量众多且多种多样。这是 ATsPU（字母数字

⟦folio 52⟧

第一打印设备）、打孔卡输入设备和打孔带输入设备。近年来，用于操作员和计算机之间直接、交互式通信的设备已得到广泛使用 - 电子打字机和字母数字显示器 *)。所有这些设备都存在于 EC 系列计算机中。 EC 计算机输入设备是单电路：每个设备都可以同样成功地连接到该系列中的任何机器。 Cherry 存储设备（在 EC 系列计算机中以磁盘和磁带驱动器为代表）以相同的方式连接到机器。由于采用标准接口，它们可以用于不同的型号，无论其性能如何。差异通常纯粹是数量上的：更多

*) 有关外部设备的更多详细信息，请参阅“输入的组织和计算机的输入”一文（«Kvant»，1980 年，第 6 期）。

生产率更高的机器拥有强大的外部设备。例如，对于低性能 EC 计算机，磁盘上的外部存储器容量为 15 ÷ 100 兆字节，而对于高性能机器，则达到数百兆字节。

建筑的统一性

各种 EC 计算机型号的“家族”连续性在图中清晰可见（参见图），其中显示了每种型号所需的设备数量。

作为示例，考虑 EC 计算机模型 Row-2 的一般结构。

EC计算机架构Row-2的主要元素如下： 1）处理器； 2）内存； 3）输入-输入通道； 4）cherry设备的控制； 5）外部设备。

系统的核心是中央处理器（«Kvant»，1980年，第5号）。

⟦folio 53⟧

不同模型的垃圾处理过程的内部组织可能有所不同。这是因为模型的性能反映了其生产成本。类比造船业，我们可以说，游船的船体完全没有必要具备破冰强度——各有其各自的功能。

EC计算机系列不同型号机器之间的软件兼容性是通过以下事实来保证的：所有型号都实现相同的命令系统并使用相同的数据结构（参见今年第4期«Kvant»文章“三地址、单地址和...无地址机器”）。特别是，EC计算机中的每个处理器都具有16个通用寄存器和4个浮点寄存器*)以确保提高计算精度，并且最新型号的EC计算机（Series-2）在处理器中具有第16个控制寄存器；普通程序无法访问这些注册，但控制程序会主动使用这些注册来组织和控制计算过程。

EC计算机模型的所有进程的必备附件是程序状态字寄存器。程序状态字存储在这个 64 位寄存器中，旨在控制 RAM 中已知的指令执行顺序。

RAM 和外部设备之间的数据交换是通过通道（专门的输入输出处理器 - 参见«Kvant»，1980 年第 6 期提到的文章）来实现的。该处理器中的进程干预很少 - 它启动操作并在执行结束时分析结果。

*) 这意味着数字试用部分之前的逗号可以放在寄存器中的不同位置。

软件统一

EC计算机命令系统对整个系列是统一的，允许对科学任务、会计和经济应用中所需的高精度数值数据以及文本信息处理任务的派生符号特征进行广泛的操作。

在基于 Fortran、Cobol、Algams、PL/1 编程语言的高级语言编程系统中，也可以看到家族和通用应用程序中相同的标准化总体路线。 Nowadays, many users of EC machines have the opportunity to work in Pascal. This language will be discussed in detail at the Correspondence School of Programming after the summer holidays.

谈到对该系列机器的兼容性进行编程时，需要注意的是，并非所有为 EC 计算机 Row-2 编写的程序都可以在 EC 计算机 Series-1 上运行，因为该系列的较旧型号包含一个附加命令组，仅在这些最新型号上实现。 But EC computer programs Row-1 can be processed on EC computers Row-2 without any changes. In this case, they talk about programming continuity “from bottom to top.”

目前，EC计算机代表了社会国家计算机系统的发展，已广泛应用于国民经济各部门。 The development of new generations of the family continues. The main devices of designers are now aimed at both increasing productivity and reducing costs. This is primarily due to the transition to a new design and technological base - large integrated circuits.
