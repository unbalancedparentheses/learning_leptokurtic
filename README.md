# Learning Leptokurtic

A curated collection of resources on fat-tailed distributions, kurtosis, non-ergodic processes, and why Gaussian models fail in real-world systems. Heavily inspired by the work of Nassim Taleb, Mandelbrot, and Ole Peters.

## Not yet reviewed

> These resources were recently found and have not been reviewed yet.

### Taleb (New Work)
- [Statistical Consequences of Fat Tails (3rd Edition) - Taleb (2025)](https://arxiv.org/abs/2001.10488) - Three new chapters plus appendix on maximum entropy distributions
- [Working With Convex Responses: Antifragility From Finance to Oncology - Taleb & West (Entropy, 2023)](https://arxiv.org/abs/2209.14631) - Formalizes antifragility as convex dose-response functions
- [The Regress of Uncertainty and the Forecasting Paradox - Taleb & Cirillo (2025)](https://www.mdpi.com/2227-9091/13/12/247) - Iterated epistemic uncertainty structurally fattens tails

### Cirillo (New Work)
- [Forecasting: Theory and Practice - Petropoulos, Cirillo, et al. (International Journal of Forecasting, 2022)](https://ideas.repec.org/a/eee/intfor/v38y2022i3p705-871.html) - 167-page state-of-the-art forecasting survey including heavy tails sections
- [From Inequality to Extremes and Back - Cirillo & Fontanari (Mathematics, 2025)](https://www.mdpi.com/2227-7390/13/13/2047) - Links extreme-value dependence to Lorenz curves

### Power Laws
- [New Horizon in Statistical Physics of Earthquakes: Dragon-King Theory - Li, Sornette et al. (2024)](https://arxiv.org/abs/2408.10857) - Evidence for dragon-king mechanisms in major seismic events
- [Bubbles for Fama from Sornette - Zhao & Sornette (2022)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3995526) - LPPLS bubble indicator predicts low returns, addressing efficient-markets critique
- [Deep LPPLS: Forecasting Temporal Critical Points - Nielsen, Sornette & Raissi (2024)](https://arxiv.org/abs/2405.12803) - Deep learning + LPPLS for faster, more reliable crash prediction

### Forecasting Under Fat Tails
- [On Single Point Forecasts for Fat-Tailed Variables - Taleb, Bar-Yam & Cirillo (2022)](https://arxiv.org/abs/2007.16096) - Systematic errors of point-forecast methods on multiplicative processes
- [Ergodicity Breaking in Wealth Dynamics - Stojkoski & Karbevski (2022)](https://arxiv.org/abs/2111.12396) - Wealth dynamics are non-ergodic; reallocation changes long-run behavior

### Books (Not yet reviewed)
- [The Fundamentals of Heavy Tails - Nair, Wierman & Zwart (Cambridge, 2022)](https://www.cambridge.org/core/books/fundamentals-of-heavy-tails/3B1A35A6E72551E50E4723A4785044EE) - Rigorous graduate text on why heavy tails emerge and how to estimate them
- [Extreme Value Theory for Time Series - Mikosch & Wintenberger (Springer, 2024)](https://link.springer.com/book/10.1007/978-3-031-59156-3) - 766-page treatment of EVT for dependent time series with power-law tails
- [An Introduction to Ergodicity Economics - Peters & Adamou (LML Press, 2025)](https://ergodicityeconomics.com/an-introduction-to-ergodicity-economics/) - First textbook on ergodicity economics

## Table of Contents

- [Key Insights](#key-insights)
- [People](#people)
- [Articles](#articles)
- [Books](#books)
- [Papers](#papers)

## Key Insights

<details>
<summary><b>Expand to see foundational quotes</b></summary>

> How much will additional data (under such a probability distribution) help increase the stability of the observed mean". The purpose is not entirely statistical: it can equally mean: "How much will adding an additional security into my portfolio allocation increase its stability? - Nassim Taleb

> The rub is that the Gaussian is of limited applicability outside of textbook examples —the type of randomness that prevails in game setups such as coin tosses or, possibly in quantum mechanics. Using it leads to the underestimation of fat tails, to the role of extreme events, and to predictions that underestimate their own errors. For instance, Taleb (2009) showed, using close to 20 million pieces of economic data (most economic variables over a period spanning the past forty years) the following: i) The data have fat tails, meaning that the errors would be dominated by larger deviations than estimated ii) The "fat tailed" nature of the data does not disappear under aggregation, meaning that the sum of the variables remains fat-tailed, and eliminates the hypothesis of convergence to Gaussian thin-tailedness, and iii) The fat-tailedness of the data is impossible to estimate—though we know the process is fat-tailed. Assume we agreed that kurtosis is a measure of the degree of fat-tailedness of the process ( a scaled fourth moment of the distribution). For all variables, kurtosis depends on a very small number of observations —for instance, close to 78% of the total kurtosis of the U.S. stock market for 10,000 observations of data depends on one single observation, implying we can't figure out within the L2 norm the fat-tailedness of the process without a huge measurement error. For these reasons, this Gaussian framework fails us severely in economics.Now the questions that naturally arise would be: What if we used another, supposedly better fitting distribution? Would that lead to proper estimation of the risks in the real world? The answer is, alas, which distribution, and with which parameters? The problem with the "tails" is that they are not tractable and will be subjected to severe measurement errors. Even if we assumed, generously, that we had the right distribution, small errors in calibration of the parameters lead to disproportionately larger and larger effects in the tails (Taleb, 2011). Since these tail events determine a large share of the properties for almost all socio-economic data, we are left in the dark about the most important information. The conclusions are i) to focus on limiting exposures to these tail events, rather than invent distributions tofeel comfortable with them and put people at risk, and ii) limit the use of such probabilistic statements to matters not affected by tail events - Nassim Taleb

> There's a connection between heavy-tailed distributions and non-ergodicity. Actually, they're often two mathematical models of the same observation. Imagine drawing instances from a distribution whose variance doesn't exist and measuring the sample variance. As you keep drawing instances, the sample variance will increase. You, as the observer, may conclude that the "true" variance is infinite. or you may conclude that the true variance is a function of time, not stationary, and that the asymptotic distribution doesn't exist (or at least that that's a reasonable model for the situation). You may conclude the system is not ergodic. - Ole Peters

</details>

## People

- [Joe Norman](https://twitter.com/noraborealiz) - Applied complexity scientist, frequent Taleb collaborator on real-world risk and precautionary principles
- [Nassim Nicholas Taleb](https://www.fooledbyrandomness.com/) - Author of the Incerto series; developed the mathematical framework for fat tails, antifragility, and skin in the game
- [Bert Zwart](https://www.cwi.nl/en/people/bert-zwart/) - CWI researcher specializing in heavy-tailed queueing theory and rare event simulation
- [Michael Gilliland](https://scholar.google.com/citations?user=mfxHB1zxkFIC) - Supply chain forecasting expert; critic of overcomplicated forecasting methods that ignore fat tails
- [Pasquale Cirillo](https://www.pasqualecirillo.eu/) - Statistician working on tail risk, extreme value theory, and war/pandemic casualty modeling with Taleb

## Articles

- [Real life is risk taking - Nassim Taleb](https://medium.com/@nntaleb/real-life-is-risk-taking-ac424efd5fcc) - Essay on why avoiding all risk is itself the riskiest strategy; the difference between fragile and antifragile systems
- [Navigating Our World Like Birds and Bees](https://well.blogs.nytimes.com/2014/01/01/navigating-our-world-like-birds-and-bees/) - How Levy flights (fat-tailed movement patterns) appear across species; connects biology to heavy-tailed distributions
- [Cauchy distribution parameter estimation - John D. Cook](https://www.johndcook.com/blog/cauchy_estimation/) - Practical guide to estimating parameters of the Cauchy distribution, where the mean and variance don't exist

## Books

- [The Fundamentals of Heavy Tails - Jayakrishnan Nair, Adam Wierman & Bert Zwart (Cambridge, 2022)](https://www.cambridge.org/core/books/fundamentals-of-heavy-tails/3B1A35A6E72551E50E4723A4785044EE) - The rigorous graduate textbook on heavy tails: why they emerge, how to detect them, and how to estimate tail probabilities
- [Modelling Extremal Events: for Insurance and Finance - Paul Embrechts, Claudia Kluppelberg & Thomas Mikosch](https://link.springer.com/book/10.1007/978-3-642-33483-2) - The classic reference on extreme value theory applied to insurance and finance; foundational for quantitative risk management
- [The (Mis)Behavior of Markets - Benoit Mandelbrot](https://www.goodreads.com/book/show/665134.The_Mis_Behavior_of_Markets) - Mandelbrot's accessible case against Gaussian finance; introduces fractal market theory and shows why "normal" models undercount crashes
- [Why Stock Markets Crash: Critical Events in Complex Financial Systems - Didier Sornette](https://press.princeton.edu/books/paperback/9780691175959/why-stock-markets-crash) - Sornette's theory of market crashes as critical phase transitions detectable by log-periodic power law signatures (LPPLS)
- [Statistical Consequences of Fat Tails (3rd Edition) - Nassim Taleb](https://arxiv.org/abs/2001.10488) - Taleb's technical magnum opus: what breaks when you move from thin-tailed to fat-tailed distributions — estimators, regression, PCA, portfolio theory, all of it
- [The Brownian Motion: A Rigorous but Gentle Introduction for Economists - Andreas Loffler, Lutz Kruschwitz](https://www.goodreads.com/book/show/47155033-the-brownian-motion) - Accessible treatment of Brownian motion and stochastic processes, useful background before studying where Gaussian assumptions fail

## Papers

- [How Much Data Do You Need? An Operational, Pre-Asymptotic Metric for Fat-tailedness - Nassim Taleb](https://arxiv.org/abs/1802.05495) - Introduces the kappa metric: a practical way to measure how fat-tailed your data is and how much data you'd need for stable estimates
- [On the statistical properties and tail risk of violent conflicts - Pasquale Cirillo, Nassim Nicholas Taleb](https://arxiv.org/abs/1505.04722) - Shows wars follow fat-tailed distributions; the risk of extreme conflict is much higher than standard models suggest
- [The variation of certain speculative prices - Benoit Mandelbrot](https://web.williams.edu/Mathematics/sjmiller/public_html/341Fa09/econ/Mandelbroit_VariationCertainSpeculativePrices.pdf) - The 1963 paper that started it all: Mandelbrot shows cotton prices follow Levy-stable distributions, not Gaussian ones
- [The Future Has Thicker Tails than the Past: Model Error As Branching Counterfactuals - Nassim Taleb](https://arxiv.org/abs/1209.2298) - Why forecasting models systematically underestimate tail risk: each layer of uncertainty compounds into fatter tails
- [How We Tend To Overestimate Powerlaw Tail Exponents - Nassim Taleb](https://arxiv.org/abs/1210.1966) - Shows standard estimation methods (Hill, MLE) produce biased tail exponents, making distributions appear thinner-tailed than they are
- [Where Do Thin Tails Come From? - Nassim Taleb](https://arxiv.org/abs/1307.6695) - Proves thin tails require very specific generative conditions; in practice, most real processes are fat-tailed by default
- [The Skin In The Game Heuristic for Protection Against Tail Events - Nassim Taleb](https://arxiv.org/abs/1308.0958) - Formalizes why decision makers must bear the consequences of their tail risks; without skin in the game, hidden risks accumulate
- [Stochastic Tail Exponent For Asymmetric Power Laws - Nassim Taleb](https://arxiv.org/abs/1609.02369) - Technical framework for handling asymmetric fat tails where left and right tails have different exponents
- [Branching epistemic uncertainty and thickness of tails - Nassim Taleb, Pasquale Cirillo](https://arxiv.org/abs/1912.00277) - Shows that uncertainty about your uncertainty (meta-probability) makes tails thicker; the precursor to the Forecasting Paradox paper
- [Statistical and Machine Learning forecasting methods: Concerns and ways forward - Makridakis, Spiliotis, Assimakopoulos](https://journals.plos.org/plosone/article/comments?id=10.1371/journal.pone.0194889) - M4 competition results showing simple methods often beat complex ML models; raises questions about overfitting in fat-tailed domains
