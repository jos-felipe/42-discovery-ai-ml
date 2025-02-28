# 42 Discovery Piscine: AI/ML Modules

This repository contains all projects completed during the 42 Discovery Piscine for Artificial Intelligence and Machine Learning. The piscine is divided into four modules, each exploring different aspects of AI and ML.

## Module 0: Expert Systems

An introduction to basic AI concepts through a temperature control expert system. The project simulates an environment with changing temperatures and implements a rule-based expert system to maintain indoor temperature within a comfortable range.

- [Module 0 Details](./module0/README.md)

## Module 1: Game Theory and Algorithms

Implementation of an 8-puzzle solver using breadth-first search algorithm. The project includes both a basic solver that finds any valid solution and an advanced solver that finds the shortest possible solution path.

- [Module 1 Details](./module1/README.md)

## Module 2: API Integration

A weather information system that demonstrates API integration. The project progresses from basic weather data retrieval to a complete conversational chatbot that can answer weather-related questions by combining WeatherAPI data with Groq AI for natural language processing.

- [Module 2 Details](./module2/README.md)

## Module 3: Genetic Algorithms

Implementation of a genetic algorithm for optimizing antenna frequency settings to improve cellular reception across multiple locations. This project demonstrates evolutionary algorithms and their application in solving complex optimization problems.

- [Module 3 Details](./module3/README.md)

## Getting Started

Each module has its own README with specific setup instructions, but general prerequisites include:

- Python 3.8 or higher
- Various Python libraries (specified in each module's requirements.txt)

## Repository Structure

```
.
├── module0/              # Expert System Project
│   ├── environment.py    # Environment simulator
│   └── expert_system.py  # Rule-based expert system
│
├── module1/              # 8-Puzzle Solver
│   ├── ex00/             # Basic solver
│   └── ex01/             # Advanced solver
│
├── module2/              # Weather Information System
│   ├── ex00/             # API setup and testing
│   ├── ex01/             # Weather by coordinates
│   ├── ex02/             # Weather by location name
│   └── ex03/             # Weather chatbot
│
└── module3/              # Genetic Algorithm
    └── ex00/             # Antenna frequency optimization
```

## License

This project is part of the educational curriculum at 42 School.

## Author

- josfelip@student.42sp.org.br