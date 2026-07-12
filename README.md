Financial markets are highly noisy and unpredictable. Trading strategies are required to simultaneously

account for short-term price fluctuations and long-term structural regimes. Furthermore, developing

a quantitative system that balances multiple conflicting objectives, such as maximizing profit while

minimizing downside risk, according to shifting preferences remains a significant challenge. To address

these limitations, we propose an adaptive trading framework that integrates a Deep Residual Network

(DRN) with a single multi-objective Reinforcement Learning (RL) model. Operating over raw technical

indicators, our DRN architecture utilizes residual skip connections to impose a structured, nonlinear

geometric transformation on the raw technical indicator matrix, producing stable 32-dimensional latent

embeddings that are held fixed throughout the reinforcement learning optimization phase. Rather than

training a computationally heavy concatenation of multiple discrete RL networks, our system trains a

single unified agent directly on dynamic objective sets to learn the continuous relationship between different

preference combinations and the fixed DRN market representations. Experimental evaluation across eight

random-seed runs is used to characterize both preference sensitivity and initialization sensitivity, avoiding

conclusions based on a single trained realization.
