<div align="left" style="position: relative;">
<img src="https://img.icons8.com/?size=512&id=55494&format=png" align="right" width="30%" style="margin: -20px 0 0 20px;">
<h1>MUSIC-GENRE-CLASSIFIER</h1>
<p align="left">
	<img src="https://img.shields.io/github/license/MarcGeorgeML/music-genre-classifier?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/MarcGeorgeML/music-genre-classifier?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/MarcGeorgeML/music-genre-classifier?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/MarcGeorgeML/music-genre-classifier?style=default&color=0080ff" alt="repo-language-count">
</p>
<p align="left"><!-- default option, no dependency badges. -->
</p>
<p align="left">
	<!-- default option, no dependency badges. -->
</p>
</div>
<br clear="right">

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Testing](#-testing)
- [ Contributing](#-contributing)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

<code>❯ This repository provides a full pipeline for building a music genre classification model:

- **Data preprocessing** via a Jupyter notebook (`preprocessing.ipynb`)
- **Training** a CNN model saved as `Trained_model.keras`
- **Recorded training history** in `training_hist.json`</code>

---

##  Features

<code>❯ 
- Converts audio into model-friendly features
- Trains a CNN for genre classification
- Outputs a serialized trained model for inference
- Logs loss/metric history for review</code>

---

##  Project Structure

```sh
└── music-genre-classifier/
    ├── Trained_model.keras
    ├── preprocessing.ipynb
    ├── requirement.txt
    └── training_hist.json
```


###  Project Index
<details open>
	<summary><b><code>MUSIC-GENRE-CLASSIFIER/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/MarcGeorgeML/music-genre-classifier/blob/master/Trained_model.keras'>Trained_model.keras</a></b></td>
				<td><code>❯ Trained CNN model weights</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/MarcGeorgeML/music-genre-classifier/blob/master/requirement.txt'>requirement.txt</a></b></td>
				<td><code>❯ Python dependencies</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/MarcGeorgeML/music-genre-classifier/blob/master/preprocessing.ipynb'>preprocessing.ipynb</a></b></td>
				<td><code>❯ Notebook for audio prep & feature engineering</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/MarcGeorgeML/music-genre-classifier/blob/master/training_hist.json'>training_hist.json</a></b></td>
				<td><code>❯ Model training history (metrics per epoch)</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---
##  Getting Started

###  Prerequisites

Before getting started with music-genre-classifier, ensure your runtime environment meets the following requirements:

- **Programming Language:** Error detecting primary_language: {'keras': 1, 'txt': 1, 'ipynb': 1, 'json': 1}


###  Installation

Install music-genre-classifier using one of the following methods:

**Build from source:**

1. Clone the music-genre-classifier repository:
```sh
❯ git clone https://github.com/MarcGeorgeML/music-genre-classifier
```

2. Navigate to the project directory:
```sh
❯ cd music-genre-classifier
```

3. Install the project dependencies:

echo 'pip install -r requirements.txt'




##  Contributing

- **💬 [Join the Discussions](https://github.com/MarcGeorgeML/music-genre-classifier/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/MarcGeorgeML/music-genre-classifier/issues)**: Submit bugs found or log feature requests for the `music-genre-classifier` project.
- **💡 [Submit Pull Requests](https://github.com/MarcGeorgeML/music-genre-classifier/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/MarcGeorgeML/music-genre-classifier
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/MarcGeorgeML/music-genre-classifier/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=MarcGeorgeML/music-genre-classifier">
   </a>
</p>
</details>

---

##  Acknowledgments

- Used the GTzan dataset from kaggle: [GTZAN Dataset on Kaggle](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/data)
- The project playlist on youtube: [Project Demo Playlist on YouTube](https://www.youtube.com/playlist?list=PLvz5lCwTgdXCd200WNDupTMo15DP9iryv)
---
