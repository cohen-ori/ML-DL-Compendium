
The Machine & Deep Learning Compendium

The following is my personal compendium, which includes many topics, links, summaries in the fields of statistics, machine learning, deep learning, computer science, data science, deep vision, NLP, cloud computing, product management and others.

I see this compendium as a gateway and as a frequently visited resource for people of proficiency levels, for industry data scientists as well as academics.

The [following link](https://www.google.com/url?q=https://docs.google.com/document/d/e/2PACX-1vRE8XQ7y6ovbjWVkf4-Wn4ftXEqRW1a1Zxi6FF1kHsa4zrF4olPRxSwd721zZD5MBiNQtymm4eePAKv/pub&sa=D&source=editors&ust=1621930681646000&usg=AOvVaw1FHHc6VFsnNOluqd6_jh8N) is an automatically generated HTML version of this document, which is updated every 5 minutes. Some of you may prefer it over the editable version that you see here.

Please keep in mind that this is a perpetual work in progress with ~400 pages on a variety of topics. If you feel that something should be changed, please use the comment option and let me know.

I would like to thank the following contributors: [Samuel Jefroykin](https://www.google.com/url?q=https://www.linkedin.com/in/samueljefroykin/&sa=D&source=editors&ust=1621930681647000&usg=AOvVaw18oVQPuCExetxsf-qsgSw3), [Sefi Keller](https://www.google.com/url?q=https://www.linkedin.com/in/sefikeller/?originalSubdomain%3Dil&sa=D&source=editors&ust=1621930681648000&usg=AOvVaw3_aSrkqRJp8OTBITY3ZXmw)

Many Thanks,

[Dr. Ori Cohen.](https://www.google.com/url?q=http://cohenori.medium.com/&sa=D&source=editors&ust=1621930681649000&usg=AOvVaw1qBNE9TvtxscJS7ShkdFVY) ([LinkedIn](https://www.google.com/url?q=https://www.linkedin.com/in/cohenori/&sa=D&source=editors&ust=1621930681649000&usg=AOvVaw2oO9_q7Aa3FCJZrRqrykhB))

* * *

TABLE OF CONTENT
================

[TABLE OF CONTENT](#h.nsj5k29lts38)[2](#h.nsj5k29lts38)

[TYPES OF MACHINE LEARNING](#h.em2g2e1x5krl)[16](#h.em2g2e1x5krl)

[VARIOUS MODEL FAMILIES](#h.cvuli19h6ze2)[16](#h.cvuli19h6ze2)

[WEAKLY SUPERVISED](#h.u5zi1xmoebut)[17](#h.u5zi1xmoebut)

[SEMI SUPERVISED](#h.e0fgmg94ksi2)[19](#h.e0fgmg94ksi2)

[REGRESSION](#h.hrmba3x1w7wh)[22](#h.hrmba3x1w7wh)

[ACTIVE LEARNING](#h.w4s2hsc8nyr1)[23](#h.w4s2hsc8nyr1)

[ONLINE LEARNING](#h.8qsitrmpr01w)[29](#h.8qsitrmpr01w)

[ONLINE DEEP LEARNING (ODL)](#h.ddsdz437uy6s)[29](#h.ddsdz437uy6s)

[N-SHOT LEARNING](#h.aztf97nm1vni)[29](#h.aztf97nm1vni)

[ZERO SHOT LEARNING](#h.k2aa1i9h4y6)[29](#h.k2aa1i9h4y6)

[GPT3 is ZERO, ONE, FEW](#h.5zvrduu3ss7g)[30](#h.5zvrduu3ss7g)

[DATA SCIENCE](#h.3qzy5mep46r4)[31](#h.3qzy5mep46r4)

[LIFE CYCLE](#h.2nb2x8d3n00l)[31](#h.2nb2x8d3n00l)

[WORKFLOWS](#h.ed5q77niabkv)[32](#h.ed5q77niabkv)

[PLATFORMS](#h.h5e5tnr64g09)[32](#h.h5e5tnr64g09)

[STACK](#h.t74h72n9e07f)[33](#h.t74h72n9e07f)

[Data Science OKR KPI](#h.9ko8espamhlg)[34](#h.9ko8espamhlg)

[Being a DS / Researcher](#h.85qlgsgt2zvi)[35](#h.85qlgsgt2zvi)

[Team Building / Group Cohesion](#h.ba6x1xyo0qy3)[35](#h.ba6x1xyo0qy3)

[Agile for data-science-research](#h.n1qp8cbathm0)[36](#h.n1qp8cbathm0)

[SOTA AND CURRENT TRENDS SUMMARIES](#h.cf14eeze5t95)[36](#h.cf14eeze5t95)

[YOUTUBE COURSES](#h.9ef4jlaq4am7)[37](#h.9ef4jlaq4am7)

[Deep learning Course](#h.akahfsjyxf4c)[37](#h.akahfsjyxf4c)

[Machine Learning Course](#h.ed8hol4betpe)[37](#h.ed8hol4betpe)

[Predictive Analytics Course](#h.7ua7u2o417fk)[37](#h.7ua7u2o417fk)

[BOOKS & NOTEBOOKS](#h.rx6lagltec2e)[38](#h.rx6lagltec2e)

[COST](#h.4ut08dg2uvia)[38](#h.4ut08dg2uvia)

[Patents](#h.9kfcflke2qg1)[38](#h.9kfcflke2qg1)

[General Advice](#h.4t3gg8pg4iop)[39](#h.4t3gg8pg4iop)

[DATA SCIENCE TOOLS](#h.smqnev4u83o6)[39](#h.smqnev4u83o6)

[Python](#h.bwlsmnb0k1x1)[39](#h.bwlsmnb0k1x1)

[Virtual Environments](#h.ywy1lwitsxq6)[39](#h.ywy1lwitsxq6)

[PYENV](#h.thwc3rcox5z0)[40](#h.thwc3rcox5z0)

[JUPYTER](#h.qz3m1gtoi18e)[41](#h.qz3m1gtoi18e)

[SCIPY](#h.ml7z0ss447mg)[42](#h.ml7z0ss447mg)

[NUMPY](#h.n1i5j1bwflcw)[42](#h.n1i5j1bwflcw)

[PANDAS](#h.ifsqjpvrilj9)[43](#h.ifsqjpvrilj9)

[TIMESERIES](#h.qtd9561x4dch)[44](#h.qtd9561x4dch)

[SCI-KIT LEARN](#h.qhv60c2b1ttn)[45](#h.qhv60c2b1ttn)

[FAST.AI](#h.k7rl40d0bhws)[45](#h.k7rl40d0bhws)

[PYCARET](#h.i66a2kq8nw5x)[46](#h.i66a2kq8nw5x)

[NVIDIA TF CUDA CUDNN](#h.wrmgjlxolns7)[46](#h.wrmgjlxolns7)

[GCP](#h.fnbf816y38vd)[46](#h.fnbf816y38vd)

[SQL](#h.v7jgo1nkd7h8)[46](#h.v7jgo1nkd7h8)

[GIT / Bitbucket](#h.qzopwt5zlcqy)[46](#h.qzopwt5zlcqy)

[MANAGEMENT](#h.qmays8o836vr)[47](#h.qmays8o836vr)

[Style](#h.ulydg1wvwvm0)[47](#h.ulydg1wvwvm0)

[Books](#h.q1200hxhlst4)[47](#h.q1200hxhlst4)

[DATA SCIENCE MANAGEMENT](#h.w9sxubvgreqj)[48](#h.w9sxubvgreqj)

[INTERVIEW Qs](#h.6rrv5du2sr8p)[48](#h.6rrv5du2sr8p)

[Politics](#h.9piqu79q1aq4)[48](#h.9piqu79q1aq4)

[HIRING / RECRUITING](#h.m92e8bgwp3c3)[48](#h.m92e8bgwp3c3)

[WRITING DOCS](#h.wyjqtgavc0rh)[48](#h.wyjqtgavc0rh)

[LEGAL & CONTRACTS](#h.8lwz5gul5vtj)[48](#h.8lwz5gul5vtj)

[CALCULUS](#h.9lk3ceur4n7e)[49](#h.9lk3ceur4n7e)

[PROBABILITY AND STATISTICS](#h.o9xnj6rkklsz)[50](#h.o9xnj6rkklsz)

[Difference between](#h.kf76ngg8tju7)[50](#h.kf76ngg8tju7)

[Introduction to statistics](#h.85qbfkgd0k8)[50](#h.85qbfkgd0k8)

[Introduction to Probability](#h.32yrtswbgy8m)[51](#h.32yrtswbgy8m)

[More on Statistics](#h.a3bnynst1m3s)[51](#h.a3bnynst1m3s)

[Wiki](#h.5mbitrkmcbnz)[51](#h.5mbitrkmcbnz)

[Recommended Courses](#h.qrci82c96fv8)[51](#h.qrci82c96fv8)

[STATISTICAL SAMPLING AND RESAMPLING](#h.ai68616fyu12)[52](#h.ai68616fyu12)

[PROBABILITY](#h.s1p7esk84wxq)[53](#h.s1p7esk84wxq)

[PDF (PROBABILITY DENSITY FUNCTION)](#h.dx7se3uzxr84)[55](#h.dx7se3uzxr84)

[Kernel Density Estimation](#h.9qv0yyo5geqd)[55](#h.9qv0yyo5geqd)

[FEATURE TYPES](#h.f2dadjuugcpn)[56](#h.f2dadjuugcpn)

[FEATURES](#h.iic50ibtj4c8)[57](#h.iic50ibtj4c8)

[CORRELATION](#h.ggji9w2rd1bt)[57](#h.ggji9w2rd1bt)

[CORRELATION VS COVARIANCE](#h.nd0c2zlxmfvi)[57](#h.nd0c2zlxmfvi)

[CORRELATION BETWEEN FEATURE TYPES](#h.cl4usgalvzx9)[57](#h.cl4usgalvzx9)

[CORRELATION VISUALIZATION](#h.lo29xuc0e10i)[59](#h.lo29xuc0e10i)

[PREDICTIVE POWER SCORE (PPS)](#h.jdm5ps4dck4i)[59](#h.jdm5ps4dck4i)

[MUTUAL INFORMATION COEFFICIENT](#h.ij38aucm6zva)[60](#h.ij38aucm6zva)

[CRAMER’S COEFFICIENT](#h.6ycdldexq4n1)[61](#h.6ycdldexq4n1)

[FEATURE SELECTION](#h.k55tk92uook9)[62](#h.k55tk92uook9)

[FEATURE ENGINEERING](#h.3l8h45b9wahd)[64](#h.3l8h45b9wahd)

[REPRESENTATION LEARNING](#h.7b3slo3nojxz)[64](#h.7b3slo3nojxz)

[TFIDF](#h.x4anlkpq6qbc)[64](#h.x4anlkpq6qbc)

[SIMILARITY](#h.eh989qy1ehh2)[65](#h.eh989qy1ehh2)

[FEATURE IMPORTANCE](#h.tossq21au4zp)[65](#h.tossq21au4zp)

[FEATURE IMPUTING](#h.q6ksd7488v2n)[66](#h.q6ksd7488v2n)

[FEATURE STORE](#h.jhysbccx5qf8)[66](#h.jhysbccx5qf8)

[CALIBRATION](#h.wd65l12rlgqy)[68](#h.wd65l12rlgqy)

[Classic Model Calibration](#h.tvvs8ynnvagw)[68](#h.tvvs8ynnvagw)

[NEURAL NET CALIBRATION](#h.z9ok6dl95idj)[69](#h.z9ok6dl95idj)

[MULTI LABEL CLASSIFICATION](#h.xmt6essusy6n)[70](#h.xmt6essusy6n)

[DISTRIBUTION](#h.2ralw4dvnn0g)[71](#h.2ralw4dvnn0g)

[TYPES](#h.c6t45rhv49xw)[71](#h.c6t45rhv49xw)

[Gaussian \ Normal Distribution](#h.7tfhwumn5xbm)[73](#h.7tfhwumn5xbm)

[COMPARING DISTRIBUTIONS](#h.bxfze2xgifm8)[74](#h.bxfze2xgifm8)

[DISTRIBUTION TRANSFORMATION](#h.hqbqsst52nkw)[75](#h.hqbqsst52nkw)

[BOX COX](#h.qexn4sdx5k30)[75](#h.qexn4sdx5k30)

[MANN-WHITNEY U TEST](#h.hzdyn4gp86ae)[77](#h.hzdyn4gp86ae)

[NULL HYPOTHESIS](#h.db6vuzy2ny2h)[77](#h.db6vuzy2ny2h)

[INFORMATION THEORY](#h.8etkr22754ac)[78](#h.8etkr22754ac)

[ENTROPY / INFORMATION GAIN](#h.s66s3rc6vc8r)[78](#h.s66s3rc6vc8r)

[CROSS ENTROPY, RELATIVE ENT, KL-D, JS-D, SOFT MAX](#h.k81zn8r6llwn)[87](#h.k81zn8r6llwn)

[SOFTMAX](#h.urbhz3fh5y0k)[87](#h.urbhz3fh5y0k)

[TIME SERIES ENTROPY](#h.h66ayawt7jf7)[88](#h.h66ayawt7jf7)

[GAME THEORY](#h.anjc8by6g6s9)[89](#h.anjc8by6g6s9)

[DATASETS](#h.1d0bf093jht8)[90](#h.1d0bf093jht8)

[Structured / Unstructured data](#h.4wugmk7f3gjc)[90](#h.4wugmk7f3gjc)

[BIAS / VARIANCE](#h.vor5c3f6ssi8)[90](#h.vor5c3f6ssi8)

[Procedure: crossfold training and validation, or further split 70% to training and validation.](#h.gbkwbobcq8u7)[90](#h.gbkwbobcq8u7)

[SPARSE DATASETS](#h.bg8y242bg430)[94](#h.bg8y242bg430)

[TRAINING METHODOLOGIES](#h.mvypwnntuc8k)[95](#h.mvypwnntuc8k)

[TRANSFER LEARNING](#h.yyrzr8rtqt90)[96](#h.yyrzr8rtqt90)

[TRAIN / TEST / CROSS VALIDATION](#h.8rrmgfpdrecn)[97](#h.8rrmgfpdrecn)

[VARIOUS DATASETS](#h.aagcv0av54hq)[98](#h.aagcv0av54hq)

[IMBALANCED DATASETS](#h.wt6afmrst7rh)[99](#h.wt6afmrst7rh)

[SAMPLE SELECTION](#h.fcj0a3woltqs)[101](#h.fcj0a3woltqs)

[LEARNING CURVES](#h.6g7xciwr9kxa)[102](#h.6g7xciwr9kxa)

[DISTILLING DATA](#h.ogz8rdq95y87)[102](#h.ogz8rdq95y87)

[DATASET SELECTION](#h.onuzv3mdyj0h)[102](#h.onuzv3mdyj0h)

[DATASET CONFIDENCE](#h.eb8efqy6ujp7)[103](#h.eb8efqy6ujp7)

[NORMALIZATION / SCALING](#h.au92ci6vuyez)[104](#h.au92ci6vuyez)

[REGULARIZATION](#h.6cppbx5cppx5)[105](#h.6cppbx5cppx5)

[VALIDATION](#h.ga883xxeqrzz)[108](#h.ga883xxeqrzz)

[DATASETS RELIABILITY & CORRECTNESS](#h.p1efppluycri)[109](#h.p1efppluycri)

[UNIT / DATA TESTS](#h.9tps941du5cj)[109](#h.9tps941du5cj)

[REGULATION FOR AI](#h.fsklkp1xxbjm)[111](#h.fsklkp1xxbjm)

[FAIRNESS, ACCOUNTABILITY & TRANSPARENCY ML](#h.2lg7vnvkmujn)[111](#h.2lg7vnvkmujn)

[FAIRNESS TOOLS](#h.12qxszie3y4y)[111](#h.12qxszie3y4y)

[INTERPRETABLE / EXPLAINABLE AI (XAI)](#h.xs1o8m3ro5iy)[115](#h.xs1o8m3ro5iy)

[WHY WE SHOULDN’T TRUST MODELS](#h.96ljrbp24i7w)[119](#h.96ljrbp24i7w)

[DEBIASING MODELS](#h.bdupj0t5x10u)[120](#h.bdupj0t5x10u)

[PRIVACY](#h.xvdjotjck78t)[121](#h.xvdjotjck78t)

[DIFFERENTIAL PRIVACY](#h.fe8zru6bade1)[122](#h.fe8zru6bade1)

[ANONYMIZATION](#h.9uyf3yr2gtni)[122](#h.9uyf3yr2gtni)

[DE-ANONYMIZATION](#h.n471883ftbpi)[122](#h.n471883ftbpi)

[META-LEARNING](#h.e6t2w36zei75)[122](#h.e6t2w36zei75)

[ML Systems](#h.7idrobzahq7w)[123](#h.7idrobzahq7w)

[Hyper param optimization](#h.c9wtvhi6ccxg)[124](#h.c9wtvhi6ccxg)

[Architecture Search](#h.gy93erqa6zx3)[124](#h.gy93erqa6zx3)

[EXAMPLES](#h.ia1lpecxk4nh)[124](#h.ia1lpecxk4nh)

[NYC taxi pickup problem](#h.ghu9vzn9k49h)[125](#h.ghu9vzn9k49h)

[SURVIVAL ANALYSIS](#h.labckmlfsvdx)[125](#h.labckmlfsvdx)

[PROPAGANDA](#h.xnsloeii8nll)[125](#h.xnsloeii8nll)

[EVALUATION METRICS](#h.ux4usqkacfp7)[126](#h.ux4usqkacfp7)

[A metric learning reality check](#h.9u2po821l2u2)[126](#h.9u2po821l2u2)

[SUPERVISED](#h.50u43avk4057)[126](#h.50u43avk4057)

[Precision \ Recall \ ROC \ AUC](#h.3rbguyjhiygl)[126](#h.3rbguyjhiygl)

[F1 Harmonic Mean Score](#h.8mpspdy52img)[126](#h.8mpspdy52img)

[RECALL, PRECISION AND F1](#h.7uap82op070d)[128](#h.7uap82op070d)

[Recall](#h.lt26p98lv449)[128](#h.lt26p98lv449)

[Precision](#h.sbho164uzp8q)[128](#h.sbho164uzp8q)

[ROC CURVES](#h.b2xqu3q76tfc)[129](#h.b2xqu3q76tfc)

[UNSUPERVISED](#h.g09d6ss1etfu)[130](#h.g09d6ss1etfu)

[BENCHMARKING](#h.drdq3mkrm9o)[130](#h.drdq3mkrm9o)

[HYPER PARAMETER OPTIMIZATION](#h.6vhp5h6s0r3x)[133](#h.6vhp5h6s0r3x)

[Multi CPU Processing](#h.obl7ud50chb8)[133](#h.obl7ud50chb8)

[MONITORING & ALERTS](#h.kdu4ag4h8m8w)[134](#h.kdu4ag4h8m8w)

[Concept drift](#h.ucdr01a4ob3t)[134](#h.ucdr01a4ob3t)

[ALGORITHMS](#h.9vtx4h2xadka)[134](#h.9vtx4h2xadka)

[TRAINING STRATEGIES](#h.f99cbwwlkqbv)[135](#h.f99cbwwlkqbv)

[CLASSIC MACHINE LEARNING](#h.tegm4vhpg5tu)[136](#h.tegm4vhpg5tu)

[ASSOCIATION RULES](#h.qod256c3izez)[136](#h.qod256c3izez)

[Knoldus](#h.f125zob0r3wk)[136](#h.f125zob0r3wk)

[APRIORI](#h.wd3m9cq0483r)[136](#h.wd3m9cq0483r)

[FP Growth](#h.8ytvl4591dvp)[136](#h.8ytvl4591dvp)

[PROBABILISTIC ALGORITHMS](#h.xxx5mlrh8g5k)[137](#h.xxx5mlrh8g5k)

[NAIVE BAYES](#h.cwv3lbwwvzo)[137](#h.cwv3lbwwvzo)

[BAYES, BAYESIAN BELIEF NETWORKS](#h.3mvlo4wg0ilr)[137](#h.3mvlo4wg0ilr)

[MARKOV MODELS](#h.az9h0ctoahft)[138](#h.az9h0ctoahft)

[MARKOV MODELS / HIDDEN MARKOV MODEL](#h.az3g8krlga6b)[140](#h.az3g8krlga6b)

[HMM tutorials](#h.jk7bqgfvr5kh)[140](#h.jk7bqgfvr5kh)

[HMM variants](#h.5palcjbg75q8)[140](#h.5palcjbg75q8)

[INPUT OUTPUT HMM (IOHMM)](#h.waci6i8htxfo)[143](#h.waci6i8htxfo)

[CONDITIONAL RANDOM FIELDS (CRF)](#h.f6y9pwj0blgc)[143](#h.f6y9pwj0blgc)

[REGRESSION ALGORITHMS](#h.sq59ney3d3)[144](#h.sq59ney3d3)

[KERNEL REGRESSION](#h.u5ftjkixgikd)[146](#h.u5ftjkixgikd)

[DIMENSIONALITY REDUCTION](#h.eifqc86vvmk1)[147](#h.eifqc86vvmk1)

[PRINCIPAL COMPONENT REGRESSION (PCR) / PARTIAL LEAST SQUARES (PLS)](#h.h6yoy4rwih2u)[147](#h.h6yoy4rwih2u)

[LABEL ALGORITHMS](#h.oqh41kxuyjhu)[148](#h.oqh41kxuyjhu)

[Label Propagation / Spreading](#h.11a3se8m6buy)[148](#h.11a3se8m6buy)

[CLUSTERING ALGORITHMS](#h.6rhy51v3pmsc)[150](#h.6rhy51v3pmsc)

[Block Modeling - Distance Matrices](#h.z2eplfomyuor)[151](#h.z2eplfomyuor)

[Kmeans](#h.ifaz9gsv7qyk)[151](#h.ifaz9gsv7qyk)

[K-mediods](#h.8apjpd9klhaa)[151](#h.8apjpd9klhaa)

[X-means](#h.xig4hvd28aom)[152](#h.xig4hvd28aom)

[G-means](#h.arxsxves8etl)[152](#h.arxsxves8etl)

[GMM - Gaussian Mixture Models](#h.d315co2y9as4)[154](#h.d315co2y9as4)

[KMEANS++ / Kernel Kmeans](#h.81l3iovlmulg)[155](#h.81l3iovlmulg)

[KNN](#h.m3ooroo11sd5)[155](#h.m3ooroo11sd5)

[DBSCAN](#h.eezbfrgvu76u)[155](#h.eezbfrgvu76u)

[ST-DBSCAN](#h.kv5j1lebcp1k)[156](#h.kv5j1lebcp1k)

[HDBSCAN*](#h.phrbzbp932jj)[156](#h.phrbzbp932jj)

[OPTICS](#h.ao3pf0ssb5tn)[157](#h.ao3pf0ssb5tn)

[SVM CLUSTERING](#h.oy1aurt705o1)[157](#h.oy1aurt705o1)

[COP-CLUSTERING](#h.3yx95sst66xb)[158](#h.3yx95sst66xb)

[ANOMALY DETECTION](#h.mj2v68htxeds)[160](#h.mj2v68htxeds)

[OUTLIER DETECTION](#h.y6mpsp4co5t9)[161](#h.y6mpsp4co5t9)

[ISOLATION FOREST](#h.uritegfkv03w)[165](#h.uritegfkv03w)

[LOCAL OUTLIER FACTOR](#h.qvjx1l5qsshq)[166](#h.qvjx1l5qsshq)

[ELLIPTIC ENVELOPE](#h.h5dacywut0lu)[166](#h.h5dacywut0lu)

[ONE CLASS SVM](#h.3f78a2uobtqj)[166](#h.3f78a2uobtqj)

[CLUSTERING METRICS](#h.rmcd587c6iy7)[167](#h.rmcd587c6iy7)

[DECISION TREES](#h.fu6suursb7t5)[167](#h.fu6suursb7t5)

[CART TREES](#h.3tjhtu9fcfhj)[168](#h.3tjhtu9fcfhj)

[KDTREE](#h.ohb8iaccz1to)[168](#h.ohb8iaccz1to)

[RANDOM FOREST](#h.2ulvxqfveva8)[168](#h.2ulvxqfveva8)

[EXTRA TREES](#h.m4880zbp27so)[168](#h.m4880zbp27so)

[ACTIVE LEARNING ALGORITHMS](#h.rxemiwr2wjwh)[170](#h.rxemiwr2wjwh)

[PASSIVE AGGRESSIVE CLASSIFIER](#h.st27jnx5o8fg)[170](#h.st27jnx5o8fg)

[LINEAR SEPARATOR ALGORITHMS](#h.bkmhgtb2vmn1)[171](#h.bkmhgtb2vmn1)

[SEQUENTIAL MINIMAL OPTIMIZATION (SMO)](#h.c4ven7mnxwes)[171](#h.c4ven7mnxwes)

[SUPPORT VECTOR MACHINES (SVM)](#h.9fzehuav7zus)[171](#h.9fzehuav7zus)

[MULTI CLASS SVM](#h.rouk19nbvob9)[171](#h.rouk19nbvob9)

[Regularization and influence](#h.55cud8vqp17e)[173](#h.55cud8vqp17e)

[SUPPORT VECTOR REGRESSION (SVR)](#h.yqi6h13tlpl9)[173](#h.yqi6h13tlpl9)

[LibSVM vs LibLinear](#h.h038kph1c2j0)[173](#h.h038kph1c2j0)

[Support vector clustering (SVC)](#h.t9wxzg6vvlak)[174](#h.t9wxzg6vvlak)

[KERNELS](#h.ihcpsp5rdrow)[174](#h.ihcpsp5rdrow)

[Intuition for regularization in SVM](#h.cf8dnpzd2w3l)[176](#h.cf8dnpzd2w3l)

[Overfitting advice for SVM:](#h.6zl033bzjy47)[176](#h.6zl033bzjy47)

[RBF kernel use cases](#h.ga9p2d66igwt)[177](#h.ga9p2d66igwt)

[ENSEMBLES](#h.ugf47xmdj9vc)[177](#h.ugf47xmdj9vc)

[Ensembles in WEKA](#h.hliglw4se8d)[179](#h.hliglw4se8d)

[BAGGING - bootstrap aggregating](#h.2q1bzut18v9e)[180](#h.2q1bzut18v9e)

[BOOSTING](#h.wfdarqqaveww)[180](#h.wfdarqqaveww)

[XGBOOST](#h.b4jz8ldut0xy)[182](#h.b4jz8ldut0xy)

[Gradient Boosting Classifier](#h.7ij484asu0kc)[186](#h.7ij484asu0kc)

[REINFORCEMENT LEARNING](#h.ewlf017tmp9h)[187](#h.ewlf017tmp9h)

[Q-LEARN](#h.vyt33186mbgl)[187](#h.vyt33186mbgl)

[RL IN DL](#h.39zgj3aagj17)[187](#h.39zgj3aagj17)

[INCREMENTAL LEARNING](#h.nit7xafllqyo)[188](#h.nit7xafllqyo)

[HOEFFDING TREE](#h.x6p97rvhkdsx)[188](#h.x6p97rvhkdsx)

[DIMENSIONALITY REDUCTION METHODS](#h.cw5tiajapln4)[190](#h.cw5tiajapln4)

[TSNE](#h.bb0cc7cf37ur)[190](#h.bb0cc7cf37ur)

[PCA](#h.3awqixjyzw8y)[192](#h.3awqixjyzw8y)

[SVD](#h.j4qrhtyn74xb)[192](#h.j4qrhtyn74xb)

[KPCA](#h.y2ockk5s7gmb)[193](#h.y2ockk5s7gmb)

[LDA - Linear discriminant analysis](#h.mc5td3vuxeal)[195](#h.mc5td3vuxeal)

[KDA - KERNEL DISCRIMINANT ANALYSIS](#h.yj504or3ht7p)[197](#h.yj504or3ht7p)

[LSA](#h.9u5bljcvtvao)[197](#h.9u5bljcvtvao)

[ICA](#h.dvf3un43m15x)[199](#h.dvf3un43m15x)

[MANIFOLD](#h.fwdstppv00q6)[199](#h.fwdstppv00q6)

[T-SNE](#h.iersx9dfig4t)[200](#h.iersx9dfig4t)

[Sammons embedding mapping](#h.1diqbwue6158)[200](#h.1diqbwue6158)

[IVIS](#h.nrhb0hajrez3)[200](#h.nrhb0hajrez3)

[GENETIC ALGORITHMS / PROGRAMMING](#h.bb2gnvbj8r5h)[201](#h.bb2gnvbj8r5h)

[LEARNING CLASSIFIER SYSTEMS](#h.dozcutml6td9)[203](#h.dozcutml6td9)

[LCS](#h.vgmk099o4938)[203](#h.vgmk099o4938)

[XCS](#h.hdbgeebyly9x)[203](#h.hdbgeebyly9x)

[Recommender Algorithms](#h.qolla5sjaqf5)[204](#h.qolla5sjaqf5)

[TOOLS](#h.f1ay54kvc68b)[204](#h.f1ay54kvc68b)

[TEMPLATIZATION](#h.8lc53bi9v2kx)[205](#h.8lc53bi9v2kx)

[Logpai](#h.tb845gw3ql4y)[206](#h.tb845gw3ql4y)

[Metrics](#h.teag5fn8dqng)[212](#h.teag5fn8dqng)

[Tools and Benchmarks for Automated Log Parsing](#h.scnugfa0prlo)[212](#h.scnugfa0prlo)

[TIME SERIES](#h.j1zjk0nbc2am)[217](#h.j1zjk0nbc2am)

[TOOLS](#h.8mfu3xy21ivo)[217](#h.8mfu3xy21ivo)

[Forecasting methods](#h.7vv74nwlga3u)[221](#h.7vv74nwlga3u)

[Data Transformations](#h.4ldexeh4fq6e)[221](#h.4ldexeh4fq6e)

[SPLITTING TIME SERIES DATA](#h.ttc8d46q8p8q)[221](#h.ttc8d46q8p8q)

[Evaluate forecast accuracy](#h.ha94w715jjud)[221](#h.ha94w715jjud)

[Rolling window analysis](#h.1ady7v99y1bx)[222](#h.1ady7v99y1bx)

[Moving average window](#h.jswu4cx8sfwd)[222](#h.jswu4cx8sfwd)

[Decomposition](#h.h3dfhcvx3j8x)[222](#h.h3dfhcvx3j8x)

[Weighted “window”](#h.ev2305vbjve8)[223](#h.ev2305vbjve8)

[Time Series Components](#h.j2w600bp845y)[223](#h.j2w600bp845y)

[STATIONARY TIME SERIES](#h.lc8zaxdbf9va)[225](#h.lc8zaxdbf9va)

[SHORT TIME SERIES](#h.l7b39xfisa2j)[225](#h.l7b39xfisa2j)

[Kalman filters in matlab](#h.dochrcee0oek)[226](#h.dochrcee0oek)

[LTSM for time series](#h.1tcaigkmfjkw)[226](#h.1tcaigkmfjkw)

[CLASSIFICATION](#h.y19rg1p3lh2j)[226](#h.y19rg1p3lh2j)

[CLUSTERING TS](#h.76f635z85jke)[227](#h.76f635z85jke)

[ANOMALY DETECTION TS](#h.anhu8xnvreks)[227](#h.anhu8xnvreks)

[Dynamic Time Warping (DTW)](#h.xsp20kw0xwhu)[229](#h.xsp20kw0xwhu)

[FOURIER TRANSFORM](#h.fsj3x1xret9n)[231](#h.fsj3x1xret9n)

[Digital Signal Processing (DSP)](#h.va4awx9z608y)[231](#h.va4awx9z608y)

[Graph Theory](#h.h3x3i4zhylgf)[231](#h.h3x3i4zhylgf)

[SOCIAL NETWORK ANALYSIS](#h.fcxfqbonc560)[233](#h.fcxfqbonc560)

[(DEEP) NEURAL NETS](#h.juynspp6jid3)[234](#h.juynspp6jid3)

[GRADIENT DESCENT](#h.510bolvjhyow)[237](#h.510bolvjhyow)

[Stochastic](#h.o70c8voep6x1)[237](#h.o70c8voep6x1)

[Batch](#h.9r7p0m5k5mmx)[237](#h.9r7p0m5k5mmx)

[Mini batch (most common)](#h.e4enh4woqioi)[237](#h.e4enh4woqioi)

[Batch size](#h.rxfo1qi0ww6n)[239](#h.rxfo1qi0ww6n)

[BIAS](#h.kfez6px1vkkn)[242](#h.kfez6px1vkkn)

[BATCH NORMALIZATION](#h.f95thkv2q1oz)[243](#h.f95thkv2q1oz)

[HYPER PARAM GRID SEARCHES](#h.pyoa1p2hvn0u)[246](#h.pyoa1p2hvn0u)

[LOSS](#h.dyz5w5m50f6d)[246](#h.dyz5w5m50f6d)

[Early stopping](#h.fj7ao1u7njqw)[247](#h.fj7ao1u7njqw)

[LEARNING RATE REDUCTION](#h.zhzqjvazkm3m)[249](#h.zhzqjvazkm3m)

[TRAIN / VAL accuracy in NN](#h.svxzpgynjr1u)[252](#h.svxzpgynjr1u)

[INITIALIZERS](#h.shaucrenh8ez)[252](#h.shaucrenh8ez)

[ACTIVATION FUNCTIONS](#h.7vkd31956ai1)[254](#h.7vkd31956ai1)

[OPTIMIZERS](#h.udplf3kgkq3e)[254](#h.udplf3kgkq3e)

[DROPOUT LAYERS IN KERAS AND GENERAL](#h.ivfkev2webzh)[257](#h.ivfkev2webzh)

[NEURAL NETWORK OPTIMIZATION TECHNIQUES](#h.cakgia26att)[259](#h.cakgia26att)

[Fine tuning](#h.m49puc34uumc)[259](#h.m49puc34uumc)

[Deep Learning for NLP](#h.megb4xxyxoqh)[259](#h.megb4xxyxoqh)

[MULTI LABEL/OUTPUT](#h.2mb0w7xngzud)[260](#h.2mb0w7xngzud)

[FUZZY MULTI LABEL](#h.ev6tb4jjh0vi)[260](#h.ev6tb4jjh0vi)

[DNN FRAMEWORKS](#h.10l82uyqij69)[260](#h.10l82uyqij69)

[PYTORCH](#h.nl4z9yfrmywa)[261](#h.nl4z9yfrmywa)

[FAST.AI](#h.f09bh55nlbk9)[261](#h.f09bh55nlbk9)

[KERAS](#h.xxuevd6lcboa)[261](#h.xxuevd6lcboa)

[KERAS MULTI GPU](#h.ax0ma0vxt0ux)[263](#h.ax0ma0vxt0ux)

[KERAS FUNCTIONAL API](#h.6grcx723g9m0)[263](#h.6grcx723g9m0)

[KERAS EMBEDDING LAYER](#h.7jjdm7sdfnsn)[264](#h.7jjdm7sdfnsn)

[Keras: Predict vs Evaluate](#h.y036d2ql04xe)[264](#h.y036d2ql04xe)

[Keras metrics](#h.v9olfursks0m)[264](#h.v9olfursks0m)

[LOSS IN KERAS](#h.dppn5wsja6n5)[265](#h.dppn5wsja6n5)

[DNN ALGORITHMS](#h.47owvi4dz2w7)[268](#h.47owvi4dz2w7)

[AUTOENCODERS](#h.vyvi3fhzyxd3)[268](#h.vyvi3fhzyxd3)

[Variational AE](#h.vefs471ceara)[268](#h.vefs471ceara)

[SELF ORGANIZING MAPS (SOM)](#h.dy4wf2940c8)[269](#h.dy4wf2940c8)

[NEURO EVOLUTION (GA/GP based)](#h.piwkrgq88i6c)[271](#h.piwkrgq88i6c)

[NEAT](#h.seimkb6l5pqi)[271](#h.seimkb6l5pqi)

[HYPER-NEAT](#h.ukl3a4s4z80l)[271](#h.ukl3a4s4z80l)

[Radial Basis Function Network (RBFN)](#h.txe53pe6i239)[273](#h.txe53pe6i239)

[Bayesian Neural Network (BNN)](#h.slqfz2k65bd2)[274](#h.slqfz2k65bd2)

[CONVOLUTIONAL NEURAL NET](#h.yfl07avblwwl)[277](#h.yfl07avblwwl)

[CONV-1D](#h.ob06u2rju5qm)[278](#h.ob06u2rju5qm)

[1x1 CNN](#h.8frdil3xvn8t)[279](#h.8frdil3xvn8t)

[MASKED R-CNN](#h.hlatmnxg5569)[279](#h.hlatmnxg5569)

[Invariance in CNN](#h.vs1grj91ch1u)[279](#h.vs1grj91ch1u)

[MAX AVERAGE POOLING](#h.4qzme945k0z)[279](#h.4qzme945k0z)

[Dilated CNN](#h.qo922pbgw0db)[280](#h.qo922pbgw0db)

[RESNET, DENSENET UNET](#h.9rfa4yxm3nyv)[280](#h.9rfa4yxm3nyv)

[Graph Convolutional Networks](#h.r4j90wee8n0o)[281](#h.r4j90wee8n0o)

[CAPSULE NEURAL NETS](#h.e3jylcfsm7su)[281](#h.e3jylcfsm7su)

[Transfer Learning using CNN](#h.anpi6fhahsrl)[281](#h.anpi6fhahsrl)

[VISUALIZE CNN](#h.65mk3nxhpp9e)[281](#h.65mk3nxhpp9e)

[Recurrent Neural Net (RNN)](#h.exhy1jusvryp)[282](#h.exhy1jusvryp)

[LSTM](#h.loy5amwdfjvg)[282](#h.loy5amwdfjvg)

[BIDIRECTIONAL LSTM](#h.imcindmqkgor)[287](#h.imcindmqkgor)

[UNSUPERVISED LSTM](#h.tk74gs3l1x4w)[287](#h.tk74gs3l1x4w)

[GRU](#h.v3egkb320k6m)[287](#h.v3egkb320k6m)

[RECURRENT WEIGHTED AVERAGE (RNN-WA)](#h.2h69qeaf6y38)[288](#h.2h69qeaf6y38)

[QRNN](#h.qe1prp1gc071)[288](#h.qe1prp1gc071)

[GRAPH NEURAL NETWORKS (GNN)](#h.z9dg2sos3gk5)[289](#h.z9dg2sos3gk5)

[Deep walk](#h.um4cozbwspme)[289](#h.um4cozbwspme)

[Node2vec](#h.cnsulnno74bg)[289](#h.cnsulnno74bg)

[Graphsage](#h.h82qwkunmrr2)[289](#h.h82qwkunmrr2)

[SDNE - structural deep network embedding](#h.2po2fw963a9u)[290](#h.2po2fw963a9u)

[Diff2vec](#h.ukzo2ewvzfd4)[290](#h.ukzo2ewvzfd4)

[Splitter](#h.xf1cxiy20krq)[290](#h.xf1cxiy20krq)

[Nodevectors](#h.exbyd9drseiv)[292](#h.exbyd9drseiv)

[SIGNAL PROCESSING NN (FFT, WAVELETS, SHAPELETS)](#h.nrkaqmodn72c)[292](#h.nrkaqmodn72c)

[HIERARCHICAL RNN](#h.susigruixnzd)[292](#h.susigruixnzd)

[NN-Sequence Analysis](#h.ut68bet557wo)[293](#h.ut68bet557wo)

[SIAMESE NETWORKS (one shot)](#h.aj08ncoq7skq)[293](#h.aj08ncoq7skq)

[MULTI NETWORKS](#h.8vgpcchn92pe)[293](#h.8vgpcchn92pe)

[OPTIMIZING NEURAL NETS](#h.s7pcc0paylge)[293](#h.s7pcc0paylge)

[PRUNING / KNOWLEDGE DISTILLATION / LOTTERY TICKET](#h.k5rm4ycc2bbv)[293](#h.k5rm4ycc2bbv)

[Troubleshooting Neural Nets](#h.qhqjkjlx8vxn)[295](#h.qhqjkjlx8vxn)

[Dataset Issues](#h.vwb6ll86y04e)[295](#h.vwb6ll86y04e)

[Data Normalization/Augmentation](#h.apzjxm3olz8b)[295](#h.apzjxm3olz8b)

[Implementation issues](#h.p1dh5af2vwly)[296](#h.p1dh5af2vwly)

[Training issues](#h.jn9edbfq4zhs)[296](#h.jn9edbfq4zhs)

[EMBEDDINGS](#h.bybbrqiwtrxc)[297](#h.bybbrqiwtrxc)

[TOOLS](#h.o2j1ldfd9h52)[298](#h.o2j1ldfd9h52)

[FLAIR](#h.40potmrzdaix)[298](#h.40potmrzdaix)

[HUGGING FACE](#h.r5fofji913wd)[298](#h.r5fofji913wd)

[LANGUAGE EMBEDDINGS](#h.jn5us8sxh4vp)[299](#h.jn5us8sxh4vp)

[Language modelling](#h.vve9uv60uucf)[300](#h.vve9uv60uucf)

[Embedding spaces](#h.3j81ok8jay9)[301](#h.3j81ok8jay9)

[Cat2vec](#h.37cowzs0at6g)[302](#h.37cowzs0at6g)

[ENTITY EMBEDDINGS](#h.iatgah4zy83t)[303](#h.iatgah4zy83t)

[ALL2VEC EMBEDDINGS](#h.c0ml6cs4qs3h)[305](#h.c0ml6cs4qs3h)

[WORD EMBEDDINGS](#h.7ywnesi01pjj)[306](#h.7ywnesi01pjj)

[FastText](#h.lvk9528cp2t6)[306](#h.lvk9528cp2t6)

[WORD2VEC](#h.lek91wid72cf)[308](#h.lek91wid72cf)

[GLOVE](#h.3a9iqwgdo8cj)[310](#h.3a9iqwgdo8cj)

[SENTENCE EMBEDDING](#h.y4htdv2ghoib)[311](#h.y4htdv2ghoib)

[Sense2vec](#h.u2rlkcjz60un)[311](#h.u2rlkcjz60un)

[SENT2VEC aka “skip-thoughts”](#h.qfk154k0t5q2)[311](#h.qfk154k0t5q2)

[USE - Universal sentence encoder](#h.3ke4nq897wsu)[311](#h.3ke4nq897wsu)

[BERT+W2V](#h.1nrcj3tdlhez)[311](#h.1nrcj3tdlhez)

[PARAGRAPH EMBEDDING](#h.8gcjosg1bvyo)[311](#h.8gcjosg1bvyo)

[DOCUMENT EMBEDDING](#h.s03a43dkvazg)[311](#h.s03a43dkvazg)

[DOC2VEC](#h.y2w3wddew1s9)[311](#h.y2w3wddew1s9)

[ATTENTION](#h.pvgpm6icu25e)[311](#h.pvgpm6icu25e)

[BERT/ROBERTA](#h.gea0q49cwlb)[314](#h.gea0q49cwlb)

[TRANSFORMERS](#h.hhz5jnlkgvz3)[315](#h.hhz5jnlkgvz3)

[ELMO](#h.oijx13ugld3y)[316](#h.oijx13ugld3y)

[ULMFIT](#h.i5lpbqoczyxx)[317](#h.i5lpbqoczyxx)

[BERT](#h.ex7jb9p63a1)[317](#h.ex7jb9p63a1)

[GPT2](#h.3nj7f2i3nxyj)[320](#h.3nj7f2i3nxyj)

[GPT3](#h.i6mwasrlcmjy)[322](#h.i6mwasrlcmjy)

[XLNET](#h.81pk036m8ib8)[323](#h.81pk036m8ib8)

[CLIP](#h.n10obx2dfl8)[323](#h.n10obx2dfl8)

[Adversarial methodologies](#h.hcq30naqb1af)[324](#h.hcq30naqb1af)

[GAN](#h.6c9rgajn64iq)[324](#h.6c9rgajn64iq)

[SIAMESE NETWORKS](#h.4ehsyog2kjhv)[327](#h.4ehsyog2kjhv)

[NLP - NATURAL LANGUAGE PROCESSING](#h.kxrwwyo6zmpd)[328](#h.kxrwwyo6zmpd)

[NLP - a reality check](#h.mx4qv57rvqga)[328](#h.mx4qv57rvqga)

[TOOLS](#h.vxnv7cloe34b)[328](#h.vxnv7cloe34b)

[SPACY](#h.jq95vdy7m0vk)[328](#h.jq95vdy7m0vk)

[NLP embedding repositories](#h.htgu962s0uyn)[329](#h.htgu962s0uyn)

[NLP DATASETS](#h.uicw9fyuv8l)[329](#h.uicw9fyuv8l)

[NLP Libraries](#h.v6othfn6pt7u)[329](#h.v6othfn6pt7u)

[Multilingual models](#h.stpojxivwzld)[329](#h.stpojxivwzld)

[Augmenting text in NLP](#h.16z8jh1hxy7g)[329](#h.16z8jh1hxy7g)

[TF-IDF](#h.j6unoy3tejv8)[329](#h.j6unoy3tejv8)

[Sparse textual content](#h.1ma8oxog6fj)[330](#h.1ma8oxog6fj)

[Basic nlp](#h.e59147afntc2)[330](#h.e59147afntc2)

[Chunking](#h.gxbpsz9btmnc)[331](#h.gxbpsz9btmnc)

[NLP for hackers tutorials](#h.otw0xow31o03)[331](#h.otw0xow31o03)

[Synonyms](#h.rz8yky9b3ngb)[332](#h.rz8yky9b3ngb)

[ANNOTATION](#h.qxux1r42scm9)[334](#h.qxux1r42scm9)

[7 myths of annotation](#h.itlgtx1e90un)[337](#h.itlgtx1e90un)

[Crowd Sourcing](#h.ecmz0fg4g7mf)[337](#h.ecmz0fg4g7mf)

[Inter agreement](#h.2glkfoynjv54)[339](#h.2glkfoynjv54)

[Cohens kappa (two people)](#h.jfyqjgruaw0d)[340](#h.jfyqjgruaw0d)

[Fleiss’ kappa, from 3 people and above.](#h.h2hpuxy5s7qo)[340](#h.h2hpuxy5s7qo)

[Krippendorfs alpha](#h.gviq7l5qaq7)[340](#h.gviq7l5qaq7)

[MACE - the new kid on the block. -](#h.v79emved71bq)[341](#h.v79emved71bq)

[Calculating agreement](#h.85mcuqfm1mv5)[341](#h.85mcuqfm1mv5)

[Machine Vision annotation](#h.5eu3tnwd5crs)[342](#h.5eu3tnwd5crs)

[Troubling shooting agreement metrics](#h.fjh289mvusip)[342](#h.fjh289mvusip)

[CONVOLUTION NEURAL NETS (CNN)](#h.1ovz1slix9w4)[343](#h.1ovz1slix9w4)

[KNOWLEDGE GRAPHS](#h.uwbgwz5ugeiv)[343](#h.uwbgwz5ugeiv)

[SUMMARIZATION](#h.7089oga62ron)[345](#h.7089oga62ron)

[Abstractive](#h.938yzt5pn98w)[345](#h.938yzt5pn98w)

[Keywords extraction](#h.zg57rvvar8oy)[346](#h.zg57rvvar8oy)

[Extractive summarization](#h.z5ifo4rpysg8)[346](#h.z5ifo4rpysg8)

[SENTIMENT ANALYSIS](#h.6iitchih8kpc)[347](#h.6iitchih8kpc)

[Databases](#h.11ntsewbio5w)[347](#h.11ntsewbio5w)

[Tools](#h.5u4fse7s0ug)[347](#h.5u4fse7s0ug)

[Ground Truth](#h.mvmlemybsx3v)[347](#h.mvmlemybsx3v)

[TOPIC MODELING](#h.od34mmsljo9t)[350](#h.od34mmsljo9t)

[(TopSBM) topic block modeling](#h.xt5frl1lm4pr)[351](#h.xt5frl1lm4pr)

[(LDA) Latent Dirichlet Allocation](#h.q8e2mzlslbub)[351](#h.q8e2mzlslbub)

[COHERENCE](#h.l89x3sqyypq3)[359](#h.l89x3sqyypq3)

[Non-negative Matrix factorization (NMF)](#h.he05ijwue50s)[360](#h.he05ijwue50s)

[LDA2VEC](#h.vwbj8adk9ixi)[360](#h.vwbj8adk9ixi)

[TOP2VEC](#h.a9aopbqt8745)[360](#h.a9aopbqt8745)

[NAMED ENTITY RECOGNITION (NER)](#h.l0w044kp3h4n)[362](#h.l0w044kp3h4n)

[Stanford NER (SNER)](#h.203othe76j2)[364](#h.203othe76j2)

[Spacy & Others](#h.tud9v6wdwho7)[364](#h.tud9v6wdwho7)

[SEARCH](#h.8uphyifq8vrp)[365](#h.8uphyifq8vrp)

[SEQ2SEQ SEQUENCE TO SEQUENCE](#h.bri1owrekmka)[366](#h.bri1owrekmka)

[QUESTION ANSWERING](#h.x0njssx9819k)[367](#h.x0njssx9819k)

[LANGUAGE MODELS](#h.gff72j64ym58)[367](#h.gff72j64ym58)

[NEURAL LANGUAGE GENERATION](#h.cd97nw20phue)[367](#h.cd97nw20phue)

[LANGUAGE DETECTION / IDENTIFICATION](#h.5l7718r2vj4y)[368](#h.5l7718r2vj4y)

[LANGUAGE TRANSLATION](#h.j30bhxp2urw4)[371](#h.j30bhxp2urw4)

[CHAT BOTS](#h.2lilhtmd1inb)[371](#h.2lilhtmd1inb)

[STRING MATCHING](#h.sqs76fgdm1d5)[372](#h.sqs76fgdm1d5)

[REGEX](#h.teux1ct3jogk)[372](#h.teux1ct3jogk)

[DEEP MACHINE VISION](#h.b179ir33ssrn)[374](#h.b179ir33ssrn)

[TOOLS](#h.hjrw10n91uj6)[374](#h.hjrw10n91uj6)

[SUPER RESOLUTION](#h.h9yy83qqxupl)[374](#h.h9yy83qqxupl)

[DETECTION](#h.ryv8ykf4u3rv)[374](#h.ryv8ykf4u3rv)

[RECOGNITION](#h.vs512wfj6wz4)[376](#h.vs512wfj6wz4)

[DEEP AUDIO](#h.k9bumwu2lojb)[376](#h.k9bumwu2lojb)

[ROOT CAUSE EFFECT](#h.plc1suiaz3z7)[377](#h.plc1suiaz3z7)

[FULL STACK & OPS](#h.mbqjhhaqssp3)[378](#h.mbqjhhaqssp3)

[Literature](#h.klvtzzr0rnlt)[378](#h.klvtzzr0rnlt)

[DESIGN PATTERNS](#h.j27rg4t7xyq)[379](#h.j27rg4t7xyq)

[Software and architectural design patterns](#h.i4ozr8pfn0rv)[379](#h.i4ozr8pfn0rv)

[System Design and architecture](#h.mmfeps5cupx8)[379](#h.mmfeps5cupx8)

[CONTINUOUS INTEGRATION](#h.82dk90adnqv7)[380](#h.82dk90adnqv7)

[PACKAGE REPOSITORIES](#h.21fvsnm758p4)[380](#h.21fvsnm758p4)

[DEVOPS / SRE](#h.v80t5wmbuq1)[380](#h.v80t5wmbuq1)

[PMML](#h.it6jrgrvvnm9)[381](#h.it6jrgrvvnm9)

[Cap theorem](#h.t517l3y7ntdd)[381](#h.t517l3y7ntdd)

[Docker](#h.i76u8sbfzfn2)[381](#h.i76u8sbfzfn2)

[GIT REPOSITORIES](#h.q2x4y92ysik8)[381](#h.q2x4y92ysik8)

[Kubernetes](#h.5c0lo3n7dzs0)[381](#h.5c0lo3n7dzs0)

[Helm](#h.h7ig92zfb0y3)[382](#h.h7ig92zfb0y3)

[Kubeflow](#h.7ejcsteaugl6)[382](#h.7ejcsteaugl6)

[MiniKF](#h.o4vkz5lfy413)[382](#h.o4vkz5lfy413)

[S2i](#h.4cn2mrvezcer)[382](#h.4cn2mrvezcer)

[Seldon](#h.i1hjycggewcn)[382](#h.i1hjycggewcn)

[Tutorials](#h.mynip6seyfm6)[382](#h.mynip6seyfm6)

[AWS Lambda](#h.kijow1yos6xh)[383](#h.kijow1yos6xh)

[rabbitMQ](#h.795ncknjp3xe)[383](#h.795ncknjp3xe)

[ActiveMQ](#h.a1uhvhqnsgpn)[383](#h.a1uhvhqnsgpn)

[Kafka](#h.xj0oxu3tmr5h)[383](#h.xj0oxu3tmr5h)

[Zoo keeper](#h.cjd29rkql168)[384](#h.cjd29rkql168)

[ELK](#h.j7tjemttfwf2)[384](#h.j7tjemttfwf2)

[Logz.io](#h.wjfh59egcavs)[384](#h.wjfh59egcavs)

[Sentry](#h.5htcf4vtyza0)[384](#h.5htcf4vtyza0)

[Kafka for DS](#h.glb3daueaqbg)[384](#h.glb3daueaqbg)

[Redis for DS](#h.con8i4k8jwp)[384](#h.con8i4k8jwp)

[Statsd](#h.ouje1jsprj27)[385](#h.ouje1jsprj27)

[FastAPI](#h.5sepgvv7oo6w)[385](#h.5sepgvv7oo6w)

[SnowFlake / Redshift](#h.fa4tjwh6fgcm)[385](#h.fa4tjwh6fgcm)

[Programming Concepts](#h.eeytbxmss10l)[385](#h.eeytbxmss10l)

[Visualization](#h.l3t4yn8zpamt)[385](#h.l3t4yn8zpamt)

[Serving Models](#h.lqg1hydojlei)[385](#h.lqg1hydojlei)

[MLOPS](#h.d7q6a4wlni1f)[386](#h.d7q6a4wlni1f)

[EXPERIMENT MANAGEMENT](#h.f0gbilabjm8q)[388](#h.f0gbilabjm8q)

[MARKETING](#h.awwvo1d8r2au)[389](#h.awwvo1d8r2au)

[PRODUCT](#h.jkv635psdxx1)[391](#h.jkv635psdxx1)

[Books](#h.bq7238ygbj6t)[391](#h.bq7238ygbj6t)

[GENERAL](#h.yzw88mwo99n3)[391](#h.yzw88mwo99n3)

[NORTH STAR METRIC](#h.iy9j0x7khpx2)[392](#h.iy9j0x7khpx2)

[Product Market Fit](#h.57abv6s0s98e)[392](#h.57abv6s0s98e)

[Beginner reading list](#h.46ogumfnbx3f)[394](#h.46ogumfnbx3f)

[Advanced reading list](#h.13y2i97x9ep8)[394](#h.13y2i97x9ep8)

[TOOLS](#h.s4vl8qf6uzdj)[394](#h.s4vl8qf6uzdj)

[UX USER EXPERIENCE](#h.veatj74wgi78)[395](#h.veatj74wgi78)

[HUMOR](#h.uvzle9r9umy1)[396](#h.uvzle9r9umy1)

[END](#h.3tl3ttx4f4sq)[397](#h.3tl3ttx4f4sq)

* * *

TYPES OF MACHINE LEARNING
=========================

![](images/image7.png)

[A wonderful introduction into machine learning, and how to choose the right algorithm or family of algorithms for the task at hand.](https://www.google.com/url?q=https://blogs.sas.com/content/subconsciousmusings/2017/04/12/machine-learning-algorithm-use/?utm_source%3Dfacebook%26utm_medium%3Dcpc%26utm_campaign%3Danalytics-global%26utm_content%3DUS_interests-conversions&sa=D&source=editors&ust=1621930681777000&usg=AOvVaw0xFR7TGikyEQnLYF3jImmv)

VARIOUS MODEL FAMILIES
----------------------

[Stanford cs221](https://www.google.com/url?q=https://stanford.edu/~shervine/teaching/cs-221/&sa=D&source=editors&ust=1621930681778000&usg=AOvVaw0qrYCh8bcnvCJrzpl8QMcT) \- reflex, variable, state, logic

* * *

WEAKLY SUPERVISED
-----------------

1.  [Text classification with extremely small datasets](https://www.google.com/url?q=https://towardsdatascience.com/text-classification-with-extremely-small-datasets-333d322caee2&sa=D&source=editors&ust=1621930681779000&usg=AOvVaw3C4LvAQvTJz3m5ctrUP9a1), relies heavily on feature engineering methods such as number of hashtags, number of punctuations and other insights that are really good for this type of text.
2.  A great [review paper](https://www.google.com/url?q=https://pdfs.semanticscholar.org/3adc/fd254b271bcc2fb7e2a62d750db17e6c2c08.pdf&sa=D&source=editors&ust=1621930681780000&usg=AOvVaw30xAAhPpdYKgJH82rsD6ux) for weakly supervision, discusses:

1.  Incomplete supervision
2.  Inaccurate
3.  Inexact
4.  Active learning

3.  [Stanford on](https://www.google.com/url?q=https://dawn.cs.stanford.edu/2017/07/16/weak-supervision/&sa=D&source=editors&ust=1621930681781000&usg=AOvVaw1NdJHHhvSwtY93CCfj4G7V) weakly
4.  [Stanford ai on snorkel](https://www.google.com/url?q=http://ai.stanford.edu/blog/weak-supervision/&sa=D&source=editors&ust=1621930681781000&usg=AOvVaw2k5XqeqAqHA63PalvEgqvZ)
5.  [Hazy research on weak and snorkel](https://www.google.com/url?q=https://hazyresearch.github.io/snorkel/blog/ws_blog_post.html&sa=D&source=editors&ust=1621930681782000&usg=AOvVaw1wio4yQMWWZrU_PrCDwMvt)
6.  [Out of distribution generalization using test-time training](https://www.google.com/url?q=https://arxiv.org/abs/1909.13231&sa=D&source=editors&ust=1621930681782000&usg=AOvVaw0t0SM4f2G30WJwyKc2SCP5)\- Test-time training turns a single unlabeled test instance into a self-supervised learning problem, on which we update the model parameters before making a prediction on this instance.
7.  [Learning Deep Networks from Noisy Labels with Dropout Regularization](https://www.google.com/url?q=https://arxiv.org/pdf/1705.03419.pdf&sa=D&source=editors&ust=1621930681783000&usg=AOvVaw2HVglvboFFEuGYGVxF_i_1) \- Large datasets often have unreliable labels—such as those obtained from Amazon’s Mechanical Turk or social media platforms—and classifiers trained on mislabeled datasets often exhibit poor performance. We present a simple, effective technique for accounting for label noise when training deep neural networks. We augment a standard deep network with a softmax layer that models the label noise statistics. Then, we train the deep network and noise model jointly via end-to-end stochastic gradient descent on the (perhaps mislabeled) dataset. The augmented model is overdetermined, so in order to encourage the learning of a non-trivial noise model, we apply dropout regularization to the weights of the noise model during training. Numerical experiments on noisy versions of the CIFAR-10 and MNIST datasets show that the proposed dropout technique outperforms state-of-the-art methods.
8.  [Distill to label weakly supervised instance labeling using knowledge distillation](https://www.google.com/url?q=https://arxiv.org/pdf/1907.12926.pdf&sa=D&source=editors&ust=1621930681783000&usg=AOvVaw2rIAbPcT_WsKH5jYPkFfVT) \- “Weakly supervised instance labeling using only image-level labels, in lieu of expensive fine-grained pixel annotations, is crucial in several applications including medical image analysis. In contrast to conventional instance segmentation scenarios in computer vision, the problems that we consider are characterized by a small number of training images and non-local patterns that lead to the diagnosis. In this paper, we explore the use of multiple instance learning (MIL) to design an instance label generator under this weakly supervised setting. Motivated by the observation that an MIL model can handle bags of varying sizes, we propose to repurpose an MIL model originally trained for bag-level classification to produce reliable predictions for single instances, i.e., bags of size 1. To this end, we introduce a novel regularization strategy based on virtual adversarial training for improving MIL training, and subsequently develop a knowledge distillation technique for repurposing the trained MIL model. Using empirical studies on colon cancer and breast cancer detection from histopathological images, we show that the proposed approach produces high-quality instance-level prediction and significantly outperforms state-of-the MIL methods.”
9.  [Yet another article summarising FAIR](https://www.google.com/url?q=https://neurohive.io/en/state-of-the-art/semi-weakly-supervised-learning-increasing-classification-accuracy-with-billion-scale-unlabeled-images/&sa=D&source=editors&ust=1621930681784000&usg=AOvVaw3-EfBEVxDPAELCq5yTxZV1)

* * *

SEMI SUPERVISED
---------------

1.  [Paper review](https://www.google.com/url?q=https://pdfs.semanticscholar.org/3adc/fd254b271bcc2fb7e2a62d750db17e6c2c08.pdf&sa=D&source=editors&ust=1621930681784000&usg=AOvVaw3i9NlAFU3jFVJdiJwtHcXq)
2.  [Ruder an overview of proxy labeled for  semi supervised (AMAZING)](https://www.google.com/url?q=https://ruder.io/semi-supervised/&sa=D&source=editors&ust=1621930681785000&usg=AOvVaw3Rd8Rs8Tsrt6fGrJRvyIZ1)
3.  Self training

1.  [Self training and tri training](https://www.google.com/url?q=https://github.com/zidik/Self-labeled-techniques-for-semi-supervised-learning&sa=D&source=editors&ust=1621930681785000&usg=AOvVaw0K9Yr9cPoCkGmi_HbhWf9Y)
2.  [Confidence regularized self training](https://www.google.com/url?q=https://github.com/yzou2/CRST&sa=D&source=editors&ust=1621930681786000&usg=AOvVaw0mh7aH2zHnxL8lNdli7OLs)
3.  [Domain adaptation for semantic segmentation using class balanced self-training](https://www.google.com/url?q=https://github.com/yzou2/CBST&sa=D&source=editors&ust=1621930681786000&usg=AOvVaw19di7oGi5jnxXIHxbdWEpw)
4.  [Self labeled techniques for semi supervised learning](https://www.google.com/url?q=https://github.com/zidik/Self-labeled-techniques-for-semi-supervised-learning&sa=D&source=editors&ust=1621930681787000&usg=AOvVaw1LifwlDst5ekva31C4yKsF)

4.  Tri training

1.  [Trinet for semi supervised Deep learning](https://www.google.com/url?q=https://www.ijcai.org/Proceedings/2018/0278.pdf&sa=D&source=editors&ust=1621930681787000&usg=AOvVaw3enmlUYg25YwmA2ZgJ9IQn)
2.  [Tri training exploiting unlabeled data using 3 classes](https://www.google.com/url?q=https://www.researchgate.net/publication/3297469_Tri-training_Exploiting_unlabeled_data_using_three_classifiers&sa=D&source=editors&ust=1621930681788000&usg=AOvVaw1rWqT0kDojRB_zckgrPis0), [paper](https://www.google.com/url?q=http://citeseerx.ist.psu.edu/viewdoc/download?doi%3D10.1.1.487.2431%26rep%3Drep1%26type%3Dpdf&sa=D&source=editors&ust=1621930681788000&usg=AOvVaw234XwZQHeedVdLa5CGmnuc)
3.  [Improving tri training with unlabeled data](https://www.google.com/url?q=https://link.springer.com/chapter/10.1007/978-3-642-25349-2_19&sa=D&source=editors&ust=1621930681788000&usg=AOvVaw3jcXytE9Nya2LYhv-eE7Me)
4.  [Tri training using NN ensemble](https://www.google.com/url?q=https://link.springer.com/chapter/10.1007/978-3-642-31919-8_6&sa=D&source=editors&ust=1621930681789000&usg=AOvVaw2DtM1vZyy2cot9jlaGxXLZ)
5.  [Asymmetric try training for unsupervised domain adaptation](https://www.google.com/url?q=https://github.com/corenel/pytorch-atda&sa=D&source=editors&ust=1621930681789000&usg=AOvVaw0bOoDPrLhOP5-y7fuUEmGP), [another implementation](https://www.google.com/url?q=https://github.com/vtddggg/ATDA&sa=D&source=editors&ust=1621930681790000&usg=AOvVaw1cyRCLoZVqCHaFDV1b_T98), [another](https://www.google.com/url?q=https://github.com/ksaito-ut/atda&sa=D&source=editors&ust=1621930681790000&usg=AOvVaw1gWW7DHluwV-YgNnRPhEFx), [paper](https://www.google.com/url?q=https://arxiv.org/abs/1702.08400&sa=D&source=editors&ust=1621930681790000&usg=AOvVaw0z1tadQJyZ1D1ErTHYz1Ca)
6.  [Tri training git](https://www.google.com/url?q=https://github.com/LiangjunFeng/Tri-training&sa=D&source=editors&ust=1621930681791000&usg=AOvVaw0pR45Gvg9vTDWRh95c3IVM)

5.  [Fast ai forums](https://www.google.com/url?q=https://forums.fast.ai/t/semi-supervised-learning-ssl-uda-mixmatch-s4l/56826&sa=D&source=editors&ust=1621930681791000&usg=AOvVaw0LoOpK_x2x_WU18gj4_FPo)
6.  [UDA GIT](https://www.google.com/url?q=https://github.com/google-research/uda&sa=D&source=editors&ust=1621930681791000&usg=AOvVaw07NMi2MZ1513Vl5lEZ-f_U), [paper](https://www.google.com/url?q=https://arxiv.org/abs/1904.12848&sa=D&source=editors&ust=1621930681792000&usg=AOvVaw10sLSbpj8763tRlIBoTltd), [medium*](https://www.google.com/url?q=https://medium.com/syncedreview/google-brain-cmu-advance-unsupervised-data-augmentation-for-ssl-c0a6157505ce&sa=D&source=editors&ust=1621930681792000&usg=AOvVaw1WdB-6ZVO02RpD1y3us7Cy), medium 2 ([has data augmentation articles)](https://www.google.com/url?q=https://medium.com/towards-artificial-intelligence/unsupervised-data-augmentation-6760456db143&sa=D&source=editors&ust=1621930681792000&usg=AOvVaw1cyLZDXRgOi1dvoCOASASi)
7.  [s4l](https://www.google.com/url?q=https://arxiv.org/abs/1905.03670&sa=D&source=editors&ust=1621930681793000&usg=AOvVaw3sIZ8WznB73Eu8WEfRh6kQ)
8.  [Google’s UDM and MixMatch dissected](https://www.google.com/url?q=https://mlexplained.com/2019/06/02/papers-dissected-mixmatch-a-holistic-approach-to-semi-supervised-learning-and-unsupervised-data-augmentation-explained/&sa=D&source=editors&ust=1621930681793000&usg=AOvVaw0aKLsHPZYCfKo11HvvtsjE)\- For text classification, the authors used a combination of back translation and a new method called TF-IDF based word replacing.

Back translation consists of translating a sentence into some other intermediate language (e.g. French) and then translating it back to the original language (English in this case). The authors trained an English-to-French and French-to-English system on the WMT 14 corpus.

TF-IDF word replacement replaces words in a sentence at random based on the TF-IDF scores of each word (words with a lower TF-IDF have a higher probability of being replaced).

9.  [MixMatch](https://www.google.com/url?q=https://arxiv.org/abs/1905.02249&sa=D&source=editors&ust=1621930681794000&usg=AOvVaw1B6kegz8gZahV1FG6wLLXU), [medium](https://www.google.com/url?q=https://towardsdatascience.com/a-fastai-pytorch-implementation-of-mixmatch-314bb30d0f99&sa=D&source=editors&ust=1621930681794000&usg=AOvVaw2f4R7_9Bc-ZgR1BZ8mURFP), [2](https://www.google.com/url?q=https://medium.com/@sanjeev.vadiraj/eureka-mixmatch-a-holistic-approach-to-semi-supervised-learning-125b14e82d2f&sa=D&source=editors&ust=1621930681794000&usg=AOvVaw2-dOtSseJT9u3LAFOFHQC5), [3](https://www.google.com/url?q=https://medium.com/@sshleifer/mixmatch-paper-summary-1995f3d11cf&sa=D&source=editors&ust=1621930681795000&usg=AOvVaw2DVoq9x-CAZhJYUTjneeKd), [4](https://www.google.com/url?q=https://medium.com/@literallywords/tl-dr-papers-mixmatch-9dc4cd217121&sa=D&source=editors&ust=1621930681795000&usg=AOvVaw2aKTFIW3GgSAgaZv7Na6Nz), that works by guessing low-entropy labels for data-augmented unlabeled examples and mixing labeled and unlabeled data using MixUp. We show that MixMatch obtains state-of-the-art results by a large margin across many datasets and labeled data amounts
10. ReMixMatch - [paper](https://www.google.com/url?q=https://arxiv.org/pdf/1911.09785.pdf&sa=D&source=editors&ust=1621930681796000&usg=AOvVaw15U86qaK2p1Au87-j_riZl) is really good. “We improve the recently-proposed “MixMatch” semi-supervised learning algorithm by introducing two new techniques: distribution alignment and augmentation anchoring”
11. [FixMatch](https://www.google.com/url?q=https://amitness.com/2020/03/fixmatch-semi-supervised/&sa=D&source=editors&ust=1621930681796000&usg=AOvVaw1cAVEAdc8tlQigdfE5AOI7) - FixMatch is a recent semi-supervised approach by Sohn et al. from Google Brain that improved the state of the art in semi-supervised learning(SSL). It is a simpler combination of previous methods such as UDA and ReMixMatch.  
    ![](images/image191.png)
12. [Curriculum Labeling: Self-paced Pseudo-Labeling for Semi-Supervised Learning](https://www.google.com/url?q=https://arxiv.org/pdf/2001.06001.pdf&sa=D&source=editors&ust=1621930681797000&usg=AOvVaw1rEHfFKwQRcVIv30k3-Mof)
13. [FAIR](https://www.google.com/url?q=https://ai.facebook.com/blog/billion-scale-semi-supervised-learning/&sa=D&source=editors&ust=1621930681797000&usg=AOvVaw2_jt2GYVGMxiIyKnhGJzg3)[2](https://www.google.com/url?q=https://ai.facebook.com/blog/mapping-the-world-to-help-aid-workers-with-weakly-semi-supervised-learning/&sa=D&source=editors&ust=1621930681797000&usg=AOvVaw0eJDY0H5Slq12ehdz01bRi)original, [Summarization of FAIR’s student teacher weak/ semi supervision](https://www.google.com/url?q=https://analyticsindiamag.com/how-to-do-machine-learning-when-data-is-unlabelled/&sa=D&source=editors&ust=1621930681798000&usg=AOvVaw2PD1WTXV5BV3nRN0fUbUHV)
14. [Leveraging Just a Few Keywords for Fine-Grained Aspect Detection Through Weakly Supervised](https://www.google.com/url?q=https://www.aclweb.org/anthology/D19-1468.pdf&sa=D&source=editors&ust=1621930681798000&usg=AOvVaw3KuEby6kZbDAJ945gzKMZ0) [Co-Training](https://www.google.com/url?q=https://www.aclweb.org/anthology/D19-1468.pdf&sa=D&source=editors&ust=1621930681799000&usg=AOvVaw0VkPXdTZYhK2wzM41yROAi)
15. [Fidelity-Weighted](https://www.google.com/url?q=https://openreview.net/forum?id%3DB1X0mzZCW&sa=D&source=editors&ust=1621930681799000&usg=AOvVaw28RsA1lVwDYx9u-oRxouDl) Learning - “fidelity-weighted learning” (FWL), a semi-supervised student- teacher approach for training deep neural networks using weakly-labeled data. FWL modulates the parameter updates to a student network (trained on the task we care about) on a per-sample basis according to the posterior confidence of its label-quality estimated by a teacher (who has access to the high-quality labels). Both student and teacher are learned from the data.
16. [Unproven student teacher git](https://www.google.com/url?q=https://github.com/EricHe98/Teacher-Student-Training&sa=D&source=editors&ust=1621930681800000&usg=AOvVaw0ixKWVqJVIBqcxciIyVDxu)
17. [A really nice student teacher git with examples](https://www.google.com/url?q=https://github.com/yuanli2333/Teacher-free-Knowledge-Distillation&sa=D&source=editors&ust=1621930681800000&usg=AOvVaw2z8BXKG-FEPkhpIsMV9Vck).

![](images/image224.png)

18. [Teacher student for tri training for unlabeled data exploitation](https://www.google.com/url?q=https://arxiv.org/abs/1909.11233&sa=D&source=editors&ust=1621930681801000&usg=AOvVaw3NHiG2FQUbrb9FYjBg78og)

![](images/image55.png)

* * *

REGRESSION
----------

Metrics:

1.  [R2](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Coefficient_of_determination&sa=D&source=editors&ust=1621930681803000&usg=AOvVaw14F1W2THLluaG49n6UuUzY)
2.  Medium [1](https://www.google.com/url?q=https://towardsdatascience.com/regression-an-explanation-of-regression-metrics-and-what-can-go-wrong-a39a9793d914&sa=D&source=editors&ust=1621930681804000&usg=AOvVaw1n9rFSpOE-UhoOMTBGHVzR), [2](https://www.google.com/url?q=https://medium.com/@george.drakos62/how-to-select-the-right-evaluation-metric-for-machine-learning-models-part-1-regrression-metrics-3606e25beae0&sa=D&source=editors&ust=1621930681804000&usg=AOvVaw1TBwDrx1cKBFQaqspPaOLX), [3](https://www.google.com/url?q=https://medium.com/@george.drakos62/how-to-select-the-right-evaluation-metric-for-machine-learning-models-part-2-regression-metrics-d4a1a9ba3d74&sa=D&source=editors&ust=1621930681804000&usg=AOvVaw2ZOyq2oEbjvpc0mA8TM1SD), [4](https://www.google.com/url?q=https://medium.com/usf-msds/choosing-the-right-metric-for-machine-learning-models-part-1-a99d7d7414e4&sa=D&source=editors&ust=1621930681805000&usg=AOvVaw0B1PJ64dIzdghwG169bK-q),
3.  [Tutorial](https://www.google.com/url?q=https://www.dataquest.io/blog/understanding-regression-error-metrics/&sa=D&source=editors&ust=1621930681805000&usg=AOvVaw1mYqx4-DwlK7Ka5xmIS6y0)

* * *

ACTIVE LEARNING
---------------

1.  If you need to start somewhere start [here](https://www.google.com/url?q=https://www.datacamp.com/community/tutorials/active-learning&sa=D&source=editors&ust=1621930681806000&usg=AOvVaw3Unk5rQljBC9O3sL5D-gyM) \- types of AL, the methodology, examples, sample selection functions.
2.  A thorough [review paper](https://www.google.com/url?q=http://burrsettles.com/pub/settles.activelearning.pdf&sa=D&source=editors&ust=1621930681806000&usg=AOvVaw2XmAtKxAwS2sBXlO0l2_HY) about AL
3.  [The book on AL](https://www.google.com/url?q=http://burrsettles.com/pub/settles.activelearning.pdf&sa=D&source=editors&ust=1621930681807000&usg=AOvVaw2x36CjJ59zBwW3F_g_jVXv)
4.  [Choose your model first, then do AL, from lighttag](https://www.google.com/url?q=https://www.lighttag.io/blog/active-learning-optimization-is-not-imporvement/&sa=D&source=editors&ust=1621930681807000&usg=AOvVaw1qFPEZd9PRMS_fMgJ_gdP7)

1.  The alternative is Query by committee - Importantly, the active learning method we presented above is the most naive form of what is called "uncertainty sampling" where we chose to sample based on how uncertain our model was. An alternative approach, called Query by Committee, maintains a collection of models (the committee) and selecting the most "controversial" data point to label next, that is one where the models disagreed on. Using such a committee may allow us to overcome the restricted hypothesis a single model can express, though at the onset of a task we still have no way of knowing what hypothesis we should be using.
2.  [Paper](https://www.google.com/url?q=https://arxiv.org/pdf/1807.04801.pdf&sa=D&source=editors&ust=1621930681808000&usg=AOvVaw1XL7IGS9ROcmG3Rhcw0Vzu): warning against transferring actively sampled datasets to other models

5.  [How to increase accuracy with AL](https://www.google.com/url?q=http://www.ijcte.org/papers/910-AC0013.pdf&sa=D&source=editors&ust=1621930681808000&usg=AOvVaw0iBsLKXHLLBRiz2Q8fVZeh)
6.  [AL with model selection](https://www.google.com/url?q=http://www.alnurali.com/papers/paper_aaai_2014.pdf&sa=D&source=editors&ust=1621930681809000&usg=AOvVaw2NvdUCHwfvYMmAjl2RdRz4) \- paper
7.  Using weak and strong oracle in AL, [paper](https://www.google.com/url?q=http://publications.lib.chalmers.se/records/fulltext/248447/248447.pdf&sa=D&source=editors&ust=1621930681809000&usg=AOvVaw2yA2ocXs6Jz-1xf9yD-ORt).
8.  [The pitfalls of AL](https://www.google.com/url?q=http://www.kdd.org/exploration_files/v12-02-9-UR-Attenberg.pdf&sa=D&source=editors&ust=1621930681810000&usg=AOvVaw0E_cEcgR1oPo83gRAEg2vY) \- how to choose (cost-effectively) the active learning technique when one starts without the labeled data needed for methods like cross-validation; 2. how to choose (cost-effectively) the base learning technique when one starts without the labeled data needed for methods like cross-validation, given that we know that learning curves cross, and given possible interactions between active learning technique and base learner; 3. how to deal with highly skewed class distributions, where active learning strategies find few (or no) instances of rare classes; 4. how to deal with concepts including very small subconcepts (“disjuncts”)—which are hard enough to find with random sampling (because of their rarity), but active learning strategies can actually avoid finding them if they are misclassified strongly to begin with; 5. how best to address the cold-start problem, and especially 6. whether and what alternatives exist for using human resources to improve learning, that may be more cost efficient than using humans simply for labeling selected cases, such as guided learning \[3\], active dual supervision \[2\], guided feature labeling \[1\], etc.
9.  [Confidence based stopping criteria paper](https://www.google.com/url?q=http://www.cs.cmu.edu/~./hovy/papers/10ACMjournal-activelearning-stopping.pdf&sa=D&source=editors&ust=1621930681810000&usg=AOvVaw21PyMTzEWp3DeUNzlo2WpQ)
10. A great [tutorial](https://www.google.com/url?q=http://hunch.net/~active_learning/active_learning_icml09.pdf&sa=D&source=editors&ust=1621930681811000&usg=AOvVaw05UizLsQMYe7miwpmjlAQb)
11. [An ok video](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DEt7h1A1j4ns%26feature%3Dyoutu.be&sa=D&source=editors&ust=1621930681811000&usg=AOvVaw3QtSbNwrfa2TcJ7QYPuKs0)
12. [Active learning framework in python](https://www.google.com/url?q=https://github.com/bwallace/curious_snake&sa=D&source=editors&ust=1621930681812000&usg=AOvVaw1ROP_M_iLdSXG8EveHrrMu)
13. [Active Learning Using Pre-clustering](https://www.google.com/url?q=https://www.researchgate.net/profile/Arnold_Smeulders/publication/221345455_Active_learning_using_pre-clustering/links/54c3cc440cf2911c7a4cc74a/Active-learning-using-pre-clustering.pdf&sa=D&source=editors&ust=1621930681812000&usg=AOvVaw3JXdvKyd_g2x9cp58kz1yZ)
14. [A literature survey of active machine learning in the context of natural language processing](https://www.google.com/url?q=http://eprints.sics.se/3600/&sa=D&source=editors&ust=1621930681813000&usg=AOvVaw14WUlPkj9OziALXXmmy-rD)
15. [Mnist competition (unpublished) using AL](https://www.google.com/url?q=http://dag.cvc.uab.es/mnist/statistics/&sa=D&source=editors&ust=1621930681813000&usg=AOvVaw2k6QviRJe27N9nfEuCgXPX)
16. [Practical Online Active Learning for Classification](https://www.google.com/url?q=http://citeseerx.ist.psu.edu/viewdoc/download?doi%3D10.1.1.87.5536%26rep%3Drep1%26type%3Dpdf&sa=D&source=editors&ust=1621930681814000&usg=AOvVaw3ZLkyj32ia_hD1k7mWQWEr)
17. [Video 2](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D8Jwp4_WbRio%26index%3D7%26list%3DPLegWUnz91Wfsn6skGOofRoeFoOyfdqSyN&sa=D&source=editors&ust=1621930681814000&usg=AOvVaw1dKuFo-WGtmiJiMWwBi-Gw)
18. [Active learning in R - code](https://www.google.com/url?q=https://github.com/gsimchoni/ActiveLearningExercise&sa=D&source=editors&ust=1621930681815000&usg=AOvVaw009oMqxJVC0HHUifeOlNIf)
19. [Deep bayesian active learning with image data](https://www.google.com/url?q=https://arxiv.org/pdf/1703.02910.pdf&sa=D&source=editors&ust=1621930681815000&usg=AOvVaw0DkLVDvwrxnMgwnVynSeaK)
20. [Medium on AL](https://www.google.com/url?q=https://news.voyage.auto/active-learning-and-why-not-all-data-is-created-equal-8a43a758c6f9&sa=D&source=editors&ust=1621930681816000&usg=AOvVaw1__xWVa1fdW0yk0GW3WrCb)\*\*\*

[Robert munro on](https://www.google.com/url?q=https://www.manning.com/books/human-in-the-loop-machine-learning%23ref&sa=D&source=editors&ust=1621930681816000&usg=AOvVaw2eKXV5GpXnf3-LoOE9OjPS) active learning - should buy his book:

1.  [GIT](https://www.google.com/url?q=https://github.com/rmunro/pytorch_active_learning&sa=D&source=editors&ust=1621930681816000&usg=AOvVaw3IsSrQRGVQrDG6BLzBzZam)
2.  [Active transfer learning](https://www.google.com/url?q=https://medium.com/pytorch/active-transfer-learning-with-pytorch-71ed889f08c1&sa=D&source=editors&ust=1621930681817000&usg=AOvVaw05pxBtj5u8KeIMmoCsHlch)
3.  [Uncertainty sampling](https://www.google.com/url?q=https://towardsdatascience.com/uncertainty-sampling-cheatsheet-ec57bc067c0b&sa=D&source=editors&ust=1621930681817000&usg=AOvVaw0n2a6VuEN9_n_QWplyCul5)

1.  Least Confidence: difference between the most confident prediction and 100% confidence
2.  Margin of Confidence: difference between the top two most confident predictions
3.  Ratio of Confidence: ratio between the top two most confident predictions
4.  Entropy: difference between all predictions, as defined by information theory
5.  ![](images/image73.png)

4.  [Diversity sampling](https://www.google.com/url?q=https://towardsdatascience.com/https-towardsdatascience-com-diversity-sampling-cheatsheet-32619693c304&sa=D&source=editors&ust=1621930681818000&usg=AOvVaw1QbfZdwa8NaA9_PHfzQV6F)\-  you want to make sure that it covers as diverse a set of data and real-world demographics as possible.

1.  Model-based Outliers: sampling for low activation in your logits and hidden layers to find items that are confusing to your model because of lack of information
2.  Cluster-based Sampling: using Unsupervised Machine Learning to sample data from all the meaningful trends in your data’s feature-space
3.  Representative Sampling: sampling items that are the most representative of the target domain for your model, relative to your current training data
4.  Real-world diversity: using sampling strategies that increase fairness when trying to support real-world diversity

![](images/image15.png)

5.  [Combine uncertainty sampling and diversity sampling](https://www.google.com/url?q=https://towardsdatascience.com/advanced-active-learning-cheatsheet-d6710cba7667&sa=D&source=editors&ust=1621930681819000&usg=AOvVaw1ozA6bevHegv2JW7d5QT5J)

1.  Least Confidence Sampling with Clustering-based Sampling: sample items that are confusing to your model and then cluster those items to ensure a diverse sample (see diagram below).
2.  Uncertainty Sampling with Model-based Outliers: sample items that are confusing to your model and within those find items with low activation in the model.
3.  Uncertainty Sampling with Model-based Outliers and Clustering: combine methods 1 and 2.
4.  Representative Cluster-based Sampling: cluster your data to capture multinodal distributions and sample items that are most like your target domain (see diagram below).
5.  Sampling from the Highest Entropy Cluster: cluster your unlabeled data and find the cluster with the highest average confusion for your model.
6.  Uncertainty Sampling and Representative Sampling: sample items that are both confusing to your current model and the most like your target domain.
7.  Model-based Outliers and Representative Sampling: sample items that have low activation in your model but are relatively common in your target domain.
8.  Clustering with itself for hierarchical clusters: recursively cluster to maximize the diversity.
9.  Sampling from the Highest Entropy Cluster with Margin of Confidence Sampling: find the cluster with the most confusion and then sample for the maximum pairwise label confusion within that cluster.
10. Combining Ensemble Methods and Dropouts with individual strategies: aggregate results that come from multiple models or multiple predictions from one model via Monte-Carlo Dropouts aka Bayesian Deep Learning.
11. ![](images/image183.png)

6.  Active transfer learning.
7.  ![](images/image66.png)

Machine in the loop

1.  [Similar to AL, just a machine / model / algo adds suggestions. This is obviously a tradeoff of bias and clean dataset](https://www.google.com/url?q=https://www.lighttag.io/blog/when-to-use-machine-in-the-loop/&sa=D&source=editors&ust=1621930681821000&usg=AOvVaw20ZXBmKbgIzgV0Rf82o0DE)
    
    * * *
    

ONLINE LEARNING
---------------

1.  If you want to start with OL - [start here](https://www.google.com/url?q=https://dziganto.github.io/data%2520science/online%2520learning/python/scikit-learn/An-Introduction-To-Online-Machine-Learning/&sa=D&source=editors&ust=1621930681821000&usg=AOvVaw0yG_wg6yqF4OjmrDI--jKj)& [here](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2015/01/introduction-online-machine-learning-simplified-2/&sa=D&source=editors&ust=1621930681822000&usg=AOvVaw1uhF8sdcITesKxNw59qLwr)
2.  Shay Shalev - [A thesis about online learning](https://www.google.com/url?q=http://ttic.uchicago.edu/~shai/papers/ShalevThesis07.pdf&sa=D&source=editors&ust=1621930681822000&usg=AOvVaw0Zc_ekRqrK8R00v6y2jmPe)
3.  [Some answers about what is OL,](https://www.google.com/url?q=https://www.quora.com/What-is-the-best-way-to-learn-online-machine-learning&sa=D&source=editors&ust=1621930681823000&usg=AOvVaw06q7qwzHGqmMyH_wlF5_4R)the first one actually talks about S.Shalev’s [other paper.](https://www.google.com/url?q=http://www.cs.huji.ac.il/~shais/papers/OLsurvey.pdf&sa=D&source=editors&ust=1621930681823000&usg=AOvVaw3OUucau4FawfJZJr-HlYgf)
4.  Online learning - Andrew Ng - [coursera](https://www.google.com/url?q=https://www.coursera.org/learn/machine-learning/lecture/ABO2q/online-learning&sa=D&source=editors&ust=1621930681823000&usg=AOvVaw0JSZKaxjd0qvBnAAyzxjQD)
5.  [Chip Huyen on online prediction & learning](https://www.google.com/url?q=https://huyenchip.com/2020/12/27/real-time-machine-learning.html&sa=D&source=editors&ust=1621930681824000&usg=AOvVaw3cA5tFJFDK89xMOcr9YRsE)

ONLINE DEEP LEARNING (ODL)
--------------------------

1.  [Hedge back propagation (HDP), Autonomous DL, Qactor](https://www.google.com/url?q=https://towardsdatascience.com/online-deep-learning-odl-and-hedge-back-propagation-277f338a14b2&sa=D&source=editors&ust=1621930681824000&usg=AOvVaw3pRmqR-P15sAKUeFWFX_kg) \- online AL for noisy labeled stream data.

N-SHOT LEARNING
---------------

1.  [Zero shot, one shot, few shot](https://www.google.com/url?q=https://blog.floydhub.com/n-shot-learning/&sa=D&source=editors&ust=1621930681825000&usg=AOvVaw1U34_NmWohOHRzgHemmALo) (siamese is one shot)

### ZERO SHOT LEARNING

1.  [Instead of using class labels](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DjBnCcr-3bXc&sa=D&source=editors&ust=1621930681825000&usg=AOvVaw2DO2h3sg-bqU-ZSZyxLzu0), we use some kind of vector representation for the classes, taken from a co-occurrence-after-svd or word2vec. - quite clever. This enables us to figure out if a new unseen class is near one of the known supervised classes. KNN can be used or some other distance-based classifier. Can we use word2vec for similarity measurements of new classes?  
    ![](images/image5.png)
2.  for classification, we can use nearest neighbour or manifold-based labeling propagation.  
    ![](images/image109.png)
3.  Multiple category vectors? Multilabel zero-shot also in the video

### GPT3 is ZERO, ONE, FEW

1.  TBC

* * *

DATA SCIENCE
============

LIFE CYCLE
----------

![](images/image126.png)

[Google’s famous MLops](https://www.google.com/url?q=https://cloud.google.com/solutions/machine-learning/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning%23mlops_level_0_manual_process&sa=D&source=editors&ust=1621930681827000&usg=AOvVaw3706xDATqceNNRS7o45o6v)

![ML systems is more than ML code.](images/image151.png)

* * *

![](images/image140.png)

[Fast ai project checklist](https://www.google.com/url?q=https://www.fast.ai/2020/01/07/data-questionnaire/?fbclid%3DIwAR2M_kdqKGSQ9uOFfdTncA6415K31V_flN203T1vHwNJOYg83XY2a9c-Jgg&sa=D&source=editors&ust=1621930681827000&usg=AOvVaw2p1MRk8TzAAyGUTPgp11NA)

When I used to do consulting, I’d always seek to understand an organization’s context for developing data projects, based on these considerations:

* Strategy: What is the organization trying to do (objective) and what can it change to do it better (levers)?
* Data: Is the organization capturing necessary data and making it available?
* Analytics: What kinds of insights would be useful to the organization?
* Implementation: What organizational capabilities does it have?
* Maintenance: What systems are in place to track changes in the operational environment?
* Constraints: What constraints need to be considered in each of the above areas?

WORKFLOWS
---------

1.  [kaggle](https://www.google.com/url?q=https://towardsdatascience.com/my-secret-sauce-to-be-in-top-2-of-a-kaggle-competition-57cff0677d3c?fbclid%3DIwAR3Iei5OmwswIMbbqcz2dNr5rLsWS-iuuaAuOjmhCELTTEBTPmSM85mTw7U&sa=D&source=editors&ust=1621930681829000&usg=AOvVaw33zrVH0uNw8POxGZfufrmc)

PLATFORMS
---------

1.  [Uber, google, netflix, airbnb, etc](https://www.google.com/url?q=https://databaseline.tech/a-tour-of-end-to-end-ml-platforms/&sa=D&source=editors&ust=1621930681829000&usg=AOvVaw0-2wE1dJSpq5ZKmdWHuVYN)

STACK
-----

1.  [Medium on canonical stack](https://www.google.com/url?q=https://towardsdatascience.com/rise-of-the-canonical-stack-in-machine-learning-724e7d2faa75&sa=D&source=editors&ust=1621930681830000&usg=AOvVaw226BItCAwUmtLHR8oLEKXN)

* * *

Data Science OKR KPI
--------------------

1.  [OKR vs KPI](https://www.google.com/url?q=https://www.clearpointstrategy.com/okrs-vs-kpis/&sa=D&source=editors&ust=1621930681830000&usg=AOvVaw13sXgzyPgtKyN-oeGLBXFD), strategic vs tactical
2.  [Difference between KPI targets and goals](https://www.google.com/url?q=https://bernardmarr.com/default.asp?contentID%3D1346%23:~:text%3DThe%2520terms%2520key%2520performance%2520indicator,NOT%2520the%2520same%2520as%2520goals.&sa=D&source=editors&ust=1621930681831000&usg=AOvVaw0dyomWHYRUcbqr7LKz0ESE)
3.  [Comet ml on medium](https://www.google.com/url?q=https://medium.com/comet-ml/a-data-scientists-guide-to-communicating-results-c79a5ef3e9f1&sa=D&source=editors&ust=1621930681831000&usg=AOvVaw3OcWx1xv12K5PdmBKCn3Xh)

![](images/image127.png)

4.  [For the Data Driven manager (not ds)](https://www.google.com/url?q=https://www.klipfolio.com/blog/17-kpi-management-data-driven-manager&sa=D&source=editors&ust=1621930681832000&usg=AOvVaw3y4p6uQDfrUZ8QxgiCumeb)
5.  [Measuring DS business value](https://www.google.com/url?q=https://blog.dominodatalab.com/measuring-data-science-business-value/&sa=D&source=editors&ust=1621930681832000&usg=AOvVaw2UVx7ICMllS0bxt7uXltb6)
6.  [Best KPIS for DS - the best is what not to do](https://www.google.com/url?q=https://www.quora.com/What-are-the-best-KPIs-for-Data-Science-team&sa=D&source=editors&ust=1621930681833000&usg=AOvVaw04gwDaPqTzP9OsOuzbNY6w)

* * *

Being a DS / Researcher
-----------------------

1.  [A day in a life](https://www.google.com/url?q=https://towardsdatascience.com/12-things-i-learned-during-my-first-year-as-a-machine-learning-engineer-2991573a9195&sa=D&source=editors&ust=1621930681833000&usg=AOvVaw3KiF8gGDCEgMSXs8Rzyvy7)
2.  [Advice for a ds](https://www.google.com/url?q=https://medium.com/the-data-experience/building-a-data-pipeline-from-scratch-32b712cfb1db&sa=D&source=editors&ust=1621930681834000&usg=AOvVaw0EX6LfIn3wAE24nIrNx3k3), business kpi are not research kpi, etc
3.  [Review of deep learning papers and co authorship](https://www.google.com/url?q=https://neurovenge.antonomase.fr/&sa=D&source=editors&ust=1621930681834000&usg=AOvVaw3iVHdX96rD2OqzdqRzWszs)
4.  Full stack DS [Uri Weiss](https://www.google.com/url?q=https://linkedin.com/in/uriweiss&sa=D&source=editors&ust=1621930681835000&usg=AOvVaw1Dsd6shE_2bw_tOFPqCm0o)  
    ![](images/image146.png)

Team Building / Group Cohesion
------------------------------

![](images/image216.png)

5.  [DS vs DA vs MLE](https://www.google.com/url?q=https://medium.com/@meightpc_14421/data-scientist-vs-data-analysis-vs-ml-engineer-which-job-is-most-suited-for-you-def7b12b3256&sa=D&source=editors&ust=1621930681835000&usg=AOvVaw1DpWBp-U9TsqEgKejJmQ5s) \- the most intensive diagram post ever. This is the mother load of figure references.

References:

[1](https://www.google.com/url?q=https://medium.com/@rdavila01/a-team-development-roadmap-ce5247127037&sa=D&source=editors&ust=1621930681836000&usg=AOvVaw1ejs1fEjA4eFPl5Urtzept), [2](https://www.google.com/url?q=https://medium.com/swlh/team-development-stages-51df5606c0a2&sa=D&source=editors&ust=1621930681836000&usg=AOvVaw0JePTYt0Jtx5O9RCl0zPzw), [3](https://www.google.com/url?q=https://medium.com/unexpected-leadership/forming-storming-norming-and-performing-5d06d021a969&sa=D&source=editors&ust=1621930681837000&usg=AOvVaw12_FzWUxZ6wys17ASkngOI), [4](https://www.google.com/url?q=https://medium.com/@RiterApp/8-models-of-team-effectiveness-3a3b84efb3ae&sa=D&source=editors&ust=1621930681837000&usg=AOvVaw2-b2o4mraFjxRHJ2zstl4V), [5](https://www.google.com/url?q=https://medium.com/@warren2lynch/traditional-to-scrum-team-forming-storming-norming-and-performing-3fd5fd1f5ea9&sa=D&source=editors&ust=1621930681837000&usg=AOvVaw0zo9xkIC7n_jqKUNd8btAb), [6](https://www.google.com/url?q=https://medium.com/@pallawi.ds/new-employee-best-practices-to-perform-with-the-team-tuckmans-stages-of-group-development-c656ca295bee&sa=D&source=editors&ust=1621930681838000&usg=AOvVaw0erL5JJ1l6VAr_-X0_KdYB), [7](https://www.google.com/url?q=https://medium.com/agilegreat/tuckman-model-for-building-great-teams-7b3203d7a9e3&sa=D&source=editors&ust=1621930681838000&usg=AOvVaw17k0h9VdO10OdGYf8aC-TK), [8](https://www.google.com/url?q=https://medium.com/simply-agile/agile-leader-pattern-2-for-building-awesome-teams-stabilize-teams-32785b70868c&sa=D&source=editors&ust=1621930681839000&usg=AOvVaw0AIO_7Bst1_cipkRq3T3Dv), [9](https://www.google.com/url?q=https://medium.com/hackernoon/team-building-mental-models-1f431ae29361&sa=D&source=editors&ust=1621930681839000&usg=AOvVaw2bWWFyqoQk4FBX4HyT2He7), 10

[Why data science needs generalists not specialists](https://www.google.com/url?q=https://hbr.org/2019/03/why-data-science-teams-need-generalists-not-specialists&sa=D&source=editors&ust=1621930681840000&usg=AOvVaw2YWZCoraP3UJeRdXAaWbbX)

1.  (good advice) [Building a DS function (team)](https://www.google.com/url?q=https://medium.com/ww-tech-blog/from-0-to-60-models-in-two-years-building-out-an-impactful-data-science-function-9ef86abb9605&sa=D&source=editors&ust=1621930681840000&usg=AOvVaw2ZHUFUtLdxAbTtptJmtB9W)

Agile for data-science-research
-------------------------------

1.  [How to manage a data science research team using agile methodology, not scrum and not kanban](https://www.google.com/url?q=https://towardsdatascience.com/data-science-agile-cycles-my-method-for-managing-data-science-projects-in-the-hi-tech-industry-b289e8a72818&sa=D&source=editors&ust=1621930681841000&usg=AOvVaw3q1I388vkUa781fN7H1-l-)
2.  [Workflow for data science research projects](https://www.google.com/url?q=https://towardsdatascience.com/data-science-project-flow-for-startups-282a93d4508d&sa=D&source=editors&ust=1621930681841000&usg=AOvVaw3A9JjXe-GVUZdufzQdtACq)
3.  [Tips for data science research management](https://www.google.com/url?q=https://towardsdatascience.com/my-best-tips-for-agile-data-science-research-b40365cc979d&sa=D&source=editors&ust=1621930681841000&usg=AOvVaw0Q2LpZXBWpYYSLAa0AKT0B)
4.  [IMO a really bad implementation of agile for data-science-projects](https://www.google.com/url?q=https://www.locallyoptimistic.com/post/agile-analytics-p1/&sa=D&source=editors&ust=1621930681842000&usg=AOvVaw2R5hpOL_wYg59Jck34LO1i)

SOTA AND CURRENT TRENDS SUMMARIES
---------------------------------

1.  [ICLR 2019](https://www.google.com/url?q=https://huyenchip.com/2019/05/12/top-8-trends-from-iclr-2019.html?fbclid%3DIwAR28Ez8Hs-XMSxcQb2NHfLQvZ5m4C8b4NIZPue00u6MZzrlI90Oqx8TExuU&sa=D&source=editors&ust=1621930681842000&usg=AOvVaw1nGv_CasTBGtdH8Ajp_vCx)
2.  [Medium](https://www.google.com/url?q=https://medium.com/huggingface/the-best-and-most-current-of-modern-natural-language-processing-5055f409a1d1?fbclid%3DIwAR22vuGFXHil1Nz4vJr4uhueiKPRMz2T-BSwPXl8kg5iQZ54ppHe5ffecqI&sa=D&source=editors&ust=1621930681843000&usg=AOvVaw3w8mOuQhVys-b4muEPf2f0)
3.  [State of ai, a yearly report](https://www.google.com/url?q=https://www.stateof.ai/&sa=D&source=editors&ust=1621930681843000&usg=AOvVaw0H1R6qrsuAzc7Gh1iN2O6Z)

* * *

YOUTUBE COURSES
---------------

* [DEEPNET.TV YOUTUBE (excellent)](https://www.google.com/url?q=https://www.youtube.com/channel/UC9OeZkIwhzfv-_Cb7fCikLQ&sa=D&source=editors&ust=1621930681844000&usg=AOvVaw2vecYvAQna0yB_TOnUxarS)
* [Mitchel ML Lectures (too long)](https://www.google.com/url?q=http://www.cs.cmu.edu/~ninamf/courses/601sp15/lectures.shtml&sa=D&source=editors&ust=1621930681844000&usg=AOvVaw0SXsLH9Kff3OuaUBEZH0Lk)
* [Quoc Les (google) wrote DNN tutorials and 3H video (not intuitive)](https://www.google.com/url?q=http://cs.stanford.edu/~quocle/&sa=D&source=editors&ust=1621930681845000&usg=AOvVaw2iA0uH3bStwMcNs-AFxjoJ)
* [KDnuggets: numpy, panda, scikit, tutorials.](https://www.google.com/url?q=http://www.kdnuggets.com/2015/11/seven-steps-machine-learning-python.html&sa=D&source=editors&ust=1621930681845000&usg=AOvVaw2CVYowAFpiKFTVDIgKJpyA)
* [Deep learning online book (too wordy)](https://www.google.com/url?q=http://neuralnetworksanddeeplearning.com/&sa=D&source=editors&ust=1621930681845000&usg=AOvVaw3RKNrvh24Z_AGcUnXYChfv)
* [Genetic Algorithms - grid search hyper params better than brute force.. obviously](https://www.google.com/url?q=https://medium.com/@harvitronix/lets-evolve-a-neural-network-with-a-genetic-algorithm-code-included-8809bece164&sa=D&source=editors&ust=1621930681846000&usg=AOvVaw1CID-UuGH_bNoWQIbwMzab)

* [CNN tutorial](https://www.google.com/url?q=http://mccormickml.com/2015/01/10/understanding-the-deeplearntoolbox-cnn-example/&sa=D&source=editors&ust=1621930681846000&usg=AOvVaw2CeP7WEf7DkvalzBuY0mC1)
* [Introduction to programming in scikit](https://www.google.com/url?q=http://nbviewer.jupyter.org/github/donnemartin/data-science-ipython-notebooks/blob/master/scikit-learn/scikit-learn-intro.ipynb&sa=D&source=editors&ust=1621930681847000&usg=AOvVaw31qMtqik9PdyRisxkaEAO5)
* [SVM in scikit python](https://www.google.com/url?q=https://github.com/jakevdp/sklearn_pycon2015/blob/master/notebooks/03.1-Classification-SVMs.ipynb&sa=D&source=editors&ust=1621930681847000&usg=AOvVaw1AUg6zYIngOUjliUnpG511)
* [Sklearn scipy PCA tutorial](https://www.google.com/url?q=https://github.com/jakevdp/sklearn_pycon2015/blob/master/notebooks/04.1-Dimensionality-PCA.ipynb&sa=D&source=editors&ust=1621930681848000&usg=AOvVaw1MMhq8syWZBea8hDsqvuty)
* [RNN](https://www.google.com/url?q=http://colah.github.io/posts/2015-08-Understanding-LSTMs/&sa=D&source=editors&ust=1621930681848000&usg=AOvVaw0yUjQTCRNiNvVpzzm3YD68)
* [Matrix Multiplication](https://www.google.com/url?q=http://www.mathwarehouse.com/algebra/matrix/multiply-matrix.php&sa=D&source=editors&ust=1621930681848000&usg=AOvVaw3Gn4urRQWJfZoCeHVQpzIx) \- linear algebra

Deep learning Course  
----------------------

[Kadenze - deep learning tensor flow](https://www.google.com/url?q=https://www.kadenze.com/courses/creative-applications-of-deep-learning-with-tensorflow-iv/sessions/introduction-to-tensorflow&sa=D&source=editors&ust=1621930681849000&usg=AOvVaw3iO4OhwuouSdIHecFaqNZg) \- Histograms for (Image distribution - mean distribution) / std dev, are looking quite good.

Machine Learning Course
-----------------------

1.  [Recommended: Udacity includes ML and DL](https://www.google.com/url?q=https://classroom.udacity.com/courses/ud188/lessons/b4ca7aaa-b346-43b1-ae7d-20d27b2eab65/concepts/4b7026be-06e3-49de-a362-ce109172659e&sa=D&source=editors&ust=1621930681850000&usg=AOvVaw0OwNSTtWD_iMK8DLp-pEgY)
2.  [Week1: Introduction Lesson 4: Supervised, unsupervised.](https://www.google.com/url?q=https://www.coursera.org/learn/machine-learning/lecture/1VkCb/supervised-learning&sa=D&source=editors&ust=1621930681850000&usg=AOvVaw2Ly6D6Vubn1qGaXHSQMbq2)
3.  [Lesson 6: model regression, cost function](https://www.google.com/url?q=https://www.coursera.org/learn/machine-learning/lecture/db3jS/model-representation&sa=D&source=editors&ust=1621930681851000&usg=AOvVaw1SFy7n3guhMTpEdGQh2DEz)
4.  [Lesson 71: optimization objective, large margin classification](https://www.google.com/url?q=https://www.coursera.org/learn/machine-learning/lecture/sHfVT/optimization-objective&sa=D&source=editors&ust=1621930681851000&usg=AOvVaw1LDxrN95OfF-tZ7c2e7jGX)
5.  [PCA at coursera #1](https://www.google.com/url?q=https://www.coursera.org/learn/machine-learning/lecture/GBFTt/principal-component-analysis-problem-formulation&sa=D&source=editors&ust=1621930681852000&usg=AOvVaw3TpxgNAbG-ZA3R76nhe5m8)
6.  [PCA at coursera](https://www.google.com/url?q=https://www.coursera.org/learn/machine-learning/lecture/ZYIPa/principal-component-analysis-algorithm&sa=D&source=editors&ust=1621930681853000&usg=AOvVaw37nw4wzuulBsawTbOzz7pZ) #2
7.  [PCA #3](https://www.google.com/url?q=https://www.coursera.org/learn/machine-learning/lecture/S1bq1/choosing-the-number-of-principal-components&sa=D&source=editors&ust=1621930681853000&usg=AOvVaw31-5Tq66AJmaGAdfghADPj)
8.  [SVM at coursera #1 - simplified](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/2Qh1o/support-vector-machine-example&sa=D&source=editors&ust=1621930681854000&usg=AOvVaw2fcd2sekuYd76kTR-iKkpx)

Predictive Analytics Course
---------------------------

[Syllabus](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics&sa=D&source=editors&ust=1621930681855000&usg=AOvVaw2TvOWgASLsOMyOQS0jJ3p8)

[Week 2: Lesson 29: supervised learning](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/qzrx8/statistics-vs-machine-learning&sa=D&source=editors&ust=1621930681856000&usg=AOvVaw2AU_I0Zep46nu0ALV1adk4)

[Lesson 36: From rules to trees](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/qTN05/from-rules-to-trees&sa=D&source=editors&ust=1621930681856000&usg=AOvVaw3swrZwMXboCo0eMYsOQ7yj)

[Lesson 43: overfitting, then validation, then accuracy](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/cnLwv/overfitting&sa=D&source=editors&ust=1621930681857000&usg=AOvVaw0AwIYxVn4NRP4Ct39fuNyc)

[Lesson 46: bootstrap, bagging, boosting, random forests.](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/ZUJqG/bootstrap-revisited&sa=D&source=editors&ust=1621930681857000&usg=AOvVaw3m1xbC7omtAnBL0ZOyxkoJ)

[Lesson 52: NN](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/6uyga/nearest-neighbor&sa=D&source=editors&ust=1621930681858000&usg=AOvVaw0yQvstR86yY716yKtJGT9_)

[Lesson 55: Gradient Descent](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/68oAE/optimization-by-gradient-descent&sa=D&source=editors&ust=1621930681858000&usg=AOvVaw1nJcmMgFnQr82OyurzPMI_)

[Lesson 59: Logistic regression, SVM, Regularization, Lasso, Ridge regression](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/FecmG/intuition-for-logistic-regression&sa=D&source=editors&ust=1621930681859000&usg=AOvVaw1Cr6P-ceqPF_rl---_AxSH)

[Lesson 64: gradient descent, stochastic, parallel, batch.](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/eCynR/stochastic-and-batched-gradient-descent&sa=D&source=editors&ust=1621930681860000&usg=AOvVaw3-mhg7DwFoN8LpSvQiL-G0)

[Unsupervised: Lesson X K-means, DBscan](https://www.google.com/url?q=https://www.coursera.org/learn/predictive-analytics/lecture/WWiiy/introduction-to-unsupervised-learning&sa=D&source=editors&ust=1621930681860000&usg=AOvVaw0iP5abxfOzON-TAYxt0mvX)

BOOKS & NOTEBOOKS
-----------------

1.  [Machine learning design patterns](https://www.google.com/url?q=https://www.oreilly.com/library/view/machine-learning-design/9781098115777/&sa=D&source=editors&ust=1621930681861000&usg=AOvVaw2LMOdczshhsoL4UWBfHSTa), [git](https://www.google.com/url?q=https://github.com/GoogleCloudPlatform/ml-design-patterns&sa=D&source=editors&ust=1621930681861000&usg=AOvVaw36Xmc3yVOgK3_dcK7H6ZNB) notebooks!, [medium](https://www.google.com/url?q=https://lakshmanok.medium.com/machine-learning-design-patterns-58e6ecb013d7&sa=D&source=editors&ust=1621930681862000&usg=AOvVaw11t0obrV4znjgBYUZkdHa9)

1.  [DP1 - transform](https://www.google.com/url?q=https://medium.com/swlh/ml-design-pattern-1-transform-9e82ccbc3209&sa=D&source=editors&ust=1621930681862000&usg=AOvVaw1EKzYpf68BYV9RRh_aejcv) Moving an ML model to production is much easier if you keep inputs, features, and transforms separate
2.  [DP2 - checkpoints](https://www.google.com/url?q=https://towardsdatascience.com/ml-design-pattern-2-checkpoints-e6ca25a4c5fe&sa=D&source=editors&ust=1621930681863000&usg=AOvVaw3ZzavAWPtzwbElkrHx7hsa) Saving the intermediate weights of your model during training provides resilience, generalization, and tunability
3.  [DP3 - virtual epochs](https://www.google.com/url?q=https://medium.com/google-cloud/ml-design-pattern-3-virtual-epochs-f842296de730&sa=D&source=editors&ust=1621930681864000&usg=AOvVaw2ItFqJd8qBSAlw99TGEhbD) Base machine learning model training and evaluation on total number of examples, not on epochs or steps
4.  [DP4 - keyed predictions](https://www.google.com/url?q=https://towardsdatascience.com/ml-design-pattern-4-keyed-predictions-a8de67d9c0f4&sa=D&source=editors&ust=1621930681864000&usg=AOvVaw28L9vEi2vbsMNQ6J_UySNq) Export your model so that it passes through client keys
5.  [DP5 - repeatable sampling](https://www.google.com/url?q=https://towardsdatascience.com/ml-design-pattern-5-repeatable-sampling-c0ccb2889f39&sa=D&source=editors&ust=1621930681865000&usg=AOvVaw2GRK2dpJaU_QnXusf70P0a) use the hash of a well distributed column to split your data into training, validation, and testing

2.  [Gensim notebooks](https://www.google.com/url?q=https://github.com/RaRe-Technologies/gensim/tree/develop/docs/notebooks&sa=D&source=editors&ust=1621930681865000&usg=AOvVaw25RFZcHysB6-IOlIneWVGs) \- from w2v, doc2vec to nmf, lda, pca, sklearn api, cosine, topic modeling, tsne, etc.
3.  [Deep learning with python](https://www.google.com/url?q=https://www.manning.com/books/deep-learning-with-python&sa=D&source=editors&ust=1621930681866000&usg=AOvVaw13JKlfqAni6Yq45NiopKI1)\- francois chollet, deep learning & vision [git notebooks!](https://www.google.com/url?q=https://github.com/fchollet/deep-learning-with-python-notebooks&sa=D&source=editors&ust=1621930681866000&usg=AOvVaw0IKTLKYLvNQ5AznjZPGeIz), [official notebooks](https://www.google.com/url?q=https://github.com/PacktPublishing/Deep-Learning-with-Keras&sa=D&source=editors&ust=1621930681867000&usg=AOvVaw2tqhD_edVwi4cTJk8_TzUo).
4.  Yandex school, [nlp notebooks](https://www.google.com/url?q=https://github.com/yandexdataschool/nlp_course&sa=D&source=editors&ust=1621930681867000&usg=AOvVaw2wFW9qniolWiyHP8go4z89)
5.  [Machine learning engineering book](https://www.google.com/url?q=http://www.mlebook.com/wiki/doku.php&sa=D&source=editors&ust=1621930681868000&usg=AOvVaw3aFF33cUsu_B8pD9yMBQIE) (i.e., data science)
6.  [Interpretable Machine Learning book](https://www.google.com/url?q=https://christophm.github.io/interpretable-ml-book/&sa=D&source=editors&ust=1621930681868000&usg=AOvVaw0g2YIJdKA0z5UhnlrdysxX)

COST
----

1.  [GPT2/3](https://www.google.com/url?q=https://medium.com/modern-nlp/estimating-gpt3-api-cost-50282f869ab8&sa=D&source=editors&ust=1621930681869000&usg=AOvVaw3N6CL4PjNtbxqgCKhX_2--)

Patents
-------

1.  [Method Patent Exceptionalism](https://www.google.com/url?q=https://ilr.law.uiowa.edu/print/volume-102-issue-3/method-patent-exceptionalism&sa=D&source=editors&ust=1621930681870000&usg=AOvVaw1LmiTwliF-TR8PZ6QB-7fA)

General Advice
--------------

1.  (really good) [Practical advice for analysis of large, complex data sets](https://www.google.com/url?q=https://www.unofficialgoogledatascience.com/2016/10/practical-advice-for-analysis-of-large.html&sa=D&source=editors&ust=1621930681871000&usg=AOvVaw3rD-3sBpLGdgI4FTFP179V) \- distributions, outliers, examples, slices, metric significance, consistency over time, validation, description, evaluation, robustness in measurement, reproducibility, etc.

DATA SCIENCE TOOLS
==================

Python
------

[How to use better OOP in python.](https://www.google.com/url?q=https://jeffknupp.com/blog/2014/06/18/improve-your-python-python-classes-and-object-oriented-programming/&sa=D&source=editors&ust=1621930681872000&usg=AOvVaw0zKjX1NSKoPO22eInHK23H)

[Best practices programming python classes - a great lecture.](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DHTLu2DFOdTg&sa=D&source=editors&ust=1621930681872000&usg=AOvVaw0YohOpyy3swDWKhyEOEs1v)

[How to know pip packages size’](https://www.google.com/url?q=https://stackoverflow.com/questions/34266159/how-to-see-pip-package-sizes-installed&sa=D&source=editors&ust=1621930681873000&usg=AOvVaw26cUTR7lToQ2beUudqKmXy) good for removal

[Python type checking tutorial](https://www.google.com/url?q=https://medium.com/@ageitgey/learn-how-to-use-static-type-checking-in-python-3-6-in-10-minutes-12c86d72677b&sa=D&source=editors&ust=1621930681873000&usg=AOvVaw1e7KaAS9DVfPhewivlaXx9)

[Concurrency vs Parallelism (great)](https://www.google.com/url?q=https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism%23:~:text%3DConcurrency%2520is%2520when%2520two%2520or,e.g.%252C%2520on%2520a%2520multicore%2520processor.&sa=D&source=editors&ust=1621930681874000&usg=AOvVaw20tRprW59R3TXZ8YRqkkV9)

* [Async in python](https://www.google.com/url?q=https://medium.com/velotio-perspectives/an-introduction-to-asynchronous-programming-in-python-af0189a88bbb&sa=D&source=editors&ust=1621930681875000&usg=AOvVaw3GRKBvef_zTlHFxir2ofZr)

[Coroutines vs futures](https://www.google.com/url?q=https://stackoverflow.com/questions/34753401/difference-between-coroutine-and-future-task-in-python-3-5&sa=D&source=editors&ust=1621930681876000&usg=AOvVaw0FsE3Tn8wKzaXPqbt9-Peo)

1.  Coroutines[generators async wait](https://www.google.com/url?q=https://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html&sa=D&source=editors&ust=1621930681876000&usg=AOvVaw2cgXcB6j3l0lWuGNq_EyCy)
2.  [Intro to concurrent,futures](https://www.google.com/url?q=http://masnun.com/2016/03/29/python-a-quick-introduction-to-the-concurrent-futures-module.html&sa=D&source=editors&ust=1621930681877000&usg=AOvVaw0j5TKR81pKo7FJNWhUQFH-)
3.  [Future task event loop](https://www.google.com/url?q=https://masnun.com/2015/11/20/python-asyncio-future-task-and-the-event-loop.html&sa=D&source=editors&ust=1621930681877000&usg=AOvVaw3WPP_i4CSsyA9H569s_t6J)

Async io

1.  [Intro](https://www.google.com/url?q=https://realpython.com/lessons/what-asyncio/&sa=D&source=editors&ust=1621930681878000&usg=AOvVaw3_Uz_p-YZo2ojLf397Vg4Z)
2.  [complete](https://www.google.com/url?q=https://realpython.com/async-io-python/&sa=D&source=editors&ust=1621930681878000&usg=AOvVaw321AsTe11mX-sp9GTX-2MF)

Clean code:

* [Clean code in python git](https://www.google.com/url?q=https://github.com/zedr/clean-code-python&sa=D&source=editors&ust=1621930681879000&usg=AOvVaw3gUx4LTmJPJNT1PQJMs-zA)
* [About the book](https://www.google.com/url?q=https://medium.com/@m_mcclarty/tech-book-talk-clean-code-in-python-aa2c92c6564f&sa=D&source=editors&ust=1621930681879000&usg=AOvVaw1Ng5nSxntJrYW8qQgIC7nx)

Virtual Environments
--------------------

1.  [Just use venv](https://www.google.com/url?q=https://towardsdatascience.com/all-you-need-to-know-about-python-virtual-environments-9b4aae690f97&sa=D&source=editors&ust=1621930681880000&usg=AOvVaw2bGW1zvzpdGGkyHQGIC_Yo)
2.  [Summary on all the *envs](https://www.google.com/url?q=https://stackoverflow.com/questions/41573587/what-is-the-difference-between-venv-pyvenv-pyenv-virtualenv-virtualenvwrappe&sa=D&source=editors&ust=1621930681881000&usg=AOvVaw326HMWuU-5bE5PD7zSdXB_)
3.  [A really good primer on virtual environments](https://www.google.com/url?q=https://realpython.com/python-virtual-environments-a-primer/&sa=D&source=editors&ust=1621930681882000&usg=AOvVaw23LyTz7tunII5iYEouX_4X)
4.  [Introduction to venv](https://www.google.com/url?q=http://cewing.github.io/training.python_web/html/presentations/venv_intro.html&sa=D&source=editors&ust=1621930681882000&usg=AOvVaw0npm6SrEu150t2r7DNEMgP) complementary to the above
5.  [Pipenv](https://www.google.com/url?q=https://pipenv.readthedocs.io/en/latest/&sa=D&source=editors&ust=1621930681883000&usg=AOvVaw07TK0h2aw7GCBH2kgVA6dP)
6.  [A great intro to pipenv](https://www.google.com/url?q=https://realpython.com/pipenv-guide/&sa=D&source=editors&ust=1621930681883000&usg=AOvVaw2ytD3KmkWqQ-EcUXcG7BVG)
7.  [A complementary to pipenv above](https://www.google.com/url?q=https://robots.thoughtbot.com/how-to-manage-your-python-projects-with-pipenv&sa=D&source=editors&ust=1621930681883000&usg=AOvVaw2x5Iueizdy3OqERH3asNSr)
8.  [Comparison between all *env](https://www.google.com/url?q=https://stackoverflow.com/questions/41573587/what-is-the-difference-between-venv-pyvenv-pyenv-virtualenv-virtualenvwrappe&sa=D&source=editors&ust=1621930681884000&usg=AOvVaw21I4rdPmRDjvpHMEAtJ67o)

### PYENV

[Installing pyenv](https://www.google.com/url?q=https://bgasparotto.com/install-pyenv-ubuntu-debian&sa=D&source=editors&ust=1621930681884000&usg=AOvVaw3877uWZADGDiE-O2gbbKQP)

[Intro to pyenv](https://www.google.com/url?q=https://realpython.com/intro-to-pyenv/&sa=D&source=editors&ust=1621930681885000&usg=AOvVaw1JMQ9AnC7_C_ERn-iK7iLY)

[Pyenv tutorial and finding where it is](https://www.google.com/url?q=https://anil.io/blog/python/pyenv/using-pyenv-to-install-multiple-python-versions-tox/&sa=D&source=editors&ust=1621930681885000&usg=AOvVaw2zYWfKirJQioLhlv-cZ90p)

[Pyenv override system python on mac](https://www.google.com/url?q=https://github.com/pyenv/pyenv/issues/660&sa=D&source=editors&ust=1621930681885000&usg=AOvVaw3xvGiEJe9lO_IjB7601h1v)

* * *

JUPYTER
-------

* [Cloud GPUS cheap](https://www.google.com/url?q=https://www.paperspace.com/gradient&sa=D&source=editors&ust=1621930681886000&usg=AOvVaw0Vy-SF9rWnlhu6xWCIhHUU)
* [Importing a notebook as a module](https://www.google.com/url?q=http://jupyter-notebook.readthedocs.io/en/latest/examples/Notebook/Importing%2520Notebooks.html&sa=D&source=editors&ust=1621930681887000&usg=AOvVaw1QKRubGhFgm8Qrwz8l7Xki)
* Important [colaboratory commands for jupytr](https://www.google.com/url?q=https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d&sa=D&source=editors&ust=1621930681887000&usg=AOvVaw12AWVHfZCK0WCvhA8iBGtT)
* [Timing and profiling in Jupyter](https://www.google.com/url?q=http://pynash.org/2013/03/06/timing-and-profiling/&sa=D&source=editors&ust=1621930681887000&usg=AOvVaw3Lm_06IkD2klWX7X2D-wVz)
* ([Debugging in Jupyter, how?)](https://www.google.com/url?q=https://kawahara.ca/how-to-debug-a-jupyter-ipython-notebook/&sa=D&source=editors&ust=1621930681888000&usg=AOvVaw3xjBZdRMxtiTvCjp5zbXxA) \- put a one liner before the code and query the variables inside a function.
* [28 tips n tricks for jupyter](https://www.google.com/url?q=https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/&sa=D&source=editors&ust=1621930681888000&usg=AOvVaw1TPfEjBZL3A0q2O6M16owq)
* Jupyter notebooks as a module

1.  [Nbdev](https://www.google.com/url?q=https://github.com/fastai/nbdev&sa=D&source=editors&ust=1621930681888000&usg=AOvVaw07D7oKDi5MUwcPdkoZiOzS), on[fast.ai](https://www.google.com/url?q=https://www.fast.ai/2019/12/02/nbdev/&sa=D&source=editors&ust=1621930681889000&usg=AOvVaw3jwvz1pKx2FFyXXrUVchay)
2.  [jupytext](https://www.google.com/url?q=https://github.com/mwouts/jupytext&sa=D&source=editors&ust=1621930681889000&usg=AOvVaw3kP3UDg-Ym9XSZqzYwdxDs)

* [Virtual environments in jupyter](https://www.google.com/url?q=https://anbasile.github.io/programming/2017/06/25/jupyter-venv/&sa=D&source=editors&ust=1621930681889000&usg=AOvVaw0KdTdWlqcJkfM5-kJA4KxO)

1.  Enter your project directory
2.  $ python -m venv projectname
3.  $ source projectname/bin/activate
4.  (venv) $ pip install ipykernel
5.  (venv) $ ipython kernel install --user --name=projectname
6.  Run jupyter notebook \* (not entirely sure how this works out when you have multiple notebook processes, can we just reuse the same server?)
7.  Connect to the new server at port 8889

* [Virtual env with jupyter](https://www.google.com/url?q=https://janakiev.com/til/jupyter-virtual-envs/&sa=D&source=editors&ust=1621930681891000&usg=AOvVaw2VmFvTqdbIqMzr3L6LJT3b)

([how does reshape work?)](https://www.google.com/url?q=http://anie.me/numpy-reshape-transpose-theano-dimshuffle/&sa=D&source=editors&ust=1621930681891000&usg=AOvVaw1X9BbgiiwaXmiR0YSzCXDS) \-  a shape of (2,4,6) is like a tree of 2->4 and each one has more leaves 4->6.

As far as i can tell, reshape effectively flattens the tree and divide it again to a new tree, but the total amount of inputs needs to stay the same. 2\*4\*6 = 4\*2\*3*2 for example

code:

import numpy

rng = numpy.random.RandomState(234)

a = rng.randn(2,3,10)

print(a.shape)

print(a)

b = numpy.reshape(a, (3,5,-1))

print(b.shape)

print (b)

\*\*\* A tutorial for [Google Colaboratory - free Tesla K80 with Jup-notebook](https://www.google.com/url?q=https://www.kdnuggets.com/2018/02/google-colab-free-gpu-tutorial-tensorflow-keras-pytorch.html/2&sa=D&source=editors&ust=1621930681892000&usg=AOvVaw14JUs_vX7-6dLtVoTaZAdy)

[Jupyter on Amazon AWS](https://www.google.com/url?q=https://blog.keras.io/running-jupyter-notebooks-on-gpu-on-aws-a-starter-guide.html&sa=D&source=editors&ust=1621930681893000&usg=AOvVaw1cr2c88uZdY-yBzeqaLiM8)

How to add extensions to jupyter: [extensions](https://www.google.com/url?q=https://codeburst.io/jupyter-notebook-tricks-for-data-science-that-enhance-your-efficiency-95f98d3adee4&sa=D&source=editors&ust=1621930681893000&usg=AOvVaw3ay62Jyj4ldUS9kui0JZxQ)

[Connecting from COLAB to MS AZURE](https://www.google.com/url?q=https://medium.com/@d.sakryukin/simple-cryptocurrency-trading-data-preparation-in-15-minutes-using-ms-azure-and-google-colab-44872b023d11&sa=D&source=editors&ust=1621930681894000&usg=AOvVaw0da162Vh9AQ7Bspgu8KPmT)

[Streamlit vs. Dash vs. Shiny vs. Voila vs. Flask vs. Jupyter](https://www.google.com/url?q=https://towardsdatascience.com/streamlit-vs-dash-vs-shiny-vs-voila-vs-flask-vs-jupyter-24739ab5d569&sa=D&source=editors&ust=1621930681894000&usg=AOvVaw2bXsH-0TE5Vv3bE8opYMUO)

SCIPY
-----

1.  [Optimization problems, a nice tutorial](https://www.google.com/url?q=http://scipy-lectures.org/advanced/mathematical_optimization/&sa=D&source=editors&ust=1621930681895000&usg=AOvVaw2qSmNeuVpOUqT_iYkCTGQs) to finding the minima
2.  [Minima / maxima](https://www.google.com/url?q=https://stackoverflow.com/questions/4624970/finding-local-maxima-minima-with-numpy-in-a-1d-numpy-array&sa=D&source=editors&ust=1621930681895000&usg=AOvVaw1FE-0guxpGbXLs71_z9ujX) finding it in a 1d numpy array

NUMPY
-----

[Using numpy efficiently](https://www.google.com/url?q=https://speakerdeck.com/cournape/using-numpy-efficiently&sa=D&source=editors&ust=1621930681896000&usg=AOvVaw21RKfNjOc_rWWBezzZKcA0) \- explaining why vectors work faster.

  
[Fast vector calculation, a benchmark](https://www.google.com/url?q=https://towardsdatascience.com/data-science-with-python-turn-your-conditional-loops-to-numpy-vectors-9484ff9c622e&sa=D&source=editors&ust=1621930681896000&usg=AOvVaw1rT0L13SaO4_asmUVW10er) between list, map, vectorize. Vectorize wins. The idea is to use vectorize and a function that does something that may involve if conditions on a vector, and do it as fast as possible.

* * *

PANDAS
------

1.  [Great introductory tutorial](https://www.google.com/url?q=http://nikgrozev.com/2015/12/27/pandas-in-jupyter-quickstart-and-useful-snippets/%23loading_csv_files&sa=D&source=editors&ust=1621930681897000&usg=AOvVaw03MPXwjtloE5crHBvh3PuM) about using pandas, loading, loading from zip, seeing the table’s features, accessing rows & columns, boolean operations, calculating on a whole row\\column with a simple function and on two columns even, dealing with time\\date parsing.
2.  [Visualizing pandas pivoting and reshaping functions by Jay Alammar](https://www.google.com/url?q=http://jalammar.github.io/visualizing-pandas-pivoting-and-reshaping/&sa=D&source=editors&ust=1621930681897000&usg=AOvVaw1gH8P1D3mdXMwGy7Aajio4) \- pivot melt stack unstack
3.  [How to beautify pandas dataframe using html display](https://www.google.com/url?q=https://stackoverflow.com/questions/26873127/show-dataframe-as-table-in-ipython-notebook&sa=D&source=editors&ust=1621930681898000&usg=AOvVaw3CutkWmGTn2NaS2dLAoGuy)
4.  [Speeding up pandas](https://www.google.com/url?q=https://realpython.com/fast-flexible-pandas/&sa=D&source=editors&ust=1621930681898000&usg=AOvVaw0JzREw71qCfSuX-V55XGHV)
5.  [Pandas summary](https://www.google.com/url?q=https://github.com/mouradmourafiq/pandas-summary&sa=D&source=editors&ust=1621930681898000&usg=AOvVaw1xCK9fqsywSN1VKluMtWqA)
6.  [Pandas html profiling](https://www.google.com/url?q=https://github.com/pandas-profiling/pandas-profiling&sa=D&source=editors&ust=1621930681899000&usg=AOvVaw014QDR1YSvTi4OJQJr5CIW)
7.  [The fastest way to select rows by columns, by using masked values](https://www.google.com/url?q=https://stackoverflow.com/questions/17071871/select-rows-from-a-dataframe-based-on-values-in-a-column-in-pandas&sa=D&source=editors&ust=1621930681899000&usg=AOvVaw3w7xs6o61YUcFUMdM_iAp1) (benchmarked):
8.  def mask\_with\_values(df): mask = df\['A'\].values == 'foo'return df\[mask\]
9.  [Parallelism, pools, threads, dask](https://www.google.com/url?q=https://towardsdatascience.com/speed-up-your-algorithms-part-3-parallelization-4d95c0888748%237e6e&sa=D&source=editors&ust=1621930681900000&usg=AOvVaw1zKhNHo-H1_ZNBZJItwHmY)
10. [Accessing dataframe rows, columns and cells](https://www.google.com/url?q=http://pythonhow.com/accessing-dataframe-columns-rows-and-cells/&sa=D&source=editors&ust=1621930681900000&usg=AOvVaw2KmE29D3q4rG6XYP57SIhy)\- by name, by index, by python methods.
11. [Looping through pandas](https://www.google.com/url?q=https://medium.com/swlh/how-to-efficiently-loop-through-pandas-dataframe-660e4660125d&sa=D&source=editors&ust=1621930681901000&usg=AOvVaw3lQd3JqfIJ_kDDc1wxYkEd)
12. [How to inject headers into a headless CSV file](https://www.google.com/url?q=http://pythonforengineers.com/introduction-to-pandas/&sa=D&source=editors&ust=1621930681901000&usg=AOvVaw20-zlW1wDZ-m4uwuzNanHB) -
13. [Dealing with time series](https://www.google.com/url?q=http://pandas.pydata.org/pandas-docs/stable/timeseries.html&sa=D&source=editors&ust=1621930681901000&usg=AOvVaw1kv0kyZkViuX3mO3gzaWfM) in pandas,

1.  [Create a new column](https://www.google.com/url?q=https://stackoverflow.com/questions/25570147/add-new-column-based-on-boolean-values-in-a-different-column&sa=D&source=editors&ust=1621930681902000&usg=AOvVaw1nDCt8SK2HNxVPGuDM2sZ5) based on a (boolean or not) column and calculation:
2.  Using python (map)
3.  Using numpy
4.  using a function (not as pretty)

14. Given a DataFrame, the [shift](https://www.google.com/url?q=http://machinelearningmastery.com/convert-time-series-supervised-learning-problem-python/&sa=D&source=editors&ust=1621930681902000&usg=AOvVaw2eq2Lnfkdu6meMDAP3JojV)() function can be used to create copies of columns that are pushed forward (rows of NaN values added to the front) or pulled back (rows of NaN values added to the end).

1.  df\['t'\] = \[x for x in range(10)\]
2.  df\['t-1'\] = df\['t'\].shift(1)
3.  df\['t-1'\] = df\['t'\].shift(-1)

15. [Row and column sum in pandas and numpy](https://www.google.com/url?q=http://blog.mathandpencil.com/column-and-row-sums&sa=D&source=editors&ust=1621930681903000&usg=AOvVaw2NHh3O_FPdrSsJ7lRXZZyz)
16. [Dataframe Validation In Python](https://www.google.com/url?q=https://www.youtube.com/watch?time_continue%3D905%26v%3D1fHGXOfiDO0&sa=D&source=editors&ust=1621930681903000&usg=AOvVaw1bl6AdirlCcYJwbYKhV4PL) \- A Practical Introduction - Yotam Perkal - PyCon Israel 2018
17. In this talk, I will present the problem and give a practical overview (accompanied by Jupyter Notebook code examples) of three libraries that aim to address it: Voluptuous - Which uses Schema definitions in order to validate data \[[https://github.com/alecthomas/voluptuous](https://www.google.com/url?q=https://www.youtube.com/redirect?v%3D1fHGXOfiDO0%26event%3Dvideo_description%26redir_token%3DjIIzdRAEjZBpzVhRYfFzTcx52358MTU0NzQ0ODY3N0AxNTQ3MzYyMjc3%26q%3Dhttps%253A%252F%252Fgithub.com%252Falecthomas%252Fvoluptuous&sa=D&source=editors&ust=1621930681904000&usg=AOvVaw2GUwOq8Xxiu1yUmCwd0jif)\] Engarde - A lightweight way to explicitly state your assumptions about the data and check that they're actually true \[[https://github.com/TomAugspurger/engarde](https://www.google.com/url?q=https://www.youtube.com/redirect?v%3D1fHGXOfiDO0%26event%3Dvideo_description%26redir_token%3DjIIzdRAEjZBpzVhRYfFzTcx52358MTU0NzQ0ODY3N0AxNTQ3MzYyMjc3%26q%3Dhttps%253A%252F%252Fgithub.com%252FTomAugspurger%252Fengarde&sa=D&source=editors&ust=1621930681905000&usg=AOvVaw0JUd4gyYUFDtasPWtlG1PU)\] \* TDDA - Test Driven Data Analysis \[[https://github.com/tdda/tdda](https://www.google.com/url?q=https://github.com/tdda/tdda&sa=D&source=editors&ust=1621930681905000&usg=AOvVaw1HgEElLPcQyS_WKq-TvVkm)\]. By the end of this talk, you will understand the Importance of data validation and get a sense of how to integrate data validation principles as part of the ML pipeline.
18. [Stop using itterows](https://www.google.com/url?q=https://medium.com/@rtjeannier/pandas-101-cont-9d061cb73bfc&sa=D&source=editors&ust=1621930681906000&usg=AOvVaw1ZMdv7KMXQct0tcws4FYuv), use apply.
19. [(great)](https://www.google.com/url?q=https://jamesrledoux.com/code/group-by-aggregate-pandas&sa=D&source=editors&ust=1621930681907000&usg=AOvVaw3OF5UE_jv8OzGT0JubZ2v_) [Group and Aggregate by One or More Columns in Pandas](https://www.google.com/url?q=https://jamesrledoux.com/code/group-by-aggregate-pandas&sa=D&source=editors&ust=1621930681907000&usg=AOvVaw3OF5UE_jv8OzGT0JubZ2v_)
20. [Pandas Groupby: Summarising, Aggregating, and Grouping data in Python](https://www.google.com/url?q=https://www.shanelynn.ie/summarising-aggregation-and-grouping-data-in-python-pandas/%23applying-multiple-functions-to-columns-in-groups&sa=D&source=editors&ust=1621930681908000&usg=AOvVaw3IQne5YXzbpdX9O29tzlaf)

### TIMESERIES

1.  (good) [Pandas time series manipulation](https://www.google.com/url?q=https://towardsdatascience.com/practical-guide-for-time-series-analysis-with-pandas-196b8b46858f&sa=D&source=editors&ust=1621930681908000&usg=AOvVaw3tt1iHtRNF0oGwRQRPZH4m)
2.  [Using resample](https://www.google.com/url?q=https://towardsdatascience.com/using-the-pandas-resample-function-a231144194c4&sa=D&source=editors&ust=1621930681909000&usg=AOvVaw0VlOb8xwfLiaRKHLhtlxNx)

![](images/image260.png)

3.  [Basic TS manipulation](https://www.google.com/url?q=https://towardsdatascience.com/basic-time-series-manipulation-with-pandas-4432afee64ea&sa=D&source=editors&ust=1621930681910000&usg=AOvVaw0mhVCIHAH2hrPDJbblsbBj)
4.  [Fill missing ts gaps, or how to resample](https://www.google.com/url?q=https://stackoverflow.com/questions/32241692/fill-missing-timeseries-data-using-pandas-or-numpy&sa=D&source=editors&ust=1621930681910000&usg=AOvVaw23i0LSijRWCRl5RYWwrYrr)

* * *

SCI-KIT LEARN
-------------

1.  Pipeline t[o json 1](https://www.google.com/url?q=https://cmry.github.io/notes/serialize&sa=D&source=editors&ust=1621930681911000&usg=AOvVaw1YyNDxGuwGrAXZePXh6MS1), [2](https://www.google.com/url?q=https://cmry.github.io/notes/serialize-sk&sa=D&source=editors&ust=1621930681911000&usg=AOvVaw09AM6sWRoTJKl5P7JXDFeH)
2.  [cuML](https://www.google.com/url?q=https://github.com/rapidsai/cuml&sa=D&source=editors&ust=1621930681911000&usg=AOvVaw2eGr7HM4gMZ5ih2R5SQAVd) \- Multi gpu, multi node-gpu alternative for SKLEARN algorithms
3.  [Gpu TSNE ^](https://www.google.com/url?q=https://www.reddit.com/r/MachineLearning/comments/e0j9cb/p_2000x_faster_rapids_tsne_3_hours_down_to_5/?utm_source%3Dshare%26utm_medium%3Dios_app%26utm_name%3Diossmf&sa=D&source=editors&ust=1621930681912000&usg=AOvVaw3VjA749MO-Zpk9nqv4VZX6)
4.  [Awesome code examples](https://www.google.com/url?q=http://machinelearningmastery.com/get-your-hands-dirty-with-scikit-learn-now/&sa=D&source=editors&ust=1621930681912000&usg=AOvVaw0PEfB_6xNw-KAoVS6YQ7-o) about using svm\\knn\\naive\\log regression in sklearn in python, i.e., “fitting a model onto the data”
5.  [Parallelism of numpy, pandas and sklearn using dask and clusters](https://www.google.com/url?q=https://github.com/dask/dask&sa=D&source=editors&ust=1621930681913000&usg=AOvVaw0zn82_-zdwnF0KD9RGolHQ). [Webpage](https://www.google.com/url?q=https://dask.pydata.org/en/latest/&sa=D&source=editors&ust=1621930681913000&usg=AOvVaw2bQ-Bv-CRJFNlJAKq-2U7Y), [docs](https://www.google.com/url?q=http://dask-ml.readthedocs.io/en/latest/index.html&sa=D&source=editors&ust=1621930681913000&usg=AOvVaw0u0cXkV13OnVEzc37Ou84_), [example in jupyter](https://www.google.com/url?q=https://hub.mybinder.org/user/dask-dask-examples-6bi4j3qj/notebooks/machine-learning.ipynb&sa=D&source=editors&ust=1621930681914000&usg=AOvVaw2PSTIUGft6XQuiHjuekoca).

Also Insanely fast, [see here](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D5Zf6DQaf7jk&sa=D&source=editors&ust=1621930681914000&usg=AOvVaw1_nNqCVipIxQ29WOG0djkV).

6.  [Functional api for sk learn](https://www.google.com/url?q=https://scikit-lego.readthedocs.io/en/latest/preprocessing.html&sa=D&source=editors&ust=1621930681914000&usg=AOvVaw2aD8yLNrs9ByT8nGms8dlM), using pipelines. thank you sk-lego.
7.  ![](images/image81.png)![](images/image225.png)![](images/image199.png)

FAST.AI
-------

1.  [Medium](https://www.google.com/url?q=https://medium.com/@hiromi_suenaga/deep-learning-2-part-1-lesson-1-602f73869197&sa=D&source=editors&ust=1621930681915000&usg=AOvVaw0vrXT07DwAczcwUNjB13Tc) on all fast.ai courses, 14 posts

PYCARET
-------

[1\. What is? by vidhaya](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2020/05/pycaret-machine-learning-model-seconds/?utm_source%3DAVFacebook%26utm_medium%3Dpost%26utm_campaign%3D19_june_intermediate_article%26fbclid%3DIwAR0NZV5fJgXtpoCBfmauCiGQC_QOK0cbQrpuhhpDBAtEngGG_NBsRlcVRas&sa=D&source=editors&ust=1621930681916000&usg=AOvVaw3ZiMvrEuvsyJfoKLsgiNWP)\- [PyCaret](https://www.google.com/url?q=https://pycaret.org/&sa=D&source=editors&ust=1621930681916000&usg=AOvVaw3VY_EVwmI4EuQwXgh1jMeB) is an open-source, machine learning library in Python that helps you from data preparation to model deployment. It is easy to use and you can do almost every data science project task with just one line of code.

NVIDIA TF CUDA CUDNN
--------------------

* [Install TF](https://www.google.com/url?q=https://www.tensorflow.org/install/install_linux%23NVIDIARequirements&sa=D&source=editors&ust=1621930681917000&usg=AOvVaw24qIYInaIBUbyoV8k01m1N)
* [Install cuda on ubuntu](https://www.google.com/url?q=https://devtalk.nvidia.com/default/topic/1030495/cuda-setup-and-installation/install-a-specific-cuda-version-for-ubuntu-16-04/&sa=D&source=editors&ust=1621930681917000&usg=AOvVaw3FMH4wYfpBDrAYWOBHj2v3), [official linux](https://www.google.com/url?q=https://docs.nvidia.com/cuda/cuda-installation-guide-linux/&sa=D&source=editors&ust=1621930681917000&usg=AOvVaw0kM-IoeaaddSeYKMgzmF4b)
* [Replace cuda version](https://www.google.com/url?q=https://askubuntu.com/questions/959835/how-to-remove-cuda-9-0-and-install-cuda-8-0-instead&sa=D&source=editors&ust=1621930681918000&usg=AOvVaw1ZFL9WAVtjoFd9-lqLSddA)
* [Cuda 9 download](https://www.google.com/url?q=https://developer.nvidia.com/cuda-90-download-archive?target_os%3DLinux%26target_arch%3Dx86_64%26target_distro%3DUbuntu%26target_version%3D1704%26target_type%3Drunfilelocal&sa=D&source=editors&ust=1621930681918000&usg=AOvVaw3q_9GrsWnkt6fYKiF_HDGL)
* [Install cudnn](https://www.google.com/url?q=https://askubuntu.com/questions/1033489/the-easy-way-install-nvidia-drivers-cuda-cudnn-and-tensorflow-gpu-on-ubuntu-1&sa=D&source=editors&ust=1621930681919000&usg=AOvVaw2ySdDBe2NCNc2sPc2KzRQc)
* [Installing everything easily](https://www.google.com/url?q=https://askubuntu.com/questions/1033489/the-easy-way-install-nvidia-drivers-cuda-cudnn-and-tensorflow-gpu-on-ubuntu-1&sa=D&source=editors&ust=1621930681919000&usg=AOvVaw2ySdDBe2NCNc2sPc2KzRQc)
* [Failed](https://www.google.com/url?q=https://stackoverflow.com/questions/43022843/nvidia-nvml-driver-library-version-mismatch&sa=D&source=editors&ust=1621930681919000&usg=AOvVaw21k5g10O80-o1FUqCmSkAm) to initialize NVML: Driver/library version mismatch

GCP
---

[Resize google disk size](https://www.google.com/url?q=https://medium.com/google-cloud/resize-your-persist-disk-on-google-cloud-on-the-fly-b3491277b718&sa=D&source=editors&ust=1621930681920000&usg=AOvVaw09j-ZesT2ireHKYJxaxS5q), [1,](https://www.google.com/url?q=https://cloud.google.com/compute/docs/disks/add-persistent-disk&sa=D&source=editors&ust=1621930681920000&usg=AOvVaw1qw7RhPRZJGkso9SizkqRb)[2](https://www.google.com/url?q=https://www.cloudbooklet.com/how-to-resize-disk-of-a-vm-instance-in-google-cloud/&sa=D&source=editors&ust=1621930681920000&usg=AOvVaw3fY4bARyDabL5iwU5y7uCL),

 SQL
----

1.  [Introduction, index, keys, joins, aliases etc.](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DnWeW3sCmD2k&sa=D&source=editors&ust=1621930681921000&usg=AOvVaw0pz1eVXbcxz0sjiG9bNEro), [newer](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D9ylj9NR0Lcg&sa=D&source=editors&ust=1621930681921000&usg=AOvVaw0KaA7e8_Q-5Rw18bZuMJ0R)
2.  [Sql cheat sheet](https://www.google.com/url?q=https://gist.github.com/bradtraversy/c831baaad44343cc945e76c2e30927b3&sa=D&source=editors&ust=1621930681922000&usg=AOvVaw1L02CZ8aJbzGRVwMGQM8GB)
3.  [Primary key](https://www.google.com/url?q=https://www.eukhost.com/blog/webhosting/whats-the-purpose-use-primary-foreign-keys/&sa=D&source=editors&ust=1621930681922000&usg=AOvVaw1ECXa_LLbaDDRvMj1hsFMu)
4.  [Foreign key, a key constraint that is included in the primary key allowed values](https://www.google.com/url?q=https://www.1keydata.com/sql/sql-foreign-key.html&sa=D&source=editors&ust=1621930681922000&usg=AOvVaw0Xl-Fb-_fzVwtrgHh7IJ4-)
5.  [Index, i.e., book index for fast reading](https://www.google.com/url?q=https://www.tutorialspoint.com/sql/sql-indexes.htm&sa=D&source=editors&ust=1621930681923000&usg=AOvVaw0Nfp3TTZGdMzJwKeuf_shG)

GIT / Bitbucket
---------------

1.  [Installing git LFS](https://www.google.com/url?q=https://askubuntu.com/questions/799341/how-to-install-git-lfs-on-ubuntu-16-04&sa=D&source=editors&ust=1621930681924000&usg=AOvVaw14oise0ow345rLuzVt2hu1)
2.  [Use git lfs](https://www.google.com/url?q=https://confluence.atlassian.com/bitbucket/use-git-lfs-with-bitbucket-828781636.html&sa=D&source=editors&ust=1621930681924000&usg=AOvVaw3_wQs5bEI8uYgLSUK6ie1Y)
3.  [Download git-lfs](https://www.google.com/url?q=https://git-lfs.github.com/&sa=D&source=editors&ust=1621930681925000&usg=AOvVaw3nhOt9OvxuuMtQXFnFx4uF)
4.  [Git wip](https://www.google.com/url?q=https://carolynvanslyck.com/blog/2020/12/git-wip/&sa=D&source=editors&ust=1621930681925000&usg=AOvVaw3Poxcpv077AgXOMmKDQULg) (great)  
    ![](images/image219.png)

* * *

MANAGEMENT
==========

Style
-----

1.  [7 management styles and how to use them](https://www.google.com/url?q=https://www.breathehr.com/en-gb/blog/topic/business-leadership/best-management-styles-and-how-to-use-them&sa=D&source=editors&ust=1621930681926000&usg=AOvVaw0606WUU1vYod9c6-uZg5iv)
2.  7 leadership styles (similar to the above)
3.  [The secret sauce of DS management](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DqO7sl8_YtJM&sa=D&source=editors&ust=1621930681927000&usg=AOvVaw0KWqAiVx1GWTQ6QccU7Ezr)

Books
-----

1.  People management

1.  (good) the effective manager
2.  radical candor
3.  managing humans

2.  Company Management

1.  The CEO within
2.  business without the bullshit

3.  Collaborations and influence

1.  (good) crucial conversations

4.  Negotiations

1.  never split the difference

5.  Manipulations

1.  The prince
2.  [The 48 Laws of Power](https://www.google.com/url?q=https://www.amazon.com/48-Laws-Power-Robert-Greene/dp/0140280197&sa=D&source=editors&ust=1621930681929000&usg=AOvVaw26t6Yn0gvCog0ALR2hQmfE) \- “Amoral, cunning, ruthless, and instructive, this multi-million-copy New York Times bestseller is the definitive manual for anyone interested in gaining, observing, or defending against ultimate control – from the author of The Laws of Human Nature.

6.  Others

1.  (good) High output management
2.  multipliers,
3.  radical candor,
4.  Trillion dollar coach,
5.  The HP way,
6.  How to measure anything,
7.  Mindset,
8.  (good) The hard thing about hard things

* * *

DATA SCIENCE MANAGEMENT
=======================

INTERVIEW Qs
------------

1.  [40 questions on ensembles](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2017/02/40-questions-to-ask-a-data-scientist-on-ensemble-modeling-techniques-skilltest-solution/?utm_source%3Dfacebook.com%26utm_medium%3Dsocial&sa=D&source=editors&ust=1621930681931000&usg=AOvVaw2wjc2SwEyF6Ke2mNxmh2-m)
2.  [30 on trees](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2017/09/30-questions-test-tree-based-models/?utm_source%3Dfacebook.com%26utm_medium%3Dsocial&sa=D&source=editors&ust=1621930681931000&usg=AOvVaw0_fWUR3_QiAyRf5h3BGJ6A)
3.  [30 on knns](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2017/09/30-questions-test-k-nearest-neighbors-algorithm/?utm_source%3Dfacebook.com%26utm_medium%3Dsocial%26fbclid%3DIwAR0JgeXKfyLGndL2_eMX7R6HLVY9la97V6QMIYb_4LnG56N-x1Oe5DsdhqE&sa=D&source=editors&ust=1621930681932000&usg=AOvVaw1U-HBJRP57II42RT7yWhFt)

Politics
--------

1.  [The most difficult thing in ds, politics](https://www.google.com/url?q=https://towardsdatascience.com/the-most-difficult-thing-in-data-science-politics-ca6dd781da56&sa=D&source=editors&ust=1621930681933000&usg=AOvVaw3vuB_bvUad5UTZymtFsjZF)

HIRING / RECRUITING
-------------------

1.  [Data engineer skills](https://www.google.com/url?q=https://medium.com/@m_mcclarty/data-engineering-interview-guide-7a14d10887dd&sa=D&source=editors&ust=1621930681933000&usg=AOvVaw3QQWsHuEOolnyxPyUe8ZtQ) on medium

1.  Coding (Typically Python)
2.  SQL
3.  Database design
4.  Data architecture/big data technologies
5.  Soft skills

WRITING DOCS
------------

1.  [Design docs at google](https://www.google.com/url?q=https://www.industrialempathy.com/posts/design-docs-at-google/&sa=D&source=editors&ust=1621930681934000&usg=AOvVaw3Qz-aB8NuyHhj1vEpW3gOz)

LEGAL & CONTRACTS
-----------------

1.  [(FAST) Advisory board saas agreement](https://www.google.com/url?q=https://fi.co/fast&sa=D&source=editors&ust=1621930681935000&usg=AOvVaw251BBhQdysFMbrhOikA56t)

* * *

CALCULUS
========

[Start here!](https://www.google.com/url?q=http://parrt.cs.usfca.edu/doc/matrix-calculus/&sa=D&source=editors&ust=1621930681936000&usg=AOvVaw0Fgr4RSowtdtUnLgGUr9d4)

* * *

PROBABILITY AND STATISTICS
==========================

[Coursera course](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DWkOinijQmPU%26list%3DPLpl-gQkQivXiBmGyzLrUjzsblmQsLtkzJ%26index%3D1&sa=D&source=editors&ust=1621930681937000&usg=AOvVaw34MIGzNpV_gwf3fY0GtQlJ) on probabilities - for data science, actually quite good in explaining a lot of the basic tools,prob, conditional, distributions, sampling, CI, hypothesis, etc.

* [A great resource for proba/bayes/b-networks/etc](https://www.google.com/url?q=https://metacademy.org/graphs/concepts/bayesian_networks%23focus%3Di9mo2e09%26mode%3Dlearn&sa=D&source=editors&ust=1621930681937000&usg=AOvVaw1U1emY-oaSFzVPrZJayo0Y) (adam bali)

[Difference between](https://www.google.com/url?q=https://stats.stackexchange.com/questions/665/whats-the-difference-between-probability-and-statistics&sa=D&source=editors&ust=1621930681938000&usg=AOvVaw3tmTXLsfOtW4_EQpYAkC6L)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* I.e, Probabilitydeals with predicting the likelihood of future events, while statisticsinvolves the analysis of the frequency of past events. 
* The problems considered by probability and statistics are inverse to each other.

* In probability theory we consider some underlying process which has some randomness or uncertainty modeled by random variables, and we figure out what happens.

=\> Underlying process + randomness and random variables -> what happens next?

* In statistics we observe something that has happened, and try to figure out what underlying process would explain those observations.

=>observe what happened -> what is the underlying process?

* Finally, probability theory is mainly concerned with the deductive part, statistics with the inductive part of modeling processes with uncertainty

Introduction to statistics
--------------------------

1.  [Table of](https://www.google.com/url?q=https://www.mathsisfun.com/data/index.html%23stats&sa=D&source=editors&ust=1621930681939000&usg=AOvVaw1Ot3G9Wlj0v-8lMAoBw35R) content
2.  [Median](https://www.google.com/url?q=https://www.mathsisfun.com/median.html&sa=D&source=editors&ust=1621930681940000&usg=AOvVaw2vIvTBoqwKw52QpwH6KUDB)
3.  [Mode](https://www.google.com/url?q=https://www.mathsisfun.com/mode.html&sa=D&source=editors&ust=1621930681940000&usg=AOvVaw21NHbUnsnMBT8QaHFj7UGo) \- most freq
4.  [Weighted mean](https://www.google.com/url?q=https://www.mathsisfun.com/data/weighted-mean.html&sa=D&source=editors&ust=1621930681941000&usg=AOvVaw1J78dbYiYujk3MT0fJXHOc)
5.  [Geometric mean](https://www.google.com/url?q=https://www.mathsisfun.com/numbers/geometric-mean.html&sa=D&source=editors&ust=1621930681941000&usg=AOvVaw0vRxbH5rGphwkLdT7ITxdr)
6.  [Harmonic mean](https://www.google.com/url?q=https://www.mathsisfun.com/numbers/harmonic-mean.html&sa=D&source=editors&ust=1621930681941000&usg=AOvVaw2WPJHTvdboIRJU_7Du9YBW)
7.  [Percentiles](https://www.google.com/url?q=https://www.mathsisfun.com/data/percentiles.html&sa=D&source=editors&ust=1621930681942000&usg=AOvVaw2IBDZ7btUmQBRavLxhv7D2)
8.  [Mean deviation](https://www.google.com/url?q=https://www.mathsisfun.com/data/mean-deviation.html&sa=D&source=editors&ust=1621930681942000&usg=AOvVaw2YGfOiEX3ZCxdE5AxUYsXz)
9.  [Correlation](https://www.google.com/url?q=https://www.mathsisfun.com/data/correlation.html&sa=D&source=editors&ust=1621930681943000&usg=AOvVaw0P9SFQQZPSdrCOGqt3yAPo)
10. [Standard deviation](https://www.google.com/url?q=https://www.mathsisfun.com/data/standard-deviation.html&sa=D&source=editors&ust=1621930681943000&usg=AOvVaw0vpLPzrX2mhVXAv4waV0Hm), [formula](https://www.google.com/url?q=https://www.mathsisfun.com/data/standard-deviation-formulas.html&sa=D&source=editors&ust=1621930681944000&usg=AOvVaw2NrYyzsTgdwnXpzw073xct)
11. [Standard normal distribution](https://www.google.com/url?q=https://www.mathsisfun.com/data/standard-normal-distribution.html&sa=D&source=editors&ust=1621930681944000&usg=AOvVaw2SSoq57p5ILO4zK4BjBCiI)
12. [Skewness of distribution](https://www.google.com/url?q=https://www.mathsisfun.com/data/skewness.html&sa=D&source=editors&ust=1621930681945000&usg=AOvVaw23FFFfw4wWIgnIpY-xKEkz)
13. [Confidence intervals (using std)](https://www.google.com/url?q=https://www.mathsisfun.com/data/confidence-interval.html&sa=D&source=editors&ust=1621930681945000&usg=AOvVaw23xKTIsvRZZk3U0ri75_n7)
14. [Accuracy vs precision (accurate vs hitting closely or density)](https://www.google.com/url?q=https://www.mathsisfun.com/accuracy-precision.html&sa=D&source=editors&ust=1621930681946000&usg=AOvVaw00j023duVPCwZWLcrnZzRL)
15. [Probability](https://www.google.com/url?q=https://www.mathsisfun.com/data/probability.html&sa=D&source=editors&ust=1621930681946000&usg=AOvVaw3OXTFUJjLpYhM-RrEYIuRZ)
16. [Probability complement](https://www.google.com/url?q=https://www.mathsisfun.com/data/probability-complement.html&sa=D&source=editors&ust=1621930681947000&usg=AOvVaw2Kah-CDGNkmKHGnSwQPc0A)
17. [Chi-square test, p_value, independent, dependent, significance](https://www.google.com/url?q=https://www.mathsisfun.com/data/chi-square-test.html&sa=D&source=editors&ust=1621930681947000&usg=AOvVaw2wtlxfODjIcJ_UBwJ5mZxg)
18. [Variation vs variance](https://www.google.com/url?q=https://stats.stackexchange.com/questions/88348/is-variation-the-same-as-variance&sa=D&source=editors&ust=1621930681948000&usg=AOvVaw1Kp8tqxum9XW-LD_LOunwH) \- a private case
19. [Std vs variance](https://www.google.com/url?q=https://www.investopedia.com/ask/answers/021215/what-difference-between-standard-deviation-and-variance.asp&sa=D&source=editors&ust=1621930681948000&usg=AOvVaw1V6ZY8ME52WPfZ_D-7D7dv) \- std is in the same metric as the mean, is the root of variance., allows outliers to influence, will not result in samples cancelling each other without the square root in the formula.

Introduction to Probability
---------------------------

1.  [Types of events](https://www.google.com/url?q=https://www.mathsisfun.com/data/probability-events-types.html&sa=D&source=editors&ust=1621930681950000&usg=AOvVaw1fDPF6Yg_2clO3zDr2aOCh)
2.  [Independent events](https://www.google.com/url?q=https://www.mathsisfun.com/data/probability-events-independent.html&sa=D&source=editors&ust=1621930681950000&usg=AOvVaw11S1Odira-QdQCQ2y97gCe)
3.  [Conditional proba](https://www.google.com/url?q=https://www.mathsisfun.com/data/probability-events-conditional.html&sa=D&source=editors&ust=1621930681951000&usg=AOvVaw0Erk1I1fjrt70LxMBqlniP)
4.  [Proba tree diagrams](https://www.google.com/url?q=https://www.mathsisfun.com/data/probability-tree-diagrams.html&sa=D&source=editors&ust=1621930681951000&usg=AOvVaw1DTDYOXZMbAPbcmvwJZ0Gr)
5.  [Mutually exclusive events](https://www.google.com/url?q=https://www.mathsisfun.com/data/probability-events-mutually-exclusive.html&sa=D&source=editors&ust=1621930681952000&usg=AOvVaw1s3V9h6F75nHkbrbmLPq-6)
6.  [Combination and permutations](https://www.google.com/url?q=https://www.mathsisfun.com/combinatorics/combinations-permutations.html&sa=D&source=editors&ust=1621930681952000&usg=AOvVaw2v3JV3ehaIj3LY54kA0Z1W)
7.  [Bayes](https://www.google.com/url?q=https://www.mathsisfun.com/data/bayes-theorem.html&sa=D&source=editors&ust=1621930681953000&usg=AOvVaw0Mwz9HHRvbGpnlfYgu7WrB)
8.  [Least squares regresssion](https://www.google.com/url?q=https://www.mathsisfun.com/data/least-squares-regression.html&sa=D&source=editors&ust=1621930681953000&usg=AOvVaw2EotDwZAJmi1iswBc6XeJi) It works by making the total of the square of the errors as small as possible (that is why it is called "least squares"
9.  [Random variables](https://www.google.com/url?q=https://www.mathsisfun.com/data/random-variables.html&sa=D&source=editors&ust=1621930681953000&usg=AOvVaw1XCfxV824OBQAMZtHzBVAe)
10. [Continuous random variables](https://www.google.com/url?q=https://www.mathsisfun.com/data/random-variables-continuous.html&sa=D&source=editors&ust=1621930681954000&usg=AOvVaw17ambsxMgaZaRxhePs0GyW)
11. [Random vars mean, std, variance](https://www.google.com/url?q=https://www.mathsisfun.com/data/random-variables-mean-variance.html&sa=D&source=editors&ust=1621930681954000&usg=AOvVaw1Mq9C2GrLeDqK4SsZoUlLH)

More on Statistics
------------------

1.  [25 concepts](https://www.google.com/url?q=https://www.datasciencecentral.com/profiles/blogs/25-statistical-concepts-explained-in-simple-english-part-2&sa=D&source=editors&ust=1621930681955000&usg=AOvVaw11KZXGZWUCH9IkonbVB_dG)(part 2), [29 more concepts](https://www.google.com/url?q=https://www.datasciencecentral.com/profiles/blogs/29-statistical-concepts-explained-in-simple-english-part-1&sa=D&source=editors&ust=1621930681955000&usg=AOvVaw0DPvuFsYsPfB01qW9cuvXG)(part1) & [part 3](https://www.google.com/url?q=https://www.datasciencecentral.com/profiles/blogs/29-statistical-concepts-explained-in-simple-english-part-2?fbclid%3DIwAR0VQFeBaJsm3ouEf7sV5WAupE1cI3PXhzWe9-lUYkZ_XCCF72_3r8w5hrI&sa=D&source=editors&ust=1621930681956000&usg=AOvVaw1XToz57r69F7UunOz-ZxFB) in statistics.

Wiki
----

1.  [Marginal probability](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Marginal_distribution&sa=D&source=editors&ust=1621930681957000&usg=AOvVaw3pOR-0mWIN0H64foqfoeEP)
2.  [Joint probability](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Joint_probability_distribution&sa=D&source=editors&ust=1621930681958000&usg=AOvVaw026TqScpxowjLo8U7fONw9)
3.  [Conditional probability](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Probability&sa=D&source=editors&ust=1621930681958000&usg=AOvVaw0R7cwLHBZPU_PuFL-FX790)
4.  [Chain rule](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Chain_rule_(probability)&sa=D&source=editors&ust=1621930681959000&usg=AOvVaw2-HEPa8CahWxwypTdvZjfy)\- derivatives using the chain rule, on [khan](https://www.google.com/url?q=https://www.khanacademy.org/math/ap-calculus-ab/ab-differentiation-2-new/ab-3-1a/v/chain-rule-introduction&sa=D&source=editors&ust=1621930681959000&usg=AOvVaw1NAKjTLJA-jhM3e2TRN6y7)

Recommended Courses
-------------------

1.  [Another great course on probability](https://www.google.com/url?q=http://legacydirs.umiacs.umd.edu/~jbg/teaching/INST_414/&sa=D&source=editors&ust=1621930681960000&usg=AOvVaw24d9e5rbm7IkS5P0zgqwq3), distribution types, conditional, joint, chain, etc.
2.  [Kahn](https://www.google.com/url?q=https://www.khanacademy.org/math/precalculus/prob-comb&sa=D&source=editors&ust=1621930681961000&usg=AOvVaw2e6IuHqK1NOU9lsNnHaixw) academy
3.  [A really good intro](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D5NMxiOGL39M&sa=D&source=editors&ust=1621930681962000&usg=AOvVaw1IlvFa8vr0epDux9FaemSj) to probability, conditional, joint, etc.

* [What are confidence intervals?](https://www.google.com/url?q=https://towardsdatascience.com/a-very-friendly-introduction-to-confidence-intervals-9add126e714&sa=D&source=editors&ust=1621930681962000&usg=AOvVaw2lWx7ASrzanqRi9P20nY_z)

(another angle) [The main difference between probability and statistics has to do with knowledge](https://www.google.com/url?q=https://www.thoughtco.com/probability-vs-statistics-3126368&sa=D&source=editors&ust=1621930681963000&usg=AOvVaw2OrYtafz3apJiYn9wrBTrl)

* what are the known facts? Inherent in both probability and statistics is a [population](https://www.google.com/url?q=https://www.thoughtco.com/what-is-a-population-in-statistics-3126308&sa=D&source=editors&ust=1621930681964000&usg=AOvVaw2G-Ss-U6rJDsjUhChN8wS7),
* every individual we are interested in studying, and a sample, consisting of the individuals that are selected from the population.
* in probability: would start with us knowing everything about the composition of a population, and then would ask, “What is the likelihood that a selection, or sample, from the population, has certain characteristics?”
* In statistics: we have no knowledge about the types of socks in the drawer. we infer properties about the population on the basis of a random sample.

Some [calculations](https://www.google.com/url?q=https://www.mathsisfun.com/data/probability.html&sa=D&source=editors&ust=1621930681966000&usg=AOvVaw10xt81Ty_nXhtNVsfTQv3B) to get you into probability:

* Finding out the probability of an event
* Of two consecutive events (multiplication)
* Of several events (sum)
* Etc..

STATISTICAL SAMPLING AND RESAMPLING
-----------------------------------

1.  [What is? Method for sampling/resampling, and sampling errors explained.](https://www.google.com/url?q=https://machinelearningmastery.com/statistical-sampling-and-resampling/&sa=D&source=editors&ust=1621930681968000&usg=AOvVaw00hnC5OEpYigrjoFJZOF_V) (cross validation etc)

* * *

PROBABILITY
===========

![](images/image77.png)

![](images/image88.png)

![](images/image149.png)![](images/image177.png)

* * *

PDF (PROBABILITY DENSITY FUNCTION)
-------------------------------------------------------------------------------------------

1.  [Tutorial in scipy](https://www.google.com/url?q=https://oneau.wordpress.com/2011/02/28/simple-statistics-with-scipy/&sa=D&source=editors&ust=1621930681970000&usg=AOvVaw1Cr3JgBTKlf-0cLZsrVpQn)
2.  [Array-based tutorial in python with PDF and KDE](https://www.google.com/url?q=http://firsttimeprogrammer.blogspot.co.il/2015/01/how-to-estimate-probability-density.html&sa=D&source=editors&ust=1621930681971000&usg=AOvVaw0KW8hDMq6CKN7_CqHAWs6z)
3.  [Summary of univariate distribution including pdf methods](https://www.google.com/url?q=https://www.johndcook.com/blog/distributions_scipy/&sa=D&source=editors&ust=1621930681972000&usg=AOvVaw2_dJ8Z9iMlgJcaDJUDbQuD)

Kernel Density Estimation
-------------------------

This [tutorial](https://www.google.com/url?q=https://mglerner.github.io/posts/histograms-and-kernel-density-estimation-kde-2.html?p%3D28&sa=D&source=editors&ust=1621930681973000&usg=AOvVaw36EBEp7rkYSIc3DYriziWd) actually explains why we should use KDE over a Histogram, it explains the cons of histograms and how KDE helps solve some issue that we usually encounter in ‘Sparse’ histograms where the distribution is hard to figure out.

* Supposedly a better [implementation](https://www.google.com/url?q=https://github.com/Daniel-B-Smith/KDE-for-SciPy&sa=D&source=editors&ust=1621930681974000&usg=AOvVaw1dcaJqn_HG91o1Kp9DEoGO) of KDE than SCIPY

How to use KDE? A [tutorial](https://www.google.com/url?q=http://pythonhosted.org/PyQt-Fit/KDE_tut.html&sa=D&source=editors&ust=1621930681974000&usg=AOvVaw104Euf6svbGItpmuwpCQ3x) about kernel density and how to use it in python. Has several good graphs and shows use cases.

Video tutorials about Kernel Density:

1.  [KDE](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DgPWsDh59zdo&sa=D&source=editors&ust=1621930681975000&usg=AOvVaw2gN43FL3uPYcNTbgpxEKCi)
2.  Non parametric [Kernel Regression Estimation](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DncF7ArjJFqM&sa=D&source=editors&ust=1621930681975000&usg=AOvVaw3IFnpuFhoq70PPKYGGrY-X)
3.  Non parametric [Sieve Estimation](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Dcqecz-DL-jI&sa=D&source=editors&ust=1621930681976000&usg=AOvVaw1vsV-lIXV-Nhz5lPhrmOA8)
4.  [Semi- nonparametric estimation](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DG1N53K530To&sa=D&source=editors&ust=1621930681976000&usg=AOvVaw3hNKJKgItcxoYcD0iToX3a)

[Udacity Video Tutorial](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DMEP35FcrQGs%26list%3DPLAwxTw4SYaPn-ttWkPiUL7NP3lLRdUniJ%26index%3D80&sa=D&source=editors&ust=1621930681977000&usg=AOvVaw1sk5xaagJIB6fXpjw3Qe2Q) \- pretty good

1.  IMPORTANT: [Comparison and benchmarks of various KDE algo’s](https://www.google.com/url?q=https://jakevdp.github.io/blog/2013/12/01/kernel-density-estimation/&sa=D&source=editors&ust=1621930681977000&usg=AOvVaw37eTCiyYiB2WH1OQnAuk05)
2.  [Histograms and density plots](https://www.google.com/url?q=https://towardsdatascience.com/histograms-and-density-plots-in-python-f6bda88f5ac0&sa=D&source=editors&ust=1621930681978000&usg=AOvVaw3jRBbxZvnyvDseAI2cuseW)
3.  [SK LEARN](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/density.html%23kernel-density-estimation&sa=D&source=editors&ust=1621930681978000&usg=AOvVaw0fVH8qEiSB2JsxmKKpRMI3)
4.  [Gaussian KDE in scipy, version 2](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DMEP35FcrQGs%26list%3DPLAwxTw4SYaPn-ttWkPiUL7NP3lLRdUniJ%26index%3D80&sa=D&source=editors&ust=1621930681978000&usg=AOvVaw3SZrg0nNidJ-JGbjqL20NX)

* * *

[FEATURE](https://www.google.com/url?q=http://www.biostat.umn.edu/~will/6470stuff/Class09-12/Handout09.pdf&sa=D&source=editors&ust=1621930681979000&usg=AOvVaw25p71CbS8SIVVbE-XPyy17) TYPES
===========================================================================================================================================================================================

Discrete

* Numbers
* Categorical
* Categorical data are variables that contain label values rather than numeric values.

The number of possible values is often limited to a fixed set.

* Categorical variables are often called [nominal](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Nominal_category&sa=D&source=editors&ust=1621930681980000&usg=AOvVaw3DopcqwGkyM1apL3NERwik).
* labels, usually discrete values such as gender, country of origin, marital status, high-school graduate

Continuous (the opposite of discrete): real-number values, measured on a continuous scale: height, weight.

In order to compute a regression, categorical predictors must be re-expressed as numeric: some form of indicator variables (0/1) with a separate indicator for each level of the factor.

Discrete with many values are often treated as continuous, i.e. zone numbers - > binary

[Variable types:](https://www.google.com/url?q=http://www.socialresearchmethods.net/kb/measlevl.php&sa=D&source=editors&ust=1621930681981000&usg=AOvVaw3qI1cGK9XuPU1QagK42kGA) Nominal(weather), ordinal(order var 1,2,3), interval(range),

* * *

FEATURES
========

CORRELATION
-----------

1.  [Pearson](https://www.google.com/url?q=https://machinelearningmastery.com/how-to-use-correlation-to-understand-the-relationship-between-variables/&sa=D&source=editors&ust=1621930681982000&usg=AOvVaw20OVhVB9NxzHhc-suReuUQ)

### CORRELATION VS COVARIANCE

1.  [Correlation is between -1 to 1, covariance is -inf to inf, units in covariance affect the scale, so correlation is preferred, it is normalized.](https://www.google.com/url?q=https://towardsdatascience.com/correlation-coefficient-clearly-explained-f034d00b66ac&sa=D&source=editors&ust=1621930681983000&usg=AOvVaw30oouoU8ktdMVCFHPkGOf9)  
    Correlation is a measure of association. Correlation is used for bivariate analysis. It is a measure of how well the two variables are related.  
    Covariance is also a measure of association. Covariance is a measure of the relationship between two random variables.

### CORRELATION BETWEEN FEATURE TYPES

1.  Association vs correlation - correlation is a measure of association and a yes no question without assuming linearity
2.  [A great article in medium](https://www.google.com/url?q=https://medium.com/@outside2SDs/an-overview-of-correlation-measures-between-categorical-and-continuous-variables-4c7f85610365&sa=D&source=editors&ust=1621930681983000&usg=AOvVaw1jZ-rhL8DGHlmymYeRJlBC), covering just about everything with great detail and explaining all the methods plus references.
3.  Heat maps for categorical vs target - groupby count per class, normalize by total count to see if you get more grouping in a certain combination of cat/target than others.
4.  [Anova](https://www.google.com/url?q=https://www.researchgate.net/post/Which_test_do_I_use_to_estimate_the_correlation_between_an_independent_categorical_variable_and_a_dependent_continuous_variable&sa=D&source=editors&ust=1621930681984000&usg=AOvVaw0vAsoUZCGw8lG4BGFQsVw4)/[log regression](https://www.google.com/url?q=https://www.statalist.org/forums/forum/general-stata-discussion/general/1470627-correlation-between-continous-and-categorical-variable&sa=D&source=editors&ust=1621930681985000&usg=AOvVaw3Jo3DgUzHppGhO30LgPK0p)[2*,](https://www.google.com/url?q=https://dzone.com/articles/correlation-between-categorical-and-continuous-var-1&sa=D&source=editors&ust=1621930681985000&usg=AOvVaw0hL8hF4YArX7Aw_kxx7y2x)[git](https://www.google.com/url?q=https://github.com/ShitalKat/Correlation/blob/master/Correlation%2520between%2520categorical%2520and%2520continuous%2520variables.ipynb&sa=D&source=editors&ust=1621930681985000&usg=AOvVaw1etIREpfpIAelmlHiK3scq), [3](https://www.google.com/url?q=https://www.edvancer.in/DESCRIPTIVE%2BSTATISTICS%2BFOR%2BDATA%2BSCIENCE-2&sa=D&source=editors&ust=1621930681985000&usg=AOvVaw2pZ9emUkM0yfQAAclE_tfz), for numeric/[cont vs categorical](https://www.google.com/url?q=https://www.quora.com/How-can-I-measure-the-correlation-between-continuous-and-categorical-variables&sa=D&source=editors&ust=1621930681986000&usg=AOvVaw0yA0aJW31U9VTEpZUPSD0r) \- high F score from anova hints about association between a feature and a target, i.e.,  the importance of the feature to separating the target.
5.  Anova youtube [1](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DITf4vHhyGpc&sa=D&source=editors&ust=1621930681986000&usg=AOvVaw2DRQUvRm2Oof1Bhp8S0O2X), [2](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D-yQb_ZJnFXw&sa=D&source=editors&ust=1621930681987000&usg=AOvVaw0-wO5A_bUW2mxQGArGJKhh)![](images/image87.png)
6.  [Cat vs cat](https://www.google.com/url?q=https://towardsdatascience.com/the-search-for-categorical-correlation-a1cf7f1888c9&sa=D&source=editors&ust=1621930681987000&usg=AOvVaw3j1B09j8zzwAvEZCyFRYwh), many metrics - on medium
    
    * * *
    

### CORRELATION VISUALIZATION

[Feature space](https://www.google.com/url?q=https://towardsdatascience.com/escape-the-correlation-matrix-into-feature-space-4d71c51f25e5&sa=D&source=editors&ust=1621930681988000&usg=AOvVaw0lMFANC_PHMLgJdGyTdJa7)

![](images/image132.png)![](images/image160.png)

PREDICTIVE POWER SCORE (PPS)
----------------------------

[Is  an asymmetric, data-type-agnostic score for predictive relationships between two columns that ranges from 0 to 1.](https://www.google.com/url?q=https://towardsdatascience.com/rip-correlation-introducing-the-predictive-power-score-3d90808b9598&sa=D&source=editors&ust=1621930681989000&usg=AOvVaw3kOXwzlA_hzJnnkfig3hdl)[github](https://www.google.com/url?q=https://github.com/8080labs/ppscore&sa=D&source=editors&ust=1621930681989000&usg=AOvVaw13TrKAGbPfLezkGl9pB0KX)

![](images/image172.png)

Too many scenarios where the correlation is 0. This makes me wonder if I missed something… (Excerpt from the [image by Denis Boigelot](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Correlation_and_dependence&sa=D&source=editors&ust=1621930681989000&usg=AOvVaw0N6qrVwlLMvyGWewj_ln5j))

Regression

In case of an regression, the ppscore uses the mean absolute error (MAE) as the underlying evaluation metric (MAE\_model). The best possible score of the MAE is 0 and higher is worse. As a baseline score, we calculate the MAE of a naive model (MAE\_naive) that always predicts the median of the target column. The PPS is the result of the following normalization (and never smaller than 0):

PPS = 1 - (MAE\_model / MAE\_naive)

Classification

If the task is a classification, we compute the weighted F1 score (wF1) as the underlying evaluation metric (F1_model). The F1 score can be interpreted as a weighted average of the precision and recall, where an F1 score reaches its best value at 1 and worst score at 0. The relative contribution of precision and recall to the F1 score are equal. The weighted F1 takes into account the precision and recall of all classes weighted by their support as described [here](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html&sa=D&source=editors&ust=1621930681991000&usg=AOvVaw1dV0kj_VG3cBNrjabK7Lo3). As a baseline score (F1\_naive), we calculate the weighted F1 score for a model that always predicts the most common class of the target column (F1\_most\_common) and a model that predicts random values (F1\_random). F1\_naive is set to the maximum of F1\_most\_common and F1\_random. The PPS is the result of the following normalization (and never smaller than 0):

PPS = (F1\_model - F1\_naive) / (1 - F1_naive)

MUTUAL INFORMATION COEFFICIENT
------------------------------

[Paper](https://www.google.com/url?q=https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3325791/&sa=D&source=editors&ust=1621930681992000&usg=AOvVaw2GNdJ5WHreZ--8aKFsUtiS) \- we present a measure of dependence for two-variable relationships: the maximal information coefficient (MIC). MIC captures a wide range of associations both functional and not, and for functional relationships provides a score that roughly equals the coefficient of determination (R2) of the data relative to the regression function.

ComputingMIC

![](images/image11.png)

(A) For each pair (x,y), the MIC algorithm finds the x-by-y grid with the highest induced mutual information. (B) The algorithm normalizes the mutual information scores and compiles a matrix that stores, for each resolution, the best grid at that resolution and its normalized score. (C) The normalized scores form the characteristic matrix, which can be visualized as a surface; MIC corresponds to the highest point on this surface.

In this example, there are many grids that achieve the highest score. The star in (B) marks a sample grid achieving this score, and the star in (C) marks that grid's corresponding location on the surface.

* * *

[Mutual information classifier](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.mutual_info_classif.html&sa=D&source=editors&ust=1621930681994000&usg=AOvVaw0iWT5BZuGEh-aGiTyydYa3) \- Estimate mutual information for a discrete target variable.

Mutual information (MI) [\[1\]](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.mutual_info_classif.html%23r50b872b699c4-1&sa=D&source=editors&ust=1621930681995000&usg=AOvVaw22pAy5AnWUXVqNeIkFE1Gw) between two random variables is a non-negative value, which measures the dependency between the variables. It is equal to zero if and only if two random variables are independent, and higher values mean higher dependency.

The function relies on nonparametric methods based on entropy estimation from k-nearest neighbors distances as described in [\[2\]](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.mutual_info_classif.html%23r50b872b699c4-2&sa=D&source=editors&ust=1621930681996000&usg=AOvVaw3P6JUXFIGfAJxR1zNLeGga)and [\[3\]](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.mutual_info_classif.html%23r50b872b699c4-3&sa=D&source=editors&ust=1621930681996000&usg=AOvVaw1K3WCnsgfirug4GBU3x0e6). Both methods are based on the idea originally proposed in [\[4\]](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.mutual_info_classif.html%23r50b872b699c4-4&sa=D&source=editors&ust=1621930681997000&usg=AOvVaw27KKg0orC0gacJM_Vxdsu3).

[MI score](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mutual_info_score.html&sa=D&source=editors&ust=1621930681997000&usg=AOvVaw1KX4sNUbP16Jj62HuCamGb) \- Mutual Information between two clusterings.

The Mutual Information is a measure of the similarity between two labels of the same data.

[Adjusted MI score](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.metrics.adjusted_mutual_info_score.html%23sklearn.metrics.adjusted_mutual_info_score&sa=D&source=editors&ust=1621930681998000&usg=AOvVaw3dIDa1MsSKJhqmhjuwF4u_) \- Adjusted Mutual Information between two clusterings.

Adjusted Mutual Information (AMI) is an adjustment of the Mutual Information (MI) score to account for chance. It accounts for the fact that the MI is generally higher for two clusterings with a larger number of clusters, regardless of whether there is actually more information shared.

This metric is furthermore symmetric: switching label\_true with label\_pred will return the same score value. This can be useful to measure the agreement of two independent label assignments strategies on the same dataset when the real ground truth is not known

[Normalized MI score](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.metrics.normalized_mutual_info_score.html%23sklearn.metrics.normalized_mutual_info_score&sa=D&source=editors&ust=1621930681999000&usg=AOvVaw3xrSIfdIjFuuQrgsPKvvDY) \- Normalized Mutual Information (NMI) is a normalization of the Mutual Information (MI) score to scale the results between 0 (no mutual information) and 1 (perfect correlation). In this function, mutual information is normalized by some generalized mean of H(labels\_true) and H(labels\_pred)), defined by the average_method.

CRAMER’S COEFFICIENT
--------------------

[Calculating](https://www.google.com/url?q=https://stackoverflow.com/questions/20892799/using-pandas-calculate-cram%25C3%25A9rs-coefficient-matrix&sa=D&source=editors&ust=1621930682000000&usg=AOvVaw0unKDncfoNJ4dsGGDiHGfc)

* * *

FEATURE SELECTION
-----------------

A series of good articles that explain about several techniques for feature selection

1.  [How to parallelize feature selection on several CPUs,](https://www.google.com/url?q=https://stackoverflow.com/questions/37037450/multi-label-feature-selection-using-sklearn&sa=D&source=editors&ust=1621930682002000&usg=AOvVaw1b57EFThQKpxLQMDvv1qIJ) do it per label on each cpu and average the results.
2.  [A great notebook about feature correlation and manytypes of visualization, what to drop what to keep, using many feature reduction and selection methods (quite a lot actually). Its a really good intro](https://www.google.com/url?q=https://www.kaggle.com/kanncaa1/feature-selection-and-data-visualization&sa=D&source=editors&ust=1621930682003000&usg=AOvVaw0WziY0Jyf0nIQb0AXLL1xH)
3.  [Multi class classification, feature selection, model selection, co-feature analysis](https://www.google.com/url?q=https://towardsdatascience.com/multi-class-text-classification-with-scikit-learn-12f1e60e0a9f&sa=D&source=editors&ust=1621930682003000&usg=AOvVaw2hYfDGLAo15gj91nyYDBZO)
4.  [Text analysis for sentiment, doing feature selection](https://www.google.com/url?q=https://streamhacker.com/tag/chi-square/&sa=D&source=editors&ust=1621930682004000&usg=AOvVaw25WL5s3Ad7IorHDWzxkv0E) a tutorial with chi2(IG?),[part 2 with bi-gram collocation in ntlk](https://www.google.com/url?q=https://streamhacker.com/2010/05/24/text-classification-sentiment-analysis-stopwords-collocations/&sa=D&source=editors&ust=1621930682004000&usg=AOvVaw1Wr9OclLVMeO_MbrviVddg)
5.  What is collocation? - “the habitual juxtaposition of a particular word with another word or words with a frequency greater than chance.”
6.  [Sklearn feature selection methods (4) - youtube](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DwjKvyk8xStg&sa=D&source=editors&ust=1621930682005000&usg=AOvVaw17gSOKC3U6v9b5BWpW6YXx)
7.  [Univariate](https://www.google.com/url?q=http://blog.datadive.net/selecting-good-features-part-i-univariate-selection/&sa=D&source=editors&ust=1621930682005000&usg=AOvVaw2uSNUAhHOY6aiJlpMm-DH8) and independent features
8.  [Linear models and regularization,](https://www.google.com/url?q=http://blog.datadive.net/selecting-good-features-part-ii-linear-models-and-regularization/&sa=D&source=editors&ust=1621930682006000&usg=AOvVaw36EMMyzmEzHzhcIaAzBNfI) doing feature ranking
9.  [Random forests and feature ranking](https://www.google.com/url?q=http://blog.datadive.net/selecting-good-features-part-iii-random-forests/&sa=D&source=editors&ust=1621930682006000&usg=AOvVaw3EvTW3v_BhVyU81p0CY3B-)
10. [Random Search for focus and only then grid search for Random Forest](https://www.google.com/url?q=https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74&sa=D&source=editors&ust=1621930682007000&usg=AOvVaw1gluTiDNf9Mf1dTbS5gHbw), [code](https://www.google.com/url?q=https://github.com/WillKoehrsen/Machine-Learning-Projects/blob/master/random_forest_explained/Improving%2520Random%2520Forest%2520Part%25202.ipynb&sa=D&source=editors&ust=1621930682007000&usg=AOvVaw3TgE3sFdOGvlj3Uy1EwZ-c)
11. [Stability selection and recursive feature elimination (RFE).](https://www.google.com/url?q=http://blog.datadive.net/selecting-good-features-part-iv-stability-selection-rfe-and-everything-side-by-side/&sa=D&source=editors&ust=1621930682008000&usg=AOvVaw300wi1geecje9g0rqAPjHk)are wrapper methods in sklearn for the purpose of feature selection. [RFE in sklearn](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFE.html&sa=D&source=editors&ust=1621930682008000&usg=AOvVaw1TzxCMGBMCEkAooDJcHySf)
12. [Kernel feature selection via conditional covariance minimization](https://www.google.com/url?q=http://bair.berkeley.edu/blog/2018/01/23/kernels/&sa=D&source=editors&ust=1621930682008000&usg=AOvVaw135nGI1ahsBLVgoBJJUKwV) (netanel d.)
13. [Github class that does the following](https://www.google.com/url?q=https://towardsdatascience.com/a-feature-selection-tool-for-machine-learning-in-python-b64dd23710f0&sa=D&source=editors&ust=1621930682009000&usg=AOvVaw1RKrPp2wuNe9plZem6yldf):

1.  Features with a high percentage of missing values
2.  Collinear (highly correlated) features
3.  Features with zero importance in a tree-based model
4.  Features with low importance
5.  Features with a single unique value

14. [Machinelearning mastery on FS](https://www.google.com/url?q=https://machinelearningmastery.com/feature-selection-machine-learning-python/&sa=D&source=editors&ust=1621930682010000&usg=AOvVaw2IEgcMmgiLZPbASnxb_yAv):

1.  Univariate Selection.
2.  Recursive Feature Elimination.
3.  Principle Component Analysis.
4.  Feature Importance.

15. [Sklearn tutorial on FS:](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/feature_selection.html&sa=D&source=editors&ust=1621930682011000&usg=AOvVaw2ELKR25acoRPNAsD3KsDBw)

1.  Low variance
2.  Univariate kbest
3.  RFE
4.  selectFromModel using \_coef \_important_features
5.  Linear models with L1 (svm recommended L2)
6.  Tree based importance

16. [A complete overview of many methods](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2016/12/introduction-to-feature-selection-methods-with-an-example-or-how-to-select-the-right-variables/&sa=D&source=editors&ust=1621930682012000&usg=AOvVaw1W86k3lDp9Cikqn7_HPWk0)

1.  (reduction) LDA: Linear discriminant analysis is used to find a linear combination of features that characterizes or separates two or more classes (or levels) of a categorical variable.
2.  (selection) ANOVA: ANOVA stands for Analysis of variance. It is similar to LDA except for the fact that it is operated using one or more categorical independent features and one continuous dependent feature. It provides a statistical test of whether the means of several groups are equal or not.
3.  (Selection) Chi-Square: It is a is a statistical test applied to the groups of categorical features to evaluate the likelihood of correlation or association between them using their frequency distribution.
4.  Wrapper methods:

1.  Forward Selection: Forward selection is an iterative method in which we start with having no feature in the model. In each iteration, we keep adding the feature which best improves our model till an addition of a new variable does not improve the performance of the model.
2.  Backward Elimination: In backward elimination, we start with all the features and removes the least significant feature at each iteration which improves the performance of the model. We repeat this until no improvement is observed on removal of features.
3.  Recursive Feature elimination: It is a greedy optimization algorithm which aims to find the best performing feature subset. It repeatedly creates models and keeps aside the best or the worst performing feature at each iteration. It constructs the next model with the left features until all the features are exhausted. It then ranks the features based on the order of their elimination.

17. [Relief](https://www.google.com/url?q=https://medium.com/@yashdagli98/feature-selection-using-relief-algorithms-with-python-example-3c2006e18f83&sa=D&source=editors&ust=1621930682015000&usg=AOvVaw32ctbcTXe3x32Y8pKSLBpl)\- [GIT](https://www.google.com/url?q=https://github.com/GrantRVD/ReliefF&sa=D&source=editors&ust=1621930682016000&usg=AOvVaw32rVsvOmbQEyWBcLE9oHby)[git2](https://www.google.com/url?q=https://pypi.org/project/ReliefF/%23description&sa=D&source=editors&ust=1621930682016000&usg=AOvVaw3f0jw6zP2ej_sEazJ0ljUM) a new family of feature selection trying to optimize the distance of two samples from the selected one, one which should be closer the other farther.

“The weight updation of attributes works on a simple idea (line 6). That if instance Rᵢ and H have different value (i.e the diff value is large), that means that attribute separates two instance with the same class which is not desirable, thus we reduce the attributes weight. On the other hand, if the instance Rᵢ and M have different value, that means the attribute separates the two instance with different class, which is desirable.”

18. [Scikit-feature (includes relief)](https://www.google.com/url?q=https://github.com/chappers/scikit-feature&sa=D&source=editors&ust=1621930682017000&usg=AOvVaw3l-bKIL6F9xJqYbyWhDdeG)forked from [this](https://www.google.com/url?q=https://github.com/jundongl/scikit-feature/tree/master/skfeature&sa=D&source=editors&ust=1621930682017000&usg=AOvVaw1SpK9Y10g6qap5UdKvo10I)[(docs)](https://www.google.com/url?q=http://featureselection.asu.edu/algorithms.php&sa=D&source=editors&ust=1621930682018000&usg=AOvVaw0VhWOJfWOeUELDVoTivqFy)
19. [Scikit-rebate (based on relief)](https://www.google.com/url?q=https://github.com/EpistasisLab/scikit-rebate&sa=D&source=editors&ust=1621930682018000&usg=AOvVaw1wRLNfQVd7ajrx9N_84CZo)

[Feature selection using entropy, information gain, mutual information and … in sklearn.](https://www.google.com/url?q=https://gist.github.com/GaelVaroquaux/ead9898bd3c973c40429&sa=D&source=editors&ust=1621930682019000&usg=AOvVaw0ho7hgzwW_ju6TJ6coXhNL)

[Entropy, mutual information and KL Divergence by AurelienGeron](https://www.google.com/url?q=https://www.techleer.com/articles/496-a-short-introduction-to-entropy-cross-entropy-and-kl-divergence-aurelien-geron/&sa=D&source=editors&ust=1621930682019000&usg=AOvVaw1DwITejZ8rlQ7DOMNDlkr5)

* * *

FEATURE ENGINEERING
-------------------

1.  [Vidhya on FE, anomalies, engineering, imputing](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2016/01/guide-data-exploration/?utm_source%3Doutlierdetectionpyod%26utm_medium%3Dblog&sa=D&source=editors&ust=1621930682021000&usg=AOvVaw0VhSCaCdgXT9ywBJC9EnTw)
2.  [Many types of FE](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-1-continuous-numeric-data-da4e47099a7b&sa=D&source=editors&ust=1621930682021000&usg=AOvVaw1VF-VR2DLOm1SKlwi7mIdv), including log and box cox transform - a very useful explanation.
3.  [Categorical Data](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-2-categorical-data-f54324193e63&sa=D&source=editors&ust=1621930682022000&usg=AOvVaw1ndCdPOsNUoqtFBh9lf9EJ)
4.  [Dummy variables and feature hashing](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-2-categorical-data-f54324193e63&sa=D&source=editors&ust=1621930682022000&usg=AOvVaw1ndCdPOsNUoqtFBh9lf9EJ) \- hashing is really cool.
5.  [Text data](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-3-traditional-methods-for-text-data-f6f7d70acd41&sa=D&source=editors&ust=1621930682023000&usg=AOvVaw2XnDcecYCToc0Kisium4Sz)\- unigrams, bag of words, N-grams (2,3,..), tfidf matrix, cosine_similarity(tfidf) ontop of a tfidf matrix, unsupervised hierarchical clustering with similarity measures on top of (cosine_similarity), LDA for topic modelling in sklearn - pretty awesome, Kmeans(lda),.
6.  [Deep learning data for FE](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-4-deep-learning-methods-for-text-data-96c44370bbfa&sa=D&source=editors&ust=1621930682024000&usg=AOvVaw2YTzFg9CkU4CNYi2cRnVTg)\- [Word embedding using keras, continuous BOW - CBOW, SKIPGRAM, word2vec - really good.](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-4-deep-learning-methods-for-text-data-96c44370bbfa&sa=D&source=editors&ust=1621930682024000&usg=AOvVaw2YTzFg9CkU4CNYi2cRnVTg)
7.  [Topic Modelling](https://www.google.com/url?q=http://chdoig.github.io/pygotham-topic-modeling/%23/&sa=D&source=editors&ust=1621930682025000&usg=AOvVaw1CrFXgZrjW3ZcbkovfFcnP) \- a fantastic slide show about topic modelling using LDA etc.
8.  Dipanjan on feature engineering [1](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-1-continuous-numeric-data-da4e47099a7b&sa=D&source=editors&ust=1621930682025000&usg=AOvVaw0k_F02ceBTzdkXrsRfjFyA)\- cont numeric [2 -](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-2-categorical-data-f54324193e63&sa=D&source=editors&ust=1621930682026000&usg=AOvVaw3OE6_f9iB2QZ4sCu0qQ6-s) categorical [3](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-3-traditional-methods-for-text-data-f6f7d70acd41&sa=D&source=editors&ust=1621930682026000&usg=AOvVaw1Pl3bTycHcVMEIS-ZbO69N) \- traditional methods
9.  [Target encoding git](https://www.google.com/url?q=https://pypi.org/project/target_encoding/&sa=D&source=editors&ust=1621930682027000&usg=AOvVaw3lq0W4tONuus8C2U1GMnBo)
10. [Category encoding git](https://www.google.com/url?q=https://pypi.org/project/category-encoders/&sa=D&source=editors&ust=1621930682027000&usg=AOvVaw31m7ggXOycS1rRlfcEiJCK)

REPRESENTATION LEARNING
-----------------------

1.  [paper](https://www.google.com/url?q=https://arxiv.org/abs/1807.03748?utm_campaign%3DThe%2520Batch%26utm_source%3Dhs_email%26utm_medium%3Demail%26utm_content%3D83602348%26_hsenc%3Dp2ANqtz-8DcgUdDF--k3tWOmhM51lm28wHerZxlXKoGNU6hIu2P4Fj-RuEuciKtbWZZdWmvBg7KGeI44FWUrmpHdZIbAM-pUicgg%26_hsmi%3D83602348&sa=D&source=editors&ust=1621930682028000&usg=AOvVaw0H-fopBkrABB8rflVyB4vQ)

TFIDF
-----

1.  [Max_features in tf idf](https://www.google.com/url?q=https://stackoverflow.com/questions/46118910/scikit-learn-vectorizer-max-features&sa=D&source=editors&ust=1621930682029000&usg=AOvVaw3umuJlJWb0uISzMfSgh5EL) -Sometimes it is not effective to transform the whole vocabulary, as the data may have some exceptionally rare words, which, if passed to TfidfVectorizer().fit(), will add unwanted dimensions to inputs in the future. One of the appropriate techniques in this case, for instance, would be to print out word frequences accross documents and then set a certain threshold for them. Imagine you have set a threshold of 50, and your data corpus consists of 100 words. After looking at the word frequences 20 words occur less than 50 times. Thus, you set max\_features=80 and you are good to go. If max\_features is set to None, then the whole corpus is considered during the TF-IDFtransformation. Otherwise, if you pass, say, 5 to max_features, that would mean creating a feature matrix out of the most 5 frequent words accross text documents.

SIMILARITY
----------

1.  [Cosine similarity tutorial](https://www.google.com/url?q=http://blog.christianperone.com/2013/09/machine-learning-cosine-similarity-for-vector-space-models-part-iii/&sa=D&source=editors&ust=1621930682030000&usg=AOvVaw1pDko2G8GYhonBwIUU8peM)

1.  [Cosine vs dot product](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/744/cosine-similarity-versus-dot-product-as-distance-metrics&sa=D&source=editors&ust=1621930682030000&usg=AOvVaw3OwIWpMo5bbvsxEuKezAbi)
2.  [Cosine vs dot product 2](https://www.google.com/url?q=https://blog.christianperone.com/2013/09/machine-learning-cosine-similarity-for-vector-space-models-part-iii/&sa=D&source=editors&ust=1621930682030000&usg=AOvVaw0cPReiqBZaxeaAQqEQu4GT)
3.  [Fast cosine similarity](https://www.google.com/url?q=https://stackoverflow.com/questions/51425300/python-fast-cosine-distance-with-cython&sa=D&source=editors&ust=1621930682031000&usg=AOvVaw3JaLIHEf0doT7xc6joaOnX) implementation

2.  Edit distance similarity
3.  [Diff lib similarity and soundex](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/12575/similarity-between-two-words&sa=D&source=editors&ust=1621930682031000&usg=AOvVaw1PUddwLTDVY6o_Zwc3m-jZ)
4.  [Soft cosine and cosine](https://www.google.com/url?q=https://www.machinelearningplus.com/nlp/gensim-tutorial/&sa=D&source=editors&ust=1621930682032000&usg=AOvVaw3cilGdcmNq-lTqqLzaRHqP)
5.  [Pearson also used to detect similar vectors](https://www.google.com/url?q=https://machinelearningmastery.com/how-to-use-correlation-to-understand-the-relationship-between-variables/&sa=D&source=editors&ust=1621930682032000&usg=AOvVaw0Pm4AqcfylsEPwPkQeqQ1q)

FEATURE IMPORTANCE
------------------

Note: point 2, about lime is used for explainability, please also check that topic, down below.

1.  [Using RF and other methods, really good](https://www.google.com/url?q=https://towardsdatascience.com/explaining-feature-importance-by-example-of-a-random-forest-d9166011959e&sa=D&source=editors&ust=1621930682033000&usg=AOvVaw0kDzbEV2HGJJ1WTPhT903J)
2.  [Non parametric feature impact and importance](https://www.google.com/url?q=https://arxiv.org/abs/2006.04750&sa=D&source=editors&ust=1621930682033000&usg=AOvVaw11NI3sY58yr1U6-T7L1IRw) \- while there are nonparametric feature selection algorithms, they typically provide feature rankings, rather than measures of impact or importance.In this paper, we give mathematical definitions of feature impact and importance, derived from partial dependence curves, that operate directly on the data.
3.  [Paper](https://www.google.com/url?q=https://arxiv.org/abs/1602.04938&sa=D&source=editors&ust=1621930682034000&usg=AOvVaw0M4p-OJMSS0CHVVkBHSBcq) ([pdf](https://www.google.com/url?q=https://arxiv.org/pdf/1602.04938.pdf&sa=D&source=editors&ust=1621930682035000&usg=AOvVaw2oLCo3OqPe49fJ_H5Xlf7Y), [blog post](https://www.google.com/url?q=https://www.oreilly.com/learning/introduction-to-local-interpretable-model-agnostic-explanations-lime&sa=D&source=editors&ust=1621930682035000&usg=AOvVaw0_p0haIsRZJpxxHMurTM30)): ([GITHUB](https://www.google.com/url?q=https://github.com/marcotcr/lime/blob/master/README.md&sa=D&source=editors&ust=1621930682035000&usg=AOvVaw1zlp0gTP7kmA6wE1fwmhB9)) how to "explain the predictions of any classifier in an interpretable and faithful manner, by learning an interpretable model locally around the prediction."  
      
    they want to understand the reasons behind the predictions, it’s a new field that says that many 'feature importance' measures shouldn’t be used. i.e., in a linear regression model, a feature can have an importance rank of 50 (for example), in a comparative model where you duplicate that feature 50 times, each one will have 1/50 importance and won’t be selected for the top K, but it will still be one of the most important features. so new methods needs to be developed to understand feature importance. this one has git code as well.

Several github notebook examples: [binary case](https://www.google.com/url?q=https://marcotcr.github.io/lime/tutorials/Lime%2520-%2520basic%2520usage%252C%2520two%2520class%2520case.html&sa=D&source=editors&ust=1621930682036000&usg=AOvVaw1kQvRji8h8JQJoWsoC5aVJ), [multi class](https://www.google.com/url?q=https://marcotcr.github.io/lime/tutorials/Lime%2520-%2520multiclass.html&sa=D&source=editors&ust=1621930682036000&usg=AOvVaw1zBBIY2NuFU4Zv_keDNP8Q), [cont and cat features](https://www.google.com/url?q=https://marcotcr.github.io/lime/tutorials/Tutorial%2520-%2520continuous%2520and%2520categorical%2520features.html&sa=D&source=editors&ust=1621930682037000&usg=AOvVaw2IBrNf2zpbu0wVK4Cn0XWx), there are many more for images in the github link.

“Intuitively, an explanation is a local linear approximation of the model's behaviour. While the model may be very complex globally, it is easier to approximate it around the vicinity of a particular instance. While treating the model as a black box, we perturb the instance we want to explain and learn a sparse linear model around it, as an explanation. The figure below illustrates the intuition for this procedure. The model's decision function is represented by the blue/pink background, and is clearly nonlinear. The bright red cross is the instance being explained (let's call it X). We sample instances around X, and weight them according to their proximity to X (weight here is indicated by size). We then learn a linear model (dashed line) that approximates the model well in the vicinity of X, but not necessarily globally. For more information, read our paper, or take a look at this blog post.”  
  
![](images/image86.png)

FEATURE IMPUTING
----------------

1.  [Vidhya on FE, anomalies, engineering, imputing](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2016/01/guide-data-exploration/?utm_source%3Doutlierdetectionpyod%26utm_medium%3Dblog&sa=D&source=editors&ust=1621930682038000&usg=AOvVaw28GpUy7qouq1pBQZsbM87J)
2.  [Fancy impute](https://www.google.com/url?q=https://pypi.org/project/fancyimpute/&sa=D&source=editors&ust=1621930682039000&usg=AOvVaw1-TqKnFLJoAdjJsI-SnppO)

FEATURE STORE
-------------

1.  The importance of having one - [medium](https://www.google.com/url?q=https://towardsdatascience.com/the-importance-of-having-a-feature-store-e2a9cfa5619f&sa=D&source=editors&ust=1621930682040000&usg=AOvVaw2lwXOhzawcSm2JjvQMpegI)
2.  [Feast](https://www.google.com/url?q=https://docs.feast.dev/&sa=D&source=editors&ust=1621930682040000&usg=AOvVaw1F-46J4yWWM8NQDeLxLsKE)![](images/image272.png)
3.  [Tecton.ai](https://www.google.com/url?q=https://www.tecton.ai/&sa=D&source=editors&ust=1621930682041000&usg=AOvVaw0A0iy2M6E94DlvtU01pavI)  
    ![](images/image65.png)
4.  [Iguazio feature store](https://www.google.com/url?q=https://www.iguazio.com/feature-store/&sa=D&source=editors&ust=1621930682041000&usg=AOvVaw00WFaBGyTbJKcW9yJj8YdM)   
      
    ![](images/image63.png)

* * *

CALIBRATION
===========

[Why do we need to calibrate models, or in other words, dont trust predict_proba to give you probabilities](https://www.google.com/url?q=https://towardsdatascience.com/pythons-predict-proba-doesn-t-actually-predict-probabilities-and-how-to-fix-it-f582c21d63fc&sa=D&source=editors&ust=1621930682042000&usg=AOvVaw2TIwaHzyhDRCczDJ7mb8Vv)

Classic Model Calibration
-------------------------

1.  How do we do isotonic and sigmoid calibration - read [this](https://www.google.com/url?q=http://tullo.ch/articles/speeding-up-isotonic-regression/&sa=D&source=editors&ust=1621930682043000&usg=AOvVaw0Kx2hxnnynHJh945pHROUg), then [this](https://www.google.com/url?q=http://fastml.com/classifier-calibration-with-platts-scaling-and-isotonic-regression/&sa=D&source=editors&ust=1621930682044000&usg=AOvVaw1Grd4n6uZvxeoSE-T91i-u), [how to use in sklearn](https://www.google.com/url?q=https://stats.stackexchange.com/questions/263393/scikit-correct-way-to-calibrate-classifiers-with-calibratedclassifiercv&sa=D&source=editors&ust=1621930682044000&usg=AOvVaw08yzWnlTQaNvcyAneeFVab)
2.  [How to speed up isotonic regression for sklearn](https://www.google.com/url?q=http://tullo.ch/articles/speeding-up-isotonic-regression/&sa=D&source=editors&ust=1621930682045000&usg=AOvVaw2wD11HNZG24XNLc0hDj3IH)
3.  TODO: how to calibrate a DNN (except sklearn wrapper for keras)
4.  Allows us to use the probability as confidence. I.e, Well calibrated classifiers are probabilistic classifiers for which the output of the predict_proba method can be directly interpreted as a confidence level
5.  (good) [Probability Calibration Essentials (with code)](https://www.google.com/url?q=https://medium.com/analytics-vidhya/probability-calibration-essentials-with-code-6c446db74265&sa=D&source=editors&ust=1621930682046000&usg=AOvVaw1CT6AuHcGTKRYhwm20cqBB)
6.  The [Brier score](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Brier_score&sa=D&source=editors&ust=1621930682047000&usg=AOvVaw2cFQRyUZZxW0bgkm4WVxP2)is a [proper score function](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Scoring_rule%23ProperScoringRules&sa=D&source=editors&ust=1621930682047000&usg=AOvVaw0zMAB72z45UkUioV7tELP2) that measures the accuracy of probabilistic predictions.
7.  [Sk learn](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/calibration/plot_calibration_curve.html%23sphx-glr-auto-examples-calibration-plot-calibration-curve-py&sa=D&source=editors&ust=1621930682049000&usg=AOvVaw1fVIHrGmOT0PBrHH7rnqkV) example
8.  [‘calibrated classifier cv in sklearn](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.calibration.CalibratedClassifierCV.html%23sklearn.calibration.CalibratedClassifierCV&sa=D&source=editors&ust=1621930682050000&usg=AOvVaw3yorT1DOGCz96pWHotw3RN)\- The method to use for calibration. Can be ‘sigmoid’ which corresponds to Platt’s method or ‘isotonic’ which is a non-parametric approach. It is not advised to use isotonic calibration with too few calibration samples (<<1000) since it tends to overfit. Use sigmoids (Platt’s calibration) in this case.  
    However, not all classifiers provide well-calibrated probabilities, some being over-confident while others being under-confident. Thus, a separate calibration of predicted probabilities is often desirable as a postprocessing. This example illustrates two different methods for this calibration and evaluates the quality of the returned probabilities using Brier’s score
9.  Example [1](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/calibration/plot_calibration.html%23sphx-glr-auto-examples-calibration-plot-calibration-py&sa=D&source=editors&ust=1621930682051000&usg=AOvVaw3-oe9oYbTgoZlinaq6LarB)\- binary class below, [2](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/calibration/plot_calibration_multiclass.html%23sphx-glr-auto-examples-calibration-plot-calibration-multiclass-py&sa=D&source=editors&ust=1621930682051000&usg=AOvVaw3fQbKpJ2QMls8bSW8kZpJx)\- 3 class moving prob vectors to a well defined location, [3](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/calibration/plot_compare_calibration.html%23sphx-glr-auto-examples-calibration-plot-compare-calibration-py&sa=D&source=editors&ust=1621930682052000&usg=AOvVaw15khrHobqmmHpshMpMyaQs) \- comparison of non calibrated models, only logreg is calibrated naturally

![](images/image228.png)

10. [Mastery on why we need calibration](https://www.google.com/url?q=https://machinelearningmastery.com/calibrated-classification-model-in-scikit-learn/&sa=D&source=editors&ust=1621930682052000&usg=AOvVaw3F70WWa9HmYB9P6nIL_P8-)
11. [Why softmax is not good as an uncertainty measure for DNN](https://www.google.com/url?q=https://stats.stackexchange.com/questions/309642/why-is-softmax-output-not-a-good-uncertainty-measure-for-deep-learning-models&sa=D&source=editors&ust=1621930682053000&usg=AOvVaw23GhMOiQJNFtq77qcPgy2y)
12. [If a model doesn't have probabilities use the decision function](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/calibration/plot_calibration_curve.html%23sphx-glr-auto-examples-calibration-plot-calibration-curve-py&sa=D&source=editors&ust=1621930682054000&usg=AOvVaw1kkCwBdynDurrIo2nnl9__)

y_pred = clf.predict(X_test)  
       ifhasattr(clf, "predict_proba"):  
           prob_pos = clf.predict\_proba(X\_test)\[:, 1\]  
       else:  \# use decision functionprob_pos = clf.decision\_function(X\_test)  
           prob_pos =\  
               (prob_pos - prob_pos.min()) / (prob_pos.max() - prob_pos.min())  

NEURAL NET CALIBRATION
----------------------

1.  [Temperature in LSTM](https://www.google.com/url?q=https://www.quora.com/What-is-Temperature-in-LSTM&sa=D&source=editors&ust=1621930682057000&usg=AOvVaw2pPJ19YHNqStCUyp232WnH)
2.  [Paper: Calibration of modern NN](https://www.google.com/url?q=https://arxiv.org/pdf/1706.04599.pdf&sa=D&source=editors&ust=1621930682057000&usg=AOvVaw1df2lfFAQqWhbewPzLmhnZ)
3.  [Calibration post](https://www.google.com/url?q=http://geoffpleiss.com/nn_calibration&sa=D&source=editors&ust=1621930682058000&usg=AOvVaw2PTHyMCr6m2FB9WUynmC1v)
4.  [Change temperature in keras](https://www.google.com/url?q=https://stackoverflow.com/questions/37246030/how-to-change-the-temperature-of-a-softmax-output-in-keras&sa=D&source=editors&ust=1621930682058000&usg=AOvVaw1mio7pKWDLNXIl3haYff0k)
5.  Calibration can also come in a different flavor, you want to make your algorithm certain, one trick is to use dropout layers when inferring/predicting/classifying, do it 100 times and average the results in some capacity , [see this chapter on BNN](#h.slqfz2k65bd2)
6.  [How Can We Know When Language Models Know? This paper is about calibration.](https://www.google.com/url?q=http://phontron.com/paper/jiang20lmcalibration.pdf&sa=D&source=editors&ust=1621930682059000&usg=AOvVaw1ESnjKQBDby7hestCCanKj)  
    “Recent works have shown that language models (LM) capture different types of knowledge regarding facts or common sense. However, because no model is perfect, they still fail to provide appropriate answers in many cases. In this paper, we ask the question “how can we know when language models know, with confidence, the answer to a particular query?” We examine this question from the point of view of calibration, the property of a probabilistic model’s predicted probabilities actually being well correlated with the probability of correctness. We first examine a state-ofthe-art generative QA model, T5, and examine whether its probabilities are well calibrated, finding the answer is a relatively emphatic no. We then examine methods to calibrate such models to make their confidence scores correlate better with the likelihood of correctness through fine-tuning, post-hoc probability modification, or adjustment of the predicted outputs or inputs. Experiments on a diverse range of datasets demonstrate the effectiveness of our methods. We also perform analysis to study the strengths and limitations of these methods, shedding light on further improvements that may be made in methods for calibrating LMs.”
    
    * * *
    

MULTI LABEL CLASSIFICATION
==========================

(what is?) [Multilabel classification](https://www.google.com/url?q=https://mlr-org.github.io/mlr-tutorial/devel/html/multilabel/index.html&sa=D&source=editors&ust=1621930682060000&usg=AOvVaw1Ev4cov91rYP2Q5ZAU392P) is a classification problem where multiple target labels can be assigned to each observation instead of only one like in multiclass classification.

Two different approaches exist for multilabel classification:

* Problem transformation methods try to transform the multilabel classification into binary or multiclass classification problems.
* Algorithm adaptation methods adapt multiclass algorithms so they can be applied directly to the problem.

I.e., the [Two approaches](https://www.google.com/url?q=https://mlr-org.github.io/mlr-tutorial/devel/html/multilabel/index.html&sa=D&source=editors&ust=1621930682061000&usg=AOvVaw0GC__pXnVJX9sGEuTGC5gJ) are:

* Use a classifier that does multi label
* Use any classifier with a wrapper that compares each two labels

great [PDF](https://www.google.com/url?q=https://users.ics.aalto.fi/jesse/talks/Multilabel-Part01.pdf&sa=D&source=editors&ust=1621930682062000&usg=AOvVaw0Xz11lrUPvDTnC6dt0J_Va)that explains about multi label classification and especially metrics, [part 2 here](https://www.google.com/url?q=https://users.ics.aalto.fi/jesse/talks/Multilabel-Part02.pdf&sa=D&source=editors&ust=1621930682062000&usg=AOvVaw2enMmXqlNdicMH83XwH--B)

[An awesome Paper](https://www.google.com/url?q=http://citeseerx.ist.psu.edu/viewdoc/download?doi%3D10.1.1.104.9401%26rep%3Drep1%26type%3Dpdf&sa=D&source=editors&ust=1621930682063000&usg=AOvVaw3U_vAepVAXe842CtKES7Qb)that explains all of these methods in detail, also available [here](https://www.google.com/url?q=https://www.researchgate.net/publication/273859036_Multi-Label_Classification_An_Overview&sa=D&source=editors&ust=1621930682063000&usg=AOvVaw2-SzVS4VkRtbi8awjBszlI)!

PT1: for each sample select one label, remove all others.

PT2: remove every sample which has multi labels.

PT3: for every combo of labels create a single-label, i.e. A&B, A&C etc..

PT4: (most common) create L datasets, for each label learn a binary representation, i.e., is it there or not.

PT5: duplicate each sample with only one of its labels

PT6: read the paper

There are other approaches for doing it within algorithms, they rely on the ideas PT3\\4\\5\\6 implemented in the algorithms, or other tricks.

They also introduce Label cardinality and label density.

[Efficient net](https://www.google.com/url?q=https://medium.com/gumgum-tech/multi-label-classification-for-threat-detection-part-1-60318b90ce11&sa=D&source=editors&ust=1621930682065000&usg=AOvVaw3gj5feFuSqBbUvxe_UXbpk), [part 2](https://www.google.com/url?q=https://medium.com/gumgum-tech/multi-label-image-classifier-for-threat-detection-with-fp16-inference-part-2-40fe0f9a93b3&sa=D&source=editors&ust=1621930682066000&usg=AOvVaw1pjgm6SI9ievkGkjioBU8F) \- EfficientNet is based on a network derived from a neural architecture search and novel compound scaling method is applied to iteratively build more complex network which achieves state of the art accuracy on multiclass classification tasks. Compound scaling refers to increasing the network dimensions in all three scaling formats using a novel strategy.

Multi label confusion matrices with sklearn

[Scikit multilearn package](https://www.google.com/url?q=http://scikit.ml/index.html&sa=D&source=editors&ust=1621930682067000&usg=AOvVaw1-zOTiJwlS0bUJctQu_CRX)

DISTRIBUTION
============

TYPES
-----

(What are?) probabilities in a distribution always add up to 1.

* [More distribution explanations](https://www.google.com/url?q=https://machinelearningmastery.com/statistical-data-distributions/&sa=D&source=editors&ust=1621930682068000&usg=AOvVaw1tndeQ4-r-pmVgjFSmo8eT)

* [A very good explanation](https://www.google.com/url?q=https://blog.cloudera.com/blog/2015/12/common-probability-distributions-the-data-scientists-crib-sheet/&sa=D&source=editors&ust=1621930682069000&usg=AOvVaw0A24zEkLIhlEDS6mrHMb2a)

![](images/image195.png)

* [A very wordy explanation](https://www.google.com/url?q=http://people.stern.nyu.edu/adamodar/New_Home_Page/StatFile/statdistns.htm&sa=D&source=editors&ust=1621930682070000&usg=AOvVaw334NEuCVpQ0os247pcGFxR) (figure2)

![](images/image244.png)

1.  [Poison and poison process](https://www.google.com/url?q=https://towardsdatascience.com/the-poisson-distribution-and-poisson-process-explained-4e2cb17d459&sa=D&source=editors&ust=1621930682071000&usg=AOvVaw18HzTBgcs8fx_8-oyKYWg0)

Comparing distributions:

1.  [Kolmogorov smirnov not good for categoricals.](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Kolmogorov%25E2%2580%2593Smirnov_test&sa=D&source=editors&ust=1621930682072000&usg=AOvVaw2jzcvBuF3kysrJpmTNL_iy)
2.  [Comparing two](https://www.google.com/url?q=https://math.stackexchange.com/questions/159940/comparing-distribution-of-two-data-sets&sa=D&source=editors&ust=1621930682072000&usg=AOvVaw0h3Wnchp6S96nS8NRMiZwI)
3.  [Khan academy](https://www.google.com/url?q=https://www.khanacademy.org/math/ap-statistics/quantitative-data-ap/describing-comparing-distributions/v/comparing-distributions&sa=D&source=editors&ust=1621930682073000&usg=AOvVaw0t4Rmq0WlNSy9nSMbiglp-)
4.  [Visually](https://www.google.com/url?q=https://www.stat.auckland.ac.nz/~ihaka/787/lectures-distrib.pdf&sa=D&source=editors&ust=1621930682074000&usg=AOvVaw0e_NheJ-VOWMroH9pHODpZ)
5.  [When they are not normal](https://www.google.com/url?q=https://www.quora.com/Which-statistical-test-to-use-to-quantify-the-similarity-between-two-distributions-when-they-are-not-normal&sa=D&source=editors&ust=1621930682074000&usg=AOvVaw0kgBuSQZHYz3q5YtBNe5bS)
6.  [Using train / test trick](https://www.google.com/url?q=https://towardsdatascience.com/how-dis-similar-are-my-train-and-test-data-56af3923de9b&sa=D&source=editors&ust=1621930682074000&usg=AOvVaw2D7iYgohpbf6iwWdZIfL9U)
7.  [Code for Identifying distribution type and params, based on best fit.](https://www.google.com/url?q=https://stackoverflow.com/questions/37487830/how-to-find-probability-distribution-and-parameters-for-real-data-python-3&sa=D&source=editors&ust=1621930682075000&usg=AOvVaw2oFWzuFJL9umvFtQLQvw80)

* * *

Gaussian \ Normal Distribution
------------------------------

[“ if you collect data and it is not normal, “you need to collect more data”](https://www.google.com/url?q=https://www.isixsigma.com/topic/normal-distributions-why-does-it-matter/&sa=D&source=editors&ust=1621930682076000&usg=AOvVaw2rc9yw4ALaCBo4U0oMQ_LT)

[Beautiful graphs](https://www.google.com/url?q=https://stats.stackexchange.com/questions/116550/why-do-we-have-to-assume-normality-for-a-one-sample-t-test&sa=D&source=editors&ust=1621930682076000&usg=AOvVaw2HwJgBnQakkjOnbdA2Dycd)

[The normal distribution is popular for two reasons:](https://www.google.com/url?q=https://www.quora.com/Why-do-we-use-the-normal-distribution-The-normal-is-an-approximation-Why-dont-we-use-a-simpler-distribution-with-simpler-numbers-to-memorize-If-it-is-an-approximation-does-it-have-to-be-so-specific&sa=D&source=editors&ust=1621930682077000&usg=AOvVaw1jecJHcJ5iUec8v4MXnp6S)

1.  It is the most common distribution in nature (as distributions go)
2.  An enormous number of statistical relationships become clear and tractable if one assumes the normal.

Sure, nothing in real life exactly matches the Normal. But it is uncanny how many things come close.

this is partly due to the Central Limit Theorem, which says that if you average enough unrelated things, you eventually get the Normal.

* the Normal distributionin statistics is a special world in which the math is straightforward and all the parts fit together in a way that is easy to understand and interpret.

* It may not exactly match the real world, but it is close enough that this one simplifying assumption allows you to predict lots of things, and the predictions are often pretty reasonable.

* statistically convenient.
* represented by basic statistics

* average
* variance (or standard deviation) - the average of what's left when you take away the average, but to the power of 2.

In a statistical test, you need the data to be normal to guarantee that your p-values are accurate with your given sample size.

If the data are not normal, your sample size may or may not be adequate, and it may be difficult for you to know which is true.

* * *

COMPARING DISTRIBUTIONS
-----------------------

1.  Categorical data can be transformed to a histogram i.e., #class / total and then measured for distance between two histograms’, e.g., train and production. Using earth mover distance [python](https://www.google.com/url?q=https://jeremykun.com/2018/03/05/earthmover-distance/&sa=D&source=editors&ust=1621930682080000&usg=AOvVaw16Ok6rjgd9MrY_DTfybQqr)[git wrapper to c](https://www.google.com/url?q=https://github.com/pdinges/python-emd&sa=D&source=editors&ust=1621930682080000&usg=AOvVaw04M7vTUKy3pDvF0vtLFy7T), linear programming, so its slow.
2.  [Earth movers](https://www.google.com/url?q=https://towardsdatascience.com/earth-movers-distance-68fff0363ef2&sa=D&source=editors&ust=1621930682081000&usg=AOvVaw0zGzF8cMf9dXMoH-CpWMau).
3.  [EMD paper](https://www.google.com/url?q=http://infolab.stanford.edu/pub/cstr/reports/cs/tr/99/1620/CS-TR-99-1620.ch4.pdf&sa=D&source=editors&ust=1621930682081000&usg=AOvVaw0E5wON_RfEwdh5RPrVg7zP)
4.  Also check KL DIVERGENCE in the information theory section.
5.  [Bengio](https://www.google.com/url?q=https://arxiv.org/abs/1901.10912&sa=D&source=editors&ust=1621930682082000&usg=AOvVaw0No7a5x8BM53ZoCaclO5HW) et al, transfer objective for learning to disentangle casual mechanisms - We propose to meta-learn causal structures based on how fast a learner adapts to new distributions arising from sparse distributional changes

* * *

DISTRIBUTION TRANSFORMATION
===========================

1.  [Top 3 methods for handling skewed data](https://www.google.com/url?q=https://towardsdatascience.com/top-3-methods-for-handling-skewed-data-1334e0debf45&sa=D&source=editors&ust=1621930682083000&usg=AOvVaw3UONJRGae6MrxGnqzxlZ_O). Log, square root, box cox transformations

BOX COX
-------

[Power transformations](https://www.google.com/url?q=https://machinelearningmastery.com/power-transforms-with-scikit-learn/?fbclid%3DIwAR37SGKEXWQ_39qZLKAQ5WunSECo0JXsd3qgz3dPGITTGcVwHJla-_7GLKg&sa=D&source=editors&ust=1621930682084000&usg=AOvVaw39zLzLO8J6jG-9_Tpu6xcB)

(What is the Box-Cox Power Transformation?)

* a procedure to identify an appropriate exponent (Lambda = l) to use to transform data into a “normal shape.”
* The Lambda value indicates the power to which all data should be raised.

![](images/image134.png)

[The Box-Cox transformation is a useful family of transformations.](https://www.google.com/url?q=http://www.itl.nist.gov/div898/handbook/eda/section3/eda336.htm&sa=D&source=editors&ust=1621930682086000&usg=AOvVaw3femyuOfenwH-YkKmlQsTn)

* Many statistical testsand intervals are based on the assumption of normality.
* The assumption of normality often leads to tests that are simple, mathematically tractable, and powerful compared to tests that do not make the normality assumption.
* Unfortunately, many real data sets are in fact not approximately normal.
* However, an appropriate transformationof a data set can often yield a data set that does follow approximately a normal distribution.
* This increases the applicability and usefulnessof statistical techniques based on thenormality assumption.![](images/image156.png)

IMPORTANT:!! After a transformation (c), we need to measure the normality of the resulting transformation (d) .

* One measure is to compute the correlation coefficient of a [normal probability plot](https://www.google.com/url?q=http://www.itl.nist.gov/div898/handbook/eda/section3/normprpl.htm&sa=D&source=editors&ust=1621930682088000&usg=AOvVaw2OsopEaTGd8teXql1DbpGG)=\> (d).
* The correlation is computed between the vertical and horizontal axis variables of the probability plot and is a convenient measure of the linearity of the probability plot
* In other words: the more linear the probability plot, the better a normal distribution fits the data!

[*NOTE: another useful link that explains it with figures, but i did not read it.](https://www.google.com/url?q=http://blog.minitab.com/blog/applying-statistics-in-quality-projects/how-could-you-benefit-from-a-box-cox-transformation&sa=D&source=editors&ust=1621930682089000&usg=AOvVaw2jBSrTsEgRYcuyE_lVP4Rd)

GUARANTEED NORMALITY?

* NO!
* This is because it actually does not really check for normality;
* the method checks for the smallest standard deviation.
* The assumption is that among all transformations with Lambda values between -5 and +5, transformed data has the highest likelihood – but not a guarantee – to be normally distributed when standard deviation is the smallest.
* it is absolutely necessary to always check the transformed data for normality using a probability plot. (d)

\+ Additionally, the Box-Cox Power transformation only works if all the data is positive and greater than 0.

+ achieved easily by adding a constant ‘c’ to all data such that it all becomes positive before it is transformed. The transformation equation is then:

[COMMON TRANSFORMATION FORMULAS (based on the actual formula)](https://www.google.com/url?q=http://www.statisticshowto.com/box-cox-transformation/&sa=D&source=editors&ust=1621930682091000&usg=AOvVaw2wICP8RAOol3eYunFg_K_W)

![](images/image31.png)

Finally: An awesome [tutorial (dead),](https://www.google.com/url?q=http://www.kmdatascience.com/2017/07/box-cox-transformations-in-python.html&sa=D&source=editors&ust=1621930682092000&usg=AOvVaw34gutYPKwVycng-DSBQ255)[here is a new one](https://www.google.com/url?q=https://towardsdatascience.com/box-cox-transformation-explained-51d745e34203%23:~:text%3Dscipy.stats.boxcox(),the%252095%2525%2520confidence%2520interval).&sa=D&source=editors&ust=1621930682092000&usg=AOvVaw0j589wa3ixeAgVIAYBMUap)in python with [code examples](https://www.google.com/url?q=https://github.com/kentmacdonald2/Box-Cox-Transformation-Python-Example&sa=D&source=editors&ust=1621930682093000&usg=AOvVaw2m0Co9DEnaEEKK3-IL72OC), there is also another code example [here](https://www.google.com/url?q=https://stackoverflow.com/questions/33944129/python-library-for-data-scaling-centering-and-box-cox-transformation&sa=D&source=editors&ust=1621930682093000&usg=AOvVaw37oivAKJ2l_wcsl4d-67aK)  
“Simply pass a 1-D array into the function and it will return the Box-Cox transformed array and the optimal value for lambda. You can also specify a number, alpha, which calculates the confidence interval for that value. (For example, alpha = 0.05 gives the 95% confidence interval).”

![](images/image113.png)

\* Maybe there is a slight problem in the python vs R code, [details here](https://www.google.com/url?q=http://shahramabyari.com/2015/12/21/data-preparation-for-predictive-modeling-resolving-skewness/&sa=D&source=editors&ust=1621930682094000&usg=AOvVaw0RhS0K9novGfwptzva0Rct), but needs investigating.

MANN-WHITNEY U TEST
-------------------

([what is?](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Mann%25E2%2580%2593Whitney_U_test&sa=D&source=editors&ust=1621930682095000&usg=AOvVaw2K4f69c2v8eEB-o9z0k60m)) \- the Mann–Whitney U testis a [nonparametric](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Nonparametric_statistics&sa=D&source=editors&ust=1621930682096000&usg=AOvVaw1kW0V3pyO4FkZ9cTj3BgWX)[test](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Statistical_hypothesis_test&sa=D&source=editors&ust=1621930682096000&usg=AOvVaw0mvYw0R_UP0Xh5T-B4boVm)of the [null hypothesis](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Null_hypothesis&sa=D&source=editors&ust=1621930682096000&usg=AOvVaw25KT8v81XWWPwvbF5QRHms) that it is equally likely that a randomly selected value from one sample will be less than or greater than a randomly selected value from a second sample.

In other words: This test can be used to determine whether two independentsamples were selected from populations having the same distribution.

Unlike the [t](https://www.google.com/url?q=https://en.wikipedia.org/wiki/T-test&sa=D&source=editors&ust=1621930682098000&usg=AOvVaw0K_QJmZyWmDNBCAzUucNkQ)[-test](https://www.google.com/url?q=https://en.wikipedia.org/wiki/T-test&sa=D&source=editors&ust=1621930682098000&usg=AOvVaw0K_QJmZyWmDNBCAzUucNkQ)it does not require the assumption of [normal distributions](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Normal_distribution&sa=D&source=editors&ust=1621930682098000&usg=AOvVaw1J_90yaX1ybo0n0G3viyc6). It is nearly as efficient as the t-test on normal distributions.

NULL HYPOTHESIS
---------------

1.  [What is chi-square and what is a null hypothesis, and how do we calculate observed vs expected and check if we can reject the null and get significant difference.](https://www.google.com/url?q=https://medium.com/greyatom/goodness-of-fit-using-chi-square-be5bba375caf&sa=D&source=editors&ust=1621930682099000&usg=AOvVaw1aa9PSjjtV_U9hMUDeFXFY)
2.  Analytics vidhya

1.  [What is hypothesis testing](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2015/09/hypothesis-testing-explained/&sa=D&source=editors&ust=1621930682100000&usg=AOvVaw1hVtHN7oD9NeImTPZof9QO)
2.  [Intro to t-tests analytics vidhya](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2019/05/statistics-t-test-introduction-r-implementation/?utm_source%3Dfacebook.com%26utm_medium%3Dsocial&sa=D&source=editors&ust=1621930682101000&usg=AOvVaw3HXF9vVGM859X6GqL2majI) \- always good
3.  [Anova analysis of variance](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2018/01/anova-analysis-of-variance/?utm_source%3Dfacebook.com%26utm_medium%3Dsocial%26fbclid%3DIwAR1lMhaoKevShaIDpNoRNPL-V7y_LMscZSPG_0Dp1qvCkhDoJgzyt4fMDKM&sa=D&source=editors&ust=1621930682102000&usg=AOvVaw1bbC3CgRZK4SxckLn12ecw), one way, two way, manova

1.   if the means of two or more groups are significantly different from each other. ANOVA checks the impact of one or more factors by comparing the means of different samples.
2.  A one-way ANOVA tells us that at least two groups are different from each other. But it won’t tell us which groups are different.
3.  For such cases, when the outcome or dependent variable (in our case the test scores) is affected by two independent variables/factors we use a slightly modified technique called two-way ANOVA.

1.  multivariate case and the technique we will use to solve it is known as MANOVA.
    
    * * *
    

INFORMATION THEORY
==================

ENTROPY / INFORMATION GAIN
--------------------------

1.  [Shannon entropy in python, basically entropy(value counts)](https://www.google.com/url?q=https://www.kite.com/python/answers/how-to-calculate-shannon-entropy-in-python&sa=D&source=editors&ust=1621930682103000&usg=AOvVaw0F1NPIu1Wl29BVTa_5rSRb)
2.  [Mastery on plogp entropy function](https://www.google.com/url?q=https://machinelearningmastery.com/what-is-information-entropy/&sa=D&source=editors&ust=1621930682104000&usg=AOvVaw2YcLbTFGEHHR9toaghP5Y0)
3.  [Entropy functions](https://www.google.com/url?q=https://gist.github.com/jaradc/eeddf20932c0347928d0da5a09298147&sa=D&source=editors&ust=1621930682105000&usg=AOvVaw2qrDIVqdhxCAz499MnbviM)

[Great tutorial on all of these topics](https://www.google.com/url?q=https://www.bogotobogo.com/python/scikit-learn/scikt_machine_learning_Decision_Tree_Learning_Informatioin_Gain_IG_Impurity_Entropy_Gini_Classification_Error.php&sa=D&source=editors&ust=1621930682105000&usg=AOvVaw3KrNdC1N_9bl7aWYjAz-KQ)\*\*\*

[Entropy](https://www.google.com/url?q=https://www.techleer.com/articles/496-a-short-introduction-to-entropy-cross-entropy-and-kl-divergence-aurelien-geron/&sa=D&source=editors&ust=1621930682106000&usg=AOvVaw0EsIaLjWMe_tuqZp3E9sjr) \- lack of orderor lack of predictability ([excellent slide lecture by Aurelien Geron](https://www.google.com/url?q=https://www.youtube.com/watch?time_continue%3D3%26v%3DErfnhcEV1O8&sa=D&source=editors&ust=1621930682107000&usg=AOvVaw0VeFM4b_NcPdBeBPC9GbDW))

![](images/image108.png)

![](images/image145.png)

Cross entropy will be equal to entropy if the probability distributions of p (true) and q(predicted) are the same. However, if cross entropy is bigger (known as relative_entropy or kullback leibler divergence)

![](images/image111.png)

![](images/image37.png)

In this example we want the cross entropy loss to be zero, i.e., when we have a one hot vector and a predicted vector which are identical, i.e., 100% in the same class for predicted and true, we get 0. In all other cases we get some number that gets larger if the predicted class probability is lower than zero as seen here:

![](images/image33.png)

* * *

Formula for 2 classes:

![](images/image133.png)

NOTE: Entropy can be generalized as a formula for N > 2 classes:

![](images/image182.png)

(We want to grow a simple tree) [awesome pdf tutorial](https://www.google.com/url?q=http://www.ke.tu-darmstadt.de/lehre/archiv/ws0809/mldm/dt.pdf&sa=D&source=editors&ust=1621930682110000&usg=AOvVaw3rZ3w9Oq5FAllGYxxGuBHu)→ a good attribute prefers attributes that split the data so that each successor node is as pure as possible

* i.e., the distribution of examples in each node is so that it mostly contains examples of a single class
* In other words:  We want a measure that prefers attributes that have a high degree of „order“:
* Maximum order: All examples are of the same class
* Minimum order: All classes are equally likely → Entropy is a measure for (un-)orderedness  Another interpretation:
* Entropy is the amount of information that is contained
* all examples of the same class → no information

![](images/image190.png)

Entropy is the amount of unorderedness in the class distribution of S

IMAGE above:

* Maximal value when the equal class distribution
* Minimal value when only one class is in S

So basically if we have the outlook attribute and it has 3 categories, we calculate the entropy for E(feature=category) for all 3.

![](images/image95.png)

INFORMATION: The I(S,A) formula below.

What we actually want is the average entropy of theentire split, that corresponds to an entire attribute, i.e., OUTLOOK (sunny & overcast & rainy)

![](images/image17.png)

Information Gain: is actually what we gain by subtracting information from the entropy.

In other words we find the attributes that maximizes that difference,in other other words, the attribute that reduces the unorderness / lack of order / lack of predictability.

The BIGGER GAIN is selected.

![](images/image9.png)

There are some properties to Entropy that influence INFO GAIN (?):

![](images/image76.png)

There are some disadvantages with INFO GAIN, done use it when an attribute has many number values, such as “day” (date wise) 05/07, 06/07, 07/07..31/07  etc.

Information gain is biased towards choosing attributes with a large number of values and causes:

* Overfitting
* fragmentation

![](images/image275.png)

* * *

We measure Intrinsic information of an attribute, i.e., Attributes with higher intrinsic information are less useful.

We define Gain Ratioas info-gain with less bias toward multi value attributes, ie., “days”

NOTE: Day attribute would still win with the Gain Ratio, Nevertheless: Gain ratio is more reliable than Information Gain

![](images/image232.png)

* * *

Therefore, we define the alternative, which is the GINI INDEX. It measures impurity, we define the average Gini, and the Gini Gain.

![](images/image143.png)

[FINALLY, further reading about decision trees and examples of INFOGAIN and GINI here.](https://www.google.com/url?q=http://www.ke.tu-darmstadt.de/lehre/archiv/ws0809/mldm/dt.pdf&sa=D&source=editors&ust=1621930682118000&usg=AOvVaw0op_4Fnvv4LmCUZelEDcC3)

[Variational bounds on mutual informati](https://www.google.com/url?q=https://arxiv.org/abs/1905.06922v1&sa=D&source=editors&ust=1621930682118000&usg=AOvVaw0qE2rOBqclto4jZ_VcL5TV)on

CROSS ENTROPY, RELATIVE ENT, KL-D, JS-D, SOFT MAX
-------------------------------------------------

1.  [A really good explanation on all of them](https://www.google.com/url?q=https://www.countbayesie.com/blog/2017/5/9/kullback-leibler-divergence-explained&sa=D&source=editors&ust=1621930682119000&usg=AOvVaw33XNj65RuPZcfW78XSUh4F)
2.  [Another good one on all of them](https://www.google.com/url?q=https://gombru.github.io/2018/05/23/cross_entropy_loss/&sa=D&source=editors&ust=1621930682119000&usg=AOvVaw2tk1QBHrusO1v0NJYVzR6Q)
3.  [Mastery on entropy](https://www.google.com/url?q=https://machinelearningmastery.com/divergence-between-probability-distributions/&sa=D&source=editors&ust=1621930682120000&usg=AOvVaw3wO7vfIHol6iuwrCEe_R5K), kullback leibler divergence (asymmetry), jensen-shannon divergence (symmetry) (has code)
4.  [Entropy, mutual information and KL Divergence by AurelienGeron](https://www.google.com/url?q=https://www.techleer.com/articles/496-a-short-introduction-to-entropy-cross-entropy-and-kl-divergence-aurelien-geron/&sa=D&source=editors&ust=1621930682120000&usg=AOvVaw1iqq95aspp8UQKaiXF4O6F)
5.  [Gensim on divergence](https://www.google.com/url?q=https://radimrehurek.com/gensim/auto_examples/tutorials/run_distance_metrics.html%23sphx-glr-auto-examples-tutorials-run-distance-metrics-py&sa=D&source=editors&ust=1621930682121000&usg=AOvVaw3Kz1GLSOCY34rWzfOoS8zE) metrics such as KL jaccard etc, pros and cons, lda is a mess on small data.
6.  [Advise on KLD](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/9262/calculating-kl-divergence-in-python&sa=D&source=editors&ust=1621930682121000&usg=AOvVaw04htL5YSeT2GkigTIU2t7N)ivergence

SOFTMAX
-------

1.  [Understanding softmax](https://www.google.com/url?q=https://medium.com/data-science-bootcamp/understand-the-softmax-function-in-minutes-f3a59641e86d&sa=D&source=editors&ust=1621930682122000&usg=AOvVaw0dRmKjS6oKD7cp0Bqm0-dm)
2.  [Softmax and negative likelihood (NLL)](https://www.google.com/url?q=https://ljvmiranda921.github.io/notebook/2017/08/13/softmax-and-the-negative-log-likelihood/&sa=D&source=editors&ust=1621930682122000&usg=AOvVaw0xu0ZtAUUkxw5YrH9KsjkD)
3.  [Softmax vs cross entropy](https://www.google.com/url?q=https://www.quora.com/Is-the-softmax-loss-the-same-as-the-cross-entropy-loss%23&sa=D&source=editors&ust=1621930682123000&usg=AOvVaw3HiYGRepsVyhFHegHOOs1e)\- Softmax loss and cross-entropy loss terms are used interchangeably in industry. Technically, there is no term as such Softmax loss. people use the term "softmax loss" when referring to "cross-entropy loss". The softmax classifier is a linear classifier that uses the cross-entropy loss function. In other words, the gradient of the above function tells a softmax classifier how exactly to update its weights using some optimization like [gradient descent](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Gradient_descent&sa=D&source=editors&ust=1621930682123000&usg=AOvVaw1Qdh3I3jEip1X6OOQTILNw).

The softmax() part simply normalises your network predictions so that they can be interpreted as probabilities. Once your network is predicting a probability distribution over labels for each input, the log loss is equivalent to the cross entropy between the true label distribution and the network predictions. As the name suggests, softmax function is a “soft” version of max function. Instead of selecting one maximum value, it breaks the whole (1) with maximal element getting the largest portion of the distribution, but other smaller elements getting some of it as well.

This property of softmax function that it outputs a probability distribution makes it suitable for probabilistic interpretation in classification tasks.

Cross entropy indicates the distance between what the model believes the output distribution should be, and what the original distribution is. Cross entropy measure is a widely used alternative of squared error. It is used when node activations can be understood as representing the probability that each hypothesis might be true, i.e. when the output is a probability distribution. Thus it is used as a loss function in neural networks which have softmax activations in the output layer.

* * *

TIME SERIES ENTROPY
-------------------

1.  [entroPY](https://www.google.com/url?q=https://raphaelvallat.com/entropy/build/html/index.html&sa=D&source=editors&ust=1621930682124000&usg=AOvVaw0DyxvxAyGLgcXiE60n08-N)\- EntroPy is a Python 3 package providing several time-efficient algorithms for computing the complexity of one-dimensional time-series. It can be used for example to extract features from EEG signals.

[Approximate entropy paper](https://www.google.com/url?q=https://journals.physiology.org/doi/pdf/10.1152/ajpheart.2000.278.6.H2039&sa=D&source=editors&ust=1621930682125000&usg=AOvVaw0cT6V8i0sLEwGGWfUdQ0Z7)  

print(perm_entropy(x, order=3, normalize=True)) \# Permutation entropy

print(spectral_entropy(x, 100, method='welch', normalize=True)) \# Spectral entropy

print(svd_entropy(x, order=3, delay=1, normalize=True)) \# Singular value decomposition entropy

print(app_entropy(x, order=2, metric='chebyshev'))              \# Approximate entropy

print(sample_entropy(x, order=2, metric='chebyshev')) \# Sample entropy

print(lziv_complexity('01111000011001', normalize=True))        \# Lempel-Ziv complexity

2.  [PyInform](https://www.google.com/url?q=https://elife-asu.github.io/PyInform/index.html&sa=D&source=editors&ust=1621930682127000&usg=AOvVaw3DSk_eI2JjgXTgdj2MpvRB)![](images/image69.png)![](images/image217.png)

GAME THEORY
===========

1.  [In computer science](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2019/11/game-theory-ai/&sa=D&source=editors&ust=1621930682128000&usg=AOvVaw0y-SZQ4vRbIROlCrTpkYhd)
    
    * * *
    

DATASETS
========

Structured / Unstructured data
------------------------------

[Unstructured](https://www.google.com/url?q=https://www.webopedia.com/TERM/U/unstructured_data.html&sa=D&source=editors&ust=1621930682128000&usg=AOvVaw2cLA8_kyIinZ0hReFAjWYc)

[Structured](https://www.google.com/url?q=https://www.webopedia.com/TERM/S/structured_data.html&sa=D&source=editors&ust=1621930682129000&usg=AOvVaw0398LjHU7QD6794miecz8g)

BIAS / VARIANCE
---------------

[Overfitting your test set, a statistican view point, a great article](https://www.google.com/url?q=https://lukeoakdenrayner.wordpress.com/2019/09/19/ai-competitions-dont-produce-useful-models/?fbclid%3DIwAR1WM5U7imq-2LFPifyCoTPp-MFwPoGROMLr2TZWAp41qgVeLdT-_2bkLyk%26blogsub%3Dconfirming%23subscribe-blog&sa=D&source=editors&ust=1621930682129000&usg=AOvVaw1gaQBnESFO75RbraJ3eHn5), bottom line use bonferroni correction.

Understanding what is the next stage in DL (& ML) algorithm development: basic approach - [Andrew NG](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DF1ka6a13S9I&sa=D&source=editors&ust=1621930682130000&usg=AOvVaw0BQHQXJ7CjWu0bBETUKDBK) on youtube

Terms: training, validation, test.

Split: training & validation 70%, test 30%

Procedure: crossfold training and validation, or further split 70% to training and validation.
----------------------------------------------------------------------------------------------

BIAS - Situation 1 - doing much worse than human:

Human expert: 1% error

Training set error: 5% error (test on train)

Validation set error: 6% error (test on validation or CFV)

Conclusion: there is a BIAS between human expert and training set

Solution: 1. Train deeper or bigger\\larger networks, 2. train longer, 3. May needs more data to get to the human expert level, Or 4. New model architecture.

VARIANCE - Situation 2 - validation set not close to training set error:

Human expert: 1% error

Training set error: 2% error

Validation set error: 6% error

Conclusion: there is a VARIANCE problem, i.e. OVERFITTING, between training and validation.

Solution: 1. Early stopping, 2. Regularization or 3. get more data, or 4. New model architecture.

Situation 3 - both:

Human expert: 1% error

Training set error: 5% error

Validation set error: 10% error

Conclusion: both problems occur, i.e., BIAS as and VARIANCE .

Solution:  do it all.

Underfitting = Get more data

Overfitting = Early stop, regularization, reason: models detail & noise.

* Happens more in non parametric (and non linear) algorithms such as decision trees.

Bottom line, bigger model or more data will solve most issues.

\+ In practice advice with [regularized linear regression.](https://www.google.com/url?q=http://www.holehouse.org/mlclass/10_Advice_for_applying_machine_learning.html&sa=D&source=editors&ust=1621930682133000&usg=AOvVaw2EByTyG0M6isBWKwHKRJC6)

![](images/image227.png)

![](images/image21.png)

![](images/image48.png)

![](images/image29.png)

IMPORTANT! For Test Train efficiency when the data is from different distributions:

E.g: TRAIN: 50K hours of voice chatter as the train set for a DLN, TEST: 10H for specific voice-based problem, i.e, taxi chatter.

Best practice: better to divide the validation & test from the same distribution, i.e. the 10H set.

Reason: improving scores on validation which is from a diff distribution will not be the same quality as improving scores on a validation set originated from the actual distribution of the problem’s data, i.e., 10H.

NOTE: Unlike the usual supervised learning, where all the data is from the same distribution, where we split the training to train and validation (cfv).

[Situation 4](https://www.google.com/url?q=https://youtu.be/F1ka6a13S9I?t%3D47m26s&sa=D&source=editors&ust=1621930682134000&usg=AOvVaw3B6UaBvYlmDct0VauZnqGv): However, when there are 2 distributions it’s possible to extend the division of the training set to validation_training and training, and the test to validation and test.

Split:  Train, Valid_Train = 48K\\2K & Valid, Test, 5K & 5K.

![](images/image20.png)

So situation 1 stays the same,

Situation 2 is Valid\_Train error (train\_dev)

Situation 3 is Valid_Test error - need more data, data synthesis \- tweak test to be similar to train data, new architecture as a solution

Situation 4 is now Test set error - get more data

SPARSE DATASETS
---------------

[Sparse matrices](https://www.google.com/url?q=https://machinelearningmastery.com/sparse-matrices-for-machine-learning/&sa=D&source=editors&ust=1621930682135000&usg=AOvVaw1JQhNUmRr33gwvm6kavSVb) in ML - one hot/tfidf, dictionary/list of lists/ coordinate list.

* * *

TRAINING METHODOLOGIES
----------------------

1.  Train test split
2.  Cross validation
3.  Transfer learning - using a pre existing classifier similar to your domain, usually trained on millions of samples. fine-tuned on new data in order to create a new classifier that utilizes that information in the new domain. Examples such as w2v or classic resnet fine-tuning.
4.  Bootstrapping training- using a similar dataset, such as yelp, with 5 stars to create a pos/neg sentiment classifier based on 1 star and 5 stars. Finally using that to label or sample select from an unlabelled dataset, in order to create a new classifier or just to sample for annotation etc.
5.  [Student-teacher paradigm](https://www.google.com/url?q=https://developers.facebook.com/videos/2019/from-visual-recognition-to-reasoning/&sa=D&source=editors&ust=1621930682136000&usg=AOvVaw2MuguUOEYhzE3FsZSrKb9D) (facebook), using a big labelled dataset to train a teacher classifier, predicting on unlabelled data, choosing the best classified examples based on probability, using those to train a new student model, finally fine-tune on the labeled dataset to create a more robust model, which is expected to know the unlabelled dataset and the labelled dataset with higher accuracy. With respect to the fully supervised teacher model / baseline.

![](images/image194.png)

6.  Yoav’s method for transfer learning for languages - train a classifier on labelled data from english and spanish, fine tune using left out spanish data, stop before overfitting. This can be generalized to other domains.

### TRANSFER LEARNING

1.  [In deep learning](https://www.google.com/url?q=https://towardsdatascience.com/a-comprehensive-hands-on-guide-to-transfer-learning-with-real-world-applications-in-deep-learning-212bf3b2f27a&sa=D&source=editors&ust=1621930682137000&usg=AOvVaw2MABfwTVfjZqyp93jyvstv)
2.  ![](images/image47.png)

* * *

TRAIN / TEST / CROSS VALIDATION
-------------------------------

[Scikit-lego on group-based splitting and transformation](https://www.google.com/url?q=https://scikit-lego.readthedocs.io/en/latest/meta.html%23Grouped-Prediction&sa=D&source=editors&ust=1621930682138000&usg=AOvVaw085QLXTlI5WoHoY8-kKzoi)

[Images from here](https://www.google.com/url?q=https://www.kdnuggets.com/2017/08/dataiku-predictive-model-holdout-cross-validation.html&sa=D&source=editors&ust=1621930682138000&usg=AOvVaw1MykJJDeks2QPkiW-zDZ5d).

![](images/image78.png)

![](images/image45.png)

[Train Test methodology](https://www.google.com/url?q=http://machinelearningmastery.com/how-to-choose-the-right-test-options-when-evaluating-machine-learning-algorithms/&sa=D&source=editors&ust=1621930682139000&usg=AOvVaw1qJnsc_8W4XtTMnOB4r6-_) -

“[The training](https://www.google.com/url?q=https://stats.stackexchange.com/questions/19048/what-is-the-difference-between-test-set-and-validation-set&sa=D&source=editors&ust=1621930682140000&usg=AOvVaw2sA8HJ9d1yJ3b-tB_bYRzo) set is used to fit the models; the validation set is used to estimate prediction error for model selection; the test set is used for assessment of the generalization error of the final chosen model. Ideally, the test set should be kept in a “vault,” and be brought out only at the end of the data analysis”

* Random Split tests 66\\33 - problem: variance each time we rerun.
* Multiple times random split tests - problem: samples may not be included in train\\test or selected multiple times.
* Cross validation - pretty good, diff random seed results in diff mean accuracy, variance due to randomness
* Multiple cross validation - accounts for the randomness of the CV
* Statistical significance ( t-test)  on multi CV - are two samples drawn from the same population? (no difference). If “yes”, not significant, even if the mean and std deviations differ.

Finally, When in doubt, use k-fold cross validation (k=10) and use multiple runs of k-fold cross validation with statistical significance tests.

[Out of fold](https://www.google.com/url?q=https://machinelearningmastery.com/out-of-fold-predictions-in-machine-learning/&sa=D&source=editors&ust=1621930682141000&usg=AOvVaw0C70tncpm8oTmtRZUsIbCk) \- leave unseen data, do cross fold on that. Good for ensembles.

VARIOUS DATASETS
----------------

1.  [26 of them](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2018/05/24-ultimate-data-science-projects-to-boost-your-knowledge-and-skills/?utm_source%3Dfacebook.com%26utm_medium%3Dsocial&sa=D&source=editors&ust=1621930682141000&usg=AOvVaw1lNPVE4ug-Xg-0bkobGtJf)
2.  [24](https://www.google.com/url?q=https://lionbridge.ai/datasets/25-best-parallel-text-datasets-for-machine-translation-training/&sa=D&source=editors&ust=1621930682142000&usg=AOvVaw3TLN3QEtt5qocJmONEurFD)
3.  [Eu-](https://www.google.com/url?q=https://datarepository.wolframcloud.com/resources/Europarl-English-Spanish-Machine-Translation-Dataset-V7&sa=D&source=editors&ust=1621930682142000&usg=AOvVaw1hr1H4pq8evzyMpmI60RYT)es, [2](https://www.google.com/url?q=https://data.europa.eu/euodp/en/data/dataset/elrc_339&sa=D&source=editors&ust=1621930682142000&usg=AOvVaw0otGnWupS3sbwu1jmWtBCq)
4.  50K -  [ModelDepot](https://www.google.com/url?q=https://modeldepot.io/&sa=D&source=editors&ust=1621930682143000&usg=AOvVaw3LGOp38kbS_lQ-exlV3Ayx) alone has over 50,000 freely accessible pre-trained models with search functionality to

* * *

IMBALANCED DATASETS
-------------------

1.  ([the BEST resource and a great api for python)](https://www.google.com/url?q=http://contrib.scikit-learn.org/imbalanced-learn/stable/over_sampling.html&sa=D&source=editors&ust=1621930682143000&usg=AOvVaw31k1Kp5AbMM-xuwVVU2wLW) with visual samples - it actually works well on clustering.
2.  [Mastery on](https://www.google.com/url?q=https://machinelearningmastery.com/cost-sensitive-learning-for-imbalanced-classification/?fbclid%3DIwAR0_DeIydTAAkutypcMBfrnC4QyuyqVxDu_uej5t48AvQKShcRUqfMm8Rqo&sa=D&source=editors&ust=1621930682144000&usg=AOvVaw3Vim-yazpA6Hwgo1MSIPcT) cost sensitive sampling
3.  [Smote for imbalance](https://www.google.com/url?q=https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/?fbclid%3DIwAR3W59c54ohoaIHnHLQFCcZZanFXI4QzIzuWiUtaUC851JFkwlevCAgvpbM&sa=D&source=editors&ust=1621930682144000&usg=AOvVaw1Voa1cZptJ3rY-ng6dcq8D)

[Systematic Investigation of imbalance effects in CNN’s](https://www.google.com/url?q=https://arxiv.org/abs/1710.05381&sa=D&source=editors&ust=1621930682145000&usg=AOvVaw2Ef6wf7qCNufZkDqgu1vTS), with several observations. This is crucial when training networks, because in real life you don’t always get a balanced DS.

They recommend the following:

1.  (i) the effect of class imbalance on classification performance is detrimental;
2.  (ii) the method of addressing class imbalance that emerged as dominant in almost all analyzed scenarios was oversampling;
3.  (iii) oversampling should be applied to the level that totally eliminates the imbalance, whereas undersampling can perform better when the imbalance is only removed to some extent;
4.  (iv) as opposed to some classical machine learning models, oversampling does not necessarily cause overfitting of CNNs;
5.  (v) thresholding should be applied to compensate for prior class probabilities when overall number of properly classified cases is of interest.

General Rules:

1.  Many samples - undersampling
2.  Few  samples  - over sampling
3.  Consider random and non-random schemes
4.  Different sample rations, instead of 1:1 (proof? papers?)

Balancing data sets ([wiki](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Oversampling_and_undersampling_in_data_analysis&sa=D&source=editors&ust=1621930682146000&usg=AOvVaw2I6PFFzuda63bs8_aIWF9T), [scikit learn](https://www.google.com/url?q=https://github.com/scikit-learn-contrib/imbalanced-learn&sa=D&source=editors&ust=1621930682147000&usg=AOvVaw2SVoBv_KG1xoI3TgZsYA0Z)& [examples in SKLEARN](https://www.google.com/url?q=http://contrib.scikit-learn.org/imbalanced-learn/auto_examples/index.html&sa=D&source=editors&ust=1621930682147000&usg=AOvVaw2ba4zlaOw_dNMe4e2mpzdi)):

1.  Oversampling the minority class

1.  (Random) duplication of samples
2.  SMOTE [(in weka + needs to be installed](https://www.google.com/url?q=http://www.jair.org/media/953/live-953-2037-jair.pdf&sa=D&source=editors&ust=1621930682148000&usg=AOvVaw09W_YOX5TldEUnEuLuAk9j) &[paper)](https://www.google.com/url?q=http://www.jair.org/media/953/live-953-2037-jair.pdf&sa=D&source=editors&ust=1621930682148000&usg=AOvVaw09W_YOX5TldEUnEuLuAk9j) \- find k nearest neighbours,

New\_Sample = (random num in \[0,1\] ) * vec(ki,current\_sample)

* (in weka) The nearestNeighbors parameter says how many nearest neighbor instances (surrounding the currently considered instance) are used to build an in between synthetic instance. The default value is 5. Thus the attributes of 5 nearest neighbors of a real existing instance are used to compute a new synthetic one.
* (in weka) The percentage parameter says how many synthetic instances are created based on the number of the class with less instances (by default - you can also use the majority class by setting the -Coption). The default value is 100. This means if you have 25 instances in your minority class, again 25 instances are created synthetically from these (using their nearest neighbours' values). With 200% 50 synthetic instances are created and so on.

1.  ADASYN - shifts the classification boundary to the minority class, synthetic data generated for majority class.

2.  Undersampling the majority class

1.  Remove samples
2.  Cluster centroids - replaces a cluster of samples (k-means) with a centroid.
3.  Tomek links - cleans overlapping samples between classes in the majority class.
4.  Penalizing the majority class during training

3.  Combined over and under (hybrid) - i.e., SMOTE and tomek/ENN
4.  Ensemble sampling

1.  EasyEnsemble
2.  BalanceCascade

5.  Dont balance, try algorithms that perform well with unbalanced DS

1.  Decision trees - C4.5\\5\\CART\\Random Forest
2.  SVM

6.  Penalize Models -

1.  added costs for misclassification on the minority class during training such as penalized-SVM
2.  a [CostSensitiveClassifier](https://www.google.com/url?q=http://weka.sourceforge.net/doc.dev/weka/classifiers/meta/CostSensitiveClassifier.html&sa=D&source=editors&ust=1621930682150000&usg=AOvVaw1ZLTbgY5KFkv23R3GiwEsA) meta classifier in Weka that wraps classifiers and applies a custom penalty matrix for miss classification.
3.  complex

* * *

SAMPLE SELECTION
----------------

1.  [How to choose your sample size from a population based on confidence interval](https://www.google.com/url?q=https://www.checkmarket.com/blog/how-to-estimate-your-population-and-survey-sample-size/&sa=D&source=editors&ust=1621930682151000&usg=AOvVaw2ye3w89DyjoBKvHA3XLS3H)

![](images/image180.png)

2.  [Data advise, should we get more data? How much](https://www.google.com/url?q=https://machinelearningmastery.com/much-training-data-required-machine-learning/&sa=D&source=editors&ust=1621930682151000&usg=AOvVaw0aTaclq60FiTTPTkAC94cW)

[Gibbs sampling](https://www.google.com/url?q=https://wiseodd.github.io/techblog/2015/10/09/gibbs-sampling/&sa=D&source=editors&ust=1621930682151000&usg=AOvVaw2EBXjhi4KojN34OM-YVgoH): \- Gibbs Sampling is a MCMC method to draw samples from a potentially really really complicated, high dimensional distribution, where analytically, it’s hard to draw samples from it. The usual suspect would be those nasty integrals when computing the normalizing constant of the distribution, especially in Bayesian inference. Now Gibbs Sampler can draw samples from any distribution, provided you can provide all of the conditional distributions of the joint distribution analytically.

* * *

LEARNING CURVES
---------------

1.  [Git examples](https://www.google.com/url?q=https://gist.github.com/orico/260097cb1a2926c6b6ca6f71c37c135b&sa=D&source=editors&ust=1621930682152000&usg=AOvVaw1Z6bj1KsjaNxsI4qL0ys4o)
2.  [Sklearn examples](https://www.google.com/url?q=https://stats.stackexchange.com/questions/283738/sklearn-learning-curve-example&sa=D&source=editors&ust=1621930682153000&usg=AOvVaw22Urz_uml2kXEL5qei7dmp)
3.  [Understanding bias variance via learning curves](https://www.google.com/url?q=http://digitheadslabnotebook.blogspot.com/2011/12/practical-advice-for-applying-machine.html&sa=D&source=editors&ust=1621930682153000&usg=AOvVaw22Yyz68WnaoXxI35bwgmIO)
4.  [Unread - learning curve sampling applied to  model based clustering](https://www.google.com/url?q=http://www.jmlr.org/papers/volume2/meek02a/meek02a.pdf&sa=D&source=editors&ust=1621930682153000&usg=AOvVaw3HnoslHPSneR_PHjn2Fah6) \- seemed like active learning, i.e., sample using EM/cluster to achieve nearly as accurate on all data
5.  Predicting sample size required for training
6.  [Advice on many things, including learning curves](https://www.google.com/url?q=https://blog.acolyer.org/2018/03/28/deep-learning-scaling-is-predictable-empirically/amp/?fbclid%3DIwAR0V1X1vuCZYmeku12YHJI7wwK7RCKEyE2Q7aRDDT58hjRPzAOrHfvo98WY&sa=D&source=editors&ust=1621930682154000&usg=AOvVaw1eAkP5L-joXfYWeF3_wfX6)

This is a really wonderful study with far-reaching implications that could even impact company strategies in some cases. It starts with a simple question: “how can we improve the state of the art in deep learning?” We have three main lines of attack:

1.  We can search for improved model architectures.
2.  We can scale computation
3.  We can create larger training data sets.

DISTILLING DATA
---------------

1.  [Medium on](https://www.google.com/url?q=https://towardsdatascience.com/data-maps-datasets-can-be-distilled-too-1991c3c260d6&sa=D&source=editors&ust=1621930682155000&usg=AOvVaw0D0UNbx7_MScYGJzruGmeS) this [Dataset Cartography: Mapping and Diagnosing Datasets with Training Dynamics](https://www.google.com/url?q=https://arxiv.org/abs/2009.10795&sa=D&source=editors&ust=1621930682155000&usg=AOvVaw3pVYJpCi8AtgkaeUj6kMLj). What I found interesting about this paper is that it challenges the common approach of “the more the merrier” when it comes to training data, and shifts the focus from the quantity of the data to the quality of the data.

DATASET SELECTION
-----------------

1.  [Medium](https://www.google.com/url?q=https://medium.com/@amielmeiseles/how-to-choose-the-best-source-model-for-transfer-learning-41d5c91c1338&sa=D&source=editors&ust=1621930682156000&usg=AOvVaw0TVAeYPWoGMxOqpwXzkw02)
2.  ![](images/image215.png)

DATASET CONFIDENCE
==================

1.  [Dataset cartography mapping and diagnosing datasets with training dynamics -](https://www.google.com/url?q=https://arxiv.org/abs/2009.10795&sa=D&source=editors&ust=1621930682157000&usg=AOvVaw3cKcrE2yrM2nlqJ7y5aLGq) Large datasets have become commonplace in NLP research. However, the increased emphasis on data quantity has made it challenging to assess the quality of data. We introduce Data Maps---a model-based tool to characterize and diagnose datasets. We leverage a largely ignored source of information: the behavior of the model on individual instances during training (training dynamics) for building data maps. This yields two intuitive measures for each example---the model's confidence in the true class, and the variability of this confidence across epochs---obtained in a single run of training. Experiments across four datasets show that these model-dependent measures reveal three distinct regions in the data map, each with pronounced characteristics. First, our data maps show the presence of "ambiguous" regions with respect to the model, which contribute the most towards out-of-distribution generalization. Second, the most populous regions in the data are "easy to learn" for the model, and play an important role in model optimization. Finally, data maps uncover a region with instances that the model finds "hard to learn"; these often correspond to labeling errors. Our results indicate that a shift in focus from quantity to quality of data could lead to robust models and improved out-of-distribution generalization.
    
    * * *
    

NORMALIZATION / SCALING
=======================

1.  [A comparison of normalization / scaling techniques in sklearn](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/preprocessing/plot_all_scaling.html%23sphx-glr-auto-examples-preprocessing-plot-all-scaling-py&sa=D&source=editors&ust=1621930682157000&usg=AOvVaw0VODhlXvVb5oRfNIc8hE6X)
2.  [Another great explanation on sklearn and (general) scaling](https://www.google.com/url?q=http://benalexkeen.com/feature-scaling-with-scikit-learn/&sa=D&source=editors&ust=1621930682158000&usg=AOvVaw0qFyuLHifhVrpF0Wtsmsuk) \- normal, min max, etc..
3.  [Normalization\\standardize features](https://www.google.com/url?q=http://machinelearningmastery.com/normalize-standardize-machine-learning-data-weka/&sa=D&source=editors&ust=1621930682158000&usg=AOvVaw1fxaXoVSTnOxp87kuNPYJw)

* data has varying scales
* Normalize between range 0 to 1.

* When the algorithm you are using does not make assumptions about the distribution of your data, such as k-nearest neighbors and artificial neural networks.

* Standardize, mean of 0 and a std of 1:

* When the algorithm assumes a gaussian dist, such as linear regression, logistic regression and linear discriminant analysis. LR, LogR, LDA

**Generally, it is a good idea to standardize data that has a Gaussian (bell curve) distribution and normalize otherwise.

4\. In general terms, we should test 0,1 or -1,1 empirically and possibly match the range to the NN gates/activation function etc.

* * *

REGULARIZATION
==============

Youtube? [Watch this.](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DsO4ZirJh9ds&sa=D&source=editors&ust=1621930682160000&usg=AOvVaw2BP_GY95FcbVExbubPDUIS) Also explains about iso surfaces, lp norm, sparseness.

(what is?) [Regularization (in linear regression](https://www.google.com/url?q=https://datanice.github.io/machine-learning-101-what-is-regularization-interactive.html&sa=D&source=editors&ust=1621930682160000&usg=AOvVaw3f1FU6hCR7I3KMz5eyf2IR)) \- to find the best model we define a loss or cost function that describes how well the model fits the data, and try minimize it. For a complex model that fits even the noise, i.e., over fitted, we penalize it by adding a complexity term that would add BIGGER LOSS for more complex models.

* Bigger lambda -> high complexity models (deg 3) are ruled out, more punishment.
* Smaller lambda -> models with high training error are rules out. I.e.,  linear model on non linear data?, i.e., deg 1.
* Optimal is in between (deg 2)

[L1 - for sparse models,](https://www.google.com/url?q=https://stats.stackexchange.com/questions/45643/why-l1-norm-for-sparse-models&sa=D&source=editors&ust=1621930682161000&usg=AOvVaw173dtw7Ofy1KwgTOO17J9k)

[L1 vs L2, some formula](https://www.google.com/url?q=https://towardsdatascience.com/l1-and-l2-regularization-methods-ce25e7fc831c&sa=D&source=editors&ust=1621930682161000&usg=AOvVaw0RNd1Tvlci7CmaUgOIn8fe)

[Rehearsal on vector normalization](https://www.google.com/url?q=http://mathworld.wolfram.com/VectorNorm.html&sa=D&source=editors&ust=1621930682162000&usg=AOvVaw1cprtdtrtph1JjYfqkHVpq) \- for l1,l2,l3,l4 etc, what is the norm? (absolute value in certain cases)![](images/image202.png)

(Difference between? And features of) [L1 vs L2](https://www.google.com/url?q=http://www.chioka.in/differences-between-l1-and-l2-as-loss-function-and-regularization/&sa=D&source=editors&ust=1621930682162000&usg=AOvVaw3uXxIqk7n8jfOLbNn5IeKa) as loss function and regularization.

* L1 - moves the regressor faster, feature selection by sparsing coefficients (zeroing them), with sparse algorithms it is computationally efficient, with others no, so use L2.
* L2 - moves slower, doesn't sparse, computationally efficient.

Why does L1 lead to sparity?

* [Intuition](https://www.google.com/url?q=https://www.quora.com/Why-is-L1-regularization-supposed-to-lead-to-sparsity-than-L2&sa=D&source=editors&ust=1621930682163000&usg=AOvVaw35WtPpJDHj0Jw_Ag1_CQNF) \+ [some mathematical info](https://www.google.com/url?q=https://www.quora.com/What-is-the-difference-between-L1-and-L2-regularization&sa=D&source=editors&ust=1621930682163000&usg=AOvVaw32S_VsD3MVbi6bmvp44zxy)![](images/image254.png)
* L1 & L2 regularization add constraints to the optimization problem. The curve H0 is the hypothesis. The solution is a set of points where the H0 meets the constraints.
* In L2 the the hypothesis is tangential to the ||w||\_2. The point of intersection has both x1 and x2 components. On the other hand, in L1, due to the nature of ||w||\_1, the viable solutions are limited to the corners of the axis, i.e.,  x1. So that the value of x2 = 0. This means that the solution has eliminated the role of x2 leading to sparsity.
* This can be extended to a higher dimensions and you can see why L1 regularization leads to solutions to the optimization problem where many of the variables have value 0.  
* In other words, L1 regularization leads to sparsity.
* Also considered feature selection - although with LibSVM the recommendation is to feature select prior to using the SVM and use L2 instead.

[L1 sparsity - intuition #2](https://www.google.com/url?q=https://www.quora.com/What-is-the-difference-between-L1-and-L2-regularization&sa=D&source=editors&ust=1621930682164000&usg=AOvVaw3f37Ey2cf2tPrkWJlE9nL0)

* For simplicity, let's just consider the 1-dimensional case.
* L2:

* L2-regularized loss function F(x)=f(x)+λ∥x∥^2 is smooth.
* This means that the optimum is the stationary point (0-derivative point).
* The stationary point of F can get very small when you increase λ, but it will still won't be 0 unless f′(0)=0.

* L1:

* regularized loss function F(x)=f(x)+λ∥x∥ is non-smooth, i.e., a min knee of 0.
* It's not differentiable at 0.
* Optimization theory says that the optimum of a function is either the point with 0-derivative or one of the irregularities (corners, kinks, etc.). So, it's possible that the optimal point of F is 0 even if 0 isn't the stationary point of f.
* In fact, it would be 0 if λ is large enough (stronger regularization effect). Below is a graphical illustration.

![](images/image138.png)

In multi-dimensional settings: if a feature is not important, the loss contributed by it is small and hence the (non-differentiable) regularization effect would turn it off.

[Intuition + formulation, which is pretty good:](https://www.google.com/url?q=https://stats.stackexchange.com/questions/45643/why-l1-norm-for-sparse-models&sa=D&source=editors&ust=1621930682166000&usg=AOvVaw0TJ9koJ0FW0nvCK3jDXF4L)

![](images/image247.png)

([did not watch](https://www.google.com/url?q=https://www.coursera.org/learn/machine-learning/lecture/db3jS/model-representation&sa=D&source=editors&ust=1621930682167000&usg=AOvVaw2w-9Vva7fjZGdiDIrbM5a7)) but here is andrew ng talks about cost functions.

* * *

L2 regularization [equivalent to Gaussian prior](https://www.google.com/url?q=https://stats.stackexchange.com/questions/163388/l2-regularization-is-equivalent-to-gaussian-prior&sa=D&source=editors&ust=1621930682167000&usg=AOvVaw0A8QO7iO_adlHI5p-1zwKo)

![](images/image258.png)

L1 regularization [equivalent to a Laplacean Prior](https://www.google.com/url?q=https://stats.stackexchange.com/questions/163388/l2-regularization-is-equivalent-to-gaussian-prior&sa=D&source=editors&ust=1621930682168000&usg=AOvVaw3Etg0RGURn19sE8LB9AspT)(same link as above) - “Similarly the relationship between L1 norm and the Laplace prior can be undestood in the same fashion. Take instead of a Gaussian prior, a Laplace prior combine it with your likelihood and take the logarithm.“

[How does regularization look like in SVM](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/4943/intuition-for-the-regularization-parameter-in-svm&sa=D&source=editors&ust=1621930682168000&usg=AOvVaw3_-is8366Lg-et0LvR6I9N) \- controlling ‘C’

* * *

VALIDATION
==========

DATASETS RELIABILITY & CORRECTNESS
----------------------------------

1\. [Clever Hans effect](https://www.google.com/url?q=https://thegradient.pub/nlps-clever-hans-moment-has-arrived/?fbclid%3DIwAR3vSx9EjXcSPhXU3Jyf7aWpTqhbVDARnh3qGpSw0rysv9rLeGyZFFCPnJA&sa=D&source=editors&ust=1621930682169000&usg=AOvVaw0TMmN3yjMIKGIifNg_u06Y) \- in relations to cues left in the dataset that models find, instead of actually solving the defined task!

* Ablating, i.e. removing, part of a model and observing the impact this has on performance is a common method for verifying that the part in question is useful. If performance doesn't go down, then the part is useless and should be removed. Carrying this method over to datasets, it should become common practice to perform dataset ablations, as well, for example:

* Provide only incomplete input (as done in the reviewed paper): This verifies that the complete input is required. If not, the dataset contains cues that allow taking shortcuts.
* Shuffle the input: This verifies the importance of word (or sentence) order. If a bag-of-words/sentences gives similar results, even though the task requires sequential reasoning, then the model has not learned sequential reasoning and the dataset contains cues that allow the model to "solve" the task without it.
* Assign random labels: How much does performance drop if ten percent of instances are relabeled randomly? How much with all random labels? If scores don't change much, the model probably didn't learning anything interesting about the task.
* Randomly replace content words: How much does performance drop if all noun phrases and/or verb phrases are replaced with random noun phrases and verbs? If not much, the dataset may provide unintended non-content cues, such as sentence length or distribution of function words.

[2\. Paper](https://www.google.com/url?q=https://arxiv.org/abs/1908.05267?fbclid%3DIwAR1xOHxCF3gewyijMYAfZJSysu88Y8lgRIT2OiG-jWQav4zcbPqGYSoFFkk&sa=D&source=editors&ust=1621930682170000&usg=AOvVaw1ajtJn1JqVgRadfGTRuKHk)

UNIT / DATA TESTS
-----------------

1.  A great :P [unit test and logging](https://www.google.com/url?q=https://towardsdatascience.com/unit-testing-and-logging-for-data-science-d7fb8fd5d217?fbclid%3DIwAR3pze0DtV-2Q4L4ysPyjrInk7LB89mdiodxlEUTv4rv37ZoDzl_2I4ZbgA&sa=D&source=editors&ust=1621930682170000&usg=AOvVaw1_KbLHD66x2hwTwGvzn8AZ) post on medium - it’s actually mine :)
2.  A mind blowing [lecture](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D1fHGXOfiDO0%26feature%3Dyoutu.be%26fbclid%3DIwAR1bKByLgdYBDoBEr-e6Pw0Un5o0wvOg1yp4C-q4AoWZ1QuBEopTFFn0Gdw&sa=D&source=editors&ust=1621930682171000&usg=AOvVaw3eOQtRjWYqo15_osUibQSJ) about unit testing your data using Voluptuous & engrade & TDDA lecture
3.  [Great expectations](https://www.google.com/url?q=https://greatexpectations.io/&sa=D&source=editors&ust=1621930682171000&usg=AOvVaw2xWhnXt0JUcc0BOIgjzQdX), [article](https://www.google.com/url?q=https://github.blog/2020-10-01-keeping-your-data-pipelines-healthy-with-the-great-expectations-github-action/&sa=D&source=editors&ust=1621930682171000&usg=AOvVaw1DAnx7fXIlhba9OHgeGDGp), “TDDA” for Unit tests and CI
4.  [DataProfiler git](https://www.google.com/url?q=https://github.com/capitalone/DataProfiler&sa=D&source=editors&ust=1621930682172000&usg=AOvVaw20d-KFps7cI1Pm6VnegBBI)
5.  [Unit tests in python](https://www.google.com/url?q=https://jeffknupp.com/blog/2013/12/09/improve-your-python-understanding-unit-testing/&sa=D&source=editors&ust=1621930682172000&usg=AOvVaw2mPzqvFpWnv_-rLiG1o6pV)
6.  [Unit tests in python - youtube](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D6tNS--WetLI&sa=D&source=editors&ust=1621930682173000&usg=AOvVaw0JHbSUPQHPwSAQiiFXNyeA)
7.  [Unit tests asserts](https://www.google.com/url?q=https://docs.python.org/3/library/unittest.html%23unittest.TestCase.debug&sa=D&source=editors&ust=1621930682173000&usg=AOvVaw0-PGX07S4SUTh_yZkT5Yln)
8.  [Auger - automatic unit tests, has a blog post inside](https://www.google.com/url?q=https://github.com/laffra/auger&sa=D&source=editors&ust=1621930682173000&usg=AOvVaw0IpH3ilSNgCDcUAN5H4fMm), doesn't work with py 3+
9.  [A rather naive unit tests article aimed for DS](https://www.google.com/url?q=https://medium.com/@danielhen/unit-tests-for-data-science-the-main-use-cases-1928d9e7a4d4&sa=D&source=editors&ust=1621930682174000&usg=AOvVaw1pqdU7MFLD14a0mH0XEkiB)
10. A good pytest [tutorial](https://www.google.com/url?q=https://www.tutorialspoint.com/pytest/index.htm&sa=D&source=editors&ust=1621930682174000&usg=AOvVaw14Q9jrp1wAiPhLGblGs_kA)
11. [Mock](https://www.google.com/url?q=https://medium.com/@yasufumy/python-mock-basics-674c33de1ced&sa=D&source=editors&ust=1621930682174000&usg=AOvVaw0MqB53xRNj_2QnKDhL57Bj), [mock 2](https://www.google.com/url?q=https://medium.com/python-pandemonium/python-mocking-you-are-a-tricksy-beast-6c4a1f8d19b2&sa=D&source=editors&ust=1621930682175000&usg=AOvVaw3GmFnn1K7BhDr2r8OH2zdJ)
    
    * * *
    

REGULATION FOR AI
-----------------

1.  [Preparing for EU regulations](https://www.google.com/url?q=https://towardsdatascience.com/how-ai-leaders-should-prepare-for-the-looming-eu-regulations-99e9d4f4c039&sa=D&source=editors&ust=1621930682175000&usg=AOvVaw2SbjQh4YtUBltHfKa6aQhF) by MonaLabs
2.  [EU regulation DOC](https://www.google.com/url?q=https://drive.google.com/file/d/1ZaBPsfor_aHKNeeyXxk9uJfTru747EOn/view&sa=D&source=editors&ust=1621930682176000&usg=AOvVaw3e_clwNxgdtoLqRfwtkPhG)

FAIRNESS, ACCOUNTABILITY & TRANSPARENCY ML
------------------------------------------

1.  FATML [website](https://www.google.com/url?q=https://www.fatml.org/&sa=D&source=editors&ust=1621930682176000&usg=AOvVaw0RCwGOPd6agq7dt-FM_5Cr) \- The past few years have seen growing recognition that machine learning raises novel challenges for ensuring non-discrimination, due process, and understandability in decision-making. In particular, policymakers, regulators, and advocates have expressed fears about the potentially discriminatory impact of machine learning, with many calling for further technical research into the dangers of inadvertently encoding bias into automated decisions.

At the same time, there is increasing alarm that the complexity of machine learning may reduce the justification for consequential decisions to “the algorithm made me do it.”

1.  [Principles and best practices](https://www.google.com/url?q=https://www.fatml.org/resources/principles-and-best-practices&sa=D&source=editors&ust=1621930682177000&usg=AOvVaw1LvaHwunsxQDGrnb-MggMC), [projects](https://www.google.com/url?q=https://www.fatml.org/resources/relevant-projects&sa=D&source=editors&ust=1621930682177000&usg=AOvVaw3QtTe78bUgkqLZsBiBnbYv)

2.  [FAccT](https://www.google.com/url?q=https://facctconference.org/&sa=D&source=editors&ust=1621930682177000&usg=AOvVaw2TIMlDYU9c-U9XShZuO6xK) \- A computer science conference with a cross-disciplinary focus that brings together researchers and practitioners interested in fairness, accountability, and transparency in socio-technical systems.
3.  [Paper - there is no fairness, enforcing fairness can improve accuracy](https://www.google.com/url?q=https://openreview.net/forum?id%3DwXoHN-Zoel%26fbclid%3DIwAR1MZArpfpu8L8ildamF0ngnUbKgD8-9NFBCXVo0JKwS6yP9g-2BJmWUv68&sa=D&source=editors&ust=1621930682178000&usg=AOvVaw2xIMqsXnXLid5A_Bc2lTNX)
4.  [Google on responsible ai practices](https://www.google.com/url?q=https://ai.google/responsibilities/responsible-ai-practices/&sa=D&source=editors&ust=1621930682178000&usg=AOvVaw36Wq3TuG8_7ccMtCXucgjj) see also PAIR
5.  [Ethics and regulation in israel](https://www.google.com/url?q=https://machinelearning.co.il/4330/israelaiethicsreport/%23more-4330&sa=D&source=editors&ust=1621930682178000&usg=AOvVaw3WbHCAr64IiERv3EdR8RbQ), [lecture](https://www.google.com/url?q=https://machinelearning.co.il/3349/googleai/&sa=D&source=editors&ust=1621930682179000&usg=AOvVaw2qUmI7c4nxEycMSq9dC4ba)
6.  [Bengio on ai](https://www.google.com/url?q=https://www.wired.com/story/ai-pioneer-algorithms-understand-why/?fbclid%3DIwAR03uWEmVSjrOmP4dp77v_mdjPAXOsKPams_xsUOKameKbuzY8JN4brGC9o&sa=D&source=editors&ust=1621930682179000&usg=AOvVaw0mLlH-2m2pnomnMGr1P_xG)
7.  [Poisoning attacks on fairness](https://www.google.com/url?q=https://arxiv.org/pdf/2004.07401.pdf&sa=D&source=editors&ust=1621930682179000&usg=AOvVaw1ccs9Va7HhODzxXDAC6bt6) \- Research in adversarial machine learning has shown how the performance of machine learning models can be seriously compromised by injecting even a small fraction of poisoning points into the training data. We empirically show that our attack is effective not only in the white-box setting, in which the attacker has full access to the target model, but also in a more challenging black-box scenario in which the attacks are optimized against a substitute model and then transferred to the target model

* * *

### FAIRNESS TOOLS

1.  [PII tools, by gensim](https://www.google.com/url?q=https://pii-tools.com/&sa=D&source=editors&ust=1621930682180000&usg=AOvVaw2CWjVH5xktZ9oESBe-28Dn)
2.  [Fair-learn](https://www.google.com/url?q=https://github.com/fairlearn/fairlearn&sa=D&source=editors&ust=1621930682180000&usg=AOvVaw0l02gdGYeW7uUhx84xZR4E) A Python package to assess and improve fairness of machine learning models.  
    ![](images/image58.png)
3.  [Sk-lego](https://www.google.com/url?q=https://scikit-lego.readthedocs.io/en/latest/fairness.html&sa=D&source=editors&ust=1621930682181000&usg=AOvVaw1YUXKas49mQjXP_f7L_njx)

![](images/image256.png)

1.  Regression  
    ![](images/image35.png)
2.  classification![](images/image241.png)
3.  ![](images/image34.png)
4.  ![](images/image34.png)
5.  ![](images/image23.png)
6.  information filter  
    ![](images/image264.png)

M. Zafar et al. (2017), Fairness Constraints: Mechanisms for Fair Classification

M. Hardt, E. Price and N. Srebro (2016), Equality of Opportunity in Supervised Learning

* * *

INTERPRETABLE / EXPLAINABLE AI (XAI)
------------------------------------

![](images/image240.png)

1.  [A curated document about XAI research resources.](https://www.google.com/url?q=https://docs.google.com/spreadsheets/d/1uQy6a3BfxOXI8Nh3ECH0bqqSc95zpy4eIp_9JAMBkKg/edit?usp%3Dsharing&sa=D&source=editors&ust=1621930682182000&usg=AOvVaw2mMvVyvYuLxJttjHG-afXf)
2.  From the above image: [Paper: Principles and practice of explainable models](https://www.google.com/url?q=https://arxiv.org/abs/2009.11698&sa=D&source=editors&ust=1621930682183000&usg=AOvVaw27YLUrIpThJiuYf4duiGwp) \- a really good review for everything XAI - “a survey to help industry practitioners (but also data scientists more broadly) understand the field of explainable machine learning better and apply the right tools. Our latter sections build a narrative around a putative data scientist, and discuss how she might go about explaining her models by asking the right questions. From an organization viewpoint, after motivating the area broadly, we discuss the main developments, including the principles that allow us to study transparent models vs opaque models, as well as model-specific or model-agnostic post-hoc explainability approaches. We also briefly reflect on deep learning models, and conclude with a discussion about future research directions.”
3.  [Book: interpretable machine learning](https://www.google.com/url?q=https://christophm.github.io/interpretable-ml-book/agnostic.html&sa=D&source=editors&ust=1621930682183000&usg=AOvVaw2sDpHVlbAtMiLH3txrSvXy), [christoph mulner](https://www.google.com/url?q=https://christophm.github.io/&sa=D&source=editors&ust=1621930682184000&usg=AOvVaw05n0ATj0GAO2C-ScvhMIZB)
4.  (great) [Interpretability overview,](https://www.google.com/url?q=https://thegradient.pub/interpretability-in-ml-a-broad-overview/?fbclid%3DIwAR2ltYQWbS5jixIJzAnFg8dz1A-9y9eGIMxQfpB_Pp5x9knP1Y4JhQg3xgI&sa=D&source=editors&ust=1621930682184000&usg=AOvVaw2ejcWFb4Wf6-JqtEMJp6s6) transparent (simultability, decomposability, algorithmic transparency) post-hoc interpretability (text explanation, visual local, explanation by example,), evaluation, utility.
5.  [Medium: the great debate](https://www.google.com/url?q=https://medium.com/swlh/the-great-ai-debate-interpretability-1d139167b55&sa=D&source=editors&ust=1621930682184000&usg=AOvVaw3Pp1TM5pWub93oamPgRBRm)

![](images/image174.png)

6.  [Paper: pitfalls to avoid when interpreting ML models](https://www.google.com/url?q=https://arxiv.org/abs/2007.04131&sa=D&source=editors&ust=1621930682185000&usg=AOvVaw12FMYwdFTdllsfnSC--KOb) “y. A growing number of techniques provide model interpretations, but can lead to wrong conclusions if applied incorrectly. We illustrate pitfalls of ML model interpretation such as bad model generalization, dependent features, feature interactions or unjustified causal interpretations. Our paper addresses ML practitioners by raising awareness of pitfalls and pointing out solutions for correct model interpretation, as well as ML researchers by discussing open issues for further research.” - mulner et al.

![](images/image196.png)

7.  **\* [whitening a black box.](https://www.google.com/url?q=https://francescopochetti.com/whitening-a-black-box-how-to-interpret-a-ml-model/&sa=D&source=editors&ust=1621930682185000&usg=AOvVaw1vDKqjM8ABqjdAQsExukYC)This is very good, includes eli5, lime, shap, many others.
8.  Book: [exploratory model analysis](https://www.google.com/url?q=https://pbiecek.github.io/ema/&sa=D&source=editors&ust=1621930682186000&usg=AOvVaw2ewtfBCeLe1X0D6D0pqkZ_)
9.  [Alibi-explain](https://www.google.com/url?q=https://github.com/SeldonIO/alibi&sa=D&source=editors&ust=1621930682186000&usg=AOvVaw0KbZeMUIo11rvSL5eFHZpf)\- White-box and black-box ML model explanation library. [Alibi](https://www.google.com/url?q=https://docs.seldon.io/projects/alibi&sa=D&source=editors&ust=1621930682186000&usg=AOvVaw3pc-8fXa3fSR9SPMTcstLk) is an open source Python library aimed at machine learning model inspection and interpretation. The focus of the library is to provide high-quality implementations of black-box, white-box, local and global explanation methods for classification and regression models.

![](images/image51.png)

10. [Hands on explainable ai](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D1mNhPoab9JI%26fbclid%3DIwAR1cV__3zBClI-mq3XpJfgn691xB7EM5gdZpejJ86wnrsVoiGmQFY9P5Uho&sa=D&source=editors&ust=1621930682187000&usg=AOvVaw15O6mTZ9VKToI8rcmIjGbX)youtube, [git](https://www.google.com/url?q=https://github.com/PacktPublishing/Hands-On-Explainable-AI-XAI-with-Python?fbclid%3DIwAR012IQFa4ce3camoD13iIRyCfQlWPi3HwQs8VDjIGgFnGdcm3xkq7zir-U&sa=D&source=editors&ust=1621930682187000&usg=AOvVaw05mwmAgPqBIy0CUUpp6x9l)
11. [Explainable methods](https://www.google.com/url?q=https://towardsdatascience.com/interpretable-machine-learning-with-xgboost-9ec80d148d27&sa=D&source=editors&ust=1621930682188000&usg=AOvVaw1Zrty-Cp2_FMlYG6D1SbSU) are not always consistent and do not agree with each other, this article has a make-sense explanation and flow for using shap and its many plots.

![](images/image207.png)

12. Intro to shap and lime, [part 1](https://www.google.com/url?q=https://blog.dominodatalab.com/shap-lime-python-libraries-part-1-great-explainers-pros-cons/&sa=D&source=editors&ust=1621930682188000&usg=AOvVaw38JSnLRkKxqBeopTm2GlQc), [part 2](https://www.google.com/url?q=https://blog.dominodatalab.com/shap-lime-python-libraries-part-2-using-shap-lime/&sa=D&source=editors&ust=1621930682188000&usg=AOvVaw1qTl8tM080HXtY6nYaEtzm)
13. Lime

1.  [\*\*\* how lime works behind the scenes](https://www.google.com/url?q=https://medium.com/analytics-vidhya/explain-your-model-with-lime-5a1a5867b423&sa=D&source=editors&ust=1621930682189000&usg=AOvVaw3If3tOLhaqPNkc45CZQiKC)
2.  [LIME to interpret models](https://www.google.com/url?q=https://www.oreilly.com/learning/introduction-to-local-interpretable-model-agnostic-explanations-lime&sa=D&source=editors&ust=1621930682189000&usg=AOvVaw3OGmgjQwPEQclYnD_eCEOz)NLP and IMAGE, [github](https://www.google.com/url?q=https://github.com/marcotcr/lime&sa=D&source=editors&ust=1621930682190000&usg=AOvVaw2DphyAKGq0eR0TRTjnAldb)\- In the experiments in [our research paper](https://www.google.com/url?q=http://arxiv.org/abs/1602.04938&sa=D&source=editors&ust=1621930682190000&usg=AOvVaw1Fj9T6PeNNYaKKmjB6IqGA), we demonstrate that both machine learning experts and lay users greatly benefit from explanations similar to Figures 5 and 6 and are able to choose which models generalize better, improve models by changing them, and get crucial insights into the models' behavior.

14. Anchor

1.  [Anchor from the authors of Lime,](https://www.google.com/url?q=https://github.com/marcotcr/anchor&sa=D&source=editors&ust=1621930682190000&usg=AOvVaw0_GQz9SByX-zlctEG2Pzn0) \- An anchor explanation is a rule that sufficiently “anchors” the prediction locally – such that changes to the rest of the feature values of the instance do not matter. In other words, for instances on which the anchor holds, the prediction is (almost) always the same.

15. Shap:

1.  Medium [Intro to lime and shap](https://www.google.com/url?q=https://towardsdatascience.com/explain-nlp-models-with-lime-shap-5c5a9f84d59b&sa=D&source=editors&ust=1621930682191000&usg=AOvVaw3QMD_ptAFsSjcLmoG_6LBL)
2.  \*\*\*\* In depth [SHAP](https://www.google.com/url?q=https://towardsdatascience.com/introducing-shap-decision-plots-52ed3b4a1cba&sa=D&source=editors&ust=1621930682191000&usg=AOvVaw1AwCJExkfSXXVcI8nd5WpN)
3.  [Github](https://www.google.com/url?q=https://github.com/slundberg/shap&sa=D&source=editors&ust=1621930682192000&usg=AOvVaw0iBl0tTjMxM_0a_Z0eWWy1)
4.  [Country happiness using shap](https://www.google.com/url?q=https://sararobinson.dev/2019/03/24/preventing-bias-machine-learning.html&sa=D&source=editors&ust=1621930682192000&usg=AOvVaw0xNqfLey_XX9DzVydKgnvV)
5.  [Stackoverflow example, predicting tags, pandas keras etc](https://www.google.com/url?q=https://stackoverflow.blog/2019/05/06/predicting-stack-overflow-tags-with-googles-cloud-ai/&sa=D&source=editors&ust=1621930682192000&usg=AOvVaw2zCpw5n39YQvY426y9HgeU)
6.  [Intro to shapely and shap](https://www.google.com/url?q=https://towardsdatascience.com/a-new-perspective-on-shapley-values-an-intro-to-shapley-and-shap-6f1c70161e8d?&sa=D&source=editors&ust=1621930682193000&usg=AOvVaw2a3BtDZHirECoIWQP9-xEu)
7.  [Fiddler on shap](https://www.google.com/url?q=https://medium.com/fiddlerlabs/case-study-explaining-credit-modeling-predictions-with-shap-2a7b3f86ec12&sa=D&source=editors&ust=1621930682193000&usg=AOvVaw2P1JGUl5fvq2ciSQAJNAsr)
8.  [Shapash - a web app for Lime and shap.](https://www.google.com/url?q=https://github.com/MAIF/shapash&sa=D&source=editors&ust=1621930682194000&usg=AOvVaw03ImNvFW4Wk8LfONUInxck)

16. SHAP advanced

1.  [Official shap tutorial on their plots, you can never read this too many times.](https://www.google.com/url?q=https://slundberg.github.io/shap/notebooks/plots/decision_plot.html&sa=D&source=editors&ust=1621930682194000&usg=AOvVaw1gyT4YlFeW6MqAv8pQNWEh)
2.  [What are shap values on kaggle](https://www.google.com/url?q=https://www.kaggle.com/dansbecker/shap-values&sa=D&source=editors&ust=1621930682195000&usg=AOvVaw0EMXsTN4HIIQKT7md-NBxu) \- whatever you do start with this
3.  [Shap values on kaggle #2](https://www.google.com/url?q=https://www.kaggle.com/dansbecker/advanced-uses-of-shap-values&sa=D&source=editors&ust=1621930682195000&usg=AOvVaw2oZeIPYyqudgbZY1Cc5JyH) \- continue with this
4.  How to calculate Shap values per class based on this graph

![](images/image167.png)

5.  Shap [intro](https://www.google.com/url?q=https://towardsdatascience.com/explain-your-model-with-the-shap-values-bc36aac4de3d&sa=D&source=editors&ust=1621930682195000&usg=AOvVaw1s__srk4fgxdgUhaFFLqI1), [part 2](https://www.google.com/url?q=https://towardsdatascience.com/explain-any-models-with-the-shap-values-use-the-kernelexplainer-79de9464897a&sa=D&source=editors&ust=1621930682196000&usg=AOvVaw3hE-H6oK3R35G_PSah0wgl) with many algo examples and an explanation about the four plots.

17. [A thorough post about the many ways of explaining a model, from regression, to bayes, to trees, forests, lime, beta, feature selection/elimination](https://www.google.com/url?q=https://lilianweng.github.io/lil-log/2017/08/01/how-to-explain-the-prediction-of-a-machine-learning-model.html%23interpretable-models&sa=D&source=editors&ust=1621930682196000&usg=AOvVaw3C_EzUFyM3RJ8pub-nJLtE)
18. [Trusting models](https://www.google.com/url?q=https://arxiv.org/pdf/1602.04938.pdf&sa=D&source=editors&ust=1621930682197000&usg=AOvVaw2qJHdfbbnWXZlVzBrTD6nQ)
19. [3\. Interpret using uncertainty](https://www.google.com/url?q=https://becominghuman.ai/using-uncertainty-to-interpret-your-model-67a97c28fea5&sa=D&source=editors&ust=1621930682197000&usg=AOvVaw1wM8HmY0j69QHzq1uUPwXM)
20. [Keras-vis](https://www.google.com/url?q=https://github.com/raghakot/keras-vis&sa=D&source=editors&ust=1621930682197000&usg=AOvVaw3LVDzsjoKe-NgQEIOg2Wdw) for cnns, 3 methods, activation maximization, saliency and class activation maps
21. [The notebook!](https://www.google.com/url?q=https://github.com/FraPochetti/KagglePlaygrounds/blob/master/InterpretableML.ipynb&sa=D&source=editors&ust=1621930682198000&usg=AOvVaw3UdHpsde-zHFSpALfKWaPW)[Blog](https://www.google.com/url?q=https://francescopochetti.com/whitening-a-black-box-how-to-interpret-a-ml-model/&sa=D&source=editors&ust=1621930682198000&usg=AOvVaw1uNQqt8pyX44kgt_r669WW)
22. [More resources!](https://www.google.com/url?q=https://docs.google.com/spreadsheets/d/1uQy6a3BfxOXI8Nh3ECH0bqqSc95zpy4eIp_9JAMBkKg/edit%23gid%3D0&sa=D&source=editors&ust=1621930682198000&usg=AOvVaw3G9rOnp28thZbAFlGilutU)
23. [Visualizing the impact of feature attribution baseline](https://www.google.com/url?q=https://distill.pub/2020/attribution-baselines/&sa=D&source=editors&ust=1621930682199000&usg=AOvVaw0eSh6Q2csu80TzpDgK2Tfi)\- Path attribution methods are a gradient-based way of explaining deep models. These methods require choosing a hyperparameter known as the baseline input. What does this hyperparameter mean, and how important is it? In this article, we investigate these questions using image classification networks as a case study. We discuss several different ways to choose a baseline input and the assumptions that are implicit in each baseline. Although we focus here on path attribution methods, our discussion of baselines is closely connected with the concept of missingness in the feature space - a concept that is critical to interpretability research.
24. WHAT IF TOOL - GOOGLE, [notebook](https://www.google.com/url?q=https://colab.research.google.com/github/PAIR-code/what-if-tool/blob/master/WIT_Smile_Detector.ipynb&sa=D&source=editors&ust=1621930682199000&usg=AOvVaw0WWfy1i_3-azWQskIHeRdZ), [walkthrough](https://www.google.com/url?q=https://pair-code.github.io/what-if-tool/learn/tutorials/walkthrough/&sa=D&source=editors&ust=1621930682200000&usg=AOvVaw1LhYcQbGdS_Jh2mVcJCePs)
25. [Language interpretability tool (LIT) -](https://www.google.com/url?q=https://pair-code.github.io/lit/&sa=D&source=editors&ust=1621930682200000&usg=AOvVaw3VIvJHMgfnPDRyI9Eb7rIW) The Language Interpretability Tool (LIT) is an open-source platform for visualization and understanding of NLP models.
26. [Stop Explaining Black Box Machine Learning Models for High Stakes Decisions and Use Interpretable Models Instead](https://www.google.com/url?q=https://arxiv.org/abs/1811.10154&sa=D&source=editors&ust=1621930682200000&usg=AOvVaw1UQdMz4feFbWehQgyyu5Fo) \- “trying to \\textit{explain} black box models, rather than creating models that are \\textit{interpretable} in the first place, is likely to perpetuate bad practices and can potentially cause catastrophic harm to society. There is a way forward -- it is to design models that are inherently interpretable. This manuscript clarifies the chasm between explaining black boxes and using inherently interpretable models, outlines several key reasons why explainable black boxes should be avoided in high-stakes decisions, identifies challenges to interpretable machine learning, and provides several example applications where interpretable models could potentially replace black box models in criminal justice, healthcare, and computer vision.”
27. [Using genetic algorithms](https://www.google.com/url?q=https://towardsdatascience.com/interpreting-black-box-machine-learning-models-with-genetic-algorithms-a803bfd134cb&sa=D&source=editors&ust=1621930682201000&usg=AOvVaw01NxKdBX1dNi8seR5xTWDu)
28. [Google’s what-if tool](https://www.google.com/url?q=https://pair-code.github.io/what-if-tool/demos/image.html&sa=D&source=editors&ust=1621930682201000&usg=AOvVaw2LlVFLUAwHpwXX5OvkSl0A)from [PAIR](https://www.google.com/url?q=https://pair.withgoogle.com/&sa=D&source=editors&ust=1621930682202000&usg=AOvVaw3DU1QFaVGGR2cO9hgewDsR)

WHY WE SHOULDN’T TRUST MODELS
-----------------------------

1.  [Clever Hans effect for NLP](https://www.google.com/url?q=https://thegradient.pub/nlps-clever-hans-moment-has-arrived/&sa=D&source=editors&ust=1621930682202000&usg=AOvVaw2XNxLnVXedwFJF87LpBSzc)

1.  Datasets need more love
2.  Datasets ablation and public beta
3.  Inter-prediction agreement

2.  Behavioral testing and CHECKLIST

1.  [Blog](https://www.google.com/url?q=https://amitness.com/2020/07/checklist/&sa=D&source=editors&ust=1621930682203000&usg=AOvVaw03x3f1h1HSSu53fkg3tRjH), [Youtube](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DL3gaWctPg6E&sa=D&source=editors&ust=1621930682203000&usg=AOvVaw1dbDBtujdBDJwdvopz2TsD), [paper](https://www.google.com/url?q=https://arxiv.org/pdf/2005.04118.pdf&sa=D&source=editors&ust=1621930682204000&usg=AOvVaw3qgmxEWTyVbWxjltAHkhrb), [git](https://www.google.com/url?q=https://github.com/marcotcr/checklist&sa=D&source=editors&ust=1621930682204000&usg=AOvVaw0lFLeWQEkPuUWloyA3sWvj)
2.  [Yonatan hadar on the subject in hebrew](https://www.google.com/url?q=https://www.facebook.com/groups/MDLI1/permalink/1627671704063538/&sa=D&source=editors&ust=1621930682204000&usg=AOvVaw3BIZ1DLJWR9g-MehoqMJuH)

DEBIASING MODELS
----------------

1.  [Adversarial removal of demographic features](https://www.google.com/url?q=https://arxiv.org/abs/1808.06640&sa=D&source=editors&ust=1621930682205000&usg=AOvVaw1hL0aQONmlu5zd8uzv1KL6) \- “We show that demographic information of authors is encoded in -- and can be recovered from -- the intermediate representations learned by text-based neural classifiers. The implication is that decisions of classifiers trained on textual data are not agnostic to -- and likely condition on -- demographic attributes. “  
    “we explore several techniques to improve the effectiveness of the adversarial component. Our main conclusion is a cautionary one: do not rely on the adversarial training to achieve invariant representation to sensitive features.”  
    
2.  [Null It Out: Guarding Protected Attributes by Iterative Nullspace Projection](https://www.google.com/url?q=https://arxiv.org/abs/2004.07667&sa=D&source=editors&ust=1621930682205000&usg=AOvVaw3C4QLxXVA0wDoOCtAJLVSj)(paper) , [github](https://www.google.com/url?q=https://github.com/shauli-ravfogel/nullspace_projection&sa=D&source=editors&ust=1621930682205000&usg=AOvVaw15LnVGy5UNzQIej4SuRCmT), [presentation](https://www.google.com/url?q=https://docs.google.com/presentation/d/1Xi5HLpvvRE8BqcNBZMyPS4gBa0i0lqZvRebz-AZxAPA/edit&sa=D&source=editors&ust=1621930682206000&usg=AOvVaw0RMBMbcRXKLatdy4zGJK26) by Shauli et al. - removing biased information such as gender from an embedding space using nullspace projection.  
    The objective is this: give a representation of text, for example BERT embeddings of many resumes/CVs, we want to achieve a state where a certain quality, for example a gender representation of the person who wrote this resume is not encoded in X. they used the light version definition for “not encoded”, i.e., you cant predict the quality from the representation with a higher than random score, using a linear model. I.e., every linear model you will train, will not be able to predict the person’s gender out of the embedding space and will reach a 50% accuracy.  
    This is done by an iterative process that includes. 1. Linear model training to predict the quality of the concept from the representation. 2. Performing ‘projection to null space’ for the linear classifier, this is an acceptable linear algebra calculation that has a meaning of zeroing the representation from the projection on the separation place that the linear model is representing, making the model useless. I.e., it will always predict the zero vector. This is done iteratively on the neutralized output, i.e., in the second iteration we look for an alternative way to predict the gender out of X, until we reach 50% accuracy (or some other metric you want to measure) at this point we have neutralized all the linear directions in the embedding space, that were predictive to the gender of the author.

For a matrix W, the null space is a sub-space of all X such that WX=0, i.e., W maps X to the zero vector, this is a linear projection of the zero vector into a subspace. For example you can take a 3d vectors and calculate its projection on XY.

3.  Can we extinct predictive samples? Its an open question, Maybe we can use influence functions?

[Understanding Black-box Predictions via Influence Functions](https://www.google.com/url?q=https://arxiv.org/pdf/1703.04730.pdf&sa=D&source=editors&ust=1621930682206000&usg=AOvVaw3XEBa5BuEq_u4SIm-bvfoX) \- How can we explain the predictions of a blackbox model? In this paper, we use influence functions — a classic technique from robust statistics — to trace a model’s prediction through the learning algorithm and back to its training data, thereby identifying training points most responsible for a given prediction.

We show that even on non-convex and non-differentiable models where the theory breaks down, approximations to influence functions can still provide valuable information. On linear models and convolutional neural networks, we demonstrate that influence functions are useful for multiple purposes: understanding model behavior, debugging models, detecting dataset errors, and even creating visually indistinguishable training-set attacks.

4.  [Removing ‘gender bias using pair mean pca](https://www.google.com/url?q=https://stackoverflow.com/questions/48019843/pca-on-word2vec-embeddings&sa=D&source=editors&ust=1621930682207000&usg=AOvVaw2100Thn7Erf_b9on4SYoqg)
5.  [Bias detector by intuit](https://www.google.com/url?q=https://github.com/intuit/bias-detector&sa=D&source=editors&ust=1621930682207000&usg=AOvVaw2XsuI1P2L__VPsJq8-3OtV) \- Based on first and last name/zip code the package analyzes the probability of the user belonging to different genders/races. Then, the model predictions per gender/race are compared using various bias metrics.

* * *

PRIVACY
-------

1.  [Privacy in DataScience](https://www.google.com/url?q=http://www.unsupervised-podcast.xyz/ab55d406&sa=D&source=editors&ust=1621930682208000&usg=AOvVaw1r7oa6IV26_NtKMJo85Eyw) podcast
2.  [Fairness in AI](https://www.google.com/url?q=http://www.unsupervised-podcast.xyz/5d7fc118&sa=D&source=editors&ust=1621930682208000&usg=AOvVaw2etRUpiPs6tMh2sTeZqlHy)

DIFFERENTIAL PRIVACY
--------------------

1.  [Differential privacy](https://www.google.com/url?q=https://georgianpartners.com/what-is-differential-privacy/&sa=D&source=editors&ust=1621930682209000&usg=AOvVaw0Kks0YWWM7HwcKgfx2lE12) has emerged as a major area of research in the effort to prevent the identification of individuals and private data. It is a mathematical definition for the privacy loss that results to individuals when their private information is used to create AI products. It works by injecting noise into a dataset, during a machine learning training process, or into the output of a machine learning model, without introducing significant adverse effects on data analysis or model performance. It achieves this by calibrating the noise level to the sensitivity of the algorithm. The result is a differentially private dataset or model that cannot be reverse engineered by an attacker, while still providing useful information. Uses BOTLON & EPSILON
2.  [youtube](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DgI0wk1CXlsQ%26feature%3Demb_title&sa=D&source=editors&ust=1621930682210000&usg=AOvVaw3X_RvIiEDhVrjSvcN22V71)

ANONYMIZATION
-------------

1.  [Using NER (omri mendels)](https://www.google.com/url?q=https://towardsdatascience.com/nlp-approaches-to-data-anonymization-1fb5bde6b929&sa=D&source=editors&ust=1621930682210000&usg=AOvVaw2Jd6jm_PZfG5nr1AKGIQkf)

DE-ANONYMIZATION
----------------

1.  GPT2 - [Of language datasets](https://www.google.com/url?q=https://arxiv.org/pdf/2012.07805.pdf&sa=D&source=editors&ust=1621930682211000&usg=AOvVaw1y62wu4pm5A61iY3wVvqsE)  
    ![](images/image226.png)

* * *

META-LEARNING
=============

[What is?](https://www.google.com/url?q=https://www.automl.org/&sa=D&source=editors&ust=1621930682212000&usg=AOvVaw1YXuJ9OTA3Nb986zNzI0n6)Automated Machine Learning provides methods and processes to make Machine Learning available for non-Machine Learning experts, to improve efficiency of Machine Learning and to accelerate research on Machine Learning.

Personal note: automl algorithms in this field will bridge the gap and automate several key processes, but it will not allow a practitioner to do serious research or solve business or product problems easily. The importance of this field is to advance each subfield, whether HPO, NAS, etc. these selective novelties can help us solve specific issues, i.e, lets take HPO, we can use it to save time and money on redundant parameter searches, especially when it comes to resource heavy algorithms such as Deep learning (think GPU costs).

Personal thoughts on optimizations: be advised that optimizing problems will not guarantee a good result, you may over fit your problem in ways you are not aware of, beyond traditional overfitting and better accuracy doesn't guarantee a better result (for example if your dataset is unbalanced, needs imputing, cleaning, etc.).    

Always examine the data and results in order to see if they are correct.

[Automl.org’s github - it has a backup for the following projects.](https://www.google.com/url?q=https://github.com/automl&sa=D&source=editors&ust=1621930682213000&usg=AOvVaw07Bg41gYpJtSoPjvp04Gio)

[Automl.org](https://www.google.com/url?q=https://www.automl.org/&sa=D&source=editors&ust=1621930682213000&usg=AOvVaw2k_IDpvpoNx9MI4KSQoE5C) is a joint effort between two universitie, freiburg and hannover, their website curates information regarding:

1.  HPO - hyper parameter optimization
2.  NAS - neural architecture search
3.  Meta Learning - learning across datasets, warmstarting of HPO and NAS etc.

Automl aims to automate these processes:

* Preprocess and clean the data.
* Select and construct appropriate features.
* Select an appropriate model family.
* Optimize model hyperparameters.
* Postprocess machine learning models.
* Critically analyze the results obtained.

Historically, AFAIK AutoML’s birth started with several methods to optimize each one of the previous processes in ml. IINM, [weka’s paper (2012](https://www.google.com/url?q=https://arxiv.org/abs/1208.3719&sa=D&source=editors&ust=1621930682214000&usg=AOvVaw1nuF52P1wPOUeNrVwLxq-l)) was the first step in aggregating these ideas into a first public working solution.

The following is referenced from AutoML.org:

ML Systems
----------

* [AutoWEKA](https://www.google.com/url?q=http://www.cs.ubc.ca/labs/beta/Projects/autoweka/&sa=D&source=editors&ust=1621930682215000&usg=AOvVaw0PhZ-MSAmpVlUWVf3ySgVu)is an approach for the simultaneous selection of a machine learning algorithm and its hyperparameters; combined with the [WEKA](https://www.google.com/url?q=http://www.cs.waikato.ac.nz/ml/weka/&sa=D&source=editors&ust=1621930682215000&usg=AOvVaw2Zw4mtDM87s0JDUZLK8QY1) package it automatically yields good models for a wide variety of data sets.
* [Auto-sklearn](https://www.google.com/url?q=http://automl.github.io/auto-sklearn/stable/&sa=D&source=editors&ust=1621930682216000&usg=AOvVaw2RHTdwAxqCvAvhm_o4vimR)is an extension of AutoWEKA using the Python library [scikit-learn](https://www.google.com/url?q=http://scikit-learn.org/stable/&sa=D&source=editors&ust=1621930682216000&usg=AOvVaw1NNfYa9ya2EelMIykbJw0Z) which is a drop-in replacement for regular scikit-learn classifiers and regressors.
* [TPOT](https://www.google.com/url?q=http://epistasislab.github.io/tpot/&sa=D&source=editors&ust=1621930682216000&usg=AOvVaw3enom_KkR5pZT19K2ZFBuH) is a data-science assistant which optimizes machine learning pipelines using genetic programming.
* (google) [H2O AutoML](https://www.google.com/url?q=http://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html&sa=D&source=editors&ust=1621930682217000&usg=AOvVaw3SUuxkXccs5V9AGWKd_4j9)provides automated model selection and ensembling for the [H2O machine learning and data analytics platform](https://www.google.com/url?q=http://docs.h2o.ai/h2o/latest-stable/h2o-docs/welcome.html&sa=D&source=editors&ust=1621930682217000&usg=AOvVaw1w9sc5HlKO7arhjRYmj5Ox). ([git](https://www.google.com/url?q=https://github.com/google/automl&sa=D&source=editors&ust=1621930682218000&usg=AOvVaw0XxO-PEW6P1FJxwTm27rGt))
* [TransmogrifAI](https://www.google.com/url?q=https://github.com/salesforce/TransmogrifAI&sa=D&source=editors&ust=1621930682219000&usg=AOvVaw28mHXssO5WIz1E0vxCL_Vj) is an AutoML library running on top of Spark.
* [MLBoX](https://www.google.com/url?q=https://github.com/AxeldeRomblay/MLBox&sa=D&source=editors&ust=1621930682219000&usg=AOvVaw2Psuc62XgVajvWs7HNteLq) is an AutoML  library with three components: preprocessing, optimisation and prediction.

Hyper param optimization
------------------------

* [Hyperopt](https://www.google.com/url?q=http://jaberg.github.io/hyperopt/&sa=D&source=editors&ust=1621930682220000&usg=AOvVaw3lPOSoD2-fEI7I-4y308so), including the TPE algorithm
* [Sequential Model-based Algorithm Configuration (SMAC)](https://www.google.com/url?q=http://aclib.net/SMAC/&sa=D&source=editors&ust=1621930682220000&usg=AOvVaw06yRuxETNxZqzJpyILfa8a)
* [Spearmint](https://www.google.com/url?q=https://github.com/JasperSnoek/spearmint&sa=D&source=editors&ust=1621930682221000&usg=AOvVaw3HxGQ2Oq7QI8xfFDe1UWo5)

* [BOHB](https://www.google.com/url?q=https://www.automl.org/automl/bohb/&sa=D&source=editors&ust=1621930682221000&usg=AOvVaw0ZPSWgYdZo3D0m2AHz1T_u): Bayesian Optimization combined with HyperBand
* [RoBO – Robust Bayesian Optimization framework](https://www.google.com/url?q=http://www.automl.org/automl/robo/&sa=D&source=editors&ust=1621930682222000&usg=AOvVaw0SyD0uDr4c1EowesReutn_)
* [SMAC3](https://www.google.com/url?q=https://github.com/automl/SMAC3&sa=D&source=editors&ust=1621930682222000&usg=AOvVaw3U0sCtNL2nJzNinmr4wYyG) – a python re-implementation of the SMAC algorithm

Architecture Search
-------------------

* [Auto-PyTorch](https://www.google.com/url?q=https://github.com/automl/Auto-PyTorch&sa=D&source=editors&ust=1621930682222000&usg=AOvVaw2uuQQls1T93_V9pmD2Al2_)
* [AutoKeras](https://www.google.com/url?q=https://autokeras.com/&sa=D&source=editors&ust=1621930682223000&usg=AOvVaw19d0QEmntNwfHoRKbDrrnj)
* [DEvol](https://www.google.com/url?q=https://github.com/joeddav/devol&sa=D&source=editors&ust=1621930682223000&usg=AOvVaw1_kWbmio4xm2o_fXnMMg07)
* [HyperAS](https://www.google.com/url?q=https://github.com/maxpumperla/hyperas&sa=D&source=editors&ust=1621930682224000&usg=AOvVaw3UpJsOy11L_0KSWmnHlSa0): a combination of Keras and Hyperopt
* [talos](https://www.google.com/url?q=https://github.com/autonomio/talos&sa=D&source=editors&ust=1621930682224000&usg=AOvVaw2lhAqEm7slmBjNiT_whXfe): Hyperparameter Scanning and Optimization for Keras

* * *

EXAMPLES
========

[NYC taxi pickup problem](https://www.google.com/url?q=http://www.vivekchoksi.com/papers/taxi_pickups.pdf&sa=D&source=editors&ust=1621930682225000&usg=AOvVaw0PBkcsCO-bGvyCftXN0XF3)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

[The taxi problem](https://www.google.com/url?q=http://www.vivekchoksi.com/papers/taxi_pickups.pdf&sa=D&source=editors&ust=1621930682225000&usg=AOvVaw0PBkcsCO-bGvyCftXN0XF3) is an intro to a well known machine learning problem, the paper will explain about feature engineering, analysis and using various regression algorithms for the purpose of solving the problem, you can use this as a base for many regression and classification problems.

A [Second study](https://www.google.com/url?q=http://blog.nycdatascience.com/student-works/predict-new-york-city-taxi-demand/&sa=D&source=editors&ust=1621930682226000&usg=AOvVaw0pnaG_tCUrGQv8gtvMyhhQ)(regression, random forest, [xgboost](https://www.google.com/url?q=http://xgboost.readthedocs.io/en/latest/model.html&sa=D&source=editors&ust=1621930682226000&usg=AOvVaw26gw9-IJ22kmI3MOp8pJdm) (extreme gradient boosting tree)).

[Standard error estimate](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Dr-txC-dpI-E%26index%3D4%26list%3DPLF596A4043DBEAE9C&sa=D&source=editors&ust=1621930682227000&usg=AOvVaw1vX9EPAKZLJHF1dUQR5qtz) \-\- measures the distance from the estimated value to the real value

R^2 error estimate- measures the distance of the estimated to the mean against the real to the mean, 1 no error, 0 lots.

\*\*\*\* with regression prediction it's best to create dummy variables (i.e., binary variables - exist or doesn't exist) from numeric variables, such as grid\_number to grid\_1, grid_2 etc..

SURVIVAL ANALYSIS
-----------------

1.  A good [introduction](https://www.google.com/url?q=http://www.stat.columbia.edu/~madigan/W2025/notes/survival.pdf&sa=D&source=editors&ust=1621930682228000&usg=AOvVaw34xf6UqUYPA4pssZ_2c_cB) for Survival Analysis

 PROPAGANDA
-----------

1.  [medium](https://www.google.com/url?q=https://medium.com/@jihwangk/fine-grained-propaganda-detection-and-classification-with-bert-dfad4acaa321&sa=D&source=editors&ust=1621930682229000&usg=AOvVaw05dpTgp2NoltVwCE4FjKxz)

* * *

EVALUATION METRICS
==================

A metric learning reality check
-------------------------------

1.  [Medium](https://www.google.com/url?q=https://medium.com/@tkm45/updates-to-a-metric-learning-reality-check-730b6914dfe7&sa=D&source=editors&ust=1621930682229000&usg=AOvVaw3jcLnepteSBO5Kf7--adn6)
2.  [Git](https://www.google.com/url?q=https://github.com/KevinMusgrave/pytorch-metric-learning?fbclid%3DIwAR3PmPTDgYFok4p095WmkRWLfWhixyjFXkZgFJzeYXs5Y92pofoNZL_lGTg&sa=D&source=editors&ust=1621930682230000&usg=AOvVaw1XWlR4hsb9WdjZT0a6pKks)
3.  [Website](https://www.google.com/url?q=https://kevinmusgrave.github.io/powerful-benchmarker/papers/mlrc/?fbclid%3DIwAR3jK3-qFphFsO7ocmjeN-zPLkcaQkTAcC78cFUNFVe1BgXzM-iE5PLh3bU&sa=D&source=editors&ust=1621930682230000&usg=AOvVaw3AWGnfT3_G0Rz6W_CoiOGR)

SUPERVISED
----------

### Precision \ Recall \ ROC \ AUC

\- [Performance Measures](https://www.google.com/url?q=http://machinelearningmastery.com/classification-accuracy-is-not-enough-more-performance-measures-you-can-use/&sa=D&source=editors&ust=1621930682231000&usg=AOvVaw2sV2d8vdkaDvp9a0WXlU-g):

A balanced confusion matrix is better than one that is either one row of numbers and one of zeros, or a column of numbers and a column of zeros. Therefore an algorithm that outputs a lower classification accuracy but has a better confusion matrix wins.

\# of Positive predictions divided by the total number of positive class values predicted.

Precision = True Positives / (True Positives + False Positives)

Low can be thought of many false positives.

\# of positive predictions divided by the number of positive class values in the test data

Recall (sensitivity) = True Positives / (True Positives + False Negatives)

Low can be thought of many false  negatives.

### F1 Harmonic Mean Score

F1_Score = 2 * ((Precision * Recall) / (Precision + Recall))

F1 helps select a model based on a balance between precision and recall.

In a multi-class problem, there are many methods to calculate F1, some are more appropriate for balanced data, others are not.

1.  [The best link yet](https://www.google.com/url?q=https://simonhessner.de/why-are-precision-recall-and-f1-score-equal-when-using-micro-averaging-in-a-multi-class-problem/&sa=D&source=editors&ust=1621930682233000&usg=AOvVaw32R8D1_f8h8oxGdHYfgPXM) \- micro macro weighted (macro balanced, micro imbalanced, weighted imbalanced)
2.  [Micro vs macro](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/15989/micro-average-vs-macro-average-performance-in-a-multiclass-classification-settin/16001&sa=D&source=editors&ust=1621930682233000&usg=AOvVaw2NdnJaE9UNB76s8B1FgSdR)
3.  [Micro vs weighted (not a good link](https://www.google.com/url?q=https://stats.stackexchange.com/questions/169439/micro-vs-weighted-f1-score&sa=D&source=editors&ust=1621930682234000&usg=AOvVaw1bkMcqkBKvcsGzw8Wq9OyS))
4.  [What is weighted](https://www.google.com/url?q=https://stats.stackexchange.com/questions/283961/where-does-sklearns-weighted-f1-score-come-from&sa=D&source=editors&ust=1621930682234000&usg=AOvVaw23WKNe6YKXgRvUTtNbLkDd)
5.  [Micro is accuracy](https://www.google.com/url?q=https://stackoverflow.com/questions/37358496/is-f1-micro-the-same-as-accuracy&sa=D&source=editors&ust=1621930682235000&usg=AOvVaw07tQksnLgx40GGb-GR4GV6) in multi class

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

* Accuracy = (1 – Error) = (TP + TN)/(PP + NP) = Pr(C), the probability of a correct classification.
* Sensitivity (recall) = TP/(TP + FN) = TP/PP = the ability of the test to detect disease in a population of diseased individuals.
* Specificity = TN/(TN + FP) = TN / NP = the ability of the test to correctly rule out the disease in a disease-free population.

([What are ?)](https://www.google.com/url?q=http://machinelearningmastery.com/assessing-comparing-classifier-performance-roc-curves-2/&sa=D&source=editors&ust=1621930682235000&usg=AOvVaw1CTBTKC7Vqg60IG14J2j6y) Sensitivity and specificity against ROC and AUC.

[ROC curve and AUC in weka](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Dj97h_-b0gvw%26list%3DPLJbE6j2EG1pZnBhOg3_Rb63WLCprtyJag&sa=D&source=editors&ust=1621930682236000&usg=AOvVaw3eiLJLx37tmVYqVWZW2fvf) \- explains how the curve should look like for the negative or positive predictions, against what is actually plotted.

Mean F1? [How](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/16179/what-is-the-correct-way-to-compute-mean-f1-score&sa=D&source=editors&ust=1621930682236000&usg=AOvVaw1kSnNfl03r4JDftLjpmTgn) do we calculate [it](https://www.google.com/url?q=http://rushdishams.blogspot.com/2011/08/micro-and-macro-average-of-precision.html&sa=D&source=editors&ust=1621930682237000&usg=AOvVaw3gn4NqV5-Am0b1MP5uxi0U).

[Multiclass Precision / Recall](https://www.google.com/url?q=https://towardsdatascience.com/multi-class-metrics-made-simple-part-ii-the-f1-score-ebe8b2c2ca1&sa=D&source=editors&ust=1621930682238000&usg=AOvVaw2nUR-CTgoSJxt-Sqt5Gc_a), [part 1](https://www.google.com/url?q=https://towardsdatascience.com/multi-class-metrics-made-simple-part-i-precision-and-recall-9250280bddc2&sa=D&source=editors&ust=1621930682238000&usg=AOvVaw3Qv1DRQvZjRlUkuGBCpHxJ)

[Precision at K](https://www.google.com/url?q=https://medium.com/@m_n_malaeb/recall-and-precision-at-k-for-recommender-systems-618483226c54&sa=D&source=editors&ust=1621930682239000&usg=AOvVaw3OHfX8_GMzbP1CUI3Q459R), [formulas, examples](https://www.google.com/url?q=https://surprise.readthedocs.io/en/latest/FAQ.html%23how-to-compute-precision-k-and-recall-k&sa=D&source=editors&ust=1621930682239000&usg=AOvVaw2qeVXg4nXh813cEhZU_BWI), [git 1](https://www.google.com/url?q=https://github.com/scikit-learn/scikit-learn/pull/14859&sa=D&source=editors&ust=1621930682240000&usg=AOvVaw1Qcz9NuGcXTJxsT4Ipirc2), [git 2](https://www.google.com/url?q=https://gist.github.com/mblondel/7337391&sa=D&source=editors&ust=1621930682240000&usg=AOvVaw06TVK0_MZX6OYbvQfDQXT-), [git 3](https://www.google.com/url?q=https://github.com/scikit-learn/scikit-learn/issues/7343&sa=D&source=editors&ust=1621930682241000&usg=AOvVaw0H--UUxIYggJj8AqTHXVpp) (suggestive, recommendation application)

* * *

### RECALL, PRECISION AND F1

1.  [Medium on Controling the decision threshold using the probabilities any model gives, code, samples, tutorial](https://www.google.com/url?q=https://towardsdatascience.com/fine-tuning-a-classifier-in-scikit-learn-66e048c21e65&sa=D&source=editors&ust=1621930682242000&usg=AOvVaw1nJhx0ZfynqrBLZrOJvIWe)
2.  [Another good medium explanation on precision / recall / fpr/ tpr etc](https://www.google.com/url?q=https://towardsdatascience.com/beyond-accuracy-precision-and-recall-3da06bea9f6c&sa=D&source=editors&ust=1621930682243000&usg=AOvVaw0rIGVlzotpaDCqtlB8Q_HL)
3.  [Scikit lego on choosing the threshold using grid search](https://www.google.com/url?q=https://scikit-lego.readthedocs.io/en/latest/meta.html%23Thresholder&sa=D&source=editors&ust=1621930682244000&usg=AOvVaw2PqsLalgt0io8XTm26Det9)
4.  [Best explanation ever](https://www.google.com/url?q=https://www.quora.com/What-is-the-best-way-to-understand-the-terms-precision-and-recall&sa=D&source=editors&ust=1621930682245000&usg=AOvVaw3cPUk1H9sCF_mVDigsrC3L)

#### Recall

* one day, your girlfriend asks you: ‘Sweetie, do you remember all birthday surprises from me?’
* This simple question makes your life in danger. To extend your life, you need to recallall 10 surprising events from your memory.
* So, recallis the ratio of a number of events you can correctly recallto a number of all correct events. If you can recall all 10events correctly, then, your recall ratio is 1.0 (100%). If you can recall 7events correctly, your recall ratio is 0.7 (70%).

#### Precision

* For example, you answers 15times, 10events are correct and 5events are wrong. This means you can recall all events but it’s not so precise.
* So, precisionis the ratio of a number of events you can correctly recallto a number all events you recall(mix of correct and wrong recalls). In other words, it is how precise of your recall.
* From the previous example (10 real events, 15 answers: 10 correct answers, 5 wrong answers), you get 100%recall but your precision is only 66.67% (10 / 15).

[Confusion matrix wise](https://www.google.com/url?q=http://www.kdnuggets.com/faq/precision-recall.html&sa=D&source=editors&ust=1621930682250000&usg=AOvVaw3xhMVSKd5kbcID9JFAE3tY): bottom line is recall (%correct out of positive cases), right column is precision (% of  POS  predictions) & % accuracy in diagonal

![](images/image169.png)

[F1 score](https://www.google.com/url?q=http://machinelearningmastery.com/classification-accuracy-is-not-enough-more-performance-measures-you-can-use/&sa=D&source=editors&ust=1621930682252000&usg=AOvVaw257In2Z8KB1tIq8elybRkl):

* conveys the balance between the precision and the recall
* 2*((precision*recall)/(precision+recall)

[Yet another(pretty good) source](https://www.google.com/url?q=http://blog.exsilio.com/all/accuracy-precision-recall-f1-score-interpretation-of-performance-measures/&sa=D&source=editors&ust=1621930682253000&usg=AOvVaw2EqpOu56LNyjTsN91XqJVT)

[Another (bad) source](https://www.google.com/url?q=https://chrisalbon.com/machine-learning/precision_recall_and_F1_scores.html&sa=D&source=editors&ust=1621930682253000&usg=AOvVaw38YVUxDadEnpRLir7KKben) for explaining, precision, recall, accuracy, true positive rate etc.

(How to use precision and recall?) answer by aurelien geron:

* In a binary classifier, the decision function is the function that produces a score for the positive class.
* In a logistic regression classifier, that decision function is simply a linear combination of the input features.
* If that score is greater than some threshold that you choose, then the classifier "predicts" the positive class, or else it predicts the negative class.
* If you want your model to have high precision (at the cost of a low recall), then you must set the threshold pretty high. This way, the model will only predict the positive class when it is absolutely certain. For example, you may want this if the classifier is selecting videos that are safe for kids: it's better to err on the safe side.
* Conversely, if you want high recall (at the cost of a low precision) then you must use a low threshold. For example, if the classifier is used to detect intruders in a nuclear plant, then you probably want to detect all actual intruders, even if it means getting a lot of false alarms (called "false positives").
* If you make a few assumptions about the distribution of the data (i.e., the positive and negative class are separated by a linear boundary plus Gaussian noise), then computing the logistic of the score gives you the probability that the instance belongs to the positive class. A score of 0 corresponds to the 50% probability. So by default, a LogisticClassifier predicts the positive class if it estimates the probability to be greater than 50%. In general, this sounds like a reasonable default threshold, but really it all depends on what you want to do with the classifier.
* If the assumptions I mentioned above were perfect, then if the Logistic Classifier outputs a probability of X% for an instance, it means there is exactly X% chance that it's positive. But in practice, the assumptions are imperfect, so I try to always make it clear that we are talking about an "estimated probability", not an actual probability.

### ROC CURVES

1.  [Diff between precision recall to roc curve](https://www.google.com/url?q=https://www.quora.com/What-is-the-difference-between-a-ROC-curve-and-a-precision-recall-curve-When-should-I-use-each&sa=D&source=editors&ust=1621930682255000&usg=AOvVaw3VLAJnMidKcEGj4LdVWS2a)
2.  [What is ROC AUC and PR AUC and when to use then (i.e for imbalanced data use PRAUC)](https://www.google.com/url?q=http://www.chioka.in/differences-between-roc-auc-and-pr-auc/&sa=D&source=editors&ust=1621930682256000&usg=AOvVaw1hDp0rA8ARxLgDjbPITxqR)
3.  [What is AUC (AUROC)](https://www.google.com/url?q=https://stats.stackexchange.com/questions/132777/what-does-auc-stand-for-and-what-is-it&sa=D&source=editors&ust=1621930682256000&usg=AOvVaw09nj6eZqz374cFcv0dRTTy)

* * *

[(RMSE - what is?)](https://www.google.com/url?q=https://stats.stackexchange.com/questions/56302/what-are-good-rmse-values&sa=D&source=editors&ust=1621930682257000&usg=AOvVaw00pWHvqW6Om7QBOPQ0Vp6A)\- it is important to recall that RMSE has the same unit as the dependent variable (DV). It means that there is no absolute good or bad threshold, however you can define it based on your DV. For a datum which ranges from 0 to 1000, an RMSE of 0.7 is small, but if the range goes from 0 to 1, it is not that small anymore.However, although the smaller the RMSE, the better, 

[(R^2 vs RMSE)](https://www.google.com/url?q=https://stats.stackexchange.com/questions/142248/difference-between-r-square-and-rmse-in-linear-regression&sa=D&source=editors&ust=1621930682257000&usg=AOvVaw10wQov0eWRQ3frbnFSWLmt)\- R-squared is conveniently scaled between 0 and 1, whereas RMSE is not scaled to any particular values. This can be good or bad; obviously R-squared can be more easily interpreted, but with RMSE we explicitly know how much our predictions deviate, on average, from the actual values in the dataset. So in a way, RMSE tells you more.

I also found this [video](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Daq8VU5KLmkY&sa=D&source=editors&ust=1621930682258000&usg=AOvVaw35AkjBt3lAuNsmYm6Foorh) really helpful.

[Kappa](https://www.google.com/url?q=https://stats.stackexchange.com/questions/82162/cohens-kappa-in-plain-english&sa=D&source=editors&ust=1621930682258000&usg=AOvVaw2aSJcqt2qtiU5jx8SYyeeV) \- measures accuracy while considering imbalanced datasets

References:

1.  [A Survey on Deep Learning in Medical Image Analysis](https://www.google.com/url?q=https://arxiv.org/abs/1702.05747&sa=D&source=editors&ust=1621930682259000&usg=AOvVaw1VNrkryaxYqonYwlzF6oSO)

UNSUPERVISED
------------

1.  [Silhouette Analysis vs Elbow Method vs Davies-Bouldin Index: Selecting the optimal number of clusters for KMeans clustering](https://www.google.com/url?q=https://gdcoder.com/silhouette-analysis-vs-elbow-method-vs-davies-bouldin-index-selecting-the-optimal-number-of-clusters-for-kmeans-clustering/&sa=D&source=editors&ust=1621930682259000&usg=AOvVaw0SYmED7E01cJ6vbULkqoEX)

* * *

BENCHMARKING
============

Numpy Blas:

1.  [How do i know which version of blas is installed](https://www.google.com/url?q=https://stackoverflow.com/questions/37184618/find-out-if-which-blas-library-is-used-by-numpy&sa=D&source=editors&ust=1621930682260000&usg=AOvVaw1Qa7DjTwxJzYb95U_olZqT)
2.  [Benchmark OpenBLAS, Intel MKL vs ATLAS](https://www.google.com/url?q=https://github.com/tmolteno/necpp/issues/18&sa=D&source=editors&ust=1621930682261000&usg=AOvVaw2ufiwmApCV7sbQVpS3lGqJ)

![](images/image164.png)

3.  [Another comparison](https://www.google.com/url?q=http://markus-beuckelmann.de/blog/boosting-numpy-blas.html&sa=D&source=editors&ust=1621930682261000&usg=AOvVaw36WFEFyIILmWnT9LtP-vdR)
4.  ![](images/image266.png)

GLUE:

1.  [Glue / super glue](https://www.google.com/url?q=https://gluebenchmark.com/leaderboard/?fbclid%3DIwAR17Xo2pgpDVE_ZuwITDSi07FLM6S2f1VTXiLywwr2NnUGqS8AdndZLQpXI&sa=D&source=editors&ust=1621930682262000&usg=AOvVaw1r8BD2G4doHqBnRPpt007S)

State of the art in AI:

1.  In terms of [domain X datasets](https://www.google.com/url?q=https://www.stateoftheart.ai/&sa=D&source=editors&ust=1621930682262000&usg=AOvVaw3ikUdk6pn4I9YVlLYEDcd-)

Cloud providers:

* [Part 1](https://www.google.com/url?q=https://rare-technologies.com/machine-learning-hardware-benchmarks/&sa=D&source=editors&ust=1621930682263000&usg=AOvVaw0ovH7PP_nvzMkinqUdhNm4), [part 2 y gensim](https://www.google.com/url?q=https://rare-technologies.com/machine-learning-benchmarks-hardware-providers-gpu-part-2/&sa=D&source=editors&ust=1621930682263000&usg=AOvVaw1HFp23H44hTpnHgqY65LkM)

Datasets:

* [EFF FF Benchmarks in AI](https://www.google.com/url?q=https://www.eff.org/ai/metrics&sa=D&source=editors&ust=1621930682264000&usg=AOvVaw2X92369sjs3EU1zrl2xvH3)

Hardware:

* [Nvidia](https://www.google.com/url?q=https://www.phoronix.com/scan.php?page%3Darticle%26item%3Dnvidia-rtx2080ti-tensorflow%26num%3D1&sa=D&source=editors&ust=1621930682264000&usg=AOvVaw1Xe_B-2i-LvAstB8HOhFZy) 1070 vs 1080 vs 2080
* [Cpu vs GPU benchmarking for CNN\\Test\\LTSM\\BDLTSM](https://www.google.com/url?q=http://minimaxir.com/2017/07/cpu-or-gpu/&sa=D&source=editors&ust=1621930682264000&usg=AOvVaw3s6tMjx0Y5qZveMXO0ikBr) \- google and amazon vs gpu
* [Nvidia GPUs](https://www.google.com/url?q=https://www.pugetsystems.com/labs/hpc/TitanXp-vs-GTX1080Ti-for-Machine-Learning-937/&sa=D&source=editors&ust=1621930682265000&usg=AOvVaw2Jv-VF4rXYLHYJ3rxjw-h9) \- titax Xp\\1080TI\\1070 on googlenet
* March\\17 - [Nvidia GPUs for desktop](https://www.google.com/url?q=https://medium.com/@timcamber/deep-learning-pc-build-5cffa71ad97&sa=D&source=editors&ust=1621930682265000&usg=AOvVaw1pKWSzqGiQK_BbBqjm82J5), in terms of price and cuda units, the bottom line is 1060-1080.
* [Another bench up to 2013](https://www.google.com/url?q=http://timdettmers.com/2017/04/09/which-gpu-for-deep-learning/&sa=D&source=editors&ust=1621930682266000&usg=AOvVaw15Jpei9UH41mqfPWtKsyCA) \- regarding many GPUS vs CPUs in terms of BW

Platforms

* [Cntk vs tensorflow](https://www.google.com/url?q=http://minimaxir.com/2017/06/keras-cntk/&sa=D&source=editors&ust=1621930682266000&usg=AOvVaw1WsF6E-71Bz0rMSbWvrgma)
* [CNTK, TEnsor, torch, etc on cpu and gpu](https://www.google.com/url?q=https://arxiv.org/pdf/1608.07249.pdf&sa=D&source=editors&ust=1621930682266000&usg=AOvVaw0x_kxzudSNa0IXLF8-Eyhj)

Algorithms:

* [Comparing](https://www.google.com/url?q=https://martin-thoma.com/comparing-classifiers/&sa=D&source=editors&ust=1621930682267000&usg=AOvVaw2jRhGwS11Yp0HKSnyktkQ0) accuracy, speed, memory and 2D visualization of classifiers:

[SVM,](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html&sa=D&source=editors&ust=1621930682267000&usg=AOvVaw043M0xfHJ_J2JPoXWCAKLZ)[k-nearest neighbors,](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html&sa=D&source=editors&ust=1621930682267000&usg=AOvVaw2oGeYbNLLgtoLywDmCJcyz)[Random Forest,](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html&sa=D&source=editors&ust=1621930682268000&usg=AOvVaw1naSW-9fnbI97lQrKph1ah)[AdaBoost Classifier,](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html&sa=D&source=editors&ust=1621930682268000&usg=AOvVaw1z7_hvqmvDGx1CQ5pd3UBP)[Gradient Boosting,](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html&sa=D&source=editors&ust=1621930682268000&usg=AOvVaw2pj9AtZLbjVIqNj_kvL0nY)[Naive, Bayes,](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html&sa=D&source=editors&ust=1621930682269000&usg=AOvVaw34v7RZ_ziz_FMKyebpmuZf)[LDA,](https://www.google.com/url?q=http://scikit-learn.org/0.16/modules/generated/sklearn.lda.LDA.html&sa=D&source=editors&ust=1621930682269000&usg=AOvVaw0qukgm0MEw1SL8v-6F83-3) [QDA,](https://www.google.com/url?q=http://scikit-learn.org/0.16/modules/generated/sklearn.qda.QDA.html&sa=D&source=editors&ust=1621930682269000&usg=AOvVaw3GiAbdIlIsREFIQLauleBa)[RBMs,](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.neural_network.BernoulliRBM.html&sa=D&source=editors&ust=1621930682270000&usg=AOvVaw3Y69Kc9b_b8cUzpy5lDbrS) [Logistic Regression,](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html&sa=D&source=editors&ust=1621930682270000&usg=AOvVaw0Ao973ol4Wgqd0NS1kwfb5) [RBM](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.neural_network.BernoulliRBM.html&sa=D&source=editors&ust=1621930682270000&usg=AOvVaw3Y69Kc9b_b8cUzpy5lDbrS) \+ Logistic Regression Classifier

* [LSTM vs cuDNN LS1TM](https://www.google.com/url?q=https://chainer.org/general/2017/03/15/Performance-of-LSTM-Using-CuDNN-v5.html&sa=D&source=editors&ust=1621930682271000&usg=AOvVaw0q7tXxJIfJ1PWgMKP2X0fu) \- batch size of power 2 matters, the latter is faster.

Scaling networks and predicting performance of NN:

* [A great overview of NN type](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DlgK0BlXdOCw%26feature%3Dyoutu.be&sa=D&source=editors&ust=1621930682272000&usg=AOvVaw1bnWx_OAetDN5yQpjwHDTm)s, but the idea behind the video is to create a system that can predict train time and possibly accuracy when scaling networks using multiple GPUs, there is also a nice slide about general hardware recommendations.

![](images/image192.png)

NLP

* [XTREME: A Massively Multilingual Multi-task Benchmark for Evaluating Cross-lingual Generalization](https://www.google.com/url?q=https://github.com/google-research/xtreme/blob/master/README.md&sa=D&source=editors&ust=1621930682273000&usg=AOvVaw2WZI4Iz1XprNirYwWtoAFk)

* * *

HYPER PARAMETER OPTIMIZATION
============================

[1\. Using HyperOpt](https://www.google.com/url?q=http://hyperopt.github.io/hyperopt/&sa=D&source=editors&ust=1621930682274000&usg=AOvVaw0qqDZNevzVfWIZ89zJgbXH) -

* Random Search
* Tree of Parzen Estimators (TPE)

Hyperopt has been designed to accommodate Bayesian optimization algorithms based on Gaussian processes and regression trees, but these are not currently implemented.

All algorithms can be run either serially, or in parallel by communicating via [MongoDB](https://www.google.com/url?q=http://www.mongodb.org/&sa=D&source=editors&ust=1621930682276000&usg=AOvVaw02F8zbeWK09GwBgkJslE3j).

* [Mlflow, Hyperparameterhunter,hyperopt, concept drift, unit tests.](https://www.google.com/url?q=https://towardsdatascience.com/putting-ml-in-production-ii-logging-and-monitoring-algorithms-91f174044e4e&sa=D&source=editors&ust=1621930682276000&usg=AOvVaw1InwgfCqX5drrToDsVZBJP)
* [Hyperopt](https://www.google.com/url?q=http://hyperopt.github.io/hyperopt/&sa=D&source=editors&ust=1621930682277000&usg=AOvVaw0FwC5RMYYmLPfqMLG8PWyW) for hyper parameter search

2\. [HyperparameterHunter](https://www.google.com/url?q=https://github.com/HunterMcGushion/hyperparameter_hunter&sa=D&source=editors&ust=1621930682278000&usg=AOvVaw3ErdRT2V51o5O6HPNe6D2y) \-    
        provides a wrapper for machine learning algorithms that saves all the important data. Simplify the experimentation and hyperparameter tuning process by letting HyperparameterHunter do the hard work of recording, organizing, and learning from your tests — all while using the same libraries you already do. Don't let any of your experiments go to waste, and start doing hyperparameter optimization the way it was meant to be.

3\. [Implementation and comparison](https://www.google.com/url?q=https://towardsdatascience.com/putting-ml-in-production-ii-logging-and-monitoring-algorithms-91f174044e4e&sa=D&source=editors&ust=1621930682278000&usg=AOvVaw2Is1MOVPzlBqndYC25sgeR) \- HH slower than HO due to usage of skopt.

Multi CPU Processing
====================

1.  [Numpy](https://www.google.com/url?q=https://gitlab.com/tenzing/shared-array&sa=D&source=editors&ust=1621930682279000&usg=AOvVaw0NrUS8SPmdTQ-DnVsL3djV) on multi process, and [how to use it.](https://www.google.com/url?q=https://medium.com/analytics-vidhya/multiprocessing-for-data-scientists-in-python-427b2ff93af1&sa=D&source=editors&ust=1621930682280000&usg=AOvVaw03CZOS34NCrs1JPZ8QLWGU)
2.  [Pandas on multi process](https://www.google.com/url?q=https://github.com/nalepae/pandarallel&sa=D&source=editors&ust=1621930682280000&usg=AOvVaw2B2G6dkjNgdYlZ8gasNRC5)
3.  \*\*\*[Dask](https://www.google.com/url?q=https://docs.dask.org/en/latest/&sa=D&source=editors&ust=1621930682281000&usg=AOvVaw1mninTafrjqVbqy99FtfQT) \- youtube [intros](https://www.google.com/url?q=https://www.youtube.com/channel/UCj9eavqmvwaCyKhIlu2GaoA&sa=D&source=editors&ust=1621930682281000&usg=AOvVaw1RSL_G_BU1v7UW8QhFmwj_)

1.  Diagnostic [dashboards](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DN_GqzcuGLCY&sa=D&source=editors&ust=1621930682282000&usg=AOvVaw3ShiV_fy2i1D-uo303NGNk)
2.  [Ditributed sklearn](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D5Zf6DQaf7jk&sa=D&source=editors&ust=1621930682282000&usg=AOvVaw3JQfntcm5NLjkNg_ADLFYg) (amazing)

4.  [Dask vs swifter vs vectorize](https://www.google.com/url?q=https://gdcoder.com/speed-up-pandas-apply-function-using-dask-or-swifter-tutorial/&sa=D&source=editors&ust=1621930682283000&usg=AOvVaw1rg5RveQICsJpINp5NzNR_)

1.  Dask is dask
2.  Swifter will attempt to understand if dask or pandas apply should be used, looks like its using multi cpu so it may not be just using dask on the backend?
3.  Vectorize is just another option

5.  [Multi process cpu example](https://www.google.com/url?q=https://datascience.blog.wzb.eu/2017/06/19/speeding-up-nltk-with-parallel-processing/&sa=D&source=editors&ust=1621930682284000&usg=AOvVaw0izTaDjUVM2Oj91_bLl9cZ)
6.  [Medium on MP, using MP pool, Ray etc.](https://www.google.com/url?q=https://medium.com/distributed-computing-with-ray/how-to-scale-python-multiprocessing-to-a-cluster-with-one-line-of-code-d19f242f60ff&sa=D&source=editors&ust=1621930682284000&usg=AOvVaw3paoZOEFjZORUUKQXjUjUa)
7.  [Async (multi process/thread/coroutines/asyncio)](https://www.google.com/url?q=https://medium.com/velotio-perspectives/an-introduction-to-asynchronous-programming-in-python-af0189a88bbb&sa=D&source=editors&ust=1621930682285000&usg=AOvVaw2s4t-afcNlNXjsxtPqKPtL)

* * *

MONITORING & ALERTS
===================

* [Monitor! Stop being a blind DS](https://www.google.com/url?q=https://towardsdatascience.com/monitor-stop-being-a-blind-data-scientist-ac915286075f&sa=D&source=editors&ust=1621930682286000&usg=AOvVaw0IDDdYuQffmMUzETiZYvOa)
* [Monitor your dependencies! Stop being a blind DS](https://www.google.com/url?q=https://towardsdatascience.com/monitor-your-dependencies-stop-being-a-blind-data-scientist-a3150bd64594&sa=D&source=editors&ust=1621930682287000&usg=AOvVaw1UldpqB_B5h4up802MAsIW)
* [Production Machine Learning Monitoring: Outliers, Drift, Explainers & Statistical Performance](https://www.google.com/url?q=https://towardsdatascience.com/production-machine-learning-monitoring-outliers-drift-explainers-statistical-performance-d9b1d02ac158&sa=D&source=editors&ust=1621930682287000&usg=AOvVaw0R4GTklTVfzGFfzOPJBb9N), [youtube](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DQcevzK9ZuDg&sa=D&source=editors&ust=1621930682288000&usg=AOvVaw1GZ3R1OKRUr-mx2JmYvwei), uses [alibi-explain](#h.xs1o8m3ro5iy) (see compendium)  and ali-detect (see compendium)
* [Mlflow, Hyperparameterhunter,hyperopt, concept drift, unit tests.](https://www.google.com/url?q=https://towardsdatascience.com/putting-ml-in-production-ii-logging-and-monitoring-algorithms-91f174044e4e&sa=D&source=editors&ust=1621930682289000&usg=AOvVaw0TNqmUOSwLOEQ4kl6RR__V)
* [meta anomaly over multiple models, aggregate.](https://www.google.com/url?q=https://www.anodot.com/blog/monitoring-machine-learning/&sa=D&source=editors&ust=1621930682289000&usg=AOvVaw0WITFbkUiJQKDrq-ugFOQ-)
* [Vidhya on monitoring data / models](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2019/10/deployed-machine-learning-model-post-production-monitoring/&sa=D&source=editors&ust=1621930682290000&usg=AOvVaw2x4_Qd00F2-fn7ESNSOWk1)

Concept drift
-------------

1.  [Some advice on medium](https://www.google.com/url?q=https://towardsdatascience.com/concept-drift-and-model-decay-in-machine-learning-a98a809ea8d4&sa=D&source=editors&ust=1621930682291000&usg=AOvVaw3x0wyAjylXNCC2Ko6ZxCsW), relabel using latest model (can we even trust it?) retrain after.
2.  [Adversarial Validation Approach to Concept Drift Problem in User Targeting Automation Systems at Uber](https://www.google.com/url?q=https://arxiv.org/abs/2004.03045&sa=D&source=editors&ust=1621930682291000&usg=AOvVaw1n5sRvzcIl8mRdB2my_i4t)  \- Previous research on concept drift mostly proposed model retraining after observing performance decreases. However, this approach is suboptimal because the system fixes the problem only after suffering from poor performance on new data. Here, we introduce an adversarial validation approach to concept drift problems in user targeting automation systems. With our approach, the system detects concept drift in new data before making inference, trains a model, and produces predictions adapted to the new data.
3.  Drift estimator between data sets using random forest, formula is in the medium article above, code here at [mlBOX](https://www.google.com/url?q=https://github.com/AxeldeRomblay/MLBox/blob/811dbcb04fc7f5501e82f3e78aa6c119f426ee78/python-package/mlbox/preprocessing/drift/drift_estimator.py&sa=D&source=editors&ust=1621930682292000&usg=AOvVaw1K4j2Ht0CAUer97CogqwPJ)
4.  [Alibi-detect](#h.y6mpsp4co5t9)\- is an open source Python library focused on outlier, adversarial and drift detection.

![](images/image54.png)

* * *

ALGORITHMS
==========

1.  [Amortization](https://www.google.com/url?q=https://medium.com/@aleksandrasays/amortised-analysis-in-the-nutshell-7b056277ab9b&sa=D&source=editors&ust=1621930682294000&usg=AOvVaw3ilOxYSdjmM2GGsJjZcq-J) \- Amortised analysis in the nutshell, Worst-Case vs Average-Case, and then where amortized is the average performance (over time) of each operation in the worst-case.

TRAINING STRATEGIES
===================

1.  (amazing) [Framework for a successful training strategy](https://www.google.com/url?q=https://towardsdatascience.com/framework-for-a-successful-continuous-training-strategy-8c83d17bb9dc&sa=D&source=editors&ust=1621930682295000&usg=AOvVaw2UUUF0S6wkiVuzZE7W3ZW_), periodic, performance based, driven by data changes, dynamic window size, dynamic data selection, what to retrain and the level of training.
    
    * * *
    

CLASSIC MACHINE LEARNING
========================

 ASSOCIATION RULES
------------------

1.  [Association rules slides](https://www.google.com/url?q=https://www.slideshare.net/wanaezwani/apriori-and-eclat-algorithm-in-association-rule-mining&sa=D&source=editors&ust=1621930682297000&usg=AOvVaw0VzPmVz7LjU4lIU54vzv_2) \- apriori, eclat, fp growth - pretty complete
2.  [Terms](https://www.google.com/url?q=https://www.kdnuggets.com/2016/04/association-rules-apriori-algorithm-tutorial.html&sa=D&source=editors&ust=1621930682297000&usg=AOvVaw1QBj0oHz8UQ3ruuIurCsyW) \- lift, confidence
3.  [Paper - basic concepts and algo](https://www.google.com/url?q=https://www-users.cs.umn.edu/~kumar001/dmbook/ch5_association_analysis.pdf&sa=D&source=editors&ust=1621930682298000&usg=AOvVaw3koDTUbMw_l2wn3P9BEmS2)

#### Knoldus

1.  [Apriori](https://www.google.com/url?q=https://blog.knoldus.com/machinex-why-no-one-uses-apriori-algorithm-for-association-rule-learning/&sa=D&source=editors&ust=1621930682299000&usg=AOvVaw0ws0tQzCO0xr1tlTgmhvP2)
2.  [Association rules](https://www.google.com/url?q=https://blog.knoldus.com/machinex-two-parts-of-association-rule-learning/&sa=D&source=editors&ust=1621930682299000&usg=AOvVaw1Psv0Z3sdxX5Fl5iwLPSe7)
3.  [Fp-growth](https://www.google.com/url?q=https://blog.knoldus.com/machinex-frequent-itemset-generation-with-the-fp-growth-algorithm/&sa=D&source=editors&ust=1621930682300000&usg=AOvVaw1FzTgydfZWV7_u42yWQAQW)
4.  [Fp-tree construction](https://www.google.com/url?q=https://blog.knoldus.com/machinex-understanding-fp-tree-construction/&sa=D&source=editors&ust=1621930682300000&usg=AOvVaw2qIlcNnIAclLdTJVOo0Z9Z)

#### APRIORI

5.  [Apyori tut](https://www.google.com/url?q=https://stackabuse.com/association-rule-mining-via-apriori-algorithm-in-python/&sa=D&source=editors&ust=1621930682301000&usg=AOvVaw3ElHsXHpx6liiMMhWItX2c)[git](https://www.google.com/url?q=https://github.com/ymoch/apyori&sa=D&source=editors&ust=1621930682302000&usg=AOvVaw0inkLaENGa5o7s6MzhZKDz)
6.  [Efficient apriori](https://www.google.com/url?q=https://github.com/tommyod/Efficient-Apriori&sa=D&source=editors&ust=1621930682302000&usg=AOvVaw3ACrHGSKTbj22-LMOiRVGu)
7.  [One of the best known association rules algorithm](https://www.google.com/url?q=https://machinelearningmastery.com/market-basket-analysis-with-association-rule-learning/&sa=D&source=editors&ust=1621930682303000&usg=AOvVaw3Iodyyf05T4lDB_ocD_HOt) \- apriori in weka
8.  [A very good visual example of a transaction DB with the apriori algorithm step by step](https://www.google.com/url?q=http://www.lessons2all.com/Apriori.php&sa=D&source=editors&ust=1621930682303000&usg=AOvVaw0vlVKs2XGV4awEwwjQK6Vr)
9.  [Python 3.0 code](https://www.google.com/url?q=http://adataanalyst.com/machine-learning/apriori-algorithm-python-3-0/&sa=D&source=editors&ust=1621930682304000&usg=AOvVaw31mgI4flYHREw3Smx_5g_q)
10. [Mlxtnd](https://www.google.com/url?q=http://rasbt.github.io/mlxtend/api_subpackages/mlxtend.frequent_patterns/&sa=D&source=editors&ust=1621930682304000&usg=AOvVaw2ylO79iNfzb9tdsmb1egXf)[tutorial](https://www.google.com/url?q=https://www.geeksforgeeks.org/implementing-apriori-algorithm-in-python/&sa=D&source=editors&ust=1621930682305000&usg=AOvVaw1gsJGaKyFeWi0YAtKkDl4M)

1.  Apriori
2.  Rules
3.  pgrowth
4.  fpmax

#### FP Growth

11. [How to construct the fp-tree](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Dgq6nKbye648&sa=D&source=editors&ust=1621930682306000&usg=AOvVaw0cCyGt7Vbgk8-3XsIcDOJj)
12. The same example, but with a graph that shows that lower support cost less for fp-growth in terms of calc time.
13. [Coursera video](https://www.google.com/url?q=https://www.coursera.org/learn/data-patterns/lecture/ugqCs/2-5-fpgrowth-a-pattern-growth-approach&sa=D&source=editors&ust=1621930682306000&usg=AOvVaw0bCMfWw_0NSZ2YAkzZY_1a)
14. Another clip video

4.  [How to validate these algorithms](https://www.google.com/url?q=https://stackoverflow.com/questions/32843093/how-to-validate-association-rules&sa=D&source=editors&ust=1621930682307000&usg=AOvVaw1R-GcgDlYZGplQnWv3Rjdq) \- probably the best way is confidence/support/lift

It depends on your task. But usually you want all [three to be high.](https://www.google.com/url?q=https://stats.stackexchange.com/questions/229523/association-rules-support-confidence-and-lift&sa=D&source=editors&ust=1621930682307000&usg=AOvVaw2GO5zCFR_je6g_KkP0o2GS)

* high support: should apply to a large amount of cases
* high confidence: should be correct often
* high lift: indicates it is not just a coincidence

5.  [Difference between apriori and fp-growth](https://www.google.com/url?q=https://www.quora.com/What-is-the-difference-between-FPgrowth-and-Apriori-algorithms-in-terms-of-results&sa=D&source=editors&ust=1621930682308000&usg=AOvVaw1Fp_SsAROrrN6qJVSFgLvO)
    
    * * *
    

PROBABILISTIC ALGORITHMS
------------------------

### NAIVE BAYES

1.  [Vidhya on NB](https://www.google.com/url?q=https://towardsdatascience.com/my-secret-sauce-to-be-in-top-2-of-a-kaggle-competition-57cff0677d3c?fbclid%3DIwAR3Iei5OmwswIMbbqcz2dNr5rLsWS-iuuaAuOjmhCELTTEBTPmSM85mTw7U&sa=D&source=editors&ust=1621930682309000&usg=AOvVaw1RX5WzRMPOpC852-01Vjou)
2.  [Baysian tree](https://www.google.com/url?q=https://github.com/UBS-IB/bayesian_tree&sa=D&source=editors&ust=1621930682310000&usg=AOvVaw2Ss31tZx-ptHVmCk-5eNWD)
3.  [NB, GNB, multi nominal NB](https://www.google.com/url?q=https://jakevdp.github.io/PythonDataScienceHandbook/05.05-naive-bayes.html&sa=D&source=editors&ust=1621930682310000&usg=AOvVaw0U9whC5ngg9TsB2Yrf2_UM)

### BAYES, BAYESIAN BELIEF NETWORKS

1.  [Mastery on bayes theorem](https://www.google.com/url?q=https://machinelearningmastery.com/bayes-theorem-for-machine-learning/?fbclid%3DIwAR3txPR1zRLXhmArXsGZFSphhnXyLEamLyyqbAK8zBBSZ7TM3e6b3c3U49E&sa=D&source=editors&ust=1621930682311000&usg=AOvVaw0T6hmRCiVH0OuZN1oywBNi)
2.  [Introduction To BBS](https://www.google.com/url?q=https://codesachin.wordpress.com/2017/03/10/an-introduction-to-bayesian-belief-networks/&sa=D&source=editors&ust=1621930682312000&usg=AOvVaw2Z9RxtOh1tC32ACxKklLSj) \- a very good blog post
3.  A [complementing SLIDE presentation](https://www.google.com/url?q=https://www.slideshare.net/GiladBarkan/bayesian-belief-networks-for-dummies&sa=D&source=editors&ust=1621930682312000&usg=AOvVaw1yXJc5PCkUC_pwpW-Js6Pz) that shows how to build the network’s tables
4.  A [very nice presentation](https://www.google.com/url?q=http://chem-eng.utoronto.ca/~datamining/Presentations/Bayesian_Belief_Network.pdf&sa=D&source=editors&ust=1621930682313000&usg=AOvVaw01jZow0pJn4s10W7dWyNn1) regarding BBS

6.  [Maximum Likelihood](https://www.google.com/url?q=http://mathworld.wolfram.com/MaximumLikelihood.html&sa=D&source=editors&ust=1621930682314000&usg=AOvVaw0WWyNuqTi0SLw4fsSGOAT3) (log likelihood) - proofs for bernoulli, normal, poisson.
7.  [Another example](https://www.google.com/url?q=https://codesachin.wordpress.com/2017/03/10/an-introduction-to-bayesian-belief-networks/&sa=D&source=editors&ust=1621930682314000&usg=AOvVaw2LBWkt0BgH_4IEG_wiFjTt)

* * *

### MARKOV MODELS

Random vs Stochastic ([here](https://www.google.com/url?q=https://math.stackexchange.com/questions/114373/whats-the-difference-between-stochastic-and-random&sa=D&source=editors&ust=1621930682316000&usg=AOvVaw0LX0ZeotJz1WQtC_Z4Cuss)and [here](https://www.google.com/url?q=https://math.stackexchange.com/questions/569951/what-is-the-difference-between-a-random-vector-and-a-stochastic-process&sa=D&source=editors&ust=1621930682317000&usg=AOvVaw0XynqqstcsnR79txB4ZW0p)):

* A variable is 'random'.
* A process is 'stochastic'.

Apart from this difference the two words are synonyms

In other words:

* A random vectoris a generalization of a single random variables to many.
* A stochastic processis a sequence of random variables, or a sequence of random vectors (and then you have a vector-stochastic process).

([What is a Markov Model?)](https://www.google.com/url?q=http://cecas.clemson.edu/~ahoover/ece854/refs/Ramos-Intro-HMM.pdf&sa=D&source=editors&ust=1621930682319000&usg=AOvVaw1NOJmxc-1OeKwAdsjmXctX) A Markov Model is a stochastic(random) model which models temporal or sequential data, i.e., data that are ordered.

* It provides a way to model the dependencies of current information (e.g. weather) with previous information.
* It is composed of states, transition scheme between states, and emission of outputs (discrete or continuous).  
* Several goals can be accomplished by using Markov models:  

* Learn statistics of sequential data.
* Do prediction or estimation.  
* Recognize patterns.

([sunny cloudy explanation](https://www.google.com/url?q=http://techeffigytutorials.blogspot.co.il/2015/01/markov-chains-explained.html&sa=D&source=editors&ust=1621930682321000&usg=AOvVaw354Vlw-5fNMZL-XsVhKK2L)) Markov Chains is a probabilistic process, that relies on the current state to predict the next state.

* to be effective the current state has to be dependent on the previous state in some way
* if it looks cloudy outside, the next state we expect is rain.
* If the rain starts to subside into cloudiness, the next state will most likely be sunny.
* Not every process has the Markov Property, such as the Lottery, this weeks winning numbers have no dependence to the previous weeks winning numbers.

1.  They show how to build an order 1 markov table of probabilities, predicting the next state given the current.
2.  Then it shows the state diagram built from this table.
3.  Then how to build a transition matrix from the 3 states, i.e., from the probabilities in the table
4.  Then how to calculate the next state using the “current state vector” doing vec*matrix multiplications.
5.  Then it talks about the setting always into the rain prediction, and the solution is using two last states in a bigger table of order 2. He is not really telling us why the probabilities don't change if we add more states, it stays the same as in order 1, just repeating.
    
    * * *
    

### MARKOV MODELS / HIDDEN MARKOV MODEL

#### HMM tutorials

1.  HMM tutorial

1.  Part [1](https://www.google.com/url?q=http://gekkoquant.com/2014/05/18/hidden-markov-models-model-description-part-1-of-4/&sa=D&source=editors&ust=1621930682324000&usg=AOvVaw0yu9ULo5tD9Mny7Kpvlcmo), [2](https://www.google.com/url?q=http://gekkoquant.com/2014/05/26/hidden-markov-models-forward-viterbi-algorithm-part-2-of-4/&sa=D&source=editors&ust=1621930682325000&usg=AOvVaw2PrdkfZsX2cgRSLgJgQB8A), [3](https://www.google.com/url?q=http://gekkoquant.com/2014/09/07/hidden-markov-models-examples-in-r-part-3-of-4/&sa=D&source=editors&ust=1621930682325000&usg=AOvVaw1-5CGcSi4VzyezKnvc0fIP), [4](https://www.google.com/url?q=http://gekkoquant.com/2015/02/01/hidden-markov-models-trend-following-sharpe-ratio-3-1-part-4-of-4/&sa=D&source=editors&ust=1621930682326000&usg=AOvVaw2FcXqGMUcSvvRXzQ5U6o92)

2.  Medium

1.  [Intro to HMM](https://www.google.com/url?q=https://towardsdatascience.com/introduction-to-hidden-markov-models-cd2c93e6b781&sa=D&source=editors&ust=1621930682327000&usg=AOvVaw14xgemHoAj3dMmo780v_ZZ) / MM
2.  [Paper like example](https://www.google.com/url?q=https://medium.com/@kangeugine/hidden-markov-model-7681c22f5b9&sa=D&source=editors&ust=1621930682327000&usg=AOvVaw0Y-uN8oQR9rbeF8FQGZS4K)

3.  [HMM with sklearn and networkx](https://www.google.com/url?q=http://www.blackarbs.com/blog/introduction-hidden-markov-models-python-networkx-sklearn/2/9/2017&sa=D&source=editors&ust=1621930682328000&usg=AOvVaw2wWPD0whBpPMdig3gOmWWg)

#### HMM variants

1.  [Stack exchange on hmm](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/8460/python-library-to-implement-hidden-markov-models&sa=D&source=editors&ust=1621930682329000&usg=AOvVaw18VfgMSmQEDzC_X4TkHZSe)
2.  [HMM LEARN](https://www.google.com/url?q=https://github.com/hmmlearn/hmmlearn&sa=D&source=editors&ust=1621930682329000&usg=AOvVaw0efaiBxqkafDk65RsGFL14) (sklearn, still being developed)
3.  [Pomegranate](https://www.google.com/url?q=https://pomegranate.readthedocs.io/en/latest/&sa=D&source=editors&ust=1621930682330000&usg=AOvVaw1o_huv4am4kz6Nm8jlBFRK) (this is good)

1.  General mixture models
2.  Hmm
3.  Basyes classifiers and naive bayes
4.  Markov changes
5.  Bayesian networks
6.  Markov networks
7.  Factor graphs

4.  [GHMM with python wrappers](https://www.google.com/url?q=http://ghmm.org/&sa=D&source=editors&ust=1621930682332000&usg=AOvVaw0eNjDDg2r84q70JhdJolq4),
5.  [Hmms](https://www.google.com/url?q=https://github.com/lopatovsky/HMMs&sa=D&source=editors&ust=1621930682332000&usg=AOvVaw32o20LXF6n0AqjOGLrXhVo) (old)

HMM ([what is? And why HIDDEN?)](https://www.google.com/url?q=https://youtu.be/jY2E6ExLxaw?t%3D27m38s&sa=D&source=editors&ust=1621930682333000&usg=AOvVaw3M62MuGvIVLZPMx9YLERK4)\- the idea is that there are things that you CAN OBSERVE and there are things that you CAN'TOBSERVE. From the things you OBSERVE you want to INFER the things you CAN'TOBSERVE (HIDDEN). I.e., you play against someone else in a game, you don't see their choice of action, but you see the result.

1.  Python [code](https://www.google.com/url?q=https://github.com/hmmlearn/hmmlearn&sa=D&source=editors&ust=1621930682334000&usg=AOvVaw0cqZRXzeFa1OYNb-_84IDi), previously part of [sklearn](https://www.google.com/url?q=http://scikit-learn.sourceforge.net/stable/modules/hmm.html&sa=D&source=editors&ust=1621930682334000&usg=AOvVaw0qbw1zBri1kJgap6Czmcld)
2.  Python [seqLearn](https://www.google.com/url?q=http://larsmans.github.io/seqlearn/reference.html&sa=D&source=editors&ust=1621930682335000&usg=AOvVaw1iqA6NDEUvly1s44rBg0tY) \- supervised multinomial HMM

This youtube video [part1](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DTPRoLreU9lA&sa=D&source=editors&ust=1621930682336000&usg=AOvVaw15BFZ8Uiy8RzqXfzUlzMVc) \- explains about the hidden markov model. It shows the visual representation of the model and how we go from that the formula: ![](images/image94.png)

It  breaks down the formula to:

* transition probability formula \- the probability of going from Zk to Zk+1

* emission probability formula  \- the probability of going from Zk to Xk
* (Pi) Initial distribution - the probability of Z1=i for i=1..m

![](images/image110.png)

In [part2](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DM_IIW0VYMEA&sa=D&source=editors&ust=1621930682337000&usg=AOvVaw0qZbhxuRiMzvjxOGHJ1nMJ) of the video:

\* [HMM in weka, with github, working on 7.3, not on 9.1](https://www.google.com/url?q=http://www.doc.gold.ac.uk/~mas02mg/software/hmmweka/index.html&sa=D&source=editors&ust=1621930682338000&usg=AOvVaw3pmK5Iw1sEU0HDFPCyxknU)

1.  Probably the simplest explanation of Markov Models and HMM as a “game” - [link](https://www.google.com/url?q=http://www.fejes.ca/EasyHMM.html&sa=D&source=editors&ust=1621930682339000&usg=AOvVaw1nNBV85_Rtc-BMpXZvbTcr)
2.  This [video](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DjY2E6ExLxaw&sa=D&source=editors&ust=1621930682339000&usg=AOvVaw0eu1NBRlDWC3ZNZA0BJSbq) explains that building blocks of the needed knowledge in HMM, starting probabilities P0, transitions and emissions (state probabilities)
3.  This [post](https://www.google.com/url?q=https://www.quora.com/What-is-a-simple-explanation-of-the-Hidden-Markov-Model-algorithm&sa=D&source=editors&ust=1621930682340000&usg=AOvVaw3p4x9lLJj3W_g5oaIwR9Xv), explains HMM and ties our understanding.

[A cute explanation on quora](https://www.google.com/url?q=https://www.quora.com/What-is-a-simple-explanation-of-the-Hidden-Markov-Model-algorithm&sa=D&source=editors&ust=1621930682341000&usg=AOvVaw3H2iDKUAEy7CEYKrYG0VCg):

![](images/image257.png)

This is the iconic image of a Hidden Markov Model. There is some state (x) that changes with time (markov). And you want to estimate or track it. Unfortunately, you cannot directly observe this state (hidden). That's the hidden part. But, you can observe something correlated with the state (y).

OBSERVED DATA -> INFER -> what you CANT OBSERVE (HIDDEN).

![](images/image157.png)

Considering this model:

* where P(X0) is the initial state for happy or sad
* Where P(Xt | X t-1) is the transition model from time-1 to time
* Where P(Yt | Xt) is the observation model for happy and sad (X) in 4 situations (w, sad, crying, facebook)

![](images/image249.png)

* * *

### INPUT OUTPUT HMM (IOHMM)

1.  [Incomplete python code](https://www.google.com/url?q=https://github.com/Mogeng/IOHMM&sa=D&source=editors&ust=1621930682343000&usg=AOvVaw2IrC77qnRepghPdcxbQruB) for unsupervised / semi-supervised / supervised IOHMM - training is there, prediction is missing.
2.  [Machine learning - a probabilistic approach, david barber.](https://www.google.com/url?q=https://pdfs.semanticscholar.org/a632/9a41ee67fae978ccac1e37370f074497a4fe.pdf&sa=D&source=editors&ust=1621930682344000&usg=AOvVaw1SPnKAeCO0aD5R9IllmtNZ)

### CONDITIONAL RANDOM FIELDS (CRF)

1.  [Make sense intro to CRF, comparison against HMM](https://www.google.com/url?q=https://medium.com/ml2vec/overview-of-conditional-random-fields-68a2a20fa541&sa=D&source=editors&ust=1621930682345000&usg=AOvVaw0pfGANUAwbUVjq_xd7MItS)
2.  [HMM, CRF, MEMM](https://www.google.com/url?q=https://medium.com/@Alibaba_Cloud/hmm-memm-and-crf-a-comparative-analysis-of-statistical-modeling-methods-49fc32a73586&sa=D&source=editors&ust=1621930682345000&usg=AOvVaw2P9vPogb_tHUpPyuP8cy8T)
3.  [Another crf article](https://www.google.com/url?q=https://medium.com/@phylypo/nlp-text-segmentation-using-conditional-random-fields-e8ff1d2b6060&sa=D&source=editors&ust=1621930682346000&usg=AOvVaw0sZxBys11Qz8SrselZez2o)
4.  Neural network CRF [NNCRF](https://www.google.com/url?q=https://medium.com/@Akhilesh_k_r/neural-networks-conditional-random-field-crf-973712a0fd30&sa=D&source=editors&ust=1621930682347000&usg=AOvVaw3T1mHeCtcJ-cLu-0AHXHs5)
5.  [Another one](https://www.google.com/url?q=https://towardsdatascience.com/conditional-random-fields-explained-e5b8256da776&sa=D&source=editors&ust=1621930682347000&usg=AOvVaw2E2kRSoPEiMC9FRqz7Qpei)
6.  [scikit-learn inspired API for CRFsuite](https://www.google.com/url?q=https://github.com/TeamHG-Memex/sklearn-crfsuite&sa=D&source=editors&ust=1621930682348000&usg=AOvVaw3zXXtc7ZWUFfQYFKhwrQvk)
7.  [Sklearn wrapper](https://www.google.com/url?q=https://github.com/supercoderhawk/sklearn-crfsuite&sa=D&source=editors&ust=1621930682348000&usg=AOvVaw1L4xKdhRYCZlQW79fot8ef)
8.  [Python crfsuite](https://www.google.com/url?q=https://github.com/scrapinghub/python-crfsuite&sa=D&source=editors&ust=1621930682349000&usg=AOvVaw05zUzs3PKxiKE_5EfFXT1l) wrapper
9.  [Pycrf suite vidahya](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2018/08/nlp-guide-conditional-random-fields-text-classification/&sa=D&source=editors&ust=1621930682349000&usg=AOvVaw0GOGbCL_y4O3fbQvCFpP7w)

* * *

REGRESSION ALGORITHMS
---------------------

1.  [Sk-lego](https://www.google.com/url?q=https://scikit-lego.readthedocs.io/en/latest/preprocessing.html%23Interval-Encoders&sa=D&source=editors&ust=1621930682350000&usg=AOvVaw2Q9ZQ4DZR2iBqs9-bJHQqZ) to fit with intervals a linear regressor on top of non linear data

![](images/image235.png)

2.  Sk-lego monotonic

![](images/image96.png)

3.  [Lightning](https://www.google.com/url?q=https://github.com/scikit-learn-contrib/lightning&sa=D&source=editors&ust=1621930682351000&usg=AOvVaw1VwY-OwujzhMdRjITeP8Ol)\- lightning is a library for large-scale linear classification, regression and ranking in Python.  
    ![](images/image79.png)
4.  Linear regression TBC
5.  CART - [classification and regression tree](https://www.google.com/url?q=http://www.simafore.com/blog/bid/62482/2-main-differences-between-classification-and-regression-trees&sa=D&source=editors&ust=1621930682352000&usg=AOvVaw2VMO4PogKrIpCmTs6N1kCo), basically the diff between classification and regression trees - instead of IG we use sum squared error
6.  SVR - regression based svm, with kernel only.
7.  [NNR](https://www.google.com/url?q=https://deeplearning4j.org/linear-regression&sa=D&source=editors&ust=1621930682353000&usg=AOvVaw11dnWKfM1DKm9_HRx_u_xs)\- regression based NN, one output node
8.  [LOGREG](https://www.google.com/url?q=http://www.statisticssolutions.com/what-is-logistic-regression/&sa=D&source=editors&ust=1621930682354000&usg=AOvVaw3cfItPKAQzZiYL2jx2h0uZ) \- Logistic regression - is used as a classification algo to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables. Output is BINARY. I.e.,  If the likelihood of killing the bug is > 0.5 it is assumed dead, if it is < 0.5 it is assumed alive.

* Assumes binary outcome
* Assumes no outliers
* Assumes no intercorrelations among predictors (inputs?)

Regression Measurements:

1.  R^2 - [several reasons it can be too high.](https://www.google.com/url?q=http://blog.minitab.com/blog/adventures-in-statistics-2/five-reasons-why-your-r-squared-can-be-too-high&sa=D&source=editors&ust=1621930682355000&usg=AOvVaw22KboCdrWxFRvl7dETurf8)

1.  Too many variables
2.  Overfitting
3.  Time series - seasonality trends can cause this

* * *

### KERNEL REGRESSION

[Gaussian Kernel Regression](https://www.google.com/url?q=http://mccormickml.com/2014/02/26/kernel-regression/&sa=D&source=editors&ust=1621930682357000&usg=AOvVaw0AJouv9lsD1KdHL6jcQXxm) does–it takes a weighted average of the surrounding points

* variance, sigma^2. Informally, this parameter will control the smoothness of your approximated function.
* Smaller valuesof sigma will cause the function to overfit the data points, while larger valueswill cause it to underfit
* There is a proposed method to find sigma in the post!
* Gaussian Kernel Regression is equivalent to creating an RBF Network with the following properties: - described in the post

![](images/image91.png)
-----------------------

### DIMENSIONALITY REDUCTION

#### PRINCIPAL COMPONENT REGRESSION (PCR) / PARTIAL LEAST SQUARES (PLS)

[Principal component regression (PCR) Partial least squares and (PLS)](https://www.google.com/url?q=https://www.kdnuggets.com/2017/11/10-statistical-techniques-data-scientists-need-master.html/2&sa=D&source=editors&ust=1621930682360000&usg=AOvVaw0F54a05LTtMApPsQlf_1nY) \- basically PCA and linear regression , however PLS makes use of the response variable in order to identify the new features.

One can describe Principal Components Regression as an approach for deriving a low-dimensional set of features from a large set of variables. The first principal component direction of the data is along which the observations vary the most. In other words, the first PC is a line that fits as close as possible to the data. One can fit p distinct principal components. The second PC is a linear combination of the variables that is uncorrelated with the first PC, and has the largest variance subject to this constraint. The idea is that the principal components capture the most variance in the data using linear combinations of the data in subsequently orthogonal directions. In this way, we can also combine the effects of correlated variables to get more information out of the available data, whereas in regular least squares we would have to discard one of the correlated variables.

The PCR method that we described above involves identifying linear combinations of X that best represent the predictors. These combinations (directions) are identified in an unsupervised way, since the response Y is not used to help determine the principal component directions. That is, the response Y does not supervise the identification of the principal components, thus there is no guarantee that the directions that best explain the predictors also are the best for predicting the response (even though that is often assumed). Partial least squares (PLS) are a supervised alternative to PCR. Like PCR, PLS is a dimension reduction method, which first identifies a new smaller set of features that are linear combinations of the original features, then fits a linear model via least squares to the new M features. Yet, unlike PCR, PLS makes use of the response variable in order to identify the new features.

* * *

LABEL ALGORITHMS
================

Label Propagation / Spreading
-----------------------------

Note: very much related to weakly and semi supervision, i.e., we have small amounts of labels and we want to generalize the labels to other samples, see also weak supervision methods.

1.  Step 1: [build a laplacian](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Laplacian_matrix&sa=D&source=editors&ust=1621930682363000&usg=AOvVaw1k21bUVRtG8NeG7-CHRGOE) graph using KNN, distance metric is minkowski with p=2, i.e. euclidean distance.
2.  [Step by step tutorial](https://www.google.com/url?q=https://medium.com/@graphml/introduction-to-label-propagation-with-networkx-part-1-abcbe954a2e8&sa=D&source=editors&ust=1621930682364000&usg=AOvVaw2yP_Ek6Q7Lz5h7P1s3dD82), [part 2](https://www.google.com/url?q=https://medium.com/@graphml/introduction-to-label-propagation-with-networkx-part-2-cd041fa44e1&sa=D&source=editors&ust=1621930682364000&usg=AOvVaw3fsgs4BqrvY5BF6UVMazNq)
3.  [Spreading](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.semi_supervised.LabelSpreading.html&sa=D&source=editors&ust=1621930682365000&usg=AOvVaw1jmh7GbYJ5bIBub7ihVmVH) (propagation upgrade), Essentially a community graph algorithm, however it resembles KNN in its nature, using semi supervised data set (i.e., labeled and unlabeled data) to spread or propagate labels to unlabeled data, with small incrementations in the algorithm, using KNN-like methodology, each unlabeled sample will be given a label based on its 1st order friends, if there is a tie, a random label is chosen. Nodes are connected by using a euclidean distance.
4.  [Difference](https://www.google.com/url?q=https://www.researchgate.net/post/What_is_the_difference_between_Label_propagation_and_Label_spreading_in_semi-supervised_learning_context&sa=D&source=editors&ust=1621930682365000&usg=AOvVaw3CE2ACv3qy_3eR7ARi-paE) between propagation and spreading is a laplacian matrix, vs normalized LM
5.  [Laplacian matrix on youtube, videos 30-33](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DsiCPjpUtE0A%26list%3DPLLssT5z_DsK9JDLcT8T62VtzwyW9LNepV%26index%3D33&sa=D&source=editors&ust=1621930682366000&usg=AOvVaw3j6gx5zRdoE_qIHA3Xfl0q)
6.  [Really good example notebook](https://www.google.com/url?q=https://github.com/DavidBrear/sklearn-cookbook/blob/master/Chapter%25204/4.1.1%2520Label%2520Propagation%2520with%2520Semi-Supervised%2520Learning.ipynb&sa=D&source=editors&ust=1621930682367000&usg=AOvVaw0ggwPzLz_BUUSpoW4Ip2sw)
7.  [Spreading vs propagation](https://www.google.com/url?q=https://www.researchgate.net/post/What_is_the_difference_between_Label_propagation_and_Label_spreading_in_semi-supervised_learning_context&sa=D&source=editors&ust=1621930682367000&usg=AOvVaw2rjtOSlFp8CNrYHygYssSk)
8.  [https://en.wikipedia.org/wiki/Label\_Propagation\_Algorithm](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Label_Propagation_Algorithm&sa=D&source=editors&ust=1621930682368000&usg=AOvVaw2Y5R_9BF6u5epnavhnq9UH)
9.  Youtube [1](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DUWf8hxeehOg&sa=D&source=editors&ust=1621930682368000&usg=AOvVaw2IJYKUONtnqKWs20FFd_x6), [2](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DhmashUPJwSQ&sa=D&source=editors&ust=1621930682369000&usg=AOvVaw2oMjpGjump9RNfgt0jVXr3), [3](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DF4f247IyOTs&sa=D&source=editors&ust=1621930682369000&usg=AOvVaw0IYScY20jqAMPFm5ZOmklI),
10. [Medium](https://www.google.com/url?q=https://medium.com/@graphml/introduction-to-label-propagation-with-networkx-part-1-abcbe954a2e8&sa=D&source=editors&ust=1621930682370000&usg=AOvVaw0gMJHSDSH52uLmz8ZR2mI_),
11. [Sklearn](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/label_propagation.html&sa=D&source=editors&ust=1621930682370000&usg=AOvVaw0O4dZeziyEPxe8eGaw4ET_), [1](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.semi_supervised.LabelPropagation.html&sa=D&source=editors&ust=1621930682371000&usg=AOvVaw0l0kSzt8DacN1D47W4h4R8), [2](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/generated/sklearn.semi_supervised.LabelPropagation.html&sa=D&source=editors&ust=1621930682371000&usg=AOvVaw0l0kSzt8DacN1D47W4h4R8), [3](https://www.google.com/url?q=https://scikit-learn.org/stable/auto_examples/semi_supervised/plot_label_propagation_digits.html&sa=D&source=editors&ust=1621930682371000&usg=AOvVaw1bGEmKD_Su1IeiersYwGzV), [4](https://www.google.com/url?q=https://plot.ly/scikit-learn/plot-label-propagation-structure/&sa=D&source=editors&ust=1621930682372000&usg=AOvVaw3eZcWFiQdkDW02nvTVWFFk), 5,

![](images/image83.png)

12. [Git](https://www.google.com/url?q=https://github.com/benedekrozemberczki/LabelPropagation&sa=D&source=editors&ust=1621930682372000&usg=AOvVaw228JJf5GgzSAxmP5QH3gM5), [incremental LP](https://www.google.com/url?q=https://github.com/johny-c/incremental-label-propagation&sa=D&source=editors&ust=1621930682373000&usg=AOvVaw2lfZWNLi1yHmMRgIjCv31G)
13. [Git2](https://www.google.com/url?q=https://github.com/yamaguchiyuto/label_propagation%255C&sa=D&source=editors&ust=1621930682373000&usg=AOvVaw0d0Eieo8Cz_5jLc7ir6ypB)

1.  Harmonic Function (HMN) \[Zhu+, ICML03\]
2.  Local and Global Consistency (LGC) \[Zhou+, NIPS04\]
3.  Partially Absorbing Random Walk (PARW) \[Wu+, NIPS12\]
4.  OMNI-Prop (OMNIProp) \[Yamaguchi+, AAAI15\]
5.  Confidence-Aware Modulated Label Propagation (CAMLP) \[Yamaguchi+, SDM16\]

![](images/image218.png)

15. Presentation [1](https://www.google.com/url?q=http://www.leonidzhukov.net/hse/2015/networks/lectures/lecture17.pdf&sa=D&source=editors&ust=1621930682375000&usg=AOvVaw2couU73yoJgSIM-wYSr_bY),[2](https://www.google.com/url?q=https://www.slideshare.net/dav009/label-propagation-semisupervised-learning-with-applications-to-nlp&sa=D&source=editors&ust=1621930682375000&usg=AOvVaw3fFyz1-0Xr2XuCtZzWnLSM)
16. Neo4j [1](https://www.google.com/url?q=https://dzone.com/articles/graph-algorithms-in-neo4j-label-propagation&sa=D&source=editors&ust=1621930682376000&usg=AOvVaw0Azf8HxdZinfesylLwdSlP), 2, 3,
    
    * * *
    

CLUSTERING ALGORITHMS
=====================

1.  [Vidhya on clustering and methods](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2016/11/an-introduction-to-clustering-and-different-methods-of-clustering/?utm_source%3Dfacebook.com&sa=D&source=editors&ust=1621930682377000&usg=AOvVaw0yb2vQLSLheZaUwYyc4i1E)
2.  [KNN](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D4ObVzTuFivY&sa=D&source=editors&ust=1621930682378000&usg=AOvVaw182VRvRAj7wn497O4OCe0A)[intuition 2](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DUqYde-LULfs&sa=D&source=editors&ust=1621930682378000&usg=AOvVaw3iIO4cMq7kRkWaOmzY92EQ), [thorough explanation 3](https://www.google.com/url?q=https://towardsdatascience.com/introduction-to-k-nearest-neighbors-3b534bb11d26&sa=D&source=editors&ust=1621930682378000&usg=AOvVaw1WJi3qgmIkFR3d2FwhycZZ)  \- classify a new sample by looking at the majority vote of its K-nearest neighbours. k=1 special case. Even amount of classes needs an odd K that is not a multiple of the amount of classes in order to break ties.

3.  [Determinging the number of clusters, a comparison of several methods, elbow, silhouette etc](https://www.google.com/url?q=https://www.datanovia.com/en/lessons/determining-the-optimal-number-of-clusters-3-must-know-methods/&sa=D&source=editors&ust=1621930682379000&usg=AOvVaw0MHM6GyOp8Fpp6hh6lo9vT)
4.  [A good visual example of kmeans / gmm](https://www.google.com/url?q=https://medium.com/sfu-cspmp/distilling-gaussian-mixture-models-701fa9546d9&sa=D&source=editors&ust=1621930682380000&usg=AOvVaw1evpyvPLmTg9BkeK5cUkJh)
5.  [Kmeans with DTW, probably fixed length vectors, using tslearn](https://www.google.com/url?q=https://towardsdatascience.com/how-to-apply-k-means-clustering-to-time-series-data-28d04a8f7da3&sa=D&source=editors&ust=1621930682380000&usg=AOvVaw3B2-tt5BZrPkaOt0EcJycI)
6.  [Kmeans for variable length](https://www.google.com/url?q=https://medium.com/@iliazaitsev/how-to-classify-a-dataset-with-observations-of-various-length-96fab8e95baf&sa=D&source=editors&ust=1621930682381000&usg=AOvVaw1Z3kD8gJjB_KzpiBgD29up), [notebook](https://www.google.com/url?q=https://github.com/devforfu/Blog/blob/master/trees/scikit_learn.py&sa=D&source=editors&ust=1621930682381000&usg=AOvVaw1OEnpBkY89gi2G1cfTTXAH)

TOOLS

1.  [pyClustering](https://www.google.com/url?q=https://pyclustering.github.io/docs/0.10.1/html/index.html&sa=D&source=editors&ust=1621930682382000&usg=AOvVaw1fM4vGcVrD28S4rZglBlSi)  
    ![](images/image210.png)

* * *

Block Modeling - Distance Matrices
----------------------------------

1.  [Biclustering and spectral co clustering](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/biclustering.html&sa=D&source=editors&ust=1621930682383000&usg=AOvVaw3f2WipwPjTc67JuYY30b7Z)

2.  [Clustering correlation, or distance matrices.](https://www.google.com/url?q=https://stats.stackexchange.com/questions/138325/clustering-a-correlation-matrix&sa=D&source=editors&ust=1621930682383000&usg=AOvVaw1dKDuHmQ24M66--9KlgtMT)

![](images/image42.png)

3.  Any of the “precomputed” algorithms in sklearn, just remember to [do 1-distanceMatrix](https://www.google.com/url?q=https://github.com/scikit-learn/scikit-learn/issues/6787&sa=D&source=editors&ust=1621930682384000&usg=AOvVaw0wvZx40v4QF7wOgpgHsXX4). I.e., using dbscan/hdbscan/optics, you need a dissimilarity matrix.

[Kmeans](https://www.google.com/url?q=https://github.com/jakevdp/sklearn_pycon2015/blob/master/notebooks/04.2-Clustering-KMeans.ipynb&sa=D&source=editors&ust=1621930682385000&usg=AOvVaw0B12_2a9ga7uiKkNMdHKnt)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.  Sensitive to outliers, can skew results (because we rely on the mean)

[K-mediods](https://www.google.com/url?q=https://en.wikipedia.org/wiki/K-medoids&sa=D&source=editors&ust=1621930682385000&usg=AOvVaw0tTDzAe4a-kdJg0kL-x9ET)
-----------------------------------------------------------------------------------------------------------------------------------------------------------

\- basically k-means with a most center object rather than a center virtual point that was based on mean distance from all points, we keep choosing medoids samples based on minimised SSE

* k-medoid is a classical partitioning technique of clustering that clusters the data set of nobjects into kclusters known a priori.
* It is more robust to noise and outliers as compared to [k](https://www.google.com/url?q=https://en.wikipedia.org/wiki/K-means&sa=D&source=editors&ust=1621930682386000&usg=AOvVaw0TRGzKcpxwJNJypNtd6Dm3)[-means](https://www.google.com/url?q=https://en.wikipedia.org/wiki/K-means&sa=D&source=editors&ust=1621930682386000&usg=AOvVaw0TRGzKcpxwJNJypNtd6Dm3) because it minimizes a sum of pairwise dissimilarities instead of a sum of squared Euclidean distances.
* A [medoid](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Medoid&sa=D&source=editors&ust=1621930682387000&usg=AOvVaw3fmb25DSmqEINfTygofykL) can be defined as the object of a cluster whose average dissimilarity to all the objects in the cluster is minimal. i.e. it is a most centrally located point in the cluster.
* Does Not scale to many samples, its O(K*n-K)^2
* Randomized resampling can assure efficiency and quality.

[From youtube (okay video)](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DOWpRBCrx5-M&sa=D&source=editors&ust=1621930682388000&usg=AOvVaw0jy0Ef5DsTYBB4myVnCjQt)

![](images/image155.png)

X-means![](images/image92.png)
------------------------------

X-means([paper](https://www.google.com/url?q=https://www.cs.cmu.edu/~dpelleg/download/xmeans.pdf&sa=D&source=editors&ust=1621930682389000&usg=AOvVaw3GsM7PNlHGI-vzOtEqbg-6)):

1.  [Theory](https://www.google.com/url?q=https://stats.stackexchange.com/questions/13103/x-mean-algorithm-bic-calculation-question&sa=D&source=editors&ust=1621930682390000&usg=AOvVaw1dxtpkiFHZmZVfMw-MwGzY) behind bic calculation with a formula.
2.  Code: [Calculate bic in k-means](https://www.google.com/url?q=https://stats.stackexchange.com/questions/90769/using-bic-to-estimate-the-number-of-k-in-kmeans?rq%3D1&sa=D&source=editors&ust=1621930682391000&usg=AOvVaw36VezR7aggx1Pl5wZyJO8t)

![](images/image1.png)

G-means
-------

G-means [Improves on X-means](https://www.google.com/url?q=https://papers.nips.cc/paper/2526-learning-the-k-in-k-means.pdf&sa=D&source=editors&ust=1621930682392000&usg=AOvVaw1bKzMzaG-wTH2g94idecRH)in the paper: The G-means algorithm starts with a small number of k-means centers, and grows the number of centers. Each iteration of the algorithm splits into two those centers whose data appear not to come from a Gaussian distribution using the Anderson Darling test. Between each round of splitting, we run k-means on the entire dataset and all the centers to refine the current solution. We can initialize with just k = 1, or we can choose some larger value of k if we have some prior knowledge about the range of k. G-means repeatedly makes decisions based on a statistical test for the data assigned to each enter. If the data currently assigned to a k-means center appear to be Gaussian, then we want to represent that data with only one center.

![](images/image68.png)

* * *

GMM - Gaussian Mixture Models
-----------------------------

?\- [What is GMM](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/14435/how-to-get-the-probability-of-belonging-to-clusters-for-k-means&sa=D&source=editors&ust=1621930682394000&usg=AOvVaw33PuMYNmFZmL43n0jQRS6j) in short its knn with mean/variance centroids, a sample can be in several centroids with a certain probability.

Let us briefly talk about a probabilistic generalisation of k-means: the [Gaussian Mixture Model](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Mixture_model&sa=D&source=editors&ust=1621930682395000&usg=AOvVaw1YmyK8K7KJEo59cMl2OYG1)(GMM).

In k-means, you carry out the following procedure:

\- specify k centroids, initialising their coordinates randomly

\- calculate the distance of each data point to each centroid

\- assign each data point to its nearest centroid

\- update the coordinates of the centroid to the mean of all points assigned to it

\- iterate until convergence.

In a GMM, you carry out the following procedure:

\- specify k multivariate Gaussians (termed components), initialising their mean and variance randomly

\- calculate the probability of each data point being produced by each component (sometimes termed the responsibility each component takes for the data point)

\- assign each data point to the component it belongs to with the highest probability

\- update the mean and variance of the component to the mean and variance of all data points assigned to it

\- iterate until convergence

You may notice the similarity between these two procedures. In fact, k-means is a GMM with fixed-variance components. Under a GMM, the probabilities (I think) you're looking for are the responsibilities each component takes for each data point.

1.  [Gmm code on sklearn](https://www.google.com/url?q=https://scikit-learn.org/stable/auto_examples/mixture/plot_gmm.html%23sphx-glr-auto-examples-mixture-plot-gmm-py&sa=D&source=editors&ust=1621930682398000&usg=AOvVaw0QXInKyw3LDYRcKoCGm7O7) using ellipsoids
2.  [How to select the K  using bic](https://www.google.com/url?q=https://scikit-learn.org/stable/auto_examples/mixture/plot_gmm_selection.html%23sphx-glr-auto-examples-mixture-plot-gmm-selection-py&sa=D&source=editors&ust=1621930682398000&usg=AOvVaw2MKcyAwKN1iP0k_s7NhaR1)
3.  [Density estimation for gmm - nice graph](https://www.google.com/url?q=https://scikit-learn.org/stable/auto_examples/mixture/plot_gmm_pdf.html%23sphx-glr-auto-examples-mixture-plot-gmm-pdf-py&sa=D&source=editors&ust=1621930682399000&usg=AOvVaw0FLS6T5YIRC8y24gA8u25r)
    
    * * *
    

KMEANS++ / Kernel Kmeans
------------------------

1.  [A comparison of kmeans++ vs kernel kmeans](https://www.google.com/url?q=https://sandipanweb.wordpress.com/2016/08/29/kernel-k-means-and-cluster-evaluation/&sa=D&source=editors&ust=1621930682401000&usg=AOvVaw1CFN8KwfcE_oiCURanTJBk)
2.  [Kernel Kmeans is part of TSLearn](https://www.google.com/url?q=http://tslearn.readthedocs.io/en/latest/gen_modules/clustering/tslearn.clustering.GlobalAlignmentKernelKMeans.html&sa=D&source=editors&ust=1621930682401000&usg=AOvVaw2JGeFHGyEaSLaAbBrVSSTw)
3.  [Elbow method](https://www.google.com/url?q=https://blog.cambridgespark.com/how-to-determine-the-optimal-number-of-clusters-for-k-means-clustering-14f27070048f&sa=D&source=editors&ust=1621930682402000&usg=AOvVaw0RSAHcjCDzkYCvthuJ-XPv),
4.  [elbow and mean silhouette](https://www.google.com/url?q=https://www.datanovia.com/en/lessons/determining-the-optimal-number-of-clusters-3-must-know-methods/%23elbow-method&sa=D&source=editors&ust=1621930682403000&usg=AOvVaw1CaN6-hAep9Cuga86ra0iF),
5.  [elbow on medium using mean distance per cluster from the center](https://www.google.com/url?q=https://towardsdatascience.com/what-is-k-ddf36926a752&sa=D&source=editors&ust=1621930682403000&usg=AOvVaw0TpHVFJu1ZnhK7FS6nslx_)
6.  [Kneed a library to find the knee in a curve](https://www.google.com/url?q=https://github.com/arvkevi/kneed&sa=D&source=editors&ust=1621930682404000&usg=AOvVaw15FE4dFzOYPeGift_aPvN5)

KNN
---

1.  [Nearpy](https://www.google.com/url?q=https://github.com/pixelogik/NearPy&sa=D&source=editors&ust=1621930682405000&usg=AOvVaw0p3QCi86f8KjLmpVFMNj98), knn in scale! On github

* * *

DBSCAN
------

1.  [How to use effectively](https://www.google.com/url?q=https://towardsdatascience.com/how-to-use-dbscan-effectively-ed212c02e62&sa=D&source=editors&ust=1621930682406000&usg=AOvVaw0OCCBbwhJEeqzHyYwpB2lM)
2.  [a DBSCAN visualization - very good!](https://www.google.com/url?q=https://www.naftaliharris.com/blog/visualizing-dbscan-clustering/&sa=D&source=editors&ust=1621930682407000&usg=AOvVaw29ixGJytsjrA6kC9gY7XXm)
3.  [DBSCAN for GPS.](https://www.google.com/url?q=https://geoffboeing.com/2014/08/clustering-to-reduce-spatial-data-set-size/&sa=D&source=editors&ust=1621930682407000&usg=AOvVaw3gPldwuLF3NF1ab9c8SvIu)
4.  [A practical guide to dbscan - pretty good](https://www.google.com/url?q=https://towardsdatascience.com/a-practical-guide-to-dbscan-method-d4ec5ab2bc99&sa=D&source=editors&ust=1621930682408000&usg=AOvVaw2dIkTnwi0gOZoqUHbBNS5S)
5.  [Custom DBSCAN  “predict”](https://www.google.com/url?q=https://stackoverflow.com/questions/27822752/scikit-learn-predicting-new-points-with-dbscan&sa=D&source=editors&ust=1621930682409000&usg=AOvVaw2XMdzraiEmFdREpkYB72GX)
6.  [Haversine distances for](https://www.google.com/url?q=https://kanoki.org/2019/12/27/how-to-calculate-distance-in-python-and-pandas-using-scipy-spatial-and-distance-functions/&sa=D&source=editors&ust=1621930682409000&usg=AOvVaw14BFsBr5NV1hAqYyehsbiH) dbscan
7.  Optimized dbscans:

1.  [muDBSCAN](https://www.google.com/url?q=https://githubmemory.com/repo/AdityaAS/MuDBSCAN&sa=D&source=editors&ust=1621930682410000&usg=AOvVaw1oU4YFELdGwvOoCOiKOLT_), [paper](https://www.google.com/url?q=https://adityaas.github.io/&sa=D&source=editors&ust=1621930682410000&usg=AOvVaw3ZrtdTU5Rr7LJOSPvlCb7U)\- A fast, exact, and scalable algorithm for DBSCAN clustering. This repository contains the implementation for the distributed spatial clustering algorithm proposed in the paper μDBSCAN: An Exact Scalable DBSCAN Algorithm for Big Data Exploiting Spatial Locality
2.  [Dbscan multiplex](https://www.google.com/url?q=https://github.com/GGiecold/DBSCAN_multiplex&sa=D&source=editors&ust=1621930682411000&usg=AOvVaw0qcR9Qwjp3s8JJKqh3QUmz) \- A fast and memory-efficient implementation of DBSCAN (Density-Based Spatial Clustering of Applications with Noise).
3.  [Fast dbscan](https://www.google.com/url?q=https://github.com/harmslab/fast_dbscan&sa=D&source=editors&ust=1621930682411000&usg=AOvVaw2wUteTyRcZYZ-6Ak1ZCxvM) \- A lightweight, fast dbscan implementation for use on peptide strings. It uses pure C for the distance calculations and clustering. This code is then wrapped in python.
4.  [Faster dbscan paper](https://www.google.com/url?q=https://arxiv.org/pdf/1702.08607.pdf&sa=D&source=editors&ust=1621930682412000&usg=AOvVaw2aHXF_e0bQXXhzByAC43Ij)

ST-DBSCAN
---------

1.  [Paper - st-dbscan an algo for clustering spatio temporal data](https://www.google.com/url?q=https://www.sciencedirect.com/science/article/pii/S0169023X06000218&sa=D&source=editors&ust=1621930682413000&usg=AOvVaw2_thy4BLIriLl7bjjwceWR)
2.  [Popular git](https://www.google.com/url?q=https://github.com/eubr-bigsea/py-st-dbscan&sa=D&source=editors&ust=1621930682413000&usg=AOvVaw2nlu5Rga3QIMAyOvIz2rjT)
3.  [git](https://www.google.com/url?q=https://github.com/gitAtila/ST-DBSCAN&sa=D&source=editors&ust=1621930682414000&usg=AOvVaw39s3No66bptL-rwXnPUlgE)

HDBSCAN*
--------

(what is?) HDBSCAN is a clustering algorithm developed by [Campello, Moulavi, and Sander](https://www.google.com/url?q=http://link.springer.com/chapter/10.1007%252F978-3-642-37456-2_14&sa=D&source=editors&ust=1621930682415000&usg=AOvVaw0hQ9NmSOj7ZpSqjaFXcZ9U). It extends DBSCAN by converting it into a hierarchical clustering algorithm, and then using a technique to extract a flat clustering based in the stability of clusters.

* [Github code](https://www.google.com/url?q=https://github.com/scikit-learn-contrib/hdbscan&sa=D&source=editors&ust=1621930682415000&usg=AOvVaw1p7LUlg2hCsjhUia4g76ar)
* (great) [Documentation](https://www.google.com/url?q=http://hdbscan.readthedocs.io/en/latest/basic_hdbscan.html&sa=D&source=editors&ust=1621930682416000&usg=AOvVaw2x61UKzY2Vxlg5Mlo9JB3I)  with examples, for clustering, outlier detection, comparison, benchmarking and analysis!
* ([jupytr example](https://www.google.com/url?q=http://nbviewer.jupyter.org/github/scikit-learn-contrib/hdbscan/blob/master/notebooks/How%2520HDBSCAN%2520Works.ipynb&sa=D&source=editors&ust=1621930682417000&usg=AOvVaw2lQM0hKlUww-fjCiVPAp4k)) \- take a look and see how to use it, usage examples are also in the docs and github

What are the algorithm’s [steps](https://www.google.com/url?q=http://nbviewer.jupyter.org/github/scikit-learn-contrib/hdbscan/blob/master/notebooks/How%2520HDBSCAN%2520Works.ipynb&sa=D&source=editors&ust=1621930682417000&usg=AOvVaw2lQM0hKlUww-fjCiVPAp4k):

1.  Transform the space according to the density/sparsity.
2.  Build the minimum spanning tree of the distance weighted graph.
3.  Construct a cluster hierarchy of connected components.
4.  Condense the cluster hierarchy based on minimum cluster size.
5.  Extract the stable clusters from the condensed tree.

OPTICS
------

([What is?](https://www.google.com/url?q=https://en.wikipedia.org/wiki/OPTICS_algorithm&sa=D&source=editors&ust=1621930682419000&usg=AOvVaw2zMEdowKqA4CPTsPUnW2c5)) Ordering points to identify the clustering structure (OPTICS) is an algorithm for finding density-based[\[1\]](https://www.google.com/url?q=https://en.wikipedia.org/wiki/OPTICS_algorithm%23cite_note-1&sa=D&source=editors&ust=1621930682420000&usg=AOvVaw1myXg3mUSLwq_R5pBMHEwp)[clusters](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Cluster_analysis&sa=D&source=editors&ust=1621930682421000&usg=AOvVaw0QcR2oFFbmq_A_mtqD8Zen) in spatial data

* Its basic idea is similar to [DBSCAN](https://www.google.com/url?q=https://en.wikipedia.org/wiki/DBSCAN&sa=D&source=editors&ust=1621930682421000&usg=AOvVaw00M6SLkKwLLX5kQivrugNy),[\[3\]](https://www.google.com/url?q=https://en.wikipedia.org/wiki/OPTICS_algorithm%23cite_note-3&sa=D&source=editors&ust=1621930682422000&usg=AOvVaw1zC7ctukyyVSuyS2vhaE0k)
* it addresses one of DBSCAN's major weaknesses: the problem of detecting meaningful clusters in data of varying density.
* (How?) the points of the database are (linearly) ordered such that points which are spatially closest become neighbors in the ordering.
* a special distance is stored for each point that represents the density that needs to be accepted for a cluster in order to have both points belong to the same cluster. (This is represented as a [dendrogram](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Dendrogram&sa=D&source=editors&ust=1621930682423000&usg=AOvVaw2A2u5Y9lWEBeo7HLZMOdfV).)

SVM CLUSTERING
--------------

[Paper](https://www.google.com/url?q=https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2099486/%23:~:text%3DAn%2520SVM%252Dbased%2520clustering%2520algorithm,until%2520an%2520initial%2520convergence%2520occurs.&sa=D&source=editors&ust=1621930682424000&usg=AOvVaw3iWZ6rrPgXvjliRY1RL0dN)

An SVM-based clustering algorithm is introduced that clusters data with no a priori knowledge of input classes.

1.  The algorithm initializes by first running a binary SVM classifier against a data set with each vector in the set randomly labelled, this is repeated until an initial convergence occurs.
2.  Once this initialization step is complete, the SVM confidence parameters for classification on each of the training instances can be accessed.
3.  The lowest confidence data (e.g., the worst of the mislabelled data) then has its' labels switched to the other class label.
4.  The SVM is then re-run on the data set (with partly re-labelled data) and is guaranteed to converge in this situation since it converged previously, and now it has fewer data points to carry with mislabelling penalties.
5.  This approach appears to limit exposure to the local minima traps that can occur with other approaches. Thus, the algorithm then improves on its weakly convergent result by SVM re-training after each re-labeling on the worst of the misclassified vectors – i.e., those feature vectors with confidence factor values beyond some threshold.
6.  The repetition of the above process improves the accuracy, here a measure of separability, until there are no misclassifications. Variations on this type of clustering approach are shown.
    
    * * *
    

COP-CLUSTERING
--------------

Constrained K-means algorithm, [git](https://www.google.com/url?q=https://github.com/Behrouz-Babaki/COP-Kmeans&sa=D&source=editors&ust=1621930682427000&usg=AOvVaw0wK8xICiL9LqBkczv04BQl), [paper](https://www.google.com/url?q=https://web.cse.msu.edu/~cse802/notes/ConstrainedKmeans.pdf&sa=D&source=editors&ust=1621930682427000&usg=AOvVaw0vHxtO8JGaEixdP8llaO-3), is a semi-supervised algorithm.

Clustering is traditionally viewed as an unsupervised method for data analysis. However, in some cases information about the problem domain is available in addition to the data instances themselves. In this paper, we demonstrate how the popular k-means clustering algorithm can be profitably modified to make use of this information. In experiments with artificial constraints on six data sets, we observe improvements in clustering accuracy. We also apply this method to the real-world problem of automatically detecting road lanes from GPS data and observe dramatic increases in performance.  

In the context of partitioning algorithms, instance level constraints are a useful way to express a priori knowledge about which instances should or should not be grouped together. Consequently, we consider two types of pairwise constraints:  
• Must-link constraints specify that two instances have to be in the same cluster.  
• Cannot-link constraints specify that two instances must not be placed in the same cluster.

![](images/image27.png)

* * *


--------------------------------

ANOMALY DETECTION
=================

“whether a new observation belongs to the same distribution as existing observations (it is an inlier), or should be considered as different (it is an outlier). “

=\> Often, this ability is used to clean real data sets

Two important distinction must be made:

|     |     |
| --- | --- |
| novelty detection: |     |
|     | The training data is not polluted by outliers, and we are interested in detecting anomalies in new observations. |
| outlier detection: |     |
|     | The training data contains outliers, and we need to fit the central mode of the training data, ignoring the deviant observations |

1.  [Medium](https://www.google.com/url?q=https://towardsdatascience.com/anomaly-detection-for-dummies-15f148e559c1%23:~:text%3DK%2520%252D%2520Nearest%2520Neighbors%2520(KNN),algorithms%2520were%2520not%2520very%2520different.&sa=D&source=editors&ust=1621930682434000&usg=AOvVaw1ATEHLS_PACXdiJrsDnu68) \- good
2.  [kdnuggets](https://www.google.com/url?q=https://www.kdnuggets.com/2017/04/datascience-introduction-anomaly-detection.html&sa=D&source=editors&ust=1621930682435000&usg=AOvVaw25RpijcbC29-sFkiIQhNyF)
3.  Index for [Z-score and other moving averages.](https://www.google.com/url?q=https://turi.com/learn/userguide/anomaly_detection/moving_zscore.html&sa=D&source=editors&ust=1621930682436000&usg=AOvVaw1-gsjQQxtbE12CKBGUJkXe)
4.  [A survey](https://www.google.com/url?q=https://d1wqtxts1xzle7.cloudfront.net/49916547/Mohiuddin_Survey_financial_2015.pdf?1477591055%3D%26response-content-disposition%3Dinline%253B%2Bfilename%253DA_survey_of_anomaly_detection_techniques.pdf%26Expires%3D1594649751%26Signature%3DU~N32meGWYyIIQz1zRYC4s2tCb7e5ut28GIBC3GSG4250UjhgTMQwEIB63zwPKtS5JyKew7RWVog8gytIhc3GSSfTwsRM7lqyghuDgbds-QMp3mNyVw2bYNztnoOWncHG8rhtkwUK1EbWcYeLKvqARnJoAS177C8r1GAhfKp14GgJzHpmnsoSkB6AowJ68nauf2VyA1b~w1m~UfSNoWtjbL59clAqHn7nfqw5PGBuLHSSSxCa5PX09mADy4VzuOySzYjIviRwOlgT1eQrART0KqozqVSiGKM3SeapuI3K5tSERVPPSTnpupp--WJyYCNzzvPrdjB121P2XU7fq73wQ__%26Key-Pair-Id%3DAPKAJLOHF5GGSLRBV4ZA&sa=D&source=editors&ust=1621930682437000&usg=AOvVaw3caL3iGWYgOczP15ik57yk)

5.  [A great tutorial](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2019/02/outlier-detection-python-pyod/?utm_source%3Dfacebook.com%26utm_medium%3Dsocial%26fbclid%3DIwAR33KDnGMf5zp491WmhTsCFtinBDUp5RaVnoC4Cfxcc5rfo2yHreMo3M_M4&sa=D&source=editors&ust=1621930682438000&usg=AOvVaw2CnxDTxXAhxj035aEAaPj_)about AD using 20 algos in a [single python package](https://www.google.com/url?q=https://github.com/yzhao062/pyod&sa=D&source=editors&ust=1621930682438000&usg=AOvVaw1aEBvJVDoQm5rkL9d72TR9).
6.  [Mastery on classifying rare events using lstm-autoencoder](https://www.google.com/url?q=https://machinelearningmastery.com/lstm-model-architecture-for-rare-event-time-series-forecasting/&sa=D&source=editors&ust=1621930682439000&usg=AOvVaw1X09VNcL24L9dOg9DrC46H)
7.  A [comparison](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/outlier_detection.html%23outlier-detection&sa=D&source=editors&ust=1621930682440000&usg=AOvVaw3Sr3laiysjUqfLPWj-f0sv) of One-class SVM versus Elliptic Envelope versus Isolation Forest versus LOF in sklearn. (The examples below illustrate how the performance of the [covariance.EllipticEnvelope](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.covariance.EllipticEnvelope.html%23sklearn.covariance.EllipticEnvelope&sa=D&source=editors&ust=1621930682440000&usg=AOvVaw2pCTNKjtmGNaLCSjQ6uxfS)degrades as the data is less and less unimodal. The [svm.OneClassSVM](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.svm.OneClassSVM.html%23sklearn.svm.OneClassSVM&sa=D&source=editors&ust=1621930682441000&usg=AOvVaw29SEnD3EXYUbB_WjUQDs8M)works better on data with multiple modes and [ensemble.IsolationForest](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html%23sklearn.ensemble.IsolationForest&sa=D&source=editors&ust=1621930682441000&usg=AOvVaw2OfLgvQQ92e-rOwLvOy5iA) and[neighbors.LocalOutlierFactor](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.LocalOutlierFactor.html%23sklearn.neighbors.LocalOutlierFactor&sa=D&source=editors&ust=1621930682442000&usg=AOvVaw0S97MUBCi1f91lxocqq0yy) perform well in every cases.)
8.  [Using Autoencoders](https://www.google.com/url?q=https://shiring.github.io/machine_learning/2017/05/01/fraud&sa=D&source=editors&ust=1621930682442000&usg=AOvVaw0s1Y2DXooo_KtTdGxyxO59) \- the information is there, but its all over the place.
9.  Twitter anomaly -
10. Microsoft anomaly - a well documented black box, i cant find a description of the algorithm, just hints to what they sort of did

1.  [up/down trend, dynamic range, tips and dips](https://www.google.com/url?q=https://blogs.technet.microsoft.com/machinelearning/2014/11/05/anomaly-detection-using-machine-learning-to-detect-abnormalities-in-time-series-data/&sa=D&source=editors&ust=1621930682443000&usg=AOvVaw0dwWN2n5JnJONOSr9TltgE)
2.  [Api here](https://www.google.com/url?q=https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/apps-anomaly-detection-api&sa=D&source=editors&ust=1621930682444000&usg=AOvVaw0v4aqum56kEwGRf7YEREq5)

11. STL and [LSTM for anomaly prediction](https://www.google.com/url?q=https://github.com/omri374/moda/blob/master/moda/example/lstm/LSTM_AD.ipynb&sa=D&source=editors&ust=1621930682445000&usg=AOvVaw3RkXUL6qszN7wuWl2tD_2i) by microsoft

1.  [Medium on AD](https://www.google.com/url?q=https://towardsdatascience.com/machine-learning-for-anomaly-detection-and-condition-monitoring-d4614e7de770&sa=D&source=editors&ust=1621930682445000&usg=AOvVaw1TuFTTq9HqUqMrbnpGDMry)
2.  [Medium on AD using mahalanobis, AE and](https://www.google.com/url?q=https://towardsdatascience.com/how-to-use-machine-learning-for-anomaly-detection-and-condition-monitoring-6742f82900d7&sa=D&source=editors&ust=1621930682446000&usg=AOvVaw21xvkfKTeTYcyehJSYrXBt)

* * *

OUTLIER DETECTION
-----------------

1.  [Alibi Detect](https://www.google.com/url?q=https://github.com/SeldonIO/alibi-detect&sa=D&source=editors&ust=1621930682447000&usg=AOvVaw1xCIUhcex2OBO8y_ZKweRJ) is an open source Python library focused on outlier, adversarial and drift detection. The package aims to cover both online and offline detectors for tabular data, text, images and time series. The outlier detection methods should allow the user to identify global, contextual and collective outliers.  
    ![](images/image200.png)  
    
2.  [Pyod](https://www.google.com/url?q=https://pyod.readthedocs.io/en/latest/pyod.html&sa=D&source=editors&ust=1621930682448000&usg=AOvVaw32oxMb3KHlEinkF6pSc7Dg)

![](images/image57.png)

![](images/image105.png)![](images/image4.png)

3.  [Anomaly detection resources](https://www.google.com/url?q=https://github.com/yzhao062/anomaly-detection-resources&sa=D&source=editors&ust=1621930682449000&usg=AOvVaw1HFto-fMffBHE5adkW48Fv) (great)
4.  [Novelty and outlier detection inm sklearn](https://www.google.com/url?q=https://scikit-learn.org/stable/modules/outlier_detection.html&sa=D&source=editors&ust=1621930682450000&usg=AOvVaw1sAMKfYkCuxkuwLphguQ3M)
5.  [SUOD](https://www.google.com/url?q=https://github.com/yzhao062/suod&sa=D&source=editors&ust=1621930682450000&usg=AOvVaw25KlMSJYV_uG5T4RCBxo4f) (Scalable Unsupervised Outlier Detection) is an acceleration framework for large-scale unsupervised outlier detector training and prediction. Notably, anomaly detection is often formulated as an unsupervised problem since the ground truth is expensive to acquire. To compensate for the unstable nature of unsupervised algorithms, practitioners often build a large number of models for further combination and analysis, e.g., taking the average or majority vote. However, this poses scalability challenges in high-dimensional, large datasets, especially for proximity-base models operating in Euclidean space.

![](images/image112.png)

SUOD is therefore proposed to address the challenge at three complementary levels: random projection (data level), pseudo-supervised approximation (model level), and balanced parallel scheduling (system level). As mentioned, the key focus is to accelerate the training and prediction when a large number of anomaly detectors are presented, while preserving the prediction capacity. Since its inception in Jan 2019, SUOD has been successfully used in various academic researches and industry applications, include PyOD [\[2\]](https://www.google.com/url?q=https://github.com/yzhao062/suod%23zhao2019pyod&sa=D&source=editors&ust=1621930682451000&usg=AOvVaw2Uq9hnwbiLNiIleJ5oUskv)and [IQVIA](https://www.google.com/url?q=https://www.iqvia.com/&sa=D&source=editors&ust=1621930682452000&usg=AOvVaw272YJDSUVMxlTIjVkOyuHB) medical claim analysis. It could be especially useful for outlier ensembles that rely on a large number of base estimators.

6.  [Skyline](https://www.google.com/url?q=https://github.com/earthgecko/skyline&sa=D&source=editors&ust=1621930682452000&usg=AOvVaw2sKkLNlMLPux8F4JYN3eqi)
7.  [Scikit-lego](https://www.google.com/url?q=https://scikit-lego.readthedocs.io/en/latest/outliers.html&sa=D&source=editors&ust=1621930682453000&usg=AOvVaw2_PV0n5PpjqRo7beweETUm)

1.  ![](images/image136.png)
2.  ![](images/image131.png)

![](images/image263.png)

3.  ![](images/image115.png)

* * *

ISOLATION FOREST
----------------

[The best resource to explain isolation forest](https://www.google.com/url?q=http://blog.easysol.net/using-isolation-forests-anamoly-detection/&sa=D&source=editors&ust=1621930682455000&usg=AOvVaw3wADFmLZvBbFKMeLIbPZv1) \- the basic idea is that for an anomaly (in the example) only 4 partitions are needed, for a regular point in the middle of a distribution, you need many many more.

[Isolation Forest](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/ensemble/plot_isolation_forest.html&sa=D&source=editors&ust=1621930682456000&usg=AOvVaw220YpwStOqObFEwd2o7HNc) -Isolating observations:

* randomly selecting a feature
* randomly selecting a split value between the maximum and minimum values of the selected feature.

Recursive partitioning can be represented by a tree structure, the number of splittings required to isolate a sample is equivalent to the path length from the root node to the terminating node.

This path length, averaged over a forest of such random trees, is a measure of normality and our decision function.

Random partitioning produces noticeable shorter paths for anomalies.

=\> when a forest of random trees collectively produce shorter path lengths for particular samples, they are highly likely to be anomalies.

[the paper is pretty good too -](https://www.google.com/url?q=https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf&sa=D&source=editors&ust=1621930682458000&usg=AOvVaw1kXLG6VJp3jO94jDmtxfZZ)  In the training stage, iTrees are constructed by recursively partitioning the given training set until instances are isolated or a specific tree height is reached of which results a partial model.

Note that the tree height limit l is automatically set by the sub-sampling size ψ: l = ceiling(log2 ψ), which is approximately the average tree height \[7\].

The rationale of growing trees up to the average tree height is that we are only interested in data points that have shorter-than average path lengths, as those points are more likely to be anomalies

* * *

LOCAL OUTLIER FACTOR
--------------------

* [LOF](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/outlier_detection.html%23local-outlier-factor&sa=D&source=editors&ust=1621930682460000&usg=AOvVaw1p5bfzafEXHcD1V2L-Qran) computes a score (called local outlier factor) reflecting the degree of abnormality of the observations.
* It measures the local density deviation of a given data point with respect to its neighbors. The idea is to detect the samples that have a substantially lower density than their neighbors.
* In practice the local density is obtained from the k-nearest neighbors.
* The LOF score of an observation is equal to the ratio of the average local density of his k-nearest neighbors, and its own local density:

* a normal instance is expected to have a local density similar to that of its neighbors,
* while abnormal data are expected to have much smaller local density.

ELLIPTIC ENVELOPE
-----------------

1.  We assume that the regular data come from a known distribution (e.g. data are Gaussian distributed).
2.  From this assumption, we generally try to define the “shape” of the data,
3.  And can define outlying observations as observations which stand far enough from the fit shape.

* * *

ONE CLASS SVM
-------------

1.  [A nice article about ocs, with github code, two methods are described.](https://www.google.com/url?q=http://rvlasveld.github.io/blog/2013/07/12/introduction-to-one-class-support-vector-machines/&sa=D&source=editors&ust=1621930682464000&usg=AOvVaw2pOFgs65csoaqVo5J0Mb8_)
2.  [Resources for ocsvm](https://www.google.com/url?q=https://www.quora.com/What-is-a-good-resource-for-understanding-One-Class-SVM-for-distribution-esitmation&sa=D&source=editors&ust=1621930682464000&usg=AOvVaw09E1DPMaFKSMTzcOAXVGr9)
3.  It looks like there are [two such methods](https://www.google.com/url?q=http://rvlasveld.github.io/blog/2013/07/12/introduction-to-one-class-support-vector-machines/&sa=D&source=editors&ust=1621930682465000&usg=AOvVaw1L6Sl_YDpYlPa7qHi76H2y), -The 2nd one: The algorithm obtains a spherical boundary, in feature space, around the data. The volume of this hypersphere is minimized, to minimize the effect of incorporating outliers in the solution.

The resulting hypersphere is characterized by a center and a radius R>0 as distance from the center to (any support vector on) the boundary, of which the volume R2 will be minimized.

CLUSTERING METRICS
------------------

For community detection, text clusters, etc.

[Google search for convenience](https://www.google.com/url?q=https://www.google.com/search?biw%3D1600%26bih%3D912%26sxsrf%3DALeKk00NbB52pfM6J1N42ieEddIOirBmcQ%253A1597514997743%26ei%3D9SQ4X-_uLLLhkgWJsIbADw%26q%3Dword%2Bembedding%2Bsilhouette%2Bscore%26oq%3Dword%2Bembedding%2Bsilhouette%2Bscore%26gs_lcp%3DCgZwc3ktYWIQAzoECAAQRzoECCMQJzoHCCMQsAIQJ1DVd1jqjQFgm5ABaARwAXgBgAGMAogBrQ2SAQUwLjkuMpgBAKABAaoBB2d3cy13aXrAAQE%26sclient%3Dpsy-ab%26ved%3D0ahUKEwivvdqP553rAhWysKQKHQmYAfg4ChDh1QMIDA%26uact%3D5&sa=D&source=editors&ust=1621930682467000&usg=AOvVaw3staMHmkEQQ1ytCiRZ1TV9)

Silhouette:

1.  [TFIDF, PCA, SILHOUETTE](https://www.google.com/url?q=https://towardsdatascience.com/mmmm-foodporn-a-clustering-and-classification-study-using-natural-language-processing-e2eae8ddefe1&sa=D&source=editors&ust=1621930682468000&usg=AOvVaw3pxGXACLEfJq0ZtWaAq_id) for deciding how many clusters to use, the knee/elbow method.
2.  [Embedding based silhouette community detection](https://www.google.com/url?q=https://link.springer.com/article/10.1007/s10994-020-05882-8%23Sec10&sa=D&source=editors&ust=1621930682469000&usg=AOvVaw159ukSvUq_qsGlMNlybURz)
3.  [A notebook](https://www.google.com/url?q=https://rlbarter.github.io/superheat-examples/word2vec/&sa=D&source=editors&ust=1621930682469000&usg=AOvVaw1VC5D2moWHymYOa_wQrupf), using the SuperHeat package, clustering w2v cosine similarity matrix, measuring using silhouette score.
4.  [Topic modelling clustering, cant access this document on github](https://www.google.com/url?q=https://github.com/danielwilentz/Cuisine-Classifier/blob/master/topic_modeling/clustering.ipynb&sa=D&source=editors&ust=1621930682470000&usg=AOvVaw0QPu9PeVwk-kt51u1ESX_F)

* * *

DECISION TREES
==============

1.  [Using hellinger distance to split supervised datasets, instead of gini and entropy. Claims better results.](https://www.google.com/url?q=https://medium.com/@evgeni.dubov/classifying-imbalanced-data-using-hellinger-distance-f6a4330d6f9a&sa=D&source=editors&ust=1621930682471000&usg=AOvVaw3pDs4HWPYFlQe8hAaE7PAS)

Visualize decision [trees](https://www.google.com/url?q=https://towardsdatascience.com/interactive-visualization-of-decision-trees-with-jupyter-widgets-ca15dd312084&sa=D&source=editors&ust=1621930682471000&usg=AOvVaw0GPPdrFTSE8mX5jGk5fbv_), [forests](https://www.google.com/url?q=https://towardsdatascience.com/how-to-visualize-a-decision-tree-from-a-random-forest-in-python-using-scikit-learn-38ad2d75f21c&sa=D&source=editors&ust=1621930682472000&usg=AOvVaw3z7qsTPJCneZmDZUL_wK_c)

[CART TREES](https://www.google.com/url?q=http://machinelearningmastery.com/classification-and-regression-trees-for-machine-learning/&sa=D&source=editors&ust=1621930682472000&usg=AOvVaw2sGjYr_olyLwrj7bdX9JTM)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

explains about the similarities and how to measure. which is the best split? based on SSE and GINI (good info about gini here).

* For classification the Gini cost function is used which provides an indication of how “pure” the leaf nodes are (how mixed the training data assigned to each node is).

Gini = sum(pk * (1 – pk))

* Early stop - 1 sample per node is overfitting, 5-10 are good
* Pruning - evaluate what happens if the lead nodes are removed, if there is a big drop, we need it.

KDTREE
------

1.  [Similar to a binary search tree, just by using the median and selecting a feature randomly for each level.](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DTLxWtXEbtFE&sa=D&source=editors&ust=1621930682474000&usg=AOvVaw1SIkk7IwUFAozFZYEOuo8u)
2.  [Used to find nearest neighbours.](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DY4ZgLlDfKDg&sa=D&source=editors&ust=1621930682475000&usg=AOvVaw2-WsHXXAuNL3mDmiV9ob6D)
3.  [Many applications of using KD tree, reduce color space, Database key search, etc](https://www.google.com/url?q=https://www.quora.com/What-is-a-kd-tree-and-what-is-it-used-for&sa=D&source=editors&ust=1621930682476000&usg=AOvVaw2_SmDWuY49T_3pi410KoAh)

RANDOM FOREST
-------------

[Using an ensemble of trees to create a high dimensional and sparse representation of the data and classifying using a linear classifier](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/ensemble/plot_feature_transformation.html%23sphx-glr-auto-examples-ensemble-plot-feature-transformation-py&sa=D&source=editors&ust=1621930682477000&usg=AOvVaw2DJ0EG2FFqKnrkMwfC8dbu)

[How do deal with imbalanced data in Random-forest](https://www.google.com/url?q=http://statistics.berkeley.edu/sites/default/files/tech-reports/666.pdf&sa=D&source=editors&ust=1621930682478000&usg=AOvVaw0IJiSyaZY_hoPCtPvkvf8J) -

1.  One is based on cost sensitive learning.
2.  Other is based on a sampling technique

EXTRA TREES
-----------

1.  [A comparison between random forest and extra trees](https://www.google.com/url?q=https://www.thekerneltrip.com/statistics/random-forest-vs-extra-tree/&sa=D&source=editors&ust=1621930682479000&usg=AOvVaw0OURHb6KB_-dXKA5CVIYzw)  
    Fig. 1: Comparison of random forests and extra trees in presence of irrelevant predictors. In blue are presented the results from the random forest and red for the extra trees. The results are quite striking: Extra Trees perform consistently better when there are a few relevant predictors and many noisy ones![Comparison of random forests and extra trees in presence of irrelevant predictors](images/image80.png)
2.  [Difference between RF and ET](https://www.google.com/url?q=https://stats.stackexchange.com/questions/175523/difference-between-random-forest-and-extremely-randomized-trees&sa=D&source=editors&ust=1621930682480000&usg=AOvVaw1OHqDHu1Y5W9caBjXF2IkV)
3.  [Differences #2](https://www.google.com/url?q=https://stackoverflow.com/questions/22409855/randomforestclassifier-vs-extratreesclassifier-in-scikit-learn&sa=D&source=editors&ust=1621930682481000&usg=AOvVaw32jW2-WSexqdo2dGJt3rjX)

* * *

ACTIVE LEARNING ALGORITHMS
==========================

PASSIVE AGGRESSIVE CLASSIFIER
-----------------------------

1.  [The Passive Aggressive](https://www.google.com/url?q=https://www.quora.com/Classification-machine-learning-What-is-an-intuitive-explanation-of-the-Passive-Aggressive-classifier&sa=D&source=editors&ust=1621930682482000&usg=AOvVaw3h5tMjhGguDZgEg21xfcjD) (PA) algorithm is perfect for classifying massive streams of data (e.g. Twitter). It's easy to implement and very fast, but does not provide global guarantees like the support-vector machine (SVM).
2.  [Youtube, seems like active learning in stream..?](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DTJU8NfDdqNQ&sa=D&source=editors&ust=1621930682482000&usg=AOvVaw2ahw4fXRPlHyVECbu8ZmHy)

* * *

LINEAR SEPARATOR ALGORITHMS
===========================

SEQUENTIAL MINIMAL OPTIMIZATION (SMO)
-------------------------------------

\- [What is the SMO (SVM) classifier?](https://www.google.com/url?q=https://www.microsoft.com/en-us/research/publication/sequential-minimal-optimization-a-fast-algorithm-for-training-support-vector-machines/?from%3Dhttp%253A%252F%252Fresearch.microsoft.com%252Fpubs%252F69644%252Ftr-98-14.pdf&sa=D&source=editors&ust=1621930682484000&usg=AOvVaw2d34OxK3jgs6FmFd2pgija)\- Sequential Minimal Optimization , or SMO . Training a support vector machine requires the solution of a very large quadratic programming (QP) optimization problem. SMO breaks this large QP problem into a series of smallest possible QP problems. These small QP problems are solved analytically, which avoids using a time-consuming numerical QP optimization as an inner loop. The amount of memory required for SMO is linear in the training set size, which allows SMO to handle very large training sets. Because matrix computation is avoided, SMO scales somewhere between linear and quadratic in the training set size for various test problems, while the standard chunking SVM algorithm scales somewhere between linear and cubic in the training set size. SMO’s computation time is dominated by SVM evaluation, hence SMO is fastest for linear SVMs and sparse data sets. On real- world sparse data sets, SMO can be more than 1000 times faster than the chunking algorithm.

[Differences between libsvm and liblinear](https://www.google.com/url?q=https://stackoverflow.com/questions/11508788/whats-the-difference-between-libsvm-and-liblinear&sa=D&source=editors&ust=1621930682485000&usg=AOvVaw0tvw4r4EcP9JaH_ukGR24j) &[smo vs libsvm](https://www.google.com/url?q=https://stackoverflow.com/questions/23674411/weka-smo-vs-libsvm&sa=D&source=editors&ust=1621930682486000&usg=AOvVaw16hU0YQwWdYzpMJbYeXvrs)

SUPPORT VECTOR MACHINES (SVM)
-----------------------------

\- [Definition](https://www.google.com/url?q=http://docs.opencv.org/3.0-beta/modules/ml/doc/support_vector_machines.html&sa=D&source=editors&ust=1621930682486000&usg=AOvVaw0HdbP8imPi3NuQxCHcovsI), [tutorial](https://www.google.com/url?q=https://jakevdp.github.io/PythonDataScienceHandbook/05.07-support-vector-machines.html&sa=D&source=editors&ust=1621930682487000&usg=AOvVaw0XD9dk0EEtp_4wlaYGncfi)***:

* For Optimal 2-class classifier.
* Extended for regression and clustering problems (1 class).
* Kernel-based

* maps feature vectors into a higher-dimensional space using a kernelfunction
* buildsan optimal linear discriminating functionin this space (linear?) or an optimal hyper-plane (RBF?) that fits the training data

* In case of SVM, the kernel is not defined explicitly.
* A distance needsto be defined between any 2 points in the hyper-space.
* The solution is optimal, the marginis maximal. between the separating hyper-plane and the nearest feature vectors
* The feature vectors that are the closest to the hyper-plane are called support vectors, which means that the position of other vectors does not affect the hyper-plane (the decision function).
* The model produced by support vector classification (as described above) depends only on a subset of the training data, because the cost function for building the model does not care about training points that lie beyond the margin.

[MULTI CLASS SVM](https://www.google.com/url?q=https://www.csie.ntu.edu.tw/~cjlin/papers/multisvm.pdf&sa=D&source=editors&ust=1621930682491000&usg=AOvVaw2NFn2BU-FruNYpNrKSVtSO)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

\- one against all, one against one, and Direct Acyclic Graph SVM (one against one with DAG). bottom line One Against One in LIBSVM.

[A few good explanation about SVM, formulas, figures, C, gamma, etc.](https://www.google.com/url?q=https://www.quora.com/What-are-C-and-gamma-with-regards-to-a-support-vector-machine&sa=D&source=editors&ust=1621930682492000&usg=AOvVaw36d3dz-Npmm3Rj1KasSHub)

Math of SVM on youtube:

* [very good number-based example #1](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D1NxnPkZM9bc&sa=D&source=editors&ust=1621930682493000&usg=AOvVaw3JxvmDY-dNKrGPj8ElRMxe)
* [Very good but lengthy and chatty example with make-sense math #2](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DmU_N3nmv0Go%26list%3DPLAwxTw4SYaPlkESDcHD-0oqVx5sAIgz7O%26index%3D4&sa=D&source=editors&ust=1621930682493000&usg=AOvVaw1z5WinNZ0N-8IP28aNICPE) \- udacity

* Linear - maximize the margin, optimal solution, only a few close points are really needed the others are zeroes by the alphas (alpha says “pay attention to this variable”) in the quadratic programming equation. XtX is a similarity function (pairs of points that relate to each other in output labels and how similar to one another, Xi’s point in the same direction) y1y2 are the labels. Therefore further points are not needed. But the similarity is important here(?)
* Non-linear - e.g. circle inside a circle, needs to map to a higher plane, a measure of similarity as XtX is important. We use this similarity idea to map into a higher plane, but we choose the higher plane for the purpose of a final function that behaves likes a known function, such as (A+B)^2. It turns out that (q1,q2,root(2)q1q2) is engineered with that root(2) thing for the purpose of making the multiplication of X^tY, which turns out to be (X^tY)^2. We can substitute this formula (X^tY)^2 instead of the X^tX in the quadratic equation to do that for us.This is the kernel trick that maps the inner class to one side and the outer circle class to the other and passes a plane in between them.
* Similarity is defined intuitively as all the points in one class vs the other.. I think
* A general kernel K=(X^tY + C)^p is a polynomial kernel that can define the above function and others.
* Quadratic eq with possible kernels including the polynomial.

![](images/image153.png)

* Most importantly the kernel function is our domain knowledge. (?) IMO we should choose a kernel that fits our feature data.
* The output of K is a number(?)
* Infinite dimensions - possible as well.
* Mercer condition - it acts like a distance\\similar so that is the “rule” of which a kernel needs to follow.

* [Super good lecture on MIT OPEN COURSE WARE](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D_PwhiWxHK8o&sa=D&source=editors&ust=1621930682496000&usg=AOvVaw1I4EmHSO-fh0bv5F0I-GUV) \- expands on the quadratic equations that were introduced in the previous course above.

Regularization and influence
----------------------------

\- (basically punishment for overfitting and raising the non- linear class points higher and lower)

* [How does regularization look like in SVM](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/4943/intuition-for-the-regularization-parameter-in-svm&sa=D&source=editors&ust=1621930682498000&usg=AOvVaw0ezvgxbXj4nepKgwqIP15r) \- controlling ‘C’
* [The best explanation about Gamma (and C) in  SVM!](https://www.google.com/url?q=https://www.quora.com/What-are-C-and-gamma-with-regards-to-a-support-vector-machine&sa=D&source=editors&ust=1621930682498000&usg=AOvVaw1Hi1wg_qVN3JH-s3QSb8A2)

SUPPORT VECTOR REGRESSION (SVR)
-------------------------------

\- [Definition Support Vector Regression](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/svm.html%23svm-implementation-details&sa=D&source=editors&ust=1621930682499000&usg=AOvVaw2ztrqKNgJUzsh6-WUIgiSq).:

* The method of SVM can be extended to solve regression problems.
* Similar to SVM, the model produced by Support Vector Regression depends only on a subset of the training data, because the cost function for building the model ignores any training data close to the model prediction.

[LibSVM vs LibLinear](https://www.google.com/url?q=https://stackoverflow.com/questions/11508788/whats-the-difference-between-libsvm-and-liblinear&sa=D&source=editors&ust=1621930682500000&usg=AOvVaw1JS9x_DwwqEQujE_8-V7Xh)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

\- using many kernel transforms to turn a non-linear problem into a linear problem beforehand.

From the link above, it seems like liblinear is very much the same thing, without those kernel transforms. So, as they say, in cases where the kernel transforms are not needed (they mention document classification), it will be faster.

*  libsvm (SMO) implementation

* kernel (n^2)
* Linear SVM (n^3)

* liblinear - optimized to deal with linear classification without kernels

* Complexity O(n)
* does not support kernel SVMs.
* Scores higher

n is the number of samples in the training dataset.

Conclusion: In practice libsvm becomes painfully slow at 10k samples. Hence for medium to large scale datasets use liblinear and forget about libsvm (or maybe have a look at approximate kernel SVM solvers such as [LaSVM](https://www.google.com/url?q=http://leon.bottou.org/projects/lasvm&sa=D&source=editors&ust=1621930682503000&usg=AOvVaw3DEkRaafVdqo_T7_7HG-_i), which saves training time and memory usage for large scale datasets).

Support vector clustering (SVC)
-------------------------------

[paper](https://www.google.com/url?q=http://www.jmlr.org/papers/volume2/horn01a/horn01a.pdf&sa=D&source=editors&ust=1621930682504000&usg=AOvVaw0kqtpMeK0qajQcuY000Hk5), [short explanation](https://www.google.com/url?q=https://www.quora.com/Is-it-possible-to-use-SVMs-for-unsupervised-learning-density-estimation&sa=D&source=editors&ust=1621930682504000&usg=AOvVaw0EIM0NeJssFzAS5m7-prAQ)

* * *

KERNELS
-------

[What are kernels in SVM](https://www.google.com/url?q=https://www.quora.com/What-are-Kernels-in-Machine-Learning-and-SVM&sa=D&source=editors&ust=1621930682505000&usg=AOvVaw24bn6TfDhZ44cPaKkiBAMj)-intuition and example

* allows us to do certain calculations faster which otherwise would involve computations in higher dimensional space.
* K(x, y) = &lt;f(x), f(y)&gt;. Here K is the kernel function, x, y are n dimensional inputs. f is a map from n-dimension to m-dimension space. &lt; x,y&gt; denotes the dot product. usually m is much larger than n.
* normally calculating &lt;f(x), f(y)&gt; requires us to calculate f(x), f(y) first, and then do the dot product. These two computation steps can be quite expensive as they involve manipulations in m dimensional space, where m can be a large number.
* Result is ONLY a scalar, i..e., 1-dim space.
* We don’t need to do that calc if we use a clever kernel.

Example:

Simple Example: x = (x1, x2, x3); y = (y1, y2, y3). Then for the function f(x) = (x1x1, x1x2, x1x3, x2x1, x2x2, x2x3, x3x1, x3x2, x3x3), the kernel is K(x, y ) = (&lt;x, y&gt;)^2.

Let's plug in some numbers to make this more intuitive: suppose x = (1, 2, 3); y = (4, 5, 6). Then:

f(x) = (1, 2, 3, 2, 4, 6, 3, 6, 9)  and f(y) = (16, 20, 24, 20, 25, 30, 24, 30, 36)

&lt;f(x), f(y)&gt; = 16 + 40 + 72 + 40 + 100+ 180 + 72 + 180 + 324 = 1024 i.e., 1\*16+2\*20+\*3\*24..

A lot of algebra. Mainly because f is a mapping from 3-dimensional to 9 dimensional space.

With a kernel its faster.

K(x, y) = (4 + 10 + 18 ) ^2 = 32^2 = 1024

A kernel is a magical shortcut to calculate even infinite dimensions!

[Relation to SVM](https://www.google.com/url?q=https://www.quora.com/What-are-Kernels-in-Machine-Learning-and-SVM&sa=D&source=editors&ust=1621930682508000&usg=AOvVaw1jwXotoXjySah9Q-N7yuPa)?:

* The idea of SVM is that y = w phi(x) +b, where w is the weight, phi is the feature vector, and b is the bias.
* if y> 0, then we classify datum to class 1, else to class 0.
* We want to find a set of weight and bias such that the margin is maximized.
* Previous answers mention that kernel makes data linearly separable for SVM. I think a more precise way to put this is, kernels do not make the the data linearly separable.
* The feature vector phi(x) makes the data linearly separable. Kernel is to make the calculation process faster and easier, especially when the feature vector phi is of very high dimension (for example, x1, x2, x3, ..., x\_D^n, x1^2, x2^2, ...., x\_D^2).
* Why it can also be understood as a measure of similarity:  if we put the definition of kernel above, &lt;f(x), f(y)&gt;, in the context of SVM and feature vectors, it becomes &lt;phi(x), phi(y)&gt;. The inner product means the projection of phi(x) onto phi(y). or colloquially, how much overlap do x and y have in their feature space. In other words, how similar they are.

[Kernels](https://www.google.com/url?q=http://docs.opencv.org/3.0-beta/modules/ml/doc/support_vector_machines.html&sa=D&source=editors&ust=1621930682511000&usg=AOvVaw2kAVi2ZIXIhr8OblNFDUSM):

* SVM::LINEAR Linear kernel. No mapping is done, linear discrimination (or regression) is done in the original feature space. It is the fastest option. ![K(x_i, x_j) = x_i^T x_j](images/image270.png).
* SVM::RBF Radial basis function (RBF), a good choice in most cases. ![K(x_i, x_j) = e^{-\gamma ||x_i - x_j||^2}, \gamma > 0](images/image159.png).

[Intuition for regularization in SVM](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/4943/intuition-for-the-regularization-parameter-in-svm&sa=D&source=editors&ust=1621930682513000&usg=AOvVaw3xWyeSPL5O8C5G7JsrKYyB)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

[Grid search for SVM Hyper parameters](https://www.google.com/url?q=http://docs.opencv.org/3.0-beta/modules/ml/doc/support_vector_machines.html&sa=D&source=editors&ust=1621930682513000&usg=AOvVaw2aOEPFfKuicOUVITRFq0Y1)\- in openCV. [Example in log space](https://www.google.com/url?q=https://stackoverflow.com/questions/29128074/choosing-the-best-svm-kernel-type-and-parameters-using-opencv-on-python&sa=D&source=editors&ust=1621930682514000&usg=AOvVaw0X7ZTv6bZNHy0sGR3XaUt0)

* [I.e., (for example](https://www.google.com/url?q=https://www.csie.ntu.edu.tw/~cjlin/papers/guide/guide.pdf&sa=D&source=editors&ust=1621930682514000&usg=AOvVaw1gwTXeZNxRPa_VvjXJE_Wn), C = 2^-5 , 2 ^-3 , . . . , 2^15 , γ = 2^-15 , 2 ^-13 , . . . , 2^3 ).
* There are heuristic methods that skip some search options
* However, no need for heuristics, computation-time is small, grid can be paralleled and we dont skip parameters.
* Controlling search complexity using two tier grid, coarse grid and then fine tune.

[Overfitting advice for SVM:](https://www.google.com/url?q=https://stats.stackexchange.com/questions/35276/svm-overfitting-curse-of-dimensionality&sa=D&source=editors&ust=1621930682515000&usg=AOvVaw1tqkt__-r3wgt05RhyWifo)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Regularization parameter C - [penalty example](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/svm/plot_rbf_parameters.html&sa=D&source=editors&ust=1621930682516000&usg=AOvVaw1dRnj70uPqbmAIdwLLMbdj)
* In non linear kernels:

* Kernel choice
* Kernel parameters

* [RBF](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/svm/plot_rbf_parameters.html&sa=D&source=editors&ust=1621930682518000&usg=AOvVaw3zF2JRfeSEdoP0GSKJs4sx) \- gamma, low and high values are far and near influence

* Great [Tutorial at LIBSVM](https://www.google.com/url?q=https://www.csie.ntu.edu.tw/~cjlin/papers/guide/guide.pdf&sa=D&source=editors&ust=1621930682519000&usg=AOvVaw0yJf_Ji98v6fLGDZakHMvI)
* Reasonable first choice
* when the relation between class labels and attributes is nonlinear.
* Special case of C can make this similar to linear kernel (only! After finding C and gamma)
* Certain parameters makes it behave like the sigmoid kernel.
* Less hyperparameters than RBF kernel.
* 0 <Kij <1 unlike other kernels where the degree is 0<k<infinity
* Sigmoid is not valid under some parameters.
* DON'T USE when the #features is very large, use linear.

[RBF kernel](https://www.google.com/url?q=https://www.csie.ntu.edu.tw/~cjlin/papers/guide/guide.pdf&sa=D&source=editors&ust=1621930682521000&usg=AOvVaw0e3H1UC_NwKX8o2WXwMWp0) use cases
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Number of instances <<  number of features. I.e, 38 instances over 7000 features.

RBF=LINEAR When the number of features is large, we may not need to use RBF over Linear and vice versa (After finding C and gamma)

* Number of Instances & features is VERY LARGE. I.e, 20K samples X 20K features.

Similar performance with libsvm and liblinear, liblinear is faster by 150 times. Rule of thumb is to use for document classification.

* Number of instances >> number of features. Usuallyhigh dimensional mapping using non linear kernel. If we insist on liblinear, -s 2 leads to faster training.

[Kdnuggets: When to use DL over SVM and other algorithms. Computationally expensive for a very small boost in accuracy.](https://www.google.com/url?q=http://www.kdnuggets.com/2016/04/deep-learning-vs-svm-random-forest.html&sa=D&source=editors&ust=1621930682523000&usg=AOvVaw2Iu64GiDdtXT2u26fWYJ6o)

* * *

ENSEMBLES
=========

1.  [How to combine several sklearn algorithms into a voting ensemble](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DvlTQLb_a564%26list%3DPLQVvvaa0QuDf2JswnfiGkliBInZnIC4HL%26index%3D16&sa=D&source=editors&ust=1621930682524000&usg=AOvVaw2erqGEEV-RJAsEgrNjzzf1)
2.  [Stacking api, MLXTEND](https://www.google.com/url?q=http://rasbt.github.io/mlxtend/user_guide/classifier/StackingClassifier/&sa=D&source=editors&ust=1621930682525000&usg=AOvVaw3Vd5HWPDvLjudkDuxyh1qv)
3.  Machine learning Mastery on

1.  [stacking neural nets - really good](https://www.google.com/url?q=https://machinelearningmastery.com/stacking-ensemble-for-deep-learning-neural-networks/&sa=D&source=editors&ust=1621930682526000&usg=AOvVaw0M1QANBd0kBleMS99bKVLZ)

1.  Stacked Generalization Ensemble
2.  Multi-Class Classification Problem
3.  Multilayer Perceptron Model
4.  Train and Save Sub-Models
5.  Separate Stacking Model
6.  Integrated Stacking Model

2.  [How to Combine Predictions for Ensemble Learning](https://www.google.com/url?q=https://machinelearningmastery.com/combine-predictions-for-ensemble-learning/?fbclid%3DIwAR3sEAjoqP1KNScXrKV1HdiG98PZC-_gfB7ngDEwL_NMMSngRNqcwxABejQ&sa=D&source=editors&ust=1621930682528000&usg=AOvVaw015hRJK45mNLZwpJoiB-sY)

1.  Plurality Voting.
2.  Majority Voting.
3.  Unanimous Voting.
4.  Weighted Voting.

3.  [Essence of Stacking Ensembles for Machine Learning](https://www.google.com/url?q=https://machinelearningmastery.com/essence-of-stacking-ensembles-for-machine-learning/?fbclid%3DIwAR18Tm_CzyxufVpFjjd-n_VvpFNZRj3TuMBNd02EXmNhYWdG80KVyBjzmfo&sa=D&source=editors&ust=1621930682530000&usg=AOvVaw1_-nYvIzN9jEQDk1IthIah)

1.  Voting Ensembles
2.  Weighted Average
3.  Blending Ensemble
4.  Super Learner Ensemble

4.  [Dynamic Ensemble Selection (DES) for Classification in Python](https://www.google.com/url?q=https://machinelearningmastery.com/dynamic-ensemble-selection-in-python/?fbclid%3DIwAR2cFTJY3bXiCkPKFIGM7X5HDsTjZEehINfA40wyqPWw8KAIOpXCdblu3eM&sa=D&source=editors&ust=1621930682531000&usg=AOvVaw0NaCtAyEbRQGYkeCYyabV-)\- Dynamic Ensemble Selection algorithms operate much like DCS algorithms, except predictions are made using votes from multiple classifier models instead of a single best model. In effect, each region of the input feature space is owned by a subset of models that perform best in that region.

1.  k-Nearest Neighbor Oracle (KNORA) With Scikit-Learn

1.  KNORA-Eliminate (KNORA-E)
2.  KNORA-Union (KNORA-U)

2.  Hyperparameter Tuning for KNORA

1.  Explore k in k-Nearest Neighbor
2.  Explore Algorithms for Classifier Pool

5.  [A Gentle Introduction to Mixture of Experts Ensembles](https://www.google.com/url?q=https://machinelearningmastery.com/mixture-of-experts/?fbclid%3DIwAR3Y9K-QOmF6H06vZOYQH8phv5C0a2rhV-4FfNffCb2XKmvDsL-d8bMOuLM&sa=D&source=editors&ust=1621930682534000&usg=AOvVaw3XU7wpuBVfqQpQIikRF2iu)

1.  Mixture of Experts

1.  Subtasks
2.  Expert Models
3.  Gating Model
4.  Pooling Method

2.  Relationship With Other Techniques

1.  Mixture of Experts and Decision Trees
2.  Mixture of Experts and Stacking

6.  [Strong Learners vs. Weak Learners in Ensemble Learning](https://www.google.com/url?q=https://machinelearningmastery.com/strong-learners-vs-weak-learners-for-ensemble-learning/?fbclid%3DIwAR0yQzfYq0JGZu7xYErX2W42jtm949pOYSbKN8jClQCPMwgEUDNyv6uuXFU&sa=D&source=editors&ust=1621930682536000&usg=AOvVaw1lsEfgR_n4SMauGK8cYrqm)\- Weak learners are models that perform slightly better than random guessing. Strong learners are models that have arbitrarily good accuracy.  
    Weak and strong learners are tools from computational learning theory and provide the basis for the development of the boosting class of ensemble methods.

4.  [Vidhya on trees, bagging boosting, gbm, xgb](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2016/04/complete-tutorial-tree-based-modeling-scratch-in-python/?utm_source%3Dfacebook.com%26utm_medium%3Dsocial%26fbclid%3DIwAR1Fji6N01Zc3rhLCJiIq76CX5aC8W0dWmw0hpyceYwMr9Z3QPCbnPu0a2A%23three&sa=D&source=editors&ust=1621930682538000&usg=AOvVaw0OI27RMRr4pl8zUOEww5-e)
5.  [Parallel grad boost treest](https://www.google.com/url?q=http://zhanpengfang.github.io/418home.html&sa=D&source=editors&ust=1621930682539000&usg=AOvVaw1x-S_5yiOQ_V4USbeyhrnb)
6.  [A comprehensive guide to ensembles read!](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2018/06/comprehensive-guide-for-ensemble-models/&sa=D&source=editors&ust=1621930682539000&usg=AOvVaw0CINw-_2LMgApPvbn7DAe9) (samuel jefroykin)

1.  Basic Ensemble Techniques
2.  2.1 Max Voting
3.  2.2 Averaging
4.  2.3 Weighted Average
5.  Advanced Ensemble Techniques
6.  3.1 Stacking
7.  3.2 Blending
8.  3.3 Bagging
9.  3.4 Boosting
10. Algorithms based on Bagging and Boosting
11. 4.1 Bagging meta-estimator
12. 4.2 Random Forest
13. 4.3 AdaBoost
14. 4.4 GBM
15. 4.5 XGB
16. 4.6 Light GBM
17. 4.7 CatBoost

7.  [Kaggler guide to stacking](https://www.google.com/url?q=http://blog.kaggle.com/2016/12/27/a-kagglers-guide-to-model-stacking-in-practice/&sa=D&source=editors&ust=1621930682543000&usg=AOvVaw3Ji1ZWtCLJNu3c2Vic1cQB)
8.  [Blending vs stacking](https://www.google.com/url?q=https://www.quora.com/What-are-examples-of-blending-and-stacking-in-Machine-Learning&sa=D&source=editors&ust=1621930682543000&usg=AOvVaw0hst3F1OdXlv1iq4bAkRyo)
9.  [Kaggle ensemble guide](https://www.google.com/url?q=https://mlwave.com/kaggle-ensembling-guide/&sa=D&source=editors&ust=1621930682544000&usg=AOvVaw2endTyOj9c1DHNFyV1M9Ew)

[Ensembles in WEKA](https://www.google.com/url?q=http://machinelearningmastery.com/use-ensemble-machine-learning-algorithms-weka/&sa=D&source=editors&ust=1621930682545000&usg=AOvVaw1LMgM2CmvLUGIGkhq0eodt)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

\- bagging (random sample selection, multi classifier training), random forest (random feature selection for each tree, multi tree training), boosting(creating stumps, each new stump tries to fix the previous error, at last combining results using new data, each model is assigned a skill weight and accounted for in the end), voting(majority vote, any set of algorithms within weka, results combined via mean or some other way), stacking(same as voting but combining predictions using a meta model is used).

* * *

BAGGING - bootstrap aggregating
-------------------------------

[Bagging](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D2Mg8QD0F1dQ%26list%3DPLAwxTw4SYaPnIRwl6rad_mYwEk4Gmj7Mx%26index%3D192&sa=D&source=editors&ust=1621930682546000&usg=AOvVaw1ZabT_ifimt5GaVUaz-g7K) \- best example so far, create m bags, put n’<n samples (60% of n) in each bag - with replacement which means that the same sample can be selected twice or more, query from the test (x) each of the m models, calculate mean, this is the classification.

![](images/image40.png)

Overfitting - not an issue with bagging, as the mean of the models actually averages or smoothes the “curves”. Even if all of them are overfitted.

![](images/image44.png)

* * *

BOOSTING
--------

Mastery on using [all the boosting algorithms](https://www.google.com/url?q=https://machinelearningmastery.com/gradient-boosting-with-scikit-learn-xgboost-lightgbm-and-catboost/?fbclid%3DIwAR1wenJZ52kU5RZUgxHE4fj4M9Ods1p10EBh5J4QdLSSq2XQmC4s9Se98Sg&sa=D&source=editors&ust=1621930682548000&usg=AOvVaw27VAjE9ZtPO4_TZIjvhs9L): Gradient Boosting with Scikit-Learn, XGBoost, LightGBM, and CatBoost

Adaboost: similar to bagging, create a system that chooses from samples that were modelled poorly before.

1.  create bag\_1 with n’ features <n with replacement, create the model\_1, test on ALL train.
2.  Create bag\_2 with n’ features with replacement, but add a bias for selecting from the samples that were wrongly classified by the model\_1. Create a model\_2. Average results from model\_1 and model_2. I.e., who was classified correctly or not.
3.  Create bag\_3 with n’ features with replacement, but add a bias for selecting from the samples that were wrongly classified by the model\_1+2. Create a model\_3. Average results from model\_1, 2 & 3 I.e., who was classified correctly or not. Iterate onward.
4.  Create bag_m with n’ features with replacement, but add a bias for selecting from the samples that were wrongly classified by the previous steps.

![](images/image24.png)

* * *

XGBOOST
-------

* [What is XGBOOST?](https://www.google.com/url?q=http://homes.cs.washington.edu/~tqchen/2016/03/10/story-and-lessons-behind-the-evolution-of-xgboost.html&sa=D&source=editors&ust=1621930682550000&usg=AOvVaw2-sd1cItrpnyRSiLIuSxEj)XGBoost is an optimized distributed gradient boosting system designed to be highly efficient, flexibleand portable [#2nd link](https://www.google.com/url?q=http://dmlc.cs.washington.edu/xgboost.html&sa=D&source=editors&ust=1621930682552000&usg=AOvVaw1OCZzGNM0SvQKDDgil_g_6)
* [Does it cause overfitting?](https://www.google.com/url?q=https://stats.stackexchange.com/questions/20714/does-ensembling-boosting-cause-overfitting&sa=D&source=editors&ust=1621930682553000&usg=AOvVaw2oEDYOnvAe4b0NhSokUBGe)
* [Authors Youtube lecture.](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DVly8xGnNiWs&sa=D&source=editors&ust=1621930682553000&usg=AOvVaw1v-Wi-AgZKheSJsKk5brxV)
* [GIT here](https://www.google.com/url?q=https://github.com/dmlc/xgboost&sa=D&source=editors&ust=1621930682554000&usg=AOvVaw3cAjee53t5B6rWoPOSI3SU)
* [How to use XGB tutorial on medium (comparison to GBC)](https://www.google.com/url?q=https://towardsdatascience.com/boosting-algorithm-xgboost-4d9ec0207d&sa=D&source=editors&ust=1621930682554000&usg=AOvVaw2_ZseKK1pssNQHykmJDNkE)
* [How to code tutorial](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D87xRqEAx6CY&sa=D&source=editors&ust=1621930682555000&usg=AOvVaw0evSWVDnVnKZgmyOwtKCOX), short and makes sense, with info about the parameters.

* Threads
* Rounds
* Tree height
* Loss function
* Error
* Cross fold.

* [Beautiful Video Class about XGBOOST](https://www.google.com/url?q=https://www.youtube.com/playlist?list%3DPLZnYQQzkMilqTC12LmnN4WpQexB9raKQG&sa=D&source=editors&ust=1621930682556000&usg=AOvVaw07nNnS0bPZLSpTT26K5mRY) \- mostly practical in jupyter but with some insight about the theory.
* [Machine learning master](https://www.google.com/url?q=http://machinelearningmastery.com/gentle-introduction-xgboost-applied-machine-learning/&sa=D&source=editors&ust=1621930682557000&usg=AOvVaw12mOEoT0bJX-IwerOLHV8D)y - slides, video, lots of info.

[R Installation in Weka](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DEGwHXC3baWU%26list%3DPLm4W7_iX_v4Msh-7lDOpSFWHRYU_6H5Kx%26index%3D15&sa=D&source=editors&ust=1621930682558000&usg=AOvVaw0rFVIpWmrC3z3a9GmryLxF), then XGBOOST in weka through R

[Parameters](https://www.google.com/url?q=http://weka.8497.n7.nabble.com/XGBoost-in-Weka-through-R-or-Python-td40282.html&sa=D&source=editors&ust=1621930682559000&usg=AOvVaw1xmm-DtTfQsL9aLJAbbaMW) for weka mlr class.xgboost.

* [https://cran.r-project.org/web/packages/xgboost/xgboost.pdf](https://www.google.com/url?q=https://cran.r-project.org/web/packages/xgboost/xgboost.pdf&sa=D&source=editors&ust=1621930682559000&usg=AOvVaw3y1eFrn0cp2Ga5sxAG5hOp)
* Here is an example configuration for multi-class classification:
*  weka.classifiers.mlr.MLRClassifier -learner “nrounds = 10, max_depth = 2, eta = 0.5, nthread = 2”
* classif.xgboost -params "nrounds = 1000, max_depth = 4, eta = 0.05, nthread = 5, objective = \\"multi:softprob\\"

Copy: nrounds = 10, max_depth = 2, eta = 0.5, nthread = 2

[Special case of random forest using XGBOOST](https://www.google.com/url?q=https://github.com/dmlc/xgboost/blob/master/R-package/vignettes/discoverYourData.Rmd%23special-note-what-about-random-forests&sa=D&source=editors&ust=1621930682561000&usg=AOvVaw3aBooHFwydQ9qsfM_dCujQ):

#Random Forest™ - 1000 trees  
bst <- xgboost(data = train$data, label = train$label, max\_depth = 4, num\_parallel\_tree = 1000, subsample = 0.5, colsample\_bytree =0.5, nrounds = 1, objective = "binary:logistic")  
  
#Boosting - 3 rounds  
bst <- xgboost(data = train$data, label = train$label, max_depth = 4, nrounds = 3, objective = "binary:logistic")

RF1000: \- max\_depth = 4, num\_parallel\_tree = 1000, subsample = 0.5, colsample\_bytree =0.5, nrounds = 1, nthread = 2

XG: nrounds = 10, max_depth = 4, eta = 0.5, nthread = 2

* * *

Gradient Boosting Classifier
----------------------------

1.  [Loss functions and GBC vs XGB](https://www.google.com/url?q=https://stats.stackexchange.com/questions/202858/loss-function-approximation-with-taylor-expansion&sa=D&source=editors&ust=1621930682563000&usg=AOvVaw0SaAmZ4DRE9ol2j1UAp2jO)
2.  [Why is XGB faster than SK GBC](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/10943/why-is-xgboost-so-much-faster-than-sklearn-gradientboostingclassifier&sa=D&source=editors&ust=1621930682564000&usg=AOvVaw0ylAkAztmkK4q2iPppZo6X)
3.  [Good XGB vs GBC](https://www.google.com/url?q=https://towardsdatascience.com/boosting-algorithm-xgboost-4d9ec0207d&sa=D&source=editors&ust=1621930682564000&usg=AOvVaw0eqhFk0kOkPHu1M59Nmih7) tutorial
4.  [XGB vs GBC](https://www.google.com/url?q=https://stats.stackexchange.com/questions/282459/xgboost-vs-python-sklearn-gradient-boosted-trees&sa=D&source=editors&ust=1621930682565000&usg=AOvVaw29GFRod9o-uzMCCXkgiNu3)
    
    * * *
    

REINFORCEMENT LEARNING
======================

Q-LEARN
-------

[Q-Learning](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D9m_6q_KECTk&sa=D&source=editors&ust=1621930682566000&usg=AOvVaw2erwl0OAsWDGzKe_BSoGXl)

* Markov chain problem, (state, action, new state, reward)
* Lots of Exploration in the beginning, then exploitation
* Returns optimal policy.
* Refer to youtube [here](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D9m_6q_KECTk&sa=D&source=editors&ust=1621930682567000&usg=AOvVaw3f7RcIPz6RQut6HDtVfE4f)

RL IN DL
--------

[A review paper about RL in DL](https://www.google.com/url?q=https://arxiv.org/pdf/1701.07274.pdf&sa=D&source=editors&ust=1621930682568000&usg=AOvVaw0rX54rBsuErkwFsi9-Bwnx)

* * *

INCREMENTAL LEARNING
====================

(wiki) In computer science, incremental learningis a method of machine learning in which input data is continuously used to extend the existing model's knowledge i.e. to further train the model.

![](images/image52.png)

![](images/image179.png)

* Using incremental learning for time series, i.e., sent[iment from twitter api streat, learning from smiley in weka.](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DjScSxkuSei8%26list%3DPLm4W7_iX_v4Msh-7lDOpSFWHRYU_6H5Kx%26index%3D12&sa=D&source=editors&ust=1621930682571000&usg=AOvVaw0rD5BTzlKBUbtK7AH3WPaX)
* And [time series in weka](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D9R0mz_gfhBs%26list%3DPLm4W7_iX_v4Msh-7lDOpSFWHRYU_6H5Kx%26index%3D3&sa=D&source=editors&ust=1621930682571000&usg=AOvVaw1nBI7VY5gAZ67ZgDucG2AG), with some ideas about dealing with time series data, especially date and time.

HOEFFDING TREE
--------------

* IS STATE OF THE ART

* * *

DIMENSIONALITY REDUCTION METHODS
================================

* A series on DR for dummies on medium part [1](https://www.google.com/url?q=https://towardsdatascience.com/https-medium-com-abdullatif-h-dimensionality-reduction-for-dummies-part-1-a8c9ec7b7e79?_branch_match_id%3D584170448791192656&sa=D&source=editors&ust=1621930682573000&usg=AOvVaw3zgz7jGVYjCpBOEwTe8H8O)[2](https://www.google.com/url?q=https://towardsdatascience.com/dimensionality-reduction-for-dummies-part-2-3b1e3490bdc9&sa=D&source=editors&ust=1621930682574000&usg=AOvVaw1gsKrltWA3yddIOILnW_Su)[3](https://www.google.com/url?q=https://towardsdatascience.com/dimensionality-reduction-for-dummies-part-3-f25729f74c0a&sa=D&source=editors&ust=1621930682575000&usg=AOvVaw1Khdh7brw5xR68lPnUdPFm)
* [A small blog post about PCA, AE & TSNE](https://www.google.com/url?q=https://towardsdatascience.com/reducing-dimensionality-from-dimensionality-reduction-techniques-f658aec24dfe&sa=D&source=editors&ust=1621930682575000&usg=AOvVaw1X1ORlJSybu_qmbOpMw6TA) in tensorflow
* [Visualizing PCA/TSNE using plots](https://www.google.com/url?q=https://towardsdatascience.com/visualising-high-dimensional-datasets-using-pca-and-t-sne-in-python-8ef87e7915b&sa=D&source=editors&ust=1621930682576000&usg=AOvVaw31Sykms9wgZo3Q6vIB7_JO)

![](images/image102.png)

* [Parallex by uber for tsne \ pca visualization](https://www.google.com/url?q=https://github.com/uber-research/parallax&sa=D&source=editors&ust=1621930682577000&usg=AOvVaw1ABDh1FyJdIVFbj6DCz5kB)
* [About tsne / ae / pca](https://www.google.com/url?q=https://towardsdatascience.com/reducing-dimensionality-from-dimensionality-reduction-techniques-f658aec24dfe&sa=D&source=editors&ust=1621930682578000&usg=AOvVaw2wGc0ag1SoymbGwEPy012R)
* [Does dim-reduction loses information - yes and no, in pca yes only if you use less than the entire matrix](https://www.google.com/url?q=https://stats.stackexchange.com/questions/66060/does-dimension-reduction-always-lose-some-information&sa=D&source=editors&ust=1621930682579000&usg=AOvVaw3MTO9J0hdhILvc9sf9c4cF)
* [Performance comparison between dim-reduction implementations, tsne etc.](https://www.google.com/url?q=https://umap-learn.readthedocs.io/en/latest/benchmarking.html&sa=D&source=editors&ust=1621930682579000&usg=AOvVaw3Qt20v-zS8dpBd1dvGI--H)![](images/image75.png)

* * *

TSNE
----

1.  [Stat quest](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DNEaUSP4YerM%26list%3DPLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF%26index%3D30&sa=D&source=editors&ust=1621930682581000&usg=AOvVaw2OcFgwieZ_mZC1JAUCKhVw) \- the jist of it is that we assume a t- distribution on distances and remove those that are farther.normalized for density. T-dist used so that clusters are not clamped in the middle.

![](images/image203.png)

![](images/image121.png)

Iteratively moving from the left to the right![](images/image130.png)

2.  [TSNE algorithm](https://www.google.com/url?q=https://www.oreilly.com/learning/an-illustrated-introduction-to-the-t-sne-algorithm&sa=D&source=editors&ust=1621930682583000&usg=AOvVaw3Mqq6-lp0w9QgWUZ8BiXeN)
3.  [Are there cases where PCA more suitable than TSNE](https://www.google.com/url?q=https://stats.stackexchange.com/questions/238538/are-there-cases-where-pca-is-more-suitable-than-t-sne?rq%3D1&sa=D&source=editors&ust=1621930682583000&usg=AOvVaw2WoWWx8H5pGpmIZA_7zRdC)
4.  [PCA preserving pairwise distances over tSNE?](https://www.google.com/url?q=https://stats.stackexchange.com/questions/176672/what-is-meant-by-pca-preserving-only-large-pairwise-distances&sa=D&source=editors&ust=1621930682584000&usg=AOvVaw0OswGYSxWpbuiNmecslAXZ) How why, all here.
5.  [Another advice about using tsne and the possible misinterpetations](https://www.google.com/url?q=https://towardsdatascience.com/why-you-are-using-t-sne-wrong-502412aab0c0&sa=D&source=editors&ust=1621930682585000&usg=AOvVaw354RijuBsadQPBlAba1sr7)

PCA
---

1.  Machine learning mastery:

1.  [Expected value, variance, covariance](https://www.google.com/url?q=https://machinelearningmastery.com/introduction-to-expected-value-variance-and-covariance&sa=D&source=editors&ust=1621930682586000&usg=AOvVaw3Aw2LQqCuipz_8ohmPITSk)
2.  [PCA](https://www.google.com/url?q=https://machinelearningmastery.com/calculate-principal-component-analysis-scratch-python/&sa=D&source=editors&ust=1621930682587000&usg=AOvVaw1TpG1d-6sY2gh-o04sZ_dy) (remove the mean from A, calculate cov(A), calculate eig(cov), A*eigK = PCA)
3.  [EigenDecomposition](https://www.google.com/url?q=https://machinelearningmastery.com/introduction-to-eigendecomposition-eigenvalues-and-eigenvectors/&sa=D&source=editors&ust=1621930682588000&usg=AOvVaw1fuikH6xs7OKlK6p2bMCIp) \- what is an eigen vector - simply put its a vector that satisfies A\*v = lambda\*v, how to use eig() and how to confirm an eigenvector/eigenvalue and reconstruct the original A matrix.
4.  [SVD](https://www.google.com/url?q=https://machinelearningmastery.com/singular-value-decomposition-for-machine-learning&sa=D&source=editors&ust=1621930682588000&usg=AOvVaw09j2j4sc1GyHnfyJsQQ1zQ)
5.  What is missing is how the EigenDecomposition is calculated.

1.  [PCA on large matrices!](https://www.google.com/url?q=https://amedee.me/post/pca-large-matrices/&sa=D&source=editors&ust=1621930682589000&usg=AOvVaw3PXjODp1YsUvuuTG60a3dd)

1.  Randomized svd
2.  Incremental svd

2.  [PCA on Iris](https://www.google.com/url?q=http://sebastianraschka.com/Articles/2015_pca_in_3_steps.html&sa=D&source=editors&ust=1621930682590000&usg=AOvVaw294zaE3AO9_jfEln_2JmJj)
3.  (did not read) [What is PCA?](https://www.google.com/url?q=https://stats.stackexchange.com/questions/222/what-are-principal-component-scores&sa=D&source=editors&ust=1621930682591000&usg=AOvVaw1tnz4RtnsvZu731q47PvJT)
4.  (did not read) [What is a covariance matrix?](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Covariance_matrix&sa=D&source=editors&ust=1621930682592000&usg=AOvVaw1cVnk8U8C9zzXeYKOudVuK)
5.  (did not read) [Variance covariance matrix](https://www.google.com/url?q=http://stattrek.com/matrix-algebra/covariance-matrix.aspx&sa=D&source=editors&ust=1621930682592000&usg=AOvVaw37R_YQxraxpnI9RUC8GBCY)
6.  [Visualization of the first PCA vectors](https://www.google.com/url?q=https://medium.com/@rtjeannier/using-pca-to-visualize-high-dimensional-data-6ff028c911c5&sa=D&source=editors&ust=1621930682593000&usg=AOvVaw1FvHdJk3NULa7xYQVIbXtR), it is unclear what he is trying to show.
7.  [A very nice introductory tutorial on how to use PCA](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2016/03/practical-guide-principal-component-analysis-python/&sa=D&source=editors&ust=1621930682593000&usg=AOvVaw1rdM8K5Ol9f6HPhacHEseO)
8.  \*\* [An in-depth tutorial on PCA (paper)](https://www.google.com/url?q=https://www.cs.princeton.edu/picasso/mats/PCA-Tutorial-Intuition_jp.pdf&sa=D&source=editors&ust=1621930682594000&usg=AOvVaw3TGZT7DhCYuT5g9u4jPXU8)
9.  \*\* [yet another tutorial paper on PCA (looks good)](https://www.google.com/url?q=https://www.researchgate.net/publication/309165405_Principal_component_analysis_-_a_tutorial&sa=D&source=editors&ust=1621930682595000&usg=AOvVaw0xF-9gScPXeGX50qPtfFYF)
10. [How to use PCA in Cross validation and for train\\test split](https://www.google.com/url?q=https://stats.stackexchange.com/questions/114560/pca-on-train-and-test-datasets-do-i-need-to-merge-them&sa=D&source=editors&ust=1621930682596000&usg=AOvVaw0jvONrfP6HP6l7M-aqyHwx). (bottom line, do it on the train only.)
11. [Another tutorial paper - looks decent](https://www.google.com/url?q=https://www.researchgate.net/publication/309165405_Principal_component_analysis_-_a_tutorial&sa=D&source=editors&ust=1621930682596000&usg=AOvVaw1YzjIn_bpuGV2SKzyPEGWa)
12. [PCA whitening](https://www.google.com/url?q=http://mccormickml.com/2014/06/03/deep-learning-tutorial-pca-and-whitening/&sa=D&source=editors&ust=1621930682597000&usg=AOvVaw0idABPAsPu6cfl1tb50f2s), [Stanford tutorial](https://www.google.com/url?q=http://ufldl.stanford.edu/tutorial/unsupervised/PCAWhitening/&sa=D&source=editors&ust=1621930682597000&usg=AOvVaw1D5TCRSsPC8fC3JAUksEGE)(pca/zca whitening), [Stackoverflow (really good)](https://www.google.com/url?q=https://stats.stackexchange.com/questions/117427/what-is-the-difference-between-zca-whitening-and-pca-whitening/117459&sa=D&source=editors&ust=1621930682598000&usg=AOvVaw0yjvPlk7JuypUIM1qnM9KE) ,

There are two things we are trying to accomplish with whitening:

1.  Make the features less correlated with one another.
2.  Give all of the features the same variance.

Whitening has two simple steps:

1.  Project the dataset onto the eigenvectors. This rotates the dataset so that there is no correlation between the components.
2.  Normalize the the dataset to have a variance of 1 for all components. This is done by simply dividing each component by the square root of its eigenvalue.

SVD
---

1.  [An explanation about SVD’s formulas.](https://www.google.com/url?q=https://blog.statsbot.co/singular-value-decomposition-tutorial-52c695315254&sa=D&source=editors&ust=1621930682600000&usg=AOvVaw2HbWnQlois_c9CL-ySDxkd)

KPCA
----

1.  [First they say that](https://www.google.com/url?q=https://web.cs.hacettepe.edu.tr/~aykut/classes/fall2016/bbm406/slides/l25-kernel_pca.pdf&sa=D&source=editors&ust=1621930682601000&usg=AOvVaw0A7e6AOBJWPIiu2rbvu-p_) Autoencoder is PCA based on their equation, i.e. minimize the reconstruction error formula.![](images/image250.png)

2.  Then they say that PCA cant separate certain non-linear situations (circle within a circle), therefore they introduce kernel based PCA (using the kernel trick - like svm) which mapps the space to another linearly separable space, and performs PCA on it,![](images/image158.png)

![](images/image43.png)

3.  Finally, showing results how KPCA works well on noisy images, compared to PCA.

![](images/image253.png)

* * *

LDA - Linear discriminant analysis
----------------------------------

[A comparison / tutorial with code on pca vs lda - read!](https://www.google.com/url?q=http://rstudio-pubs-static.s3.amazonaws.com/84669_cd15214061d44e1493ffee69c5d55925.html&sa=D&source=editors&ust=1621930682605000&usg=AOvVaw1OP8xgb2XRFLcU6Exh0a5j)

[A comprehensive tutorial on LDA - read!](https://www.google.com/url?q=https://iksinc.online/2018/11/12/dimensionality-reduction-via-linear-discriminant-analysis/?fbclid%3DIwAR3d0ja_HP0DkamiL3W4QxzjcsIfoySB_G7LetTNf0cE0ed_MVduXfi6bv0&sa=D&source=editors&ust=1621930682606000&usg=AOvVaw0DTSsq93wicDszdr66pjaG)

[Dim reduction with LDA - nice examples](https://www.google.com/url?q=https://iksinc.online/2018/11/12/dimensionality-reduction-via-linear-discriminant-analysis/?fbclid%3DIwAR3d0ja_HP0DkamiL3W4QxzjcsIfoySB_G7LetTNf0cE0ed_MVduXfi6bv0&sa=D&source=editors&ust=1621930682607000&usg=AOvVaw3sG7S7rH3EgcH26j1UHoVs)

([Not to be confused with the other LDA](https://www.google.com/url?q=http://sebastianraschka.com/Articles/2014_python_lda.html&sa=D&source=editors&ust=1621930682608000&usg=AOvVaw2aDnM-e_bIr0KLArle8N-Y)) \- Linear Discriminant Analysis (LDA)is most commonly used as dimensionality reduction technique in the pre-processing step for pattern-classification and machine learning applications. The goal is to project a dataset onto a lower-dimensional space with good class-separability in order avoid overfitting(“curse of dimensionality”) and also reduce computational costs.

PCA vs LDA:

Both Linear Discriminant Analysis (LDA) and Principal Component Analysis (PCA) are linear transformation techniques used for dimensionality reduction.

* PCA can be described as an “unsupervised” algorithm, since it “ignores” class labels and its goal is to find the directions (the so-called principal components) that maximize the variance in a dataset.
* In contrast to PCA, LDA is “supervised” and computes the directions (“linear discriminants”) that will represent the axes that maximize the separation between multiple classes.

Although it might sound intuitive that LDA is superior to PCA for a multi-class classification task where the class labels are known, this might not always the case.

For example, comparisons between classification accuracies for image recognition after using PCA or LDA show that :

* PCA tends to outperform LDA if the number of samples per class is relatively small ([PCA vs. LDA](https://www.google.com/url?q=http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber%3D908974&sa=D&source=editors&ust=1621930682611000&usg=AOvVaw0DYVNkxxYGRbpBEAG0lYlk), A.M. Martinez et al., 2001).

* In practice, it is also not uncommon to use both LDA and PCA in combination:

Best Practice: PCA for dimensionality reduction can be followed by an LDA.But before we skip to the results of the respective linear transformations, let us quickly recapitulate the purposes of PCA and LDA: PCA finds the axes with maximum variance for the whole data set where LDA tries to find the axes for best class separability. In practice, often a LDA is done followed by a PCA for dimensionality reduction.

![](images/image137.png)

\*\* To fully understand the details please follow the LDA link to the original and very informative article

\*\*\* TODO: need some benchmarking for PCA\\LDA\\LSA\\ETC..

* * *

KDA - KERNEL DISCRIMINANT ANALYSIS
----------------------------------

1.  [pyDML package](https://www.google.com/url?q=https://pydml.readthedocs.io/en/latest/dml.html%23dml.kda.KDA&sa=D&source=editors&ust=1621930682614000&usg=AOvVaw2E_NOYzi_674BoRuMAJQII) \- has KDA - This package provides the classic algorithms of supervised distance metric learning, together with some of the newest proposals.

![](images/image271.png)

* * *

LSA
---

[LSA](https://www.google.com/url?q=http://mccormickml.com/2016/03/25/lsa-for-text-classification-tutorial/&sa=D&source=editors&ust=1621930682615000&usg=AOvVaw3UpJXF7LdV5lRzJyyfMJrH) is quite simple, you just use SVD to perform dimensionality reduction on the tf-idf vectors–that’s really all there is to it! And [LSA CLUSTERING](https://www.google.com/url?q=http://mccormickml.com/2015/08/05/document-clustering-example-in-scikit-learn/&sa=D&source=editors&ust=1621930682616000&usg=AOvVaw1AEDFfQpoHtwW9EFhjlcAb)

Here is a very nice [tutorial about LSA,](https://www.google.com/url?q=https://technowiki.wordpress.com/2011/08/27/latent-semantic-analysis-lsa-tutorial/&sa=D&source=editors&ust=1621930682617000&usg=AOvVaw3QOA59EplBkL8_yZ3p4cxL) with code, explaining what are the three matrices, word clustering, sentence clustering and vector importance. They say that for sentence space we need to remove the first vector as it is correlated with sentence length.

*how to [interpret LSA vectors](https://www.google.com/url?q=http://mccormickml.com/2016/03/25/lsa-for-text-classification-tutorial/&sa=D&source=editors&ust=1621930682618000&usg=AOvVaw2H5VI5Y44kp_xeUy6XBuET)

PCA vs LSA: ([intuition1](https://www.google.com/url?q=https://stats.stackexchange.com/questions/65699/lsa-vs-pca-document-clustering&sa=D&source=editors&ust=1621930682619000&usg=AOvVaw3OoTWr2b40IytU1ohODP05), [intuition2](https://www.google.com/url?q=https://math.stackexchange.com/questions/3869/what-is-the-intuitive-relationship-between-svd-and-pca&sa=D&source=editors&ust=1621930682620000&usg=AOvVaw2JIQ7zDJkpDw1gJZumS2W-))

* reduction of the dimensionality
* noise reduction
* incorporating relations between terms into the representation.
* SVD and PCA and "total least-squares" (and several other names) are the same thing. It computes the orthogonal transform that decorrelates the variables and keeps the ones with the largest variance. There are two numerical approaches: one by SVD of the (centered) data matrix, and one by Eigen decomposition of this matrix "squared" (covariance).

[LSA vs W2V](https://www.google.com/url?q=https://arxiv.org/pdf/1610.01520.pdf&sa=D&source=editors&ust=1621930682621000&usg=AOvVaw3yNh4LgXoGentkB7lrkRsO)

* * *

ICA
---

1.  While PCA is global, it finds global variables (with images we get eigen faces, good for reconstruction) that maximizes variance in orthogonal directions, and is not influenced by the TRANSPOSE of the data matrix.
2.  On the other hand, ICA is local and finds local variables (with images we get eyes ears, mouth, basically edges!, etc), ICA will result differently on TRANSPOSED matrices, unlike PCA, its also “directional” - consider the “cocktail party” problem. On documents, ICA gives topics.
3.  It helps, similarly to PCA, to help us analyze our data.

Sparse[info on ICA with security returns.](https://www.google.com/url?q=https://www.quantopian.com/posts/an-experiment-with-independent-component-analysis&sa=D&source=editors&ust=1621930682624000&usg=AOvVaw1D5NB2DIVnqpBjAa1IZqDa)

* * *

MANIFOLD
--------

1.  [The best tutorial that explains manifold (high to low dim projection/mapping/visuzation)](https://www.google.com/url?q=https://jhui.github.io/2017/01/15/Machine-learning-Multi-dimensional-scaling-and-visualization/&sa=D&source=editors&ust=1621930682625000&usg=AOvVaw0MWnUoJZI_2W6c2BYPNx8W) (pca, sammon, isomap, tsne)
2.  [Many manifold methods used to visualize high dimensional data.](https://www.google.com/url?q=http://scikit-learn.org/stable/modules/manifold.html%23t-sne&sa=D&source=editors&ust=1621930682626000&usg=AOvVaw2_OWkDdAWWiAbxrtk6afBb)
3.  [Comparing manifold methods](https://www.google.com/url?q=http://scikit-learn.org/stable/auto_examples/manifold/plot_compare_methods.html%23sphx-glr-auto-examples-manifold-plot-compare-methods-py&sa=D&source=editors&ust=1621930682627000&usg=AOvVaw0rWnBkjHAqcIUd1ffrJiDm)

### T-SNE

1.  [Code and in-depth tutorial on TSNE, mapping probabilities to distributions](https://www.google.com/url?q=https://towardsdatascience.com/t-sne-python-example-1ded9953f26&sa=D&source=editors&ust=1621930682628000&usg=AOvVaw2AiUsh7xFW6nNn4x-vx3TE)\*\*\*\*
2.  [A great example of using PCA and then TSNE to see clusters that arent visible with PCA only.](https://www.google.com/url?q=https://towardsdatascience.com/dimensionality-reduction-by-stacking-pca-and-t-sne-420d9fcfab54&sa=D&source=editors&ust=1621930682629000&usg=AOvVaw36TUjdfUs7w_Bpo19RTq6O)
3.  [Misreading T-SNE](https://www.google.com/url?q=https://distill.pub/2016/misread-tsne/&sa=D&source=editors&ust=1621930682629000&usg=AOvVaw0WdTQGrXqeuYVk13UxUQxy), this is a very important read.
4.  In contrary to what it says on sklearn’s website, TSNE is not suited ONLY for visualization, you [can also use it for data reduction](https://www.google.com/url?q=https://lvdmaaten.github.io/tsne/&sa=D&source=editors&ust=1621930682630000&usg=AOvVaw2YVhutv7mop93lGVWzETG6)
5.  “t-Distributed Stochastic Neighbor Embedding (t-SNE) is a ([prize-winning](https://www.google.com/url?q=http://blog.kaggle.com/2012/11/02/t-distributed-stochastic-neighbor-embedding-wins-merck-viz-challenge/&sa=D&source=editors&ust=1621930682630000&usg=AOvVaw2yIgRPLnFqXwtMQ8lmLBHK)) technique for    dimensionality reduction that is particularly well suited for the visualization of high-dimensional datasets.”
6.  [Comparing PCA and TSNE, then pushing PCA to TSNE and seeing what happens (as recommended in SKLEARN](https://www.google.com/url?q=https://medium.com/@luckylwk/visualising-high-dimensional-datasets-using-pca-and-t-sne-in-python-8ef87e7915b&sa=D&source=editors&ust=1621930682631000&usg=AOvVaw3ipbqYo-vdVJ5P_FDp5g-L)
7.  [TSNE + AUTOENCODER example](https://www.google.com/url?q=https://towardsdatascience.com/reducing-dimensionality-from-dimensionality-reduction-techniques-f658aec24dfe&sa=D&source=editors&ust=1621930682631000&usg=AOvVaw3717USXPWWTlCCfeS869Jt)

### Sammons embedding mapping

1.  [In tensorflow](https://www.google.com/url?q=https://datawarrior.wordpress.com/2017/06/01/sammon-embedding-with-tensorflow/&sa=D&source=editors&ust=1621930682632000&usg=AOvVaw1iQwoDwiVS_eoe1ThUOfAt)

### IVIS

1.  [Paper:](https://www.google.com/url?q=https://www.nature.com/articles/s41598-019-45301-0&sa=D&source=editors&ust=1621930682633000&usg=AOvVaw2AhNw49MZ_RDvBAqxTSQHK)
2.  [Git](https://www.google.com/url?q=https://github.com/beringresearch/ivis&sa=D&source=editors&ust=1621930682634000&usg=AOvVaw3zqwLuHt4lKTv48s7lhpW1), [docs](https://www.google.com/url?q=https://bering-ivis.readthedocs.io/en/latest/&sa=D&source=editors&ust=1621930682634000&usg=AOvVaw2YFsbjw14Gsj4gjV7rpWFs)
3.  [Ivis animate](https://www.google.com/url?q=https://github.com/beringresearch/ivis-animate&sa=D&source=editors&ust=1621930682635000&usg=AOvVaw0RUnMHlwY_e4qPIcMljRQH)
4.  [Ivis explain](https://www.google.com/url?q=https://github.com/beringresearch/ivis-explain&sa=D&source=editors&ust=1621930682635000&usg=AOvVaw3ytmAvZKGiQwE_MzvRCszH)
    
    * * *
    

GENETIC ALGORITHMS / PROGRAMMING
================================

[What is the difference?](https://www.google.com/url?q=https://stackoverflow.com/questions/3819977/what-are-the-differences-between-genetic-algorithms-and-genetic-programming&sa=D&source=editors&ust=1621930682636000&usg=AOvVaw1olUbF6ceS3uyzQSFuMO_4)Genetic programming and genetic algorithms are very similar. They are both used to evolve the answer to a problem, by comparing the fitness of each candidate in a population of potential candidates over many generations.

Each generation, new candidates are found by randomly changing (mutation) or swapping parts (crossover) of other candidates. The least 'fit' candidates are removed from the population. - peterjwest

![](images/image18.png)

Genetic algorithms (GA) are search algorithms that mimic the process of natural evolution, where each individual is a candidate solution: individuals are generally "raw data" (in whatever encoding format has been defined).

Genetic programming(GP) is considered a special case of GA, where each individual is a computer program(not just "raw data"). GP explore the algorithmic search spaceand evolve computer programs to perform a defined task.

johnIdol

![](images/image13.png)

LEARNING CLASSIFIER SYSTEMS
===========================

LCS
---

(WIKI) [Learning classifier systems](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Learning_classifier_system&sa=D&source=editors&ust=1621930682640000&usg=AOvVaw0RuFWl9vz1IDEqb_JXbJMM), or LCS, are a paradigm of [rule-based machine learning](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Rule-based_machine_learning&sa=D&source=editors&ust=1621930682641000&usg=AOvVaw2SwaXQy6oclRbBitF-lbmb)methods that combine a discovery component (e.g. typically a [genetic algorithm](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Genetic_algorithm&sa=D&source=editors&ust=1621930682642000&usg=AOvVaw3svBlk5SPAy6qTki_IACEK)) with a learning component (performing either [supervised learning](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Supervised_learning&sa=D&source=editors&ust=1621930682642000&usg=AOvVaw0CHK9wbE7wrV9w2ZgU1NWx), [reinforcement learning](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Reinforcement_learning&sa=D&source=editors&ust=1621930682643000&usg=AOvVaw3ipfhtjHgJ4gUOaIErfB50), or [unsupervised learning](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Unsupervised_learning&sa=D&source=editors&ust=1621930682643000&usg=AOvVaw1FEQCiooG0U2EJBwdHB47u)).

XCS
---

[XCS](https://www.google.com/url?q=http://hosford42.github.io/xcs/&sa=D&source=editors&ust=1621930682644000&usg=AOvVaw1BtnJLZ8c41luzCCcOn1KJ)is a type of [Learning Classifier System (LCS)](https://www.google.com/url?q=http://en.wikipedia.org/wiki/Learning_classifier_system&sa=D&source=editors&ust=1621930682645000&usg=AOvVaw3huyeG_6HwiUA4KQbNa3Ip), a [machine learning](https://www.google.com/url?q=http://en.wikipedia.org/wiki/Machine_learning&sa=D&source=editors&ust=1621930682645000&usg=AOvVaw0R3RWM7wZzf-QGoOKVbsnu)algorithm that utilizes a [genetic algorithm](https://www.google.com/url?q=http://en.wikipedia.org/wiki/Genetic_algorithm&sa=D&source=editors&ust=1621930682646000&usg=AOvVaw1b73MaTa7X50wG89H--aUv)acting on a rule-based system, to solve a [reinforcement learning](https://www.google.com/url?q=http://en.wikipedia.org/wiki/Reinforcement_learning&sa=D&source=editors&ust=1621930682646000&usg=AOvVaw1zGWOFsiJ_osOC7Y15X7YD) problem.

[Scikit-xcs](https://www.google.com/url?q=https://github.com/UrbsLab/scikit-XCS&sa=D&source=editors&ust=1621930682647000&usg=AOvVaw2spbX11AKXMAzNRY6vnOQw)![](images/image39.png)

[Tutorial](https://www.google.com/url?q=https://pythonhosted.org/xcs/&sa=D&source=editors&ust=1621930682648000&usg=AOvVaw1LxF-va-6mOulp0Cfox3nE)

* * *

Recommender Algorithms
======================

1.  [Beginner guide](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2015/08/beginners-guide-learn-content-based-recommender-systems/&sa=D&source=editors&ust=1621930682649000&usg=AOvVaw2M1pJ7_2fr0B6I4vTZS8Kx) vidhya
2.  [Real python on CF](https://www.google.com/url?q=https://realpython.com/build-recommendation-engine-collaborative-filtering/%23steps-involved-in-collaborative-filtering&sa=D&source=editors&ust=1621930682649000&usg=AOvVaw0_-kx810yBKShM8KdD-wC3)
3.  [Intro to, using item-item or user-item](https://www.google.com/url?q=https://www.ethanrosenthal.com/2015/11/02/intro-to-collaborative-filtering/&sa=D&source=editors&ust=1621930682650000&usg=AOvVaw2KI47GdDRenp-0bI210WPO), validating using imdb data, git
4.  [Tfidf cosine similarity](https://www.google.com/url?q=https://towardsdatascience.com/recommender-engine-under-the-hood-7869d5eab072&sa=D&source=editors&ust=1621930682651000&usg=AOvVaw22a_75_x2GfaKloiUs21Eb), [countvec cosine](https://www.google.com/url?q=https://www.datacamp.com/community/tutorials/recommender-systems-python&sa=D&source=editors&ust=1621930682651000&usg=AOvVaw3KqUSY0aQsBwr9x8X7H0Ld)
5.  [Various implementations of CF](https://www.google.com/url?q=https://towardsdatascience.com/various-implementations-of-collaborative-filtering-100385c6dfe0&sa=D&source=editors&ust=1621930682652000&usg=AOvVaw32k_7nzm_CyiLAkh1ZmYeN), a serious review of algorithms
6.  [Collaborative filtering, SVD](https://www.google.com/url?q=https://hackernoon.com/introduction-to-recommender-system-part-1-collaborative-filtering-singular-value-decomposition-44c9659c5e75&sa=D&source=editors&ust=1621930682653000&usg=AOvVaw2cEIsMFoOkhFYclqC-2C2c)
7.  [Part1,](https://www.google.com/url?q=https://hackernoon.com/introduction-to-recommender-system-part-1-collaborative-filtering-singular-value-decomposition-44c9659c5e75&sa=D&source=editors&ust=1621930682654000&usg=AOvVaw2B9S-gr-eLaFQla1nDa7TQ) [Spotlight, item2vec, Neural nets for Recommender systems](https://www.google.com/url?q=https://towardsdatascience.com/introduction-to-recommender-system-part-2-adoption-of-neural-network-831972c4cbf7&sa=D&source=editors&ust=1621930682654000&usg=AOvVaw3CH6mNqCV0sU0wVAVv71E7)
8.  [A general tutorial, has a nice intro](https://www.google.com/url?q=https://www.datacamp.com/community/tutorials/recommender-systems-python&sa=D&source=editors&ust=1621930682655000&usg=AOvVaw2-Tcd78MWx4gSriS378J8H)
9.  Medium on Movies

1.  Part 1 [matrix factorization in movies, users vs movies.](https://www.google.com/url?q=https://towardsdatascience.com/fast-ai-season-1-episode-5-1-movie-recommendation-using-fastai-a53ed8e41269&sa=D&source=editors&ust=1621930682656000&usg=AOvVaw1kWM_3Wb3XIA6khdZ2Rsci)
2.  [Part 2 using collaborative filtering](https://www.google.com/url?q=https://towardsdatascience.com/fast-ai-season-1-episode-5-2-collaborative-filtering-from-scratch-1877640f514a&sa=D&source=editors&ust=1621930682657000&usg=AOvVaw0TXJdoPxBKvzASy1avZu6p) using open ai
3.  [Part 3 using col-filtering with neural nets](https://www.google.com/url?q=https://towardsdatascience.com/fast-ai-season-1-episode-5-3-collaborative-filtering-using-neural-network-48e49d7f9b36&sa=D&source=editors&ust=1621930682657000&usg=AOvVaw038sEjHn0Wf_j5TOuMK3S-)

10. Medium series on collaborative filtering and embeddings [Part 1](https://www.google.com/url?q=https://towardsdatascience.com/collaborative-filtering-and-embeddings-part-1-63b00b9739ce&sa=D&source=editors&ust=1621930682658000&usg=AOvVaw2NAimynjwkeWjnaUZkiNGF), [part 2](https://www.google.com/url?q=https://towardsdatascience.com/collaborative-filtering-and-embeddings-part-2-919da17ecefb&sa=D&source=editors&ust=1621930682659000&usg=AOvVaw1tzgjVaczyAyy7CPLvAwuY), [git](https://www.google.com/url?q=https://github.com/shik3519/collaborative-filtering&sa=D&source=editors&ust=1621930682659000&usg=AOvVaw2QOO5c16AZu-2QT0DJmzwf)
11. [Movie recommender systems](https://www.google.com/url?q=https://www.kaggle.com/rounakbanik/movie-recommender-systems&sa=D&source=editors&ust=1621930682660000&usg=AOvVaw0Iyt-ShfvDTdOPq5ESbFde) on kaggle

1.  [On git](https://www.google.com/url?q=https://github.com/jaypatel00174/Movie-Recommendation&sa=D&source=editors&ust=1621930682661000&usg=AOvVaw0sKNsfEY_nMMYbBAICWXZ6)

12. [Matrix factorization](https://www.google.com/url?q=https://towardsdatascience.com/paper-summary-matrix-factorization-techniques-for-recommender-systems-82d1a7ace74&sa=D&source=editors&ust=1621930682661000&usg=AOvVaw1MT1ECxGgbwvE_Iai0iUnV)
13. [Collaborative filtering with binary countvec data, item-item, didnt work well on another domain](https://www.google.com/url?q=https://medium.com/radon-dev/item-item-collaborative-filtering-with-binary-or-unary-data-e8f0b465b2c3&sa=D&source=editors&ust=1621930682662000&usg=AOvVaw1C_5_47omur8p4EnGvzVFO)
14. [Netflix competition, matrix factorization over classical algorithms, a survey paper](https://www.google.com/url?q=https://towardsdatascience.com/paper-summary-matrix-factorization-techniques-for-recommender-systems-82d1a7ace74&sa=D&source=editors&ust=1621930682663000&usg=AOvVaw3u-TTza7wMXE9S5gEeGO9J)
15. [Movie similarity based on genre](https://www.google.com/url?q=https://towardsdatascience.com/content-based-recommender-systems-28a1dbd858f5&sa=D&source=editors&ust=1621930682663000&usg=AOvVaw0XnbXeVE7tuDoXMF6u1_m0)
16. [Similar entities, matrix multiplication](https://www.google.com/url?q=https://medium.com/wbaa/https-medium-com-ingwbaa-boosting-selection-of-the-most-similar-entities-in-large-scale-datasets-450b3242e618&sa=D&source=editors&ust=1621930682664000&usg=AOvVaw0B6luyKlhNxpfforupLyU-) high sparsity
17. [Euclidean distance with high sparse data](https://www.google.com/url?q=https://stats.stackexchange.com/questions/117354/euclidean-distance-with-sparse-and-high-dimension-data&sa=D&source=editors&ust=1621930682665000&usg=AOvVaw2mULcJ-waPB-VoLKETzVMd)
18. Excel & fastai, [git](https://www.google.com/url?q=https://github.com/shik3519/collaborative-filtering/blob/master/cf-scratch-movielens/collaborative%2520filtering%2520from%2520scratch.ipynb&sa=D&source=editors&ust=1621930682666000&usg=AOvVaw3X0Stoq4WGjBkIPjQPZqSz)
19. [CF for movie recommendation](https://www.google.com/url?q=https://medium.com/@wwwbbb8510/python-implementation-of-baseline-item-based-collaborative-filtering-2ba7c8960590&sa=D&source=editors&ust=1621930682667000&usg=AOvVaw0iYdcUW9pInxN2YnZnCcLK)
20. [Comparison item vs user cf](https://www.google.com/url?q=https://medium.com/@wwwbbb8510/comparison-of-user-based-and-item-based-collaborative-filtering-f58a1c8a3f1d&sa=D&source=editors&ust=1621930682667000&usg=AOvVaw1ONXyD9TWGhd_txTUl-CtN)

### TOOLS

1.  [Surprise](https://www.google.com/url?q=https://github.com/NicolasHug/Surprise&sa=D&source=editors&ust=1621930682668000&usg=AOvVaw3GYjBCIUdcvUpkWoj_TIQ2), [docs](https://www.google.com/url?q=https://surprise.readthedocs.io/en/stable/FAQ.html%23how-to-get-the-top-n-recommendations-for-each-user&sa=D&source=editors&ust=1621930682669000&usg=AOvVaw34v_XH1_dlC5nqRC4myFHJ),
2.  [Grover prince](https://www.google.com/url?q=https://github.com/groverpr/Machine-Learning&sa=D&source=editors&ust=1621930682669000&usg=AOvVaw3JXwC9TBdTwz_RV6aav9a2), [related article](https://www.google.com/url?q=https://towardsdatascience.com/various-implementations-of-collaborative-filtering-100385c6dfe0&sa=D&source=editors&ust=1621930682670000&usg=AOvVaw0MZxQzvYOUSlIPTsgmBWyD)
3.  [Recsys](https://www.google.com/url?q=https://github.com/ocelma/python-recsys&sa=D&source=editors&ust=1621930682670000&usg=AOvVaw3pdu5HACThVJiBAN2f-aQO) git

* * *

TEMPLATIZATION
==============

* [Awesome log analysis](https://www.google.com/url?q=https://github.com/logpai/awesome-log-analysis&sa=D&source=editors&ust=1621930682671000&usg=AOvVaw3lA4QxH6gCa-V5S8PDUjth)  
    ![](images/image32.png)
* (really good) [And list of papers for each field](https://www.google.com/url?q=https://github.com/logpai/awesome-log-analysis/blob/master/papers.md%23anomaly-detection&sa=D&source=editors&ust=1621930682672000&usg=AOvVaw23Rw3zs4KN8dNC-QI2QJmJ)
* [How to use log analytics to detect log anomaly](https://www.google.com/url?q=https://www.msystechnologies.com/blog/how-to-use-log-analytics-to-detect-log-anomaly/&sa=D&source=editors&ust=1621930682673000&usg=AOvVaw0Vuo0SHwuwpCW3SMy0W89h) \- more of a survey into the technologies available  
    ![](images/image97.png)
* [3 things we learned about applying word vectors to logs](https://www.google.com/url?q=https://gab41.lab41.org/three-things-we-learned-about-applying-word-vectors-to-computer-logs-c199070f390b%23.bk8wnk7pr&sa=D&source=editors&ust=1621930682674000&usg=AOvVaw00Rv8MUFXc4b0HXq_ZxsMS)

* GloVe consistently identified approximately 50 percent or more of the seeded events in the synthetic data as either exact or as valid sub-sequence matches. GloVe tended to nominate a limited number of template sequences that weren’t related to seeded events and many of those were tied to high frequency templates. When we tested GloVe against a generated data set with multiple SSH sessions in an auditd file, GloVe correctly proposed a single event that included all of the auditd record types defined in the SSH user login lifecycle.
* Glove produces sub sequences that needs to be stitched to create a match![](images/image122.png)
* Glove is faster than paris and fp growth
* Their clustering method misclassified  
    

* [Towards an NLP based log template generation algorithm for system log analysis](https://www.google.com/url?q=http://www.3at.work/papers/cfi2014.pdf&sa=D&source=editors&ust=1621930682675000&usg=AOvVaw23njbq3u3fqZ-H7f27BkNU) \- CRF for templatization, i.e. ner style. “we can see that the more learning data given, the more accurately CRF produces log templates. Clearly a sufficient number of train data enables us to analyze less frequently appearing log templates. Therefore, it is reasonable that a log template can be analyzed correctly if train data include some of similar templates. However, in terms of log template accuracy, CRF requires 10000 train data to achieve same accuracy as Vaarandi’s algorithm”

![](images/image242.png)

![](images/image268.png)

![](images/image170.png)

Logpai
------

1.  [Logpai](https://www.google.com/url?q=https://github.com/logpai&sa=D&source=editors&ust=1621930682677000&usg=AOvVaw3LG6z1L8mNpguqwNu6t1TZ)
2.  [Loghub datasets](https://www.google.com/url?q=https://github.com/logpai/loghub&sa=D&source=editors&ust=1621930682677000&usg=AOvVaw2k671-ubn5Sq1sdaZFrp40)
3.  [logpaI loglizer:](https://www.google.com/url?q=https://github.com/PinjiaHe&sa=D&source=editors&ust=1621930682678000&usg=AOvVaw3Z-ifOXlXjGPnd8ZraZntR) [An Evaluation Study on Log Parsing and Its Use in Log Mining](https://www.google.com/url?q=https://pinjiahe.github.io/papers/DSN16.pdf&sa=D&source=editors&ust=1621930682678000&usg=AOvVaw0mR0J-3hq3l9BxL7mm9rhb), [git](https://www.google.com/url?q=https://github.com/logpai/loglizer&sa=D&source=editors&ust=1621930682678000&usg=AOvVaw0qdHWlVYA_vDlbv394_pB8)
4.  [log3C](https://www.google.com/url?q=https://github.com/logpai/Log3C&sa=D&source=editors&ust=1621930682679000&usg=AOvVaw12giuYu9Zcc5I7LHqWWSS3) \- [paper](https://www.google.com/url?q=https://dl.acm.org/citation.cfm?id%3D3236083&sa=D&source=editors&ust=1621930682679000&usg=AOvVaw2ZmFjJNDjFDNYzAIBGYPyU) Log3C is a general framework that identifies service system problems from system logs. It utilizes both system logs and system KPI metrics to promptly and precisely identify impactful system problems. Log3C consists of four steps: Log parsing, Sequence vectorization, Cascading Clustering and Correlation analysis. This is a joint work by CUHK and Microsoft Research. The repository contains the source code of Log3C, including data loading, sequence vectorization, cascading clustering, data saving, etc. The core part is the cascading clustering algorithm, which groups a large number of sequence vectors into clusters by iteratively sampling, clustering, matching. ![](images/image259.png)![](images/image125.png)![](images/image269.png)  
    Selection of KPI: In our experiments, we use failure rate as the KPI for problem identification. failure rateis an important KPI for evaluating system service availability. There are also other KPIs such as mean time between failures, average request latency, throughput, etc. In our future work, we will experiment with problem identification concerning different KPI metrics. Noises in labeling: Our experiments are based on three datasets that are collected as a period of logs on three different days. The engineers manually inspected and labeled the log sequences. (false positives/negatives) may be introduced during the manual labeling process. However, as the engineers are experienced professionals of the product team who maintain the service system, we believe the amount of noise is small (if it exists)

Furthermore, we compare our method with two typical methods: PCA \[41\] and Invariants Mining \[23\]. All these three methods are unsupervised, log-based problem identification methods. PCA projects the log sequence vectors into a subspace. If the projected vector is far from the majority, it is considered as a problem. Invariants Mining extracts the linear relations (invariants) between log event occurrences, which hypothesizes that log events are often pairwise generated. For example, when processing files, "File A is opened" and "File A is closed" should be printed as a pair. Log sequences that violate the invariants are regarded as problematic. Log3C achieves good recalls (similar to those achieved by two comparative methods) and surpasses the comparative methods concerning precision and F1-measure.

5.  [Logzip](https://www.google.com/url?q=https://github.com/logpai/logzip&sa=D&source=editors&ust=1621930682680000&usg=AOvVaw368fSZhxmx-7PIlI-F7D3s)[paper](https://www.google.com/url?q=https://arxiv.org/abs/1910.00409&sa=D&source=editors&ust=1621930682681000&usg=AOvVaw037F6k-dPK3diINBkiAaS2)-Logzip is an (personal note seems to be offline) efficient compression tool specific for log files. It compresses log files by utilizing the inherent structures of raw log messages, and thereby achieves a high compression ratio.The results show that logzip can save about half of the storage space on average over traditional compression tools. Meanwhile, the design of logzip is highly parallel and only incurs negligible overhead. In addition, we share our industrial experience of applying logzip to Huawei's real products.
6.  Logadvisor - [paper1](https://www.google.com/url?q=https://jiemingzhu.github.io/pub/qfu_icse2014.pdf&sa=D&source=editors&ust=1621930682681000&usg=AOvVaw0AC5z-2gge1EZDmIV8TgLI), [2](https://www.google.com/url?q=http://jmzhu.logpai.com/pub/jmzhu_icse2015.pdf&sa=D&source=editors&ust=1621930682682000&usg=AOvVaw1RZTY8-5tnfqgKG86vseri) \- Our goal, referred to as “learning to log”, is to automatically learn the common logging practice as a machine learning model, and then leverage the model to guide developers to make logging decisions during new development.

1.  Labels:  logging method (e.g., Console.Writeline())
2.  Features: we need to extract useful features (e.g., exception type) from the collected code snippets for making logging decisions,
3.  Train / suggest
4.  ![](images/image118.png)![](images/image53.png)

7.  [Logging descriptions -](https://www.google.com/url?q=https://github.com/logpai/LoggingDescriptions&sa=D&source=editors&ust=1621930682683000&usg=AOvVaw2if5UnN_Nq5Rlfw07NbP95)This repository maintains a set of &lt;code, log&gt; pairs extracted from popular open-source projects, which are amendable to logging description generation research.
8.  (REALLY GOOD) [Loglizer](https://www.google.com/url?q=https://github.com/logpai/loglizer&sa=D&source=editors&ust=1621930682683000&usg=AOvVaw0XX05kBdsyefwx0_VzXVRL)[paper](https://www.google.com/url?q=http://jmzhu.logpai.com/pub/slhe_issre2016.pdf&sa=D&source=editors&ust=1621930682684000&usg=AOvVaw2XIfKfeQVCqABudfP79o3A)[git demo](https://www.google.com/url?q=https://github.com/logpai/loglizer/tree/master/demo&sa=D&source=editors&ust=1621930682684000&usg=AOvVaw2nNWDCsYXh4rdRSHlajkcU)- Loglizer is a machine learning-based log analysis toolkit for automated anomaly detection.

![](images/image147.png)

* Feature extraction using fixed window, sliding window and session window

* Fixed window: Both fixed windows and sliding windows are based on timestamp, which records the occurrence time of each log. Each fixed window has its size, which means the time span or time duration. As shown in Figure 1, the window size is Δt, which is a constant value, such as one hour or one day. Thus, the number of fixed windows depends on the predefined window size. Logs that happened in the same window are regarded as a log sequence.
* Sliding window: Different from fixed windows, sliding windows consist of two attributes: window size and step size, e.g., hourly windows sliding every five minutes. In general, step size is smaller than window size, therefore causing the overlap of different windows. Figure 1 shows that the window size is ΔT , while the step size is the forwarding distance. The number of sliding windows, which is often larger than fixed windows, mainly depends on both window size and step size. Logs that occurred in the same sliding window are also grouped as a log sequence, though logs may duplicate in multiple sliding windows due to the overlap.
* Sessionwindow: Compared with the above two windowing types, session windows are based on identifiers instead of the timestamp. Identifiers are utilized to mark different execution paths in some log data. For instance, HDFS logs with block_id record the allocation, writing, replication, deletion of certain block. Thus, we can group logs according to the identifiers, where each session window has a unique identifier

* Many Supervised methods and most importantly a cool unsupervised method - > PCA for anomaly based on the length of the projected transformed sample vector by dividing the first and last PC vectors:
* PCA was first applied in log-based anomaly detection by Xu et al. \[47\]. In their anomaly detection method, each log sequence is vectorized as an event count vector. After that, PCA is employed to find patterns between the dimensions of event count vectors. Employing PCA, two subspace are generated, namely normal space Sn and anomaly space Sa. Sn is constructed by the first k principal components and Sn is constructed by the remaining (n−k), where n is the original dimension. Then, the projection ya = (1−P P T )y of an event count vector y to Sa is calculated, where P = \[v1,v2, ...,vk,\] is the first k principal components. If the length of ya is larger

9.  [LogParser](https://www.google.com/url?q=https://github.com/logpai/logparser&sa=D&source=editors&ust=1621930682686000&usg=AOvVaw1QeGmG3Sr3L8Q9n3mvVpxg) \- a benchmark for log parsers using 13 models on 16 datasets  
    Important insights:

1.  Drain is fastest, most performing on most datasets (9/16)
2.  Fitting parameters should be adapted, which what makes drain the most performing
3.  More demanding metrics.
4.  Papers:

* \[ICSE'19\] Jieming Zhu, Shilin He, Jinyang Liu, Pinjia He, Qi Xie, Zibin Zheng, Michael R. Lyu. [Tools and Benchmarks for Automated Log Parsing](https://www.google.com/url?q=https://arxiv.org/pdf/1811.03509.pdf&sa=D&source=editors&ust=1621930682688000&usg=AOvVaw0Yd3T9ezXbG7ZJcoAN2d2p). International Conference on Software Engineering (ICSE), 2019.
* \[TDSC'18\] Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. [Towards Automated Log Parsing for Large-Scale Log Data Analysis](https://www.google.com/url?q=https://jiemingzhu.github.io/pub/pjhe_tdsc2017.pdf&sa=D&source=editors&ust=1621930682689000&usg=AOvVaw3NuKh8wmibMEniv0LdDJtl). IEEE Transactions on Dependable and Secure Computing (TDSC), 2018.
* \[ICWS'17\] Pinjia He, Jieming Zhu, Zibin Zheng, Michael R. Lyu. [Drain: An Online Log Parsing Approach with Fixed Depth Tree](https://www.google.com/url?q=https://jiemingzhu.github.io/pub/pjhe_icws2017.pdf&sa=D&source=editors&ust=1621930682690000&usg=AOvVaw2MUtSOOKu93EUDi2x2oWyG). IEEE International Conference on Web Services (ICWS), 2017.
* \[DSN'16\] Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. [An Evaluation Study on Log Parsing and Its Use in Log Mining](https://www.google.com/url?q=https://jiemingzhu.github.io/pub/pjhe_dsn2016.pdf&sa=D&source=editors&ust=1621930682691000&usg=AOvVaw0hvr7foUOZ4rzPv3LWRm2m). IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), 2016.

![](images/image187.png)

11. [Gpt3 with logs](https://www.google.com/url?q=https://www.zebrium.com/blog/using-gpt-3-with-zebrium-for-plain-language-incident-root-cause-from-logs&sa=D&source=editors&ust=1621930682692000&usg=AOvVaw13godTuqvk6J7czhQesScq)

* * *

Metrics
-------

Unsupervised metrics:

Using silhouette score to measure clusters, with a distance metric of your choice (mean w2v, edit distance, mean edit distance, token matching score etc..)

[Drain paper:](https://www.google.com/url?q=http://jmzhu.logpai.com/pub/pjhe_icws2017.pdf&sa=D&source=editors&ust=1621930682694000&usg=AOvVaw1Wn_ZCLludJf95xBrcA6s3)

![](images/image173.png)

[Tools and Benchmarks for Automated Log Parsing](https://www.google.com/url?q=https://arxiv.org/pdf/1811.03509.pdf&sa=D&source=editors&ust=1621930682695000&usg=AOvVaw3PIgWYRJa753KGN8Lmiv9R)
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.  Accuracy measures the ability of a log parser in distinguishing constant parts and variable parts. Accuracy is one main focus of existing log parsing studies because an inaccurate log parser could greatly limit the effectiveness of the downstream log mining tasks \[9\].  
      
    Supervised Accuracy Metric: PA metric is the ratio of correctly parsed log messages over the total number of log messages:  
    

* For fairness of comparison, we apply the same preprocessing rules (e.g., IP or number replacement) to each log parser.

* After parsing, each log message has an event template, which in turn corresponds to a group of messages of the same template.  
    
* A log message is considered correctly parsed if and only if its event template corresponds to the same group of log messages as the ground truth does. For example, if a log sequence \[E1, E2, E2\] is parsed to \[E1, E4, E5\], we get PA=1/3, since the 2nd and 3rd messages are not grouped together.  
    
* In contrast to standard evaluation metrics that are used in previous studies, such as precision, recall, and F1-measure \[9\], \[22\], \[28\], PA is a more rigorous metric. In PA, partially matched events are considered incorrect.

* The parameters of all the log parsers are fine-tuned through over 10 runs and the best results are reported to avoid bias from randomization.  
      
    

2.  Robustness of a log parser measures the consistency of its accuracy under log datasets of different sizes or from different systems. A robust log parser should perform consistently across different datasets, and thus can be used in the versatile production environment.  
      
    Robustness is crucial to the practical use of a log parser in production environments. In this part, we evaluate the robustness of log parsers from two aspects: 1) robustness across different types of logs and 2) robustness on different volumes of logs.  
    
3.  Efficiency measures the processing speed of a log parser. We evaluate the efficiency by recording the time that a parser takes to parse a specific dataset. The less time a log parser consumes, the higher efficiency it provides.  
      
    Efficiency is an important aspect of log parsers to consider in order to handle log data in large scale. To measure the efficiency of a log parser, we record the running time it needs to finish the entire parsing process. Similar to the setting of the previous experiment, we evaluate six log parsers on three log datasets.

\[9\] - [An Evaluation Study on Log Parsing and Its Use in Log Mining](https://www.google.com/url?q=http://jmzhu.logpai.com/pub/pjhe_dsn2016.pdf&sa=D&source=editors&ust=1621930682699000&usg=AOvVaw1Tb0u_6DQFD5qEDzlxxElt)

a commonly used evaluation metric for clustering algorithms, to evaluate the parsing accuracy of log parsing methods. To calculate Fmeasure, we manually obtain the ground truths for all logs of these dataset. It is possible because we iteratively filter out logs with confirmed event using regular expression. Experiments about LKE and LogSig are run 10 times to avoid bias of clustering algorithms, while others are run once because they are deterministic. We note here that only the parts of free-text log message contents are used in evaluating the log parsing methods

\[22\] \- [https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.503.7668&rep=rep1&type=pdf](https://www.google.com/url?q=https://citeseerx.ist.psu.edu/viewdoc/download?doi%3D10.1.1.503.7668%26rep%3Drep1%26type%3Dpdf&sa=D&source=editors&ust=1621930682700000&usg=AOvVaw2zA0B_uGcmJVaXd2BPsc2T)

. These cluster descriptions then became our gold standard, against which to measure the performance of the other algorithms as an information retrieval (IR) task. As in classic IR, our performance metrics are Recall, Precision and F-Measure, which are described in \[17\]. The True Positive(TP), False Positive(FP) and False Negative(FN) values were derived by comparing the set of manually produced line formats to the set of retrieved formats produced by each algorithm. In our evaluation a line format is still considered a FP even if matches a manually produced line format to some degree, the match has to be exact for it to be considered a TP. The next section gives more details about the results of our experiments.

\[28\] -[A search-based approach for accurate identification of log message](https://www.google.com/url?q=https://orbilu.uni.lu/bitstream/10993/35286/1/ICPC-2018.pdf&sa=D&source=editors&ust=1621930682701000&usg=AOvVaw0J-jRlWBtcNSogK3dy0Naj)

![](images/image6.png)

In \[22\]: \[17\] \- Wikipedia.org. Precision and Recall - Wikipedia, the free encyclopedia. Published to the web, http://en.wikipedia.org/wiki/Precision and Recall. Last checked April 23, 2009.

In \[22\]: ref \[30\] & \[31\] - [evaluation of clustering](https://www.google.com/url?q=https://nlp.stanford.edu/IR-book/html/htmledition/evaluation-of-clustering-1.html&sa=D&source=editors&ust=1621930682703000&usg=AOvVaw3Jj7oA3odkeplJNcyMPFmL) by stanford

This section introduces four external criteria of clustering quality. Purityis a simple and transparent evaluation measure. Normalized mutual informationcan be information-theoretically interpreted. The Rand indexpenalizes both false positive and false negative decisions during clustering. The F measure in addition supports differential weighting of these two types of errors.

High purity is easy to achieve when the number of clusters is large \- in particular, purity is 1 if each document gets its own cluster. Thus, we cannot use purity to trade off the quality of the clustering against the number of clusters.

MI has the same problem as purity: it does not penalize large cardinalities and thus does not formalize our bias that, other things being equal, fewer clusters are better.

Because NMI is normalized, we can use it to compare clusterings with different numbers of clusters.

The Rand index gives equal weight to false positives and false negatives. Separating similar documents is sometimes worse than putting pairs of dissimilar documents in the same cluster.

![](images/image214.png)

The Rand index gives equal weight to false positives and false negatives. Separating similar documents is sometimes worse than putting pairs of dissimilar documents in the same cluster. We can use the F measuremeasuresperf to penalize false negatives more strongly than false positives by selecting a value ![$\beta > 1$](images/image262.png), thus giving more weight to recall.

![](images/image139.png)

* * *

* * *

TIME SERIES
===========

1.  [Random walk](https://www.google.com/url?q=https://machinelearningmastery.com/gentle-introduction-random-walk-times-series-forecasting-python/&sa=D&source=editors&ust=1621930682711000&usg=AOvVaw2x7UDW3ORkG6UtWTckte4L) \- what is?

![](images/image8.png)

1.  [Time series decomposition book](https://www.google.com/url?q=https://otexts.com/fpp2/forecasting-decomposition.html&sa=D&source=editors&ust=1621930682712000&usg=AOvVaw3YW_BYpGLGfhyfTpr_tu3a) \- stl x11 seats
2.  [Mastery on ts decomposition](https://www.google.com/url?q=https://machinelearningmastery.com/decompose-time-series-data-trend-seasonality/&sa=D&source=editors&ust=1621930682713000&usg=AOvVaw3SBvgx-nPRevNCi4E16CWt)

TOOLS
-----

1.  SKtime - is a sk-based api, [medium](https://www.google.com/url?q=https://towardsdatascience.com/sktime-a-unified-python-library-for-time-series-machine-learning-3c103c139a55&sa=D&source=editors&ust=1621930682713000&usg=AOvVaw3Z8J5JBAtAs72ROYDhIQ8Z), integrates algos from tsfresh and tslearn
2.  (really good) [A LightGBM Autoregressor — Using Sktime](https://www.google.com/url?q=https://towardsdatascience.com/a-lightgbm-autoregressor-using-sktime-6402726e0e7b&sa=D&source=editors&ust=1621930682714000&usg=AOvVaw3ILxMhw_RfPKY189CS2VWH), explains about the basics in time series prediction, splitting, next step, delayed step, multi step, deseason.
3.  [SKtime-DL - using keras and DL](https://www.google.com/url?q=https://github.com/sktime/sktime-dl&sa=D&source=editors&ust=1621930682715000&usg=AOvVaw3KofiWFn8_PZpxW8iiwYKV)
4.  [TSFresh](https://www.google.com/url?q=http://tsfresh.readthedocs.io&sa=D&source=editors&ust=1621930682715000&usg=AOvVaw0SfnGxIIFutWJsMhPwhXtP) \- extracts 1200 features, filters them using FDR for time series classification etc
5.  [TSlearn](https://www.google.com/url?q=http://tslearn.readthedocs.io&sa=D&source=editors&ust=1621930682716000&usg=AOvVaw1Nz1fbuYCEvcfYlCSC4m2h) \- DTW, shapes, shapelets (keras layer), time series kmeans/clustering/svm/svr/KNN/bary centers/PAA/SAX ![](images/image56.png)
6.  [DTAIDistance](https://www.google.com/url?q=https://dtaidistance.readthedocs.io/en/latest/index.html&sa=D&source=editors&ust=1621930682716000&usg=AOvVaw0HFP-IX02lBNH5LtMD7xP3)\- Library for time series distances (e.g. Dynamic Time Warping) used in the [DTAI Research Group](https://www.google.com/url?q=https://dtai.cs.kuleuven.be/&sa=D&source=editors&ust=1621930682717000&usg=AOvVaw0470y-JEvNtojSnp70A6TO). The library offers a pure Python implementation and a faster implementation in C. The C implementation has only Cython as a dependency. It is compatible with Numpy and Pandas and implemented to avoid unnecessary data copy operations  
    [dtaidistance.clustering.hierarchical](https://www.google.com/url?q=https://dtaidistance.readthedocs.io/en/latest/modules/clustering/hierarchical.html&sa=D&source=editors&ust=1621930682717000&usg=AOvVaw3tZxDJ5P8w5YhrNtRZKslM)

[Ddtaidistance.clustering.kmeans](https://www.google.com/url?q=https://dtaidistance.readthedocs.io/en/latest/modules/clustering/kmeans.html&sa=D&source=editors&ust=1621930682718000&usg=AOvVaw2qTZ-PFOfxeqgoxaWvCbwK)

[Dtaidistance.clustering.medoids](https://www.google.com/url?q=https://dtaidistance.readthedocs.io/en/latest/modules/clustering/medoids.html&sa=D&source=editors&ust=1621930682718000&usg=AOvVaw11cE7KXUohHjHtPqQNSXeI)

\* Identify anomalies, outliers or abnormal behaviour (see for example the [anomatools package](https://www.google.com/url?q=https://github.com/Vincent-Vercruyssen/anomatools&sa=D&source=editors&ust=1621930682719000&usg=AOvVaw09-AC_HoAOmuLqyBNDpJnh)).

![](images/image117.png)

7.  Semi supervised with DTAIDistance - Active semi-supervised clustering

The recommended method for perform active semi-supervised clustering using DTAIDistance is to use the COBRASfor time series clustering: [https://github.com/ML-KULeuven/cobras](https://www.google.com/url?q=https://github.com/ML-KULeuven/cobras&sa=D&source=editors&ust=1621930682720000&usg=AOvVaw2WP-ZqHB0l1BArByyxtXjK). COBRAS is a library for semi-supervised time series clustering using pairwise constraints, which natively supports both dtaidistance.dtw and kshape.

8.  [Affine warp](https://www.google.com/url?q=https://github.com/ahwillia/affinewarp&sa=D&source=editors&ust=1621930682721000&usg=AOvVaw1e9WNoOmmi8YSviTiahCTP), a neural net with time warping -  as part of the following manuscript, which focuses on analysis of large-scale neural recordings (though this code can be also be applied to many other data types)
9.  [Neural warp](https://www.google.com/url?q=https://github.com/josifgrabocka/neuralwarp&sa=D&source=editors&ust=1621930682722000&usg=AOvVaw1sULjosYRMNrJPhwzvQLz_)\- [NeuralWarp](https://www.google.com/url?q=https://arxiv.org/pdf/1812.08306.pdf&sa=D&source=editors&ust=1621930682722000&usg=AOvVaw2MQryC9lu2ZwbfTQUeczJ6): Time-Series Similarity with Warping Networks

[A great introduction into time series](https://www.google.com/url?q=https://medium.com/making-sense-of-data/time-series-next-value-prediction-using-regression-over-a-rolling-window-228f0acae363&sa=D&source=editors&ust=1621930682723000&usg=AOvVaw0hLz7zHUZUuso-JAhizzrZ)\- “The approach is to come up with a list of features that captures the temporal aspects so that the auto correlation information is not lost.” basically tells us to take sequence features and create (auto)-correlated new variables using a time window, i.e., “Time series forecasts as regression that factor in autocorrelation as well.”. we can transform raw features into other type of features that explain the relationship in time between features. we measure success using loss functions, MAE RMSE MAPE RMSEP AC-ERROR-RATE

[Interesting idea](https://www.google.com/url?q=http://blog.kaggle.com/2016/02/03/rossmann-store-sales-winners-interview-2nd-place-nima-shahbazi/&sa=D&source=editors&ust=1621930682724000&usg=AOvVaw0cMb9h6lCTZoRCssOgS7n8) on how to define ‘time series’ dummy variables that utilize beginning\\end of certain holiday events, including important information on what NOT to filter even if it seems insignificant, such as zero sales that may indicate some relationship to many sales the following day.

![](images/image89.png)

[Time series patterns:](https://www.google.com/url?q=https://www.otexts.org/fpp/2/1&sa=D&source=editors&ust=1621930682725000&usg=AOvVaw0c87fufqJ5FuTWCuZWATCk)

* A trend (a,b,c) exists when there is a long-term increase or decrease in the data.
* A seasonal (a - big waves) pattern occurs when a time series is affected by seasonal factors such as the time of the year or the day of the week. The monthly sales induced by the change in cost at the end of the calendar year.
* A cycle (a) occurs when the data exhibit rises and falls that are not of a fixed period - sometimes years.

[Some statistical measures](https://www.google.com/url?q=https://www.otexts.org/fpp/2/2&sa=D&source=editors&ust=1621930682726000&usg=AOvVaw1Kin6OCNEm5xXYG9ru2H2-) (mean, median, percentiles, iqr, std dev, bivariate statistics - correlation between variables)

Bivariate Formula: this correlation measures the extent of a linear relationship between two variables. high number = high correlation between two variable. The value of r always lies between -1 and 1 with negative values indicating a negative relationship and positive values indicating a positive relationship. Negative = decreasing, positive = increasing.![](images/image171.png)

But correlation can LIE, the following has 0.8 correlation for all of the graphs:

![](images/image237.png)

Autocorrelation measures the linear relationship between lagged values of a time series.

L8 is correlated, and has a high measure of 0.83

* White-noise has autocorrelation of 0.![](images/image142.png)

[Forecasting methods](https://www.google.com/url?q=https://www.otexts.org/fpp/2/3&sa=D&source=editors&ust=1621930682729000&usg=AOvVaw0vQfg_KqpdTvsL1eG_3Lko)
------------------------------------------------------------------------------------------------------------------------------------------------------------

* Average: Forecasts of all future values are equal to the mean of the historical data.
* Naive: Forecasts are simply set to be the value of the last observation.
* Seasonal Naive: forecast to be equal to the last observed value from the same season of the year
* Drift: A variation on the naïve method is to allow the forecasts to increase or decrease over time, the drift is set to be the average change seen in the historical data.

[Data Transformations](https://www.google.com/url?q=https://www.otexts.org/fpp/2/4&sa=D&source=editors&ust=1621930682731000&usg=AOvVaw1syifkrgG0uolkrk7za7sk)
-------------------------------------------------------------------------------------------------------------------------------------------------------------

* Log
* Box cox
* Back transform
* Calendrical adjustments
* Inflation adjustment

[Transforming time series data to tabular (in order to use tabular based approach)](https://www.google.com/url?q=https://towardsdatascience.com/approaching-time-series-with-a-tree-based-model-87c6d1fb6603&sa=D&source=editors&ust=1621930682732000&usg=AOvVaw0EgaO2ieiqPpZRVJKy-AW7)

SPLITTING TIME SERIES DATA
--------------------------

1.  SK-lego [With a gap](https://www.google.com/url?q=https://scikit-lego.readthedocs.io/en/latest/timegapsplit.html&sa=D&source=editors&ust=1621930682733000&usg=AOvVaw1cbzRV2bejJzIk1t9DcUfT)

[Evaluate forecast accuracy](https://www.google.com/url?q=https://www.otexts.org/fpp/2/5&sa=D&source=editors&ust=1621930682733000&usg=AOvVaw3yACt4dhmKZ0243FYeV9gS)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

![](images/image245.png)

* Dummy variables: sunday, monday, tues,wed,thurs, friday. NO SATURDAY!
* notice that only six dummy variables are needed to code seven categories. That is because the seventh category (in this case Sunday) is specified when the dummy variables are all set to zero. Many beginners will try to add a seventh dummy variable for the seventh category. This is known as the "dummy variable trap" because it will cause the regression to fail.
* Outliers: If there is an outlier in the data, rather than omit it, you     can use a dummy variable to remove its effect. In this case, the dummy variable takes value one for that observation and zero everywhere else.
* Public holidays: For daily data, the effect of public holidays can be accounted for by including a dummy variable predictor taking value one on public holidays and zero elsewhere.
* Easter: is different from most holidays because it is not held on the same date each year and the effect can last for several days. In this case, a dummy variable can be used with value one where any part of the holiday falls in the particular time period and zero otherwise.
* Trading days: The number of trading days in a month can vary considerably and can have a substantial effect on sales data. To allow for this, the number of trading days in each month can be included as a predictor. An alternative that allows for the effects of different days of the week has the following predictors. # Mondays in month;# Tuesdays in month;# Sundays in month.
* Advertising: $advertising for previous month;$advertising for two months previously

[Rolling window analysis](https://www.google.com/url?q=https://link.springer.com/chapter/10.1007%252F978-0-387-32348-0_9&sa=D&source=editors&ust=1621930682737000&usg=AOvVaw06afCaYgfjakhHiyQaQ4r2)
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 “compute parameter estimates over a rolling window of a fixed size through the sample. If the parameters are truly constant over the entire sample, then the estimates over the rolling windows should not be too different. If the parameters change at some point during the sample, then the rolling estimates should capture this instability”

[Moving average window](https://www.google.com/url?q=https://www.otexts.org/fpp/6/2&sa=D&source=editors&ust=1621930682738000&usg=AOvVaw0U49cIS06bKE-1syS1gmp7)
--------------------------------------------------------------------------------------------------------------------------------------------------------------

 estimate the trend cycle

* 3-5-7-9? If its too large its going to flatten the curve, too low its going to be similar to the actual curve.

* two tier moving average, first 4 then 2 on the resulted moving average.

[Visual example](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D_YXoRTQQI3U&sa=D&source=editors&ust=1621930682739000&usg=AOvVaw1BwikD5CRypuBiJUs78Ag2) of ARIMA algorithm - captures the time series trend or forecast.

Decomposition
-------------

1.  [Creating](https://www.google.com/url?q=https://scikit-lego.readthedocs.io/en/latest/preprocessing.html%23Repeating-Basis-Function-Transformer&sa=D&source=editors&ust=1621930682740000&usg=AOvVaw2irZiGXQq_k-vLcY0Foej8) curves to explain a complex seasonal fit.
2.  ![](images/image234.png)
3.  ![](images/image222.png)

Weighted “window”
-----------------

[1, scikit-lego with a decay estimator](https://www.google.com/url?q=https://scikit-lego.readthedocs.io/en/latest/meta.html%23Decayed-Estimation&sa=D&source=editors&ust=1621930682741000&usg=AOvVaw2DO9KE3428uqIjqHeCiRSw)

![](images/image50.png)

[Time Series Components](https://www.google.com/url?q=http://machinelearningmastery.com/time-series-forecasting/&sa=D&source=editors&ust=1621930682741000&usg=AOvVaw3dFJ84eQov8Gb0RdGPRWY9)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.  Level. The baseline value for the series if it were a straight line.
2.  Trend. The optional and often linear increasing or decreasing behavior of the series over time.
3.  Seasonality. The optional repeating patterns or cycles of behavior over time.
4.  Noise. The optional variability in the observations that cannot be explained by the model.

All time series have a level, most have noise, and the trend and seasonality are optional.

One step forecast using a window of “1” and a typical sample “time, measure1, measure2”:

* linear/nonlinear classifiers: predict a single output value - using the t-1 previous line, i.e., “measure1 t, measure 2 t, measure 1 t+1, measure 2 t+1 (as the class)”
* Neural networks: predict multiple output values, i.e., “measure1 t, measure 2 t, measure 1 t+1(class1), measure 2 t+1(class2)”

One-Step Forecast: This is where the next time step (t+1) is predicted.

Multi-Step Forecast: This is where two or more future time steps are to be predicted.

Multi-step forecast using a window of “1” and a typical sample “time, measure1”, i.e., using the current value input we label it as the two future input labels:

* “measure1 t, measure1 t+1(class) , measure1 t+2(class1)”

* * *

[This article explains](https://www.google.com/url?q=http://web.engr.oregonstate.edu/~tgd/publications/mlsd-ssspr.pdf&sa=D&source=editors&ust=1621930682745000&usg=AOvVaw38TiLUIpVuMqyd1mQS3Wmt) about ML Methods for Sequential Supervised Learning - Six methods that have been applied to solve sequential supervised learning problems:

1.  sliding-window methods - converts a sequential supervised problem into a classical supervised problem
2.  recurrent sliding windows
3.  hidden Markov models
4.  maximum entropy Markov models
5.  input-output Markov models
6.  conditional random fields
7.  graph transformer networks

STATIONARY TIME SERIES
----------------------

[What is?](https://www.google.com/url?q=https://machinelearningmastery.com/time-series-data-stationary-python/&sa=D&source=editors&ust=1621930682747000&usg=AOvVaw2AM1D4M88Fdn9DPRJGA9tp) A time series without a trend or seasonality, in other words non-stationary has a trend or seasonality

There are ways to [remove the trend and seasonality](https://www.google.com/url?q=https://machinelearningmastery.com/difference-time-series-dataset-python/&sa=D&source=editors&ust=1621930682748000&usg=AOvVaw0qBYlSrk6gRdX9BZMYFnVk), i.e., take the difference between time points.

1.  T+1 - T
2.  Bigger lag to support seasonal changes
3.  pandas.diff()
4.  Plot a histogram, plot a log(X) as well.
5.  Test for the unit root null hypothesis - i.e., use the Augmented dickey fuller test to determine if two samples originate in a stationary or a non-stationary (seasonal/trend) time series

[Shay on stationary time series, AR, ARMA](https://www.google.com/url?q=https://towardsdatascience.com/stationarity-in-time-series-analysis-90c94f27322&sa=D&source=editors&ust=1621930682749000&usg=AOvVaw3ko5kDzli6z7yD_s4eCwv_)

(amazing) [STL](https://www.google.com/url?q=https://otexts.com/fpp2/stl.html&sa=D&source=editors&ust=1621930682749000&usg=AOvVaw0xmoN6dqHUXOYVQqSNUORx) and more.

SHORT TIME SERIES
-----------------

1.  [Short time series](https://www.google.com/url?q=https://robjhyndman.com/hyndsight/short-time-series/&sa=D&source=editors&ust=1621930682750000&usg=AOvVaw1NWSJSQOthombPiZfhGYHn)
2.  [PDarima -](https://www.google.com/url?q=https://towardsdatascience.com/efficient-time-series-using-pythons-pmdarima-library-f6825407b7f0&sa=D&source=editors&ust=1621930682750000&usg=AOvVaw0r96CWvuHHBIb5CJVn_-tn) Pmdarima‘s auto_arima function is extremely useful when building an ARIMA model as it helps us identify the most optimal p,d,q parameters and return a fitted ARIMA model.
3.  [Min sample size for short seasonal time series](https://www.google.com/url?q=https://robjhyndman.com/papers/shortseasonal.pdf&sa=D&source=editors&ust=1621930682751000&usg=AOvVaw1suqxpKYi7XOPg0hQRjlNx)
4.  [More mastery on short time series.](https://www.google.com/url?q=https://machinelearningmastery.com/time-series-forecasting-methods-in-python-cheat-sheet/?fbclid%3DIwAR0iU9B-wsRaOPOY13F4xesGWUMevRBuPck5I9jTNlV5zmPFCX1NoG05_jI&sa=D&source=editors&ust=1621930682751000&usg=AOvVaw0zRDYA4P3cCSK3WyURb8f3)

1.  Autoregression (AR)
2.  Moving Average (MA)
3.  Autoregressive Moving Average (ARMA)
4.  Autoregressive Integrated Moving Average (ARIMA)
5.  Seasonal Autoregressive Integrated Moving-Average (SARIMA)
6.  Seasonal Autoregressive Integrated Moving-Average with Exogenous Regressors (SARIMAX)
7.  Vector Autoregression (VAR)
8.  Vector Autoregression Moving-Average (VARMA)
9.  Vector Autoregression Moving-Average with Exogenous Regressors (VARMAX)
10. Simple Exponential Smoothing (SES)
11. Holt Winter’s Exponential Smoothing (HWES)

Predicting actual Values of time series using observations

1.  [Using kalman filters](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DCaCcOwJPytQ&sa=D&source=editors&ust=1621930682754000&usg=AOvVaw3GWvsphwrHbYOUp_ZI7PKZ) \- explains the concept etc, 1 out of 55 videos.

[Kalman filters in matlab](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D4OerJmPpkRg&sa=D&source=editors&ust=1621930682754000&usg=AOvVaw3AHIuUGAQu8g9YWyBcG9CI)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

[LTSM for time series](https://www.google.com/url?q=http://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/&sa=D&source=editors&ust=1621930682755000&usg=AOvVaw3kMr2BGT4Rjm_BWMy_1KYc)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

There are three types of gates within a unit:

* Forget Gate: conditionally decides what information to throw away from the block.
* Input Gate: conditionally decides which values from the input to update the memory state.
* Output Gate: conditionally decides what to output based on input and the memory of the block.

Using lstm to predict sun spots, has some autocorrelation usage

* [Part 1](https://www.google.com/url?q=https://www.business-science.io/timeseries-analysis/2018/04/18/keras-lstm-sunspots-time-series-prediction.html&sa=D&source=editors&ust=1621930682757000&usg=AOvVaw0G5mYzNE3xJpucdlaSAEYB)
* [Part 2](https://www.google.com/url?q=https://www.business-science.io/timeseries-analysis/2018/07/01/keras-lstm-sunspots-part2.html&sa=D&source=editors&ust=1621930682758000&usg=AOvVaw0s9r2tsSr2v3OSYolj8B0V)

CLASSIFICATION
--------------

1.  [Stackexchange](https://www.google.com/url?q=https://stats.stackexchange.com/questions/131281/dynamic-time-warping-clustering/131284&sa=D&source=editors&ust=1621930682759000&usg=AOvVaw2aWVjNpOm6BqDk05NW9Xr_)\- Yes, you can use DTWapproach for classification and clustering of time series. I've compiled the following resources, which are focused on this very topic (I've recently answered a similar question, but not on this site, so I'm copying the contents here for everybody's convenience):

* UCR Time Series Classification/Clustering: [main page](https://www.google.com/url?q=http://www.cs.ucr.edu/~eamonn/time_series_data&sa=D&source=editors&ust=1621930682759000&usg=AOvVaw1ZKIzLChyhVilmR7XutntS), [software page](https://www.google.com/url?q=http://www.cs.ucr.edu/~eamonn/UCRsuite.html&sa=D&source=editors&ust=1621930682760000&usg=AOvVaw04UgHslmqgGPohYkdKSpdO)and [corresponding paper](https://www.google.com/url?q=http://www.cs.ucr.edu/~eamonn/SIGKDD_trillion.pdf&sa=D&source=editors&ust=1621930682760000&usg=AOvVaw0ZIep3uHX87fz6cjmxHHTp)
* Time Series Classification and Clustering with Python: [a blog post](https://www.google.com/url?q=http://alexminnaar.com/2014/04/16/Time-Series-Classification-and-Clustering-with-Python.html&sa=D&source=editors&ust=1621930682761000&usg=AOvVaw0-u17efVDbEl25soH0Ejmz)
* Capital Bikeshare: Time Series Clustering: [another blog post](https://www.google.com/url?q=http://ofdataandscience.blogspot.com/2013/03/capital-bikeshare-time-series-clustering.html&sa=D&source=editors&ust=1621930682762000&usg=AOvVaw1SXih0XP0jhoSQ_e_qs3q4)
* Time Series Classification and Clustering: [ipython notebook](https://www.google.com/url?q=http://nbviewer.ipython.org/github/alexminnaar/time-series-classification-and-clustering/blob/master/Time%2520Series%2520Classification%2520and%2520Clustering.ipynb&sa=D&source=editors&ust=1621930682763000&usg=AOvVaw31jch9-bpjwHX9hwIbbbZF)
* Dynamic Time Warping using rpy and Python: [another blog post](https://www.google.com/url?q=https://nipunbatra.wordpress.com/2013/06/09/dynamic-time-warping-using-rpy-and-python&sa=D&source=editors&ust=1621930682764000&usg=AOvVaw3skYDvGIJksub_Yx66hFT9)
* Mining Time-series with Trillions of Points: Dynamic Time Warping at Scale: [another blog post](https://www.google.com/url?q=http://practicalquant.blogspot.com/2012/10/mining-time-series-with-trillions-of.html&sa=D&source=editors&ust=1621930682764000&usg=AOvVaw1_RIAFF62dpKEdFynzr89s)
* Time Series Analysis and Mining in R(to add R to the mix): [yet another blog post](https://www.google.com/url?q=http://rdatamining.wordpress.com/2011/08/23/time-series-analysis-and-mining-with-r&sa=D&source=editors&ust=1621930682765000&usg=AOvVaw333b-TN2okMnhSl7vvhk7V)
* And, finally, two tools implementing/supporting DTW, to top it off: [R package](https://www.google.com/url?q=http://rdatamining.wordpress.com/2011/08/23/time-series-analysis-and-mining-with-r&sa=D&source=editors&ust=1621930682766000&usg=AOvVaw1LRhz1fKKclzaY9JEr6viU)and [Python module](https://www.google.com/url?q=http://mlpy.sourceforge.net/&sa=D&source=editors&ust=1621930682766000&usg=AOvVaw3GNiLnsfpKx7spHoeS32Ey)

CLUSTERING TS
-------------

1.  [Clustering time series, subsequences with a rolling window, the pitfall.](https://www.google.com/url?q=https://towardsdatascience.com/dont-make-this-mistake-when-clustering-time-series-data-d9403f39bbb2&sa=D&source=editors&ust=1621930682767000&usg=AOvVaw27bhr7SeInYtzlzI3vAwvA)
2.  [Clustering using tslearn](https://www.google.com/url?q=https://tslearn.readthedocs.io/en/stable/user_guide/clustering.html&sa=D&source=editors&ust=1621930682767000&usg=AOvVaw1h1D_EeN3z-Z_tG62QcdRY)
3.  [Kmeans for variable length](https://www.google.com/url?q=https://medium.com/@iliazaitsev/how-to-classify-a-dataset-with-observations-of-various-length-96fab8e95baf&sa=D&source=editors&ust=1621930682768000&usg=AOvVaw0Xc0x96QwPlnRqduu92XhJ) , [notebook](https://www.google.com/url?q=https://github.com/devforfu/Blog/blob/master/trees/scikit_learn.py&sa=D&source=editors&ust=1621930682768000&usg=AOvVaw2GvtBxhZ16_KLvBhf7cQli)

ANOMALY DETECTION TS
--------------------

4.  [What is stationary (process](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Stationary_process&sa=D&source=editors&ust=1621930682769000&usg=AOvVaw0hpIRLlsisAQY6D12v8bOf)), [stationary time series analysis](https://www.google.com/url?q=https://towardsdatascience.com/stationarity-in-time-series-analysis-90c94f27322&sa=D&source=editors&ust=1621930682769000&usg=AOvVaw1sgA7Smv2qX1mBRr8PTN8V) (shay palachi),
5.  [mastery on arimas](https://www.google.com/url?q=https://machinelearningmastery.com/time-series-forecasting-methods-in-python-cheat-sheet/?fbclid%3DIwAR0iU9B-wsRaOPOY13F4xesGWUMevRBuPck5I9jTNlV5zmPFCX1NoG05_jI&sa=D&source=editors&ust=1621930682770000&usg=AOvVaw3Q96aoTVOV-XhAFELS9R4C)
6.  [TS anomaly algos (stl, trees, arima)](https://www.google.com/url?q=https://blog.statsbot.co/time-series-anomaly-detection-algorithms-1cef5519aef2&sa=D&source=editors&ust=1621930682770000&usg=AOvVaw2xoyVcW_C5QIHJu5Z4glPe)
7.  [AD techniques](https://www.google.com/url?q=https://medium.com/dp6-us-blog/anomaly-detection-techniques-c3817e8e7b2f&sa=D&source=editors&ust=1621930682771000&usg=AOvVaw1j-ydUKtx1ui2Zsgh5cg9Y), part [2](https://www.google.com/url?q=https://medium.com/dp6-us-blog/anomaly-detection-techniques-part-ii-9a08b6562619&sa=D&source=editors&ust=1621930682771000&usg=AOvVaw1dJd4YOMm_4rrfRq1zf6nj), part [3](https://www.google.com/url?q=https://medium.com/dp6-us-blog/anomaly-detection-techniques-part-iii-d27e7b0d6c8a&sa=D&source=editors&ust=1621930682771000&usg=AOvVaw3lilqXDNrWydfhkc2PUgHP)
8.  [Z-score, modified z-score and iqr an intro why z-score is not robust](https://www.google.com/url?q=http://colingorrie.github.io/outlier-detection.html&sa=D&source=editors&ust=1621930682772000&usg=AOvVaw0CyPucifW7mrX3QrzZSJE4)
9.  [Adtk](https://www.google.com/url?q=https://adtk.readthedocs.io/en/stable/userguide.html&sa=D&source=editors&ust=1621930682772000&usg=AOvVaw2fwPlC3I5csp9zoNbr1hC9) a sklearn-like toolkit with an amazing intro, various algorithms for non seasonal and seasonal, transformers, ensembles.
10. [Awesome TS anomaly detection](https://www.google.com/url?q=https://github.com/rob-med/awesome-TS-anomaly-detection&sa=D&source=editors&ust=1621930682773000&usg=AOvVaw3zhUJC2L3TBV3D5zbEidD6) on github
11. [Transfer learning toolkit](https://www.google.com/url?q=https://github.com/FuzhenZhuang/Transfer-Learning-Toolkit&sa=D&source=editors&ust=1621930682773000&usg=AOvVaw0cC93kuuC8M-WSA4WvshV2), [paper and benchmarks](https://www.google.com/url?q=https://arxiv.org/pdf/1911.08967.pdf&sa=D&source=editors&ust=1621930682774000&usg=AOvVaw0GduZciv5LT5by2fTZQYCt)
12. [Ransac is a good baseline](https://www.google.com/url?q=https://medium.com/@iamhatesz/random-sample-consensus-bd2bb7b1be75&sa=D&source=editors&ust=1621930682774000&usg=AOvVaw1gHCS7A3erGaMWB4vETiqn) \- random sample consensus for outlier detection

1.  [Ransac](https://www.google.com/url?q=https://medium.com/@angel.manzur/got-outliers-ransac-them-f12b6b5f606e&sa=D&source=editors&ust=1621930682774000&usg=AOvVaw1wDNXTJQoy_3mXV6fMhbFT), [2](https://www.google.com/url?q=https://medium.com/@saurabh.dasgupta1/outlier-detection-using-the-ransac-algorithm-de52670adb4a&sa=D&source=editors&ust=1621930682775000&usg=AOvVaw0Y4v-xHgJHJavhi9qLpdNU), [3](https://www.google.com/url?q=https://towardsdatascience.com/detecting-the-fault-line-using-k-mean-clustering-and-ransac-9a74cb61bb96&sa=D&source=editors&ust=1621930682775000&usg=AOvVaw0pbjUV6s_W4yQL7TpAoIeo), [4](https://www.google.com/url?q=http://www.cs.tau.ac.il/~turkel/imagepapers/RANSAC4Dummies.pdf&sa=D&source=editors&ust=1621930682775000&usg=AOvVaw3QWDfonGXs3vkyAqPsG6iU), 5, 6
2.  You can feed ransac with tsfresh/tslearn features.

13. [Anomaly detection for time series](https://www.google.com/url?q=https://medium.com/@jetnew/anomaly-detection-of-time-series-data-e0cb6b382e33&sa=D&source=editors&ust=1621930682776000&usg=AOvVaw2iDXlftX8JfGNwfEOa-sGK),
14. AD for TS, recommended by DTAIDistance, [anomatools](https://www.google.com/url?q=https://github.com/Vincent-Vercruyssen/anomatools&sa=D&source=editors&ust=1621930682777000&usg=AOvVaw3LhH9iE2B_5UroGGGZFBGf)
15. STL:

1.  [AD where anomalies coincide with seasonal peaks!!](https://www.google.com/url?q=https://medium.com/@richa.mishr01/anomaly-detection-in-seasonal-time-series-where-anomalies-coincide-with-seasonal-peaks-9859a6a6b8ba&sa=D&source=editors&ust=1621930682777000&usg=AOvVaw3dBpyLOJF90RzrJLv5Y4X1)
2.  [AD challenges, stationary, seasonality, trend](https://www.google.com/url?q=https://cloudfabrix.com/blog/aiops/anomaly-detection-time-series-data/&sa=D&source=editors&ust=1621930682778000&usg=AOvVaw2BMdDTXxDZXTN3Vbsyh252)
3.  [Rt anomaly detection for time series pinterest](https://www.google.com/url?q=https://medium.com/pinterest-engineering/building-a-real-time-anomaly-detection-system-for-time-series-at-pinterest-a833e6856ddd&sa=D&source=editors&ust=1621930682779000&usg=AOvVaw3RCOfnmmHRvgSQ_SYbOHs6) using stl decomposition
4.  [AD](https://www.google.com/url?q=https://medium.com/wwblog/anomaly-detection-using-stl-76099c9fd5a7&sa=D&source=editors&ust=1621930682779000&usg=AOvVaw3dEn6_HF__hqjYv8bmmN5w)

16. Sliding windows

1.  [Solving sliding window problems](https://www.google.com/url?q=https://medium.com/outco/how-to-solve-sliding-window-problems-28d67601a66&sa=D&source=editors&ust=1621930682780000&usg=AOvVaw0gqlPblJ1jdqHvaandHS1d)
2.  [Rolling window regression](https://www.google.com/url?q=https://medium.com/making-sense-of-data/time-series-next-value-prediction-using-regression-over-a-rolling-window-228f0acae363&sa=D&source=editors&ust=1621930682781000&usg=AOvVaw1AbAXI0VaJ2Kb49DN-nm2B)

17. Forecasting using Arima [1](https://www.google.com/url?q=https://towardsdatascience.com/time-series-forecasting-using-auto-arima-in-python-bb83e49210cd&sa=D&source=editors&ust=1621930682782000&usg=AOvVaw3zP9bh1t_FKjz017msFz_p), [2](https://www.google.com/url?q=http://alkaline-ml.com/pmdarima/&sa=D&source=editors&ust=1621930682782000&usg=AOvVaw0wX6PDm7iMXl1dFChgtnPO)
18. Auto arima [1](https://www.google.com/url?q=https://towardsdatascience.com/time-series-forecasting-using-auto-arima-in-python-bb83e49210cd&sa=D&source=editors&ust=1621930682783000&usg=AOvVaw2caIFyJjiIMEMdEZROb5n_), [2](https://www.google.com/url?q=https://stackoverflow.com/questions/22770352/auto-arima-equivalent-for-python&sa=D&source=editors&ust=1621930682783000&usg=AOvVaw1Y_ttNdhW1Ybc3mCxHUcn0), [3](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2018/08/auto-arima-time-series-modeling-python-r/&sa=D&source=editors&ust=1621930682784000&usg=AOvVaw0DXXW4LtL5bssdu5xyKA7i)
19. [Twitters ESD test](https://www.google.com/url?q=https://medium.com/@elisha_12808/time-series-anomaly-detection-with-twitters-esd-test-50cce409ced1&sa=D&source=editors&ust=1621930682784000&usg=AOvVaw3p0xyLnmO2uFT3jyibjN_c) for outliers, using z-score and t test

1.  Another esd test inside [here](https://www.google.com/url?q=https://towardsdatascience.com/anomaly-detection-def662294a4e&sa=D&source=editors&ust=1621930682785000&usg=AOvVaw3OBdUQ4RrVj_zra1bzljJL)

20. [Minimal sample size for seasonal forecasting](https://www.google.com/url?q=https://robjhyndman.com/papers/shortseasonal.pdf&sa=D&source=editors&ust=1621930682785000&usg=AOvVaw1NYhw2A3dmEjcE18oTjngS)
21. [Golden signals](https://www.google.com/url?q=https://www.usenix.org/conference/srecon19asia/presentation/chen-yu&sa=D&source=editors&ust=1621930682786000&usg=AOvVaw3I7OOJUp6sZauuXq0BnY8h), [youtube](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D3T9ZzQQiPSo&sa=D&source=editors&ust=1621930682786000&usg=AOvVaw3POih1KmC2fwMkvqv4-3UB)
22. [Graph-based Anomaly Detection and Description: A Survey](https://www.google.com/url?q=https://arxiv.org/pdf/1404.4679.pdf&sa=D&source=editors&ust=1621930682787000&usg=AOvVaw2NcacqT9FXQ2GF2PBxP9Pp)
23. [Time2vec](https://www.google.com/url?q=https://towardsdatascience.com/time2vec-for-time-series-features-encoding-a03a4f3f937e&sa=D&source=editors&ust=1621930682787000&usg=AOvVaw1nfq906pnqcTDuI8ZrOxhw), [paper](https://www.google.com/url?q=https://arxiv.org/pdf/1907.05321.pdf&sa=D&source=editors&ust=1621930682787000&usg=AOvVaw3GUsXJgkb08Wab1FQSaZpS) (for deep learning, as a layer)

* * *

Dynamic Time Warping (DTW)
--------------------------

DTW, ie., how to compute a better distance for two time series.

1.  [The three myths of using DTW](https://www.google.com/url?q=http://alumni.cs.ucr.edu/~ratana/RatanamC.pdf&sa=D&source=editors&ust=1621930682788000&usg=AOvVaw0T7QHLNLFh1ra4TW0pqy_Z)

Myth 1: The ability of DTW to handle sequences of different lengths is a great advantage, and therefore the simple lower bound that requires different-length sequences to be reinterpolated to equal length is of limited utility \[10\]\[19\]\[21\]. In fact, as we will show, there is no evidence in the literature to suggest this, and extensive empirical evidence presented here suggests that comparing sequences of different lengths and reinterpolating them to equal length produce no statistically significant difference in accuracy or precision/recall.  
Myth 2: Constraining the warping paths is a necessary evil that we inherited from the speech processing community to make DTW tractable, and that we should find ways to speed up DTW with no (or larger) constraints\[19\]. In fact, the opposite is true. As we will show, the 10% constraint on warping inherited blindly from the speech processing community is actually too large for real world data mining.  
Myth 3: There is a need (and room) for improvements in the speed of DTW for data mining applications. In fact, as we will show here, if we use a simple lower bounding technique, DTW is essentially O(n) for data mining applications. At least for CPU time, we are almost certainly at the asymptotic limit for speeding up DTW.

2.  [Youtube - explains everything](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D_K1OsqCicBY&sa=D&source=editors&ust=1621930682789000&usg=AOvVaw1H6yvMb3LZmP12O5JnrZC7)
3.  [Python code](https://www.google.com/url?q=https://github.com/alexminnaar/time-series-classification-and-clustering&sa=D&source=editors&ust=1621930682790000&usg=AOvVaw0NCZZ5J8AObkL9g4U3YPsr)with a [good tutorial.](https://www.google.com/url?q=http://nbviewer.ipython.org/github/alexminnaar/time-series-classification-and-clustering/blob/master/Time%2520Series%2520Classification%2520and%2520Clustering.ipynb&sa=D&source=editors&ust=1621930682790000&usg=AOvVaw2dFjHL8-j3pvkEKf2eiw17)
4.  Another function for dtw distance in python
5.  [Medium](https://www.google.com/url?q=https://medium.com/datadriveninvestor/dynamic-time-warping-dtw-d51d1a1e4afc&sa=D&source=editors&ust=1621930682791000&usg=AOvVaw3LfxDOK6ALKRPODzNi4Axd), mentions prunedDTW, sparseDTW and fastDTW
6.  [DTW in TSLEARN](https://www.google.com/url?q=https://tslearn.readthedocs.io/en/latest/user_guide/dtw.html%23soft-dtw&sa=D&source=editors&ust=1621930682791000&usg=AOvVaw3HR3NwQILPO7JP1sXLvz_-)
7.  [DynamicTimeWarping](https://www.google.com/url?q=https://dynamictimewarping.github.io/py-api/html/api/dtw.dtw.html%23dtw.dtw&sa=D&source=editors&ust=1621930682792000&usg=AOvVaw01u6UZUNltQB06ym0j4YJc) git

![](images/image248.png)

8.  (duplicate above in classification) [Stackexchange](https://www.google.com/url?q=https://stats.stackexchange.com/questions/131281/dynamic-time-warping-clustering/131284&sa=D&source=editors&ust=1621930682793000&usg=AOvVaw3VNmTfzY9VwcxmpHYiXmir)\- Yes, you can use DTWapproach for classification and clustering of time series. I've compiled the following resources, which are focused on this very topic (I've recently answered a similar question, but not on this site, so I'm copying the contents here for everybody's convenience):

* UCR Time Series Classification/Clustering: [main page](https://www.google.com/url?q=http://www.cs.ucr.edu/~eamonn/time_series_data&sa=D&source=editors&ust=1621930682794000&usg=AOvVaw3Xy07rt8jO1eEYU8I7Ti-V), [software page](https://www.google.com/url?q=http://www.cs.ucr.edu/~eamonn/UCRsuite.html&sa=D&source=editors&ust=1621930682794000&usg=AOvVaw2CjjjiVgjAzzNFq_Ciqac6)and [corresponding paper](https://www.google.com/url?q=http://www.cs.ucr.edu/~eamonn/SIGKDD_trillion.pdf&sa=D&source=editors&ust=1621930682794000&usg=AOvVaw3wce-ymaJr55zGTnDFljCA)
* Time Series Classification and Clustering with Python: [a blog post](https://www.google.com/url?q=http://alexminnaar.com/2014/04/16/Time-Series-Classification-and-Clustering-with-Python.html&sa=D&source=editors&ust=1621930682795000&usg=AOvVaw0_y6sDvm7dpF47OqLhdJWz)
* Capital Bikeshare: Time Series Clustering: [another blog post](https://www.google.com/url?q=http://ofdataandscience.blogspot.com/2013/03/capital-bikeshare-time-series-clustering.html&sa=D&source=editors&ust=1621930682795000&usg=AOvVaw0NRs5pmaCDDQhirgA3KTas)
* Time Series Classification and Clustering: [ipython notebook](https://www.google.com/url?q=http://nbviewer.ipython.org/github/alexminnaar/time-series-classification-and-clustering/blob/master/Time%2520Series%2520Classification%2520and%2520Clustering.ipynb&sa=D&source=editors&ust=1621930682796000&usg=AOvVaw0X-G2q3apkJ5JW1TIyCaNN)
* Dynamic Time Warping using rpy and Python: [another blog post](https://www.google.com/url?q=https://nipunbatra.wordpress.com/2013/06/09/dynamic-time-warping-using-rpy-and-python&sa=D&source=editors&ust=1621930682797000&usg=AOvVaw3NSKsePu0Jd5TnR0Gk3-zH)
* Mining Time-series with Trillions of Points: Dynamic Time Warping at Scale: [another blog post](https://www.google.com/url?q=http://practicalquant.blogspot.com/2012/10/mining-time-series-with-trillions-of.html&sa=D&source=editors&ust=1621930682798000&usg=AOvVaw2rv4rT34aHkrCEUKKvlv4Y)
* Time Series Analysis and Mining in R(to add R to the mix): [yet another blog post](https://www.google.com/url?q=http://rdatamining.wordpress.com/2011/08/23/time-series-analysis-and-mining-with-r&sa=D&source=editors&ust=1621930682798000&usg=AOvVaw0WppaXRtIpYpR9I4_9sv8M)
* And, finally, two tools implementing/supporting DTW, to top it off: [R package](https://www.google.com/url?q=http://rdatamining.wordpress.com/2011/08/23/time-series-analysis-and-mining-with-r&sa=D&source=editors&ust=1621930682799000&usg=AOvVaw0OoL9y4HCcHHkZnoJEIBhw)and [Python module](https://www.google.com/url?q=http://mlpy.sourceforge.net/&sa=D&source=editors&ust=1621930682799000&usg=AOvVaw0tCRjdwlxgA23-GlpIB6iS)

9.  [Time Series Hierarchical Clustering using Dynamic Time Warping in Python](https://www.google.com/url?q=https://towardsdatascience.com/time-series-hierarchical-clustering-using-dynamic-time-warping-in-python-c8c9edf2fda5&sa=D&source=editors&ust=1621930682800000&usg=AOvVaw2mM3S1ctl-mhZdEf-Mlu_H)\- [notebook](https://www.google.com/url?q=https://github.com/avchauzov/_articles/blob/master/1.1.trajectoriesClustering.ipynb&sa=D&source=editors&ust=1621930682800000&usg=AOvVaw2EyD2chuxB9926WgFRoPAh)
10. [K-Means with DTW, probably fixed length vectors, using tslearn](https://www.google.com/url?q=https://towardsdatascience.com/how-to-apply-k-means-clustering-to-time-series-data-28d04a8f7da3&sa=D&source=editors&ust=1621930682801000&usg=AOvVaw0GLErwBG5pXbquAFQOtVgq)
11. (nice) [With time series](https://www.google.com/url?q=https://medium.com/@shachiakyaagba_41915/dynamic-time-warping-with-time-series-1f5c05fb8950&sa=D&source=editors&ust=1621930682802000&usg=AOvVaw118lfaOg94G9d65cpqSSSP)

* * *

FOURIER TRANSFORM
=================

It’s a technique to decompose signals into sine and cosine waves

1.  [Deconstructing time series using FT](https://www.google.com/url?q=https://medium.com/@khairulomar/deconstructing-time-series-using-fourier-transform-e52dd535a44e&sa=D&source=editors&ust=1621930682803000&usg=AOvVaw3PsBX4mdhIgqlyuJiGM8S1)
2.  Medium series, mostly on the math, parts [1](https://www.google.com/url?q=https://medium.com/sho-jp/fourier-transform-101-part-1-b69ea3cb4837&sa=D&source=editors&ust=1621930682804000&usg=AOvVaw04bch8lUyMzQzUSB9npdEY)[2](https://www.google.com/url?q=https://medium.com/sho-jp/fourier-transform-101-part-2-complex-fourier-series-934a885b3921&sa=D&source=editors&ust=1621930682804000&usg=AOvVaw2aB73JiviA-0Lv-XrvBNuB)[3](https://www.google.com/url?q=https://medium.com/sho-jp/fourier-transform-101-part-3-fourier-transform-6def0bd2ca9b&sa=D&source=editors&ust=1621930682805000&usg=AOvVaw30XGH5Ftb7diSsDPfFj9SJ)[4](https://www.google.com/url?q=https://medium.com/sho-jp/fourier-transform-101-part-4-discrete-fourier-transform-8fc3fbb763f3&sa=D&source=editors&ust=1621930682805000&usg=AOvVaw3mz9JR1wFQeCSdWiFUCBRY)[5](https://www.google.com/url?q=https://medium.com/sho-jp/fourier-transform-101-part-5-fast-fourier-transform-fft-38c22e05ead3&sa=D&source=editors&ust=1621930682806000&usg=AOvVaw2rqa6RCT7TfJKr0aicakrp)

Digital Signal Processing (DSP)
===============================

1.  (Out of place) - [using self-attention for sound signal processing](https://www.google.com/url?q=https://medium.com/ai%25C2%25B3-theory-practice-business/toward-interpretable-music-tagging-with-self-attention-67a8136048d0&sa=D&source=editors&ust=1621930682807000&usg=AOvVaw1Q68np_kCjkjJ6QXmSMTpW)
2.  [Scipy signal processing](https://www.google.com/url?q=https://docs.scipy.org/doc/scipy/reference/signal.html&sa=D&source=editors&ust=1621930682808000&usg=AOvVaw0dQmW1iA890ASZgGEDAyoD)
3.  [Script find peaks](https://www.google.com/url?q=https://docs.scipy.org/doc/scipy/reference/generated/scipy.signal.find_peaks.html&sa=D&source=editors&ust=1621930682808000&usg=AOvVaw3Xik3Z8FCCOMjOHDrMjkfE)
4.  Beat detection

1.  [Real time bpm beat det](https://www.google.com/url?q=https://github.com/shunfu/python-beat-detector&sa=D&source=editors&ust=1621930682809000&usg=AOvVaw3m8ePBQ9SODucyOdRCATX4)
2.  [Librosa](https://www.google.com/url?q=https://librosa.org/doc/latest/core.html%23time-domain-processing&sa=D&source=editors&ust=1621930682809000&usg=AOvVaw1ACJut6ux6fj-rldTuWSEb):[Beat detection (and temp)](https://www.google.com/url?q=https://librosa.org/doc/latest/beat.html%23beat&sa=D&source=editors&ust=1621930682810000&usg=AOvVaw0MYG_NrwwXu5VJXIDEEavz)

5.  [Mastery on Human activity recognition, smartphones](https://www.google.com/url?q=https://machinelearningmastery.com/cnn-models-for-human-activity-recognition-time-series-classification/&sa=D&source=editors&ust=1621930682810000&usg=AOvVaw1qgNIv1BMonH6DNIQz-S4P)

* * *

Graph Theory
============

1.  [General purpose and community detection GIT](https://www.google.com/url?q=https://github.com/benedekrozemberczki/karateclub&sa=D&source=editors&ust=1621930682811000&usg=AOvVaw3Bd9pwlXrSl52YN_bF-OxJ) karate club bene
2.  Connectivity
3.  Min-cut: [1](https://www.google.com/url?q=https://github.com/gsw73/min-cut/blob/master/karger_min_cut.py&sa=D&source=editors&ust=1621930682812000&usg=AOvVaw2-3zHlP4Hfj_YP0hy2yYvR), [2](https://www.google.com/url?q=https://github.com/ChuntaoLu/Algorithms-Design-and-Analysis/blob/master/week3%2520Karger%2520min%2520cut/min_cut.py&sa=D&source=editors&ust=1621930682813000&usg=AOvVaw3s0OA2zVWiXzf1N735-FHC), [3](https://www.google.com/url?q=https://github.com/WithaK16/kargerMinCut/blob/master/kargerMinCut.py&sa=D&source=editors&ust=1621930682813000&usg=AOvVaw1k4UFl_3oUsNcy4ojzxy2Q), 4, 5, 6
4.  [Louvain community](https://www.google.com/url?q=https://github.com/taynaud/python-louvain/&sa=D&source=editors&ust=1621930682814000&usg=AOvVaw2ulcDUDJr97DT013MOhXZ1)
5.  Girwan newman [gist](https://www.google.com/url?q=https://gist.github.com/chelsea1992/6c725a24d358763097bebe8223c2014a&sa=D&source=editors&ust=1621930682814000&usg=AOvVaw0hbOr07fzl9azX8GK31D-v), [this worked](https://www.google.com/url?q=https://github.com/ZwEin27/Community-Detection&sa=D&source=editors&ust=1621930682814000&usg=AOvVaw0cmxPp1kKpA5ozVV39TOY-), t[his is potentially good too](https://www.google.com/url?q=https://github.com/riteshkasat/Community-Detection-Algorithm&sa=D&source=editors&ust=1621930682815000&usg=AOvVaw0a9PlQMUP0EbBIIONpxx1K), [another](https://www.google.com/url?q=https://github.com/ServiceCutter/girvan-newman&sa=D&source=editors&ust=1621930682815000&usg=AOvVaw1v54YF30cGpNg7ZBs9G1Vf), [another](https://www.google.com/url?q=https://github.com/ZwEin27/Community-Detection&sa=D&source=editors&ust=1621930682815000&usg=AOvVaw14KP1XrBCKyA39jrqMjg5N), [another](https://www.google.com/url?q=https://github.com/kjahan/community&sa=D&source=editors&ust=1621930682816000&usg=AOvVaw3PubSMIsn0fBjoPPaCeSmg)
6.  [Node2vec](https://www.google.com/url?q=https://github.com/eliorc/Medium/blob/master/Nod2Vec-FIFA17-Example.ipynb&sa=D&source=editors&ust=1621930682816000&usg=AOvVaw1_Fm7h2GGXWm5_p6Gk15DG), [paper](https://www.google.com/url?q=https://arxiv.org/pdf/1607.00653.pdf&sa=D&source=editors&ust=1621930682816000&usg=AOvVaw1A3y72RpXyQr-DXILrDw6I),  [medium1](https://www.google.com/url?q=https://towardsdatascience.com/think-your-data-different-ddc435f70850&sa=D&source=editors&ust=1621930682817000&usg=AOvVaw2Me1uZf2ZWz5FnMlGqNPua), [medium 2](https://www.google.com/url?q=https://towardsdatascience.com/node2vec-embeddings-for-graph-data-32a866340fef&sa=D&source=editors&ust=1621930682817000&usg=AOvVaw3viEjiIhbnQ0e8pvMM-eOm) \- tutorial -[code](https://www.google.com/url?q=https://github.com/eliorc/node2vec&sa=D&source=editors&ust=1621930682817000&usg=AOvVaw0LC9F0UKclmFDEO759YduX), [git code](https://www.google.com/url?q=https://github.com/eliorc/Medium/blob/master/Nod2Vec-FIFA17-Example.ipynb&sa=D&source=editors&ust=1621930682817000&usg=AOvVaw1_EBXdL-pfwBox7WDSxUeP), [original py2 code](https://www.google.com/url?q=https://github.com/aditya-grover/node2vec&sa=D&source=editors&ust=1621930682818000&usg=AOvVaw25TxzU3XjFlqQuXA4fFHK1),[taboola code for their medium paper](https://www.google.com/url?q=https://github.com/taboola/node2vec-example/blob/master/node2vec.ipynb&sa=D&source=editors&ust=1621930682818000&usg=AOvVaw0SkHCmc1MWZttycHPdLXtx)
7.  [Evaluation metrics for community detection](https://www.google.com/url?q=https://stackoverflow.com/questions/28952104/evaluation-metrics-for-community-detection-algorithms&sa=D&source=editors&ust=1621930682818000&usg=AOvVaw32POoDvAEMZ7YNgoFLTn_H)
8.  [Review for community detection algorithms](https://www.google.com/url?q=https://arxiv.org/pdf/0906.0612.pdf&sa=D&source=editors&ust=1621930682819000&usg=AOvVaw289VuJc5CrLF26esG35IF7)\- [paper](https://www.google.com/url?q=https://arxiv.org/abs/0906.0612&sa=D&source=editors&ust=1621930682819000&usg=AOvVaw2kXXf4mjMWKViu74yUSEKi)
9.  [Term: community structure](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Community_structure%23Algorithms_for_finding_communities&sa=D&source=editors&ust=1621930682819000&usg=AOvVaw1-80bmeAOW7S4L4X497Jft)
10. [Term: modularity of networks](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Modularity_%2528networks%2529&sa=D&source=editors&ust=1621930682820000&usg=AOvVaw2YFpA_LtdbFQAuevQGlbuf)
11. [Unread paper](https://www.google.com/url?q=http://science.sciencemag.org/content/328/5980/876&sa=D&source=editors&ust=1621930682820000&usg=AOvVaw1Aj6cumnYIz5XPAnCZaoxp)
12. [Unread comparison of community detection algos](https://www.google.com/url?q=https://arxiv.org/abs/1406.2205&sa=D&source=editors&ust=1621930682821000&usg=AOvVaw2e85tRvDIc7O67NbljArVH)
13. [Clustering adjacency matrices](https://www.google.com/url?q=https://stats.stackexchange.com/questions/125295/the-best-way-for-clustering-an-adjacency-matrix&sa=D&source=editors&ust=1621930682821000&usg=AOvVaw3B6ilTUyuDxBMvWgyzSb7U)
14. [Spectral-clustering](https://www.google.com/url?q=https://calculatedcontent.com/2012/10/09/spectral-clustering/&sa=D&source=editors&ust=1621930682822000&usg=AOvVaw2PkJehD539NXQMN7jRGfrO) (is this suppose to be here?)
15. [Finding natural groups in undirected graphs](https://www.google.com/url?q=https://stats.stackexchange.com/questions/142297/finding-natural-groups-clusters-in-an-undirected-graph-over-several-undirect&sa=D&source=editors&ust=1621930682822000&usg=AOvVaw3ROGujS9bUVh4bPuiGDntp)
16. [Awesome community detection on github](https://www.google.com/url?q=https://github.com/benedekrozemberczki/awesome-community-detection?fbclid%3DIwAR3Ab2oh_skVqwUP6xOh-3G_t715eyPESzGhHQIVRogRFHK0SZ6dzoublqE&sa=D&source=editors&ust=1621930682823000&usg=AOvVaw3mEQu3MozGZn2O9wFJOYLF)
17. [Various algorithms](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/closeness-centrality/&sa=D&source=editors&ust=1621930682823000&usg=AOvVaw0AhpgqB_Iu5Bfwpk-19hhq)

[5\. Centrality algorithms](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/centrality/&sa=D&source=editors&ust=1621930682823000&usg=AOvVaw2uxwIoet5wYvq3MAPlRBT3)

1.  [5.1. The PageRank algorithm](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/page-rank/&sa=D&source=editors&ust=1621930682824000&usg=AOvVaw1-Gbs6_0BfIcbuzcZORrvz)
2.  [5.2. The Betweenness Centrality algorithm](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/betweenness-centrality/&sa=D&source=editors&ust=1621930682824000&usg=AOvVaw218o_zaTz_1qC5LAD6IXC1)
3.  [5.3. The Closeness Centrality algorithm](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/closeness-centrality/&sa=D&source=editors&ust=1621930682825000&usg=AOvVaw0fhSOlXdfws2lrHs2UoRJ5)
4.  [5.4. The Degree Centrality algorithm](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/degree-centrality/&sa=D&source=editors&ust=1621930682825000&usg=AOvVaw02g0boPf0ZAU7gLIEateod)

[6\. Community detection algorithms](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/community/&sa=D&source=editors&ust=1621930682825000&usg=AOvVaw2L-FAR07n54V2Exdt2G_Yx)

5.  [6.1. The Louvain algorithm](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/louvain/&sa=D&source=editors&ust=1621930682826000&usg=AOvVaw2dTGj9jZi5tOdXFptiwrPc)
6.  [6.2. The Label Propagation algorithm](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/label-propagation/&sa=D&source=editors&ust=1621930682826000&usg=AOvVaw3FJIfNXGmuy8Akhz18YukD)
7.  [6.3. The Connected Components algorithm](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/algorithms/connected-components/&sa=D&source=editors&ust=1621930682827000&usg=AOvVaw1iJAmdfThwxCIl-87msaa2)

[7\. Experimental algorithms](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/experimental-algorithms/&sa=D&source=editors&ust=1621930682827000&usg=AOvVaw2xuSQnnFjgt-b8rteeZVuq)

8.  [7.1. Procedures](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/experimental-procedures/&sa=D&source=editors&ust=1621930682827000&usg=AOvVaw3TYDDb4bxS75DX62Ln6AUX)
9.  [7.2. Centrality algorithms](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/experimental-algorithms/centrality/&sa=D&source=editors&ust=1621930682828000&usg=AOvVaw16j62cdZxW6NWk6fBcpsew)
10. [7.3. Community detection algorithms](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/experimental-algorithms/community/&sa=D&source=editors&ust=1621930682828000&usg=AOvVaw2SXhxlQhCUGjh5D0ZukDv_)
11. [7.4. Path finding algorithms](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/experimental-algorithms/pathfinding/&sa=D&source=editors&ust=1621930682828000&usg=AOvVaw1U6AHtuqtYL1yEjOPEI1Q9)
12. [7.5. Similarity algorithms](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/experimental-algorithms/similarity/&sa=D&source=editors&ust=1621930682829000&usg=AOvVaw0sKyF_63UKgWVGx1DSHGo8)
13. [7.6. Link Prediction algorithms](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/experimental-algorithms/linkprediction/&sa=D&source=editors&ust=1621930682829000&usg=AOvVaw3rZx3eBZqSlWs3VPIPucbH)
14. [7.7. Preprocessing functions and](https://www.google.com/url?q=https://neo4j.com/docs/graph-algorithms/current/experimental-algorithms/preprocessing/&sa=D&source=editors&ust=1621930682830000&usg=AOvVaw3152GFF2_8yrFYVdc6FvIm)

* * *

SOCIAL NETWORK ANALYSIS
=======================

1.  [Wiki](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Social_network&sa=D&source=editors&ust=1621930682830000&usg=AOvVaw0SfSHyHCEg6em-9C6kD6EG)
2.  [Paper: algorithmic approach to social networks](https://www.google.com/url?q=http://www.cs.carleton.edu/faculty/dlibenno/papers/thesis/thesis.pdf&sa=D&source=editors&ust=1621930682831000&usg=AOvVaw39CKkv0EQMuJbvohv0zIkm)
3.  [Steve borgatti](https://www.google.com/url?q=https://sites.google.com/site/steveborgatti/home&sa=D&source=editors&ust=1621930682831000&usg=AOvVaw1r2iVyQn-Hr2hIyXd3tAPe)
4.  [Intro to SNA](https://www.google.com/url?q=http://www.orgnet.com/sna.html&sa=D&source=editors&ust=1621930682832000&usg=AOvVaw34vF8dJn1Mif8CL2K3WwNV)

1.  Centrality
2.  Betweenness centrality
3.  Network centralization
4.  Network reach
5.  Network integration
6.  Boundary spanners
7.  Peripheral players

5.  [Social Network Analysis: Can Quantity Compensate for Quality?](https://www.google.com/url?q=https://33bits.wordpress.com/2009/02/15/social-network-analysis-can-quantity-substitute-for-quality/&sa=D&source=editors&ust=1621930682833000&usg=AOvVaw0K9eIpBX_ZUk55t_C5EzjQ)

[Nicholas Christakis](https://www.google.com/url?q=http://www.wjh.harvard.edu/soc/faculty/christakis/&sa=D&source=editors&ust=1621930682833000&usg=AOvVaw34FmF_oodijgjbhRuiEpH1)of Harvard and [James Fowler](https://www.google.com/url?q=http://jhfowler.ucsd.edu/&sa=D&source=editors&ust=1621930682834000&usg=AOvVaw0fgXZCwwuXwb4KWX7A5fb4)of UC San Diego have produced a series of ground-breaking papers analyzing the spread of various traits in social networks: [obesity](https://www.google.com/url?q=http://content.nejm.org/cgi/content/full/357/4/370&sa=D&source=editors&ust=1621930682834000&usg=AOvVaw1hXAioZxKPp7An-xz6vNKn), [smoking](https://www.google.com/url?q=http://content.nejm.org/cgi/content/full/358/21/2249&sa=D&source=editors&ust=1621930682834000&usg=AOvVaw3g4yOPewoAuD_0lEPnCrHx), [happiness](https://www.google.com/url?q=http://www.bmj.com/cgi/content/full/337/dec04_2/a2338&sa=D&source=editors&ust=1621930682834000&usg=AOvVaw3vcpZZxFERz_5LKX72KU_P), and most recently, in collaboration with John Cacioppo, [loneliness](https://www.google.com/url?q=http://papers.ssrn.com/sol3/papers.cfm?abstract_id%3D1319108&sa=D&source=editors&ust=1621930682835000&usg=AOvVaw1xFcR0m3ADz5rKAdoLpePV). The Christakis-Fowler collaboration has now become [well-known](https://www.google.com/url?q=http://jhfowler.ucsd.edu/science_friendship_as_a_health_factor.pdf&sa=D&source=editors&ust=1621930682835000&usg=AOvVaw1asvmYhpmQ1cdtbBBk_iKY), but from a technical perspective, what was special about their work?

It turns out that they found a way to distinguish between the three reasons why people who are related in a social network are similar to each other.

1.  Homophily is the tendency of people to seek others who are alike. For example, most of us restrict our dates to smokers or non-smokers, mirroring our own behavior.
2.  Confounding is the phenomenon of related individuals developing a trait because of a (shared) environmental circumstance. For example, people living right next to a McDonald’s might all gradually become obese.
3.  Induction is the process of one individual passing a trait or behavior on to their friends, whether by active encouragement or by setting an example

6.  [Networkx](https://www.google.com/url?q=https://networkx.org/documentation//networkx-1.10/reference/algorithms.html&sa=D&source=editors&ust=1621930682836000&usg=AOvVaw2bCLYQdfLFOwHJaZpNoFPP) \- Centrality is just a fraction of the algorithms contained in networkx.

![](images/image162.png)

7.  [Social Network analysis from theory to applications](https://www.google.com/url?q=https://towardsdatascience.com/social-network-analysis-from-theory-to-applications-with-python-d12e9a34c2c7&sa=D&source=editors&ust=1621930682837000&usg=AOvVaw3oF4nDSfoATROvBpO2uNk0)\- [dima goldenberg](https://www.google.com/url?q=https://www.linkedin.com/in/dimgold/&sa=D&source=editors&ust=1621930682838000&usg=AOvVaw0Xd8Q3iKeB76Sgnsu-BJqb)
    
    * * *
    

(DEEP) NEURAL NETS
==================

* [Deep learning notes from Andrew NG’s course.](https://www.google.com/url?q=https://www.slideshare.net/TessFerrandez/notes-from-coursera-deep-learning-courses-by-andrew-ng&sa=D&source=editors&ust=1621930682839000&usg=AOvVaw0M8WPuqjrEXp8uT1iW6tNM)

Jay Alammar on NN[Part 1](https://www.google.com/url?q=http://jalammar.github.io/visual-interactive-guide-basics-neural-networks/&sa=D&source=editors&ust=1621930682839000&usg=AOvVaw0QYxJrlzDaW_JmtZt6zLOl),[Part 2](https://www.google.com/url?q=http://jalammar.github.io/feedforward-neural-networks-visual-interactive/&sa=D&source=editors&ust=1621930682840000&usg=AOvVaw0UDXH2EOrsUlCGo01knAt9)

* [NN in general](https://www.google.com/url?q=http://briandolhansky.com/blog/?tag%3Dneural%2Bnetwork%23show-archive&sa=D&source=editors&ust=1621930682840000&usg=AOvVaw1ElXSBh6F8U8c9l1PfZKCo) \- 5 introductions  tutorials.

* [Segmentation examples](https://www.google.com/url?q=https://meetshah1995.github.io/semantic-segmentation/deep-learning/pytorch/visdom/2017/06/01/semantic-segmentation-over-the-years.html&sa=D&source=editors&ust=1621930682841000&usg=AOvVaw15MtPaCWg3E0pxevV4DPml)

MLP: fully connected, input, hidden layers, output. Gradient on the backprop takes a lot of time to calculate. Has vanishing gradient problem, because of multiplications when it reaches the first layers the loss correction is very small (0.1\*0.1\*01 = 0.001), therefore the early layers train slower than the last ones, and the early ones capture the basics structures so they are the more important ones.

AutoEncoder - unsupervised, drives the input through fully connected layers, sometime reducing their neurons amount, then does the reverse and expands the layer’s size to get to the input (images are multiplied by the transpose matrix, many times over), Comparing the predicted output to the input, correcting the cost using gradient descent and redoing it, until the networks learns the output.

* Convolutional auto encoder
* Denoiser auto encoder - masking areas in order to create an encoder that understands noisy images
* Variational autoencoder - doesnt rely on distance between pixels, rather it maps them to a function (gaussian), eventually the DS should be explained by this mapping, uses 2 new layers added to the network. Gaussian will create blurry images, but similar. Please note that it also works with CNN.

What are [logits](https://www.google.com/url?q=https://stackoverflow.com/questions/41455101/what-is-the-meaning-of-the-word-logits-in-tensorflow&sa=D&source=editors&ust=1621930682843000&usg=AOvVaw2Hg9_ed2lN1pWNjl7-yneZ) in neural net - the vector of raw (non-normalized) predictions that a classification model generates, which is ordinarily then passed to a normalization function. If the model is solving a multi-class classification problem, logits typically become an input to the softmax function. The softmax function then generates a vector of (normalized) probabilities with one value for each possible class.

[WORD2VEC](https://www.google.com/url?q=http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/&sa=D&source=editors&ust=1621930682844000&usg=AOvVaw3NcEP_jrIqM43pYgHlKWcU)\- based on autoencode, we keep only the hidden layer , [Part 2](https://www.google.com/url?q=http://mccormickml.com/2017/01/11/word2vec-tutorial-part-2-negative-sampling/&sa=D&source=editors&ust=1621930682844000&usg=AOvVaw1HOj5zIEVMsOIwu-7Sdpg9)

RBM- restricted (no 2 nodes share a connection) boltzman machine

An Autoencoder of features, tries to encode its own structure.

Works best on pics, video, voice, sensor data. 2 layers, visible and hidden, error and bias calculated via KL Divergence.

* Also known as a shallow network.
* Two layers, input and output, goes back and forth until it learns its output.

DBN - deep belief networks, similar structure to multi layer perceptron. fully connected, input, hidden(s), output layers. Can be thought of as stacks of RBM. training using GPU optimization, accurate and needs smaller labelled data set to complete the training.

Solves the ‘vanishing gradient’ problem, imagine a fully connected network, advancing each 2 layers step by step until each boltzman network (2 layers) learns the output, keeps advancing until finished.. Each layer learns the entire input.

Next step is to fine tune using a labelled test set, improves performance and alters the net. So basically using labeled samples we fine tune and associate features and pattern with a name. Weights and biases are altered slightly and there is also an increase in performance. Unlike CNN which learns features then high level features.

Accurate and reasonable in time, unlike fully connected that has the vanishing gradient problem.

Transfer Learning = like Inception in Tensor flow, use a prebuilt network to solve many problems that “work” similarly to the original network.

* [CS course definition](https://www.google.com/url?q=http://cs231n.github.io/transfer-learning/&sa=D&source=editors&ust=1621930682847000&usg=AOvVaw0sUsmeBLVbry1zlIgW7tdz) \- also very good explanation of the common use cases:

*  Feature extraction from the CNN part (removing the fully connected layer)
* Fine-tuning, everything or partial selection of the hidden layers, mainly good to keep low level neurons that know what edges and color blobs are, but not dog breeds or something not as general.

* [CNN checkpoints](https://www.google.com/url?q=https://github.com/BVLC/caffe/wiki/Model-Zoo%23cascaded-fully-convolutional-networks-for-biomedical-image-segmentation&sa=D&source=editors&ust=1621930682848000&usg=AOvVaw3u4qKZxre_IoN_06r3kjzk)for many problems with transfer learning. Has several relevant references
* Such as this “[How transferable are features in deep neural networks?](https://www.google.com/url?q=http://arxiv.org/abs/1411.1792&sa=D&source=editors&ust=1621930682848000&usg=AOvVaw1fN99P7fPMV2lY0EOzN36h) “
* (the indian guy on facebook) [IMDB transfer learning using cnn vgg and word2vec](https://www.google.com/url?q=https://spandan-madan.github.io/DeepLearningProject/&sa=D&source=editors&ust=1621930682849000&usg=AOvVaw0APE8vktijNMplhbZq_5ci), the word2vec is interesting, the cnn part is very informative. With python code, keras.

CNN, Convolutional Neural Net ([this link explains CNN quite well](https://www.google.com/url?q=https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/&sa=D&source=editors&ust=1621930682850000&usg=AOvVaw3IsJYy50NLp3JPEWLPIjJU), [2nd tutorial](https://www.google.com/url?q=https://hackernoon.com/deep-learning-cnns-in-tensorflow-with-gpus-cba6efe0acc2&sa=D&source=editors&ust=1621930682850000&usg=AOvVaw3oQy_nh_sqSx7yLIB8rAMR) \- both explain about convolution, padding, relu - sparsity, max and avg pooling):

* Common Layers: input->convolution->relu activation->pooling to reduce dimensionality **** ->fully connected layer
* ****repeat several times over as this discover patterns but needs another layer -> fully connected layer
* Then we connect at the end a fully connected layer (fcl) to classify data samples.
* Good for face detection, images etc.
* Requires lots of data, not always possible in a real world situation
* Relu is quite resistant to vanishing gradient & allows for deactivating neurons and for sparsity.

RNN - what is RNN by Andrej Karpathy - [The Unreasonable Effectiveness of Recurrent Neural Networks](https://www.google.com/url?q=http://karpathy.github.io/2015/05/21/rnn-effectiveness/&sa=D&source=editors&ust=1621930682852000&usg=AOvVaw2CQTkRpYoqLv6bUeTqeOeT), basically a lot of information about RNNs and their usage cases

*  basic NN node with a loop, previous output is merged with current input. for the purpose of remembering history, for time series, to predict the next X based on the previous Y.
* 1 to N = frame captioning
* N to 1 = classification
* N to N = predict frames in a movie
* N\\2 with time delay to N\\2 = predict supply and demand
* Vanishing gradient is 100 times worse.
* Gate networks like LSTM solves vanishing gradient.

[SNN](https://www.google.com/url?q=https://medium.com/@eliorcohen/selu-make-fnns-great-again-snn-8d61526802a9&sa=D&source=editors&ust=1621930682853000&usg=AOvVaw22lm9ZnISOGnrV-UggJLJG) \- SELU activation function is inside not outside, results converge better.

Probably useful for feedforward networks

[DEEP REINFORCEMENT LEARNING COURSE](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DQDzM8r3WgBw%26t%3D2958s&sa=D&source=editors&ust=1621930682854000&usg=AOvVaw0-_uQ5bQe5FrNJ1amQtfPb) (for motion planning)or  
[DEEP RL COURSE](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DPtAIh9KSnjo&sa=D&source=editors&ust=1621930682855000&usg=AOvVaw3aSWP9eZEojLiIlYrMYL0Q)  (Q-LEARNING?) - using unlabeled data, reward, and probably a CNN to solve games beyond human level.

A[brief survey of DL for Reinforcement learning](https://www.google.com/url?q=https://arxiv.org/abs/1708.05866&sa=D&source=editors&ust=1621930682855000&usg=AOvVaw0Sxic5znsyO5Wad3krtu3j)

[WIKI](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Recurrent_neural_network%23Long_short-term_memory&sa=D&source=editors&ust=1621930682856000&usg=AOvVaw23OKWXE17z4FfVj71uFFQg) has many types of RNN networks (unread)

Unread and potentially good tutorials:

1.  [deep learning python](https://www.google.com/url?q=https://www.datacamp.com/community/tutorials/deep-learning-python&sa=D&source=editors&ust=1621930682856000&usg=AOvVaw1yBUs_05nKAKG5_LaIzN4R)

EXAMPLES of Using NN on images:

[Deep image prior / denoiser/ high res/ remove artifacts/ etc..](https://www.google.com/url?q=https://dmitryulyanov.github.io/deep_image_prior&sa=D&source=editors&ust=1621930682857000&usg=AOvVaw1mUndL2WJv2i7Z6TLiRbJq)

* * *

GRADIENT DESCENT
----------------

([What are](https://www.google.com/url?q=http://machinelearningmastery.com/gentle-introduction-mini-batch-gradient-descent-configure-batch-size/&sa=D&source=editors&ust=1621930682858000&usg=AOvVaw25YKUZ_8pm39pXQ-gVN0zr)?) batch, stochastic, and mini-batch gradient descent are and the benefits and limitations of each method.

[What is gradient descent, how to use it, local minima okay to use, compared to global. Saddle points, learning rate strategies and research points](https://www.google.com/url?q=https://blog.paperspace.com/intro-to-optimization-in-deep-learning-gradient-descent/&sa=D&source=editors&ust=1621930682859000&usg=AOvVaw3QMAVwbXXV2TEoZEcw9hS9)

1.  Gradient descent is an optimization algorithm often used for finding the weights or coefficients of machine learning algorithms, such as artificial neural networks and logistic regression.
2.  the model makes predictions on training data, then use the error on the predictions to update the model to reduce the error.
3.  The goal of the algorithm is to find model parameters (e.g. coefficients or weights) that minimize the error of the model on the training dataset. It does this by making changes to the model that move it along a gradient or slope of errors down toward a minimum error value. This gives the algorithm its name of “gradient descent.”

### Stochastic

* calculate error and updates the model after every training sample

### Batch

* calculates the error for each example in the training dataset, but only updates the model after all training examples have been evaluated.

### Mini batch (most common)

* splits the training dataset into small batches, used to calculate model error and update model coefficients.
* Implementations may choose to sum the gradient over the mini-batch or take the average of the gradient (reduces variance of gradient) (unclear?)

* * *

\+ Tips on how to choose and train using mini batch in the link above

[Dont decay the learning rate, increase batchsize - paper](https://www.google.com/url?q=https://arxiv.org/abs/1711.00489&sa=D&source=editors&ust=1621930682861000&usg=AOvVaw0u-ZL6hyM5316l2ZQDW28t) (optimization of a network)

![](images/image211.png)

![](images/image220.png)

* * *

* [Big batches are not the cause for the ‘generalization gap’ between mini and big batches, it is not advisable to use large batches because of the low update rate, however if you change that, authors claim its okay](https://www.google.com/url?q=https://arxiv.org/abs/1705.08741&sa=D&source=editors&ust=1621930682862000&usg=AOvVaw2NxrDwdiz97Stbs8QcCixp).

* [So what is a batch size in NN (another source)](https://www.google.com/url?q=https://stats.stackexchange.com/questions/153531/what-is-batch-size-in-neural-network&sa=D&source=editors&ust=1621930682863000&usg=AOvVaw1onzbC91oBj76pGtZfL1DM) \- and how to find the “right” number. In general terms a good mini bach between 1 and all samples is a good idea. Figure it out empirically.

* one epoch= one forward pass and one backward pass of all the training examples
* batch size = the number of training examples in one forward/backward pass. The higher the batch size, the more memory space you'll need.
* number of iterations = number of passes, each pass using \[batch size\] number of examples. To be clear, one pass = one forward pass + one backward pass (we do not count the forward pass and backward pass as two different passes).

Example: if you have 1000 training examples, and your batch size is 500, then it will take 2 iterations to complete 1 epoch.

* [How to balance and what is the tradeoff between batch size and the number of iterations.](https://www.google.com/url?q=https://stats.stackexchange.com/questions/164876/tradeoff-batch-size-vs-number-of-iterations-to-train-a-neural-network&sa=D&source=editors&ust=1621930682865000&usg=AOvVaw00YkgyXqRGcJfFm0HWBobX)

![](images/image30.png)

[GD with Momentum](https://www.google.com/url?q=https://towardsdatascience.com/stochastic-gradient-descent-with-momentum-a84097641a5d&sa=D&source=editors&ust=1621930682866000&usg=AOvVaw3_EQFLpTEt06p3mxmg_Ar7) \- explain

* * *

* * *

Batch size
----------

([a good read)](https://www.google.com/url?q=https://machinelearningmastery.com/use-different-batch-sizes-training-predicting-python-keras/&sa=D&source=editors&ust=1621930682867000&usg=AOvVaw3Tupnmd3SDp6HHs7MZKDo5) about batch sizes in keras, specifically LSTM, read this first!

A sequence prediction problem makes a good case for a varied batch size as you may want to have a batch size equal to the training dataset size (batch learning) during training and a batch size of 1 when making predictions for one-step outputs.

power of 2: have some advantages with regards to vectorized operations in certain packages, so if it's close it might be faster to keep your batch_size in a power of 2.

([pushing batches of samples to memory in order to train)](https://www.google.com/url?q=https://stats.stackexchange.com/questions/153531/what-is-batch-size-in-neural-network&sa=D&source=editors&ust=1621930682868000&usg=AOvVaw3qJ52V4uqrnTo0jLvhSjHy) -

Batch size defines number of samples that going to be propagated through the network.

For instance, let's say you have 1050 training samples and you want to set up batch_size equal to 100. Algorithm takes first 100 samples (from 1st to 100th) from the training dataset and trains network. Next it takes second 100 samples (from 101st to 200th) and train network again. We can keep doing this procedure until we will propagate through the networks all samples. The problem usually happens with the last set of samples. In our example we've used 1050 which is not divisible by 100 without remainder. The simplest solution is just to get final 50 samples and train the network.

Advantages:

* It requires less memory. Since you train network using less number of samples the overall training procedure requires less memory. It's especially important in case if you are not able to fit dataset in memory.
* Typically networks trains faster with mini-batches. That's because we update weights after each propagation. In our example we've propagated 11 batches (10 of them had 100 samples and 1 had 50 samples) and after each of them we've updated network's parameters. If we used all samples during propagation we would make only 1 update for the network's parameter.

Disadvantages:

* The smaller the batch the less accurate estimate of the gradient.In the figure below you can see that mini-batch (green color) gradient's direction fluctuates compare to the full batch (blue color).

![enter image description here](images/image274.png)

[Small batch size has an effect on validation accuracy.](https://www.google.com/url?q=http://forums.fast.ai/t/batch-size-effect-on-validation-accuracy/413&sa=D&source=editors&ust=1621930682872000&usg=AOvVaw3dfUPa9jIKQDTYDI6TMoA6)

![](images/image175.png)IMPORTANT: batch size in ‘.prediction’ is needed for some models, [only for technical reasons as seen here](https://www.google.com/url?q=https://github.com/fchollet/keras/issues/3027&sa=D&source=editors&ust=1621930682873000&usg=AOvVaw0gyAJFkHpInsVU7FynJg3q), in keras.

1.  ([unread](https://www.google.com/url?q=https://www.quora.com/Intuitively-how-does-mini-batch-size-affect-the-performance-of-stochastic-gradient-descent&sa=D&source=editors&ust=1621930682875000&usg=AOvVaw2v8IyHHlze8eZgJKMVeniV)) about mini batches and performance.
2.  ([unread](https://www.google.com/url?q=https://stats.stackexchange.com/questions/164876/tradeoff-batch-size-vs-number-of-iterations-to-train-a-neural-network&sa=D&source=editors&ust=1621930682876000&usg=AOvVaw2ETVmWn5brjgLgTNsSrBOf)) tradeoff between bath size and number of iterations

[Another observation, probably empirical](https://www.google.com/url?q=https://stackoverflow.com/questions/35050753/how-big-should-batch-size-and-number-of-epochs-be-when-fitting-a-model-in-keras&sa=D&source=editors&ust=1621930682877000&usg=AOvVaw1NQAWbzTzuuJlB6lteHjWx) \-  to answer your questions on Batch Size and Epochs:

In general: Larger batch sizes result in faster progress in training, but don't always converge as fast. Smaller batch sizes train slower, but can converge faster. It's definitely problem dependent.

In general, the models improve with more epochs of training, to a point. They'll start to plateau in accuracy as they converge. Try something like 50 and plot number of epochs (x axis) vs. accuracy (y axis). You'll see where it levels out.

* * *

BIAS
----

[The role of bias in NN](https://www.google.com/url?q=https://stackoverflow.com/questions/2480650/role-of-bias-in-neural-networks&sa=D&source=editors&ust=1621930682880000&usg=AOvVaw0Nmd9cKzsbwvraoXZ_k2FX) \- similarly to the ‘b’ in linear regression.

![](images/image201.png)

![](images/image3.png)

BATCH NORMALIZATION
-------------------

1.  The [best explanation](https://www.google.com/url?q=https://blog.paperspace.com/busting-the-myths-about-batch-normalization/&sa=D&source=editors&ust=1621930682882000&usg=AOvVaw0h25YjGXlXeAJtlQrChvFe) to what is BN and why to use it, including busting the myth that it solves internal covariance shift - shifting input distribution, and saying that it should come after activations as it makes more sense (it does),also a nice quote on where a layer ends is really good - it can end at the activation (or not). How to use BN in the test, hint: use a moving window. Bn allows us to use 2 parameters to control the input distribution instead of controlling all the weights.
2.  [Medium on BN](https://www.google.com/url?q=https://towardsdatascience.com/an-alternative-to-batch-normalization-2cee9051e8bc&sa=D&source=editors&ust=1621930682883000&usg=AOvVaw3HlHYoiQiKuvUFYS5wLKpM)
3.  [Medium on BN](https://www.google.com/url?q=https://towardsdatascience.com/batch-normalization-theory-and-how-to-use-it-with-tensorflow-1892ca0173ad&sa=D&source=editors&ust=1621930682884000&usg=AOvVaw12yZol5QhqXsEFAXE7xAf-)
4.  [Ian goodfellow on BN](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DXogn6veSyxA%26feature%3Dyoutu.be%26t%3D325&sa=D&source=editors&ust=1621930682884000&usg=AOvVaw1uSIQLiKkW6tbTaFP8htxm)
5.  [Medium #2 - a better one on BN, and adding to VGG](https://www.google.com/url?q=https://towardsdatascience.com/batch-normalization-in-neural-networks-1ac91516821c&sa=D&source=editors&ust=1621930682885000&usg=AOvVaw25M4k-N_oE7BISwN5qI3ij)
6.  [Reddit on BN, mainly on the paper saying to use it before, but best practice is to use after](https://www.google.com/url?q=https://www.reddit.com/r/MachineLearning/comments/67gonq/d_batch_normalization_before_or_after_relu/&sa=D&source=editors&ust=1621930682885000&usg=AOvVaw3shqfIFKygEgVpM0XXse1I)
7.  [Diff between batch and norm (weak explanation)](https://www.google.com/url?q=https://www.quora.com/What-are-the-practical-differences-between-batch-normalization-and-layer-normalization-in-deep-neural-networks&sa=D&source=editors&ust=1621930682886000&usg=AOvVaw2UiB1jLeI-lb1A7s8hRP7E)
8.  [Weight normalization for keras and TF](https://www.google.com/url?q=http://krasserm.github.io/2018/11/10/weightnorm-implementation-options/&sa=D&source=editors&ust=1621930682887000&usg=AOvVaw0LJV6yMkG2E6_4CLD7wSv_)
9.  [Layer normalization keras](https://www.google.com/url?q=https://pypi.org/project/keras-layer-normalization/&sa=D&source=editors&ust=1621930682887000&usg=AOvVaw3CnQxziYgB8Jaz7tZFA5Gp)
10. [Instance normalization keras](https://www.google.com/url?q=https://github.com/keras-team/keras-contrib/blob/master/keras_contrib/layers/normalization/instancenormalization.py&sa=D&source=editors&ust=1621930682887000&usg=AOvVaw3K3plnCgkAIdUQTnQR8Kbg)
11. [batch/layer/instance in TF with code](https://www.google.com/url?q=https://towardsdatascience.com/implementing-spatial-batch-instance-layer-normalization-in-tensorflow-manual-back-prop-in-tf-77faa8d2c362&sa=D&source=editors&ust=1621930682888000&usg=AOvVaw3JYYDugWRKHJyVZOA6qGmQ)
12. Layer [norm for rnn’s or whatever name it is in this post](https://www.google.com/url?q=https://twimlai.com/new-layer-normalization-technique-speeds-rnn-training/&sa=D&source=editors&ust=1621930682889000&usg=AOvVaw018R9qm83PYs-HVfS1U-ZL)with [code](https://www.google.com/url?q=https://gist.github.com/udibr/7f46e790c9e342d75dcbd9b1deb9d940&sa=D&source=editors&ust=1621930682889000&usg=AOvVaw09w9s9R7DjlUUjvM1b6BBb) for GRU

[What is the diff between batch/layer/recurrent batch and back rnn normalization](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/12956/paper-whats-the-difference-between-layer-normalization-recurrent-batch-normal&sa=D&source=editors&ust=1621930682890000&usg=AOvVaw36qI-ePykSaI6KeLOJWAFI)

* Layer normalization (Ba 2016): Does not use batch statistics. Normalize using the statistics collected from all units within a layer of the current sample. Does not work well with ConvNets.
* Recurrent Batch Normalization (BN) (Cooijmans, 2016; also proposed concurrently by Qianli Liao & Tomaso Poggio, but tested on Recurrent ConvNets, instead of RNN/LSTM): Same as batch normalization. Use different normalization statistics for each time step. You need to store a set of mean and standard deviation for each time step.
* Batch Normalized Recurrent Neural Networks (Laurent, 2015): batch normalization is only applied between the input and hidden state, but not between hidden states. i.e., normalization is not applied over time.
* Streaming Normalization (Liao et al. 2016) : it summarizes existing normalizations and overcomes most issues mentioned above. It works well with ConvNets, recurrent learning and online learning (i.e., small mini-batch or one sample at a time):
* Weight Normalization (Salimans and Kingma 2016): whenever a weight is used, it is divided by its L2 norm first, such that the resulting weight has L2 norm 1. That is, output y=x∗(w/|w|), where x and w denote the input and weight respectively. A scalar scaling factor g is then multiplied to the output y=y∗g. But in my experience g seems not essential for performance (also downstream learnable layers can learn this anyway).
* Cosine Normalization (Luo et al. 2017): weight normalization is very similar to cosine normalization, where the same L2 normalization is applied to both weight and input: y=(x/|x|)∗(w/|w|). Again, manual or automatic differentiation can compute appropriate gradients of x and w.
* Note that both Weight and Cosine Normalization have been extensively used (called normalized dot product) in the 2000s in a class of ConvNets called HMAX (Riesenhuber 1999) to model biological vision. You may find them interesting.

[More about](https://www.google.com/url?q=https://nealjean.com/ml/neural-network-normalization/&sa=D&source=editors&ust=1621930682893000&usg=AOvVaw0tyT6WKbalxtbf7lVFgLHl) [Batch/layer/instance/group norm are different methods for normalizing the inputs to the layers of deep neural networks](https://www.google.com/url?q=https://nealjean.com/ml/neural-network-normalization/&sa=D&source=editors&ust=1621930682893000&usg=AOvVaw0tyT6WKbalxtbf7lVFgLHl)

1.  Layer normalization solves the rnn case that batch couldnt - Is done per feature within the layer and normalized features are replaced
2.  Instance does it for (cnn?) using per channel normalization
3.  Group does it for group of channels
4.  ![](images/image238.png)

[Part1: intuitive explanation to batch normalization](https://www.google.com/url?q=http://mlexplained.com/2018/01/10/an-intuitive-explanation-of-why-batch-normalization-really-works-normalization-in-deep-learning-part-1/&sa=D&source=editors&ust=1621930682895000&usg=AOvVaw0Zh8gPb3tW_Y9T5gm9BngS)

Part2: [batch/layer/weight normalization](https://www.google.com/url?q=http://mlexplained.com/2018/01/13/weight-normalization-and-layer-normalization-explained-normalization-in-deep-learning-part-2/&sa=D&source=editors&ust=1621930682896000&usg=AOvVaw04iSItajCNDP4nls2Vp7op) \- This is a good resource for advantages for every layer

* Layer, per feature in a batch,
* weight - divided by the norm

![](images/image233.png)

* * *

HYPER PARAM GRID SEARCHES
-------------------------

1.  [A disciplined approach to neural network hyper-parameters: Part 1 -- learning rate, batch size, momentum, and weight decay](https://www.google.com/url?q=https://arxiv.org/abs/1803.09820&sa=D&source=editors&ust=1621930682897000&usg=AOvVaw3hwelazDAFwucQ27DHDN22)

LOSS
----

[Very Basic advice](https://www.google.com/url?q=https://stats.stackexchange.com/questions/232754/reference-to-learn-how-to-interpret-learning-curves-of-deep-convolutional-neural&sa=D&source=editors&ust=1621930682898000&usg=AOvVaw3WzrQsI4XKM1w1dnRtR4RO): You should probably switch train/validation repartition to something like 80% training and 20% validation. In most cases it will improve the classifier performance overall (more training data = better performance)

+If Training error and test error are too close (your system is unable to overfit on your training data), this means that your model is too simple. Solution: more layers or more neurons per layer.

* * *

#### Early stopping

If you have never heard about "early-stopping" you should look it up, it's an important concept in the neural network domain : [https://en.wikipedia.org/wiki/Early_stopping](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Early_stopping&sa=D&source=editors&ust=1621930682900000&usg=AOvVaw3CRe_c4mMPE3ROznl4lvSi). To summarize, the idea behind early-stopping is to stop the training once the validation loss starts plateauing. Indeed, when this happens it almost always mean you are starting to overfitt your classifier. The training loss value in itself is not something you should trust, beacause it will continue to increase event when you are overfitting your classifier.

With [cross entropy](https://www.google.com/url?q=https://www.quora.com/Loss-cross-entropy-is-decreasing-but-accuracy-remains-the-same-while-training-convolutional-neural-networks-How-can-it-happen&sa=D&source=editors&ust=1621930682901000&usg=AOvVaw3FzNQNxEeb0JfXr6rjApWC) there can be an issue where the accuracy is the same for two cases, one where the loss is decreasing and the other when the loss is not changing much.

![](images/image189.png)

[How to read LOSS graphs (and accuracy on top)](https://www.google.com/url?q=https://github.com/fchollet/keras/issues/3755&sa=D&source=editors&ust=1621930682901000&usg=AOvVaw19fRDa56-AxIk4i2TOqjOt)

![](images/image114.png)![](images/image90.png)

This indicates that the model is overfitting. It continues to get better and better at fitting the data that it sees (training data) while getting worse and worse at fitting the data that it does not see (validation data).

[This is a very good example of a train/test loss and an accuracy behavior.](https://www.google.com/url?q=https://machinelearningmastery.com/display-deep-learning-model-training-history-in-keras/&sa=D&source=editors&ust=1621930682902000&usg=AOvVaw1Xa_FCsr-itweQG-8PG6mo)

![](images/image204.png)![](images/image71.png)

[Cross entropy formula with soft labels (probability) rather than classes.](https://www.google.com/url?q=https://stats.stackexchange.com/questions/206925/is-it-okay-to-use-cross-entropy-loss-function-with-soft-labels&sa=D&source=editors&ust=1621930682903000&usg=AOvVaw1-AxmhTdlz6P5ynit3rToE)

[Mastery on cross entropy, brier, roc auc, how to ‘game’ them and calibrate them](https://www.google.com/url?q=https://machinelearningmastery.com/how-to-score-probability-predictions-in-python/&sa=D&source=editors&ust=1621930682903000&usg=AOvVaw3BsCjFgKi95PQCGvhuBYEB)

[Game changer paper - a general adaptive loss search in nn](https://www.google.com/url?q=https://www.reddit.com/r/computervision/comments/bsd82j/a_general_and_adaptive_robust_loss_function/?utm_medium%3Dandroid_app%26utm_source%3Dshare&sa=D&source=editors&ust=1621930682904000&usg=AOvVaw0tEiqL0_foOGk8sqvIUUqC)

* * *

LEARNING RATE REDUCTION
-----------------------

[Intro to Learning Rate methods](https://www.google.com/url?q=https://medium.com/@chengweizhang2012/quick-notes-on-how-to-choose-optimizer-in-keras-9d3d12d09039&sa=D&source=editors&ust=1621930682906000&usg=AOvVaw2TLBchyCkgWT-BD3cehhjk) \- what they are doing and what they are fixing in other algos.

[Callbacks](https://www.google.com/url?q=https://keras.io/callbacks/&sa=D&source=editors&ust=1621930682906000&usg=AOvVaw3RmGpzUfaKqCo4CEZNfcxr), especially ReduceLROnPlateau - this callback monitors a quantity and if no improvement is seen for a 'patience' number of epochs, the learning rate is reduced.

[Cs123](https://www.google.com/url?q=http://cs231n.github.io/neural-networks-3/&sa=D&source=editors&ust=1621930682907000&usg=AOvVaw3aZL8cWiuTK9UFjgT2vrxE) (very good): explains about many things related to CNN, but also about LR and adaptive methods.

[An excellent comparison of several learning rate schedule methods and adaptive methods:](https://www.google.com/url?q=https://medium.com/towards-data-science/learning-rate-schedules-and-adaptive-learning-rate-methods-for-deep-learning-2c8f433990d1&sa=D&source=editors&ust=1621930682907000&usg=AOvVaw2oxtfJYD9t5j6Ymp7yiw-J)  ([same here but not as good](https://www.google.com/url?q=https://machinelearningmastery.com/using-learning-rate-schedules-deep-learning-models-python-keras/&sa=D&source=editors&ust=1621930682908000&usg=AOvVaw2rzMrv5UPEjgYenqmiIlDJ))

![](images/image64.png)

Adaptive gradient descent algorithms such as [Adagrad](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Stochastic_gradient_descent%23AdaGrad&sa=D&source=editors&ust=1621930682909000&usg=AOvVaw1XEa6FswvEpM4cFr3JXvl8), Adadelta, [RMSprop](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Stochastic_gradient_descent%23RMSProp&sa=D&source=editors&ust=1621930682909000&usg=AOvVaw1zWTlIgKhzdgHm3-QjyCb6), [Adam](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Stochastic_gradient_descent%23Adam&sa=D&source=editors&ust=1621930682909000&usg=AOvVaw0uNoYs_4E_Mhs2Olit2JUI), provide an alternative to classical SGD.

These per-parameter learning rate methods provide heuristic approach without requiring expensive work intuning hyperparameters for the learning rate schedule manually.

1.  Adagrad performs larger updates for more sparse parameters and smaller updates for less sparse parameter. It has good performance with sparse data and training large-scale neural network. However, its monotonic learning rate usually proves too aggressive and stops learning too early when training deep neural networks.
2.  Adadelta is an extension of Adagrad that seeks to reduce its aggressive, monotonically decreasing learning rate.
3.  RMSprop adjusts the Adagrad method in a very simple way in an attempt to reduce its aggressive, monotonically decreasing learning rate.
4.  [Adam](https://www.google.com/url?q=https://machinelearningmastery.com/adam-optimization-algorithm-for-deep-learning/&sa=D&source=editors&ust=1621930682911000&usg=AOvVaw2I9J44L4dFMt5uIvo3irVr) is an update to the RMSProp optimizer which is like RMSprop with momentum.

![](images/image273.png)

adaptive learning rate methods demonstrate better performance than learning rate schedules, and they require much less effort in hyperparamater settings

![](images/image166.png)

[Recommended paper](https://www.google.com/url?q=https://arxiv.org/pdf/1206.5533v2.pdf&sa=D&source=editors&ust=1621930682912000&usg=AOvVaw3dT5LM4l36fcHBBTSMxLGf): practical recommendation for gradient based DNN

Another great comparison - [pdf paper](https://www.google.com/url?q=https://arxiv.org/abs/1609.04747&sa=D&source=editors&ust=1621930682913000&usg=AOvVaw0OOdnalWP_JJyzQZQFelO5)and [webpage link](https://www.google.com/url?q=http://ruder.io/optimizing-gradient-descent/&sa=D&source=editors&ust=1621930682913000&usg=AOvVaw3BdVsu0jgmNrqPdwvg6Bm7) -

* if your input data is sparse, then you likely achieve the best results using one of the adaptive learning-rate methods.

* An additional benefit is that you will not need to tune the learning rate but will likely achieve the best results with the default value.
* In summary, RMSprop is an extension of Adagrad that deals with its radically diminishing learning rates. It is identical to Adadelta, except that Adadelta uses the RMS of parameter updates in the numerator update rule. Adam, finally, adds bias-correction and momentum to RMSprop. Insofar, RMSprop, Adadelta, and Adam are very similar algorithms that do well in similar circumstances. Kingma et al. \[10\] show that its bias-correction helps Adam slightly outperform RMSprop towards the end of optimization as gradients become sparser. Insofar, Adam might be the best overall choice

* * *

TRAIN / VAL accuracy in NN
--------------------------

The second important quantity to track while training a classifier is the validation/training accuracy. This plot can give you valuable insights into the amount of overfitting in your model:

![](images/image230.jpg)

* The gap between the training and validation accuracy indicates the amount of overfitting.
* Two possible cases are shown in the diagram on the left. The blue validation error curve shows very small validation accuracy compared to the training accuracy, indicating strong overfitting (note, it's possible for the validation accuracy to even start to go down after some point).
* NOTE: When you see this in practice you probably want to increase regularization:

* stronger L2 weight penalty
* Dropout
* collect more data.

* The other possible case is when the validation accuracy tracks the training accuracy fairly well. This case indicates that your model capacity is not high enough: make the model larger by increasing the number of parameters.
    
    * * *
    

INITIALIZERS
------------

XAVIER GLOROT:

[Why’s Xavier initialization important?](https://www.google.com/url?q=http://andyljones.tumblr.com/post/110998971763/an-explanation-of-xavier-initialization&sa=D&source=editors&ust=1621930682918000&usg=AOvVaw2J2VjpdxqPm7L0mcFwcWp6)

In short, it helps signals reach deep into the network.

* If the weights in a network start too small, then the signal shrinks as it passes through each layer until it’s too tiny to be useful.
* If the weights in a network start too large, then the signal grows as it passes through each layer until it’s too massive to be useful.

Xavier initialization makes sure the weights are ‘just right’, keeping the signal in a reasonable range of values through many layers.

To go any further than this, you’re going to need a small amount of statistics - specifically you need to know about random distributions and their variance.

[When to use glorot uniform-over-normal initialization?](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/13061/when-to-use-he-or-glorot-normal-initialization-over-uniform-init-and-what-are&sa=D&source=editors&ust=1621930682920000&usg=AOvVaw0S4N84meKf3mevkM-UgWk0)

However, i am still not seeing anything empirical that says that glorot surpesses everything else under certain conditions ([except the glorot paper](https://www.google.com/url?q=http://proceedings.mlr.press/v9/glorot10a/glorot10a.pdf&sa=D&source=editors&ust=1621930682921000&usg=AOvVaw1oDDfvHBVWODdfSLIKyfU2)), most importantly, does it really help in LSTM where the vanishing gradient is ~no longer an issue?

[He-et-al Initialization](https://www.google.com/url?q=https://towardsdatascience.com/random-initialization-for-neural-networks-a-thing-of-the-past-bfcdd806bf9e&sa=D&source=editors&ust=1621930682921000&usg=AOvVaw1m-Vr0MQD3xPW3-z6QoX2t)

This method of initializing became famous through a paper submitted in 2015 by He et al, and is similar to Xavier initialization, with the factor multiplied by two. In this method, the weights are initialized keeping in mind the size of the previous layer which helps in attaining a global minimum of the cost function faster and more efficiently.

w=np.random.randn(layer\_size\[l\],layer\_size\[l-1\])*np.sqrt(2/layer_size\[l-1\])

* * *

ACTIVATION FUNCTIONS
--------------------

([a bunch of observations, seems like a personal list](https://www.google.com/url?q=http://sentiment-mining.blogspot.co.il/2015/08/the-difference-of-activation-function.html&sa=D&source=editors&ust=1621930682923000&usg=AOvVaw0Xu8prfEyJ68W77JTrkQTY)) -

* Output layer - linear for regression, softmax for classification
* Hidden layers - hyperbolic tangent for shallow networks (less than 3 hidden layers), and ReLU for deep networks

ReLU \- The purpose of ReLU is to introduce non-linearity, since most of the real-world data we would want our network to learn would be nonlinear (e.g. convolution is a linear operation – element wise matrix multiplication and addition, so we account for nonlinearity by introducing a nonlinear function like ReLU, e.g [here](https://www.google.com/url?q=https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/&sa=D&source=editors&ust=1621930682925000&usg=AOvVaw10yBttlqYIG5J1IUxSapv4) \- search for ReLU).

* Relu is quite resistant to vanishing gradient & allows for deactivating neurons and for sparsity.
* Other nonlinear functions such as tanh or sigmoid can also be used instead of ReLU, but ReLU has been found to perform better in most situations.

1.  [Visual  + description of activation functions](https://www.google.com/url?q=https://medium.com/the-theory-of-everything/understanding-activation-functions-in-neural-networks-9491262884e0&sa=D&source=editors&ust=1621930682927000&usg=AOvVaw1ANo4GhUFzcimJ3NXuks3z)
2.  [A very good explanation + figures about activations functions](https://www.google.com/url?q=https://towardsdatascience.com/activation-functions-neural-networks-1cbd9f8d91d6&sa=D&source=editors&ust=1621930682927000&usg=AOvVaw10orY-trlhdZ3aK-3cjaT1)

[Selu](https://www.google.com/url?q=https://towardsdatascience.com/selu-make-fnns-great-again-snn-8d61526802a9&sa=D&source=editors&ust=1621930682928000&usg=AOvVaw0A_fab83QFvtsJiimzRwkW) \- better than RELU? Possibly.

[Mish](https://www.google.com/url?q=https://github.com/digantamisra98/Mish&sa=D&source=editors&ust=1621930682929000&usg=AOvVaw0ayYYnFXET4IOfxBmAFNVs): A Self Regularized Non-Monotonic Neural Activation Function, [yam peleg’s code](https://www.google.com/url?q=https://gist.github.com/ypeleg/3af35d07d7f659f387952c9843849772?fbclid%3DIwAR2x_Hzlg79_mo_zQMJGFbQWORbpdydnllnHoA_RmUlCLpqKdGwClBuJy8g&sa=D&source=editors&ust=1621930682929000&usg=AOvVaw2jwGi2RJTkZchKyBRubvHz)

[Mish, Medium, Keras Code, with benchmarks, computationally expensive.](https://www.google.com/url?q=https://towardsdatascience.com/mish-8283934a72df&sa=D&source=editors&ust=1621930682930000&usg=AOvVaw2dwu6LBHWZflKMeIcZIoE6)

* * *

OPTIMIZERS
----------

There are several optimizers, each had his 15 minutes of fame, some optimizers are recommended for CNN, Time Series, etc..

There are also what I call ‘experimental’ optimizers, it seems like these pop every now and then, with or without a formal proof. It is recommended to follow the literature and see what are the ‘supposedly’ state of the art optimizers atm.

[Adamod](https://www.google.com/url?q=https://medium.com/@lessw/meet-adamod-a-new-deep-learning-optimizer-with-memory-f01e831b80bd&sa=D&source=editors&ust=1621930682932000&usg=AOvVaw3QqcWi8i-Na1zIMkFlw1NQ) deeplearning optimizer with memory

[Backstitch](https://www.google.com/url?q=http://www.danielpovey.com/files/2017_nips_backstitch.pdf&sa=D&source=editors&ust=1621930682933000&usg=AOvVaw2mjtck9Mc3LgFExmMLHtMf)\- September 17 - supposedly an improvement over SGD for speech recognition using DNN. Note: it wasnt tested with other datasets or other network types.

(how does it work?) take a negative step back, then a positive step forward. I.e., When processing a minibatch, instead of taking a single SGD step, we first take a step with −α times the current learning rate, for α > 0 (e.g. α = 0.3), and then a step with 1 + α times the learning rate, with the same minibatch (and a recomputed gradient). So we are taking a small negative step, and then a larger positive step. This resulted in quite large improvements – around 10% relative improvement \[37\] – for our best speech recognition DNNs. The recommended hyper parameters are in the paper.

Drawbacks: takes twice to train, momentum not implemented or tested, dropout is mandatory for improvement, slow starter.

[Documentation about optimizers](https://www.google.com/url?q=https://keras.io/optimizers/&sa=D&source=editors&ust=1621930682934000&usg=AOvVaw0R-S-1JVFJVXnp4mmPTO2Q) in keras

* SGD can be fine tuned
* For others Leave most parameters as they were

[Best description on optimizers with momentum etc, from sgd to nadam, formulas and intuition](https://www.google.com/url?q=https://towardsdatascience.com/10-gradient-descent-optimisation-algorithms-86989510b5e9&sa=D&source=editors&ust=1621930682935000&usg=AOvVaw1g8woPVNZgE1AygH6P2RX7)

![](images/image72.png)

* * *

DROPOUT LAYERS IN KERAS AND GENERAL
-----------------------------------

[A very influential paper about dropout and how beneficial it is - bottom line always use it.](https://www.google.com/url?q=http://jmlr.org/papers/volume15/srivastava14a/srivastava14a.pdf&sa=D&source=editors&ust=1621930682936000&usg=AOvVaw0t2Pm4oQu35M1oCrCAHKNO)

OPEN QUESTIONs:

1.  does a dropout layer improve performance even if an lstm layer has dropout or recurrent dropout.
2.  What is the diff between a separate layer and inside the lstm layer.
3.  What is the diff in practice and intuitively between drop and recurrentdrop

[Dropout layers in keras, or dropout regularization:](https://www.google.com/url?q=https://machinelearningmastery.com/dropout-regularization-deep-learning-models-keras/&sa=D&source=editors&ust=1621930682938000&usg=AOvVaw3Vvge2pbwUjtEawvmb_SaU)

* Dropout is a technique where randomly selected neurons are ignored RANDOMLY during training.
* contribution to the activation of downstream neurons is temporally removed on the forward pass and any weight updates are not applied to the neuron on the backward pass.
* As a neural network learns, neuron weights settle into their context within the network.
* Weights of neurons are tuned for specific features providing some specialization. Neighboring neurons become to rely on this specialization, which if taken too far can result in a fragile model too specialized to the training data. (overfitting)
* This reliant on context for a neuron during training is referred to complex co-adaptations.
* After dropout, other neurons will have to step in and handle the representation required to make predictions for the missing neurons, which is believed to result in multiple independent internal representations being learned by the network.
* Thus, the effect of dropout is that the network becomes less sensitive to the specific weights of neurons.
* This in turn leads to a network with better generalization capability and less likely to overfit the training data.

[Another great answer about drop out](https://www.google.com/url?q=https://www.quora.com/In-Keras-what-is-a-dense-and-a-dropout-layer&sa=D&source=editors&ust=1621930682940000&usg=AOvVaw3XPWgsr1RAf5Bgql9BR-oD) -

* as a consequence of the 50% dropout, the neural network will learn different, redundant representations; the network can’t rely on the particular neurons and the combination (or interaction) of these to be present.
* Another nice side effect is that training will be faster.
* Rules:

* Dropout is only applied during training,
* Need to rescale the remaining neuron activations. E.g., if you set 50% of the activations in a given layer to zero, you need to scale up the remaining ones by a factor of 2.
* if the training has finished, you’d use the complete network for testing (or in other words, you set the dropout probability to 0).

[Implementation of drop out in keras](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/18088/convolutional-layer-dropout-layer-in-keras/18098&sa=D&source=editors&ust=1621930682942000&usg=AOvVaw2eJNCozQOp9jPN98agHacM) is “inverse dropout” -  n the Keras implementation, the output values are corrected during training (by dividing, in addition to randomly dropping out the values) instead of during testing (by multiplying). This is called "inverted dropout".

Inverted dropout is functionally equivalent to original dropout (as per your link to Srivastava's paper), with a nice feature that the network does not use dropout layers at all during test and prediction. This is explained a little in this [Keras issue](https://www.google.com/url?q=https://github.com/fchollet/keras/issues/3305&sa=D&source=editors&ust=1621930682943000&usg=AOvVaw3scB3zhvvEE3HBGqQmJg92).

[Dropout notes and rules of thumb aka “best practice” -](https://www.google.com/url?q=http://blog.mrtanke.com/2016/10/09/Keras-Study-Notes-3-Dropout-Regularization-for-Deep-Networks/&sa=D&source=editors&ust=1621930682944000&usg=AOvVaw0ik828YiFBenik9aEzU_fZ)

* dropout value of 20%-50% of neurons with 20% providing a good starting point. (A probability too low has minimal effect and a value too high results in underlearning by the network.)
* Use a large network for better performance, i.e.,  when dropout is used on a larger network, giving the model more of an opportunity to learn independent representations.
* Use dropout on VISIBLE AND HIDDEN. Application of dropout at each layer of the network has shown good results.
* Unclear ? Use a large learning rate with decay and a large momentum. Increase your learning rate by a factor of 10 to 100 and use a high momentum value of 0.9 or 0.99.
* Unclear ? Constrain the size of network weights. A large learning rate can result in very large network weights. Imposing a constraint on the size of network weights such as max-norm regularization with a size of 4 or 5 has been shown to improve results.

[Difference between LSTM ‘dropout’ and ‘recurrent_dropout’](https://www.google.com/url?q=https://stackoverflow.com/questions/44924690/keras-the-difference-between-lstm-dropout-and-lstm-recurrent-dropout&sa=D&source=editors&ust=1621930682946000&usg=AOvVaw3zqLYOO_pUmDDIpu900Jhv) \- vertical vs horizontal.

I suggest taking a look at (the first part of) [this paper](https://www.google.com/url?q=https://arxiv.org/pdf/1512.05287.pdf&sa=D&source=editors&ust=1621930682946000&usg=AOvVaw0SriFMKB5HMjIShYr0k-0E). Regular dropout is applied on the inputs and/or the outputs, meaning the vertical arrows from x_tand to h_t. In you add it as an argument to your layer, it will mask the inputs; you can add a Dropout layer after your recurrent layer to mask the outputs as well. Recurrent dropout masks (or "drops") the connections between the recurrent units; that would be the horizontal arrows in your picture.

This picture is taken from the paper above. On the left, regular dropout on inputs and outputs. On the right, regular dropout PLUS recurrent dropout:

![This picture is taken from the paper above. On the left, regular dropout on inputs and outputs. On the right, regular dropout PLUS recurrent dropout.](images/image261.png)

NEURAL NETWORK OPTIMIZATION TECHNIQUES
--------------------------------------

Basically do these after you have a working network

1.  [Dont decay the learning rate, increase batchsize - paper](https://www.google.com/url?q=https://arxiv.org/abs/1711.00489&sa=D&source=editors&ust=1621930682948000&usg=AOvVaw1neeiXbkNFjeZvJZ93f_-L) (optimization of a network)
2.  [Add one neuron with skip connection, or to every layer in a binary classification network to get global minimum](https://www.google.com/url?q=https://arxiv.org/abs/1805.08671&sa=D&source=editors&ust=1621930682949000&usg=AOvVaw2hVNEFu8D8KIxJ-g_TCkOd).

Fine tuning
-----------

1.  [3 methods to fine tune, cut softmax layer, smaller learning rate, freeze layers](https://www.google.com/url?q=https://flyyufelix.github.io/2016/10/03/fine-tuning-in-keras-part1.html&sa=D&source=editors&ust=1621930682950000&usg=AOvVaw1bKDo-WJ77_TyOQm2nNZFa)
2.  [Fine tuning on a sunset of data](https://www.google.com/url?q=https://stats.stackexchange.com/questions/289036/fine-tuning-with-a-subset-of-the-same-data&sa=D&source=editors&ust=1621930682950000&usg=AOvVaw3kHdN9fkS_ZWD2PwOKN7eC)

Deep Learning for NLP
---------------------

* (did not fully read) [Yoav Goldberg’s course](https://www.google.com/url?q=https://docs.google.com/document/d/1Xf_dqjf7mWmSoYX0HTKnml2mssP5BjrKUs-4E17CbNo/edit%23&sa=D&source=editors&ust=1621930682951000&usg=AOvVaw0biBBCFeO2K7kXWXRJIJ51) syllabus with lots of relevant topics on DL4NLP, including bidirectional RNNS and tree RNNs.
* (did not fully read) [CS224d](https://www.google.com/url?q=http://cs224d.stanford.edu/index.html&sa=D&source=editors&ust=1621930682952000&usg=AOvVaw1ealSYQmTLJPtrGMKvzmp-): Deep Learning for Natural Language Processing, with [slides etc.](https://www.google.com/url?q=http://cs224d.stanford.edu/syllabus.html&sa=D&source=editors&ust=1621930682953000&usg=AOvVaw2nncQ326wj8aGGdB8syFkj)

[Deep Learning using Linear Support Vector Machines](https://www.google.com/url?q=http://deeplearning.net/wp-content/uploads/2013/03/dlsvm.pdf&sa=D&source=editors&ust=1621930682953000&usg=AOvVaw2-0YoRInWB_IGIc1Z7nkpg) \- 1-3% decrease in error by replacing the softmax layer with a linear support vector machine

* * *

MULTI LABEL/OUTPUT
------------------

1.  A machine learning framework for [multi-output/multi-label](https://www.google.com/url?q=https://github.com/scikit-multiflow/scikit-multiflow&sa=D&source=editors&ust=1621930682955000&usg=AOvVaw1yGZ9-VL_ivRl_xtQ0YOOl)and stream data. Inspired by MOA and MEKA, following scikit-learn's philosophy. [https://scikit-multiflow.github.io/](https://www.google.com/url?q=https://scikit-multiflow.github.io/&sa=D&source=editors&ust=1621930682956000&usg=AOvVaw2W0ZG7vatiPvqCSWL2pJ7c)
2.  [Medium on MO, sklearn and keras](https://www.google.com/url?q=https://towardsdatascience.com/what-data-scientists-should-know-about-multi-output-and-multi-label-training-b9d4be620e11&sa=D&source=editors&ust=1621930682957000&usg=AOvVaw1pQOSu4OR6Bvc7U3LgP4tV)
3.  [MO in keras, see functional API on how.](https://www.google.com/url?q=https://www.pyimagesearch.com/2018/06/04/keras-multiple-outputs-and-multiple-losses/%255C&sa=D&source=editors&ust=1621930682957000&usg=AOvVaw27XVWLGOGkdUGH5z94SMN7)

### FUZZY MULTI LABEL

1.  [Ie., probabilities or soft values instead of hard labels](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/48111/multilabel-classifcation-in-sklearn-with-soft-fuzzy-labels&sa=D&source=editors&ust=1621930682959000&usg=AOvVaw2h6zLrIG-kQibSGHub4L0c)
    
    * * *
    

DNN FRAMEWORKS
--------------

### PYTORCH

1.  Deep learning with pytorch - [The book](https://www.google.com/url?q=https://pytorch.org/assets/deep-learning/Deep-Learning-with-PyTorch.pdf&sa=D&source=editors&ust=1621930682960000&usg=AOvVaw0NBQ0kutxfEKrU7lfBK4UH)
2.  [Pytorch DL course](https://www.google.com/url?q=https://atcold.github.io/pytorch-Deep-Learning/&sa=D&source=editors&ust=1621930682961000&usg=AOvVaw3xhlMjqQ26TkihlbhVVsxD), [git](https://www.google.com/url?q=https://github.com/Atcold/pytorch-Deep-Learning&sa=D&source=editors&ust=1621930682961000&usg=AOvVaw0aLJcrskc62JiqYJRApy2p) \- yann lecun

### FAST.AI

1.  [git](https://www.google.com/url?q=https://github.com/fastai/fastai&sa=D&source=editors&ust=1621930682962000&usg=AOvVaw0evOlDhMZjEp9rAyI--gPP)

### KERAS

[A make sense introduction into keras](https://www.google.com/url?q=https://www.youtube.com/playlist?list%3DPLFxrZqbLojdKuK7Lm6uamegEFGW2wki6P&sa=D&source=editors&ust=1621930682963000&usg=AOvVaw0nsB594LtRsqC7l_ZaISAV), has several videos on the topic, going through many network types, creating custom activation functions, going through examples.

\+ Two extra videos from the same author, [examples](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D6RdflAr66-E&sa=D&source=editors&ust=1621930682964000&usg=AOvVaw0zMiPv3Ua6pOsPpLS46WH0) and [examples-2](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DfDKdITMBAGk&sa=D&source=editors&ust=1621930682964000&usg=AOvVaw3Ddm_m4t3dEPd6g3z-DMpA)

Didn’t read:

1.  [Keras cheatsheet](https://www.google.com/url?q=https://www.datacamp.com/community/blog/keras-cheat-sheet&sa=D&source=editors&ust=1621930682965000&usg=AOvVaw2NuFGdE8Cq-lIc_wsw2Cg4)
2.  [Seq2Seq RNN](https://www.google.com/url?q=https://stackoverflow.com/questions/41933958/how-to-code-a-sequence-to-sequence-rnn-in-keras&sa=D&source=editors&ust=1621930682965000&usg=AOvVaw2zcAaMZbEZCyNj8GEM_gAZ)
3.  [Stateful LSTM](https://www.google.com/url?q=https://github.com/fchollet/keras/blob/master/examples/stateful_lstm.py&sa=D&source=editors&ust=1621930682966000&usg=AOvVaw1m7s8zNaGEBDUf2Z15XDS_) \- Example script showing how to use stateful RNNs to model long sequences efficiently.
4.  [CONV LSTM](https://www.google.com/url?q=https://github.com/fchollet/keras/blob/master/examples/conv_lstm.py&sa=D&source=editors&ust=1621930682967000&usg=AOvVaw0PyWuV0nw5pa7XvGCSBnJt) \- this script demonstrate the use of a conv LSTM network, used to predict the next frame of an artificially generated move which contains moving squares.

[How to force keras to use tensorflow](https://www.google.com/url?q=https://github.com/ContinuumIO/anaconda-issues/issues/1735&sa=D&source=editors&ust=1621930682967000&usg=AOvVaw02hERHPxC4eDe4hAzTrUrf) and not teano (set the .bat file)

[Callbacks - how to create an AUC ROC score callback with keras](https://www.google.com/url?q=https://keunwoochoi.wordpress.com/2016/07/16/keras-callbacks/&sa=D&source=editors&ust=1621930682968000&usg=AOvVaw2riNjy53mxl1MgAH39Mmdz) \- with code example.

[Batch size vs. Iteratio](https://www.google.com/url?q=https://stats.stackexchange.com/questions/164876/tradeoff-batch-size-vs-number-of-iterations-to-train-a-neural-network&sa=D&source=editors&ust=1621930682969000&usg=AOvVaw1LZvvL7UmkL3X7_gyD3puD)ns in NN \ Keras.

[Keras metrics](https://www.google.com/url?q=https://machinelearningmastery.com/custom-metrics-deep-learning-keras-python/&sa=D&source=editors&ust=1621930682970000&usg=AOvVaw1fmj9h2mzKaVkGHpIsFxBB) \- classification regression and custom metrics

[Keras Metrics 2](https://www.google.com/url?q=https://machinelearningmastery.com/metrics-evaluate-machine-learning-algorithms-python/&sa=D&source=editors&ust=1621930682970000&usg=AOvVaw3V63q7gekXBcZGjAJaEg3S) \- accuracy, ROC, AUC, classification, regression r^2.

[Introduction to regression models in Keras,](https://www.google.com/url?q=https://machinelearningmastery.com/regression-tutorial-keras-deep-learning-library-python/&sa=D&source=editors&ust=1621930682971000&usg=AOvVaw00bWXi6nFKIwZsnf8U7Rai) using MSE, comparing baseline vs wide vs deep networks.

[How does Keras calculate accuracy](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/14415/how-does-keras-calculate-accuracy&sa=D&source=editors&ust=1621930682971000&usg=AOvVaw3wuCC5Nyk1kX8SnPN5IKJj)? Formula and explanation

Compares label with the rounded predicted float, i.e. bigger than 0.5 = 1, smaller than = 0

For categorical we take the argmax for the label and the prediction and compare their location.

In both cases, we average the results.

[Custom metrics (precision recall) in keras](https://www.google.com/url?q=https://stackoverflow.com/questions/41458859/keras-custom-metric-for-single-class-accuracy&sa=D&source=editors&ust=1621930682973000&usg=AOvVaw1RE0a-s-FVckVLoG2n6YGT). Which are taken from [here](https://www.google.com/url?q=https://github.com/autonomio/talos/tree/master/talos/metrics&sa=D&source=editors&ust=1621930682973000&usg=AOvVaw2_XEXEfi_JFIAIqTXoXYpe), including entropy and f1

* * *

#### KERAS MULTI GPU

1.  [When using SGD only batches between 32-512 are adequate, more can lead to lower performance, less will lead to slow training times.](https://www.google.com/url?q=https://arxiv.org/pdf/1609.04836.pdf&sa=D&source=editors&ust=1621930682974000&usg=AOvVaw1mQCeL8aQIqtFQdqRCvHRD)
2.  Note: probably doesn't reflect on adam, is there a reference?
3.  [Parallel gpu-code for keras. Its a one liner, but remember to scale batches by the amount of GPU used in order to see a (non linear) scaability in training time.](https://www.google.com/url?q=https://datascience.stackexchange.com/questions/23895/multi-gpu-in-keras&sa=D&source=editors&ust=1621930682975000&usg=AOvVaw25s97pPzD04gRo687aqys0)
4.  [Pitfalls in GPU training, this is a very important post, be aware that you can corrupt your weights using the wrong combination of batches-to-input-size](https://www.google.com/url?q=http://blog.datumbox.com/5-tips-for-multi-gpu-training-with-keras/&sa=D&source=editors&ust=1621930682976000&usg=AOvVaw0HSzY0l4tF_xXU5KoJrz3u), in keras-tensorflow.  
    When you do multi-GPU training, it is important to feed all the GPUs with data. It can happen that the very last batch of your epoch has less data than defined (because the size of your dataset can not be divided exactly by the size of your batch). This might cause some GPUs not to receive any data during the last step. Unfortunately some Keras Layers, most notably the Batch Normalization Layer, can’t cope with that leading to nan values appearing in the weights (the running mean and variance in the BN layer).
5.  [5 things to be aware of for multi gpu using keras, crucial to look at before doing anything](https://www.google.com/url?q=http://blog.datumbox.com/5-tips-for-multi-gpu-training-with-keras/&sa=D&source=editors&ust=1621930682976000&usg=AOvVaw0HSzY0l4tF_xXU5KoJrz3u)

#### KERAS FUNCTIONAL API

[What is and how to use?](https://www.google.com/url?q=https://machinelearningmastery.com/keras-functional-api-deep-learning/&sa=D&source=editors&ust=1621930682977000&usg=AOvVaw0DAC98GzrgUEA0xSRYCTfQ) A flexible way to declare layers in parallel, i.e. parallel  ways to deal with input, feature extraction, models and outputs as seen in the following images.

![Neural Network Graph With Shared Feature Extraction Layer](images/image221.png)![Neural Network Graph With Multiple Inputs](images/image161.png)

![Neural Network Graph With Multiple Outputs](images/image150.png)

#### KERAS EMBEDDING LAYER

1.  [Injecting glove to keras embedding layer and using it for classification + what is and how to use the embedding layer in keras.](https://www.google.com/url?q=https://machinelearningmastery.com/use-word-embedding-layers-deep-learning-keras/&sa=D&source=editors&ust=1621930682979000&usg=AOvVaw3XHegzCXIN697r0BFbqSW_)
2.  [Keras blog - using GLOVE for pretrained embedding layers.](https://www.google.com/url?q=https://blog.keras.io/using-pre-trained-word-embeddings-in-a-keras-model.html&sa=D&source=editors&ust=1621930682980000&usg=AOvVaw1YvcSNqE50Pg6lh0GHsGDS)
3.  [Word embedding using keras, continuous BOW - CBOW, SKIPGRAM, word2vec - really good.](https://www.google.com/url?q=https://towardsdatascience.com/understanding-feature-engineering-part-4-deep-learning-methods-for-text-data-96c44370bbfa&sa=D&source=editors&ust=1621930682980000&usg=AOvVaw1TOWH-RCelH5aDPCxApDjP)
4.  [Fasttext - comparison of key feature against word2vec](https://www.google.com/url?q=https://www.quora.com/What-is-the-main-difference-between-word2vec-and-fastText&sa=D&source=editors&ust=1621930682981000&usg=AOvVaw3peVPHLkgg_Dt5cEGucQLk)
5.  [Multiclass classification using word2vec/glove + code](https://www.google.com/url?q=https://github.com/dennybritz/cnn-text-classification-tf/issues/69&sa=D&source=editors&ust=1621930682982000&usg=AOvVaw3JSZ85Z2i3-sTcjAlPXItF)
6.  [word2vec/doc2vec/tfidf code in python for text classification](https://www.google.com/url?q=https://github.com/davidsbatista/text-classification/blob/master/train_classifiers.py&sa=D&source=editors&ust=1621930682982000&usg=AOvVaw0YYwqpeh8if4JrahJO9_Q_)
7.  [Lda & word2vec](https://www.google.com/url?q=https://www.kaggle.com/vukglisovic/classification-combining-lda-and-word2vec&sa=D&source=editors&ust=1621930682982000&usg=AOvVaw1fVNlGeKb8RhfwGHIFvo-p)
8.  [Text classification with word2vec](https://www.google.com/url?q=http://nadbordrozd.github.io/blog/2016/05/20/text-classification-with-word2vec/&sa=D&source=editors&ust=1621930682983000&usg=AOvVaw3bIsenokTxGO9NLn6O3hvJ)
9.  [Gensim word2vec](https://www.google.com/url?q=https://radimrehurek.com/gensim/models/word2vec.html&sa=D&source=editors&ust=1621930682983000&usg=AOvVaw13-lsVh5HwXi_tzAfsXHco), and [another one](https://www.google.com/url?q=http://kavita-ganesan.com/gensim-word2vec-tutorial-starter-code/&sa=D&source=editors&ust=1621930682984000&usg=AOvVaw1ekqdSXVdTWkC6qWRucEF4)
10. [Fasttext paper](https://www.google.com/url?q=https://arxiv.org/abs/1607.01759&sa=D&source=editors&ust=1621930682984000&usg=AOvVaw0uqLVern7IBjqeotWbKVFe)

#### Keras: Predict vs Evaluate

[here:](https://www.google.com/url?q=https://www.quora.com/What-is-the-difference-between-keras-evaluate-and-keras-predict&sa=D&source=editors&ust=1621930682985000&usg=AOvVaw1xTODHVFlCBubCXcJRlC8Q)

.predict()generates output predictions based on the input you pass it (for example, the predicted characters in the [MNIST example](https://www.google.com/url?q=https://github.com/fchollet/keras/blob/master/examples/mnist_mlp.py&sa=D&source=editors&ust=1621930682986000&usg=AOvVaw2bwRxHAmQfne0yx74WYWYl))

.evaluate()computes the loss based on the input you pass it, along with any other metrics that you requested in the metrics param when you compiled your model (such as accuracy in the [MNIST example](https://www.google.com/url?q=https://github.com/fchollet/keras/blob/master/examples/mnist_mlp.py&sa=D&source=editors&ust=1621930682987000&usg=AOvVaw1a6hIpUhTkSBfaDpoL7BPw))

#### Keras metrics

[For classification methods - how does keras calculate accuracy, all functions.](https://www.google.com/url?q=https://www.quora.com/How-does-Keras-calculate-accuracy&sa=D&source=editors&ust=1621930682988000&usg=AOvVaw0UYHB4YPGU4LlBpTnRfsXp)

* * *

* * *

#### LOSS IN KERAS

[Why is the training loss much higher than the testing loss?](https://www.google.com/url?q=https://keras.io/getting-started/faq/%23why-is-the-training-loss-much-higher-than-the-testing-loss&sa=D&source=editors&ust=1621930682989000&usg=AOvVaw0jzb62cxx2d-Dy2_LO6k0_) A Keras model has two modes: training and testing. Regularization mechanisms, such as Dropout and L1/L2 weight regularization, are turned off at testing time.

The training loss is the average of the losses over each batch of training data. Because your model is changing over time, the loss over the first batches of an epoch is generally higher than over the last batches. On the other hand, the testing loss for an epoch is computed using the model as it is at the end of the epoch, resulting in a lower loss.

* * *

DNN ALGORITHMS
--------------

### AUTOENCODERS

1.  [How to use AE for dimensionality reduction + code](https://www.google.com/url?q=https://statcompute.wordpress.com/2017/01/15/autoencoder-for-dimensionality-reduction/&sa=D&source=editors&ust=1621930682991000&usg=AOvVaw3ZK7AtGue-oQUDvqfRnz7G) \- using keras’ functional API
2.  [Keras.io blog post about AE’s](https://www.google.com/url?q=https://blog.keras.io/building-autoencoders-in-keras.html&sa=D&source=editors&ust=1621930682992000&usg=AOvVaw27kbEmzP2DsvLyRKty-aTj) \- regular, deep, sparse, regularized, cnn, variational

1.  A keras.io [replicate post](https://www.google.com/url?q=https://towardsdatascience.com/deep-inside-autoencoders-7e41f319999f&sa=D&source=editors&ust=1621930682992000&usg=AOvVaw0eEdYy3bdlal1RI4XjRDwm) but explains AE quite nicely.

3.  [Examples of vanilla, multi layer, CNN and sparse AE’s](https://www.google.com/url?q=https://wiseodd.github.io/techblog/2016/12/03/autoencoders/&sa=D&source=editors&ust=1621930682993000&usg=AOvVaw3_-vpH7Y3vqSOSuNt5Bqq_)
4.  [Another example of CNN-AE](https://www.google.com/url?q=https://hackernoon.com/autoencoders-deep-learning-bits-1-11731e200694&sa=D&source=editors&ust=1621930682993000&usg=AOvVaw02tuvQz-vBzB2jlkgXX3JY)
5.  [Another AE tutorial](https://www.google.com/url?q=https://towardsdatascience.com/how-to-reduce-image-noises-by-autoencoder-65d5e6de543&sa=D&source=editors&ust=1621930682994000&usg=AOvVaw0NHhz_zOsO-WA9i1fpcGiy)
6.  [Hinton’s coursera course](https://www.google.com/url?q=https://www.coursera.org/learn/neural-networks/lecture/JiT1i/from-pca-to-autoencoders-5-mins&sa=D&source=editors&ust=1621930682995000&usg=AOvVaw10htKF4VOGH8zMwFiIsIYf) on PCA vs AE, basically some info about what PCA does - maximizing variance and projecting and then what AE does and can do to achieve similar but non-linear dense representations
7.  [A great tutorial on how does the clusters look like after applying PCA/ICA/AE](https://www.google.com/url?q=https://www.kaggle.com/den3b81/2d-visualization-pca-ica-vs-autoencoders&sa=D&source=editors&ust=1621930682995000&usg=AOvVaw0N6Ul_c38_V-pd2eFQlAtR)
8.  [Another great presentation on PCA vs AE,](https://www.google.com/url?q=https://web.cs.hacettepe.edu.tr/~aykut/classes/fall2016/bbm406/slides/l25-kernel_pca.pdf&sa=D&source=editors&ust=1621930682996000&usg=AOvVaw0zFpUIFSmA6Kl0d0iLfFw-) summarized in the KPCA section of this notebook. +[another one](https://www.google.com/url?q=https://www.cs.toronto.edu/~urtasun/courses/CSC411/14_pca.pdf&sa=D&source=editors&ust=1621930682996000&usg=AOvVaw1g32ABK4NrrGfEZj-ultW3) +[StackE](https://www.google.com/url?q=https://stats.stackexchange.com/questions/261265/factor-analysis-vs-autoencoders&sa=D&source=editors&ust=1621930682997000&usg=AOvVaw1rtoe3j_qPxql15lnfyQgy)xchange        
9.  [Autoencoder tutorial with python code and how to encode after](https://www.google.com/url?q=https://ramhiser.com/post/2018-05-14-autoencoders-with-keras/&sa=D&source=editors&ust=1621930682997000&usg=AOvVaw0I6H4VUhDURjfSbIuL3769), [mastery](https://www.google.com/url?q=https://machinelearningmastery.com/encoder-decoder-attention-sequence-to-sequence-prediction-keras/&sa=D&source=editors&ust=1621930682998000&usg=AOvVaw0MlD0Qob-CYj7rM1ciTwAi)
10. [Git code for low dimensional auto encoder](https://www.google.com/url?q=https://github.com/Mylittlerapture/Low-Dimensional-Autoencoder&sa=D&source=editors&ust=1621930682998000&usg=AOvVaw3oTZA0ukQFI-ICBs1iAWPE)
11. [Bart denoising AE](https://www.google.com/url?q=https://arxiv.org/pdf/1910.13461.pdf&sa=D&source=editors&ust=1621930682999000&usg=AOvVaw1N8XbKSpYXew50lM0Mnkax), sequence to sequence pre training for NL generation translation and comprehension.
12. [Attention based seq to seq auto encoder](https://www.google.com/url?q=https://wanasit.github.io/attention-based-sequence-to-sequence-in-keras.html&sa=D&source=editors&ust=1621930682999000&usg=AOvVaw1u9jL0WFR_zknFI5dxX4rp), [git](https://www.google.com/url?q=https://github.com/wanasit/katakana&sa=D&source=editors&ust=1621930683000000&usg=AOvVaw17HOyxTFKv_gybhVgU6cQx)

[AE for anomaly detection, fraud detection](https://www.google.com/url?q=https://medium.com/@curiousily/credit-card-fraud-detection-using-autoencoders-in-keras-tensorflow-for-hackers-part-vii-20e0c85301bd&sa=D&source=editors&ust=1621930683001000&usg=AOvVaw0mpi_00zcqGTgJAHRkm9bb)

### Variational AE

1.  Unread - [Simple explanation](https://www.google.com/url?q=https://medium.com/@dmonn/what-are-variational-autoencoders-a-simple-explanation-ea7dccafb0e3&sa=D&source=editors&ust=1621930683002000&usg=AOvVaw3ddE4JjSqOxQ8DAhlYPMRw)
2.  [Pixel art VAE](https://www.google.com/url?q=https://mlexplained.wordpress.com/category/generative-models/vae/&sa=D&source=editors&ust=1621930683002000&usg=AOvVaw0sS1oz3IMdN8x4ZAbTwork)
3.  [Unread - another VAE](https://www.google.com/url?q=https://towardsdatascience.com/teaching-a-variational-autoencoder-vae-to-draw-mnist-characters-978675c95776&sa=D&source=editors&ust=1621930683003000&usg=AOvVaw1I34YX1O2VIw0_Mz3nRPBp)
4.  [Pixel GAN VAE](https://www.google.com/url?q=https://medium.com/@Synced/pixelgan-autoencoders-17496632b755&sa=D&source=editors&ust=1621930683004000&usg=AOvVaw0Vt5YNCXVNfrFS-C2SFmci)
5.  [Disentangled VAE](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D9zKuYvjFFS8&sa=D&source=editors&ust=1621930683004000&usg=AOvVaw1K1EzKraCElIW5A_S8HJNW) \- improves VAE

* * *

### SELF ORGANIZING MAPS (SOM)

1.  Git

1.  [Sompy](https://www.google.com/url?q=https://github.com/sevamoo/SOMPY&sa=D&source=editors&ust=1621930683005000&usg=AOvVaw0Na3FYANPN_9smWKH4dLUT),
2.  \*\*\*[minisom!](https://www.google.com/url?q=https://github.com/JustGlowing/minisom&sa=D&source=editors&ust=1621930683006000&usg=AOvVaw2T1H554LlYcmOd4PFwEDEX)
3.  [Many graph examples](https://www.google.com/url?q=https://medium.com/@s.ganjoo96/self-organizing-maps-b2cf58b74fdb&sa=D&source=editors&ust=1621930683006000&usg=AOvVaw3k2Q6BCFdDXmo4IgMtVPdp), [example](https://www.google.com/url?q=https://github.com/lightsalsa251/Self-Organizing-Map&sa=D&source=editors&ust=1621930683007000&usg=AOvVaw0NfuNnUz62qcpGws4pQgmJ)

2.  [Step by step with examples, calculations](https://www.google.com/url?q=https://mc.ai/self-organizing-mapsom/&sa=D&source=editors&ust=1621930683007000&usg=AOvVaw3f_uSuaxCD6eJz5tF__FR9)
3.  [Adds intuition regarding “magnetism”’](https://www.google.com/url?q=https://towardsdatascience.com/self-organizing-maps-1b7d2a84e065&sa=D&source=editors&ust=1621930683008000&usg=AOvVaw1yMIpJqCB48wxt2NJq0zOC)
4.  [Implementation and faces](https://www.google.com/url?q=https://medium.com/@navdeepsingh_2336/self-organizing-maps-for-machine-learning-algorithms-ad256a395fc5&sa=D&source=editors&ust=1621930683008000&usg=AOvVaw10Y1ScFn-cCHervDBRv4xF), intuition towards each node and what it represents in a vision. I.e., each face resembles one of K clusters.
5.  [Medium on kohonen networks, i.e., SOM](https://www.google.com/url?q=https://towardsdatascience.com/kohonen-self-organizing-maps-a29040d688da&sa=D&source=editors&ust=1621930683009000&usg=AOvVaw2l9dfF3CEtBxkuY8ClzUKE)
6.  [Som on iris](https://www.google.com/url?q=https://towardsdatascience.com/self-organizing-maps-ff5853a118d4&sa=D&source=editors&ust=1621930683010000&usg=AOvVaw3Gvs0XMw1-iZkDU3TxP6iP), explains inference - averaging, and cons of the method.
7.  [Simple explanation](https://www.google.com/url?q=https://medium.com/@valentinerutto/selforganizingmaps-in-english-35574f95b0ac&sa=D&source=editors&ust=1621930683010000&usg=AOvVaw2tjvXBINosOwvAiAdmWDcB)
8.  [Algorithm, formulas](https://www.google.com/url?q=https://towardsdatascience.com/kohonen-self-organizing-maps-a29040d688da&sa=D&source=editors&ust=1621930683011000&usg=AOvVaw2A04b2qPRDn85Ea4WUxz0o)
    
    * * *
    

* * *

### NEURO EVOLUTION (GA/GP based)

#### NEAT

[NEAT](https://www.google.com/url?q=http://www.cs.ucf.edu/~kstanley/neat.html&sa=D&source=editors&ust=1621930683012000&usg=AOvVaw17cxhKaCf3YZKVETqTmYiK) stands for NeuroEvolution of Augmenting Topologies. It is a method for evolving artificial neural networks with a genetic algorithm.  
  
NEAT implements the idea that it is most effective to start evolution with small, simple networks and allow them to become increasingly complex over generations.

  
That way, just as organisms in nature increased in complexity since the first cell, so do neural networks in NEAT.  
  
This process of continual elaboration allows finding highly sophisticated and complex neural networks.

[A great article about NEAT](https://www.google.com/url?q=http://hunterheidenreich.com/blog/neuroevolution-of-augmenting-topologies/&sa=D&source=editors&ust=1621930683013000&usg=AOvVaw1EVLgsUqo_wRwityMtmqHn)

#### HYPER-NEAT

[HyperNEAT](https://www.google.com/url?q=http://eplex.cs.ucf.edu/hyperNEATpage/&sa=D&source=editors&ust=1621930683014000&usg=AOvVaw1ErMpx8dADdW1QGuqoWO46) computes the connectivity of its neural networks as a function of their geometry.  
  
HyperNEAT is based on a theory of representation that hypothesizes that a good representation for an artificial neural network should be able to describe its pattern of connectivity compactly.  

The encoding in HyperNEAT, called [compositional pattern producing networks](https://www.google.com/url?q=http://en.wikipedia.org/wiki/Compositional_pattern-producing_network&sa=D&source=editors&ust=1621930683015000&usg=AOvVaw3P65e4f2hVqmbWQJ5MO5Nq), is designed to represent patterns with regularities such as symmetry, repetition, and repetition with variationץ  
  
(WIKI) [Compositional pattern-producing networks](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Compositional_pattern-producing_network&sa=D&source=editors&ust=1621930683015000&usg=AOvVaw2m2u7QKpJWeEVaCcHYWJL2) (CPPNs) are a variation of artificial neural networks (ANNs) that have an architecture whose evolution is guided by genetic algorithms

![](images/image205.png)

[A great HyperNeat tutorial on Medium.](https://www.google.com/url?q=https://towardsdatascience.com/hyperneat-powerful-indirect-neural-network-evolution-fba5c7c43b7b&sa=D&source=editors&ust=1621930683017000&usg=AOvVaw3Zla_GqZXvdLwTw7MFVx07)

* * *

* * *

### Radial Basis Function Network (RBFN)

\+ [RBF layer in Keras.](https://www.google.com/url?q=https://github.com/PetraVidnerova/rbf_keras/blob/master/test.py&sa=D&source=editors&ust=1621930683018000&usg=AOvVaw1FuciS27fG4-eQdZluEN_p)

The [RBFN](https://www.google.com/url?q=http://mccormickml.com/2013/08/15/radial-basis-function-network-rbfn-tutorial/&sa=D&source=editors&ust=1621930683019000&usg=AOvVaw0L1eWUlV6dYT93aYpyb88S) approach is more intuitive than the MLP.

* An RBFN performs classification by measuring the input’s similarity to examples from the training set.
* Each RBFN neuron stores a “prototype”, which is just one of the examples from the training set.
* When we want to classify a new input, each neuron computes the Euclidean distance between the input and its prototype.
* Roughly speaking, if the input more closely resembles the class A prototypes than the class B prototypes, it is classified as class A.

![Architecture_Simple](images/image186.png)

* * *

### Bayesian Neural Network (BNN)

[BNN](https://www.google.com/url?q=https://eng.uber.com/neural-networks-uncertainty-estimation/&sa=D&source=editors&ust=1621930683021000&usg=AOvVaw1anYdW49W6WO9Xxy45U1ud) -(what is?) [Bayesian neural network (BNN)](https://www.google.com/url?q=http://edwardlib.org/tutorials/bayesian-neural-network&sa=D&source=editors&ust=1621930683022000&usg=AOvVaw0seA_DN8WS5pF-JzY1tcoK)according to Uber - architecture that more accurately forecasts time series predictions and uncertainty estimations at scale. “how Uber has successfully applied this model to large-scale time series anomaly detection, enabling better accommodate rider demand during high-traffic intervals.”

Under the BNN framework, prediction uncertainty can be categorized into three types:

1.  Model uncertaintycaptures our ignorance of the model parameters and can be reduced as more samples are collected.
2.  model misspecification
3.  inherent noisecaptures the uncertainty in the data generation process and is irreducible.

Note: in a series of articles, uber explains about time series and leads to a BNN architecture.

1.  [Neural networks](https://www.google.com/url?q=https://eng.uber.com/neural-networks/&sa=D&source=editors&ust=1621930683023000&usg=AOvVaw2bud2FUW4p7Wz49NARLyHa) \- training on multi-signal raw data, training X and Y are window-based and the window size(lag) is determined in advance.

Vanilla LSTM did not work properly, therefore an architecture of

Regarding point 1: ‘run prediction with dropout 100 times’

**\* [MEDIUM with code how to do it.](https://www.google.com/url?q=https://medium.com/hal24k-techblog/how-to-generate-neural-network-confidence-intervals-with-keras-e4c0b78ebbdf&sa=D&source=editors&ust=1621930683024000&usg=AOvVaw2S_C46_cRfghb6_fnhR8Ao)

[Why do we need a confidence measure when we have a softmax probability layer?](https://www.google.com/url?q=https://hjweide.github.io/quantifying-uncertainty-in-neural-networks&sa=D&source=editors&ust=1621930683024000&usg=AOvVaw2Aplz301pA38xTpcDWf_oK) The blog post explains, for example, that with a CNN of apples, oranges, cat and dogs, a non related example such as a frog image may influence the network to decide its an apple, therefore we can’t rely on the probability as a confidence measure. The ‘run prediction with dropout 100 times’ should give us a confidence measure because it draws each weight from a bernoulli distribution.

“By applying dropout to all the weight layers in a neural network, we are essentially drawing each weight from a [Bernoulli distribution](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Bernoulli_distribution&sa=D&source=editors&ust=1621930683025000&usg=AOvVaw31ucTI1xcj846J0zt6Uf9S). In practice, this mean that we can sample from the distribution by running several forward passes through the network. This is referred to as [Monte Carlo dropout](https://www.google.com/url?q=http://arxiv.org/abs/1506.02158&sa=D&source=editors&ust=1621930683025000&usg=AOvVaw3T2clRK5Qbwtxqx4ECBoe1).”

Taken from Yarin Gal’s [blog post](https://www.google.com/url?q=http://mlg.eng.cam.ac.uk/yarin/blog_3d801aa532c1ce.html&sa=D&source=editors&ust=1621930683026000&usg=AOvVaw10wD_PRBkaw4-aOPWpoWe9) . In this figure we see how sporadic is the signal from a forward pass (black line) compared to a much cleaner signal from 100 dropout passes.

![](images/image12.png)

Is it applicable for time series? In the figure below he tried to predict the missing signal between each two dotted lines, A is a bad estimation, but with a dropout layer we can see that in most cases the signal is better predicted.

![](images/image2.png)

Going back to uber, they are actually using this idea to predict time series with LSTM, using encoder decoder framework.

![](images/image246.png)

Note: this is probably applicable in other types of networks.

[Phd Thesis by Yarin](https://www.google.com/url?q=http://mlg.eng.cam.ac.uk/yarin/blog_2248.html?fref%3Dgc%26dti%3D999449923520287&sa=D&source=editors&ust=1621930683027000&usg=AOvVaw1EcRtxtYp-1qHne9w9DH2k), he talks about uncertainty in Neural networks and using BNNs. he may have proved this thesis, but I did not read it. This blog post links to his full Phd.

Old note: [The idea behind uncertainty is (](https://www.google.com/url?q=http://mlg.eng.cam.ac.uk/yarin/blog_3d801aa532c1ce.html&sa=D&source=editors&ust=1621930683028000&usg=AOvVaw3pIPRpWjpC6ds6pYCB91zu)[paper here](https://www.google.com/url?q=https://arxiv.org/pdf/1506.02142.pdf&sa=D&source=editors&ust=1621930683028000&usg=AOvVaw1VmVK1pPwSStNrOsp5-00t))  that in order to trust your network’s classification, you drop some of the neurons during prediction, you do this ~100 times and you average the results. Intuitively this will give you confidence in your classification and increase your classification accuracy, because only a partial part of your network participated in the classification, randomly, 100 times. Please note that Softmax doesn't give you certainty.

[Medium post on prediction with drop out](https://www.google.com/url?q=https://towardsdatascience.com/is-your-algorithm-confident-enough-1b20dfe2db08&sa=D&source=editors&ust=1621930683029000&usg=AOvVaw3g3BGjdbyNqUi0lQsCpnVz)

The [solution for keras](https://www.google.com/url?q=https://github.com/keras-team/keras/issues/9412&sa=D&source=editors&ust=1621930683029000&usg=AOvVaw23esGRxyUT-pL9tVMRPjdw) says to add trainable=true for every dropout layer and add another drop out at the end of the model. Thanks sam.

“import keras

inputs = keras.Input(shape=(10,))

x = keras.layers.Dense(3)(inputs)

outputs = keras.layers.Dropout(0.5)(x, training=True)

model = keras.Model(inputs, outputs)“

* * *

### CONVOLUTIONAL NEURAL NET

![](images/image243.png)

([an excellent and thorough explanation about LeNet](https://www.google.com/url?q=https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/&sa=D&source=editors&ust=1621930683031000&usg=AOvVaw2UXrV3GsGHdrz4kJG6vJmt)) -

* Convolution Layer primary purpose is to extract features from the input image. Convolution preserves the spatial relationship between pixels by learning image features using small squares of input data.
* ReLU (more in the activation chapter) - The purpose of ReLU is to introduce non-linearity in our ConvNet

* Spatial Pooling (also called subsampling or downsampling) reduces the dimensionality of each feature map but retains the most important information. Spatial Pooling can be of different types: Max, Average, Sum etc.
* Dense / Fully Connected - a traditional Multi Layer Perceptron that uses a softmaxactivation function in the output layer to classify. The output from the convolutional and pooling layers represent high-level features of the input image. The purpose of the Fully Connected layer is to use these features for classifying the input image into various classes based on the training dataset.

The overall training process of the Convolutional Network may be summarized as below:

* Step1: We initialize all filters and parameters / weights with random values

* Step2: The network takes a single training imageas input, goes through the forward propagation step (convolution, ReLU and pooling operations along with forward propagation in the Fully Connected layer) and finds the output probabilities for each class.

* Let's say the output probabilities for the boat image above are \[0.2, 0.4, 0.1, 0.3\]
* Since weights are randomly assigned for the first training example, output probabilities are also random.

* Step3: Calculate the total error at the output layer (summation over all 4 classes)

*  (L2) Total Error = ∑  ½ (target probability – output probability) ²

* Step4: Use Backpropagation to calculate the gradients of the error with respect to all weights in the network and use gradient descent to update all filter values / weights and parameter values to minimize the output error.

* The weights are adjusted in proportion to their contribution to the total error.
* When the same image is input again, output probabilities might now be \[0.1, 0.1, 0.7, 0.1\], which is closer to the target vector \[0, 0, 1, 0\].
* This means that the network has learnt to classify this particular image correctly by adjusting its weights / filters such that the output error is reduced.
* Parameters like number of filters, filter sizes, architecture of the network etc. have all been fixed before Step 1 and do not change during training process – only the values of the filter matrix and connection weights get updated.

* Step5: Repeat steps 2-4 with all images in the training set.

The above steps train the ConvNet – this essentially means that all the weights and parameters of the ConvNet have now been optimized to correctly classify images from the training set.

When a new (unseen) image is input into the ConvNet, the network would go through the forward propagation step and output a probability for each class (for a new image, the output probabilities are calculated using the weights which have been optimized to correctly classify all the previous training examples). If our training set is large enough, the network will (hopefully) generalize well to new images and classify them into correct categories.

[Illustrated 10 CNNS architectures](https://www.google.com/url?q=https://towardsdatascience.com/illustrated-10-cnn-architectures-95d78ace614d&sa=D&source=editors&ust=1621930683035000&usg=AOvVaw3_ZKXMyN4tKa65neY-zlrb)

[A study that deals with class imbalance in CNN’s](https://www.google.com/url?q=https://arxiv.org/pdf/1710.05381.pdf&sa=D&source=editors&ust=1621930683035000&usg=AOvVaw3QEL1rNxqHuS_RUliBmDEJ) \- we systematically investigate the impact of class imbalance on classification performance of convolutional neural networks (CNNs) and compare frequently used methods to address the issue

1.  Over sampling
2.  Undersampling
3.  Thresholding probabilities (ROC?)
4.  Cost sensitive classification -different cost to misclassification
5.  One class - novelty detection. This is a concept learning technique that recognizes positive instances rather than discriminating between two classes

Using several imbalance scenarios, on several known data sets, such as MNIST![](images/image116.png)

The results indication (loosely) that oversampling is usually better in most cases, and doesn't cause overfitting in CNNs.

* * *

#### CONV-1D

1.  [How to setup a conv1d in keras, most importantly how to reshape your input vector](https://www.google.com/url?q=https://stackoverflow.com/questions/43396572/dimension-of-shape-in-conv1d/43399308%2343399308&sa=D&source=editors&ust=1621930683037000&usg=AOvVaw09jODTuXPpvlPzKpeCeGqr)
2.  [Mastery on Character ngram cnn for sentiment analysis](https://www.google.com/url?q=https://machinelearningmastery.com/develop-n-gram-multichannel-convolutional-neural-network-sentiment-analysis/&sa=D&source=editors&ust=1621930683037000&usg=AOvVaw3m5TpSOZf0cBM9QfaojJNH)

#### 1x1 CNN

1.  [Mastery](https://www.google.com/url?q=https://machinelearningmastery.com/introduction-to-1x1-convolutions-to-reduce-the-complexity-of-convolutional-neural-networks/&sa=D&source=editors&ust=1621930683038000&usg=AOvVaw3PE2L7QobOx_DqEGCWlQjj) on 1x1 cnn, for dim reduction, decreasing feature maps and other usages.

1.   “This is the most common application of this type of filter and in this way, the layer is often called a feature map pooling layer.”
2.  “In the paper, the authors propose the need for an MLP convolutional layer and the need for cross-channel pooling to promote learning across channels.”
3.  “the 1×1 filter was used explicitly for dimensionality reduction and for increasing the dimensionality of feature maps after pooling in the design of the inception module, used in the GoogLeNet model”
4.  “The 1×1 filter was used as a projection technique to match the number of filters of input to the output of residual modules in the design of the residual network “

#### MASKED R-CNN

[1\. Using mask rnn for object detection](https://www.google.com/url?q=https://machinelearningmastery.com/how-to-perform-object-detection-in-photographs-with-mask-r-cnn-in-keras/&sa=D&source=editors&ust=1621930683039000&usg=AOvVaw01b1J7wuloG-9j--QdbHGu)

#### Invariance in CNN

1.  [Making cnn shift invariance](https://www.google.com/url?q=https://richzhang.github.io/antialiased-cnns/&sa=D&source=editors&ust=1621930683040000&usg=AOvVaw2_mOGBfzTNakDzXXCzP2XZ) \- “Small shifts -- even by a single pixel -- can drastically change the output of a deep network (bars on left). We identify the cause: aliasing during downsampling. We anti-alias modern deep networks with classic signal processing, stabilizing output classifications (bars on right). We even observe accuracy increases (see plot below).

#### MAX AVERAGE POOLING

[Intuitions to the differences between max and average pooling:](https://www.google.com/url?q=https://stats.stackexchange.com/questions/291451/feature-extracted-by-max-pooling-vs-mean-pooling&sa=D&source=editors&ust=1621930683041000&usg=AOvVaw2U0QkBydom8ddq3zdVOpjE)

1.  A max-pool layer compressed by taking the maximum activation in a block. If you have a block with mostly small activation, but a small bit of large activation, you will loose the information on the low activations. I think of this as saying "this type of feature was detected in this general area".
2.  A mean-pool layer compresses by taking the mean activation in a block. If large activations are balanced by negative activations, the overall compressed activations will look like no activation at all. On the other hand, you retain some information about low activations in the previous example.
3.  MAX pooling In other words: Max pooling roughly means that only those features that are most strongly triggering outputs are used in the subsequent layers. You can look at it a little like focusing the network’s attention on what’s most characteristic for the image at hand.
4.  [GLOBAL MAX pooling](https://www.google.com/url?q=https://alexisbcook.github.io/2017/global-average-pooling-layers-for-object-localization/&sa=D&source=editors&ust=1621930683043000&usg=AOvVaw3eM-pfYg0As_LfYXLfymNf): In the last few years, experts have turned to global average pooling (GAP) layers to minimize overfitting by reducing the total number of parameters in the model. Similar to max pooling layers, GAP layers are used to reduce the spatial dimensions of a three-dimensional tensor. However, GAP layers perform a more extreme type of dimensionality reduction,
5.  [Hinton’s controversy thoughts on pooling](https://www.google.com/url?q=https://mirror2image.wordpress.com/2014/11/11/geoffrey-hinton-on-max-pooling-reddit-ama/&sa=D&source=editors&ust=1621930683044000&usg=AOvVaw18fLAlbHDmKzr0Sj3cXTZt)

#### Dilated CNN

1.  [For improved performance](https://www.google.com/url?q=https://stackoverflow.com/questions/41178576/whats-the-use-of-dilated-convolutions&sa=D&source=editors&ust=1621930683045000&usg=AOvVaw0oDUA7XY-_aVXhmZ1_5Kyh)

####  RESNET, DENSENET UNET

1.  A [https://medium.com/swlh/resnets-densenets-unets-6bbdbcfdf010](https://www.google.com/url?q=https://medium.com/swlh/resnets-densenets-unets-6bbdbcfdf010&sa=D&source=editors&ust=1621930683047000&usg=AOvVaw2SmNB960MX9RzjshdZar8N)
2.   on the trick behind them, concatenating both f(x) = x
    
    * * *
    

### Graph Convolutional Networks

[Explaination here, with some examples](https://www.google.com/url?q=https://tkipf.github.io/graph-convolutional-networks/&sa=D&source=editors&ust=1621930683048000&usg=AOvVaw3ZvYeqpkcGBQp0mJiLjARw)

### CAPSULE NEURAL NETS

1.  [The solution to CNN’s shortcomings](https://www.google.com/url?q=https://hackernoon.com/capsule-networks-are-shaking-up-ai-heres-how-to-use-them-c233a0971952&sa=D&source=editors&ust=1621930683049000&usg=AOvVaw2iHDFqND_kFuk2a2cSdcA1), where features can be identified without relations to each other in an image, i.e. changing the location of body parts will not affect the classification, and changing the orientation of the image will. The promise of capsule nets is that these two issues are solved.
2.  [Understanding capsule nets - part 2,](https://www.google.com/url?q=https://medium.com/ai%25C2%25B3-theory-practice-business/understanding-hintons-capsule-networks-part-ii-how-capsules-work-153b6ade9f66&sa=D&source=editors&ust=1621930683050000&usg=AOvVaw2Mom9qAmTH_WuybvMFS0FF) there are more parts to the series

### Transfer Learning using CNN

1.  To Add keras book chapter 5 (i think)
2.  [Mastery](https://www.google.com/url?q=https://machinelearningmastery.com/how-to-use-transfer-learning-when-developing-convolutional-neural-network-models/&sa=D&source=editors&ust=1621930683052000&usg=AOvVaw1v2D0PwHjw3gE2Zprl4ch3) on TL using CNN

1.  Classifier: The pre-trained model is used directly to classify new images.
2.  Standalone Feature Extractor: The pre-trained model, or some portion of the model, is used to pre-process images and extract relevant features.
3.  Integrated Feature Extractor: The pre-trained model, or some portion of the model, is integrated into a new model, but layers of the pre-trained model are frozen during training.
4.  Weight Initialization: The pre-trained model, or some portion of the model, is integrated into a new model, and the layers of the pre-trained model are trained in concert with the new model.

### VISUALIZE CNN

1.  [How to](https://www.google.com/url?q=https://towardsdatascience.com/how-to-visualize-convolutional-features-in-40-lines-of-code-70b7d87b0030&sa=D&source=editors&ust=1621930683055000&usg=AOvVaw1-61NKACzA_zSRkhnUxAr-)
    
    * * *
    

### Recurrent Neural Net (RNN)

RNN \- a basic NN node with a loop, previous output is merged with current input (using tanh?), for the purpose of remembering history, for time series - to predict the next X based on the previous Y.

(What is RNN?) by Andrej Karpathy - [The Unreasonable Effectiveness of Recurrent Neural Networks](https://www.google.com/url?q=http://karpathy.github.io/2015/05/21/rnn-effectiveness/&sa=D&source=editors&ust=1621930683057000&usg=AOvVaw24LvOaSe43R05aJBCJmjIh), basically a lot of information about RNNs and their usage cases 1 to N = frame captioning

* N to 1 = classification
* N to N = predict frames in a movie
* N\\2 with time delay to N\\2 = predict supply and demand
* Vanishing gradient is 100 times worse.
* Gate networks like LSTM solves vanishing gradient.

(how to initialize?) [Benchmarking RNN networks for text](https://www.google.com/url?q=https://danijar.com/benchmarking-recurrent-networks-for-language-modeling&sa=D&source=editors&ust=1621930683059000&usg=AOvVaw2GWmQLQmf0cfOPgcONpQkP) \- don't worry about initialization, use normalization and GRU for big networks.

\*\* Experimental improvements:

[Ref](https://www.google.com/url?q=https://arxiv.org/abs/1709.02755&sa=D&source=editors&ust=1621930683060000&usg=AOvVaw0vkfJifLbIK8OYGgtlBxuI) \- ”Simplified RNN, with pytorch implementation” -  changing the underlying mechanism in RNNs for the purpose of parallelizing calculation, seems to work nicely in terms of speed, not sure about state of the art results. [Controversy regarding said work](https://www.google.com/url?q=https://www.facebook.com/cho.k.hyun/posts/10208564563785149&sa=D&source=editors&ust=1621930683061000&usg=AOvVaw14qSP1QBs7xLFS9YU61NMz), author claims he already mentioned these ideas (QRNN) [first](https://www.google.com/url?q=https://www.reddit.com/r/MachineLearning/comments/6zduh2/r_170902755_training_rnns_as_fast_as_cnns/dmv9gnh/&sa=D&source=editors&ust=1621930683061000&usg=AOvVaw2hXaRb4GxnyqDNly2_fTms), a year before, however it seems like his ideas have also been reviewed as [incremental](https://www.google.com/url?q=https://openreview.net/forum?id%3DH1zJ-v5xl&sa=D&source=editors&ust=1621930683062000&usg=AOvVaw23fQ04h-TSWFLcZbth-8ZN) (PixelRNN). Its probably best to read all 3 papers in chronological order and use the most optimal solution.

[RNNCELLS - recurrent shop](https://www.google.com/url?q=https://github.com/farizrahman4u/recurrentshop&sa=D&source=editors&ust=1621930683062000&usg=AOvVaw33D6m_bSRSiywWa9kCxogm), enables you to build complex rnns with keras. Details on their significance are inside the link

Masking for RNNs - the ideas is simple, we want to use variable length inputs, although rnns do use that, they require a fixed size input. So masking of 1’s and 0’s will help it understand the real size or where the information is in the input. Motivation: Padded inputs are going to contribute to our loss and we dont want that.

[Source 1](https://www.google.com/url?q=https://www.quora.com/What-is-masking-in-a-recurrent-neural-network-RNN&sa=D&source=editors&ust=1621930683063000&usg=AOvVaw0K_q6bkFvWwf1xYO0zDIPG), [source 2](https://www.google.com/url?q=https://r2rt.com/recurrent-neural-networks-in-tensorflow-iii-variable-length-sequences.html&sa=D&source=editors&ust=1621930683064000&usg=AOvVaw2u7Zcydwm_5aP59dzW1T-X),

Visual attention RNNS - Same idea as masking but on a window-based cnn. [Paper](https://www.google.com/url?q=https://papers.nips.cc/paper/5542-recurrent-models-of-visual-attention.pdf&sa=D&source=editors&ust=1621930683065000&usg=AOvVaw1qYRtwhnFL3jNFhMjg7HHE)

* * *

#### LSTM

* [The best, hands down, lstm post out there](https://www.google.com/url?q=https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21&sa=D&source=editors&ust=1621930683066000&usg=AOvVaw2pbWKoD7MBn_GV9PnnstBv)
* LSTM - [what is?](https://www.google.com/url?q=http://colah.github.io/posts/2015-08-Understanding-LSTMs/&sa=D&source=editors&ust=1621930683067000&usg=AOvVaw3I2iGYnA3976egmsZ-xSIn) the first reference for LSTM on the web, but you should know the background before reading.
* ![](images/image103.png)
* [Hidden state vs cell state](https://www.google.com/url?q=https://www.quora.com/How-is-the-hidden-state-h-different-from-the-memory-c-in-an-LSTM-cell&sa=D&source=editors&ust=1621930683068000&usg=AOvVaw2kMDZzHPMA7JYP_7SoY1r5)\- you have to understand this concept before you dive in. i.e, Hidden state is overall state of what we have seen so far.   
    Cell state is selective memory of the past. The hidden state (h) carries the information about what an RNN cell has seen over the time and supply it to the present time such that a loss function is not just dependent upon the data it is seeing in this time instant, but also, data it has seen historically.
* [Illustrated rnn lstm gru](https://www.google.com/url?q=https://towardsdatascience.com/animated-rnn-lstm-and-gru-ef124d06cf45&sa=D&source=editors&ust=1621930683069000&usg=AOvVaw1t9lR2jupjUAkvrY50aeuG)

* [Paper](https://www.google.com/url?q=https://arxiv.org/pdf/1503.04069.pdf&sa=D&source=editors&ust=1621930683069000&usg=AOvVaw34vfXDNdI5Gl9APo6uKD3o) \- a comparison of many LSTMs variants and they are pretty much the same performance wise
* [Paper](https://www.google.com/url?q=https://arxiv.org/pdf/1503.04069.pdf&sa=D&source=editors&ust=1621930683070000&usg=AOvVaw0rJpGZlu2vlLk-E67GV6IO)  \- comparison of lstm variants, vanilla is mostly the best, forget and output gates are the most important in terms of performance. Other conclusions in the paper..
* Master on [unrolling RNN’s introductory post](https://www.google.com/url?q=https://machinelearningmastery.com/rnn-unrolling/&sa=D&source=editors&ust=1621930683070000&usg=AOvVaw22sGtMF-bOaW2AQHVCEmfr)
* Mastery on [under/over fitting lstms](https://www.google.com/url?q=https://machinelearningmastery.com/diagnose-overfitting-underfitting-lstm-models/&sa=D&source=editors&ust=1621930683071000&usg=AOvVaw3FgHrlK-vLeazA7-bFCJpV) \- but makes sense for all types of networks
* Mastery on r[eturn\_sequence and return\_state in keras LSTM](https://www.google.com/url?q=https://machinelearningmastery.com/return-sequences-and-return-states-for-lstms-in-keras/&sa=D&source=editors&ust=1621930683072000&usg=AOvVaw0ohv-hZni7CfqYpWuzN-ot)

* That return sequences return the hidden state output for each input time step.
* That return state returns the hidden state output and cell state for the last input time step.
* That return sequences and return state can be used at the same time.

* Mastery on [understanding stateful vs stateless](https://www.google.com/url?q=https://machinelearningmastery.com/understanding-stateful-lstm-recurrent-neural-networks-python-keras/&sa=D&source=editors&ust=1621930683073000&usg=AOvVaw1XLhcybdYAu31nnQBvWjh2), [stateful stateless for time series](https://www.google.com/url?q=https://machinelearningmastery.com/stateful-stateless-lstm-time-series-forecasting-python/&sa=D&source=editors&ust=1621930683074000&usg=AOvVaw2ELCk-pxrScydI9PFGb9ep)
* Mastery on [timedistributed layer](https://www.google.com/url?q=https://machinelearningmastery.com/timedistributed-layer-for-long-short-term-memory-networks-in-python/&sa=D&source=editors&ust=1621930683074000&usg=AOvVaw1a6s6YerHRoUjRQDEcugnl) and seq2seq

* TimeDistributed Layer - used to connect 3d inputs from lstms to dense layers, in order to utilize the time element. Otherwise it gets flattened when the connection is direct, nulling the lstm purpose. Note: nice trick that doesn't increase the dense layer structure multiplied by the number of dense neurons. It loops for each time step!  
    I.e., The TimeDistributed achieves this trick by applying the same Dense layer (same weights) to the LSTMs outputs for one time step at a time. In this way, the output layer only needs one connection to each LSTM unit (plus one bias).

For this reason, the number of training epochs needs to be increased to account for the smaller network capacity. I doubled it from 500 to 1000 to match the first one-to-one example

* Sequence Learning Problem
* One-to-One LSTM for Sequence Prediction
* Many-to-One LSTM for Sequence Prediction (without TimeDistributed)
* Many-to-Many LSTM for Sequence Prediction (with TimeDistributed)

* Mastery on [wrapping cnn-lstm with time distributed](https://www.google.com/url?q=https://machinelearningmastery.com/cnn-long-short-term-memory-networks/&sa=D&source=editors&ust=1621930683077000&usg=AOvVaw1c0q8DgbigZKisVGU3vLdr), as a whole model wrap, or on every layer in the model which is equivalent and preferred.
* Master on [visual examples](https://www.google.com/url?q=https://machinelearningmastery.com/sequence-prediction/&sa=D&source=editors&ust=1621930683078000&usg=AOvVaw3-j4I7Zl2CVDWhlzPnjeqU) for sequence prediction
* Unread - sentiment classification of IMDB movies using [Keras and LSTM](https://www.google.com/url?q=http://machinelearningmastery.com/sequence-classification-lstm-recurrent-neural-networks-python-keras/&sa=D&source=editors&ust=1621930683078000&usg=AOvVaw0jIMQuKGsi-8SBD_NYVkZ-)

* [Very important](https://www.google.com/url?q=https://yerevann.github.io/2017/06/27/interpreting-neurons-in-an-LSTM-network/&sa=D&source=editors&ust=1621930683079000&usg=AOvVaw2ZIZt1nCaik2KFK2fFJqRl) [\- how to interpret LSTM neurons in keras](https://www.google.com/url?q=https://yerevann.github.io/2017/06/27/interpreting-neurons-in-an-LSTM-network/&sa=D&source=editors&ust=1621930683079000&usg=AOvVaw2ZIZt1nCaik2KFK2fFJqRl)
* [LSTM for time-series](https://www.google.com/url?q=http://www.jakob-aungiers.com/articles/a/LSTM-Neural-Network-for-Time-Series-Prediction&sa=D&source=editors&ust=1621930683080000&usg=AOvVaw08zMEjfvPclFZtTMjDCdJT) \- (jakob) single point prediction, sequence prediction and shifted-sequence prediction with code.

Stateful vs Stateless: crucial for understanding how to leverage LSTM networks:

1.  [A good description on what it is and how to use it.](https://www.google.com/url?q=https://groups.google.com/forum/%23!topic/keras-users/l1RV_tthjoY&sa=D&source=editors&ust=1621930683081000&usg=AOvVaw3tYqFTBGEJTF2rGIxft17A)
2.  [ML mastery](https://www.google.com/url?q=https://machinelearningmastery.com/stateful-stateless-lstm-time-series-forecasting-python/&sa=D&source=editors&ust=1621930683081000&usg=AOvVaw0I5WuN8tmXFh0WRj0bZpqT)
3.  [Philippe remy](https://www.google.com/url?q=http://philipperemy.github.io/keras-stateful-lstm/&sa=D&source=editors&ust=1621930683082000&usg=AOvVaw3IdIjX7M9iCUd5LE-r79Gp) on stateful vs stateless, intuition mostly with code, but not 100% clear

Machine Learning mastery:

[A good tutorial on LSTM:](https://www.google.com/url?q=https://machinelearningmastery.com/time-series-forecasting-long-short-term-memory-network-python/&sa=D&source=editors&ust=1621930683083000&usg=AOvVaw0ywjO8bLHERZjswszlrqlQ) important notes:

1\. Scale to -1,1, because the internal activation in the lstm cell is tanh.

2.[stateful](https://www.google.com/url?q=https://machinelearningmastery.com/understanding-stateful-lstm-recurrent-neural-networks-python-keras/&sa=D&source=editors&ust=1621930683084000&usg=AOvVaw2xGlH1AeFVRJA0h87visV9) \- True, needs to reset internal states, False =stateless.  Great info & results  [HERE](https://www.google.com/url?q=https://machinelearningmastery.com/stateful-stateless-lstm-time-series-forecasting-python/&sa=D&source=editors&ust=1621930683084000&usg=AOvVaw3O2ALxZ8xF6r9Zt3Px6xrS), with seeding, with training resets (and not) and predicting resets (and not) - note: empirically matching the shampoo input, network config, etc.

[Another explanation/tutorial about stateful lstm, should be thorough.](https://www.google.com/url?q=http://philipperemy.github.io/keras-stateful-lstm/&sa=D&source=editors&ust=1621930683085000&usg=AOvVaw0SzSGgXUx5pwhmaUN4p9gK)

3\. [what is return\_sequence, return\_states](https://www.google.com/url?q=https://machinelearningmastery.com/return-sequences-and-return-states-for-lstms-in-keras/&sa=D&source=editors&ust=1621930683086000&usg=AOvVaw0delDFUJDZs0tDMLzneU5r), and how to use each one and both at the same time.

Return_sequence is needed for stacked LSTM layers.

4.[stacked LSTM](https://www.google.com/url?q=https://machinelearningmastery.com/stacked-long-short-term-memory-networks/&sa=D&source=editors&ust=1621930683087000&usg=AOvVaw2eWIDJMHRXT1edVKCTAXN1) \- each layer has represents a higher level of abstraction in TIME!

[Keras Input shape](https://www.google.com/url?q=https://stackoverflow.com/questions/44747343/keras-input-explanation-input-shape-units-batch-size-dim-etc&sa=D&source=editors&ust=1621930683088000&usg=AOvVaw3n6o4SNldUHo6MNR0kgqhL) \- a good explanation about differences between input_shape, dim, and what is. Additionally about layer calculation of inputs and output based on input shape, and sequence model vs API model.

A [comparison](https://www.google.com/url?q=https://danijar.com/language-modeling-with-layer-norm-and-gru/&sa=D&source=editors&ust=1621930683089000&usg=AOvVaw24FszDi2Q2oUJTs3UwD2L_) of LSTM/GRU/MGU with batch normalization and various initializations, GRu/Xavier/Batch are the best and recommended for RNN

[Benchmarking LSTM variants](https://www.google.com/url?q=http://proceedings.mlr.press/v37/jozefowicz15.pdf&sa=D&source=editors&ust=1621930683090000&usg=AOvVaw3F05lw_7cwuUzsJrT0Y92u): \- it looks like LSTM and GRU are competitive to mutation (i believe its only in pytorch) adding a bias to LSTM works (a bias of 1 as recommended in the [paper](https://www.google.com/url?q=https://pdfs.semanticscholar.org/1154/0131eae85b2e11d53df7f1360eeb6476e7f4.pdf&sa=D&source=editors&ust=1621930683090000&usg=AOvVaw1TR2HXZDerMHUisJZKW1SZ)), but generally speaking there is no conclusive empirical evidence that says one type of network is better than the other for all tests, but the mutated networks tend to win over lstm\\gru variants.

[BIAS 1 in keras](https://www.google.com/url?q=https://keras.io/layers/recurrent/%23lstm&sa=D&source=editors&ust=1621930683091000&usg=AOvVaw36XbrhMXqAKuzXtAxvH-e0)\- unit\_forget\_bias: Boolean. If True, add 1 to the bias of the forget gate at initializationSetting it to true will also force bias_initializer="zeros". This is recommended in [Jozefowicz et al.](https://www.google.com/url?q=http://www.jmlr.org/proceedings/papers/v37/jozefowicz15.pdf&sa=D&source=editors&ust=1621930683092000&usg=AOvVaw2K4nGAJg2ktIj4YfoMvb-I)

![](images/image135.png)

[Validation_split arg](https://www.google.com/url?q=https://www.quora.com/What-is-the-importance-of-the-validation-split-variable-in-Keras&sa=D&source=editors&ust=1621930683093000&usg=AOvVaw15nnO6lupQ4osFUPE4H90S) \- The validation split variable in Keras is a value between \[0..1\]. Keras proportionally split your training set by the value of the variable. The first set is used for training and the 2nd set for validation after each epoch.

This is a nice helper add-on by Keras, and most other Keras examples you have seen the training and test set was passed into the fit method, after you have manually made the split. The value of having a validation set is significant and is a vital step to understand how well your model is training. Ideally on a curve you want your training accuracy to be close to your validation curve, and the moment your validation curve falls below your training curve the alarm bells should go off and your model is probably busy over-fitting.

Keras is a wonderful framework for deep learning, and there are many different ways of doing things with plenty of helpers.

[Return_sequence](https://www.google.com/url?q=https://stackoverflow.com/questions/42755820/how-to-use-return-sequences-option-and-timedistributed-layer-in-keras&sa=D&source=editors&ust=1621930683094000&usg=AOvVaw1cm96gilhxzJP9I42TyZ90): unclear.

[Sequence.pad_sequences](https://www.google.com/url?q=https://stackoverflow.com/questions/42943291/what-does-keras-io-preprocessing-sequence-pad-sequences-do&sa=D&source=editors&ust=1621930683095000&usg=AOvVaw0aTA2lYtIce3HqskQ_QSRj) \- using maxlength it will either pad with zero if smaller than, or truncate it if bigger.

[Using batch size for LSTM in Keras](https://www.google.com/url?q=https://machinelearningmastery.com/use-different-batch-sizes-training-predicting-python-keras/&sa=D&source=editors&ust=1621930683096000&usg=AOvVaw2JXNsL3pvEH25L6g4W2M6X)

Imbalanced classes? Use [class_weight](https://www.google.com/url?q=https://stackoverflow.com/questions/43459317/keras-class-weight-vs-sample-weights-in-the-fit-generator&sa=D&source=editors&ust=1621930683097000&usg=AOvVaw3qAxknEDMbbIaWhpfEQKzJ)s, another explanation [here](https://www.google.com/url?q=https://stackoverflow.com/questions/43459317/keras-class-weight-vs-sample-weights-in-the-fit-generator&sa=D&source=editors&ust=1621930683098000&usg=AOvVaw3mEA5rGJ89T-XJhRSeo8BC) about class\_weights and sample\_weights.

SKlearn Formula for balanced class weights and why it works, [example](https://www.google.com/url?q=https://stackoverflow.com/questions/50152377/in-sklearn-logistic-regression-class-balanced-helps-run-the-model-with-imbala/50154388&sa=D&source=editors&ust=1621930683099000&usg=AOvVaw36eNb-SiV-HMpOPH__0JkM)

[number of units in LSTM](https://www.google.com/url?q=https://www.quora.com/What-is-the-meaning-of-%25E2%2580%259CThe-number-of-units-in-the-LSTM-cell&sa=D&source=editors&ust=1621930683100000&usg=AOvVaw2sRWGIdLUPPsZYqqrUV-rR)

[Calculate how many params are in an LSTM layer?](https://www.google.com/url?q=https://stackoverflow.com/questions/38080035/how-to-calculate-the-number-of-parameters-of-an-lstm-network&sa=D&source=editors&ust=1621930683128000&usg=AOvVaw28vCR0K4x1RwXISTn2QL4j)

![](images/image61.png)

[Understanding timedistributed in Keras](https://www.google.com/url?q=https://machinelearningmastery.com/timedistributed-layer-for-long-short-term-memory-networks-in-python/&sa=D&source=editors&ust=1621930683129000&usg=AOvVaw1SOdZMAYHc2cNcISC-w0I4), but with focus on lstm one to one, one to many and many to many - here the timedistributed is applying a dense layer to each output neuron from the lstm, which returned_sequence = true for that purpose.

This tutorial clearly shows how to manipulate input construction, lstm output neurons and the target layer for the purpose of those three problems (1:1, 1:m, m:m).

* * *

#### BIDIRECTIONAL LSTM

(what is?) Wiki -  The basic idea of BRNNs is to connect two hidden layers of opposite directions to the same output. By this structure, the output layer can get information from past and future states.

BRNN are especially useful when the context of the input is needed. For example, in handwriting recognition, the performance can be enhanced by knowledge of the letters located before and after the current letter.

[Another](https://www.google.com/url?q=https://machinelearningmastery.com/develop-bidirectional-lstm-sequence-classification-python-keras/&sa=D&source=editors&ust=1621930683131000&usg=AOvVaw2OoVBm1Srr19mZzYxE3Ike) explanation- It involves duplicating the first recurrent layer in the network so that there are now two layers side-by-side, then providing the input sequence as-is as input to the first layer and providing a reversed copy of the input sequence to the second.

.. It allows you to specify the merge mode, that is how the forward and backward outputs should be combined before being passed on to the next layer. The options are:

* ‘sum‘: The outputs are added together.
* ‘mul‘: The outputs are multiplied together.
* ‘concat‘: The outputs are concatenated together (the default), providing double the number of outputs to the next layer.
* ‘ave‘: The average of the outputs is taken.

The default mode is to concatenate, and this is the method often used in studies of bidirectional LSTMs.

[Another simplified example](https://www.google.com/url?q=https://stackoverflow.com/questions/43035827/whats-the-difference-between-a-bidirectional-lstm-and-an-lstm&sa=D&source=editors&ust=1621930683132000&usg=AOvVaw18R4VRB4wASnEZkVT7JAyn)

BACK PROPAGATION

[A great Slide about back prop, on a simple 3 neuron network, with very easy to understand calculations.](https://www.google.com/url?q=https://www.slideshare.net/AhmedGadFCIT/backpropagation-understanding-how-to-update-anns-weights-stepbystep&sa=D&source=editors&ust=1621930683133000&usg=AOvVaw3bxJ2SlptY_A-kiyF91wD8)

#### UNSUPERVISED LSTM

1.  [Paper](ftp://ftp.idsia.ch/pub/juergen/icann2001unsup.pdf), [paper2](https://www.google.com/url?q=https://arxiv.org/pdf/1502.04681.pdf&sa=D&source=editors&ust=1621930683134000&usg=AOvVaw2pSL9IK11Ysq3bRwnPZICa), [paper3](https://www.google.com/url?q=https://arxiv.org/abs/1709.02081&sa=D&source=editors&ust=1621930683134000&usg=AOvVaw0UFyJ8Fm_dazA3jRBnfSeJ)
2.  [In keras](https://www.google.com/url?q=https://www.reddit.com/r/MachineLearning/comments/4adrie/unsupervised_lstm_using_keras/&sa=D&source=editors&ust=1621930683134000&usg=AOvVaw0a9Gtb3rvE8jIzbyxkCSw0)

#### GRU

[A tutorial about GRU](https://www.google.com/url?q=https://towardsdatascience.com/understanding-gru-networks-2ef37df6c9be&sa=D&source=editors&ust=1621930683135000&usg=AOvVaw1lxZcCrmu3eRPi9WeubOaS) \- To solve the vanishing gradient problem of a standard RNN, GRU uses, so called, update gate and reset gate. Basically, these are two vectors which decide what information should be passed to the output. The special thing about them is that they can be trained to keep information from long ago, without washing it through time or remove information which is irrelevant to the prediction.

1.  update gate helps the model to determine how much of the past information (from previous time steps) needs to be passed along to the future.
2.  Reset gate essentially, this gate is used from the model to decide how much of the past information to forget.

#### RECURRENT WEIGHTED AVERAGE (RNN-WA)

What is? (a type of cell that converges to higher accuracy faster than LSTM.

it implements attention into the recurrent neural network:

1\. the keras implementation is available at [https://github.com/keisuke-nakata/rwa](https://www.google.com/url?q=https://github.com/keisuke-nakata/rwa&sa=D&source=editors&ust=1621930683136000&usg=AOvVaw2d2JTaKpUusPR4alSmfyql)

2\. the whitepaper is at [https://arxiv.org/pdf/1703.01253.pdf](https://www.google.com/url?q=https://arxiv.org/pdf/1703.01253.pdf&sa=D&source=editors&ust=1621930683137000&usg=AOvVaw1TUgO6lDlNYePDmrnk29iv)

![](images/image208.png)

#### QRNN

[Potential competitor to the transformer](https://www.google.com/url?q=https://towardsdatascience.com/qrnn-a-potential-competitor-to-the-transformer-86b5aef6c137&sa=D&source=editors&ust=1621930683137000&usg=AOvVaw3_pbIU6WcwA8iisSd7_g6X)

* * *

### GRAPH NEURAL NETWORKS (GNN)

1.  (amazing) [Why i am luke warm about GNN’s](https://www.google.com/url?q=https://www.singlelunch.com/2020/12/28/why-im-lukewarm-on-graph-neural-networks/&sa=D&source=editors&ust=1621930683138000&usg=AOvVaw0NVz8K0zCmt65XlmApNdg_) \- really good insight to what they do (compressing data, vs adjacy graphs, vs graphs, high dim relations, etc.)
2.  [Learning on graphs youtube - uriel singer](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DsnLsWos_1WU%26feature%3Dyoutu.be%26fbclid%3DIwAR0JlvF9aPgKMmeh2zGr3l3j_8AebOTjknVGyMsz0Y2EvgcqrS0MmLkBTMU&sa=D&source=editors&ust=1621930683139000&usg=AOvVaw3g3WYupQkyTgIlU1iV8nEQ)
3.  [Benchmarking GNN’s, methodology, git, the works.](https://www.google.com/url?q=https://graphdeeplearning.github.io/post/benchmarking-gnns/&sa=D&source=editors&ust=1621930683140000&usg=AOvVaw2HvRYgzrg-JZ83R1i4NiRo)
4.  [Awesome graph classification on github](https://www.google.com/url?q=https://github.com/benedekrozemberczki/awesome-graph-classification&sa=D&source=editors&ust=1621930683140000&usg=AOvVaw2m0Rld0DBZpBFSD5KOMgYs)
5.  Octavian in medium on graphs, [A really good intro to graph networks, too long too summarize](https://www.google.com/url?q=https://medium.com/octavian-ai/deep-learning-with-knowledge-graphs-3df0b469a61a&sa=D&source=editors&ust=1621930683141000&usg=AOvVaw1_M1Ktu0Yi43n3hWxhVuft), clever, mcgraph, regression, classification, embedding on graphs.
6.  [Application of graph networks](https://www.google.com/url?q=https://towardsdatascience.com/https-medium-com-aishwaryajadhav-applications-of-graph-neural-networks-1420576be574&sa=D&source=editors&ust=1621930683142000&usg=AOvVaw3dXhRe5bnsbwNX9e5vTcyD)
7.  [Recommender systems using GNN](https://www.google.com/url?q=https://towardsdatascience.com/recommender-systems-applying-graph-and-nlp-techniques-619dbedd9ecc&sa=D&source=editors&ust=1621930683142000&usg=AOvVaw0_Mt8ZELyuEIEl60HUY4LT), w2v, pytorch w2v, networkx, sparse matrices, matrix factorization, dictionary optimization, part 1 here [(how to find product relations, important: creating negative samples)](https://www.google.com/url?q=https://eugeneyan.com/2020/01/06/recommender-systems-beyond-the-user-item-matrix&sa=D&source=editors&ust=1621930683143000&usg=AOvVaw1UFL2PE-ofZUuUo-ITSWZ_)
8.  [Transformers are GNN](https://www.google.com/url?q=https://towardsdatascience.com/transformers-are-graph-neural-networks-bca9f75412aa&sa=D&source=editors&ust=1621930683143000&usg=AOvVaw3YZN6A-HzmruA2gV1FVC-3), original: [Transformers are graphs, not the typical embedding on a graph, but a more holistic approach to understanding text as a graph.](https://www.google.com/url?q=https://thegradient.pub/transformers-are-graph-neural-networks/&sa=D&source=editors&ust=1621930683143000&usg=AOvVaw0flRLbCf2MmLqfpQWj0oPB)
9.  [Cnn for graphs](https://www.google.com/url?q=https://towardsdatascience.com/how-to-do-deep-learning-on-graphs-with-graph-convolutional-networks-62acf5b143d0&sa=D&source=editors&ust=1621930683144000&usg=AOvVaw0kDxvJyvl1Q49qXYGcI6I-)
10. [Staring with gnn](https://www.google.com/url?q=https://medium.com/octavian-ai/how-to-get-started-with-machine-learning-on-graphs-7f0795c83763&sa=D&source=editors&ust=1621930683144000&usg=AOvVaw0EAriZRJcw6y8GpkNaISB4)
11. Really good - [Basics deep walk and graphsage](https://www.google.com/url?q=https://towardsdatascience.com/a-gentle-introduction-to-graph-neural-network-basics-deepwalk-and-graphsage-db5d540d50b3&sa=D&source=editors&ust=1621930683145000&usg=AOvVaw3F9GF29izg8bf_jn76Wfc-)
12. [Application of gnn](https://www.google.com/url?q=https://towardsdatascience.com/https-medium-com-aishwaryajadhav-applications-of-graph-neural-networks-1420576be574&sa=D&source=editors&ust=1621930683145000&usg=AOvVaw0nnhZTDoxJ-haATPITi2rh)
13. Michael Bronstein’s [Central page for Graph deep learning articles on Medium](https://www.google.com/url?q=https://towardsdatascience.com/graph-deep-learning/home&sa=D&source=editors&ust=1621930683146000&usg=AOvVaw2zs6Xj7gl2zbmGNn9ucfh2) (worth reading)
14. [GAT graphi attention networks](https://www.google.com/url?q=https://petar-v.com/GAT/&sa=D&source=editors&ust=1621930683146000&usg=AOvVaw1YbdN9xGbYNlPIh_Vgtgm8), paper, examples - The graph attentional layer utilised throughout these networks is computationally efficient (does not require costly matrix operations, and is parallelizable across all nodes in the graph), allows for (implicitly) assigning different importances to different nodes within a neighborhood while dealing with different sized neighborhoods, and does not depend on knowing the entire graph structure upfront—thus addressing many of the theoretical issues with approaches.
15. Medium on [Intro, basics, deep walk, graph sage](https://www.google.com/url?q=https://towardsdatascience.com/a-gentle-introduction-to-graph-neural-network-basics-deepwalk-and-graphsage-db5d540d50b3&sa=D&source=editors&ust=1621930683146000&usg=AOvVaw013j1vHcyLyMxDz3vrQPLM)

#### Deep walk

1.  [Git](https://www.google.com/url?q=https://github.com/phanein/deepwalk&sa=D&source=editors&ust=1621930683147000&usg=AOvVaw0tX31l9QiSEVxEVcuxAHjG)
2.  [Paper](https://www.google.com/url?q=https://arxiv.org/abs/1403.6652&sa=D&source=editors&ust=1621930683147000&usg=AOvVaw0yk1OuSMWfT2G7HwBQFdwW)
3.  [Medium](https://www.google.com/url?q=https://medium.com/@_init_/an-illustrated-explanation-of-using-skipgram-to-encode-the-structure-of-a-graph-deepwalk-6220e304d71b&sa=D&source=editors&ust=1621930683148000&usg=AOvVaw12dtAtC0fX6achB5cVaere) and medium on [W2v, deep walk, graph2vec, n2v](https://www.google.com/url?q=https://towardsdatascience.com/graph-embeddings-the-summary-cc6075aba007&sa=D&source=editors&ust=1621930683148000&usg=AOvVaw0GmbHYji8AJWu3JW9tztI4)

#### Node2vec

4.  [Git](https://www.google.com/url?q=https://github.com/eliorc/node2vec&sa=D&source=editors&ust=1621930683148000&usg=AOvVaw3VGluhIdFY5gs5X-J6ufge)
5.  [Stanford](https://www.google.com/url?q=https://snap.stanford.edu/node2vec/&sa=D&source=editors&ust=1621930683149000&usg=AOvVaw2V-dtghPFSTB24OvzTMuOy)
6.  [Elior on medium](https://www.google.com/url?q=https://towardsdatascience.com/node2vec-embeddings-for-graph-data-32a866340fef&sa=D&source=editors&ust=1621930683149000&usg=AOvVaw3l-AASx9DPd6keoPTKUUNu), [youtube](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D828rZgV9t1g&sa=D&source=editors&ust=1621930683149000&usg=AOvVaw0zCggsKlLPmgBuyngAdPL_)
7.  [Paper](https://www.google.com/url?q=https://cs.stanford.edu/~jure/pubs/node2vec-kdd16.pdf&sa=D&source=editors&ust=1621930683150000&usg=AOvVaw22LkOEDo1S31ucIgKyRL9b)

#### Graphsage

8.  [medium](https://www.google.com/url?q=https://towardsdatascience.com/a-gentle-introduction-to-graph-neural-network-basics-deepwalk-and-graphsage-db5d540d50b3&sa=D&source=editors&ust=1621930683150000&usg=AOvVaw1VWyg-13N6k7Mkfq1st1HC)

#### SDNE - structural deep network embedding

9.  [medium](https://www.google.com/url?q=https://towardsdatascience.com/graph-embeddings-the-summary-cc6075aba007&sa=D&source=editors&ust=1621930683151000&usg=AOvVaw0F4fgR_r2CxDwxchQb7MrV)

#### Diff2vec

10. [Git](https://www.google.com/url?q=https://github.com/benedekrozemberczki/diff2vec&sa=D&source=editors&ust=1621930683151000&usg=AOvVaw2QuzDVnm7x9DEXt7fTTP5s)
11. ![](images/image107.png)

#### Splitter

, [git](https://www.google.com/url?q=https://github.com/benedekrozemberczki/Splitter&sa=D&source=editors&ust=1621930683152000&usg=AOvVaw2JyjmzqhYZN_CdfgtQLyCr), [paper](https://www.google.com/url?q=http://epasto.org/papers/www2019splitter.pdf&sa=D&source=editors&ust=1621930683152000&usg=AOvVaw0xCDGkeaP7cEYGGrUAKiUp), “Is a Single Embedding Enough? Learning Node Representations that Capture Multiple Social Contexts”

Recent interest in graph embedding methods has focused on learning a single representation for each node in the graph. But can nodes really be best described by a single vector representation? In this work, we propose a method for learning multiple representations of the nodes in a graph (e.g., the users of a social network). Based on a principled decomposition of the ego-network, each representation encodes the role of the node in a different local community in which the nodes participate. These representations allow for improved reconstruction of the nuanced relationships that occur in the graph a phenomenon that we illustrate through state-of-the-art results on link prediction tasks on a variety of graphs, reducing the error by up to 90%. In addition, we show that these embeddings allow for effective visual analysis of the learned community structure.

![](images/image129.png)

![](images/image14.png)

16\. [Self clustering graph embeddings](https://www.google.com/url?q=https://github.com/benedekrozemberczki/GEMSEC&sa=D&source=editors&ust=1621930683153000&usg=AOvVaw0GW88XVkkxTASM3ebmfgTh)

![](images/image141.png)

17\. [Walklets](https://www.google.com/url?q=https://github.com/benedekrozemberczki/walklets?fbclid%3DIwAR2ymD7lbgP_sUde5UvKGZp7TYYYmACMFJS6UGNjqW29ethONHy7ibmDL0Q&sa=D&source=editors&ust=1621930683154000&usg=AOvVaw0HveGGXZazFCEVh6CAg7QN), similar to deep walk with node skips. - lots of improvements, works in scale due to lower size representations, improves results, etc.

#### Nodevectors

[Git](https://www.google.com/url?q=https://github.com/VHRanger/nodevectors&sa=D&source=editors&ust=1621930683154000&usg=AOvVaw0kYjRjoPEZtnIpmhjQ9hqP), The fastest network node embeddings in the west![](images/image10.png)

### SIGNAL PROCESSING NN (FFT, WAVELETS, SHAPELETS)

1.  [Fourier Transform](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DspUNpyF58BY&sa=D&source=editors&ust=1621930683155000&usg=AOvVaw1c-jWRN75cz5IXjA9eDxrS) \- decomposing frequencies
2.  [WAVELETS On youtube (4 videos)](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DQX1-xGVFqmw&sa=D&source=editors&ust=1621930683155000&usg=AOvVaw2gKbjIR5SVQOihJyp_rsY6):

1.  [used for denoising](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DveCvP1mYpww&sa=D&source=editors&ust=1621930683156000&usg=AOvVaw0djqad1pefzshtt_fzSv6m), compression, detect edges, detect features with various orientation, analyse signal power, detect and localize transients, change points in time series data and detect optimal signal representation (peaks etc) of time freq analysis of images and data.
2.  Can also be used to [reconstruct time and frequencies](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DveCvP1mYpww&sa=D&source=editors&ust=1621930683156000&usg=AOvVaw0djqad1pefzshtt_fzSv6m), analyse images in space, frequencies, orientation, identifying coherent time oscillation in time series
3.  Analyse signal variability and correlation

### HIERARCHICAL RNN

1.  [githubcode](https://www.google.com/url?q=https://github.com/keras-team/keras/blob/master/examples/mnist_hierarchical_rnn.py&sa=D&source=editors&ust=1621930683157000&usg=AOvVaw1djlTrlTAiD135TChDDX_2)

### NN-Sequence Analysis

(did not read) [A causal framework for explaining the predictions of black-box sequence-to-sequence models](https://www.google.com/url?q=http://people.csail.mit.edu/tommi/papers/AlvJaa_EMNLP2017.pdf&sa=D&source=editors&ust=1621930683157000&usg=AOvVaw1usZQ-u2JoE7jhcXgvb9Vy) \- can this be applied to other time series prediction?

### SIAMESE NETWORKS (one shot)

1.  [Siamese CNN, learns a similarity between images, not to classify](https://www.google.com/url?q=https://medium.com/predict/face-recognition-from-scratch-using-siamese-networks-and-tensorflow-df03e32f8cd0&sa=D&source=editors&ust=1621930683158000&usg=AOvVaw32u_Lf4BTu6vdkuu-xuWMD)
2.  [Visual tracking, explains contrastive and triplet loss](https://www.google.com/url?q=https://medium.com/intel-student-ambassadors/siamese-networks-for-visual-tracking-96262eaaba77&sa=D&source=editors&ust=1621930683158000&usg=AOvVaw2yv3P2-7G7Q4HSjPnFw0G1)
3.  [One shot learning, very thorough, baseline vs siamese](https://www.google.com/url?q=https://towardsdatascience.com/one-shot-learning-with-siamese-networks-using-keras-17f34e75bb3d&sa=D&source=editors&ust=1621930683159000&usg=AOvVaw0QQZznhA61JmHtOloh-3Ca)
4.  [What is triplet loss](https://www.google.com/url?q=https://towardsdatascience.com/siamese-network-triplet-loss-b4ca82c1aec8&sa=D&source=editors&ust=1621930683159000&usg=AOvVaw09v8OnSddpOhQ4ANDrdRFc)

### MULTI NETWORKS

1.  [Google whitening black boxes using multi nets, segmentation and classification](https://www.google.com/url?q=https://medium.com/health-ai/google-deepmind-might-have-just-solved-the-black-box-problem-in-medical-ai-3ed8bc21f636&sa=D&source=editors&ust=1621930683160000&usg=AOvVaw2XmOjsZa5vFbL2rUiqjHLh)

### OPTIMIZING NEURAL NETS

####  PRUNING / KNOWLEDGE DISTILLATION / LOTTERY TICKET

1.  [Awesome Knowledge distillation](https://www.google.com/url?q=https://github.com/dkozlov/awesome-knowledge-distillation&sa=D&source=editors&ust=1621930683161000&usg=AOvVaw3_WQGNhJ7tLmZcx7hb-YZ0)
2.  Lottery ticket

1.  [1](https://www.google.com/url?q=https://towardsdatascience.com/breaking-down-the-lottery-ticket-hypothesis-ca1c053b3e58&sa=D&source=editors&ust=1621930683161000&usg=AOvVaw0js9FizdvPemVEDF2EhHZn), [2](https://www.google.com/url?q=https://arxiv.org/pdf/1803.03635.pdf&sa=D&source=editors&ust=1621930683161000&usg=AOvVaw0c0tQRZla6yXWFFTahnaHx)-paper
2.  [Uber on Lottery ticket, masking weights retraining](https://www.google.com/url?q=https://eng.uber.com/deconstructing-lottery-tickets/?utm_campaign%3Dthe_algorithm.unpaid.engagement%26utm_source%3Dhs_email%26utm_medium%3Demail%26utm_content%3D72562707%26_hsenc%3Dp2ANqtz--3mi4IwIFWZsW8UaWeuiv2nCzXDXattjRENzdKT-7J6wc7ftReuDXbn39mxCnX5y18o3z7cXfxPXQgysBMJnVnfeYpHg%26_hsmi%3D72562707&sa=D&source=editors&ust=1621930683162000&usg=AOvVaw28ZHS9PQ1_oLEtf33wkPJH)
3.  [Facebook article and paper](https://www.google.com/url?q=https://ai.facebook.com/blog/understanding-the-generalization-of-lottery-tickets-in-neural-networks&sa=D&source=editors&ust=1621930683162000&usg=AOvVaw2h50ifxdJQo-0LhTVCKize)

3.  [Knowledge distillation 1](https://www.google.com/url?q=https://medium.com/neuralmachine/knowledge-distillation-dc241d7c2322&sa=D&source=editors&ust=1621930683163000&usg=AOvVaw0t8HT1fSKQqsuj3nkU4B7g), [2](https://www.google.com/url?q=https://towardsdatascience.com/knowledge-distillation-a-technique-developed-for-compacting-and-accelerating-neural-nets-732098cde690&sa=D&source=editors&ust=1621930683163000&usg=AOvVaw35LfK9RVmabmAbFINT-nns), [3](https://www.google.com/url?q=https://medium.com/neuralmachine/knowledge-distillation-dc241d7c2322&sa=D&source=editors&ust=1621930683164000&usg=AOvVaw3aJu6iTNETeQ4_ZNasopvX)
4.  [Pruning 1](https://www.google.com/url?q=https://towardsdatascience.com/scooping-into-model-pruning-in-deep-learning-da92217b84ac&sa=D&source=editors&ust=1621930683164000&usg=AOvVaw2UVQ0SKiVscvZ_I6Zz2uz-), [2](https://www.google.com/url?q=https://towardsdatascience.com/pruning-deep-neural-network-56cae1ec5505&sa=D&source=editors&ust=1621930683164000&usg=AOvVaw2EDnoEVdnoFjG7z6_ZN5Aw)
5.  [Teacher-student knowledge distillation](https://www.google.com/url?q=https://towardsdatascience.com/model-distillation-and-compression-for-recommender-systems-in-pytorch-5d81c0f2c0ec&sa=D&source=editors&ust=1621930683165000&usg=AOvVaw2Yf32OzpKAex3L3XSvbMlA) focusing on Knowledge & Ranking distillation

![](images/image119.png)

6.  [Deep network compression using teacher student](https://www.google.com/url?q=https://github.com/Zhengyu-Li/Deep-Network-Compression-based-on-Student-Teacher-Network-&sa=D&source=editors&ust=1621930683165000&usg=AOvVaw1lP0RyebttWDHW_Qev2fnI)
7.  [Lottery ticket on BERT](https://www.google.com/url?q=https://thegradient.pub/when-bert-plays-the-lottery-all-tickets-are-winning/&sa=D&source=editors&ust=1621930683166000&usg=AOvVaw1g9OhKwyZBJPCCjvuwbr46), magnitude vs structured pruning on a various metrics, i.e., LT works on bert.  
    The classical Lottery Ticket Hypothesis was mostly tested with unstructured pruning, specifically magnitude pruning (m-pruning) where the weights with the lowest magnitude are pruned irrespective of their position in the model. We iteratively prune 10% of the least magnitude weights across the entire fine-tuned model (except the embeddings) and evaluate on dev set, for as long as the performance of the pruned subnetwork is above 90% of the full model.

We also experiment with structured pruning (s-pruning) of entire components of BERT architecture based on their importance scores: specifically, we 'remove' the least important self-attention heads and MLPs by applying a mask. In each iteration, we prune 10% of BERT heads and 1 MLP, for as long as the performance of the pruned subnetwork is above 90% of the full model. To determine which heads/MLPs to prune, we use a loss-based approximation: the importance scores proposed by [Michel, Levy and Neubig (2019)](https://www.google.com/url?q=https://thegradient.pub/when-bert-plays-the-lottery-all-tickets-are-winning/%23RefMichel&sa=D&source=editors&ust=1621930683166000&usg=AOvVaw0NEJxcUIxNX7H7Z8ZL2PWk) for self-attention heads, which we extend to MLPs. Please see our paper and the original formulation for more details.

* * *

### Troubleshooting Neural Nets

([37 reasons](https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://blog.slavv.com/37-reasons-why-your-neural-network-is-not-working-4020854bd607?fref%253Dgc%2526dti%253D543283492502370%26sa%3DD%26ust%3D1505196977713000%26usg%3DAFQjCNHpCL1boTmKrBLBiaVFV4YxoxoroA&sa=D&source=editors&ust=1621930683168000&usg=AOvVaw2Ljii6q50ES0iMDf0C6E_e), [10 more](https://www.google.com/url?q=http://theorangeduck.com/page/neural-network-not-working?utm_campaign%3DRevue%2520newsletter%26utm_medium%3DNewsletter%26utm_source%3DThe%2520Wild%2520Week%2520in%2520AI%26fref%3Dgc%26dti%3D543283492502370&sa=D&source=editors&ust=1621930683168000&usg=AOvVaw0yP0h7IqHfHurNyD4l_pML)) \- copy pasted and rewritten here for convenience, it's pretty thorough, but long and extensive, you should have some sort of intuition and not go through all of these. The following list is has much more insight and information in the article itself.

The author of the original article suggests to turn everything off and then start building your network step by step, i.e., “a divide and conquer ‘debug’ method”.

#### Dataset Issues

1\. Check your input data - for stupid mistakes

2\. Try random input - if the error behaves the same on random data, there is a problem in the net. Debug layer by layer

3\. Check the data loader - input data is possibly broken. Check the input layer.

4\. Make sure input is connected to output - do samples have correct labels, even after shuffling?

5\. Is the relationship between input and output too random? - the input are not sufficiently related to the output. Its pretty amorphic, just look at the data.

6\. Is there too much noise in the dataset? - badly labelled datasets.

7\. Shuffle the dataset - useful to counteract order in the DS, always shuffle input and labels together.

8\. Reduce class imbalance - imbalance datasets may add a bias to class prediction. Balance your class, your loss, do something.

9\. Do you have enough training examples? - training from scratch? ~1000 images per class, ~probably similar numbers for other types of samples.

10\. Make sure your batches don’t contain a single label - this is probably something you wont notice and will waste a lot of time figuring out! In certain cases shuffle the DS to prevent batches from having the same label.

11\. Reduce batch size - [This paper](https://www.google.com/url?q=https://arxiv.org/abs/1609.04836&sa=D&source=editors&ust=1621930683171000&usg=AOvVaw0hJwc2YWvAGlQQI30C5uNw) points out that having a very large batch can reduce the generalization ability of the model. However, please note that I found other references that claim a too small batch will impact performance.

12\. Test on well known Datasets

* * *

#### Data Normalization/Augmentation

12\. Standardize the features - zero mean and unit variance, sounds like normalization.

13\. Do you have too much data augmentation?

Augmentation has a regularizing effect. Too much of this combined with other forms of regularization (weight L2, dropout, etc.) can cause the net to underfit.

14\. Check the preprocessing of your pretrained model - with a pretrained model make sure your input data is similar in range\[0, 1\], \[-1, 1\] or \[0, 255\]?

15\. Check the preprocessing for train/validation/test set - CS231n points out a [common pitfall](https://www.google.com/url?q=http://cs231n.github.io/neural-networks-2/%23datapre&sa=D&source=editors&ust=1621930683172000&usg=AOvVaw3iR9-295Lf3zTY0Q0qmssK):

Any preprocessing should be computed ONLY on the training data, then applied to val/test

* * *

#### Implementation issues

16\. Try solving a simpler version of the problem -divide and conquer prediction, i.e., class and box coordinates, just use one.

17\. Look for correct loss “at chance” - calculat loss for chance level, i.e 10% baseline is -ln(0.1) = 2.3 Softmax loss is the negative log probability. Afterwards increase regularization strength which should increase the loss.

18\. Check your custom loss function.

19\. Verify loss input - parameter confusion.

20\. Adjust loss weights -If your loss is composed of several smaller loss functions, make sure their magnitude relative to each is correct. This might involve testing different combinations of loss weights.

21\. Monitor other metrics -like accuracy.

22\. Test any custom layers, debugging them.

23\. Check for “frozen” layers or variables - accidentally frozen?

24\. Increase network size - more layers, more neurons.

25\. Check for hidden dimension errors - confusion due to vectors ->(64, 64, 64)

26\. Explore Gradient checking -does your backprop work for custon gradients? [1](https://www.google.com/url?q=http://ufldl.stanford.edu/tutorial/supervised/DebuggingGradientChecking/&sa=D&source=editors&ust=1621930683174000&usg=AOvVaw2n_Lk8wcoGK551dKJmsQOy)[2](https://www.google.com/url?q=http://cs231n.github.io/neural-networks-3/%23gradcheck&sa=D&source=editors&ust=1621930683174000&usg=AOvVaw0MJ_XkKg8E4usjfpsrBUnH)[3](https://www.google.com/url?q=https://www.coursera.org/learn/machine-learning/lecture/Y3s6r/gradient-checking&sa=D&source=editors&ust=1621930683175000&usg=AOvVaw3Z7HV6x3UW1-u4_Pi28FQk).

* * *

#### Training issues

27\. Solve for a really small dataset - can you generalize on 2 samples?

28\. Check weights initialization - [Xavier](https://www.google.com/url?q=http://proceedings.mlr.press/v9/glorot10a/glorot10a.pdf&sa=D&source=editors&ust=1621930683176000&usg=AOvVaw2odBoYMU1XNFPLpVuwrZU9)or [He](https://www.google.com/url?q=http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/He_Delving_Deep_into_ICCV_2015_paper.pdf&sa=D&source=editors&ust=1621930683176000&usg=AOvVaw1Ophyz0axandarKOjzH5VJ) or forget about it for networks such as RNN.

29\. Change your hyperparameters - grid search

30\. Reduce regularization - too much may underfit, try for dropout, batch norm, weight, bias , L2.

31\. Give it more training  time as long as the loss is decreasing.

32\. Switch from Train to Test mode - not clear.

33\. Visualize the training - activations, weights, layer updates, biases. [Tensorboard](https://www.google.com/url?q=https://www.tensorflow.org/get_started/summaries_and_tensorboard&sa=D&source=editors&ust=1621930683177000&usg=AOvVaw0nT-OgfZQrKUMDrfsyBj_p)and [Crayon](https://www.google.com/url?q=https://github.com/torrvision/crayon&sa=D&source=editors&ust=1621930683177000&usg=AOvVaw2Q2iT6guIYvnuJEfyz853Y). Tips on [Deeplearning4j](https://www.google.com/url?q=https://deeplearning4j.org/visualization%23usingui&sa=D&source=editors&ust=1621930683177000&usg=AOvVaw0MLqgyQ_Vce94cz5ytkyHV). Expect gaussian distribution for weights, biases start at 0 and end up almost gaussian. Keep an eye out for parameters that are diverging to +/- infinity. Keep an eye out for biases that become very large. This can sometimes occur in the output layer for classification if the distribution of classes is very imbalanced.

34\. Try a different optimizer, Check this [excellent post](https://www.google.com/url?q=http://ruder.io/optimizing-gradient-descent/&sa=D&source=editors&ust=1621930683178000&usg=AOvVaw0upuWYRzaIxM51Ha_9_rgM) about  gradient descent optimizers.

35\. Exploding / Vanishing gradients - Gradient clipping may help. Tips on: [Deeplearning4j](https://www.google.com/url?q=https://deeplearning4j.org/visualization%23usingui&sa=D&source=editors&ust=1621930683178000&usg=AOvVaw3NTXO1iyiWjWsuIGtJacbm): “A good standard deviation for the activations is on the order of 0.5 to 2.0. Significantly outside of this range may indicate vanishing or exploding activations.”

36\. Increase/Decrease Learning Rate, or use adaptive learning

37\. Overcoming NaNs, big issue for RNN - decrease LR, [how to deal with NaNs](https://www.google.com/url?q=http://russellsstewart.com/notes/0.html&sa=D&source=editors&ust=1621930683179000&usg=AOvVaw0_ZwVzUi6wihV4KjwdU5wh). evaluate layer by layer, why does it appear.

* * *

![Neural Network Graph With Shared Inputs](images/image46.png)

EMBEDDINGS
----------

(amazing) [embeddings from the ground up singlelunch](https://www.google.com/url?q=https://www.singlelunch.com/2020/02/16/embeddings-from-the-ground-up/&sa=D&source=editors&ust=1621930683180000&usg=AOvVaw32H-4TnEJgJry2BWcsg1tu)

### TOOLS

#### [FLAIR](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2019/02/flair-nlp-library-python/&sa=D&source=editors&ust=1621930683181000&usg=AOvVaw0-uuyMgX6ibXJAPTMWaTuA)

1.  Name-Entity Recognition (NER): It can recognise whether a word represents a person, location or names in the text.
2.  Parts-of-Speech Tagging (PoS): Tags all the words in the given text as to which “part of speech” they belong to.
3.  Text Classification: Classifying text based on the criteria (labels)
4.  Training Custom Models: Making our own custom models.
5.  It comprises of popular and state-of-the-art word embeddings, such as GloVe, BERT, ELMo, Character Embeddings, etc. There are very easy to use thanks to the Flair API
6.  Flair’s interface allows us to combine different word embeddings and use them to embed documents. This in turn leads to a significant uptick in results
7.  ‘Flair Embedding’ is the signature embedding provided within the Flair library. It is powered by contextual string embeddings. We’ll understand this concept in detail in the next section
8.  Flair supports a number of languages – and is always looking to add new ones

#### HUGGING FACE

1.  [git](https://www.google.com/url?q=https://github.com/huggingface/transformers&sa=D&source=editors&ust=1621930683183000&usg=AOvVaw0AVr-a_L61xN2bb9DzZUlL)

* * *

### LANGUAGE EMBEDDINGS

![](images/image99.png)

1.  History:

1.  [Google’s intro to transformers and multi-head self attention](https://www.google.com/url?q=https://ai.googleblog.com/2017/08/transformer-novel-neural-network.html&sa=D&source=editors&ust=1621930683184000&usg=AOvVaw09i-TuZsS5TDX8ofeGK1_a)
2.  [How self attention and relative positioning work](https://www.google.com/url?q=https://medium.com/@_init_/how-self-attention-with-relative-position-representations-works-28173b8c245a&sa=D&source=editors&ust=1621930683185000&usg=AOvVaw1oi0M-IBAHw4zz-J1h4wCa) (great!)

1.  Rnns are sequential, same word in diff position will have diff encoding due to the input from the previous word, which is inherently different.
2.  Attention without positional! Will have distinct (Same) encoding.
3.  Relative look at a window around each word and adds a distance vector in terms of how many words are before and after, which fixes the problem.
4.  ![](images/image49.png)
5.  ![](images/image100.png)
6.  The authors hypothesized that precise relative position information is not useful beyond a certain distance.
7.  Clipping the maximum distance enables the model to generalize to sequence lengths not seen during training.

2.  [From bert to albert](https://www.google.com/url?q=https://medium.com/@hamdan.hussam/from-bert-to-albert-pre-trained-langaug-models-5865aa5c3762&sa=D&source=editors&ust=1621930683186000&usg=AOvVaw3IdZ9BpUwUbvTFJMC8I5YW)
3.  [All the latest buzz algos](https://www.google.com/url?q=https://www.topbots.com/most-important-ai-nlp-research/%23ai-nlp-paper-2018-12&sa=D&source=editors&ust=1621930683187000&usg=AOvVaw1d_ymYIuxLEdD0JMfeUSiG)
4.  A [Summary of them](https://www.google.com/url?q=https://www.topbots.com/ai-nlp-research-pretrained-language-models/?utm_source%3Dfacebook%26utm_medium%3Dgroup_post%26utm_campaign%3Dpretrained%26fbclid%3DIwAR0smqf8qanfMayo4fRH2hFuc5LYA8-Bn5oEp-xedKcRR43QsqXIelIAzEE&sa=D&source=editors&ust=1621930683187000&usg=AOvVaw1xvBUoi3HSK0DSdty-0imH)
5.  [8 pretrained language embeddings](https://www.google.com/url?q=https://www.analyticsvidhya.com/blog/2019/03/pretrained-models-get-started-nlp/&sa=D&source=editors&ust=1621930683188000&usg=AOvVaw3wsXuaFCfEWGq_EB2IikmZ)
6.  [Hugging face pytorch transformers](https://www.google.com/url?q=https://github.com/huggingface/pytorch-transformers&sa=D&source=editors&ust=1621930683188000&usg=AOvVaw37yrx6Hdakro7P-REks_2Y)
7.  [Hugging face nlp pretrained](https://www.google.com/url?q=https://huggingface.co/models?search%3DHelsinki-NLP%252Fopus-mt%26fbclid%3DIwAR0YN7qn9uTlCeBOZw4jzWgq9IXq_9ju1ww_rVL-f1fa9EjlSP50q05QcmU&sa=D&source=editors&ust=1621930683189000&usg=AOvVaw3LJFYvx2MgpgMQNYhTu4hb)

#### Language modelling

1.  [Ruder on language modelling as the next imagenet](https://www.google.com/url?q=http://ruder.io/nlp-imagenet/&sa=D&source=editors&ust=1621930683190000&usg=AOvVaw0JJ-v69fwK3-v7K9Vqsyv-)\- Language modelling, the last approach mentioned, has been shown to capture many facets of language relevant for downstream tasks, such as [long-term dependencies](https://www.google.com/url?q=https://arxiv.org/abs/1611.01368&sa=D&source=editors&ust=1621930683190000&usg=AOvVaw1Fqv30e5xXMHGTr5lpZq-j) , [hierarchical relations](https://www.google.com/url?q=https://arxiv.org/abs/1803.11138&sa=D&source=editors&ust=1621930683190000&usg=AOvVaw1xYVUgPU-U33_3MSA25pVw) , and [sentiment](https://www.google.com/url?q=https://arxiv.org/abs/1704.01444&sa=D&source=editors&ust=1621930683190000&usg=AOvVaw2nubHjHnH23qfVlsbVsP5i) . Compared to related unsupervised tasks such as skip-thoughts and autoencoding, [language modelling performs better on syntactic tasks even with less training data](https://www.google.com/url?q=https://openreview.net/forum?id%3DBJeYYeaVJ7&sa=D&source=editors&ust=1621930683191000&usg=AOvVaw3-_3Wj7BN9YdqMGPf1MJtg).
2.  A [tutorial](https://www.google.com/url?q=https://blog.myyellowroad.com/unsupervised-sentence-representation-with-deep-learning-104b90079a93&sa=D&source=editors&ust=1621930683191000&usg=AOvVaw2qMUn9uP8qn3XhGk8HynNX) about w2v skipthought - with code!, specifically language modelling here is important - Our second method is training a language model to represent our sentences. A language model describes the probability of a text existing in a language. For example, the sentence “I like eating bananas” would be more probable than “I like eating convolutions.” We train a language model by slicing windows of n words and predicting what the next word will be in the text
3.  [Unread - universal language model fine tuning for text-classification](https://www.google.com/url?q=https://arxiv.org/abs/1801.06146&sa=D&source=editors&ust=1621930683192000&usg=AOvVaw0hRDwGQl1VRDub8BkPuWT1)
4.  ELMO - [medium](https://www.google.com/url?q=https://towardsdatascience.com/beyond-word-embeddings-part-2-word-vectors-nlp-modeling-from-bow-to-bert-4ebd4711d0ec&sa=D&source=editors&ust=1621930683192000&usg=AOvVaw0K1jCrI5q6mlhT9WxLtLD5)
5.  [Bert](https://www.google.com/url?q=https://arxiv.org/abs/1810.04805v1&sa=D&source=editors&ust=1621930683193000&usg=AOvVaw1mBEY2H1-9slS7COmXtH0i)[python git](https://www.google.com/url?q=https://github.com/CyberZHG/keras-bert&sa=D&source=editors&ust=1621930683193000&usg=AOvVaw39JEBT4cm_6Bz8jMVC2A9b)\- We introduce a new language representation model called BERT, which stands for Bidirectional Encoder Representationsfrom Transformers. Unlike recent language representation models, BERT is designed to pre-train deep bidirectional representations by jointly conditioning on both left and right context in all layers. As a result, the pre-trained BERT representations can be fine-tuned with just one additional output layer to create state-of-the-art models for a wide range of tasks, such as question answering and language inference, without substantial task-specific architecture modifications. BERT is conceptually simple and empirically powerful. It obtains new state-of-the-art results on eleven natural language processing tasks.  
    ![](images/image168.png)
6.  [Open.ai on language modelling](https://www.google.com/url?q=https://blog.openai.com/language-unsupervised/&sa=D&source=editors&ust=1621930683194000&usg=AOvVaw2pnqKGi7bU69BQscR60LDq) \- We’ve obtained state-of-the-art results on a suite of diverse language tasks with a scalable, task-agnostic system, which we’re also releasing. Our approach is a combination of two existing ideas: [transformers](https://www.google.com/url?q=https://arxiv.org/abs/1706.03762&sa=D&source=editors&ust=1621930683194000&usg=AOvVaw0AuYadzHQTYJsrnY7drhtA)and [unsupervised pre-training](https://www.google.com/url?q=https://arxiv.org/abs/1511.01432&sa=D&source=editors&ust=1621930683194000&usg=AOvVaw2nK564tSOLSqTMOf0OnP7p). [READ PAPER](https://www.google.com/url?q=https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf&sa=D&source=editors&ust=1621930683194000&usg=AOvVaw0YWZfp26ogPoL5MOo9uE0J), [VIEW CODE](https://www.google.com/url?q=https://github.com/openai/finetune-transformer-lm&sa=D&source=editors&ust=1621930683195000&usg=AOvVaw145PGXmoTiraNbOk5KITo7).
7.  Scikit-learn inspired model finetuning for natural language processing.

[finetune](https://www.google.com/url?q=https://finetune.indico.io/%23module-finetune&sa=D&source=editors&ust=1621930683195000&usg=AOvVaw2B1ezwhotIw3EwuXejHNMc)ships with a pre-trained language model from [“Improving Language Understanding by Generative Pre-Training”](https://www.google.com/url?q=https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf&sa=D&source=editors&ust=1621930683196000&usg=AOvVaw3IGBSfVbii2oAJELLkNnfG)and builds off the [OpenAI/finetune-language-model repository](https://www.google.com/url?q=https://github.com/openai/finetune-transformer-lm&sa=D&source=editors&ust=1621930683196000&usg=AOvVaw2OfGgnmC_g9fb4z0qJ6yIO).

8.  Did not read - [The annotated Transformer](https://www.google.com/url?q=http://nlp.seas.harvard.edu/2018/04/03/attention.html?fbclid%3DIwAR2_ZOfUfXcto70apLdT_StObPwatYHNRPP4OlktcmGfj9uPLhgsZPsAXzE&sa=D&source=editors&ust=1621930683196000&usg=AOvVaw2yx7QD63HAEVGAyjTr4qxk) \- jupyter on transformer with annotation
9.  Medium on [Dissecting Bert](https://www.google.com/url?q=https://medium.com/dissecting-bert/dissecting-bert-part-1-d3c3d495cdb3&sa=D&source=editors&ust=1621930683197000&usg=AOvVaw3dXerfawDUwcTDi_L_7-LS), [appendix](https://www.google.com/url?q=https://medium.com/dissecting-bert/dissecting-bert-appendix-the-decoder-3b86f66b0e5f&sa=D&source=editors&ust=1621930683197000&usg=AOvVaw1-nXu8bIk7De65IvvqhfSM)
10. [Medium on distilling 6 patterns from bert](https://www.google.com/url?q=https://towardsdatascience.com/deconstructing-bert-distilling-6-patterns-from-100-million-parameters-b49113672f77&sa=D&source=editors&ust=1621930683198000&usg=AOvVaw125lzVaR87gT5x-4RDRXYg)

#### Embedding spaces

1.  [A good overview of sentence embedding methods](https://www.google.com/url?q=http://mlexplained.com/2017/12/28/an-overview-of-sentence-embedding-methods/&sa=D&source=editors&ust=1621930683199000&usg=AOvVaw3ru5qQZLXAfdOSnsh50QFM) \- w2v ft s2v skip, d2v
2.  [A very good overview of word embeddings](https://www.google.com/url?q=http://sanjaymeena.io/tech/word-embeddings/&sa=D&source=editors&ust=1621930683199000&usg=AOvVaw3AIlSrR8S31ggC7-YeQPzi)
3.  [Intro to word embeddings - lots of images](https://www.google.com/url?q=https://www.springboard.com/blog/introduction-word-embeddings/&sa=D&source=editors&ust=1621930683200000&usg=AOvVaw1jiRsoS4ACC7wMe1zdiVhW)
4.  [A very long and extensive thesis about embeddings](https://www.google.com/url?q=http://ad-publications.informatik.uni-freiburg.de/theses/Bachelor_Jon_Ezeiza_2017.pdf&sa=D&source=editors&ust=1621930683201000&usg=AOvVaw1EWpqBdMVtgyh58Lf6Xc_v)
5.  [Sent2vec by gensim](https://www.google.com/url?q=https://rare-technologies.com/sent2vec-an-unsupervised-approach-towards-learning-sentence-embeddings/&sa=D&source=editors&ust=1621930683201000&usg=AOvVaw2I3oJyR_lhWLT_zgrT17Zt) \- sentence embedding is defined as the average of the source word embeddings of its constituent words. This model is furthermore augmented by also learning source embeddings for not only unigrams but also n-grams of words present in each sentence, and averaging the n-gram embeddings along with the words
6.  [Sent2vec vs fasttext - with info about s2v parameters](https://www.google.com/url?q=https://github.com/epfml/sent2vec/issues/19&sa=D&source=editors&ust=1621930683202000&usg=AOvVaw1FF2PupPfxx3Ox2TPprZ7w)
7.  [Wordrank vs fasttext vs w2v comparison](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Automatic_summarization%23TextRank_and_LexRank&sa=D&source=editors&ust=1621930683202000&usg=AOvVaw1KdqOcxGfN96Ny4Lf__JqS) \- the better word similarity algorithm
8.  [W2v vs glove vs sppmi vs svd by gensim](https://www.google.com/url?q=https://rare-technologies.com/making-sense-of-word2vec/&sa=D&source=editors&ust=1621930683203000&usg=AOvVaw2sI6hj1k_aqdD_4sQYI6o5)
9.  [Medium on a gentle intro to d2v](https://www.google.com/url?q=https://medium.com/scaleabout/a-gentle-introduction-to-doc2vec-db3e8c0cce5e&sa=D&source=editors&ust=1621930683203000&usg=AOvVaw0HGMQeYvcjs4TVQGBS3J9Q)
10. [Doc2vec tutorial by gensim](https://www.google.com/url?q=https://rare-technologies.com/doc2vec-tutorial/&sa=D&source=editors&ust=1621930683204000&usg=AOvVaw0LLPCo-YYIUZV0xg4nn8UG) \-  Doc2vec (aka paragraph2vec, aka sentence embeddings) modifies the word2vec algorithm to unsupervised learning of continuous representations for larger blocks of text, such as sentences, paragraphs or entire documents. -  
    Most importantly this tutorial has crucial information about the implementation parameters that should be read before using it.
11. [Git for word embeddings - taken from mastery’s nlp course](https://www.google.com/url?q=https://github.com/IshayTelavivi/nlp_crash_course&sa=D&source=editors&ust=1621930683204000&usg=AOvVaw2WOKwaQALkmmB0JgY039SF)
12. [Skip-thought -](https://www.google.com/url?q=http://mlexplained.com/2017/12/28/an-overview-of-sentence-embedding-methods/&sa=D&source=editors&ust=1621930683204000&usg=AOvVaw3gnN9xr936cptVGFveUph-) [git](https://www.google.com/url?q=https://github.com/ryankiros/skip-thoughts&sa=D&source=editors&ust=1621930683205000&usg=AOvVaw3ij4ItEZfGiHzXyhdlqI-P)\- Where word2vec attempts to predict surrounding words from certain words in a sentence, skip-thought vector extends this idea to sentences: it predicts surrounding sentences from a given sentence. NOTE: Unlike the other methods, skip-thought vectors require the sentences to be ordered in a semantically meaningful way. This makes this method difficult to use for domains such as social media text, where each snippet of text exists in isolation.
13. [Fastsent](https://www.google.com/url?q=http://mlexplained.com/2017/12/28/an-overview-of-sentence-embedding-methods/&sa=D&source=editors&ust=1621930683205000&usg=AOvVaw3BQGsPo8-UP7-G1i73qABN) \- Skip-thought vectors are slow to train. FastSent attempts to remedy this inefficiency while expanding on the core idea of skip-thought: that predicting surrounding sentences is a powerful way to obtain distributed representations. Formally, FastSent represents sentences as the simple sum of its word embeddings, making training efficient. The word embeddings are learned so that the inner product between the sentence embedding and the word embeddings of surrounding sentences is maximized. NOTE: FastSent sacrifices word order for the sake of efficiency, which can be a large disadvantage depending on the use-case.
14. Weighted sum of words - In this method, each word vector is weighted by the factor ![\frac{a}{a + p(w)} ](images/image178.png "\frac{a}{a + p(w)} ")where ![a ](images/image16.png "a ")is a hyperparameter and ![p(w) ](images/image188.png "p(w) ") is the (estimated) word frequency. This is similar to tf-idf weighting, where more frequent terms are weighted downNOTE: Word order and surrounding sentences are ignored as well, limiting the information that is encoded.
15. [Infersent by facebook](https://www.google.com/url?q=https://github.com/facebookresearch/InferSent&sa=D&source=editors&ust=1621930683206000&usg=AOvVaw1oUjQh76tiqEz2UUH_tE7O)\- [paper](https://www.google.com/url?q=https://arxiv.org/abs/1705.02364&sa=D&source=editors&ust=1621930683207000&usg=AOvVaw1JNkLFbLKVtixpbpKRi3XB) InferSent is a sentence embeddings method that provides semantic representations for English sentences. It is trained on natural language inference data and generalizes well to many different tasks. ABSTRACT: we show how universal sentence representations trained using the supervised data of the Stanford Natural Language Inference datasets can consistently outperform unsupervised methods like SkipThought vectors on a wide range of transfer tasks. Much like how computer vision uses ImageNet to obtain features, which can then be transferred to other tasks, our work tends to indicate the suitability of natural language inference for transfer learning to other NLP tasks.
16. [Universal sentence encoder - google](https://www.google.com/url?q=https://tfhub.dev/google/universal-sentence-encoder/1&sa=D&source=editors&ust=1621930683207000&usg=AOvVaw3--uCUvUsOIRRgu5rt2kUE) \- [notebook](https://www.google.com/url?q=https://colab.research.google.com/github/tensorflow/hub/blob/master/examples/colab/semantic_similarity_with_tf_hub_universal_encoder.ipynb%23scrollTo%3D8OKy8WhnKRe_&sa=D&source=editors&ust=1621930683208000&usg=AOvVaw2aGamzez9ma69ESYyoBl04), [git](https://www.google.com/url?q=https://github.com/tensorflow/hub/blob/master/examples/colab/semantic_similarity_with_tf_hub_universal_encoder.ipynb&sa=D&source=editors&ust=1621930683208000&usg=AOvVaw3PyVyK_Z2PRoloVcOxz9Vf) The Universal Sentence Encoder encodes text into high dimensional vectors that can be used for text classification, semantic similarity, clustering and other natural language tasks. The model is trained and optimized for greater-than-word length text, such as sentences, phrases or short paragraphs. It is trained on a variety of data sources and a variety of tasks with the aim of dynamically accommodating a wide variety of natural language understanding tasks. The input is variable length English text and the output is a 512 dimensional vector. We apply this model to the [STS benchmark](https://www.google.com/url?q=http://ixa2.si.ehu.es/stswiki/index.php/STSbenchmark&sa=D&source=editors&ust=1621930683209000&usg=AOvVaw1neCiR9-Lrg2_NfO5ue3hI)for semantic similarity, and the results can be seen in the [example notebook](https://www.google.com/url?q=https://colab.research.google.com/github/tensorflow/hub/blob/master/examples/colab/semantic_similarity_with_tf_hub_universal_encoder.ipynb&sa=D&source=editors&ust=1621930683209000&usg=AOvVaw0cLtyC-6uXpPkcYG7NGKEF) made available. The universal-sentence-encoder model is trained with a deep averaging network (DAN) encoder.
17. [Multi language universal sentence encoder](https://www.google.com/url?q=https://ai.googleblog.com/2019/07/multilingual-universal-sentence-encoder.html?fbclid%3DIwAR2fubNOwrxWWxYous7IyQCJ3_bY0UAdAYO_yuWONMv-aV3o8hDckSS3FCE&sa=D&source=editors&ust=1621930683210000&usg=AOvVaw3sIruXajnPs40fT5D0tRxZ) \- no hebrew
18. Pair2vec - [paper](https://www.google.com/url?q=https://arxiv.org/abs/1810.08854&sa=D&source=editors&ust=1621930683211000&usg=AOvVaw1WptfeA42KSMuu6TioV-KS)\- paper proposes new methods for learning and using embeddings of word pairs that implicitly represent background knowledge about such relationships. I.e., using p2v information with existing models to increase performance. Experiments show that our pair embeddings can complement individual word embeddings, and that they are perhaps capturing information that eludes the traditional interpretation of the Distributional Hypothesis
19. [Fast text python tutorial](https://www.google.com/url?q=http://ai.intelligentonlinetools.com/ml/fasttext-word-embeddings-text-classification-python-mlp/&sa=D&source=editors&ust=1621930683211000&usg=AOvVaw2tsttsEia-ROpEC3pE02Og)

### Cat2vec

1.  Part1: [Label encoder/ ordinal, One hot, one hot with a rare bucket, hash](https://www.google.com/url?q=https://blog.myyellowroad.com/using-categorical-data-in-machine-learning-with-python-from-dummy-variables-to-deep-category-66041f734512&sa=D&source=editors&ust=1621930683212000&usg=AOvVaw1yw4bUvor55OSR0Ihz31j9)
2.  [Part2: cat2vec using w2v](https://www.google.com/url?q=https://blog.myyellowroad.com/using-categorical-data-in-machine-learning-with-python-from-dummy-variables-to-deep-category-42fd0a43b009&sa=D&source=editors&ust=1621930683213000&usg=AOvVaw0I10REb4DH5xQJxpNvpTtz), and entity embeddings for categorical data

![](images/image229.png)

### ENTITY EMBEDDINGS

1.  Star - [General purpose embedding paper with code somewhere](https://www.google.com/url?q=https://arxiv.org/pdf/1709.03856.pdf&sa=D&source=editors&ust=1621930683214000&usg=AOvVaw0vTijjSriaXLErakQ6-dxF)
2.  [Using embeddings on tabular data, specifically categorical - introduction](https://www.google.com/url?q=http://www.fast.ai/2018/04/29/categorical-embeddings/&sa=D&source=editors&ust=1621930683214000&usg=AOvVaw3YHUGkuII-qKTWmFQoK1CC), using fastai without limiting ourselves to pytorch - the material from this post is covered in much more detail starting around 1:59:45 in [the Lesson 3 video](https://www.google.com/url?q=http://course.fast.ai/lessons/lesson3.html&sa=D&source=editors&ust=1621930683215000&usg=AOvVaw1_NYmgO3wYT86BOrFUswOM)and continuing in [Lesson 4](https://www.google.com/url?q=http://course.fast.ai/lessons/lesson4.html&sa=D&source=editors&ust=1621930683215000&usg=AOvVaw0sPxD5KRIoY2GCrV301iUr)of our free, online [Practical Deep Learning for Coders](https://www.google.com/url?q=http://course.fast.ai/&sa=D&source=editors&ust=1621930683215000&usg=AOvVaw1oy0iFnXHh0OH09rzAHzhg)course. To see example code of how this approach can be used in practice, check out our [Lesson 3 jupyter notebook](https://www.google.com/url?q=https://github.com/fastai/fastai/blob/master/courses/dl1/lesson3-rossman.ipynb&sa=D&source=editors&ust=1621930683215000&usg=AOvVaw3zaaNVJexWyjQZoitNuuLH). Perhaps Saturday and Sunday have similar behavior, and maybe Friday behaves like an average of a weekend and a weekday. Similarly, for zip codes, there may be patterns for zip codes that are geographically near each other, and for zip codes that are of similar socio-economic status.  
    The jupyter notebook doesn't seem to have the embedding example they are talking about.
3.  [Rossman on kaggle](https://www.google.com/url?q=http://blog.kaggle.com/2016/01/22/rossmann-store-sales-winners-interview-3rd-place-cheng-gui/&sa=D&source=editors&ust=1621930683216000&usg=AOvVaw2-3j74NrxOX3BGt47DRFNM), used entity-embeddings, [here](https://www.google.com/url?q=https://www.kaggle.com/c/rossmann-store-sales/discussion/17974&sa=D&source=editors&ust=1621930683216000&usg=AOvVaw3EgDpf7U-9oujB3hXGOiSa), [github](https://www.google.com/url?q=https://github.com/entron/entity-embedding-rossmann&sa=D&source=editors&ust=1621930683217000&usg=AOvVaw0VDBmyU2qw9hOlGGQxmCPK), [paper](https://www.google.com/url?q=https://arxiv.org/abs/1604.06737&sa=D&source=editors&ust=1621930683217000&usg=AOvVaw25Ak3C3JSGv1JwIPqq-NqN)
4.  [Medium on rossman - good](https://www.google.com/url?q=https://towardsdatascience.com/deep-learning-structured-data-8d6a278f3088&sa=D&source=editors&ust=1621930683218000&usg=AOvVaw0MoL_50UpCkUzvR2gaHdCl)
5.  [Embedder](https://www.google.com/url?q=https://github.com/dkn22/embedder&sa=D&source=editors&ust=1621930683218000&usg=AOvVaw0-rqQ4HXqOvN32MkWRxqcE) \- git code for a simplified entity embedding above.
6.  Finally what they do is label encode each feature using labelEncoder into an int-based feature, then push each feature into its own embedding layer of size 1 with an embedding size defined by a rule of thumb (so it seems), merge all layers, train a synthetic regression/classification and grab the weights of the corresponding embedding layer.
7.  [Entity2vec](https://www.google.com/url?q=https://github.com/ot/entity2vec&sa=D&source=editors&ust=1621930683219000&usg=AOvVaw2Ezcu9XdhQLMUp4BNnvQxU)
8.  [Categorical using keras](https://www.google.com/url?q=https://medium.com/@satnalikamayank12/on-learning-embeddings-for-categorical-data-using-keras-165ff2773fc9&sa=D&source=editors&ust=1621930683219000&usg=AOvVaw3AeQzeHk2T9FXC5fqbLJ3C)

* * *

### ALL2VEC EMBEDDINGS

1.  [ALL ???-2-VEC ideas](https://www.google.com/url?q=https://github.com/MaxwellRebo/awesome-2vec&sa=D&source=editors&ust=1621930683220000&usg=AOvVaw0oO4ivUwz-iFwKmueKESCx)
2.  Fast.ai [post](https://www.google.com/url?q=http://www.fast.ai/2018/04/29/categorical-embeddings/&sa=D&source=editors&ust=1621930683220000&usg=AOvVaw1-HpBMku4OMaoBd94bwyUf) regarding embedding for tabular data, i.e., cont and categorical data
3.  [Entity embedding for](https://www.google.com/url?q=https://github.com/fastai/fastai/blob/master/courses/dl1/lesson3-rossman.ipynb&sa=D&source=editors&ust=1621930683221000&usg=AOvVaw2HaCrpabyrgMdT8Iz34hn4) categorical data + [notebook](https://www.google.com/url?q=https://github.com/fastai/fastai/blob/master/courses/dl1/lesson3-rossman.ipynb&sa=D&source=editors&ust=1621930683221000&usg=AOvVaw2HaCrpabyrgMdT8Iz34hn4)
4.  [Kaggle taxi competition + code](https://www.google.com/url?q=http://blog.kaggle.com/2015/07/27/taxi-trajectory-winners-interview-1st-place-team-%25F0%259F%259A%2595/&sa=D&source=editors&ust=1621930683221000&usg=AOvVaw0vqAO8d5w_IJb5Xx2P5rVC)
5.  [Ross man competition - entity embeddings, code missing](https://www.google.com/url?q=http://blog.kaggle.com/2016/01/22/rossmann-store-sales-winners-interview-3rd-place-cheng-gui/&sa=D&source=editors&ust=1621930683222000&usg=AOvVaw2piR2NTubf9Ff31XmJRpbE) +[alternative code](https://www.google.com/url?q=https://github.com/entron/entity-embedding-rossmann&sa=D&source=editors&ust=1621930683222000&usg=AOvVaw0203sOI-kEAUviCz1um_Nh)
6.  [CODE TO CREATE EMBEDDINGS straight away, based onthe ideas by cheng guo in keras](https://www.google.com/url?q=https://github.com/dkn22/embedder&sa=D&source=editors&ust=1621930683223000&usg=AOvVaw2LUMeqyPBnV4Rie53hNXXS)
7.  [PIN2VEC - pinterest embeddings using the same idea](https://www.google.com/url?q=https://medium.com/the-graph/applying-deep-learning-to-related-pins-a6fee3c92f5e&sa=D&source=editors&ust=1621930683223000&usg=AOvVaw1XjQWckZWIxBxrgnQ37prt)
8.  [Tweet2Vec](https://www.google.com/url?q=https://github.com/soroushv/Tweet2Vec&sa=D&source=editors&ust=1621930683224000&usg=AOvVaw3o3CGfVDuuunj7n3I3W4Qw) \- code in theano, [paper](https://www.google.com/url?q=https://dl.acm.org/citation.cfm?doid%3D2911451.2914762&sa=D&source=editors&ust=1621930683224000&usg=AOvVaw1uN5OBJxrp9R0AEuAgF4nT).
9.  [Clustering](https://www.google.com/url?q=https://github.com/svakulenk0/tweet2vec_clustering&sa=D&source=editors&ust=1621930683224000&usg=AOvVaw3PvIsgfea4zol-yQ3XGGIe) of tweet2vec, [paper](https://www.google.com/url?q=https://arxiv.org/abs/1703.05123&sa=D&source=editors&ust=1621930683225000&usg=AOvVaw2jz3KJnlcseNYZlIQoFL2l)
10. Paper: [Character neural embeddings for tweet clustering](https://www.google.com/url?q=https://arxiv.org/pdf/1703.05123.pdf&sa=D&source=editors&ust=1621930683225000&usg=AOvVaw1dIk9OEL1BILRJvO0R-EOo)
11. Diff2vec - might be useful on social network graphs, [paper](https://www.google.com/url?q=http://homepages.inf.ed.ac.uk/s1668259/papers/sequence.pdf&sa=D&source=editors&ust=1621930683225000&usg=AOvVaw3wDJZpNqJr6zliJZUdgIi1), [code](https://www.google.com/url?q=https://github.com/benedekrozemberczki/diff2vec&sa=D&source=editors&ust=1621930683226000&usg=AOvVaw3-IVxTNMhKlJWQBIVMdf4Z)
12. emoji 2vec (below)
13. [Char2vec](https://www.google.com/url?q=https://hackernoon.com/chars2vec-character-based-language-model-for-handling-real-world-texts-with-spelling-errors-and-a3e4053a147d&sa=D&source=editors&ust=1621930683226000&usg=AOvVaw3-WzmnSKiqpwRZ1gVGVBPP) [Git](https://www.google.com/url?q=https://github.com/IntuitionEngineeringTeam/chars2vec&sa=D&source=editors&ust=1621930683227000&usg=AOvVaw0Jq3HN9SLQadRBBA0fHhNt), similarity measure for words with types.[](https://www.google.com/url?q=https://arxiv.org/abs/1708.00524&sa=D&source=editors&ust=1621930683227000&usg=AOvVaw1EBYz856PSyvUnfY_trFRZ)

EMOJIS

1.  1\. [Deepmoji](https://www.google.com/url?q=http://datadrivenjournalism.net/featured_projects/deepmoji_using_emojis_to_teach_ai_about_emotions&sa=D&source=editors&ust=1621930683227000&usg=AOvVaw0J1Esnh4DY8xT8ooZcJ9Gt),
2.  [hugging face on emotions](https://www.google.com/url?q=https://medium.com/huggingface/understanding-emotions-from-keras-to-pytorch-3ccb61d5a983&sa=D&source=editors&ust=1621930683228000&usg=AOvVaw3XPmnPb4K1I-1odSX6vk72)

1.  how to make a custom pyTorch LSTM with custom activation functions,
2.  how the PackedSequence object works and is built,
3.  how to convert an attention layer from Keras to pyTorch,
4.  how to load your data in pyTorch: DataSets and smart Batching,
5.  how to reproduce Keras weights initialization in pyTorch.

3.  [Another great emoji paper, how to get vector representations from](https://www.google.com/url?q=https://aclweb.org/anthology/S18-1039&sa=D&source=editors&ust=1621930683229000&usg=AOvVaw3zcCZkgjQBkcQcXPH6dgEA)
4.  [3\. What can we learn from emojis (deep moji)](https://www.google.com/url?q=https://www.media.mit.edu/posts/what-can-we-learn-from-emojis/&sa=D&source=editors&ust=1621930683229000&usg=AOvVaw07xQuLwi-06-UEPEJVq0Wi)
5.  [Learning millions of](https://www.google.com/url?q=https://arxiv.org/pdf/1708.00524.pdf&sa=D&source=editors&ust=1621930683230000&usg=AOvVaw36b25nGZNFUA7UjQiWb6Yw) for emoji, sentiment, sarcasm, [medium](https://www.google.com/url?q=https://medium.com/@bjarkefelbo/what-can-we-learn-from-emojis-6beb165a5ea0&sa=D&source=editors&ust=1621930683230000&usg=AOvVaw1UZ4FO-X3si4ncgWJ73kOx)
6.  [EMOJI2VEC](https://www.google.com/url?q=https://tech.instacart.com/deep-learning-with-emojis-not-math-660ba1ad6cdc&sa=D&source=editors&ust=1621930683230000&usg=AOvVaw1en_cq7ivReyibHbGRAOzN) \- medium article with keras code, a[nother paper on classifying tweets using emojis](https://www.google.com/url?q=https://arxiv.org/abs/1708.00524&sa=D&source=editors&ust=1621930683231000&usg=AOvVaw1OAf0SXqWLxTUsPio3xe4-)
7.  [Group2vec](https://www.google.com/url?q=https://github.com/cerlymarco/MEDIUM_NoteBook/tree/master/Group2Vec&sa=D&source=editors&ust=1621930683231000&usg=AOvVaw0kf3zlUB6NrfPURCyh4-z1) git and [medium](https://www.google.com/url?q=https://towardsdatascience.com/group2vec-for-advance-categorical-encoding-54dfc7a08349&sa=D&source=editors&ust=1621930683231000&usg=AOvVaw2xiYw_4e3mh-f6QEq2O6Xx), which is a multi input embedding network using a-f below. plus two other methods that involve groupby and applying entropy and join/countvec per class. Really interesting

1.  Initialize embedding layers for each categorical input;
2.  For each category, compute dot-products among other embedding representations. These are our ‘groups’ at the categorical level;
3.  Summarize each ‘group’ adopting an average pooling;
4.  Concatenate ‘group’ averages;
5.  Apply regularization techniques such as BatchNormalization or Dropout;
6.  Output probabilities.

* * *

### WORD EMBEDDINGS

1.  [Medium on Introduction into word embeddings, sentence embeddings, trends in the field.](https://www.google.com/url?q=https://towardsdatascience.com/deep-transfer-learning-for-natural-language-processing-text-classification-with-universal-1a2c69e5baa9&sa=D&source=editors&ust=1621930683233000&usg=AOvVaw35ECqNWXq1AliCLkZBLNOS) The Indian guy, [git](https://www.google.com/url?q=https://nbviewer.jupyter.org/github/dipanjanS/data_science_for_all/blob/master/tds_deep_transfer_learning_nlp_classification/Deep%2520Transfer%2520Learning%2520for%2520NLP%2520-%2520Text%2520Classification%2520with%2520Universal%2520Embeddings.ipynb&sa=D&source=editors&ust=1621930683233000&usg=AOvVaw3PnN_E9gFstVn0vetS_tHj)notebook, [his git](https://www.google.com/url?q=https://github.com/dipanjanS&sa=D&source=editors&ust=1621930683234000&usg=AOvVaw2dBUnXmBJPbThqj42Tp23w),

1.  Baseline Averaged Sentence Embeddings
2.  Doc2Vec
3.  Neural-Net Language Models (Hands-on Demo!)
4.  Skip-Thought Vectors
5.  Quick-Thought Vectors
6.  InferSent
7.  Universal Sentence Encoder

2.  [Shay palachy on word embedding covering everything from bow to word/doc/sent/phrase.](https://www.google.com/url?q=https://medium.com/@shay.palachy/document-embedding-techniques-fed3e7a6a25d&sa=D&source=editors&ust=1621930683235000&usg=AOvVaw2QXWiV_81Vn8ySMvxVFFK4)
3.  [Another intro, not as good as the one above](https://www.google.com/url?q=https://medium.com/huggingface/universal-word-sentence-embeddings-ce48ddc8fc3a&sa=D&source=editors&ust=1621930683235000&usg=AOvVaw1y-hlf8hf0RPvN5hlWEVMX)
4.  [Using sklearn vectorizer to create custom ones, i.e. a vectorizer that does preprocessing and tfidf and other things.](https://www.google.com/url?q=https://towardsdatascience.com/hacking-scikit-learns-vectorizers-9ef26a7170af&sa=D&source=editors&ust=1621930683236000&usg=AOvVaw3cnQTlLZXl3-Hz2fWOOaB_)
5.  [TFIDF - n-gram based top weighted tfidf words](https://www.google.com/url?q=https://stackoverflow.com/questions/25217510/how-to-see-top-n-entries-of-term-document-matrix-after-tfidf-in-scikit-learn&sa=D&source=editors&ust=1621930683236000&usg=AOvVaw06e9-XCsUztE8FUElZ6siT)
6.  [Gensim bi-gram phraser/phrases analyser/converter](https://www.google.com/url?q=https://radimrehurek.com/gensim/models/phrases.html&sa=D&source=editors&ust=1621930683236000&usg=AOvVaw2g-DHFB5Oblcpa3QZ_4-J9)
7.  [Countvectorizer, stemmer, lemmatization code tutorial](https://www.google.com/url?q=https://medium.com/@rnbrown/more-nlp-with-sklearns-countvectorizer-add577a0b8c8&sa=D&source=editors&ust=1621930683237000&usg=AOvVaw3MwmfPVRbGGkXGlL8k7kGG)
8.  [Current 2018 best universal word and sentence embeddings -> elmo](https://www.google.com/url?q=https://medium.com/huggingface/universal-word-sentence-embeddings-ce48ddc8fc3a&sa=D&source=editors&ust=1621930683237000&usg=AOvVaw1gTU-3UrbNv-n7W_jF-8Kp)
9.  [5-part series on word embeddings](https://www.google.com/url?q=http://ruder.io/word-embeddings-1/&sa=D&source=editors&ust=1621930683238000&usg=AOvVaw1zUR0rsuBjfSMNFwMbhguG), [part 2](https://www.google.com/url?q=http://ruder.io/word-embeddings-softmax/index.html&sa=D&source=editors&ust=1621930683238000&usg=AOvVaw04XciTW4Tda4psjUI_nfvG), [3](https://www.google.com/url?q=http://ruder.io/secret-word2vec/index.html&sa=D&source=editors&ust=1621930683239000&usg=AOvVaw1HbHaKlKYanjTyQlvriOTQ), [4 - cross lingual review](https://www.google.com/url?q=http://ruder.io/cross-lingual-embeddings/index.html&sa=D&source=editors&ust=1621930683239000&usg=AOvVaw1BrIBJCUpABu3Dkqjz07xk), [5-future trends](https://www.google.com/url?q=http://ruder.io/word-embeddings-2017/index.html&sa=D&source=editors&ust=1621930683239000&usg=AOvVaw18JMBmGg0_1yhl1DWEEVRp)
10. [Word embedding posts](https://www.google.com/url?q=https://datawarrior.wordpress.com/2016/05/15/word-embedding-algorithms/&sa=D&source=editors&ust=1621930683240000&usg=AOvVaw3W03UCRWdbBAPlkI3-nh6q)

* * *

#### FastText




![](images/image206.png)


