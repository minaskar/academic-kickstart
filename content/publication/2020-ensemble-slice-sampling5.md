+++
abstract = "Slice Sampling has emerged as a powerful Markov Chain Monte Carlo algorithm that adapts to the characteristics of the target distribution with minimal hand-tuning. However, Slice Sampling's performance is highly sensitive to the user-specified initial length scale hyperparameter. Moreover, Slice Sampling generally struggles with poorly scaled or strongly correlated distributions. This paper introduces Ensemble Slice Sampling, a new class of algorithms that bypasses such difficulties by adaptively tuning the length scale. Furthermore, Ensemble Slice Sampling's performance is immune to linear correlations by exploiting an ensemble of parallel walkers. These algorithms are trivial to construct, require no hand-tuning, and can easily be implemented in parallel computing environments. Empirical tests show that Ensemble Slice Sampling can improve efficiency by more than an order of magnitude compared to conventional MCMC methods on highly correlated target distributions such as the Autoregressive Process of Order 1 and the Correlated Funnel distribution. "

authors = ["Minas Karamanis", "Florian Beutler"]
date = "2020-01-19"
image_preview = ""
math = true
publication_types = ["3"] # 2 is Journal paper, 3 is preprint
#publication = "In *Journal of Machine Learning Research*"
#publication_short = "JMLR"
selected = true
title = "Ensemble Slice Sampling"
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/2002.06212.pdf"
url_project = ""
url_slides = ""
url_video = ""
featured = true

#[[url_custom]]
#name = "View Journal Article"
#url = "http://onlinelibrary.wiley.com/doi/10.1002/aur.1301/full"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++