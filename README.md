- [Problem Statement](#Problem-Statement)
- [Summary](#Summary)
- [Next Steps](#Next-Steps)
- [Data Dictionary](#Data-Dictionary)
- [External Resources](#External-Resources)

---

## Problem Statement

The goal of this project is to predict the outcome for cats and dogs in an animal shelter based on features like their type, sex, age, breed, and color.

---

## Summary



---

### Next Steps

With more time and resources, I would be interested in pursuing:  
- further examination of the relationship between animal names and outcomes
- 

---

### Data Dictionary  

|Feature|Type|Description|
|---|---|---|
|**animalid**|str|unique animal ID number|
|**name**|str|the animal's name|
|**datetime**|str|time of outcome|
|**outcometype**|str|our prediction goal - Return_to_owner, Euthanasia, Adoption, Transfer, or Died|
|**outcomesubtype**|str|subset of outcome|
|**animaltype**|str|cat or dog|
|**sexuponoutcome**|str|male or female, neutered, spayed, or intact|
|**ageuponoutcome**|int|age of animal in days|
|**breed**|str|breed of animal|
|**color**|str|color of animal|

---

### External Resources  
https://www.kaggle.com/c/shelter-animal-outcomes/data?select=sample_submission.csv.gz