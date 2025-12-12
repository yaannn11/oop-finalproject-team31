# oop-finalproject-team31
## 1.Project overview
   ### 1.Part1--Install and Run  
   ### 2.Part2--Frozen Lake Reinforcement Learning  
   Revise the sample code to achieve a **consistent success rate > 0.70**
   ### 3.Part3--Warehouse_robot
  This project implements a warehouse robot navigation system.
  We designed a custom Gymnasium environment where a robot must avoid obstacles, detect shelves, and reach the goal efficiently.
  The program includes an agent class, environment class, training script, and demo script.
  This project was developed emphasizing OOP principles such as inheritance, encapsulation, and polymorphism.
## 2.Dependencies
-Python 3.8 – 3.12   
-gymnasium   
-numpy  
## 3.How to run?
  ### Install Dependencies
  1.Install Python 3.8–3.12 from the official website.  
  2.Install required dependencies:  
  ```bash
  pip install gymnasium numpy  
  ```  
  3.Test Gym installation:  
  ```bash
  python
  >>> import gymnasium as gym
  >>> env = gym.make("warehouse-robot-v0")
  >>> env.reset()
  ```
  ### Run Frozen Lake Training
  ```bash
  python frozen_lake.py
  ```
  ### Run Custom Project
  ```bash
  python train_warehouse.py
  python demo_trained_agent.py
  ```
## 4.Team Contribution List
|Member|Student ID|Contribution|
|------|----------|------------|
|潘冠仁|B123040047|Frozen Lake,training,parameter turning,evaluation|
|邱子庭|B123040029|Agent implementation,training loop,core logic|
|陳彥伃|I143040017|UML,documentation,README,code refactor,logger/utils|
