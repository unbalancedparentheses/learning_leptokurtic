# Leptokurtic and Forecasting World

A curated collection of resources on fat-tailed distributions, kurtosis, non-ergodic processes, and why Gaussian models fail in real-world systems. Heavily inspired by the work of Nassim Taleb, Mandelbrot, and Ole Peters.

# Not yet reviewed

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

### Books
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

# People
- Joe Norman
- Nassim Nicholas Taleb
- Bert Zwart
- [Michael Gilliland](https://scholar.google.com/citations?user=mfxHB1zxkFIC)
- [Pasquale Cirillo](https://www.pasqualecirillo.eu/)


# Articles

- [Real life is risk taking - Nassim Taleb](https://medium.com/@nntaleb/real-life-is-risk-taking-ac424efd5fcc)
- [Navigating Our World Like Birds and Bees](https://well.blogs.nytimes.com/2014/01/01/navigating-our-world-like-birds-and-bees/)
- [Cauchy distribution parameter estimation - John D. Cook](https://www.johndcook.com/blog/cauchy_estimation/)

# Books

- The Fundamentals of Heavy-Tails by Jayakrishnan Nair, Adam Wierman, and Bert Zwart 
- Modelling Extremal Events: for Insurance and Finance (Stochastic Modelling and Applied Probability - Paul Embrechts, Thomas Mikosch
- The (Mis)Behavior of Markets - Benoit Mandelbrot
- Why Stock Markets Crash: Critical Events in Complex Financial Systems - Didier Sornette
- Statistical consequences of fat tails - Nassim Taleb
- [The Brownian Motion: A Rigorous but Gentle Introduction for Economists - Andreas Löffler, Lutz Kruschwitz](https://www.goodreads.com/book/show/47155033-the-brownian-motion)

# Papers

- [How Much Data Do You Need? An Operational, Pre-Asymptotic Metric for Fat-tailedness - Nassim Taleb](https://arxiv.org/abs/1802.05495)
- [On the statistical properties and tail risk of violent conflicts - Pasquale Cirillo, Nassim Nicholas Taleb](https://arxiv.org/abs/1505.04722)
- [The variation of certain speculative prices - Benoit Mandelbrot](web.williams.edu/Mathematics/sjmiller/public_html/341Fa09/econ/Mandelbroit_VariationCertainSpeculativePrices.pdf)
- [The Future Has Thicker Tails than the Past: Model Error As Branching Counterfactuals - Nassim Taleb](https://arxiv.org/abs/1209.2298)
- [How We Tend To Overestimate Powerlaw Tail Exponents - Nassim Taleb](https://arxiv.org/abs/1210.1966)
- [Where Do Thin Tails Come From? - Nassim Taleb](https://arxiv.org/abs/1307.6695)
- [The Skin In The Game Heuristic for Protection Against Tail Events - Nassim Taleb](https://arxiv.org/abs/1308.0958)
- [Stochastic Tail Exponent For Asymmetric Power Laws - Nassim Taleb](https://arxiv.org/abs/1609.02369)
- [Branching epistemic uncertainty and thickness of tails - Nassim Taleb, Pasquale Cirillo](https://arxiv.org/abs/1912.00277)
- [Statistical and Machine Learning forecasting methods: Concerns and ways forward](https://journals.plos.org/plosone/article/comments?id=10.1371/journal.pone.0194889)
