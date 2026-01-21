Open Data Science and Network Theory for High School Students

This repository contains the materials developed for an Open Data Science course conducted for high school students at Liceo B. Cairoli, delivered over a total of ten hours. The course introduces students to the foundations of data science and network theory through a combination of conceptual explanations, real datasets, and hands-on Python activities.

The main goal of the course is to provide students with tools to reason about data, ask meaningful questions, and understand complex systems using networks. No prior knowledge of data science or network theory is assumed; the course starts from basic concepts and gradually builds intuition and technical skills.

Course overview

The first part of the course focuses on the fundamentals of data science. Students learn how to formulate data-driven questions, understand different types of data sources, and follow a basic data analysis pipeline from data collection to interpretation. Particular attention is given to the distinction between correlation and causation, encouraging a critical approach to data analysis and results.

The second part introduces network theory as a powerful framework for describing complex systems. Students explore the idea of the world as a collection of networks made of nodes and links and learn key concepts such as degree, degree distribution, and centrality. Different types of networks are discussed, including undirected and directed networks, weighted networks (for example, representing friendship strength), and bipartite networks.

Classic network models are introduced and compared, including lattice networks, small-world networks, and scale-free networks. These models are used to explain structural properties observed in real systems such as social networks, transportation networks, and online platforms.

Practical activities and datasets

A significant portion of the course is dedicated to hands-on activities using Python. Students work with the NetworkX library to create and manipulate graphs, compute basic network metrics, and visualize network structures. The notebooks include both synthetic examples and well-known real-world datasets, such as the Karate Club network and the Florentine Families network, to illustrate concepts like community structure and centrality beyond simple node degree.

Bipartite networks play a central role in the course. Starting from a students–subjects example, students learn how bipartite data naturally arises in surveys and how such networks can be projected to obtain friendship or interest-based networks. A Pokémon dataset is used as an accessible and engaging example to show how traditional data analysis with Pandas can be combined with network-based representations.

Research design and data collection

The course also introduces basic principles of research design. Students are guided through the process of defining research questions, structuring a survey, selecting relevant variables, designing questionnaires, and choosing data collection channels such as schoolmates, friends, and social media. Collected data is then analyzed through its network structure and associated metrics, reinforcing the link between data collection, modeling, and interpretation.

Technologies used

All analyses are implemented in Python using Pandas for data handling, NetworkX for network analysis, and Matplotlib for visualization. The materials are designed to run in Jupyter Notebook or Google Colab environments.

Educational focus

The emphasis throughout the repository is on clarity, interpretation, and conceptual understanding rather than technical complexity. Each notebook explains not only how to perform an analysis, but also why a particular method is used and what the results mean. The project aims to build intuition about data and networks while providing students with practical tools they can apply to many real-world problems.
