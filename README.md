# twitter-sentiment-analysis
This project performs sentiment analysis on Twitter data, classifying tweets as Positive, Negative, or Neutral. Built with Python, Tweepy, and TextBlob in Google Colab, it fetches, cleans, and analyzes tweets to show sentiment distribution. Developed as a university-level AI project.

⚠️ Note:  
The current output screenshots show `429 Too Many Requests - Usage cap exceeded` because the free Twitter API monthly quota was exhausted. The code works fine — you just need a valid API token or can use `snscrape` as an alternative to bypass the cap.

## Known Issues
- The free Twitter API has strict monthly limits.  
- Once the quota is used up, you may see:  
  `TooManyRequests: 429 Too Many Requests - Usage cap exceeded`.  
- This is not a bug in the code. You can wait for the reset or switch to `snscrape`.
