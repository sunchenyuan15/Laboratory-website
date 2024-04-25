+++
abstract = "Heterogeneous graphs (HGs) contain many nodes and their interaction relationships, which can model complex systems and provide rich semantic and structural information for task execution. Among these, HG representation stands as the fundamental and pivotal component. Existing HG representation methods primarily employ graph neural networks to acquire the semantics of nodes along various meta-paths and fuse them to represent the nodes. The most prevalent HG representation methods encompass two steps: semantic information extraction within meta-paths and semantic fusion between meta-paths. However, these methods overlooked the consideration of node heterogeneity within meta-paths and the simultaneous semantic correlation between meta-paths. Specifically, node heterogeneity within meta-paths signifies that the meta-path-based neighbors do not consistently contain information that positively influences the target node, and the semantic correlation between meta-paths indicates that different meta-path spaces are not entirely independent. Disregarding either of these issues leads to the propagation of irrelevant or redundant information and potential disruption of HG embedding. Consequently, in this study, we propose the HBHG, which is a hierarchical bottleneck for heterogeneous graph representation. HBHG primarily employs the information bottleneck (IB) as a guiding principle, constraining the propagation of irrelevant information within and between meta-paths while preserving relevant information. The central concept of the IB revolves around viewing model learning as the preservation of relevant information and compression of irrelevant information, accomplished by minimizing the dependency between input and hidden features through mutual information (MI) and maximizing the dependency between hidden features and ground-truth. Considering the complexity associated with MI estimation, this paper introduces a novel dependency index, namely the Hilbert-Schmidt independence criterion (HSIC), which offers ease of calculation. Specifically, HBHG comprises two primary components: a semantic bottleneck within meta-paths and a semantic bottleneck between meta-paths. The semantic bottleneck within meta-paths relies primarily on the HSIC-based limitations of dependencies at different layers of the graph neural network on various meta-paths, thereby maximizing the extraction of information relevant to the target node from neighboring nodes. The semantic bottleneck between meta-paths enables flexible extraction and fusion of semantic information based on downstream tasks, achieved by managing the trade-off of dependencies with HSIC between different meta-path semantic spaces. In summary, the proposed HBHG integrates hierarchical bottleneck constraints within and between meta-paths. This integration serves to maximize the aggregation of relevant information while effectively compressing irrelevant information, thereby enhancing the quality of heterogeneous graph embedding. The effectiveness of HBHG was validated through performance and ablation experiments conducted on multiple datasets."
abstract_short = "Short version of abstract."
date = "2024-02-01"
image = ""
image_preview = ""
math = false
publication = "Information Sciences"
publication_short = ""
selected = false
title = "Hierarchical bottleneck for heterogeneous graph representation"
url_code = "//github.com"
url_dataset = ""
url_pdf = "https://www.sciencedirect.com/science/article/abs/pii/S0020025524003359"
url_slides = ""
url_video = ""

[[authors]]
    name = "Yunfei He"
    is_member = true
[[authors]]
    name = "Li Meng"
    is_member = true
[[authors]]
    name = "Jian Ma"
    is_member = true
[[authors]]
    name = "Yiwen Zhang"
    is_member = true
[[authors]]
    name = "Qun Wu"
    is_member = true
[[authors]]
    name = "Weiping Ding"
    is_member = true
[[authors]]
    name = "Fei Yang"
    is_member = true
+++


<!-- You can add information in $\LaTeX$ and *Markdown* here. -->
