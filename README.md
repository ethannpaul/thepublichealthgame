# Public Health Command Center
An interactive educational game that puts you in the role of a public health official responding to real world crises. Make decisions about disease outbreaks, environmental emergencies, health equity challenges, and pandemic preparedness - then get scored on how well your response matches evidence-based best practices.

Play it now: https://thepublichealthgame.com
## How It Works
You're presented with a public health scenario - anything from a cholera outbreak in Sub-Saharan Africa to a wildfire smoke emergency in a megacity to an ethical dilemma about AI-powered disease surveillance. You type your response as the health official in charge, and the game scores you based on how many key concepts and best practices you address.

## Game Modes
* Arcade - Random scenarios, streak-based scoring, quick rounds
* Campaign - Progress through four difficulty tiers (Easy → Medium → Hard → Realistic), unlocking harder levels as you prove your skills
* World - Explore a D3.js interactive world map with country-specific health scenarios across 101 countries
* Daily Challenge - One scenario per day, shared across all players

## Difficulty Levels
* Easy - Core public health fundamentals (vaccination campaigns, water contamination, food safety, disease basics)
* Medium - Multi-factor problems requiring systems thinking (TB in overcrowded settlements, antimicrobial resistance, maternal mortality, refugee health)
* Hard - Complex scenarios with competing priorities, ethical tensions, and incomplete information (Ebola response, drug-resistant malaria containment, pandemic vaccine allocation)
* Realistic - No clean answers. Political resistance, resource constraints, collapsing health systems, and converging crises that mirror what real public health officials face

## Scenarios
46 research-backed scenarios covering global public health, built with current WHO data and epidemiological evidence:
* Infectious disease - Cholera, dengue, malaria, TB, Ebola, Marburg, measles, mpox, H5N1, antimicrobial resistance
* Environmental health - Air pollution, lead contamination, PFAS chemicals, wildfire smoke, climate adaptation, chemical disasters
* Health equity - Maternal mortality disparities, food deserts, life expectancy gaps, refugee health, converging epidemics
* Emergency response - Typhoons, pandemics, bioterrorism, healthcare system collapse, conflict zones
* Ethics and policy - Compulsory isolation, AI surveillance tools, vaccine prioritisation, pandemic fatigue, whistleblower dilemmas
Scenarios span Sub-Saharan Africa, South and Southeast Asia, East Africa, the Greater Mekong, the Middle East, and more.

## Tech Stack
* Vanilla HTML/CSS/JS (no framework dependencies)
* D3.js for the interactive world map
* Firebase Realtime Database for authentication, progress saving, and leaderboards
* Hosted on Netlify

## Scoring
The keyword-based scoring engine evaluates your free-text response against weighted concepts. Each scenario has 5-7 key concepts (e.g., "Establish oral rehydration points," "Safe and dignified burial practices") with associated keywords and importance weights. Longer, more thorough responses earn bonus points. You get a percentage score and detailed feedback showing which concepts you hit and which you missed, along with an ideal response for learning.
