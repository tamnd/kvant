---
id: 2020-4-bakaev-esche-raz-o-grafike-sinusa-38066da2
issue: kvant_2020_4
year: 2020
number: "4"
title: 再次关于正弦图
authors:
  - Бакаев Е. В.
rubric: osnovnye-stati
page_first: 13
page_last: 13
tag: N635
lang: zh
source: kvant_digital
extraction: native
content_sha256: 97557ed280fb1ca5530a149e8ffb4a3ba3a7402f76388ce654bba74d53a841ef
prompt_sha256: draft-1
translated_from: content/ru/2020/04/articles/01_bakaev-esche-raz-o-grafike-sinusa-38066da2.md
source_content_sha256: 26c75205ebe2b6c784e0c5a26218199c47d61423ead3f38b65e295894ae3f21b
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

再次关于正弦图

巴卡耶夫

P. Panov 的文章（参见 «Kvant» No. 3）讨论了 sin(314x) 图的样子，该图由横坐标为 $10^{-} 3$ 倍数的点组成。很自然地概括这个问题并找出 sin ( ax ) 的图形，如果仅标记其横坐标为 d 的倍数的点，它会是什么样子。在这里我们将考虑解决这个问题的另一种方法。为了简单起见，我们还将采用一种特殊情况，但不同的情况：a = d = 1。让我们构建一个图：图 1 显示与 0 到 50 之间的整数 x 的 sin x 值相对应的点。但是图的尺寸以及相应的轴的比例可以通过不同的方式选择。例如，这里是自然 x (图2) 的 sin x 的前 1000 个点和前 10000 个点 (图3)。事实证明，a 和 d 并不是决定我们在图表上看到的内容的唯一参数；轴的比例也很重要。

⟦figure⟧

图 1

⟦column⟧

⟦figure⟧

图 3

这些图形彼此并不相似：在一个图形上出现六边形图案，在另一个图形上出现类似于正弦的线条交织。但它们的结构是相同的，只是一个有 1000 个点的图是一个有 10,000 个点的图的一部分，拉伸了 1 10 的宽度（通过这种拉伸，点本身不会拉伸成椭圆形，但仍然保持圆形）。您可以通过从侧面以锐角查看 图 2 处的图表来验证这一点。然而，这些图看起来有所不同，因为这种拉伸方式会增加许多点对之间的距离，而在 图 3 上看起来很接近的点在 图 2 上可能不会出现。这个问题是由 Gilbert Strang 在书中提出的 [1]。 Norman Richert 的文章“Strang 的奇怪人物”[2]对此进行了更详细的讨论。我们的方法将很大程度上遵循这些来源。但情况会有所不同。

直型，缠绕在圆柱体上

图 2

DOI: https://doi.org/10.4213/kvant20200402

为了使进一步的推理和计算更简单，让我们从正弦转向考虑直线。为此，想象一个圆柱体。如果在透明薄膜上画一条直线并将薄膜缠绕在透明圆筒上
