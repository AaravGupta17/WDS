# WDS


# Findings
# Overtime
- **Phillipines** : Good at defense , not so good offense , wins most of their games in overtime , they basically take their games to ot and then try to win.
1. The "Pure" Juggernauts (Low Deception Gap)Brazil ($0.707 \rightarrow 0.621$) and Thailand ($0.609 \rightarrow 0.536$).The Insight: These teams are the most dangerous. They finish games in 60 minutes. Their standing isn't "padded" by the high-variance 3-on-3 or Shootout.Wharton Value: In a playoff simulation (where games are 5-on-5), these teams are your statistical favorites because their success is rooted in sustainable, regulation play.


2. The "Paper Tigers" (High Deception Gap)Peru ($0.634 \rightarrow 0.463$) and UAE ($0.463 \rightarrow 0.268$).The Insight: These teams are "frauds" in the context of power rankings. UAE loses nearly 20% of their win value when you remove OT.The Argument: They likely have a specific skill (like a great shootout goalie or a fast 3-on-3 duo) that won't translate to long-term 5-on-5 dominance.Ranking Action: We must penalize these teams. They are currently "over-ranked" by standard standings.


3. The "Hidden Gems" (The Resilience Metric)Look at teams with a low win_pct but a high resilience_factor (which we calculated in the previous step).The Insight: These teams are "Hard Outs." Even though they are losing, they are forcing elite teams into OT.Wharton Value: This proves that "Total Points" is a lagging indicator. A team like Serbia or Germany might actually be "stronger" defensively than a team like Peru, even though they have fewer points.

reg_win: Dominance (won within 60 minutes).

ot_win: High Variance (won in 3v3 or Shootout).

ot_loss: Resilience (lost, but forced the opponent to extra time).

reg_loss: Failure (unable to stay competitive for 60 minutes).


Deception Gap: The difference between a team's official win rate and their regulation win rate. A high gap means a team is "padded" by OT points.

Corsi For %: A measure of puck possession based on shot volume. In hockey, if you have a high Corsi, you are driving the play.

Usage Normalization (Per 60): It adjusts xG (Expected Goals) based on total_minutes. This ensures that teams playing many OTs don't have "inflated" stats just because they spent more time on the ice.

Fagitue ratio is of no use 
* the pattern clearly visible is first off of each team is fatigued
