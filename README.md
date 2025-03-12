# Unity RL

A repository for creating Unity environments to integrate with Gymnasium for reinforcement learning.

## Project Overview

This project aims to develop Unity-based environments that can be used with Gymnasium, a toolkit for developing and comparing reinforcement learning algorithms. The goal is to provide a seamless integration between Unity's powerful simulation capabilities and Gymnasium's reinforcement learning framework.

## Installation

To get started, you'll need to have Unity installed on your machine. You can download it from the [Unity website](https://unity.com/).

Additionally, you'll need to set up Gymnasium. You can install it via pip:

```bash
pip install gymnasium
```

## Environment Setup

1. **Create a Conda Environment**: Create a new Conda environment with a compatible Python version.

   ```bash
   conda create --name unity-ml python=3.10.12
   conda activate unity-ml
   ```

2. **Install Required Packages**: Install the necessary packages for ML-Agents and Gymnasium.

   ```bash
   pip install mlagents==0.30.0 gym-unity==0.28.0 gymnasium
   ```

3. **Clone the ML-Agents Repository**: Get access to the pre-built environments.

   ```bash
   git clone https://github.com/Unity-Technologies/ml-agents.git
   cd ml-agents
   ```

4. **Install ML-Agents Environments**: Navigate to the `ml-agents-envs` directory and install the package.

   ```bash
   cd ml-agents-envs
   pip install .
   ```

5. **Install ML-Agents**: Navigate back to the `ml-agents` directory and install the package.

   ```bash
   cd ../ml-agents
   python -m pip install .
   ```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/JovannyReb/Unity-RL.git
   ```
2. Open the Unity project in the Unity Editor.
3. Follow the instructions in the project to set up and run the environments.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
