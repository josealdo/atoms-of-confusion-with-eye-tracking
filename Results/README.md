# Summarizing the Results for Our Research Questions (RQs)

Table: Results for all metrics for all atoms. O = obfuscated code; C = clarified code; PD = percentage difference; PV = \textit{p}-value; ES =  effect size {(Cliff's delta)}. Columns O and C are based on the median as a measure of central tendency except for attempts, which is base on the mean.

<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/results-atoms-individual.png" width="800" title="hover text">
</p>


Table: Results for all metrics for all atoms. O = obfuscated code; C = clarified code; PD = percentage difference; PV = \textit{p}-value; ES =  effect size (Cliff's delta). Columns O and C are based on the median as a measure of central tendency except for attempts, which is base on the mean.

<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/results-atoms-all.png" width="800" title="hover text">
</p>

All atoms. We analyze all atoms combined. The idea of combining all atoms follows the Latin Square design methodology. We assign two subjects to each square. Each subject solves six programs obfuscated by the atoms from one set of programs, and six clarified programs from another set of programs. We can combine the atoms in two ways. We can perform combinations of the individual atoms, but not pairing the participants in the squares, and we can combine the atoms by pairing the participants. In the former, if we have a reduction in time in code for all six individual atoms, we will have a reduction across all atoms as well. However, in the latter one, which we used, we can better control for differences among the subjects and we may have slight increases in the combination.

Combined, the differences were not so evident expect for the number of horizontal and vertical regressions in the AOI clarified. The results revealed that, across all atoms, the average number of horizontal regressions reduced by 31.6% while the average number of vertical reduced from zero to 6.5. For Multiple Variable Assignment, True or False Evaluation, and Conditional Expression, we have shorter lines of code in the clarified version, however, for the Operator Precedence, Implicit Predicate, and Augmented Operator, even with more elements, we observed reductions.

We also present each of the null-hypotheses with its respective confirmation or rejection. The two most sensitive metrics were the regressions count, which showed significant differences in three out of six atoms, followed by time, which showed  differences in two atoms. The most noticeable effect size was observed for the code containing the Operator Precedence with respect to the clarified version in RQ2 (Cliff's delta of -46). The other effects observed for clarified versions of the code containing the Multiple Variable Assignment, True or False Evaluation, and Operator Precedence were also noticeable, but to a smaller degree.

Table: Summary of the rejection of the null hypothesis in isolated atoms in the AOIs. Null-Hypothesis consists of no difference between control and treatment groups with respect to the mentioned metric.

<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/hipoteses.png" width="600" title="hover text">
</p>

Distribution of the data in the AOI. Obfuscated (O) and Clarified (C) versions of all atoms for ST1–ST2 together
<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/a1.png" width="600" title="hover text">
</p>

<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/a2.png" width="600" title="hover text">
</p>

<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/a3.png" width="600" title="hover text">
</p>

<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/a4.png" width="600" title="hover text">
</p>

<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/a5.png" width="600" title="hover text">
</p>

<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/a6.png" width="600" title="hover text">
</p>

<p align="center">
  <img src="https://github.com/josealdo/atoms-of-confusion-with-eye-tracking/blob/main/Results/Tables/all.png" width="600" title="hover text">
</p>
