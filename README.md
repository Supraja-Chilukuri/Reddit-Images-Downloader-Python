# Reddit-Images-Downloader-Python

### Step 1: Create a reddit account!
1. Signup for a reddit account.
2. Then, select the "Are you a developer? Create an app button".
3. Give your program a name and a redirect URL(http://localhost).
4. On the final screen, note your client id and secret.
5. Create Account	Access Developer	Name	ID and secret

### Step 2: Run download script!
1. Add any subs you want to download to the subreddits_list.csv one per line.
2. Run ImagesDownload.py
3. The first time you run the script, it will ask you for details. 
4. You can just enter the client_id and client_secret and some random name for user agent.
5. Note you don't need to enter a user name or password if you don't plan on posting.
6. The script will create a token.pickle file so you don't have to enter them again. 
7. If you mess up your credentials just delete the pickle file and it will ask for them again.
8. The script will create an images folder and fill it with images it finds. 
9. You can change how many posts it checks on each subreddit by changing POST_SEARCH_AMOUNT. 
10. Also not note every post is a image post so if you put in 10 it may only find 2 images.



Thank you.....
