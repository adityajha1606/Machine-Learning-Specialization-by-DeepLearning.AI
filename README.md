# 🧠 Andrew Ng’s Machine Learning Specialization – My Humble Beginnings

![GitHub last commit](https://img.shields.io/github/last-commit/adityajha1606/Machine-Learning-Specialization-by-DeepLearning.AI)
![GitHub repo size](https://img.shields.io/github/repo-size/adityajha1606/Machine-Learning-Specialization-by-DeepLearning.AI)
![GitHub](https://img.shields.io/github/license/adityajha1606/Machine-Learning-Specialization-by-DeepLearning.AI)
![Maintenance](https://img.shields.io/maintenance/yes/2026)

> *“The journey of a thousand miles begins with a single step – and a whole lot of gradient descent.”*  
> — Someone wise (probably after debugging at 2 AM)

Welcome to my **glorious** repository, where I document my (sometimes painful, often enlightening) journey through the **Machine Learning Specialization** by the legendary **Andrew Ng**, brought to you by DeepLearning.AI and Stanford Online.

**Current status:** Just finished **Week 1 of Course 1** (*Supervised Machine Learning: Regression and Classification*).  
So, yeah, I’m basically a machine learning expert now. (Please don’t ask me about backpropagation yet.)

---

## 📚 About the Specialization

This world-famous specialization (the 2022 reboot of the classic 2011 course) is designed to give you a solid foundation in ML. It covers:

- **Course 1:** Supervised Machine Learning (Regression & Classification)  
- **Course 2:** Advanced Learning Algorithms  
- **Course 3:** Unsupervised Learning, Recommenders, Reinforcement Learning  

I’m working through the labs and assignments, trying to keep my sanity intact, and storing all my work here. Maybe one day this repo will help someone else. Or at least serve as a cautionary tale.

---

## 📁 Repository Structure

The repo is organised by course and week. Here’s how it looks so far (it’s a bit sparse – I’m only a week in, give me a break!):

```
Machine-Learning-Specialization-by-DeepLearning.AI/
│
├── Machine Learning Specialization/
│   └── Supervised Machine Learning Regression and Classification/
│       ├── .idea/                         # PyCharm project files (ignore these, they're just for my IDE)
│       ├── images/                        # Handy diagrams from the labs
│       ├── C1_W1_Lab01_Model_Representation_Soln.ipynb
│       ├── C1_W1_Lab02_Cost_Function_Soln.ipynb
│       ├── C1_W1_Lab03_Linear_Regression_Soln.ipynb
│       ├── C1_W1_Lab04_Gradient_Descent_Soln.ipynb
│       ├── C1_W1_Lab05_Feature_Scaling_and_Learning_Rate_Soln.ipynb
│       └── README.md                        # (this file – meta, I know)
│
└── README.md                                # You are here (the root README)
```

> **Note:** The `.idea/` folder is just PyCharm’s workspace config – you can safely ignore it (and probably delete it if you’re not using PyCharm).  
> Also, the notebooks have `_Soln` in their names because I worked through the labs and kept my own solutions. If you’re taking the course, I recommend doing the same – but remember the honor code!

---

## 🏁 Week 1 – What I’ve Learned So Far

Week 1 of Course 1 is all about the **fundamentals of supervised learning**, with a focus on **linear regression**. Here’s a quick recap of the labs:

| Lab | Topic | What I Learned |
|-----|-------|----------------------------------|
| **C1_W1_Lab01** | Model Representation | Learned how a linear model works: \( f_{w,b}(x) = wx + b \). Turns out "w" and "b" are not random letters, they actually *mean something*. |
| **C1_W1_Lab02** | Cost Function | Introduced to the cost function \( J(w,b) \), specifically Mean Squared Error. Basically: how wrong is my model, and how do I measure that pain mathematically? |
| **C1_W1_Lab03** | Gradient Descent | The core idea of optimization, updating parameters step by step to minimize cost. AKA: walking downhill blindfolded but with math as your guide. |
| **C1_W1_Lab04** | Gradient Descent in Practice | Implemented gradient descent for linear regression and actually saw it converge. Very satisfying when it works… mildly traumatic when it doesn’t. |

Each notebook contains code, visualisations, and my own comments (some serious, some less so). Feel free to snoop around.

---

## 🚀 How to Use This Repo

If you’re also taking the course and want to run my notebooks (or just curious), here’s how:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/adityajha1606/Machine-Learning-Specialization-by-DeepLearning.AI.git
   cd Machine-Learning-Specialization-by-DeepLearning.AI
   ```

2. **Set up a Python environment** (I recommend using `venv` or `conda`):
   ```bash
   python -m venv ml-env
   source ml-env/bin/activate   # On Windows: ml-env\Scripts\activate
   ```

3. **Install required packages:**
   ```bash
   pip install numpy matplotlib scikit-learn jupyter
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Then navigate to the notebook you want to explore.

---

## 🧰 Prerequisites

- **Python 3.7+** (I’m using 3.10)
- Basic knowledge of Python (loops, functions, arrays)
- A healthy dose of curiosity – and maybe a stress ball for when gradient descent refuses to converge.

---

## 🙏 Acknowledgments

- **Andrew Ng** – for being the most enthusiastic and clear educator in the ML world. Seriously, that guy could make a lecture on paint drying sound exciting.
- **DeepLearning.AI** and **Stanford Online** – for making this course freely available (well, mostly – but it’s worth every penny).
- **My future self** – for not rage-quitting when the learning rate was too high and the loss shot to infinity.

---

## ⚠️ Honor Code & Plagiarism

I’ve uploaded my work primarily for my own backup and to share with friends who are also taking the course. If you’re an active student, I strongly encourage you to **write your own code** – you’ll learn much more that way. Please don’t just copy-paste these notebooks and submit them as your own. Andrew Ng and the team worked hard to create this course; let’s respect their effort and the learning process.

If you’re a recruiter or a fellow developer checking out my work – welcome! Feel free to look around, but remember that these are just my learning notes, not production-ready code. 😉

---


## 📝 License

This project is for educational purposes only. The original course content belongs to DeepLearning.AI and Stanford Online. My code and notes are shared under the [MIT License](LICENSE) – use them at your own risk (and maybe with a grain of salt).

---

**Happy Learning!**  
May your gradients be small and your learning rates just right. 🚀

P.S. – If you spot a bug or an embarrassing mistake, please let me know gently. I’m fragile.
