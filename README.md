# Decoding Dilemmas

Welcome to Decoding Dilemmas! This project is all about understanding a cool game called the Iterated Prisoner's Dilemma (IPD). It's like a game where two friends have to decide whether to work together or be selfish.

## Understanding the Game
In the IPD game, players play many rounds. They can either choose to work together (cooperate) or be selfish (defect). Depending on what both players choose, they get different points:
- If both cooperate, they both get some points.
- If one cooperates and the other defects, the defector gets more points, and the cooperator gets fewer.
- If both defect, they both get the fewest points.

## Our Approach: RL Q-Learning
To help understand how to play this game better, we're using a smart computer method called Reinforcement Learning (RL) with a technique called Q-learning. The computer learns the best strategies by trying different things and seeing what works best over time.

## Running the Project:

1. **Clone the Repository:**
   Clone the project repository to your local machine using the following command:
   ```
   git clone <repository-url>
   ```

2. **Navigate to the Project Directory:**
   Move into the directory of the cloned repository using the `cd` command:
   ```
   cd prisoner-dilemma-project
   ```

3. **Install Dependencies:**
   Ensure you have Python installed on your system. Then, install the required dependencies by running:
   ```
   pip install -r requirements.txt
   ```

4. **Run the Code:**
   There are two main scripts in the project: `prisoners_dilemma.py` and `prisoners_dilemma_testing.py`.
   
   - To run the training phase of the project, execute the following command:
     ```
     python prisoners_dilemma.py
     ```
   
   - To run the testing phase of the project, execute the following command:
     ```
     python prisoners_dilemma_testing.py
     ```

5. **Interact with the Program:**
   - During the training phase, you can observe the progress of the AI agents as they learn to play the Prisoner's Dilemma game.
   - During the testing phase, you can observe the performance of the trained AI agents against various testing scenarios.

6. **Explore the Results:**
   After running the code, you can explore the results, which may include visualizations of agent performance and analysis of outcomes.

7. **Adjust Parameters (Optional):**
   If desired, you can adjust the parameters in the configuration section of the code files to customize the behavior of the AI agents or the experiment setup.

8. **Contribute (Optional):**
   If you're interested in contributing to the project, feel free to fork the repository, make your changes, and submit a pull request with your improvements or bug fixes.




> Ready to try it out? Click the button below to download the code and get started!

[![Download](https://img.shields.io/badge/Download-Code-green?style=for-the-badge&logo=github)](https://github.com/captain-khuman/Decoding-Dilemmas/archive/refs/heads/main.zip)
