+++
title = "Don’t Walk, Skip! Online Learning of Multi-scale Network Embeddings"
date = "2017-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Bryan Perozzi", "Vivek Kulkarni", "Haochen Chen", "Steven Skiena"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Advances in Social Networks Analysis and Mining (ASONAM), 2017 "
publication_short = "ASONAM" 

# Abstract and optional shortened version.
abstract = "We present Walklets, a novel approach for learning multiscale representations of vertices in a network. In contrast to previous works, these representations explicitly encode multiscale vertex relationships in a way that is analytically derivable. Walklets generates these multiscale relationships by subsampling short random walks on the vertices of a graph. By `skipping' over steps in each random walk, our method generates a corpus of vertex pairs which are reachable via paths of a fixed length. This corpus can then be used to learn a series of latent representations, each of which captures successively higher order relationships from the adjacency matrix. We demonstrate the efficacy of Walklets's latent representations on several multi-label network classification tasks for social networks such as BlogCatalog, DBLP, Flickr, and YouTube. Our results show that Walklets outperforms new methods based on neural matrix factorization. Specifically, we outperform DeepWalk by up to 10% and LINE by 58% Micro-F1 on challenging multi-label classification tasks. Finally, Walklets is an online algorithm, and can easily scale to graphs with millions of vertices and edges. "
abstract_short = "We present Walklets, a novel approach for learning multiscale representations of vertices in a network. In contrast to previous works, these representations explicitly encode multiscale vertex relationships in a way that is analytically derivable. Walklets generates these multiscale relationships by subsampling short random walks on the vertices of a graph. By `skipping' over steps in each random walk, our method generates a corpus of vertex pairs which are reachable via paths of a fixed length. This corpus can then be used to learn a series of latent representations, each of which captures successively higher order relationships from the adjacency matrix. We demonstrate the efficacy of Walklets's latent representations on several multi-label network classification tasks for social networks such as BlogCatalog, DBLP, Flickr, and YouTube. Our results show that Walklets outperforms new methods based on neural matrix factorization. Specifically, we outperform DeepWalk by up to 10% and LINE by 58% Micro-F1 on challenging multi-label classification tasks. Finally, Walklets is an online algorithm, and can easily scale to graphs with millions of vertices and edges."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["language variation"]

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1605.02115.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "ln.jpg"
caption = ""

+++
