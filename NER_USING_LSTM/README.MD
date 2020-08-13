Named-entity recognition (NER) (also known as entity identification, entity chunking and entity extraction) is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc.

following steps followed:
1. Load the dataset
2. Extract mappings required for the neural network
3. Transform columns to extract sequential data
4. Split the dataset into train, test after padding
5. Build the model architecture
6. Fit the model
7. highlight the entities in any given sentence using spaCy.
