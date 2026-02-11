# Core-Design-Framewor

# 📐 The Design Protocols
*"Game Design is not just art; it is an engineering problem of balancing Logic, Mathematics, and Causality."*

🔍 OverviewThe Design Protocols is a collection of high-level architectural frameworks designed to solve three fundamental problems in modern game development: Artificial Intelligence Optimization, Player Retention Psychology, and Systemic World Consistency.Unlike traditional design documents, this repository treats game mechanics as reusable engineering modules, focusing on data-driven implementation and performance optimization suitable for AA/AAA development pipelines.📂 Repository StructureThis framework is structured to resemble a standard Unity Package architecture for easy integration.

# 📦 Core-Design-Framework
    ┣ 📂 Docs                           # Theoretical documentation & Whitepapers
    ┃ ┣ 📜 01_FuzzyLogicalMachine.md    # The Brain
    ┃ ┣ 📜 02_RabbitHoleInOne.md        # The Heart
    ┃ ┗ 📜 03_BinaryCausality.md        # The World
    ┃
    ┣ 📂 Runtime                        # Core C# Implementation
    ┃ ┣ 📂 FuzzyLogicalMachine          
    ┃ ┣ 📂 RabbitHoleInOne              
    ┃ ┗ 📂 BinaryCausalityEngine        
    ┃
    ┗ 📂 CaseStudies                    # Practical Applications (Prototypes)
      ┣ 📂 01_Boss_Multiplayer_Opt      # AI Implementation
      ┣ 📂 02_Tycoon_Progression        # Economy Balancing
      ┗ 📂 03_Vount_DarkFantasy_World   # Narrative Consistency

   
# 🧠 I. Fuzzy Logical Machine
Target: Adaptive AI, Performance Optimization, Dynamic Difficulty.
A lightweight AI architecture that replaces rigid boolean logic (True/False) with "Degrees of Truth". This system allows NPCs and Bosses to make more natural, human-like decisions based on vague inputs (e.g., "Player is somewhat far" vs "Player is very low HP").

Core Logic Visualization

<img width="1106" height="207" alt="image" src="https://github.com/user-attachments/assets/5a06beea-a897-4f0d-bfb0-7cd33b8ae6f9" />

    
- Key Benefit: Reduces state-machine complexity ("Spaghetti Code") and optimizes CPU usage by evaluating logic only when fuzzy thresholds are crossed. 

# 🕳️ II. The Rabbit Hole in One Algorithm
Target: Player Retention, Economy Balancing, Churn Prevention.
A mathematical approach to retention mechanics based on the Sunk Cost Fallacy and Variable Ratio Rewards. This algorithm calculates the "Immersion Score" to dynamically adjust loot drops and difficulty, ensuring players remain in the "Flow State."

**The Formula:**

$$Progress = \frac{Playtime(t)}{(Cost - Reward) - (Punishment \times \alpha)}$$

Where:
$\alpha$ represents the Player Resilience Factor.

As the denominator approaches zero (High Risk/High Cost), the perceived value of Progress increases exponentially, creating a "Rabbit Hole" effect that discourages quitting.

# ⚖️ III. The Binary Causality Engine
Target: World Building, Procedural Generation, Narrative Consistency.
A systemic framework where every entity in the game universe (Characters, Events, Items) is assigned a signed value (Black/Negative or White/Positive). The engine constantly monitors the World State Sum, triggering procedural events to force the universe back into a Zero-Sum Equilibrium.System BehaviorIf World State > +100 (Too White/Order): The Engine spawns "Chaos" events (Black entities) to restore balance.If World State < -100 (Too Black/Chaos): The Engine provides "Hope" or "Order" mechanics (White entities).Result: A narrative that feels alive and reactive, where every action has a mathematically guaranteed consequence.🛠️ Usage & IntegrationThis repository is designed as a reference for Technical Game Designers and System Architects.To test the algorithms:Clone this repository.Open the CaseStudies folder in Unity 2022.3 (LTS) or higher.Check the Runtime folder for the core C# scripts.👤 Author[Nama Kamu] Game Programmer & Technical Designer Certified Unity Associate | Focus on AI & SystemsLinkedIn | Portfolio
