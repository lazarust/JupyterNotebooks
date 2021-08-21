# Pokémon Statistical Analysis
___Dataset:___ https://www.kaggle.com/abcsds/pokemon

**Check out the [Jupyter Notebook](./notebook.ipynb) to see better versions of the charts and code!**

## The Idea
The purpose of this project is to experiment with some Exploratory data analysis with some Pokèmon statistics.
In this notebook I will frequently use the abbreviation "gen" when referring to "generation".

## Exploratory Charts Per Generation

<details>
  <summary>Generation 1</summary>

  ![](./images/gen_1/gen_1_charts.jpg)
  ![](./images/gen_1/gen_1_count.jpg)
</details>

<details>
  <summary>Generation 2</summary>

  ![](./images/gen_2/gen_2_charts.jpg)
  ![](./images/gen_2/gen_2_counts.jpg)
</details>

<details>
  <summary>Generation 3</summary>

  ![](./images/gen_3/gen_3_charts.jpg)
  ![](./images/gen_3/gen_3_counts.jpg)
</details>

<details>
  <summary>Generation 4</summary>

  ![](./images/gen_4/gen_4_charts.jpg)
  ![](./images/gen_4/gen_4_counts.jpg)
</details>

<details>
  <summary>Generation 5</summary>

  ![](./images/gen_5/gen_5_charts.jpg)
  ![](./images/gen_5/gen_5_counts.jpg)
</details>

<details>
  <summary>Generation 6</summary>

  ![](./images/gen_6/gen_6_charts.jpg)
  ![](./images/gen_6/gen_6_counts.jpg)
</details>

From the general shape of these charts we can start to see that between generations there do seem to be some general patterns.

## Exploratory Charts Cross Generation

<details>
  <summary>Attack Comparison</summary>

  ![](./images/attack_compare.jpg)
  ![](./images/attack_means.jpg)
</details>

<details>
  <summary>Defense Comparison</summary>

  ![](./images/defense_compare.jpg)
  ![](./images/defense_means.jpg)
</details>

<details>
  <summary>HP Comparison</summary>

  ![](./images/hp_compare.jpg)
  ![](./images/hp_means.jpg)
</details>

<details>
  <summary>Speed Comparison</summary>

  ![](./images/speed_compare.jpg)
  ![](./images/speed_means.jpg)
</details>

When comparing the histogram charts of different Pokèmon stats you can notice a strange behavior that Gens 1, 3, and 5 have
similar distributions and 2, 4, and 6 have similar distributions. This is interesting because it also looks like Gen 1, 3, and
5 have a higher top bin than on most stats. This would mean that more of the Pokèmon have lower stats, but the max
stats for the generation are higher.

For Gens 2, 4, and 6 we can notice that the distribution is more even throughout the stats but the max stats for these gens
are lower than the other generations.

Now I want to compare the mean stats for each generation.

Also, from the above charts were I compared the mean of each stat per generation we can see that there isn't as much
of a pattern as we saw with the histograms. This shows that even though the histograms are off that there are
just a few outliers in each generation but the majority of Pokèmon have similar stats across generations.


This next chart is going to look a little crazy but stick with me.

![](./images/type_per_gen.jpg)
![](./images/type_per_gen_legend.png)

I warned you this chart was going to look a little crazy, but we can notice some interesting things from this chart.
We notice the same correlation pattern between Gens 1, 3, and 5 having, in some cases significantly, more Pokèmon
than the other generations. Knowing this, we can revisit some of the earlier charts we generated with a little more
context.


## Conclusion

In this project I looked at how to visualize different data from the Pokémon stats dataset. I really wanted
to focus on gaining some experience with the matplotlib library and working with panda's DataFrames.

To see some of my experiments with Classification and Clustering using the sklearn library checkout the JupyterNotebook!
