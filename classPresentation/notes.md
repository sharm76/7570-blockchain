
# Class notes of Nabila's presentation on BitcoinHeist: Topological Data Analysis for Ransomware Detection on the Bitcoin Blockchain

Q1) Fig. 4 displays that patterns are skewed for ransomware. What is the significance of this pattern?

The metrics on figure four effectively show how many of them are merging (count) and splitting coins, moving them around using different paths, and then merging them in a single address (loop), which are different ways of money laundering. The pattern indicates that this behavior is more common among accounts associated with ransomware.

Q2) Can TDA filtering use weighted feature-based approaches?

Yes, since their TDA relies on mapper and mapper creates its filtering based on equal intervals of each feature, a modification would allow us to use the weighted feature by changing the intervals for the heavier features in comparison to the lighter ones. However, this is not the behavior the author used in their experiments.

# Class notes of Nabila's presentation on An Empirical Analysis of Traceability in the Monero Blockchain

Q1) How is effective untraceability is related to guessing entropy?

Guessing entropy is the expected number of guesses before guessing the spent output. It is defined as the sum of probabilities in sorted order, each multiplied by the sorted index (Ge = \sum i.pi). The effective untraceability is defined as (1+2.Ge)

Q2) Why the ideal effective untraceability set is linearly related to the number of mixins?

The ideal effective untraceability is achieved if all referenced outputs of a transaction input are equally likely to be the real spend, in which case the effective untraceability would be M+1, which is linearly related.

Proof that it would be M+1:

Ge = \sum i . pi

pi = 1/(M+1), since all inputs have the same probability and we have M+1 outputs

(=>) Ge = \sum i/(M+1) = (sum i )/(M+1)

We know the sum of numbers 1 to m is m*(m+1)/2

(=>) Ge = (M * (M+1)/2) / (M+1) = M/2

(=>) eu = 1 + 2 * Ge = 1 + 2 * (M)/2 =  M + 1
