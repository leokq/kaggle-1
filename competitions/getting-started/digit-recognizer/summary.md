# @rujinshi

## 个人总结

为期半个月的手写识别数字项目已完结。不想谈最终的排名（因为我做的排名很差）。谈谈收获与自己的不足。 

 我真正参加了大概只有十天时间。这是我第一次抛开课本理论去实现这个题目，这个题目虽然已经很老，数据的处理过程已经很成熟，正是因为这样，我在参考别人的代码下做了自我参数的调整，让我熟悉了一点点这个调参的过程，也是我第一次去认认真真地去阅读sklearn（还有其他的）的官方文档，我只接触到了一点点sklearn的API，差的还很多很多，更不谈熟练使用。

## 不足

 1.特征工程不熟练。此数据集已经很干净了，几乎没有太多的噪声。但是还是会涉及一点小技巧，我不会使用，不会清洗数据。后来我在书上看到了关于归一化和标准化的操作。之前看理论看的最多的就是PCA，我一开始根本不会用sklearn这个API。后来学会了画图观察降维的程度，但是用的还是不行。此外，我并没有用其他的降维模式。

  2.代码能力差，模型不熟练。算法的调优要从哪些步骤着手，局限是什么？相互间的联系，适用的数据类型？评价指标是什么？万年精准度？

 3.可视化能力不足。对与箱形图散点图折线图各种不熟练。不知道怎么构造数字特征，从而去可视化。

## 得到了什么

自己不足的地方太多了。短期计划1.精读wepon的开源代码。2.低头写代码，不断总结对比。3.做事的计划性。4.深挖一个领域（金融量化or推荐系统or计算广告）



#@hduyyg

1. 第二版的结果还是很不满意的，主要原因还是出在我自己身上吧。

   这段时间忙着找工作，是真的头痛，我甚至都想着是不是滚回去考研，或者去当个初中老师，一边工作一边考研。现在大四了，接近毕业，我个人是很不希望还要靠家里接济的，所以真的是压力山大，每天都要为工作的事情头痛。这段经历也给我自己很大的一个教训：自己的提升最重要。

   工作很难找的原因主要有二：1. 春招的时候，大公司的名额真的是太少了，很难进； 2.在上家公司的时候，主要精力都放在公司的工作上，做的是爬虫，导致自己看书荒废了，找工作的时候，后遗症就凸显了，基础基本都是半年前看的了，真的是记不清楚了。

   在这种状态下，身体疲惫、精神上更加疲惫，我个人无论是在项目进度、人员管理等方面都是存在问题的。对于这种情况，我只能对大家说：真的很抱歉。还好现在工作已定，虽然工作会更忙，但是压力没有之前那么大了，同时，新一代的两位管理成员也熟悉起来，之后也不用什么事情都打在我自己身上了。

2. 流程经验总结：

   就经验来看，把项目按照版本进行划分还是比较合理的。因为都是初学者，在做的过程中，随着了解的深入，肯定会有更多新的解法被发现，但是需要去尝试吗？肯定需要。立马实现吗？这样不太好。我觉得这样的话，项目没有明确的规划，陷入越做越多，不知结束在何方的尴尬境地。我想的话，进行版本划分之后，提前结束版本规划，然后在下个版本尝试这些新的东西，也会比想到哪儿搞到那儿要好一点。当然，这些事情并不绝对，毕竟现在也是摸索阶段，什么都要尝试以下，才能知道怎样做才是最好的。

   项目流程主要分为三大步：项目规划——项目实现——总结。

   1. 项目规划：

      这一步要做的事情包括：这个项目要完成的内容（使用哪些基础解法）、进度规划（所谓将跑一万米变成跑十个一千米）、每个阶段要达成的目标（比如前程什么解法，达到多少的得分）、流程规范（由谁来合pr、项目结构、是否写日报等等）。

      在数字识别第二版中，项目规划就没有做好，直接导致整个过程效率地下。后面项目实施的时候，发现这个算法毫无作用，导致浪费了安排的时间，或者，原本安排的时间，不够来做某个事情。实际上在第二版中，并没哟添加什么新的东西，我自己的时间实际上有很多是没有利用起来的。

   2. 项目实现

      这一步要做的事情包括：各个基础解法的实现、将基础解法进行糅合得到强学习器。

   3. 总结

      这一步主要是就是每个人写一下从项目开始到结束的这个过程中的感想，比如：自己的学习方法有什么问题、什么事情没有做好等等。目的是希望参与的成员，通过回顾，对自身的优缺点有一个更好的认识，从而在之后的项目中做得更好。

3. 人员管理经验：

   1. 作为管理者，很多事情需要自己去主动引导，调动他人的积极性。

      很多人也许会有这样的想法，他自己不主动，难道还指望我主动吗？但正所谓屁股决定脑袋，既然已经作为管理者，那么你的首要任务自然是自己的提升，你以为我会说带领组织向前进吗？那是你的次要任务。

      目前阶段的组织，仅仅是大家自行发起的，就算作为发起人，我也是没有利益在其中，这意味着，一旦某天你离开组织，也许你的付出就辅助东流。虽然，我说这种话，不是很妥当。

      当然了，作为管理者，带领组织前进，也是你锻炼自己能力的极好机会。既然有这个目标，自然是要想方设法去完成，不能像普通成员那样任性。人都有从众的心里，很多事情，只要有人第一个发起、带领，就能爆发出平时所看不到的力量。

   2. 要能够充分考虑到团队成员的情况。

      我们是非盈利的自发性组织，大家都是因为兴趣聚集到一起，既如此，只要别人怀有激情，想要参与到组织中来，那我们就不应当拒绝别人，否则，即是和组织创立理念相违背。

      但激情是一回事，实际操作有事一回事。根据成员的各自情况，可以允许他们不同程度的参与到项目中来。哪怕只是跟随项目打酱油，没有实际参与代码编写等等，但在这个过程中，至少他也能够熟悉我们的一个项目流程，完全在可以在之后，作为一个独立项目的负责人主持项目进行。从这个角度看，我们培养内部人才就是成功的。

   3. 重视内部人才的培养

      这一点很重要，目前是草创阶段，所以管理模式等方面都需要自己摸索，寻找合适的管理者也是势在必行，我一个人毕竟不能管理全部的事情。那么这个时候，寻找合适的、与自己理念相近的成员，使其熟悉已有的运行模式，与自己一同进行管理，或者作为后备干部，都是很有必要的。

   4. 不能任性

      这个确实是从普通成员到管理者的一个艰难过渡吧。其实很多时候、很多事情都需要自己的耐心与承受力足够好才行。比如：大家刚进组织，会有人觉得自己很菜，跟不上进度，不敢说话、不敢参与，即使自己告诉他们前几天我和他们一样菜；很多事情，也不是说一遍就能完的，需要经常、反复的讲等等。

      总之，为了组织的良性发展，必要的规模是要有的，我们的每一个成员都是很珍贵的，抱着能挽救就挽救的态度。