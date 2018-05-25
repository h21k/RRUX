# Machine learning to help researchers evaluate biases in clinical trials: a prospective, randomized user study
Authors:<br> 
[Frank Soboczenski](https://h21k.github.io/) School of Population Health and Life Sciences, King's College London, London, UK<br>
[Thomas Trikalinos](https://vivo.brown.edu/display/ttrikali) Center for Evidence-based Medicine, Brown University, Providence, USA<br>
[Jo\"el Kuiper](https://joelkuiper.eu/) Vortext Systems, Groningen, Netherlands<br>
[Randolph G Bias](https://www.ischool.utexas.edu/~rbias/site/) School of Information, University of Texas at Austin, Austin, USA<br>
[Byron C Wallace](http://www.byronwallace.com/) College of Computer and Information Science, Northeastern University, Boston, USA<br>
[Iain J Marshall](https://kclpure.kcl.ac.uk/portal/iain.marshall.html) School of Population Health and Life Sciences, King's College London, London, UK<br>

## Structure of the repository

Data folder:<br> 
              + `TimeAnalysis2_1.xlsx` (main data file)<br>
              + `UXData1.xlsx` (aux data file - mainly including qualitative answers)<br>
              + `sus_calculation.csv` (System Usability Scale data)<br>
              + `subset_selfreported.xlsx` (subset of TimeAnalysis2_1.xlsx for self reported characteristics)<br>
              + `annotaionschanged.xlsx` (subset of TimeAnalysis2_1.xlsx for annotations analysis)<br>
              + `agreement.xlsx` (subset of TimeAnalysis2_1.xlsx for self judgement agreement analysis)<br>
              
Jupyter Notebook: Analysis.ipynb<br>
              Structure:  1. `Main Analysis` (distribution of the data, Wilcoxon significance tests, boxplots, scatterplots)<br>
                          2. `Descriptives` (mean, sd etc of timing data)
                          3. `Tukey Ladder of Powers` (data transformation and plots)
                          4. `Linear Mixed Effects Model Analysis` (primary and auxiluiary model analysis)
                          5. `Reviewer Judgments & Annoations Analysis` (descriptives, self-reported characteristics, agreement data, annotation data)
                          6. `Questionnaire Analysis` (likert scale analysis, System Usability Score (SUS) evaluation)
