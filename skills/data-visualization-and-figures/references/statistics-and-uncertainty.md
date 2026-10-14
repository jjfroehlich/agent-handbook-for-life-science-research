# Observations, summaries and uncertainty

Read this when choosing distribution layers, displaying an effect or interpreting replication. Resolve what is measured and compared before deciding how much ink each layer receives.

## What should the reader compare?

Separate three jobs: describe the observed sample, estimate a population quantity, or estimate a contrast. A median tick can describe four observations without claiming a precise population median. An effect claim needs the actual contrast; overlap of two group intervals is not an interval for their difference. A mean remains a valid target for skewed data when the scientific question concerns the mean. Do not replace it automatically with a median because the distribution is nonnormal.

Name each mark and interval. Standard deviation describes spread; standard error concerns an estimator's sampling variability; a confidence interval concerns an estimation procedure; a prediction interval concerns a future observation under a model. Quartiles and boxplot whiskers are not confidence intervals. Show the magnitude and relevant uncertainty ahead of significance stars. Never manufacture an interval from a few summary values without a justified method.

## Choose useful layers, group by group

For an ordinary comparison of continuous groups, consider a quiet violin for shape, a narrow box for median/quartiles and small circular observations. This is a useful candidate, not a required three-layer template. Make the center readily visible when central tendency is the comparison. Add or substitute a clearly identified mean if that is the estimand.

- With few observations, show them all. A median or mean can remain useful; omit an unsupported smooth density for that group. A sparse group need not force removal of boxes or violins from better-supported groups.
- With many observations, a box plus density can be clearer than thousands of dots. Binning, an empirical cumulative distribution or another distribution display may serve the task better. If points are sampled, disclose sampling and use the full data for summaries.
- With ties, boundaries or multiple modes, inspect the density bandwidth and support. Smooth tails must not imply impossible values. No universal sample-size threshold guarantees a trustworthy violin.
- State the box/whisker convention, group sizes and violin width normalization. Equal maximum width, equal area and width proportional to count answer different questions. Equal-width violins do not imply equal evidence.

Keep layers subordinate to the comparison: light fills, thin boundaries and unobscured center marks. Jitter is display displacement, not measured variation along the categorical axis. Preserve reproducible jitter when comparing versions.

Hollow circles can clarify moderate single-category overlap, but accumulated outlines are not a computed density and filled marks can separate objects better. Transparency eventually saturates in dense regions; binned counts or density can then represent frequency more faithfully. Check that contours or additional layers do not create new clutter.

Changed condition: groups of 4, 24 and 48 observations can use points plus a center for the first and box/violin/points for the others. With 1,500–2,500 observations per group, density plus a box can convey more than an opaque point cloud. Neither case requires abandoning summaries.

## Identify the independent unit and weighting

Determine how units were sampled or assigned. Cells within a culture, fields within an image and repeated measurements within an animal are not automatically independent replicates. Show lower-level variation when useful, alongside the culture/animal/sample structure that supports the intended inference. Individually randomized cells could be units in another design; the biological label alone does not settle independence. A different acquisition day is not automatically a biological replicate.

Unequal numbers of cells per culture change the weighting: a pooled-cell mean weights cultures by their cell counts, whereas a mean of culture means weights cultures equally. State which quantity is intended. A plot cannot repair an analysis that uses the wrong unit. Do not invent pairing, missing identifiers, randomization or hierarchical estimates.

For genuine pairing, preserve identities with connecting lines, aligned paired points or within-unit differences. The median of paired differences need not equal the difference of marginal medians. When there is no pairing, a connecting line falsely suggests it. A factorial layout helps reveal interactions but does not itself fit an interaction model.

## Estimation and model displays

Use compatible estimates and uncertainty methods. Bootstrap the appropriate independent unit or hierarchy; more bootstrap iterations do not make the data normal, and a bias-corrected interval is not simply the central percentiles of the plotted bootstrap values. Distinguish uncertainty in a fitted mean from prediction uncertainty and distinguish pointwise bands from simultaneous coverage. If the available data do not support the requested uncertainty, show the descriptive information and explain the missing requirement.

Keep observed data distinct from fitted, smoothed or predicted values. Label transformations, exclusions and extrapolation. Outliers can matter scientifically; do not omit them to improve appearance. A change in scale or a detail panel must retain enough context to prevent exaggeration.

A bootstrap distribution approximates an estimator's sampling behavior under its resampling scheme; a permutation distribution represents a specified null randomization. They are not interchangeable clouds of uncertainty. Choose a compact labeled interval when that answers the question. A density with an interval overlay, quantile dots or a frequency display can reveal shape or make probability more concrete, but requires a clear denominator and explanation. More dots add granularity and complexity. Plausible-outcome displays must reflect the underlying uncertainty rather than an arbitrary short sample. A frequentist confidence interval describes repeated-procedure coverage, not posterior probability for a fixed realized parameter; credible intervals depend on the stated model and prior.

Treat smoothing and detrending as analytical choices. A trailing window can lag a change; a centered window loses endpoint information; LOESS and splines can erase features or behave poorly at boundaries. Compare plausible strengths and retain observations or meaningful departures. Additive residuals describe absolute departures; ratios can describe relative departures from an appropriate trend. Fitting on a log scale changes error weighting and must follow the estimand/error model rather than appearance. A decomposition remainder may contain real events and is not automatically random noise.

Before delivering, verify that the reader can recover the unit, group sizes, center definition, spread/interval meaning and comparison of interest. Report checks actually performed; do not turn this list into automatic extra analyses beyond the task.
