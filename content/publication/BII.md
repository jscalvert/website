+++
abstract = "Algorithm–based clinical decision support (CDS) systems associate patient-derived health data with outcomes of interest, such as in-hospital mortality. However, the quality of such associations often depends on the availability of site-specific training data. Without sufficient quantities of data, the underlying statistical apparatus cannot differentiate useful patterns from noise and, as a result, may underperform. This initial training data burden limits the widespread, out-of-the-box, use of machine learning–based risk scoring systems. In this study, we implement a statistical transfer learning technique, which uses a large “source” data set to drastically reduce the amount of data needed to perform well on a “target” site for which training data are scarce. We test this transfer technique with AutoTriage, a mortality prediction algorithm, on patient charts from the Beth Israel Deaconess Medical Center (the source) and a population of 48249 adult inpatients from University of California San Francisco Medical Center (the target institution). We find that the amount of training data required to surpass 0.80 area under the receiver operating characteristic (AUROC) on the target set decreases from more than 4000 patients to fewer than 220. This performance is superior to the Modified Early Warning Score (AUROC: 0.76) and corresponds to a decrease in clinical data collection time from approximately 6months to less than 10days. Our results highlight the usefulness of transfer learning in the specialization of CDS systems to new hospital sites, without requiring expensive and time-consuming data collection efforts."
abstract_short = "We develop a mortality prediction algorithm which outperforms existing methods, and apply transfer learning to overcome the barrier of data scarcity during site implementation."
authors = ["Thomas Desautels","Jacob Calvert","Jana Hoffman","Qingqing Mao","Melissa Jay","Grant Fletcher","Christopher Barton","Uli Chettipally","Yaniv Kerem","Ritankar Das"]
date = "2017-05-10"
image = ""
image_preview = ""
math = false
publication = "In *Biomedical Informatics Insights*"
title = "Using transfer learning for improved mortality prediction in a data-scarce hospital setting"
url_code = ""
selected = true
publication_types = ["2"]
url_dataset = ""
url_pdf = "pdf/BII.pdf"
url_project = ""
url_slides = ""
url_video = ""
+++