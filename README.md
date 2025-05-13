# Final-Year-Project-FYP-Machine-Learning-Implementation
---

## 📖 Overview
The core objective of this simulation is to provide a controlled environment in which the two agents—FSM and ML-based—compete under identical gameplay conditions. Both agents are tasked with scoring goals in the presence of a dynamic goalkeeper, using different decision-making frameworks.

FSM Agent: Operates on predefined conditional logic, transitioning between states like “Approach Ball”, “Align to Goal”, and “Shoot”.

RL Agent (PPO): Learns optimal policies through trial and error, using a reward system to improve performance over time.

---

## Purpose and Relevance

This simulation acts as a sandbox for evaluating the practical applications and trade-offs of different AI strategies in interactive digital environments. It is particularly relevant for:

- Game AI prototyping

- Reinforcement learning research

- AI performance benchmarking in constrained environments
  
---

## 🧠 Machine Learning Approach

- **Techniques Used**: Reinforcement learning, provided by Unity ML-Agents
- **Data Source**: Custom datasets based on environment as per reinforcement learning
- **Evaluation Metrics**: Shoot Attempts, Goal Keeper Save Count, elapsed time

---
## Flowchart and Design
<table>
  <tr>
    <td><img src="images/screenshots/Flowchart.png" alt="Flowchart" width="300"></td>
    <td><img src="images/screenshots/Design.png" alt="Design" width="300"></td>
  </tr>
</table>


## 📸 Screenshots

<table>
  <tr>
    <td><img src="images/screenshots/MainMenu.png" alt="Main Menu" width="400"></td>
    <td><img src="images/screenshots/EndScreen.png" alt="End Screen" width="400"></td>
  </tr>
  <tr>
    <td><img src="images/screenshots/InGame1.png" alt="In Game 1" width="400"></td>
    <td><img src="images/screenshots/InGame2.png" alt="In Game 2" width="400"></td>
  </tr>
</table>

---
## 📈 Learning Curves

<table>
  <tr>
    <td><img src="images/learning_curves/goal_scoring.png" alt="Goal Scoring Curve" width="400"></td>
    <td><img src="images/learning_curves/ball_possession.png" alt="Ball Possession Curve" width="400"></td>
  </tr>
  <tr>
    <td colspan="2"><img src="images/learning_curves/positioning.png" alt="Positioning Curve" width="400"></td>
  </tr>
</table>

---

## 🧪 Results

<table>
  <tr>
    <td><img src="images/results/result_1.png" alt="Result 1" width="500"></td>
    <td><img src="images/results/result_2.png" alt="Result 2" width="500"></td>
  </tr>
  <tr>
    <td colspan="2"><img src="images/results/result_3.png" alt="Result 3" width="300"></td>
    <td colspan="2"><img src="images/results/result_4.png" alt="Result 4" width="300"></td>
  </tr>
</table>

---

## 🎥 Demo Video

<p>Watch the full simulation demo here:</p>

<a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID" target="_blank">
</a>

<p><i>Click the image above to watch on YouTube.</i></p>


## ⚙️ Tech Stack

- **Game Engine**: Unity 2022.3.17f1
- **Programming Language**: C#
- **ML Libraries**: TensorFlow / PyTorch / Scikit-learn 
- **Tools**: Conda / Unity ML-Agents
