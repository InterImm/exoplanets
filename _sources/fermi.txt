费米悖论——他们在哪里
*****************************


我们发现了这么多的行星，可是为什么我们还没有遇到外星人呢？他们都到哪里去了？

1950年，费米问出这个问题（Whre are they?）的时候，我们并没有观测到太阳系之外的行星，在那样一个年代，这样的问题似乎并不是那么有趣。

现在我们已经确认了一千多颗系外行星，几千颗候选，而且这些数字还在继续增长。时至今日，费米的这个问题越来越重要，如果有那么多的栖居地，大家都在哪里呢？


   宇宙显著的尺度和年龄意味着高等地外文明应该存在。

   The apparent size and age of the universe suggest that many technologically advanced extraterrestrial civilizations ought to exist.

   但是，这个假设得不到充分的证据支持。

   However, this hypothesis seems inconsistent with the lack of observational evidence to support it.

   -- `费米悖论|维基百科 <http://zh.wikipedia.org/wiki/%E8%B4%B9%E7%B1%B3%E6%82%96%E8%AE%BA>`_



费米悖论的解释
===========================


David Brin 的 Great Silence
--------------------------------------------------------


.. admonition: 评论
   :class: note

   这些比较老的研究和讨论中，大多在讨论能够通过监测外星智慧生命主动发射的通信或其他用途的电磁波探测到，或者有星际飞行能力来到地球附近从而被我们发现这样的事件。然而，随着现在科学和技术的进展，我们现在能够探测系外行星的大气层的一些细节甚至行星表面的细节，这使得我们可以讨论的探测方式由对方主动发射电磁波被我们探测到转变为我们可以直接探测系外行星上的生命的活动痕迹。而这样的探测甚至不需要智慧生命掌握电磁波通信能力，例如，我们可以直接探测可能的化石燃料燃烧的痕迹等。

   然而，这也只是在短短几年间发展起来的技术。或许，在很快的将来，我们可以看到系外行星的更多细节，那时候，也许，我们观测的外星生命，却没有能力看到我们。技术的不平等，将会给我们提供很多的契机。



Glen David Brin 在 1983 年曾经发表过一篇名为 `The Great Silence - the Controversy Concerning Extraterrestrial Intelligent Life <http://www.brin-l.com/downloads/silence.pdf>`_ 的论文。在篇论文中，David Brin 导出了一个类似用来描述在当前人类接触到 ETIS，即 Extraterrestrial Intelligent Species，的几率。


.. admonition:: Drake 方程
   :class: note

   Drake 方程是用来计算（描述）一个完整范围内（例如一个星系）存在可以被探测到的智慧文明的地点（例如行星）的数目：

   .. math::
      E = R f_g n_e f_1 f_i f_c L，

   其中各个参数的意思在下面的列表中指明。

   * :math:`R`，该完整范围内的恒星的产生率；
   * :math:`f_g`，有行星的稳定的（矮）恒星；
   * :math:`n_e`，每个恒星系中的潜在的可以利用的行星；
   * :math:`f_1`，上面提到的行星中能产生生命的比率；
   * :math:`f_i`，所有产生的生命中，演化出智能的比率；
   * :math:`f_c`，上面提到的智慧生命中制造出可以被检测到的技术的比率；
   * :math:`L`，带有这样的技术的种类的寿命。


当前（电磁波通信，低速飞船这样的技术水平）人类遇到外星智慧生命的概率（更严格的说是 likelihood）可以用下式计算，

.. math::
   C = \frac{1}{N^*}\sum_{j=1}^{E} A_j (n_j+1).

公式中的 :math:`E` 就是 Drake 方程计算出来的存在可以探测到的智慧文明的栖居点。:math:`A_j` 是第 j 种演化出来的智慧生命栖居的或者排出的机器人（例如 von Neuman robot）所占据的栖居点的数目，之所以有个 :math:`+1` 是因为我们假定这个种类的生命是在其母星上演化出来的，所以他们总共在 :math:`n_j+1` 个行星上留下了痕迹。:math:`A_j` 是这类智慧生命的“接触截面”（contact cross-section），是这类生命跟其他的生命有接触的可能性的一个参数。:math:`N^*` 是“归一化”系数，这里选用有效的恒星数目，去掉了那些不合适的恒星（例如短寿命的恒星，太过靠近的双星等等）。


David Brin 提出了 :math:`n_j` 的一个形式，

.. math::
   n_j = B f_g n_e 4 \pi \int_0^{R_j} e^{-(R_j-r)/v L'}\mathrm d r,


:math:`B` 是恒星的数密度，:math:`R_j` 是该种类的生命的扩展范围的半径，:math:`v` 是他们的扩展速度（与他们的飞船的速度、繁殖速度等有关），:math:`L'` 是每个栖居点上面的寿命（与 :math:`L` 有关）。


这样总结下来，我们关心的量 C，即当前人类遇到外星智慧生命的 likelihood 与这些的参数相关：:math:`f_g`、:math:`n_e`、:math:`f_1`、:math:`f_c`、:math:`f_i`、:math:`L`、:math:`A`. 要解决这个问题，就要分别讨论这些量。



.. admonition:: 关于为什么我们接触不到外星智慧生命
   :class: note

   有很多关于这个问题的讨论。下面从 David Brin 的论文中节选一些列举出来。

   1. 外星智慧生命可能故意躲开我们这样的低级的智能或技术。毕竟相遇之后我们大多在获取新的信息，而不能提供给他们新的信息。
   2. 由于电磁波很容易被检测到，所以智慧生命可能会使用 `Bracewell probe <https://en.wikipedia.org/wiki/Bracewell_probe>`_ 来传递信息，从而减少电磁波的使用和泄露，而且他们也会很注意少使用用来扩展殖民地的机器人（可能会叛变失去控制）。
   3. 因为我们的探测方式不对。外星文明在使用一些我们不懂的技术进行通信，因此我们无法加入到他们的通信中。
   4. 外星智慧生命故意隔离我们。可能的原因例如，把我们太阳系当作一个大型的野生动物园来看待（Ball, John A., 1973. Icarus, 19, 347），想要让地球独立发展以期待新的类型的事物出现（Kuiper, T.B.H. & Morris, M., 1977. Science, 196, 616）。也可能是等待地球上的社会发展成熟，或者觉得地球上人类太过危险（获得与社会发展以及人类心智不相匹配的科技之后）。
   5. Macrolife：摒弃了在行星上生活的方式。例如建造大型飞船游走在太空中，甚至拆解行星作为自己的飞船的原料。例如小说 Macrolife.
   6. 某些种类可能害怕太空，在行星上极力发展其他的技术并达到了出神入化的程度，但是依然没有离开自己的行星。例如虽然有过一个短暂的扩展时期，但是很快就蜗居在自己的母星上不出门了。
   7. 地球并不是他们想要的地方或者地球无法接近。例如这些智慧生命依靠某种类似虫洞的技术来快速穿越在不同的地方，但是由于某些原因，这类技术不能在地球附近建造，从而与地球没有接触。

   除了文中这些比较基础的解释，还有很多其他的可能解释可以从这些里面衍生出来。

   1. 由第一条中，我们可以猜测甚至我们的太阳系就是一个被“圈起来”的动物园。他们在观察我们，而我们并没有观察他们。
   2. 可能为了保护自己，外星文明把自己保护起来，不敢发出声音，以免被发现受到可能的外来伤害。这条似乎并不是很成立，因为探测一个文明的技术要比星际飞行的技术容易多了。大气层中的活动，云层，地表活动等等，都能暴露自己。
   3. 我们人类是外来的。外星文明在这个行星播种，然后离去，等待我们成长成人。因为 DNA 结构拿了诺贝尔奖的 Francis Crick 和 L. Orgel 合写过一篇文章，提出了 Directed Panspermia 的思路。[#directedpanspermia]_ 我们的地球上的生命可能是外星生命的播种。论文中讨论了如何播种、动机等等问题。






.. admonition:: 小知识：星系围绕银河系中心的公转
   :class: note

   由于公转的角速度不一样，所以径向方向的邻居会变化。




.. [#directedpanspermia] F. H. C. Crick and L. E. Orgel, `Directed Panspermia <http://www.sciencedirect.com/science/article/pii/0019103573901103>`_ . ( `PDF <http://profiles.nlm.nih.gov/ps/access/SCBCCP.pdf>`_ )




刘慈欣的黑暗森林
---------------------------

这是一个比较有效的解释，因此也比较流行。David Brin 等人也在文章中用过森林的比喻，使用了相同的思路。



Randall Munroe (xkcd) 的 Fish
-------------------------------


.. figure:: http://imgs.xkcd.com/comics/fish.png
   :align: center
   :alt: Randall Munroe's Fish

   Randall Munroe 的 `1377号 <http://xkcd.com/1377/>`_ 漫画。



Bezsudnov 和 Snarskii 的智慧扩张模型
----------------------------------------------------------------------



`Where is everybody? -- Wait a moment ... New approach to the Fermi paradox <http://arxiv.org/abs/1007.2774>`_


`为什么我们还没遇到外星人？ <http://www.guokr.com/article/129942/>`_












文明
=================================


Kardashev
---------------


前苏联天体物理学家 Nikolai S. Kardashev （尼古拉·卡尔达肖夫，Никола́й Семёнович Кардашёв）在 `一篇论文中 <http://adsabs.harvard.edu/cgi-bin/nph-bib_query?bibcode=1964SvA.....8..217K&db_key=AST>`_ ，[#kardashev]_ 提出了 Kardashev Scale （卡尔达肖夫指数），将文明分为了三个不同的级别。

最初的问题是，如果一个文明要通信，那么他们无线电会有多么强？这是很有限制性的问题，但是却有启发意义。


* Kardashev Type I

第一类指能量消耗大约在 :math:`4\times 10^{19}erg/sec` 也就是 :math:`4\times 10^{12} W` 这样的量级。

在这样的量级上，虽然还是生活在单一星球上，但是已经开始对星系进行探索了。或者说，基本上**可以**使用自己星球上几乎所有的能源，极端的情况可以控制地震和天气。

然而这类文明可以利用的太阳的能源，却只有那么照射到星球上的那些。


* Kardashev Type II

第二类能量的消耗大约在 :math:`4\times 10^{33} erg/sec` 也就是 :math:`4×10^{26} W` 这样的量级。然而这样的文明需要喂饱自己，他们需要获得他们的恒星每时每刻所发出的所有能量。

Freeman Dyson 在 1959 年提出的 Dyson 球可以作为这类文明的一个能源采集方式。Dyson 球要用一个半径一个天文单位的球壳把整个恒星包裹起来，并且采集其中的太阳能。然而这样的方式可能导致更外层行星或者卫星上的文明的不满。



* Kardashev Type III


第三类的能量消耗级别到了整个星系级别，也就是 :math:`4 x 10^{44} erg/sec` 或者 :math:`4×10^{37} W` 。如果一个文明到了这样的级别，那他们可以殖民整个星系了。



Kardashev 的分类里面有很多的假设，例如文明增长速度的假设等等。然而这是一个非常好的思路，在有条件的情况下，我们可以扩展这个模型。





.. [#kardashev] N. S. Kardashev, `Transmission of Information by Extraterrestrial Civilizations <http://adsabs.harvard.edu/cgi-bin/nph-bib_query?bibcode=1964SvA.....8..217K&db_key=AST>`_ .


