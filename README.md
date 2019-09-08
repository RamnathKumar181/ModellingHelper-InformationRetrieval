# Psychological Counselling Information Retrieval

This application is designed to retrieve information about similar cases and episodes given the user (therapist) knows a few details about the patient. The information retrieved will be cases similar to the patient and can help the therapist treat him/her better and also help the therapist in how to go about new and uncertain cases. The therapist can also use this search engine if he/she would like to volunteer to help other patients who are in need and cannot afford a therapist.

[The Design Document ](https://drive.google.com/open?id=1sT7FhVwFoDSzTOUQ1BqnyxBw5-24k0rfljGcZlxYuOM)

## Requirements
- Python 3.6
- Jupyter Notebooks
- Google's Fake News Word Embedding
- nltk : <code> pip install nltk </code>
- pickle : <code> pip install pickle </code>
- re : <code> pip install regex </code>
- numpy : <code> pip install regex </code>
- itertools : <code> pip install more-itertools </code>

## System Used
1. CPU: Intel(R) Xeon(R) CPU @ 2.30GHz
2. GPU: 1xTesla K80 , having 2496 CUDA cores, compute 3.7,  12GB(11.439GB Usable) GDDR5  VRAM
3. RAM: 12.6GB

## Run
1. Open all the files in [Google Colaboratory](https://colab.research.google.com/) or Jupyter Notebooks
> Run Steps 2 and 3 only for the first time
2. Run all the cells in the ```Preprocessing.py```. The script builds the inverted index and stores it in the same directory.
3. Run ```WordEmbedding.py``` to use the word2vec model which calculates the similarity scores of all the unique words in the dataset
4. Run ```Search.py``` and to search for keyword(s) which will return the top 10 relevant documents


## Acknowledgements
We thank Dr. Aruna Malapati for giving the opportunity to work on this project

## License
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.




