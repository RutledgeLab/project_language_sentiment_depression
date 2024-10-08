## \data

* `study[1|2]_data.csv` are de-identified data files for each study 1 and study 2
  - Each CSV file includes the key sentiment measures, including averaged human sentiment scores, ChatGPT (GPT-3.5) sentiment measures, and LIWC sentiment measures.
  - Participants who dropped out may still have LIWC sentiment scores but are missing human and ChatGPT sentiment scores (e.g., Study 1 Participant ID 5). The drop-out participants were excluded from all our analyses, and thus we did not collect their human and ChatGPT sentiment scores to reduce analysis costs.
  - Text data of written responses provided by each participant are not publicly available. While the open-ended questions asked participants not to include any identifiable information, some responses contained information that may be sensitive and personal to the participants. To protect privacy, the text data was excluded from the shared data files. 

* `study[1|2]_language_word_count.csv` include word count for each of the nine text responses and for aggregated text responses per participant.
  - `wc` means word count in the column names.
  - The numbers following `wc_` (i.e., 1, 2, 3, ..., 9) in these columns represent the open-ended question numbers.

 * `study[1|2]_riskytask_data.mat` are .mat files that contain raw happiness, predicted happiness from computational modeling, and mood parameters. Computational modeling of happiness ratings was performed in MATLAB (R2020a), and the stored parameter values were retrieved in R to conduct further analyses. All main R Markdown analysis scripts can be found in the `..\scripts` folder.
   
* `\SI` includes data csv files for replicating the key analyses reported in the SI Appendix.
