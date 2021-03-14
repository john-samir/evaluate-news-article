## Article Or Blog Sentiment Discovery Web Tool

This web tool allows users to run **Natural Language Processing (NLP)** on **Articles or Blogs** that are found on other websites. 
When a user submits a URL of an article or a blog, the web page then dispalys sentiment analysis using [meaningcloud API](https://www.meaningcloud.com/products/sentiment-analysis) api.

## Notes

1. You can run this tool either using Production mode or Development mode.
   - Development mode runs on port 8080 (Note: to get the results you have to start the server by using command npm start).
   - Production mode runs on port 8081
```
npm run build-dev
npm run build-prod
npm start
```
2. This web tool also has a unit test packages installed. To test all functionalities of this tool you can use the below command
```
npm test
```
3. Please note that you have to enter a **valid blog/article URL** in order to get the expected results, otherwise, an alert will show and no result will be returned.

4. This web tool will display Only the below parts from the sentiment analysis.
```
- Text (**Only** the first text exists in the blog/article URL)
- Score Tag
- Agreement
- Subjectivity
- Confidence
- Irony
```

## Copyrights

This tool is implemented by **John Ghabrial** using a provided template by Udacity team as part of a project  for **"Front End Web Development Advanced Nanodegree Program"** course
