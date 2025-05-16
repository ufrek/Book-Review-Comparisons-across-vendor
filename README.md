# Comparing Book Reviews Across Vendors 

Video Presentation: [https://youtu.be/CvC0fgZFHHc](https://youtu.be/CvC0fgZFHHc)

Database of books from : https://github.com/yusanlin/Barnes-and-Noble

## Tools:
The project uses Selenium to automate searching of a book's ISBN across Barnes and Noble and Books A Million.

# Dataset

The final dataset after finding reviews of the same ISBN across both sites consisted of 150 books.

## Preprocessing:

- Each review has had punctuation removed and the text was set to lower-case.

- for each title, the reviews were compiled into a single corpus for each vendor.

  ## Text Rank

  For each vendor, the top 10 keywords were extracted from the review set for a single title.

  ## EvaluationL

  Rouge 1 precision and ngram match averages were taken for each title.

  ## Results:

  Books A Million's roug precision was rather high at .518, however they often had less review with lower word counts.
  
  THe rouge precision between vendors was pretty low at .161. This could be explained by either the users using different words to describe their experiences or using misspellings of words, which was not taken into account.

  
