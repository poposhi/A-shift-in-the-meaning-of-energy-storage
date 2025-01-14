儲能意義的轉變 建議直接看 PDF
2024年12月25日 詹家彰 m10707102@gapps.ntust.edu.tw	

結論: 
原本儲能系統主要用於配合再生能源，但因為AI工業革命的到來，需要大量能源，減少碳排已經不是最重要，儲能的作用將轉變為輔助各種發電廠，最大化發電量

特斯拉在2023年的投資者日公布了他們的 Master Plan 3，其中提到為了讓世界邁向脫碳經濟，全球大約需要 240 TWh 的電池儲能，主要應用於交通、能源、供暖等多個領域。但是 2024 年第二季的特斯拉財報會議中，馬斯克說"新增電池組後，您現在可以在穩定狀態下運行發電廠。穩態意味著基本上世界上任何地方的任何給定電網在一年中都可以產生累積能量，至少是目前產生的兩倍，在某些情況下，可能是三倍"[1]，馬斯克對電池的理解已經不是減少排碳了，在此同時Google，微軟也修改了自己的排碳標準，或者宣佈放棄碳中和[2]
減碳目標已不再是儲能發展的重點， 最重要的是最大限度的生產能源來發展AI，迎接新一輪的工業革命，輔助再生能源讓電網可以併入更多的再生能源，輔助傳統發電機，增加發電機滿載生產的時間。

儲能意義的轉變
我認為這個是個很重要的時刻，象徵著儲能系統存在意義的轉變 原本的電力系統用電成長很小，儲能的意義在於 能夠緩衝再生能源產生的不穩定能量 來匹配真實用電進而降低碳排，然而隨著ChatGPT的問世 一切都改變了，電力需求量瘋狂增加，儲能變成用來最大化發電量 以提供足夠的能量給AI


原因
AGI
華為創始人任正非:我们即将进入第四次工业革命，基础就是大算力，第四次工业革命波澜壮阔，其规模之大不可想象[ 3]
AGI（Artificial General Intelligence）的定義 AGI並沒有明確的定義，但每個人的理解都不盡相同。對於Sam Altman來講，AGI的定義是:"一個相當於普通人水準的人工智能，像一個可以被雇用的遠程同事。它可以完成你希望遠端工作者通過電腦完成的任何工作，包括學習如何成為一名醫生，學習如何成為一個非常出色的程序員"[ 4]，Google DeepMind CEO德米斯·哈萨比斯（Demis Hassabis）對於AGI的定義則是「一個通用系統，能夠完成人類可以完成的任何認知任務」。https://www.youtube.com/watch?v=vd9GxG5Qn-k&ab_channel=Greylock
[ 5]
人類一旦做出AGI，AGI預計可以取代很大部分的白領工作，很多事情可以交給 AI 去做，社會的經濟產值將會快速飆升。諾貝爾獎得主傑弗里·辛顿（Geoffrey Hinton）說，幾乎所有 AI 專家都認為是人類可以做出AGI[ 6]，Demis Hassabis也持相同看法[ 7]。然而，目前很難預估什麼時候能夠實現。科技巨頭們的預測範圍大約從2025年至2030年不等[ 8]。接下來將描述為何人類在建立 AGI 的時候會需要大算力與電力。

縮放定律
“””
 [ 9]
OpenAI 前首席科學家 Ilya Sutskever:
“如果你有一個非常大的神經網絡，並使用大量的數據集和計算資源來訓練它，那麼你可以可靠且可預測地實現驚人的效果。而這個簡單的想法是自深度學習革命開始以來，幾乎所有人工智慧進步的核心基礎。” 大神經網絡，大數據大量的算力是過去十年幾乎所有人工智慧進步的基礎，基本上就是所謂的縮放定律，什麼是縮放定律呢？
[ 10]

上圖主要是关于AI模型縮放定律的核心结果，y 軸都是模型的損失，越小代表模型預測的越精準，越聰明。最右边的图讲的是参数数量的扩展规律，x 軸是算力的對數。研究人员使用了一个非常大的数据集，因此不用擔心會用完資料，並且給所有模型很长时间訓練，确保它们基本上达到了學習性能上限(收敛状态)，可以觀察到每一個參數數量會有一個極限值，然後隨著參數量的增加，極限值會越來越低，也就是說，隨著參數量的提高，模型的聰明上限也會提高

在中间的图中进行了类似的操作，但把数据量和参数数量互换，即训练一个非常大的模型，所以模型的规模不是性能的限制因素，而是用不同大小的数据集来进行训练，并提前停止，测量在测试损失最小的点时的测试损失，再一次得到了测试损失随数据集大小变化的非常明确的幂律关系，意味著每一個資料量會有這個資料量能夠得到的最好的模型的極限，然後隨著資料量越多，可以得到更好的模型。

繪製了不同大小模型的學習曲線，給每個模型非常大量的資料並且为所有不同的模型规模训练了很长时间，因此每一個模型都可以學習到極限，在圖片上，淺藍色的細線末端呈現水平，就是隨著計算量的提升，這個模型已經到了極限，沒有辦法再繼續變好了，可以從黃色虛線直線觀察到，不論給定多少參數量大小的模型或者多少資料量，算力會有一個沒有辦法突破的極限，然後隨著算力的提升，這個極限會變低，意味著如果擁有更強大的算力，可以得到更聰明的模型

 
我們並不知道為何AI 模型會有縮放定律，它是一個經驗法則也許會繼續，也許會停下，所以我們要看看目前的情況，2024年6月最先進的開源模型 meta的llama 2 的訓練資料顯示，就算是最小參數量7B的模型在整個訓練過程中損失仍然是直線下降，還沒有放緩的跡象 [ 11]，Mark Zuckerberg在2024年4月的時候說[ 12]，他們最新的模型(llama 3)，即使是最小參數的，仍然還在學習，還沒有飽和，也就是說，到目前為止如果給模型更多的資料或更多的訓練量模型仍然在持續的變聰明，因此各大科技公司仍然在持續擴大訓練規模新建更大的算力中心

2GW+算力中心
因为人工智慧的缩放定律，我们只要投入更多的算力，也就是能源，就可以得到更聪明的模型。所以，几乎每一个大型科技公司都开始建造几栋大容量AI算力中心。甲骨文公司創始人Larry Ellison在2024年9月財報會議[ 12]向投資者说，他们已经在建设一个800MW的算力中心，并且正在设计1GW的算力中心。Ellison說目前有几家大型科技公司，甚至可能只有一个国家，将在未来几年争夺AI模型的“技术霸权”。为了在尖端AI模型竞赛中保持竞争力，成本不会便宜，他补充道。
“入场价格大约是1000亿美元。让我重复一遍，大约是1000亿美元。这是在未来五年内，任何想参与其中的人必须支付的价格，”他说[ 13]
2024年9月，Elon Musk的人工智能公司xAI已在孟菲斯的算力中心部署了约10万张英伟达H100 GPU，大約150MW，並且僅用了122天[ 14]，Mark Zuckerberg在10月的財報會議說他們現在在用超過10萬張H100訓練模型，並且计划在年底前部署35万块英伟达H100 GPU[ 15]，按照比例推估年底臉書的這個算力中心會是525MW，微軟與open AI是目前買最多 GPU 的公司，他們的算力中心不會比其他公司還要小，他們預計重啟曾經發生核事故的賓州的三哩岛核电廠，九月Alphabet CEO Sundar Pichai 表示，Google正在擴大其計算基礎設施並致力於 1GW+ 的算力中心[ 17]，我個人認為兩年內就會有幾座1GW算力中心蓋好。
也就是說，縮放定律仍在持續發展，還未達到極限，因此各大公司仍在擴大各自的算力中心。目前幾乎每家公司都宣布在設計興建1GW規模的算力中心，合理推估2025年就會有第一個1GW算力中心。根據Zuckerberg的態度，短期內我們還不會達到縮放的極限，個人認為很可能接下來會見到10GW規模的算力中心。2024年12月Zuckerberg 宣佈要蓋一個2GW算力中心，並且要新蓋一個1.5GW 天然氣發電廠為算力中心供電[ 17]
這還只是訓練模型所需的電力，實際情況下還有推理所需的電力需求。訓練過程是讓模型學習和獲取智慧，而推理過程則是模型提供服務，像我們日常使用ChatGPT時的電力消耗。目前還缺乏足夠的公開資訊，難以具體估算這些需求，但Amazon 的Claude ai 創辦人Dario Amodei說大部分成本在于推理，而不仅仅是模型的训练成本[ 18，有可能推理的電力消耗會比訓練的更多。
缺乏電力
由於模型訓練和推理都會產生大量電力需求，因此Zuckerberg在2024年4月的一次採訪中提到[ 19 他認為人工智慧發展的最大瓶頸不是晶片，而是能源。馬斯克也表示，他認為未來會電力短缺[ 20。
綜合以上信息，可以預測未來美國所有頂尖的科技公司，其發展的瓶頸之一將是能源生產。因此可以推測，未來世界上最雄厚的資本和最頂尖的工程師，將會有大量投入電力生產。
目前可以觀察到的趨勢是，許多公司已經開始購買並親自建設核能發電。此外，全球頂尖的燃氣發電機生產商——日本的三菱電機，也報告由於人工智慧的發展，2024年的訂單量較前一年增加了50%。[ 21，同樣生產燃氣發電機，還有輸電變壓器的西門子能源股票上漲的幅度比Nvidia還要多[ 22
訓練模型引發的電力系統挑戰:
馬斯克說，對於一個容量為50MW的算力中心，電力需求波動可以在100毫秒內從50MW降低到20MW，然後再回到50MW[ 23就我所知，除了儲能系統，沒有其他方法可以補償如此迅速的電力波動。根據報導[ 24，特斯拉的儲能系統也準備投入到算力中心的供電設備之中，已經在建設中。


因為臺灣會需要大量電力，然後可以使用電池幫忙

隨著人工智慧（AI）技術的發展，未來的大規模應用將顯著提升全球的電力需求。這一需求的成長呈現出一種電力循環迴圈：AI運算的增多會驅動電力需求上升，訓練好的模型會去提供服務賺錢，賺到的錢來蓋更多的算力中心，隨著這種循環持續擴大，理論上各種形式的發電資源需求亦隨之增加，包括燃氣發電、核能、再生能源，最終甚至是燃煤發電。 

在這樣的背景下，電池儲能成為應對尖峰電力需求的重要方案。發電機通常並非持續運轉，而是根據負載需求啟動或停機，受到容量因素的限制。因此，利用電池來支援電力尖峰時段的需求成為有效解決方案。相關文獻指出，電池可以在非尖峰時段儲能，並於尖峰負載高峰時進行放電，達到負載調節的效果，有效降低發電機的負荷並提高電網穩定性。
臺灣的電網一直以來都會利用抽蓄儲能來降低夜晚尖峰，臺灣抽蓄儲能電量大約10GWh，而根據電力交易平臺[ 25]截至2024年12月至少已經採購電池的E-dReg有3GW，而E-dReg的電量至少是功率的2.5倍，可以合理推測兩年內，臺灣會新增超過7.5GWh 的電池儲能，這件事會越來越重要。



Conclusion: 
Originally, energy storage systems were mainly used to cooperate with renewable energy, but due to the advent of the AI industrial revolution, a large amount of energy is needed, and reducing carbon emissions is no longer the most important, and the role of energy storage will be transformed into assisting various power plants to maximize power generation

Tesla unveiled their Master Plan 3 at the 2023 Investor Day, which mentioned that in order for the world to move towards a decarbonized economy, the world needs about 240TWh of battery energy storage, mainly used in transportation, energy, heating and other fields. But during Tesla's earnings conference in the second quarter of 2024, Musk said "With the addition of a battery pack, you can now run your power plant in steady state. Steady-state means that basically any given power grid, anywhere in the world, can produce cumulative energy over the course of a year, at least twice as much as it currently does, and in some cases, potentially triple"[1] At the same time, Google and Microsoft have also revised their carbon emission standards, or announced that they will abandon carbon neutrality[2] 
Carbon reduction goals are no longer the focus of energy storage development, the most important thing is to maximize the production of energy to develop AI, to meet the new round of industrial revolution, auxiliary renewable energy allows the grid to incorporate more renewable energy, auxiliary traditional generators, and increase the time for generators to be fully loaded.

cause
AGI
Huawei Founder Ren Zhengfei: MeWe are about to enter the fourth industrial revolution, the foundation is large computing power, the fourth industrial revolution is magnificent, and its scale is unimaginable[ 3] 
Definition of AGI (Artificial General Intelligence) There is no clear definition of AGI, but everyone's understanding is different. For Sam Altman, AGI is defined as: "An artificial intelligence equivalent to the average human being, like a remote colleague who can be hired." It can do anything you want a remote worker to do from a computer, including learning how to be a doctor, learning how to be a really good programmer."[ 4] Demis Hassabis, CEO of Google DeepMind, defines AGI as "a general-purpose system capable of accomplishing any cognitive task that a human can do."https://www.youtube.com/watch?v=vd9GxG5Qn-k&ab_channel=Greylock
[ 5] 
Once humans make AGI, AGI is expected to replace a large part of white-collar jobs, and many things can be handed over to AI to do, and the economic output value of society will soar rapidly. Nobel laureate Geoffrey Hinton said that almost all AI experts agree that humans can make AGI[ 6] Demis Hassabis agrees[ 7] 。 However, it is difficult to predict when this will happen. The tech giants' forecasts range roughly from 2025 to 2030[ 8] 。Next, we will describe why humans need a lot of computing power and power to build AGI.

The Law of Scaling
“””
 [ 9] 
Ilya Sutskever, former Chief Scientist at OpenAI:
"If you have a very large neural network and use a lot of datasets and computing resources to train it, then you can achieve amazing results reliably and predictably. And this simple idea is the core foundation of almost all AI advances since the deep learning revolution began. Big neural networks, big data, and a large amount of computing power are the basis for almost all artificial intelligence advances in the past decade, which is basically the so-called law of scaling, what is the law of scaling? 
[10] 

The above figure is mainly about the core results of the scaling law of the AI model, the y-axis is the loss of the model, and the smaller it is, the more accurate and intelligent the model predicts. The graph on the far right shows the expansion of the number of parameters, and the x-axis is the logarithm of the computing power. The researchers are using a very large data set, so they don't have to worry about running out of data, and they train all the models for a long time to make sure that they basically reach the upper limit of learning performance (convergence state), and you can observe that there is a limit for each number of parameters, and then as the number of parameters increases, the limit value gets lower and lower, that is, as the number of parameters increases, The smart upper limit of the model will also be improved 

in the middle of the graph to do a similar operation, but the amount of data and the number of parameters are interchanged, that is, a very large model is trained, so the size of the model is not a limiting factor for performance, but with a dataset of different sizes to train, and stop in advance, measure the test loss at the point with the smallest test loss, and once again get a very clear power-law relationship between the test loss and the size of the data set, This means that each amount of data will have the limit of the best model that can be obtained for that amount of data, and then as the amount of data increases, a better model can be obtained.  The 

learning curve of different size models is drawn, and each model is given a very large amount of data and trained for a long time for all different model sizes, so each model can learn to the limit, on the picture, the end of the light blue thin line is horizontal, that is, with the increase of the amount of calculation, the model has reached the limit, and there is no way to continue to get better, it can be observed from the yellow dotted line, no matter how many parameters are given or how much data is given. There will be a limit of computing power that cannot be broken, and then as the computing power increases, this limit will become lower, which means that if you have more powerful computing power, you can get a smarter model

 
We don't know why AI models have a scaling law, it's a rule of thumb maybe it will continue, maybe it will stop, so let's look at the current situation.The most advanced open source model in June 2024 Meta's llama 2 training data shows that even the model with the smallest parameter amount of 7B still loses plummeting throughout the training process, and there is no sign of slowing down [11] ，Mark Zuckerberg said in April 2024[ 12] , their latest model (llama 3Even with the smallest parameters, it is still learning and not yet saturated, that is to say, so far, if the model is given more data or more training, the model is still continuing to get smarter, so major technology companies are still continuing to expand the training scale and build larger computing centers

2GW+ computing power center
Because of the scaling law of artificial intelligence, we only need to invest more computing power, that is, energy, to get a smarter model. As a result, almost every big tech company has started to build several high-capacity AI computing centers.Oracle founder Larry Ellison in September 2024Report to the meeting[ 12]Investors were told that they were already building an 800MW hash centre and were designing a 1GW hash centre. Ellison said there are currently several big tech companies, and possibly just one country, vying for "technological supremacy" for AI models in the coming years. To remain competitive in the race for cutting-edge AI models, the cost won't be cheap, he added.
"The entry price is about $100 billion. Let me repeat, about $100 billion. This is the price that anyone who wants to participate in it will have to pay in the next five years," he said[ 13]
September 2024,Elon Musk's artificial intelligence companyxAI has deployed about 100,000 NVIDIA H100 GPUs, about 150MW, at its hash center in Memphisand it took only 122 days[ 14] ，Mark Zuckerberg said in the October earnings conference that they are now training models with more than 100,000 H100s and plan to deploy 350,000 Nvidia H100 GPUs by the end of the year[ 15] , according to the proportion, it is estimated that the computing center of Facebook at the end of the year will be 525MW,Microsoft and open AI, the companies that currently buy the most GPUs, will not have smaller computing centers than other companies, and they are expected to restart the Three Mile Island nuclear power plant in Pennsylvania, where there was a nuclear accident, CEO of Alphabet in September Sundar Pichai said,Google is expanding its computing infrastructure and working on 1GW+ of the hash center[ 17] Personally, I think there will be several 1GW computing centers built within two years.
In other words, the law of scaling continues to evolve and has not yet reached its limits, so companies are still expanding their computing centers. At present, almost every company has announced that it is designing and building a 1GW computing power center, which is reasonably estimated to be in 2025There will be the first 1GWHash Center. according toZuckerberg's attitude, we will not reach the limit of scaling in the short term,Personally, I think it is likely that we will see 10GW nextof the hash center。 Zuckerberg, December 2024 Announced the construction of a 2GW computing center and the construction of a new 1.5GW natural gas power plant to power the computing center[ 17]
And that's just the power needed to train the model, and in the real world, the power needed for inference. The training process is to allow the model to learn and acquire wisdom, while the inference process is the power consumption of the model to provide services, such as when we use ChatGPT on a daily basis. There is still a lack of publicly available information to make it difficult to estimate these needs concretely，But Amazon Claude ai, founder of Dario AmodeiSay most of the cost ininference, not just the cost of training the model[18, it is possible that the power consumption of inference will be more than that of training.
Lack of electricity
Since both model training and inference generate a lot of power demand, Zuckerberg mentioned in an interview in April 2024[ 19 He believes that the biggest bottleneck in the development of artificial intelligence is not chips, but energy. Musk also said that he thinks there will be power shortages in the future[20。
Based on the above information, it can be predicted that one of the bottlenecks for the development of all the top technology companies in the United States in the future will be energy production. Therefore, it can be speculated that in the future, the world's most abundant capital and top engineers will invest a lot in electricity production. 
The current trend that can be observed is that many companies have already started to buy and build nuclear power generation themselves. In addition, Japan's Mitsubishi Electric, the world's top manufacturer of gas generators, also reported a 50% increase in orders in 2024 compared to the previous year due to the development of artificial intelligence.[ 21Siemens Energy, which also makes gas generators and transmission transformers, has risen more than Nvidia[22
Power System Challenges Raised by Training Models:
Musk said that for a hash center with a capacity of 50MW, power demand fluctuations can be reduced from 50MW to 20MW and back to 50MW in 100 milliseconds[23As far as I know, there is no other way than an energy storage system to compensate for such rapid power fluctuations. According to reports[ 24Tesla's energy storage system is also ready to be put into the power supply equipment of the computing center, which is already under construction.

“””

“””
Because Taiwan will need a lot of electricity, and then batteries can be used to help

With the development of artificial intelligence (AI) technology, future large-scale applications will significantly increase the global demand for electricity. As this cycle continues to expand, the demand for various forms of power generation resources will also increase, including gas-fired power generation, nuclear power, renewable energy, and eventually even coal-fired power generation. 

In this context, battery energy storage has become an important solution to cope with peak power demand. Generators are often not in continuous operation, but are started or shut down based on load demand, limited by capacity factors. Therefore, the use of batteries to support the demand during peak power hours is an effective solution. Relevant literature points out that batteries can be stored during non-peak hours and discharged during peak load peaks to achieve the effect of load regulation, effectively reduce the load of generators and improve grid stability.
Taiwan's power grid has been using pumped storage to reduce night spikes, with about 10GWh of pumped storage in Taiwan, according to the power trading platform[25]As of December 2024, at least E- batteries have been procureddRegThere are 3GW, while E-dRegis at least 2.5 times the power, and it is reasonable to assume that within two years, Taiwan will add more than 7.5GWh of battery storage, which will become increasingly important.
