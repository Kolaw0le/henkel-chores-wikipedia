# henkel-chores-wikipedia

This project is about scanning the video from an expert channel on youtube to build a search tool on their contents. 
- capture the sound of the videos
- speech to text by chunks of 30 seconds
- indexation of the contents
- in parallel, summary of each 30s chunk with chatgpt
- tokenization
- flask app to match a question with a 30s sequence and return the first timestamp in each video talking about the topic and the summary of the 30 sec section.
