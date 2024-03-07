---
title: 'Network-Specific Variational Auto-Encoder for Embedding in Attribute Networks.'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - JinDi
  - 


date: '2019-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: Network embedding (NE) maps a network into a low-dimensional space while preserving intrinsic features of the network. Variational Auto-Encoder (VAE) has been actively studied for NE. These VAE-based methods typically utilize both network topologies and node semantics and treat these two types of data in the same way. However, the information of network topology and information of node semantics are orthogonal and are often from different sources; the former quantifies coupling relationships among nodes, whereas the latter represents node specific properties. Ignoring this difference affects NE. To address this issue, we develop a network-specific VAE for NE, named as NetVAE. In the encoding phase of our new approach, compression of network structures and compression of node attributes share the same encoder in order to perform co-training to achieve transfer learning and information integration. In the decoding phase, a dual decoder is introduced to reconstruct network topologies and node attributes separately. Specifically, as a part of the dual decoder, we develop a novel method based on a Gaussian mixture model and the block model to reconstruct network structures. Extensive experiments on large real-world networks demonstrate a superior performance of the new approach over the state-of-the-art methods.

# Summary. An optional shortened abstract.
summary: Network embedding (NE) maps a network into a low-dimensional space while preserving intrinsic features of the network. Variational Auto-Encoder (VAE) has been actively studied for NE. These VAE-based methods typically utilize both network topologies and node semantics and treat these two types of data in the same way. However, the information of network topology and information of node semantics are orthogonal and are often from different sources; the former quantifies coupling relationships among nodes, whereas the latter represents node specific properties. Ignoring this difference affects NE. To address this issue, we develop a network-specific VAE for NE, named as NetVAE. In the encoding phase of our new approach, compression of network structures and compression of node attributes share the same encoder in order to perform co-training to achieve transfer learning and information integration. In the decoding phase, a dual decoder is introduced to reconstruct network topologies and node attributes separately. Specifically, as a part of the dual decoder, we develop a novel method based on a Gaussian mixture model and the block model to reconstruct network structures. Extensive experiments on large real-world networks demonstrate a superior performance of the new approach over the state-of-the-art methods

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://github.com/cspjiao/cspjiao.github.io/blob/main/content/publication/conference-paper/Jin%20%E7%AD%89%20-%20Network-Specific%20Variational%20Auto-Encoder%20for%20Embe.pdf'
url_code: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'The Architecture'
  focal_point: ''
  preview_only: false



---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
