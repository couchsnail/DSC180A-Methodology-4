Camille Sicat (cisicat@ucsd.edu)  
DSC 180A Section B18: [Deep learning for understanding microbiome results](https://dsc-capstone.org/enrollment/)  
Mentor: Professor Rob Knight (rknight@ucsd.edu)

**What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic covered in our domain this quarter is how the microbiome can impact so many areas of health. 
For example, there is something called the shared cage effect, wherein rats sharing the same cage share microbes and thus have similar health outcomes.
One of the studies we read for our replication involved seeing if the shared cage effect had any impact on Parkinson's through examining the gut microbiome
(as measured by stool samples) the compositional abundance of bacteria in various microbiome ecosystems.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
A potential investigation we'd like to pursue for our Quarter 2 Project is how to measure absolute abundance in microbial samples. 
Microbial data is compositional, meaning that the abundance of each bacteria is measured as a proportion of the total sample, raher than being true count data.
You can read more about this issue [here](https://www.frontiersin.org/journals/microbiology/articles/10.3389/fmicb.2017.02224/full). 
Thus, if our team is able to develop a method of calculating absolute abundance, which reflects true bacterial populations in a given sample, we could open the
door to further study in microbiome research. Absolute abundance calculations would have the potential to measure the true statistical power of various
clinical microbiome treatments, as well as deciphering how health outcomes are tied to microbial communities. 

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
A potential change I'd make to the approach taken in our current Quarter 1 Project would be to draw Monte-Carlo realizations from the replication data and then
calculate the alpha and beta diversity from there. Because we were replicating a study that used count data in order to determine sample size for optimal
statistical power analysis, we had to treat abundance values as absolute. However, in order to connect with our investigation for next quarter, as well as illustrating
the relative abundance problem, it would be nice to compare the results with a transformation designed to preserve the compositional nature of the data.

**What other techniques would you be interested in using in your project?**  
I would be interested in doing comparative analyses across different microbial datasets. For our replication this quarter, we only performed analysis on one dataset,
which was the one used in the paper. In order to test the efficacy of our absolute abundance calculation method, and also to see if we could develop machine-learning
methods based on it, we would need to run it multiple times on different sets of data. This comparative analysis and statistical significance calculation would be
extremely useful to validate our results, especially if we compare them to the original studies and the figures they generated.
