**OPEN DATA SCIENCE AND NETWORK THEORY — HIGH SCHOOL COURSE**

This repository contains the materials developed for an Open Data Science course taught to high school students at Liceo B. Cairoli.
The course lasts 10 hours and introduces students to the fundamentals of data science and network theory through examples, discussion, and hands-on Python activities.

The main goal of the course is to help students learn how to ask meaningful questions using data and how to understand complex systems using networks.
No prior knowledge of data science or network theory is required.

**INTRODUCTION TO DATA SCIENCE**

The course begins with the basic ideas of data science. Students learn what it means to ask data-driven questions, where data comes from, and how data can be collected and analyzed.
The concept of a **data analysis pipeline** is introduced, from data collection to interpretation of results.

A central theme in this part of the course is the distinction between **correlation and causation**, with examples showing why correlated data does not necessarily imply a causal relationship.

**INTRODUCTION TO NETWORK THEORY**

The second part of the course introduces **network theory** as a way to describe data. Students learn to see the world as a collection of networks made of nodes and links.

Key concepts are introduced in an intuitive way, including degree, degree distribution, and centrality. Different kinds of networks are discussed, such as undirected and directed networks, weighted networks (for example, friendship strength), and bipartite networks.

Classic network models are explored and compared, including lattice networks, small-world networks, and scale-free networks, with connections to real systems such as social networks, transportation networks, and online platforms.

**HANDS-ON ACTIVITIES AND EXAMPLES**

A large part of the course is based on practical activities in Python. Students use the NetworkX library to build networks, visualize them, and compute basic metrics such as degree and centrality.

Well-known datasets, including the **Karate Club network** and the **Florentine Families network**, are used to show how network structure can reveal community formation, influence, and power relationships that are not obvious from raw data alone.

**BIPARTITE NETWORKS AND PROJECTIONS**

**Bipartite networks** play a central role in the course. Starting from a simple students–subjects example, students learn how bipartite data naturally arises in surveys.

These networks are then projected to create new networks, such as student–student networks based on shared interests. This helps students understand indirect relationships and similarity between individuals.

A Pokémon dataset is used as an engaging example to combine traditional data analysis with network representations, showing that even playful datasets can reveal meaningful patterns.

**RESEARCH DESIGN AND DATA COLLECTION**

The course also introduces basic principles of research design. **Students learn how to define research questions, structure a survey, select relevant variables, design questionnaires, and choose data collection channels such as schoolmates, friends, and social media**.

**Collected data is then analyzed** using network structure and metrics, reinforcing the connection between data collection, modeling, and interpretation.

**TOOLS AND ENVIRONMENT**

All activities are implemented in Python, using:

- **Pandas** for data analysis

- **NetworkX** for network modeling

- **Matplotlib** for visualization

The materials are designed to run in Jupyter Notebook or Google Colab.

**EDUCATIONAL APPROACH**

The focus of this repository is on clarity, interpretation, and intuition, rather than technical complexity.
Each notebook explains what is being done, why it is done, and how to interpret the results.

The goal is to help students build a solid understanding of data and networks while providing tools that can be applied to many real-world problems.
