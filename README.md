# Hello everyone, this is Rishabh 👋

I'm a Maths grad, with a strong focus on data science. I specialize in translating complex data into actionable insights, leveraging mathematical principles and advanced techniques.

---

## 🔧 Skills & Technologies

### Programming Languages
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

### Libraries & Frameworks
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)](https://scipy.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)](https://keras.io/)
[![NLTK](https://img.shields.io/badge/NLTK-3C8C2A?style=flat&logo=nltk&logoColor=white)](https://www.nltk.org/)
[![Beautiful Soup](https://img.shields.io/badge/Beautiful%20Soup-FFD54F?style=flat&logo=python&logoColor=black)](https://www.crummy.com/software/BeautifulSoup/)
[![Requests](https://img.shields.io/badge/Requests-0074D9?style=flat&logo=python&logoColor=white)](https://docs.python-requests.org/)

### Data Visualization
[![Matplotlib](https://img.shields.io/badge/Matplotlib-003B57?style=flat&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-9C66E0?style=flat&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)

### Databases
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

### Development Tools
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/)

---

## 🧠 Mathematics Foundation

**Mathematics Teacher**  
_Years of Service: 3_  
_Taught undergraduate mathematics to engineering students._  
- Advanced Calculus
- Linear Algebra
- Differential Equations
- Numerical Analysis

---

## 🌐 My Skill Map: Graph Network

My skills, tools, and mathematical expertise are deeply interconnected. Here’s how they cluster and connect in a skill network:


Click to show code for Skill Graph Network

```
import networkx as nx
import matplotlib.pyplot as plt

# Define clusters
languages = ["Python", "SQL"]
libraries = ["Pandas", "NumPy", "SciPy", "Scikit-Learn", "TensorFlow", "Keras", "NLTK", "Beautiful Soup", "Requests"]
dataviz = ["Matplotlib", "Seaborn", "Excel", "Power BI"]
databases = ["PostgreSQL"]
devtools = ["Jupyter Notebook", "VSCode", "Git", "GitHub"]
maths = ["Advanced Calculus", "Linear Algebra", "Differential Equations", "Numerical Analysis"]

nodes = languages + libraries + dataviz + databases + devtools + maths

edges = [
    # Programming connections
    ("Python", "Pandas"), ("Python", "NumPy"), ("Python", "SciPy"),
    ("Python", "Scikit-Learn"), ("Python", "TensorFlow"), ("Python", "Keras"),
    ("Python", "Matplotlib"), ("Python", "Seaborn"), ("Python", "Jupyter Notebook"),
    ("Python", "NLTK"), ("Python", "Beautiful Soup"), ("Python", "Requests"),

    ("SQL", "PostgreSQL"), ("SQL", "Excel"), ("SQL", "Power BI"),

    # Libraries
    ("Pandas", "NumPy"), ("NumPy", "SciPy"), ("Pandas", "Scikit-Learn"),
    ("NumPy", "Scikit-Learn"), ("SciPy", "Scikit-Learn"),
    ("TensorFlow", "Keras"), ("Scikit-Learn", "TensorFlow"),
    ("NLTK", "Scikit-Learn"), ("Beautiful Soup", "Requests"),

    # Data Viz
    ("Matplotlib", "Seaborn"), ("Matplotlib", "Pandas"), ("Seaborn", "Pandas"),
    ("Excel", "Power BI"),

    # Dev Tools
    ("Jupyter Notebook", "Pandas"), ("Jupyter Notebook", "Matplotlib"),
    ("Jupyter Notebook", "Scikit-Learn"),
    ("Git", "GitHub"), ("Git", "VSCode"),

    # Maths
    ("Advanced Calculus", "Linear Algebra"), ("Linear Algebra", "Differential Equations"),
    ("Numerical Analysis", "Differential Equations"),
    ("Linear Algebra", "Scikit-Learn"), ("Linear Algebra", "TensorFlow"),
    ("Numerical Analysis", "SciPy")
]

G = nx.Graph()
G.add_nodes_from(nodes)
G.add_edges_from(edges)

plt.figure(figsize=(18, 13))
pos = nx.spring_layout(G, k=0.25)
nx.draw(G, pos, with_labels=True, node_size=2500, node_color="#E1EAF2", font_size=11, edge_color="#A0A0A0")
plt.title("Rishabh's Skill Graph Network", fontsize=18, fontweight="bold")
plt.show()
```
_Copy this into your Jupyter Notebook or Python script and run!_



---

## 🚀 Explore My Work

Check out my live projects and demos on Streamlit:

[![Streamlit Badge](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://share.streamlit.io/user/rishabhvishwakarma1729)

- [Rishabh's Streamlit Projects](https://share.streamlit.io/user/rishabhvishwakarma1729)

---

## 📬 Contact

- **Email:** [rsbvishwa88@gmail.com](mailto:rsbvishwa88@gmail.com)
- **LinkedIn:** [Rishabh Vishwakarma](https://www.linkedin.com/in/rishabh-vishwakarma-a73a141b2/)

---

_Feel free to reach out if you want to collaborate, discuss data science problems, or just connect!_
```
