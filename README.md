# Issue-Bookmarks 🔖
List of interesting articles/websites/tools on topics varying from data science to photography.

## About

A repository for organizing bookmarks on different topics in the form of Github Issues. This project was inspired by [Khuyen Tran's ©️ repo](https://github.com/khuyentran1401/machine-learning-articles), which was originally inspired by [this arXivTimes repository](https://github.com/yutarochan/arXivTimes) on summarizing machine learning papers. The article of this repo can be found [here](https://towardsdatascience.com/how-to-organize-your-data-science-articles-with-github-b5b9427dad37?source=friends_link&sk=4dfb338164ad6e95809d943f0dc0578e)

![image](https://github.com/UjwalKandi/Issue-Bookmarks/blob/master/Images/Issue-Bookmarks-1.png?raw=True)
## Motivation

Have you ever read an interesting article or have come across a fascinating website and wanted to save it somewhere for future reference or share it with your friends? If you have successfully bookmarked it on your browser, it will be easily forgotten or will be hard to find that particular link in your pile of bookmarks.

## Solution

Use this repository as a way to **keep track of your favorite sites/articles as well as see what other interesting articles that people are reading**. 

## Why should you Contribute?
Keeping track of articles in this repository comes with multiple benefits:

* Organized your articles so that it is easy find your article for **future reference**
* **Quickly review** the key points of the articles without reading the whole articles
* The art of summarizing will help you to **retain and comprehend** the information better
* **Save the time** of going through low-quality article by looking at the articles others enjoy
* **Ask questions** or express your opinons on the articles in the comment section of Issues

![image](https://github.com/UjwalKandi/Issue-Bookmarks/blob/master/Images/Issue-Bookmarks-2.png?raw=True)

## How to Contribute
### Format
To contribute an issue, please follow the format listed below:

* A website that you would like to contribute, please create a new "Issue". **A template will be created** as you create a new issue. All you need is to fill in the section
* Use the name of the website as the title of the Issues.
* Use the following guidelines when submitting a new entry (Feel free to **skip any section** that is not relevant to what you are looking for):
  * **TL;DR** - A quick short sentence summary of the paper.
  * **Link to the website.**
  * **Key Takeaways** - parts of the website(resources) that you find useful.
  * **Useful Code Snippets** - useful codes that you want to save for later
  * **Useful Tools** - useful tools that you want to try out or integrate into your workflow
  * **Comments/Questions** - Your thoughts or questions on the articles. 
    * What do you like about this article? What you wish to learn more from?
    * What issues you have while trying to follow the codes or setup in the article?
    * What parts of the articles that you are puzzling about?
    
*The general template to be used can be found [here](https://github.com/UjwalKandi/Issue-Bookmarks/issues/11). Sample example of an issue can be found [here](https://github.com/khuyentran1401/machine-learning-articles/issues/3)*   
![image](https://github.com/UjwalKandi/Issue-Bookmarks/blob/master/Images/Issue-Bookmarks-3.png?raw=True)


### Tips  
* The length of the TL;DR should be enough to **fit in a single tweet** (~140 characters). The "ideal" TL;DR should capture the essence of the problem being solved, the solution/approach the author has taken and the results. Please try your best to help communicate the essence of the article!
* Remember, regard this as your own folder. **Just write down the things that you think will be useful for yourself to look back!** If an article has many pieces of information, some of which you already know and too lazy to write down in the template. Just write down whatever you feel like writing. It is better to write something than give it up all the way
* If you are making a contribution for a specific article, please designate yourself within the **Assignees** of the issue. This will help us to identify who has provided content and accordingly give credit.
* Use the **Labels to tag the category** of the article accordingly. (Currently only contributors are only allowed to issue those tags, thus we'll take care of the tagging when submissions have been recieved.)
* Use the comments section as a place to discuss, comment, ask questions or give feedback on the article.

### Ideas for those who make fork, create Issues from origin
1. Fork repository 
2. Enable Issues in **Settings -> Issues**

    The steps 1 and 2 need be manual

3. We need set **Personal Access Token** (PAT):
    * **[Your Profile](https://github.com/settings/profile) -> Settings**
    * **Developers -> Personal access token**
    * Add new Token (copy for use in Secrets)
      Make sure set the _**scopes**_: **repo**
      Ex: Machine Learning Articles Access — repo

    3.1 Settings your Repo:
     * **Settings -> Secrets**
     * Add a new secret:
       **ACTIONS_SECRET** : `<paste personal access token generated before>`

4. Create final **release: v1.0.0** (Import Issues to the repository)
    * _**Optional**_ you can create one Project(machine-learning-articles/projects) named **Machine Learning Articles** (**To do** , **In progress**, **Done**) for manage the [Issues](https://github.com/oleksis/machine-learning-articles/projects/1)

### How to
#### Add image
Adding image can be helpful to know what the article about. Simply copy the address of the image in the website and use `![image description](link to the image)` to add image to your issue!
