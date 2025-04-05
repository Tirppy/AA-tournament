# Adapt_Exploit Strategy

A dynamic strategy for the Prisoner's Dilemma tournament that combines adaptive behavior with strategic exploitation.

## Algorithm Overview

This algorithm analyzes the opponent's cooperation patterns and adjusts its behavior accordingly:

- Initially cooperates to establish goodwill
- Evaluates overall cooperation rate and recent behavior patterns
- Exploits highly cooperative opponents with occasional defection
- Responds proportionally to moderately cooperative opponents
- Primarily defects against uncooperative opponents with occasional cooperation
- Detects and responds to specific patterns (like alternating behaviors)
- Switches to defection in end-game scenarios

The strategy balances between rewarding cooperation and punishing defection while incorporating pattern recognition and strategic timing elements to maximize points.
