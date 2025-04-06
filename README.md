# Adapt Exploit Strategy

A dynamic strategy for the Prisoner's Dilemma tournament that adapts based on opponent behavior patterns.

## How It Works

This algorithm:
- Starts by cooperating
- Analyzes the opponent's overall cooperation rate and recent behavior
- Responds generously to highly cooperative opponents (>80% cooperation)
- Uses conditional cooperation with moderately cooperative opponents
- Punishes defectors while occasionally testing for cooperation
- Recognizes specific patterns like alternating behavior
- Implements an end-game defection strategy in the final rounds

The strategy balances exploitation of naive cooperators while maintaining cooperation with other reciprocating strategies, adapting its approach based on the opponent's history rather than using a fixed response pattern.
