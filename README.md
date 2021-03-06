# REST Service using Github API

### Serves information about given repository of particular user

### Technology stack
 1. java-1.11.0-openjdk-amd64 (11.0.4)
 2. Apache Maven 3.6.0

---
### Functionality
1. REST service on address \
    {HOST}/repositories/{userName}/{repositoryName}
2. Fetching method from \
    api.github.com/repos/{userName}/{repositoryName} \
    [example](https://api.github.com/repos/axal25/BareJS)

---
### Useful links
[Lombok package & plugin config](https://www.baeldung.com/lombok-ide) \
[Test tutorial article](https://www.mkyong.com/spring-boot/spring-boot-junit-5-mockito/) \
[Rest Client usage](https://stackoverflow.com/questions/42365266/call-another-rest-api-from-my-server-in-spring-boot) \
[Response error handling](https://www.baeldung.com/spring-rest-template-error-handling) \
[Github's custom client errors](https://developer.github.com/v3/#client-errors) 
---
### To do
    1. [DONE] Change returned model class to dedicated for this REST service (wrong field names)
    2. [DONE] plug error code and error message from github response to custom error
    3. [DONE] error page as json
    4. end-to-end tests
        4.1. [DONE] jacek.oles.github.res.model.com.github.api.Repo 
        4.2. [DONE] jacek.oles.github.res.model.Repo
        4.3. Fetcher
            4.3.1. FetchException
        4.4. RepoDao
            [OPTIONAL] 4.4.1. FetchException
        4.5. RepoService
            [OPTIONAL] 4.5.1. FetchException
        4.6. RepoController
            4.6.1. ClientSideError
    5. tidy up pom.xml
    6. [REALLY OPTIONAL] handling github's custom client error fields

---
---
---

**Edit a file, create a new file, and clone from Bitbucket in under 2 minutes**

When you're done, you can delete the content in this README and update the file with details for others getting started with your repository.

*We recommend that you open this README in another tab as you perform the tasks below. You can [watch our video](https://youtu.be/0ocf7u76WSo) for a full demo of all the steps in this tutorial. Open the video in a new tab to avoid leaving Bitbucket.*

---

## Edit a file

You’ll start by editing this README file to learn how to edit a file in Bitbucket.

1. Click **Source** on the left side.
2. Click the README.md link from the list of files.
3. Click the **Edit** button.
4. Delete the following text: *Delete this line to make a change to the README from Bitbucket.*
5. After making your change, click **Commit** and then **Commit** again in the dialog. The commit page will open and you’ll see the change you just made.
6. Go back to the **Source** page.

---

## Create a file

Next, you’ll add a new file to this repository.

1. Click the **New file** button at the top of the **Source** page.
2. Give the file a filename of **contributors.txt**.
3. Enter your name in the empty file space.
4. Click **Commit** and then **Commit** again in the dialog.
5. Go back to the **Source** page.

Before you move on, go ahead and explore the repository. You've already seen the **Source** page, but check out the **Commits**, **Branches**, and **Settings** pages.

---

## Clone a repository

Use these steps to clone from SourceTree, our client for using the repository command-line free. Cloning allows you to work on your files locally. If you don't yet have SourceTree, [download and install first](https://www.sourcetreeapp.com/). If you prefer to clone from the command line, see [Clone a repository](https://confluence.atlassian.com/x/4whODQ).

1. You’ll see the clone button under the **Source** heading. Click that button.
2. Now click **Check out in SourceTree**. You may need to create a SourceTree account or log in.
3. When you see the **Clone New** dialog in SourceTree, update the destination path and name if you’d like to and then click **Clone**.
4. Open the directory you just created to see your repository’s files.

Now that you're more familiar with your Bitbucket repository, go ahead and add a new file locally. You can [push your change back to Bitbucket with SourceTree](https://confluence.atlassian.com/x/iqyBMg), or you can [add, commit,](https://confluence.atlassian.com/x/8QhODQ) and [push from the command line](https://confluence.atlassian.com/x/NQ0zDQ).