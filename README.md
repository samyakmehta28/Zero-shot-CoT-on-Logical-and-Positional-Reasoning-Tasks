<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>
<p align="center">
    <h1 align="center">ZERO-SHOT-COT-ON-LOGICAL-AND-POSITIONAL-REASONING-TASKS</h1>
</p>
<p align="center">
    <em>Unleashing Zero-Shot Logic & Positional Precision</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=Jupyter&logoColor=white" alt="Jupyter">
	<img src="https://img.shields.io/badge/OpenAI-412991.svg?style=flat&logo=OpenAI&logoColor=white" alt="OpenAI">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
	<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
</p>
<hr>

##  Quick Links

> - [ Overview](#-overview)
> - [ Features](#-features)
> - [ Repository Structure](#-repository-structure)
> - [ Modules](#-modules)
> - [ Getting Started](#-getting-started)
>   - [ Installation](#-installation)
>   - [ Running Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks](#-running-Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks)
>   - [ Tests](#-tests)
> - [ Project Roadmap](#-project-roadmap)
> - [ Contributing](#-contributing)
> - [ License](#-license)
> - [ Acknowledgments](#-acknowledgments)

---

##  Overview

The Zero-shot-CoT project focuses on logical and positional reasoning tasks by implementing capabilities such as generating prompts for question answering, model initialization, accuracy evaluation, and result logging. Key components like `main.py` orchestrate the zero-shot reasoning process, while `utils.py` provides essential functions for dataset handling, answer processing, and GPT-3 decoding. The project supports customization for various logical and positional reasoning tasks through datasets like family relationship puzzles and seating arrangements. By leveraging zero-shot learning with prompts and structured responses, the project enhances reasoning skills and enables accurate deductions in complex scenarios.

---

##  Features

|    |   Feature         | Description |
|----|-------------------|---------------------------------------------------------------|
| ⚙️  | **Architecture**  | The project architecture is designed for logical and positional reasoning tasks. It leverages Python and OpenAI for task orchestration, model initialization, question answering, and result evaluation. The `main.py`, `utils.py`, and Jupyter notebooks handle critical functionalities. |
| 🔩 | **Code Quality**  | The codebase maintains good quality and style standards, evident from modular functions in `utils.py`, clear argument parsing in `main.py`, and structured notebook execution in Jupyter notebooks. Good readability and adherence to best practices. |
| 📄 | **Documentation** | Documentation includes requirements in `requirements.txt`, dataset descriptions, and code summaries. While it could be more extensive, it adequately covers usage guidance and function explanations for different components. |
| 🔌 | **Integrations**  | It integrates with OpenAI for advanced reasoning capabilities. External dependencies include Python libraries like `py` for seamless functioning with the OpenAI platform. Integrates well with Jupyter notebooks for interactive testing. |
| 🧩 | **Modularity**    | The codebase exhibits good modularity, as seen through function encapsulation in `utils.py` and clear separation of tasks in different files. This promotes reusability and extension for different reasoning tasks. |
| 🧪 | **Testing**       | Testing frameworks aren't directly mentioned but likely include manual testing within Jupyter notebooks and CLI, ensuring accurate model outputs and task completion. Could benefit from the integration of automated testing for robustness. |
| ⚡️  | **Performance**   | The project demonstrates efficient processing, enabling quick reasoning on complex tasks. Resource usage appears optimized through minimal dependencies and streamlined code execution, resulting in effective task completion within a reasonable timeframe. |
| 🛡️ | **Security**      | Security measures primarily focus on API key validation for OpenAI usage, ensuring secure communication with external services. Limited data protection measures evident; potential area for enhancement in handling sensitive information securely. |
| 📦 | **Dependencies**  | Key dependencies include `py`, `ipynb`, and `requirements.txt`, facilitating OpenAI integration, Jupyter notebook execution, and library management. External libraries support core functionality for logical and positional reasoning tasks. |
| 🚀 | **Scalability**   | The project shows potential for scalability with its modular design, enabling easy enhancement for additional reasoning tasks. Extensive integration with OpenAI supports scalability through powerful AI capabilities for handling increased task complexity and volume. |


---

##  Repository Structure

```sh
└── Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/
    ├── README.md
    ├── implementation_code
    │   ├── -H
    │   ├── dataset
    │   │   ├── MultiArith
    │   │   │   └── MultiArith.json
    │   │   ├── family_relationship_puzzle
    │   │   │   └── family_relationship_puzzle.json
    │   │   └── seating_arrangement
    │   │       └── data_seating.json
    │   ├── main.py
    │   ├── my_log
    │   │   ├── MultiArith.json
    │   │   ├── family_relationship_puzzle.json
    │   │   ├── seating_arrangement.json
    │   │   └── testing_seating.json
    │   ├── requirements.txt
    │   ├── running_commands.ipynb
    │   └── utils.py
    └── report.pdf
```

---

##  Modules

<details closed><summary>implementation_code</summary>

| File                                                                                                                                                                      | Summary                                                                                                                                                                                                                                                            |
| ---                                                                                                                                                                       | ---                                                                                                                                                                                                                                                                |
| [main.py](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/main.py)                               | Summary: `main.py` orchestrates Zero-shot-CoT on logical and positional reasoning tasks within the parent repository. It parses arguments, initializes models, generates prompts for question answering, evaluates accuracy, and logs results.                     |
| [utils.py](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/utils.py)                             | Summary:**The `utils.py` file in the `implementation_code` directory of the repository provides functions for GPT-3 decoding, dataset handling, data loading, and answer processing. It supports customization for various logical and positional reasoning tasks. |
| [running_commands.ipynb](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/running_commands.ipynb) | Role: `running_commands.ipynb` executes logical and positional reasoning tasks code in `Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks` repository. Supports integration and testing routines for critical functionalities.                               |
| [-H](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/-H)                                         | Code snippet in `implementation_code/-H` handles API key validation error for OpenAI platform in parent repository for logical and positional reasoning tasks.                                                                                                     |
| [requirements.txt](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/requirements.txt)             | Code snippet in `implementation_code/requirements.txt` ensures OpenAI version 0.18.0 for the project's Logical & Positional Reasoning Tasks, supporting critical functionality in the repository architecture.**                                                   |

</details>

<details closed><summary>implementation_code.dataset.family_relationship_puzzle</summary>

| File                                                                                                                                                                                                                           | Summary                                                                                                                                                                                            |
| ---                                                                                                                                                                                                                            | ---                                                                                                                                                                                                |
| [family_relationship_puzzle.json](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/dataset/family_relationship_puzzle/family_relationship_puzzle.json) | Code snippet: Parses family relationship puzzle data.Summary: Parses family relationships data for logical reasoning tasks. Accurately identifies relationships within provided family structures. |

</details>

<details closed><summary>implementation_code.dataset.seating_arrangement</summary>

| File                                                                                                                                                                                        | Summary                                                                                                                                                                                         |
| ---                                                                                                                                                                                         | ---                                                                                                                                                                                             |
| [data_seating.json](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/dataset/seating_arrangement/data_seating.json) | Tech Lead snippet: Parse circular seating data from JSON in Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks repo—extracting context about people's orientations within circular tables. |

</details>

<details closed><summary>implementation_code.dataset.MultiArith</summary>

| File                                                                                                                                                                           | Summary                                                                                                                                                      |
| ---                                                                                                                                                                            | ---                                                                                                                                                          |
| [MultiArith.json](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/dataset/MultiArith/MultiArith.json) | Tech Lead: Code snippet in `MultiArith.json` enables zero-shot reasoning tasks. Crucial for logical & positional reasoning in the main project architecture. |

</details>

<details closed><summary>implementation_code.my_log</summary>

| File                                                                                                                                                                                               | Summary                                                                                                                                                                                                                                                                                                         |
| ---                                                                                                                                                                                                | ---                                                                                                                                                                                                                                                                                                             |
| [testing_seating.json](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/my_log/testing_seating.json)                       | The code snippet in `implementation_code/my_log/testing_seating.json` handles logical reasoning puzzles for seating arrangements. It assists in deriving correct answers based on given constraints, enhancing reasoning skills.                                                                                |
| [MultiArith.json](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/my_log/MultiArith.json)                                 | Code snippet in `my_log/MultiArith.json` manages prompt responses. Central to logical and positional reasoning tasks, supports zero-shot learning. Non-technical overview.                                                                                                                                      |
| [seating_arrangement.json](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/my_log/seating_arrangement.json)               | Code snippet at `implementation_code/my_log/seating_arrangement.json` organizes logical reasoning tasks with structured prompts, responses, and predictions to deduce relationships accurately. It enhances the parent repository's functionality by enabling seamless handling of complex reasoning scenarios. |
| [family_relationship_puzzle.json](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/master/implementation_code/my_log/family_relationship_puzzle.json) | Tech Lead role: Implementing logic for logical and positional reasoning tasks. Code snippet path: `implementation_code/`. Key features illustrate smart reasoning handling.                                                                                                                                     |

</details>

---

##  Getting Started

***Requirements***

Ensure you have the following dependencies installed on your system:

* **JSON**: `version x.y.z`

###  Installation

1. Clone the Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks repository:

```sh
git clone https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks
```

2. Change to the project directory:

```sh
cd Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks
```

3. Install the dependencies:

```sh
> INSERT-INSTALL-COMMANDS
```

###  Running Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks

Use the following command to run Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks:

```sh
> INSERT-RUN-COMMANDS
```

###  Tests

To execute tests, run:

```sh
> INSERT-TEST-COMMANDS
```

---

##  Project Roadmap

- [X] `► INSERT-TASK-1`
- [ ] `► INSERT-TASK-2`
- [ ] `► ...`

---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks/issues)**: Submit bugs found or log feature requests for Zero-shot-cot-on-logical-and-positional-reasoning-tasks.

<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/samyakmehta28/Zero-shot-CoT-on-Logical-and-Positional-Reasoning-Tasks
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
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

##  License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-quick-links)

---
