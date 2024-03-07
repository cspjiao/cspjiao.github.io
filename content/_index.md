---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news
    content:
      title: What's New
      text: |-
          + <font color=orange>**[Award]**</font> Congratulations to Liu Huan and Chen Hongjiang on successfully passing the PhD interview（01/2024）
          + <font color=red>**[Paper]**</font>  Congratulations to Zian Zhou for his article ["Role-oriented representation learning via fusioning local and higher-order feature"](https://ieeexplore.ieee.org/abstract/document/10409567/) being accepted by tbd（01/2024）
          + <font color=orange>**[Award]**</font> Congratulations to Chen Hongqian on winning the [Huawei Scholarship](https://grs.hdu.edu.cn/2023/1228/c1736a255369/page.htm)（12/2023）
          + <font color=red>**[Paper]**</font> Congratulations to Chen Hongqian for her article ["Enhancing Multi-scale Diffusion Prediction via Sequential Hypergraphs and Adversarial Learning"]() being accepted by AAAI（10/2023）
          + <font color=orange>**[Award]**</font> Congratulations to Liu Huan on winning the National Scholarship（10/2023）
          + <font color=red>**[Paper]**</font>  Congratulations to Ming Du for his article ["Role-oriented representation learning via fusioning local and higher-order feature"](https://www.sciencedirect.com/science/article/pii/S0950705123008651) being accepted by kbs（10/2023）
          + <font color=red>**[Paper]**</font>  Congratulations to Hongjiang Chen for his article ["Temporal Graph Representation Learning with Adaptive Augmentation Contrastive"](https://link.springer.com/chapter/10.1007/978-3-031-43415-0_40) being accepted by ecml（09/2023）
          + <font color=blue>（Ongoing update...)</font>
         
      
    design:
      columns: '2'

  - block: collection
    id: featured
    content:
      title: Featured Publications
      count: 3
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
       # - block: collection
  #   id: posts
  #   content:
  #     title: Feature Publicaions
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'

  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  # - block: markdown
  #   id: awards
  #   content:
  #     title: Awards and Grants
  #     text: |-

  #   design:
  #     columns: '2'

  - block: markdown
    id: service
    content:
      title: Professional Services
      text: |-
          ### Hosting and participating in projects
            + Research on interpretable deep generation models and algorithms for dynamic complex networks
            + Research on community detection and evolution of large-scale dynamic complex networks driven by node roles
            + Research on cross-modal semantic understanding and knowledge reasoning under brain-like characteristics
            + Research on intelligent auxiliary technology of administrative law enforcement based on graph mining
            + Research on basic theory and key algorithm of cross-modal intelligent computing
            + Knowledge representation and computation for multimodal information networks
            + XXXXX Measurement system
            + Research on the hierarchical linkage mechanical modeling of multi-scale information propagation in cyberspace
            + Research on large-scale network community discovery based on Markov random fields
            + Research on accurate semantic community discovery for large-scale and complex networks
            + Urban transmission and prediction models of highly infectious diseases Construction method
            + Specific human-event correlation open source clue mining and "people in the loop" visual research and judgment platform
            + The key technology of role identification in large-scale covert complex network
            + Network event detection
  
           ###   Program Committee
            + AAAI Conference on Artificial Intelligence（AAAI-21-23）
            + International Joint Conference on Artificial Intelligence（IJCAI-24）
            + Association for Computational Linguistics（ACL-22-23）
            +  IEEE International Conference on Data Mining （ICDM-22）
            + ACM Multimedia Conference（MM-23）
            + The Web Conference（WWW-23-24）
            + European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases（ECMLPKDD-23）

           ### Journal Reviewer

            + IEEE Transactions on Pattern Analysis and Machine Intelligence 
            + IEEE Transactions on Knowledge and Data Engineering 
            + IEEE Transactions on Fuzzy Systems 
            + IEEE Transactions on Cybernetics 
            + IEEE Transactions on Neural Networks and Learning Systems 
            + IEEE Transactions on Computational Social Systems 
            + IEEE Transactions on Big Data
            + Physica A: Statistical Mechanics and its Applications
            + Information Sciences
            + Knowledge-Based Systems
            + Neurocomputing
            + 中文信息学报
            + 计算机应用


    design:
      columns: '2'


  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: lecturer
          company: Tianjing University
          company_url: ''
          company_logo: ''
          location: Chinese
          date_start: '2018-09-01'
          date_end: '2021-11-01'
          description: Taught computer science.
        - title: Distinguished Professor
          company: Hangzhou Dianzi University
          company_url: ''
          company_logo: ''
          location: Chinese
          date_start: '2021-12-01'
          date_end: ''
          description: |2-
              Research include:

              * Graph neural
              * Time series
              * Representation learning

    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: '2024-01-01'
          date_start: '2021-01-25'
          description: 'Facing the semantic complexity of graph-structured data, the applicant focuses on the challenges of diverse node types, diverse and sparse semantic information, complex topological attribute interaction and diverse generation mechanisms in complex graphs, and effectively breaks through the difficulties of complex graph attribute semantic diversity and topological attribute interaction. Promoted the generative integration of probabilistic graph model and deep learning method in node and sublayer surface, published 12 papers in AAAI, IJCAI, TKDE, TIST, WWW and other journal conferences as the first or corresponding author. And published the review paper "A Survey of Community Detection Approaches: From Statistical Modeling to Deep Learning "(TKDE 2023), cited more than 230 times by Google academics. He applied theoretical methods to social recommendation and knowledge graph, and his related results were published in SIGIR2019, SIGIR2022, WWW2023, and won the NLPCC2019 Outstanding Paper Award. Applied to Internet edge computing, related results are published in (TNSM 2021) and (IoT-J 2021), paper "EEDTO: an energy-efficient dynamic task offloading algorithm for blockchain-enabled IoT-edge-cloud orchestrated  "computing" is included in ESI database as a highly cited paper - the number of citations has placed it in the top 1% of the corresponding academic field (more than 180 Google academic citations).'
          icon: ''
          organization: ''
          title: Topological semantic fusion of complex graphs
          url: ''
        - certificate_url: ''
          date_end: '2024-01-01'
          date_start: '2021-01-25'
          description: 'Focusing on the complexity of links in graph-structured data, the applicant has systematically broken through the problems of complex local links and difficult acquisition of common features by focusing on challenges such as complex local low-order dependencies, complex multi-order interactions, complex global dependencies and diverse generation mechanisms in complex graphs, and has innovatively built a system of structural similarity modeling, representation, mining and generation methods. He promoted the robust representation of complex link patterns for multi-order interactions in graph-structured data, task mining for heterogamy guidance and fusion generation of high-low order interactions, and published 12 papers in IEEE TCYB, TBD, IJCAI, AAAI, Information Sciences, ICDM, CIKM and other journal conferences. As the first author, he published a review paper "Review of Role-oriented Network Representation Learning" in the Journal of Computer Science, and was invited to give lectures on ICDM (CCF-B class) and DSAA (CCF-C class). Based on the research results, the applicant proposed "Threats and Countermeasures of International Biohackers to Biosecurity" (Expert advice, Ministry of Education, March 2021), pointing out how to use artificial intelligence, complex network analysis and other technologies to address the challenges brought by biohacking technology in the context of cyber security and biosecurity.'
          icon: ''
          organization: ''
          title: Link pattern learning method for complex graphs
          url: ''
        - certificate_url: ''
          date_end: '2024-01-01'
          date_start: '2021-01-25'
          description: 'Oriented towards the evolutionary complexity of graph-structured data, the applicant focuses on the challenges existing in complex graphs such as variable node evolution behavior, complex link prediction model, unknown topological evolution mechanism, multi-level dependence of global evolution and cross-scale topological evolution coupling, and innovatively breaks through the joint generation problem of micro, mesoscopic and macro coupling interaction of graph-structured data. It has formed a topology multi-scale mining and generation method system, promoted the evolutionary behavior analysis of microscopic nodes, mesoscopic subgraphs and macro snapshots in graph structure data, the generation and modeling of multi-scale topological structure coupling, and the deep mining of link prediction, subgraph evolution and anomaly discovery. He has published 10 papers as the first or corresponding author in TKDE, Computer Research and Development, TCYB, TNNLS and other related journals. Based on the proposed dynamic graph theory and method, the applicant and collaborators carried out applications in public opinion tracking and virus tracing during the novel coronavirus epidemic, provided a lot of high-value information and suggestions for relevant departments, and obtained a letter of thanks from the Ministry of Foreign Affairs of the People’s Republic of China (Arms Control Letter No. 218, 2020). In addition, the "Proposal on the Development of Tianjin Intelligent Security Industry" proposed by the applicant was selected by the Tianjin Education Committee as the first prize of 2018-2019 Tianjin University Think Tank Excellent Decision-making Consulting Research results.'
          icon: ''
          organization: ''
          title: Complex graph evolution behavior mining method
          url: ''
    design:
      columns: '2'
 
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  
  # - block: collection
  #   id: teaching
  #   content:
  #     title: Teaching
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: pjiao@hdu.edu.cn
      address:
        street: No. 280-300 Xuelin Street
        city: HangZhou
        region: Qiantang District
        postcode: '310018'
        country: Chinese
        country_code: CN
      directions: Hangzhou Dianzi University science hall 708
      office_hours:
        - 'Saturday 9:00 to 21:00'
        - 'Sunday &nbsp;&nbsp;&nbsp;9:00 to 21:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '120.349512'
        longitude: '30.320546'  
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
