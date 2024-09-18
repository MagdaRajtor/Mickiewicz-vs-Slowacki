# Mickiewicz-vs-Slowacki
Exploring Information Theory measures on Polish literature

After scraping, cleaning, unifying and sorting the complete body of works of Adam Mickiewicz and Juliusz Słowacki (from WolneLektury), I used the data to:
1. Compare entropy between literary genres (epic, drama, poetry and ballads)
2. Compare entropy between the authors
3. Estimate the information rate for Polish
4. Compare character- and word-level distributions of varied texts

For points 3. and 4. I added current entries from Polish Twitter (https://huggingface.co/datasets/clarin-pl/twitteremo) and Wikipedia (chrisociepa/wikipedia-pl-20230401 · Datasets at Hugging Face). Plots and tables are included in the presentation, with a deeper explanation provided in the report.

What I learned:
- matching data of different sources for reliable comparisons
- calculating and interpreting entropy measures
- utilizing simple n-order Markov models
- understanding and using Jensen-Shannon distance
- exploring and explaining data patterns from a new perspective
