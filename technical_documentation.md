# Technical and Methodological Documentation

## Additional Remarks Section III
In the robustness analysis, Spearman’s rank correlation between the calculation variant we used and all alternative variants (Min-Max scaling, different weighting of the indicators, etc.) is always at least 0.75. Only the variant “Min-Max scaling and median” shows a weaker correlation (r(s) = 0.65), which is mainly due to shifts among the many less canonical authors, whose scores are very close to each other anyway. Considering only the 100 most canonical authors, the correlation with this alternative variant increases to 0.97. See the notebook for further details.

## Additional Remarks Section IV.3
For change point detection, we use the Python package *ruptures*. For segmentation we apply the PELT algorithm (Pruned Exact Linear Time) and use rbf (Radial Basis Function) as the cost function. We start the penalty parameter—which controls how many change points are detected—at 1 and increase it by 1 until no further change points appear, which occurs at pen = 97. The three most frequently detected change points are at ranks 174, 114, and 285. Thus, there is some overlap with the method “Observed vs. expected percentage decrease” already introduced in the main text. However, it is important to note that the detected change points are not particularly robust with respect to the penalty parameter; the Jaccard similarity between all detected change-point sets averages only 0.42. See the notebook for further details.

## Practical Remarks
All Analyses were carried out using Python.
