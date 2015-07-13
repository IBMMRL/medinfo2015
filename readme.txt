Description:
This dataset consists of tweet annotations with medical entities. We focuses on three types of entities: Disease (T047 in UMLS), Symptoms (T184), and Pharmacologic Substance (T121). 

(Words in parenthesis represent field names in JSON)
The dataset is formatted in line JSON format. Each line contains a tweet id (tid) and entity annotations (entities). Annotations are zero or more dicts in a list. Each dict contains the medical type (type) of an entity, the start and end offsets for the entity. The offsets are 0-based index from the start of a tweet. Some dicts come with extra annotations (attributes), such as head word POS tag.

License:
This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License.

Citation:
Please cite the following paper if you use the dataset for your research
Identifying Diseases, Drugs and Symptoms in Twitter, Antonio Jimeno Yepes, Andrew MacKinlay, Bo Han, Qiang Chen, MedInfo, 2015

