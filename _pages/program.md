---
title: "Program"
permalink: /program/
---

## Friday 27, June 2025. 11h00 to 13h00 (GMT+2). 

## Workshop Program (GMT+2)

| Time              | Session                                                                 |
|-------------------|-------------------------------------------------------------------------|
| 11h00 – 11h10     | **Welcome & Introduction**                                              |
|                   | Opening remarks and overview of the workshop program                    |
| 11h10 – 11h30     | **Paper: Multi-Agent Differential Testing for the Game of Go**          |
|                   | Jiaxue Song, Xiao-Yi Zhang, Paolo Arcaini, Fuyuki Ishikawa, Yong Liu, Bin Du |
| 11h30 – 11h35     | Q&A                                                                     |
| 11h35 – 11h55     | **Paper: Enhancing Emotional Realism in Games**                         |
|                   | Jonas de Araújo Luz Junior, Rafael Fonseca Pessoa, Guadalupe P. Saldanha Ribeiro, João Vitor Vieira Lira, Maria Andréia Formico Rodrigues |
| 11h55 – 12h00     | Q&A                                                                     |
| 12h00 – 12h20     | **Paper: Incorporating Multiple Self-Adaptive Agents in Games**         |
|                   | Steven Streasick, Erik Fredericks, Byron DeVries, Ira Woodring         |
| 12h20 – 12h25     | Q&A                                                                     |
| 12h25 – 13h00     | **Keynote: Jeremy Bradbury**                                             |
|                   | Professor of Computer Science, Ontario Tech University (Canada)         |
|  | **Closing** | 



## Keynote

**[Jeremy Bradbury](https://www.sqrlab.ca/)**

Professor of Computer Science, Ontario Tech University (Canada)
Director, Software Quality Research Lab (SQRL)

Jeremy Bradbury is a Professor of Computer Science at Ontario Tech University in Oshawa, Canada, where he leads the Software Quality Research Lab (SQRL). His research focuses on improving software quality through better development practices, testing tools, and education. He explores the use of machine learning for automating software testing and analysis, and he is a strong advocate for AI-powered personalized learning to support both computer science education and software developer retraining. His work bridges research and practice, aiming to make software engineering more robust, accessible, and intelligent.

## Accepted papers

### Multi-Agent Differential Testing for the Game of Go

- **Jiaxue Song**, Beijing University of Chemical Technology
- **Xiao-Yi Zhang**, University of Science and Technology Beijing
- **Paolo Arcaini**, National Institute of Informatics
- **Fuyuki Ishikawa**, National Institute of Informatics
- **Yong Liu**, Beijing University of Chemical Technology
- **Bin Du**, Beijing University of Chemical Technology

Artificial intelligent (AI) techniques have been successfully applied in various domains, especially in complex games like Go. Indeed, although Go has simple rules, it has countless variations of possible positions, making it an extremely difficult game. Therefore, it has been taken as a benchmark to assess the abilities of AI agents (called Go Agents). However, assessing the performance of the decision-making of a Go agent is challenging; indeed, since Go agents play much better than humans, it is difficult to establish intuitive rules or to rely on human experts to determine whether a Go agent's decision is correct or not. While professional players can do it, they can not evaluate too many moves. To tackle these issues, in this paper we propose a differential testing approach, called Multi-Agent Differential testing For the game of Go (MAD4Go), to identify interesting test cases in which a Go agent may perform a non-optimal move. Specifically, we play different Go agents over the same tests and we check whether they agree with each other. In case of disagreement, we assess the level of disagreement. If two agents strongly disagree with each other, it is more likely that at least one agent made a wrong decision. We conducted experiments by evaluating Go agents from Leela Zero, using as tests different Go positions obtained from real Go games of professional players. Results revealed diverse disagreements among agents, showing that MAD4Go can identify valuable test cases.

### Enhancing Emotional Realism in Games: An Optimized Generative AI Framework for Dynamic 3D Facial Animation

- **Jonas de Araújo Luz Junior**, Universidade de Fortaleza
- **Rafael Fonseca Pessoa**, Universidade de Fortaleza
- **Guadalupe P. Saldanha Ribeiro**, Universidade de Fortaleza
- **João Vitor Vieira Lira**, Universidade de Fortaleza
- **Maria Andréia Formico Rodrigues**, Universidade de Fortaleza

Facial expressiveness is essential for immersive gaming, yet generating emotionally responsive 3D characters remains challenging. This paper presents an optimized generative AI framework that integrates OpenAI’s LLMs with OpenFace to improve blendshape-AU mapping for dynamic facial animation. The system, embedded in an original game scene, generates facial expressions based on interactive player dialogues. From a software engineering perspective, it features modular, scalable AI-driven animation pipelines that support adaptive emotion modeling and game engine integration. User evaluations demonstrate high realism, clear emotion recognition, and strong engagement, confirming the system’s potential to enhance player interaction. Further refinements in blendshape mappings and real-time adjustments can enhance the differentiation of subtle emotions like Disgust and Contempt, improving the system’s overall expressiveness.

### Incorporating Multiple Self-Adaptive Agents in Games

- **Steven Streasick**, Grand Valley State University
- **Erik Fredericks**, Grand Valley State University
- **Byron DeVries**, Grand Valley State University
- **Ira Woodring**, Grand Valley State University

A self-adaptive system (SAS) is capable of modifying its behavior at run-time to address uncertainty. For games, these self-adaptations can present a more dynamic experience (e.g., changing difficulty, optimizing performance), thereby enabling run-time updates to mitigate potential issues experienced during gameplay. For example, a self-adaptation may result in emergent behaviors that keep the player engaged or optimize performance to support a multitude of device configurations. Notably, games that leverage a run-time feedback loop have previously demonstrated success in optimizing a game's frame rate. However, multi-agent systems that incorporate self-adaptation remain largely unexplored in the video games domain.  This paper demonstrates a novel approach for using multiple goal models with competing metrics for expressing optimal behavior in balancing and mitigating video game uncertainties. To support this goal, we adapt an existing browser-based game to a new framework that incorporates two distinct self-adaptive agents with potentially competing objectives.
