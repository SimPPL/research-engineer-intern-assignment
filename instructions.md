<h1> Research Intern Assignment </h1>
We're thrilled you're interested in joining SimPPL! This assignment is designed to give you a practical, hands-on experience in social media analysis, mirroring the kind of work you'd be doing with us.  It's structured like a mini-research project, challenging you to explore how information spreads across social networks, specifically focusing on content from potentially unreliable sources.  Instead of building a data collection tool from scratch for this initial exercise, you'll be provided with existing social media data. Your task is to design and build an interactive dashboard to analyze and visualize this data, uncovering patterns and insights about how specific links, hashtags, keywords, or topics are being shared and discussed.  This will allow you to focus on your data science, machine learning, and analysis skills, which are crucial to the research we conduct at SimPPL. The plots you create and the technologies you choose will be valuable learning experiences, and directly relevant to the work we do. 

<h2>Task Objectives</h2>
1. Visualize Insights: Tell a story with a graph, building intuitive and engaging data visualizations.

2. Apply AI/ML: Use LLMs and machine learning to generate metrics and enhance your analysis.

3. Build and Deploy a Dashboard: Develop and (ideally) host an interactive dashboard to showcase your analysis.


<h2>Rubric for Evaluation</h2>
Take a look at <a href="https://parrot.simppl.org/">parrot</a> that we have previously built as a visualization platform for Twitter data (it does not have search integrations though it is a good example of a solution other than that). Below is the rubric we will use for your evaluation, provided as a checklist for you to evaluate your own assignment before you submit it to us. 

1. **IMPORTANT** Is the solution well-documented such that it is easy to understand its usage?
  
2. **IMPORTANT** Is the solution hosted with a neatly designed frontend?
   
3. **IMPORTANT** Does the solution visualize summary statistics for the results? For example:

  a. Time series of the number of posts matching a search query 
  
  b. Time series of key topics, themes, or trends in the content
  
  c. Pie chart of communities (or accounts) on the social media platform that are key contributors to a set of results
  
  d. Network visualization of accounts that have shared a particular keyword, hashtag, or URL using additional data they may have shared
  
4. Unique features (optional, but here are some creative and useful features past applicants have built that resulted in successful outcomes):

   a. Topic models embedding all the content of results using Tensorflow projector (free, basic), Datamapplot (free, advanced), or Nomic (paid) as a platform to visualize the semantic map of the posts.
   
   b. GenAI summaries of the time-series plots for non-technical audiences to understand the trends better.
   
   c. Chatbot to query the data and answer questions that the user inputs about the trends for particular topics, themes, narratives, and news articles.
   
   d. Connecting offline events from the news articles with the online sharing of posts on social media for specific searches (for example using Wikipedia to find key events in the Russian invasion of Ukraine and map them  to the online narratives that are shared – though this is somewhat manual and not easy to automate, but extremely useful nevertheless).
   
   e. Connecting multiple platform datasets together to search for data across multiple social platforms.
   
   f. Semantic search after retrieving all posts matching a URL so that the retrieved results can be queried beyond keyword matching.
   
**Bonus** If you host your Jupyter Notebook or JS dashboard, we consider it a significant improvement over applicants who haven’t hosted their solution.


<h2>Link to the dataset</h2>
<h2>Instruction for the submission</h2>
These instructions outline how to use GitHub for this assignment.  Please follow them carefully to ensure your work is properly submitted.

1. Fork the Repository:
   
  a. Go to the assignment repository provided by the instructor: [Insert Repository Link Here] 
  
  b. Click the "Fork" button in the top right corner of the page. This creates a copy of the repository in your GitHub account. 
  
2. Clone Your Fork:
   
  a. Go to your forked repository (it will be in your GitHub account).
  
  b. Click the "Code" button (the green one) and copy the URL. This will be a git URL (ending in .git).
  
  c. Open a terminal or Git Bash on your local machine.
  
  d. Navigate to the directory where you want to work on the assignment using the cd command. For example: cd /path/to/your/projects.
  
  e. Clone your forked repository using the following command: git clone <your_forked_repository_url> (Replace <your_forked_repository_url> with the URL you copied).
  
This will download the repository to your local machine.

4. Develop Your Solution

Work on your assignment within the cloned repository. Create your code files, visualizations, and any other required deliverables. Make sure to save your work regularly.

6. Commit Your Changes
   
  a. After making changes, you need to "stage" them for commit. This tells Git which changes you want to include in the next snapshot.
  
  b. Use the following command to stage all changes in the current directory: 
    i. To add all the files - git add. <br>
    ii. Or, if you want to stage-specific files - git add <file1> <file2> ...
  c. Now, commit your staged changes with a descriptive message- git commit -m "Your commit message here" (Replace "Your commit message here" with a brief1 description of the changes you made.2 Be clear and concise!)  <br>  
  d. push your commits back to your forked repository on GitHub- git push origin main (Or, if you're working on a branch other than main, replace main with your branch name. origin refers to the remote repository you cloned from). 
  
8. Please notify us of your submission by emailing simppl.collabs@gmail.com with the subject line "Applicant for SimPPL".


<h2>Things to keep in mind while submitting your assignment</h2>
Please ensure you include:
1. A detailed README file (with screenshots).

2. A detailed notebook or script for us to understand your code and thought process. 

3. A link to a video recording of your dashboard hosted on YouTube or Google Drive.

4. Both of these make it easier for us to run your code and evaluate the assignment.

<h3>Note</h3>
Remember, you don’t have to build the perfect system. It can be a simple, elegant, and effective querying platform. All we want to see is the ability to search for a keyword, hashtag, link, or piece of input in any format you prefer, and the ability to identify posts on a platform that match the input either immediately or asynchronously once data is available. We will be testing the functionality of your system and the intuitiveness of the plots you have developed. Telling a single thoughtful story is much better than telling multiple broken ones–go for quality, not quantity :)

Presentation matters, please ensure your assignment is possible to easily understand for someone who may be a non-expert on social media and non-technical at running complex queries. 
Design and UX matters. Thinking through how a user may utilize your system is more important than adding yet another feature to make it more technically complex.

<h3>References </h3>
1. <a href="https://github.com/ChrisStevens/garc">https://github.com/ChrisStevens/garc</a>

2. <a href="https://github.com/whymath/sharechat-scraper">https://github.com/whymath/sharechat-scraper </a> 

3. <a href="https://tgstat.ru/en">https://tgstat.ru/en</a> 

4. <a href="https://start.me/p/0Pqbdg/osint-500-tools?locale=el">https://start.me/p/0Pqbdg/osint-500-tools?locale=el</a>  




