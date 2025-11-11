# Summer of Code – Artificial Intelligence (Machine Learning & Deep Learning)

A comprehensive, hands-on learning path covering Python fundamentals through advanced Deep Learning concepts. This repository is organized month-by-month and week-by-week with lecture materials, Jupyter notebooks, datasets, and practical exercises that build from basics to production-ready AI skills.

<p align="center">
  <img src="https://media.giphy.com/media/QTfX9Ejfra3ZmNxh6B/giphy.gif" alt="AI learning animation" width="420">
</p>

---

## Highlights
- **Structured 3-month curriculum**: Progressive learning from Python to Deep Learning
- **Hands-on approach**: Practical exercises and real-world datasets
- **Comprehensive topics**: Python, Statistics, ML, Computer Vision, NLP
- **Ready-to-run notebooks**: Open in Jupyter or VS Code and start learning immediately

---

## Repository Structure

```
Summer of Code - AI/
├── Month 01/          # Python & Statistics Foundations
│   ├── Week 01/       # Python Basics
│   ├── Week 02/       # Functions & OOP
│   ├── Week 03/       # Statistics for ML
│   └── Week 04/       # NumPy & Pandas
├── Month 02/          # Machine Learning Fundamentals
│   ├── Week 05/       # Introduction to ML
│   ├── Week 06/       # Regression Models
│   ├── Week 07/       # Classification Models
│   └── Week 08/       # Neural Networks
├── Month 03/          # Deep Learning & Advanced Topics
│   ├── Week 09/       # NLP Fundamentals
│   └── Week 10/       # RNNs & Sequence Models
├── datasets/          # Datasets for exercises
├── Exam/             # Assessment materials
└── README.md
```

### Month 01: Python & Statistics Foundations

**Week 01: Python Fundamentals**
- Notebooks: Python basics, data structures, conditionals & loops
- Topics: Variables, strings, lists, tuples, dictionaries, control flow

**Week 02: Functions & Object-Oriented Programming**
- Notebooks: Functions, file I/O, OOP concepts
- Topics: Function parameters, classes, objects, inheritance, abstraction

**Week 03: Statistics for Machine Learning**
- Notebooks: Central tendency, dispersion, position, correlation
- Topics: Mean, median, mode, variance, standard deviation, correlation analysis

**Week 04: Data Analysis with NumPy & Pandas**
- Notebooks: NumPy arrays, Pandas fundamentals, data manipulation
- Topics: Array operations, indexing, broadcasting, DataFrames, data cleaning

### Month 02: Machine Learning Fundamentals

**Week 05: Introduction to Machine Learning**
- Notebooks: ML basics, scikit-learn introduction
- Topics: Supervised vs unsupervised learning, model evaluation, California housing dataset

**Week 06: Regression Models**
- Notebooks: Linear regression, polynomial regression
- Topics: Model fitting, feature engineering, prediction

**Week 07: Classification Models**
- Notebooks: Classification algorithms, model evaluation
- Topics: Logistic regression, decision trees, confusion matrix, precision/recall

**Week 08: Neural Networks & Deep Learning Basics**
- Notebooks: Introduction to neural networks, training deep models
- Topics: Backpropagation, activation functions, batch normalization, ResNet

### Month 03: Deep Learning & Advanced Topics

**Week 09: Natural Language Processing**
- Notebooks: NLP fundamentals, word embeddings
- Topics: Tokenization, lemmatization, POS tagging, TF-IDF, word vectors

**Week 10: Recurrent Neural Networks & Sequence Models**
- Notebooks: RNNs, LSTMs, text generation, machine translation
- Topics: Sequence modeling, sentiment analysis, language modeling, English-Urdu translation
- Datasets: IMDB reviews, Shakespeare text, English-Urdu parallel corpus

---

## Quick Start

### 1. Install Python and Dependencies

Ensure you have Python 3.9+ installed, then install required packages:

```bash
# Core packages
pip install notebook jupyterlab

# ML/DL packages
pip install numpy pandas matplotlib seaborn
pip install scikit-learn torch torchvision
pip install spacy nltk
```

### 2. Clone or Download Repository

```bash
git clone https://github.com/your-username/summer-of-code-ai.git
cd summer-of-code-ai
```

### 3. Launch Jupyter

```bash
# Option 1: Jupyter Lab (recommended)
jupyter lab

# Option 2: Classic Notebook
jupyter notebook
```

### 4. Using VS Code (Alternative)

- Install "Python" and "Jupyter" extensions
- Open the repository folder
- Navigate to any `.ipynb` file and run cells inline

---

## Suggested Learning Path

1. **Month 01 (Weeks 1-4)**: Master Python fundamentals and statistical concepts
   - Complete notebooks sequentially
   - Practice exercises at the end of each notebook
   - Work with [`students.csv`](Month 01/Week 04/Notebooks/students.csv) for Pandas practice

2. **Month 02 (Weeks 5-8)**: Build ML intuition with scikit-learn
   - Implement algorithms from scratch before using libraries
   - Focus on California housing dataset in [w5d2](Month 02/Week 05/Notebooks/w5d2 - Introduction to Machine Learning.ipynb)
   - Practice model evaluation techniques

3. **Month 03 (Weeks 9-10)**: Dive into Deep Learning and NLP
   - Experiment with RNN architectures in [w10d1](Month 03/Week 02/Notebooks/w10d1 - Recurrent Neural Networks.ipynb)
   - Build text generation models in [w10d3](Month 03/Week 02/Notebooks/w10d3 - Text Generation.ipynb)
   - Implement machine translation in [w10d5](Month 03/Week 02/Notebooks/w10d5 - Machine Translation.ipynb)

---

## Key Notebooks to Explore

### Python & Data Science
- [w4d3 - Pandas Fundamentals](Month 01/Week 04/Notebooks/w4d3 - Pandas Fundamentals.ipynb)
- [w4d2 - NumPy Indexing, Broadcasting, and I-O](Month 01/Week 04/Notebooks/w4d2 - NumPy Indexing, Broadcasting, and I-O.ipynb)

### Machine Learning
- [w5d2 - Introduction to Machine Learning](Month 02/Week 05/Notebooks/w5d2 - Introduction to Machine Learning.ipynb)
- [w7d2_d3 - Evaluating Classification Models](Month 02/Week 07/Notebooks/w7d2_d3 - Evaluating Classification Models.ipynb)

### Deep Learning & NLP
- [w9d4 - NLP Fundamentals](Month 03/Week 01/Notebooks/w9d4 - NLP Fundamentals.ipynb)
- [w10d1 - Recurrent Neural Networks](Month 03/Week 02/Notebooks/w10d1 - Recurrent Neural Networks.ipynb)
- [w10d2 - Long Short-Term Memory](Month 03/Week 02/Notebooks/w10d2 - Long Short-Term Memory.ipynb)
- [w10d3 - Text Generation](Month 03/Week 02/Notebooks/w10d3 - Text Generation.ipynb)
- [w10d5 - Machine Translation](Month 03/Week 02/Notebooks/w10d5 - Machine Translation.ipynb)

---

## Datasets

The repository includes several datasets in the [`datasets`](datasets/) folder and embedded in specific week folders:

- **California Housing**: Used in [Month 02/Week 05](Month 02/Week 05/Notebooks/w5d2 - Introduction to Machine Learning.ipynb)
- **Student Data**: [`students.csv`](Month 01/Week 04/Notebooks/students.csv) for Pandas exercises
- **IMDB Reviews**: Sentiment analysis dataset (RNN notebooks)
- **Shakespeare Text**: Character-level text generation
- **English-Urdu Corpus**: Machine translation ([eng-urd](Month 03/Week 02/Notebooks/eng-urd/))

---

## Tips for Success

- **Run cells frequently**: Experiment with parameters and visualize outputs
- **Keep notes**: Summarize key concepts after each notebook
- **Practice coding**: Re-implement utilities from memory (e.g., preprocessing functions)
- **Vectorize operations**: Convert loops to NumPy/Pandas operations for efficiency
- **Experiment**: Modify model architectures and hyperparameters
- **Use the datasets**: Apply techniques to the provided datasets

---

## Project Structure Notes

- Each week folder contains `Notebooks/` subdirectory with `.ipynb` files
- Temporary files are in [`.tmp.driveupload/`](.tmp.driveupload/) and [`.tmp.drivedownload/`](.tmp.drivedownload/)
- Configuration files in [`.vscode/`](.vscode/) for VS Code users
- [`.gitignore`](.gitignore) excludes temporary and system files

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes with clear commit messages
4. Follow the existing folder structure and naming conventions
5. Submit a pull request with a description of changes

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Thanks to all contributors who helped shape these materials
- Open-source community for amazing tools (NumPy, Pandas, PyTorch, scikit-learn)
- Dataset providers: Tatoeba Project (English-Urdu), UCI ML Repository, Kaggle
- Inspired by practical AI education and hands-on learning approaches

---

## Contact & Support

For questions, issues, or suggestions:
- Open an issue on GitHub
- Review existing notebooks for examples
- Check inline comments and markdown cells for guidance

Happy Learning! 🚀