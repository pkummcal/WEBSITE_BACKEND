+++
abstract = "The complexity of hardware implementation of the third generation audio video coding standard (AVS3) has been significantly improved due to more flexible intra prediction methods. In this paper, an efficient intra mode decision algorithm for parallel hardware architecture of the AVS3 intra encoder is presented. The key idea is to process coding units (CUs) in parallel, including intra prediction and estimating Rate- Distortion (RD) cost for mode decision. Specially, regression tree- based fast algorithm is adopted to decide several preselected modes, together with sufficient consideration into the tradeoff between RD-cost and complexity of prediction engines. In order to obtain the optimal intra mode and improve throughput, prediction module and Hadamard-cost module are devised to process all the candidate modes in parallel. To the best of our knowledge, this is the first parallel hardware architecture of AVS3 intra prediction. Compared with the HPM-6.0 reference software, the proposed algorithm leads to a reduction of 78% in computation workload, while the average BD-PSNR is -0.40 dB for the common test videos. When implemented on the Vertex UltraScale VU440 targeting at 300MHz, the proposed design can support the real-time encoding of 4K videos at 30fps."
date = "2021-01-30T16:37:31+02:00"
image = ""
image_preview = ""
math = false
publication = "IEEE International Symposium on Circuits and Systems"
publication_short = "ISCAS"
selected = false
title = "Efficient Fast Algorithm and Parallel Hardware Architecture for Intra Prediction of AVS3"
url_code = ""
url_dataset = ""
url_pdf = "https://ieeexplore.ieee.org/document/9401121"
url_project = ""
url_slides = ""
url_video = ""
sort_position = 13

[[authors]]
    name = "Zhanyuan Cai"
    is_member = true

[[authors]]
    name = "Wei Gao"
    is_member = true

+++



