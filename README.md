# 23F-3067-and-24F-3115_Oop-Lab-Final-Project-Phase2.
A turn-based strategy game where two kingdoms compete for dominance through military might, diplomacy, and resource management.

 Features

- **Two Unique Kingdoms**: Play as either the Alpha or Beta kingdom, each with their own strengths
- **Turn-Based Strategy**: Manage your kingdom's resources and make strategic decisions each turn
- **Multiple Game Systems**:
  - Military combat with army recruitment and battles
  - Diplomatic alliances and betrayals
  - Resource trading and smuggling
  - Kingdom movement on a tactical map
- **Colorful Console Interface**: Uses ANSI colors for an engaging text-based experience

 How to Play

1. **Compile and run** the C++ program
2. **Manage your kingdom** each turn by:
   - Recruiting soldiers to strengthen your army
   - Trading or smuggling resources with the other kingdom
   - Forming or breaking alliances
3. **Engage in combat** to weaken your opponent
4. **Move your kingdom** on the tactical map
5. **End your turn** to collect taxes and continue the game

 Game Mechanics

- **Resources**: Gold is used to recruit soldiers (2 gold per soldier)
- **Combat**: Battles have random elements but favor stronger armies
- **Alliances**: Prevent attacks between kingdoms but can be broken
- **Map Movement**: Position your kingdom strategically on the 5x5 grid

 Requirements

- C++ compiler with C++11 support
- Terminal that supports ANSI color codes (most modern terminals do)

 Building and Running

```bash
g++ -std=c++11 kingdom_conquest.cpp -o kingdom_conquest
./kingdom_conquest
```

 Screenshots

![Gameplay Screenshot](https://via.placeholder.com/600x400?text=Gameplay+Screenshot)
 Future Improvements

- More kingdoms and larger map
- Additional resources and buildings
- Special units and technologies
- Save/load game functionality
