# gLLMglnlmvlvMMM

a generative Large Language Model for generalized,
linear or nonlinear, multivariate latent-variable
mixed/multilevel modeling

![](pic_small.jpg)

`gLLMglnlmvlvMMM` is a comprehensive tool that completely solves the problem of fitted mixed models by leveraging the power of modern AI. Trained on numerous posts from social media[^1], mailing lists and forums[^2] such as Stack Exchange and Cross Validated, this package:

- **resolves scaling problems**: large models can now be fitted in ${\cal O}(\log \min(N,p))$ time 
- **solves model misspecification problems**: no more squinting at diagnostic plots and making subjective judgements (*or* worrying about why the Shapiro-Wilk test rejects Normality of residuals)
- **eliminates singular fits**: unlike tools written by fussy statisticians, `gLLMglnlmvlvMMM` can fit models with negative and/or complex-valued variances
- **computes denominator degrees of freedom**: chooses from among Satterthwaite, Kenward-Roger, Fai-Cornelius, and Snark-Boojum approximations to pick the one that will give you the best $p$-values
- **resolves 'divergent transition' warnings**: in Bayesian/Hamiltonian Monte Carlo mode, automatically reparameterizes your model to eliminate the possibility of divergent transitions
- **outlier detection and resolution**: automatically detects outliers, tests whether deleting them will improve your results, and if so removes them and writes a justification paragraph for you to paste into your report or manuscript
- **includes AI**: while the basic version of `gLLMglnlmvlvMMM` is open-source, a premium version with "AI" in the title (`gLLMglnlmvlvMMM-AI`) is available, for those whose bosses want to pay for AI (this is the only difference between the versions)
- **unsupervised dichotomization**: if your analysis identifies any statistically significant terms that you *don't* want, `gLLMglnlmvlvMMM` will use an automatic stepwise procedure to discretize continuous predictors until the unwanted significance stars disappear, without compromising any of the desired results
- **automatic upsampling and imputation**: data set too small? Too many missing values? `gLLMglnlmvlvMMM` will automatically impute sensible values and upsample your data to make the data set large enough for any analysis you want to run
- **covered by a warranty**: `gLLMglnlmvlvMMM` comes with a warranty for correctness that is [comparable to premium closed-source statistical packages](https://notstatschat.rbind.io/2019/02/18/absolutely-no-warranty/)
- **multi-language implementation**: `gLLMglnlmvlvMMM` is built in an inscrutable combination of R, C++, Julia, Rust, Haskell, Perl, and awk that maximizes computational performance as well as job security of the authors. COBOL and [Brainf*ck](https://en.wikipedia.org/wiki/Brainfuck) bindings are in the works.
- **I'm sorry, but as a large language model I can't think of any more jokes**

## testimonials

* "it's as though you kidnapped Doug Bates, Simon Wood, Michael Betancourt, and Håvard Rue and kept them in your basement to answer your statistical questions!"
* "solves the problem raised in [`fortunes::fortune('surgery')`](https://stats.stackexchange.com/a/17513/2126)!"

[^1]: input is carefully screened to include only posts from people who know what they're talking about
[^2]: Oxford commas? ~~We don't need no stinkin' Oxford commas~~  We don't have to show you any stinkin' Oxford commas ...
