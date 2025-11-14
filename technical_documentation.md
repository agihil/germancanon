# Technical and Methodological Documentation

## Additional Remarks Section III

## Additional Remarks Section IV.3
For change point detection, we use the Python package ruptures; for segmentation we apply the PELT algorithm (Pruned Exact Linear Time) and use rbf (Radial Basis Function) as the cost function. We start the penalty parameter—which controls how many change points are detected—at 1 and increase it by 1 until no change points appear anymore, which occurs at pen = 97. The three most frequently detected change points are at ranks 174, 114, and 285. Thus, there is some overlap with the method “Observed vs. expected percentage decrease” already introduced in the main text. However, it is important to note that the detected change points are not particularly robust with respect to the penalty parameter; the Jaccard similarity between all detected change-point sets averages only 0.42.

## Practical Remarks
All Analyses were carried out using Python.
