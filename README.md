# Analysing Insights NLP

A natural language processing analysis comparing open reports about psychedelic and meditation experiences. The study analyzes 197 reports (134 psychedelic experiences and 63 meditation experiences) using various NLP techniques.

## Analysis Methods

### Data Preprocessing
- Removed duplicate user entries
- Cleaned null values
- Applied text preprocessing including lemmatization and stop word removal

### Text Analysis Techniques
1. **Semantic Analysis (OpenAI Embeddings)**
   - Used OpenAI's text-embedding-ada-002 model for text embeddings
   - Generated 1536-dimensional vectors for each report
   - Analyzed semantic similarities between and within groups

2. **TF-IDF Analysis**
   - Identified most distinctive words in each group
   - Created comparative visualizations of word importance

3. **Topic Modeling (LDA)**
   - Used Latent Dirichlet Allocation with 5 topics per group
   - Visualized topic distributions and key words

4. **Sentiment Analysis**
   - Used NLTK's VADER sentiment analyzer
   - Analyzed compound, positive, neutral, and negative sentiments
   - Conducted statistical comparisons between groups

## Technical Implementation
The analysis was implemented using Python with key libraries including:
- pandas
- nltk
- scikit-learn
- seaborn
- matplotlib

For detailed implementation, see the analysis notebook.