## Audit 02: Deconstructing Statistical Lies

This audit examines how commonly reported metrics can misrepresent reality when distributions are skewed or biased.

First, I analyzed system latency data and showed that mean latency and standard deviation are misleading in the presence of rare but extreme tail events. Robust statistics such as the median and MAD better represent typical system performance.

Second, I demonstrated the false positive paradox using a plagiarism detection example. Even with high accuracy, low base rates lead to most flagged cases being false positives, highlighting why accuracy alone is insufficient for decision-making.

Finally, I simulated survivorship bias in crypto markets by modeling token launches using a heavy-tailed distribution. While surviving tokens appear highly successful, the average outcome across all launches is near zero. This shows how ignoring failures leads to inflated performance claims.
