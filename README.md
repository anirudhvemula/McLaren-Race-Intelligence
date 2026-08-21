GOOGLE CLOUD LABS: ONAIR
# Build an AI-Powered F1 Analytics Agent with McLaren Racing

In this <b> Intermediate-level Lab </b>, you will build a multi-tiered McLaren Racing analytics agent using Gemini Enterprise and the ADK to programmatically query over 70 years of F1 data, run ML predictions, and generate custom visualisations in BigQuery.

This fascinating Lab is now available to watch on demand. Throughout, you'll experience firsthand why data architecture — not model selection — determines what your AI can do.

## [Build an AI-Powered F1 Analytics Agent with McLaren Racing](https://cloudonair.withgoogle.com/events/aug2026-loa-agent-mclaren)


1. Build a data foundation in BigQuery with 70+ years of F1 race history, analytical views designed for AI-generated SQL, and a live-trained BQML podium prediction model
2. Configure Gemini Enterprise with FIA regulation data stores and learn why source provenance — knowing where an answer came from — matters as much as the answer itself
3. Build purpose-built agents in Agent Designer — a regulation Q&A expert and a multi-agent race briefing system — without writing a line of code
4. Develop a programmatic ADK agent that queries BigQuery, runs ML inference, and generates on-brand visualisations through a multi-agent architecture

You may also wish to continue with the following optional tasks:
1. Deploy your ADK agent to Agent Runtime for managed, scalable hosting
2. Surface the deployed agent in Gemini Enterprise to create a unified platform across all three tiers

Agents output:
### Prompt: What is McLaren's podium rate at Monaco across all time?
Response: <br>
McLaren has an all-time podium rate of 27.3% at the Circuit de Monaco.

<br><br>
### Prompt: What was Oscar Piastri's predicted podium probability at the 2024 Monaco Grand Prix, and did the model get it right?
Response: <br>
For the 2024 Monaco Grand Prix, the BQML podium prediction model gave Oscar Piastri a 50.2% probability of finishing on the podium.

Did the model get it right? Yes. Piastri started from P2 and finished the race in 2nd place, securing the podium. The model correctly classified this as a "Correct Podium" prediction.

It is worth noting that for the same race, the model also predicted a podium for Lando Norris with a slightly higher probability (50.5%), though Norris ultimately finished just off the podium in 4th place.

<br><br>
### Prompt: Show me a chart of McLaren's championship points progression through the 2024 season.
Response: <br>
<img width="2000" height="1200" alt="chart-01" src="https://github.com/user-attachments/assets/ea1a7cd4-6f6f-4f6a-bcce-9739fc8ba423" />

The chart above illustrates McLaren's championship points progression through the 2024 season.

Starting from 12 points after the opening round in Bahrain, the team showed a remarkably consistent upward trajectory, finishing the 24-round season with a total of 666 points. Notable jumps in the progression can be seen around the mid-season European stretch (rounds 7-14) and the final triple-header, reflecting McLaren's sustained competitiveness throughout the year.

<br><br>
### Prompt: Compare Norris and Piastri's average finishing positions in 2024, then show me a bar chart of their head-to-head results.
Response: <br>
In 2024, Lando Norris held a slight edge over Oscar Piastri in terms of average finishing position, though both drivers delivered a highly competitive season.

Season Averages
Lando Norris: 4.29 average finish (Best: 1st)
Oscar Piastri: 5.13 average finish (Best: 1st)
Head-to-Head Comparison
Across the 24 races of the 2024 season:

Lando Norris finished ahead of Piastri 16 times.
Oscar Piastri finished ahead of Norris 8 times.
The visual below illustrates their race-by-race finishes. Note that the Y-axis is inverted so that higher bars represent better (lower) finishing positions.

{norris_vs_piastri_2024_finishes.png}

Both drivers showcased championship-level consistency, with Norris frequently occupying the podium and Piastri securing crucial wins in Hungary and Azerbaijan. The data highlights a strong intra-team dynamic that fueled McLaren's successful 2024 campaign.

<img width="2800" height="1400" alt="chart-03" src="https://github.com/user-attachments/assets/68f5b740-2880-4ab1-994d-9e16c1214eb2" />


