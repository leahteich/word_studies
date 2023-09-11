# word_studies


This repository contains the code for several experiments on the relationship between word frequency and "length," as described by the number of characters or the number of syllables. 

Below are descriptions of all the files in the repo: 

### Notebooks ###
* **len_syn.ipynb**: Python code that finds and plots the correlation between the logarithmic frequency and word length in characters of a synonym pair 
* **syll_syn.ipynb**: Same as the above, but for syllables rather than characters
* **freq_len.ipynb**: Plots the correlation between logarithmic frequency of a word and its length in characters
* **freq_syll.ipynb**: Same as the above, but for syllables rather than characters
* **commonality_len.ipynb**: Code to generate how much more frequently a word is used over another based on the number of characters, on average. <i>Needs to be updated for syllables as well.</i>
* **other.ipynb**: Miscellaneous file for generating outputs from the average frequency for length and syllables

### Raw Data ###
* **SUBTLEXus74286wordstextversion.txt**: Frequency data from the SUBTLEX dataset 
* **eacl2017**: Raw synonym pair data 
* **eacl2017_Syll**: Synonym pair data cleaned so that only words that appear in the syllable dictionary can be used

### Dataframes ###
* **big_df_freqs_chars.csv**: Large dataframe of frequencies for each word, generated from the freq_len notebook 
* **big_df_freqs_sylls.csv**: Large dataframe of frequencies for each word, generated from the freq_syll notebook 
* **length_df_final.csv**: Dataframe of the synonym pair dataset for characters, generated from the len_syn notebook 
* **syl_df_data.csv**: Dataframe of the synonym pair dataset for syllables, generated from the len_syll notebook 