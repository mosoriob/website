+++
title = "Storage Balancing in P2P Based Distributed RDF Data Stores"

# Date first published.
date = "2017-07-29"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Osorio Maximiliano", "Buil-Aranda Carlos"]

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
publication = "Workshop on Decentralizing the Semantic Web 2017 co-located with 16th International Semantic Web Conference "
publication_short = "In *DeSemWeb@ISWC*"

# Abstract and optional shortened version.
abstract = "Centralized RDF repositories have been designed to support RDF data storage and retrieval. However, they suffer from the traditional limitations of centralized approaches which are scalability and fault tolerance. Peer to Peer (P2P) networks can provide the scalability, fault-tolerance and robustness, features that the current solutions to local RDF storage do not provide which are needed by the existing Semantic Web applications. A common strategy from state-of-the-art P2P-RDF data stores is to store triples at three locations so each triple can be found using a look-up by subject, predicate, or object identifier. One major issue of this strategy is the lack of load-balancing, since occurrences in triples are not uniformly distributed. Consequently, this issue leads an unbalance query processing load distribution and unfair storage load in the network. To solve this problem caused by load imbalance, we propose new scheme to split the data in the stressed nodes which is based in evenly distributing excess of data across neighboring nodes providing a Prefix Hash Table for fast accessing to such data. We provide an empirical evaluation of our novel approach and compare with other state of the art systems for storage balancing showing the feasibility of our approach"

abstract_short = "We propose a new scheme to split the data in the stressed nodes for P2P-RDF data stores"
url_pdf = "pdf/loadbalancing.pdf"

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true


+++