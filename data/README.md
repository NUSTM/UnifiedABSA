

# Data Naming Specification

## Task Name
ACD: Aspect Category Detection
ACOS: Aspect-Category-Opinion-Sentiment Quadruple Extraction
ACSTE: Aspect-Category-Sentiment Triple Extraction
AOSTE: Aspect-Opinion-Sentiment Triple Extraction
AOOE: Aspect-Oriented Opinion Extraction (given a aspect, extract the coresponding opinion)
AOPE: Aspect-Opinion Pair Extraction
AOSC: Aspect-Oriented Sentiment Classification (also aka ABSC)
ASPE: Aspect-Sentiment Pair Extraction (also aka E2E-ABSA)
ATE: Aspect Term Extraction
COSC: Category-Oriented Sentiment Classification (as similar with ABSC)
CSPE: Category-Sentiment Pair Extraction (as similar with ASPE)

## Few-shot Dataset Naming

Taking Laptop-ACOS as an example, `Laptop-ACOS-seed42-16` denotes the 16-shot dataset sampling from Laptop-ACOS with a random seed of `42`.

Note that since data for tasks other than ACOSQE is drived from ACOSQE task,  the number of these drived datasets does not nacessarily match the number of shots named by the dataset.