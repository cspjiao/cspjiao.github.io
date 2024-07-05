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
                + <font color=red>**[Paper]**</font>  Paper ["Physical Process Guided Graph Neural Networks for Anomaly Detection in CPSs"]() has has been accepted to the AI4TS Workshop@IJCAI 2024（06/2024)
                + <font color=red>**[Paper]**</font>  Paper ["Disentangled Representation Learning for Structural Role Discovery"]() has been finalized and posted to the "Early Access" area on IEEE Xplore（06/2024)
                + <font color=red>**[Paper]**</font>  Congratulations to Ying Jiang for his article [" Graph Contrastive Learning for Source Localization in Social Networks"]() has been accepted to Information Sciences（06/2024)
                + <font color=red>**[Paper]**</font>  Congratulations to Xinxun Zhang for his article ["A Deep Contrastive Framework for Unsupervised Temporal Link Prediction in Dynamic Networks"]() has been accepted to Information Sciences（03/2024)
                + <font color=red>**[Paper]**</font>  Congratulations to Hongjiang Chen for his article ["Contrastive Representation Learning on Dynamic Networks"]() has been accepted to NN（03/2024)
                + <font color=red>**[Paper]**</font>  Congratulations to Xinxun Zhang for his article ["VGGM: Variational Graph Gaussian Mixture Model for Unsupervised Change Point Detection in Dynamic Networks"]() has been accepted to TIFS（03/2024)
                + <font color=red>**[Paper]**</font>  Congratulations to Yuanqi Liu for her article ["CINA:Curvature-based Integrated Network Alignment with Hypergraph"]() has been accepted to ICDE（03/2024)
                + <font color=orange>**[Award]**</font> Congratulations to  Huan Liu and Hongjiang Chen on successfully passing the PhD interview（01/2024）
                + <font color=red>**[Paper]**</font>  Congratulations to Zian Zhou for his article ["Fine-tuned Personality Federated Learning for Graph Data"](https://ieeexplore.ieee.org/abstract/document/10409567/) has been accpetd to TBD（01/2024）
                + <font color=red>**[Paper]**</font> Congratulations to  Hongqian Chen for her article ["Enhancing Multi-scale Diffusion Prediction via Sequential Hypergraphs and Adversarial Learning"]() has been accpetd to AAAI（10/2023）
                + <font color=orange>**[Award]**</font> Congratulations to Huan Liu on winning the National Scholarship（10/2023）
                + <font color=red>**[Paper]**</font>  Congratulations to Ming Du for his article ["Role-oriented representation learning via fusioning local and higher-order feature"](https://www.sciencedirect.com/science/article/pii/S0950705123008651) has been accpetd to KBS（10/2023）
                + <font color=red>**[Paper]**</font>  Congratulations to Hongjiang Chen for his article ["Temporal Graph Representation Learning with Adaptive Augmentation Contrastive"](https://link.springer.com/chapter/10.1007/978-3-031-43415-0_40) has been accpetd to ECML（09/2023）
                + <font color=red>**[Paper]**</font>  Congratulations to Huan Liu for his article ["Globally Enhanced Heterogeneous Temporal Graph Neural Networks Based on Contrastive Learning"](https://www.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2023&filename=JFYZ202308017&uniplatform=OVERSEA&v=oI2GAKN1zdQCikEIR5ya_hbbPxPygrFNnPyfSID4f9Vut344MI0WZSdfone_md-X) has been accpetd to [Journal of Computer Research and Development](https://www.cnki.net/kns/Navi?DBCode=CJFD&BaseID=JFYZ)（08/2023）
                + <font color=red>**[Paper]**</font>  Congratulations to Yifan Lu for his article ["Neighborhood overlap-aware heterogeneous hypergraph neural network for link prediction"](https://www.sciencedirect.com/science/article/abs/pii/S0031320323005162) has been accpetd to Pattern Recognition（07/2023）
         
      
    design:
      columns: '2'

  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     count: 2
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card

  - block: collection
    id: publications
    content:

      title: Selected Publications
      count: 15
      text: |-
        {{% callout note %}}
        More on [Google Scholar](https://scholar.google.com/citations?hl=zh-CN&user=HaNhbi4AAAAJ).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  # - block: markdown
  #   id: teaching
  #   content:
  #     title: Teaching
  #     text: |-
  #         +  Spring 2024 : Artificial Intelligence and machine learning <font color=gray>[undergraduate students]</font>
  #         +  Spring 2024 : Fundamentals and Frontiers of network science <font color=gray>[graduated students]</font>
         
  #   design:
  #     columns: '2'

#   - block: markdown
#     id: team
#     content:
#       # title: Team
#       text: 
#          '<!DOCTYPE html>
# <html lang="en">
# <head>
#     <meta charset="UTF-8">
#     <meta name="viewport" content="width=device-width, initial-scale=1.0">
#     <title>Team Information</title>
#     <style>
#         body {
#             font-family: Arial, sans-serif;
#             margin: 0;
#             padding: 0;
#         }
#         .section {
#             padding-bottom: 50px;
#             text-align: center;
#             margin: 0 auto;
#             display: flex; /* 将 .section 设置为 Flex 容器 */
#             flex-direction: column; /* 设置主轴方向为垂直方向 */
#             align-items: center; /* 在交叉轴上居中对齐 */
#             max-width: 800px;
#         }
#         .title {
#             font-size: 28px;
#             margin-bottom: 20px;
#         }
#         .team-members {
#             display: flex;
#             flex-wrap: wrap; /* 允许内容换行 */
#             justify-content: center; /* 水平居中对齐 */
#             gap: 10px;
#         }
#         .team-member {
#             text-align: center;
#             margin: 10px;
#             width: calc(20% - 10px); /* 固定每个子元素块的宽度为20% */
#             flex-grow: 1; /* 禁止子元素块根据可用空间伸展 */
#             max-width: 130px; /* 设置最大宽度以保持布局美观 */
#         }
#         .team-member img {
#             border-radius: 50%;
#             width: 120px;
#             height: 120px;
#             margin: 0 auto;
#         }
#         .name {
#             font-size: 18px;
#             color: rgb(0, 150, 231);
#             margin-bottom: 2px;
#         }
#         .position {
#             font-size: 16px;
#             color: gray;
#         }
#     </style>
# </head>
# <body>
#     <div class="section">
#         <div class="title">Team Leader</div>
#         <div class="team-member">
#             <img src="authors/admin/avatar.jpg" alt="Pengfei Jiao">
#             <div class="name">Pengfei Jiao</div>
#             <div class="position">Team Leader</div>
#         </div>
#     </div>
#     <div class="section">
#         <div class="title">Group Teacher</div>
#         <div class="team-members">
#             <div class="team-member">
#                 <img src="authors/avatar.jpg" alt="Mengzhou Gao">
#                 <div class="name">Mengzhou Gao</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg" alt="Mengzhou Gao">
#                 <div class="name">Mengzhou Gao</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg" alt="Mengzhou Gao">
#                 <div class="name">Mengzhou Gao</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg" alt="Mengzhou Gao">
#                 <div class="name">Mengzhou Gao</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg" alt="Mengzhou Gao">
#                 <div class="name">Mengzhou Gao</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Tang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
           
#             <!-- Add more group teachers as needed -->
#         </div>
#     </div>

#     <div class="section">
#         <div class="title">Student</div>
#         <div class="team-members">
#             <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#              <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#              <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#              <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#              <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
#             <div class="team-member">
#                 <img src="authors/avatar.jpg"" alt="Group Teacher 2">
#                 <div class="name">Teacher Zhang</div>
#                 <div class="position">Group Teacher</div>
#             </div>
         
#             <!-- Add more students as needed -->
#         </div>
#     </div>
# </body>
# </html>
# '

  # - block: markdown
  #   id: awards
  #   content:
  #     title: Awards and Grants
  #     text: |-

    # design:
    #   columns: '1'

  - block: markdown
    id: service
    content:
      title: Professional Services
      text: |-
  
           ###   Program Committee
            + AAAI Conference on Artificial Intelligence
            + International Joint Conference on Artificial Intelligence
            + Association for Computational Linguistics
            +  IEEE International Conference on Data Mining 
            + ACM Multimedia Conference
            + The Web Conference
            + European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases
            + ACM SIGKDD International Conference on Knowledge Discovery and Data Mining

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


  # - block: experience
  #   id: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: lecturer
  #         company: Tianjing University
  #         company_url: ''
  #         company_logo: ''
  #         location: Chinese
  #         date_start: '2018-09-01'
  #         date_end: '2021-11-01'
  #         description: Taught computer science.
  #       - title: Distinguished Professor
  #         company: Hangzhou Dianzi University
  #         company_url: ''
  #         company_logo: ''
  #         location: Chinese
  #         date_start: '2021-12-01'
  #         date_end: ''
  #         description: |2-
  #             Research include:

  #             * Graph neural
  #             * Time series
  #             * Representation learning
  # ### Hosting and participating in projects
  #           + Research on interpretable deep generation models and algorithms for dynamic complex networks
  #           + Research on community detection and evolution of large-scale dynamic complex networks driven by node roles
  #           + Research on cross-modal semantic understanding and knowledge reasoning under brain-like characteristics
  #           + Research on intelligent auxiliary technology of administrative law enforcement based on graph mining
  #           + Research on basic theory and key algorithm of cross-modal intelligent computing
  #           + Knowledge representation and computation for multimodal information networks
  #           + XXXXX Measurement system
  #           + Research on the hierarchical linkage mechanical modeling of multi-scale information propagation in cyberspace
  #           + Research on large-scale network community discovery based on Markov random fields
  #           + Research on accurate semantic community discovery for large-scale and complex networks
  #           + Urban transmission and prediction models of highly infectious diseases Construction method
  #           + Specific human-event correlation open source clue mining and "people in the loop" visual research and judgment platform
  #           + The key technology of role identification in large-scale covert complex network
  #           + Network event detection

  #   design:
  #     columns: '2'
  # - block: accomplishments
  #   id: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: ''
  #         date_end: '2024-01-01'
  #         date_start: '2021-01-25'
  #         description: 'Facing the semantic complexity of graph-structured data, the applicant focuses on the challenges of diverse node types, diverse and sparse semantic information, complex topological attribute interaction and diverse generation mechanisms in complex graphs, and effectively breaks through the difficulties of complex graph attribute semantic diversity and topological attribute interaction. Promoted the generative integration of probabilistic graph model and deep learning method in node and sublayer surface, published 12 papers in AAAI, IJCAI, TKDE, TIST, WWW and other journal conferences as the first or corresponding author. And published the review paper "A Survey of Community Detection Approaches: From Statistical Modeling to Deep Learning "(TKDE 2023), cited more than 230 times by Google academics. He applied theoretical methods to social recommendation and knowledge graph, and his related results were published in SIGIR2019, SIGIR2022, WWW2023, and won the NLPCC2019 Outstanding Paper Award. Applied to Internet edge computing, related results are published in (TNSM 2021) and (IoT-J 2021), paper "EEDTO: an energy-efficient dynamic task offloading algorithm for blockchain-enabled IoT-edge-cloud orchestrated  "computing" is included in ESI database as a highly cited paper - the number of citations has placed it in the top 1% of the corresponding academic field (more than 180 Google academic citations).'
  #         icon: ''
  #         organization: ''
  #         title: Topological semantic fusion of complex graphs
  #         url: ''
  #       - certificate_url: ''
  #         date_end: '2024-01-01'
  #         date_start: '2021-01-25'
  #         description: 'Focusing on the complexity of links in graph-structured data, the applicant has systematically broken through the problems of complex local links and difficult acquisition of common features by focusing on challenges such as complex local low-order dependencies, complex multi-order interactions, complex global dependencies and diverse generation mechanisms in complex graphs, and has innovatively built a system of structural similarity modeling, representation, mining and generation methods. He promoted the robust representation of complex link patterns for multi-order interactions in graph-structured data, task mining for heterogamy guidance and fusion generation of high-low order interactions, and published 12 papers in IEEE TCYB, TBD, IJCAI, AAAI, Information Sciences, ICDM, CIKM and other journal conferences. As the first author, he published a review paper "Review of Role-oriented Network Representation Learning" in the Journal of Computer Science, and was invited to give lectures on ICDM (CCF-B class) and DSAA (CCF-C class). Based on the research results, the applicant proposed "Threats and Countermeasures of International Biohackers to Biosecurity" (Expert advice, Ministry of Education, March 2021), pointing out how to use artificial intelligence, complex network analysis and other technologies to address the challenges brought by biohacking technology in the context of cyber security and biosecurity.'
  #         icon: ''
  #         organization: ''
  #         title: Link pattern learning method for complex graphs
  #         url: ''
  #       - certificate_url: ''
  #         date_end: '2024-01-01'
  #         date_start: '2021-01-25'
  #         description: 'Oriented towards the evolutionary complexity of graph-structured data, the applicant focuses on the challenges existing in complex graphs such as variable node evolution behavior, complex link prediction model, unknown topological evolution mechanism, multi-level dependence of global evolution and cross-scale topological evolution coupling, and innovatively breaks through the joint generation problem of micro, mesoscopic and macro coupling interaction of graph-structured data. It has formed a topology multi-scale mining and generation method system, promoted the evolutionary behavior analysis of microscopic nodes, mesoscopic subgraphs and macro snapshots in graph structure data, the generation and modeling of multi-scale topological structure coupling, and the deep mining of link prediction, subgraph evolution and anomaly discovery. He has published 10 papers as the first or corresponding author in TKDE, Computer Research and Development, TCYB, TNNLS and other related journals. Based on the proposed dynamic graph theory and method, the applicant and collaborators carried out applications in public opinion tracking and virus tracing during the novel coronavirus epidemic, provided a lot of high-value information and suggestions for relevant departments, and obtained a letter of thanks from the Ministry of Foreign Affairs of the People’s Republic of China (Arms Control Letter No. 218, 2020). In addition, the "Proposal on the Development of Tianjin Intelligent Security Industry" proposed by the applicant was selected by the Tianjin Education Committee as the first prize of 2018-2019 Tianjin University Think Tank Excellent Decision-making Consulting Research results.'
  #         icon: ''
  #         organization: ''
  #         title: Complex graph evolution behavior mining method
  #         url: ''
  #   design:
  #     columns: '2'
 
  

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      
      # Contact (add or remove contact options as necessary)
      email: pjiao@hdu.edu.cn
      address:
        street: 1158, No.2 Street, Baiyang Street
        city: HangZhou
        region: Hangzhou Economic and Technological Development Zone
        postcode: '310018'
        country: Chinese
        country_code: CN
      directions: Hangzhou Dianzi University Science Hall 708
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '120.349512'
        longitude: '30.320546'  
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
