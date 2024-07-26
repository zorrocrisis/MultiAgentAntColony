# **Multi-agent System based on an Ant Colony Behavior**
This project, originally an evaluation component for the Autonomous Agents and Multi-Agent Systems (AAMAS) course (2023/2024), talking place in Instituto Superior Técnico, University of Lisbon, aimed to establish **a multi-agent environment based on the natural behavior of ants**. More specifically, the goal was to simulate an ant colony with multiple ants (agents) whose goals are to search for food (points of interest). By analyzing how
these **agents indirectly communicate through pheromones and cooperatively define the best paths to travel between the food and the colony** (home base), we **gain insights on how we can transfer this algorithm to real-life applications**.

<p align="center">
  <img src="https://github.com/user-attachments/assets/bb905197-ad43-483c-a50e-878c030a734d" />
</p>

The following document indicates how to access the source code and control the corresponding program. It also details the implementation's main features, referring to the official report for more detailed information.

## **Quick Start**

1. Clone the repo or download the source code
    $ git clone https://github.com/zorrocrisis/MultiAgentAntColony
    $ cd MultiAgentAntColony

1. Create virtual environment (tested with python 3.8.10)
    $ python3 -m venv venv
    $ source venv/bin/activate

3. Install dependencies
    $ pip install -r requirements.txt

4. Run the project
    $ cd Project
    $ python3 multi_agent_teams.py

5. (Optional) Fiddle and play with the values and the teams being tested in the multi_agents_teams.py
    $ To view the ants moving around, uncommment lines 90 and 91
    $ To change the teams, change the run_multi_agent function accordingly and the n_agents in the environment definition in main, this if you decide to add more agents to the teams
    $ You can also change other aspects of the environment in main (e.g.: the number of foodpiles)

## **Features**


## **Final Remarks**
As a closing remark, one could say the **FAtiMA-Toolkit undoubtedly facilitates the creation of interactive moments and emotionally intelligent agents, despite there being a multitude of different approaches and interpretations as to how these agents can/should be implemented**.

As also aforementioned, the project allowed the exploration of two distinct ways of managing emotional dialogues - **mood-dependent** and **mood-independent** -, both proving to have considerable advantages and disadvantages. We can state the dimension of the project at hand can have a heavy influence on what approach to utilise - where **the mood-independent approach requires more attention to the overall structure of the story**, **the mood-dependent relies on a simple “rule-of-thumb” that is more appropriate for less in-depth and quick storytelling**.

Lastly, it’s clear to see how a fully explored and long-term conjunction between a Unity scene and the FAtiMA’s toolkit can lead to an immersive experience like no other, bridging the gap between storytelling and gameplay systems.

## **Additional Information**
For more information about this project, you can read the final report here. This documents contains 
  
## **Authors and Acknowledgements**

This project was developed by **[Miguel Belbute (zorrocrisis)](https://github.com/zorrocrisis)**, **[Carolina Brás](https://github.com/carolinabras)** and **[Guilherme Pereira](https://github.com/the-Kob)**.

The initial code was supplied by **[Prof. Rui Prada](https://fenix.tecnico.ulisboa.pt/homepage/ist32219)**.
