# What Kine Jobs? Small Kine Jobs!

* [Link to the application repository](https://github.com/smallkinejobs/application)
* [Milestone 1 project board](https://github.com/smallkinejobs/application/projects/1)
* [Milestone 2 project board](https://github.com/smallkinejobs/application/projects/2)
* [Milestone 3 project board](https://github.com/smallkinejobs/application/projects/3)

## Small Kine Overview
The Small Kine Jobs app will be used to help students who would like to find short term employment. Reasons for needing short term employment could be: The student is only at the University for a year or less, a student needing quick cash, or even if an employer needs an employee for a short period of time. This app would provide a quick and easy outlet to find an employer/employee without having to go to a temporary job agency, which can sometimes have long replying periods or sometimes too many applicants. 
Most importantly the app is specific for UH students, who already have the financial burden of funding their education.

## User Guide
Users can go onto the [Small Kine Jobs App](http://smallkinejobs.meteorapp.com/) and they'll reach the landing page.

### The Landing Page
![Image of Landing Page](/images/landingpagedraft2.PNG)
The first thing that the user sees is the option to sign up for the application. That way they can start their job/employee search as soon as possible. Returning users can use the tab in the top right corner to login to their profiles

![Image of Landing Page Testimonial](/images/finalTestimonials.PNG)
Then at the bottom of the landing page we finally have the testimonials component, which updates when people who like small kine jobs give a review of the site. 

### The Login Page
![Image of Sign In Page](/images/sign_in.png)
If you already have your account created you can go to the login page

### Employer Sign up
![Image of Sign Up Employer Page](/images/finalEmployerSignUp.PNG)
Users can sign up as Employees on this page 

### Helper Sign up 
![Image of Sign Up Helper Page](/images/finalHelperSignUp.PNG)
Users can also sign up as a Helper as well

### Step 1: Employer posts a job
![Image of Emploer Landing Page](/images/finalEmployerLanding.PNG)
On the employer landing page, the employer can post a new job

![Image of Sign Post a job modal](/images/finalPostAJob.PNG)
Here the employer can give details of the job that's at hand, as well as the skills that are involved

### Step 2: Helper responds to the job posting
![Image of Sign Up Helper Landing](/images/finalEmployeeLandingExample.PNG)
Here the Helper can see what jobs are currently posted and then apply those jobs.

![Image of Applying to a Job Modal](/images/finalApplyToJob.PNG)
This is where the helper confirms to join the job they are interested in

### Step 3: Employer Responds to Helper's application to the job
![Image of Employer Landing Page with Hiring jobs](/images/finalHireEmployerLanding.PNG)
The employer can hire applicants to any jobs with a response

![Image of Hire Helper Modal](/images/finalHireHelper.PNG)
This is where the employer hires the Helper that they choose

![Image of In progrss photo](/images/finalInProgress.PNG)
The job will then be in progress.

### Step: 4 Helper does job, then marks it complete and rates the Employer
![Image of Helper completing on the landing Page](/images/finalcompleteJobHelper.PNG)
Here the Helper will mark the job complete once the task is done

![Image of rating modal for Helper](/images/finalHelperSubmitFeedback.PNG)
Then the Helper can rate the employee, this rating helps others see how good of an employer/employee you are

### Step 5: Employer marks the job as actually completed, closes the job, then rates the Helper

![Image of Employer seeing complete job](/images/finalEmployerCompletedSubmitFeedback.PNG)
Here the employer can verify that the job is completed and then submit feedback

![Image of Sign Up Helper Page](/images/finalRateHelper.PNG)
Here the employer can also rate the employee.

### Step 6: Job completed!
![Image of Job closed](/images/finalHelperJobClosed.PNG)
Now that the job is closed, another employer needs to post another job.

![Image of dropdown of Past User](/images/finalPastUsers.PNG)
![Image of Hire Past Helpers](/images/finalInvitePastUserToOtherJob.PNG)
If the employer wishes, they may also invite the Helper they've just hired to do another job if they wish. 

![Image of User rating](/images/SeeAvgRating.PNG)
You can also see how much you've been paid, as well as your average user rating as an employer, employee, or both!

## Community Feedback

### M2 Delpoyment
The initial launch of the app was small step in the right direction but not a success. Due to a bug within a portion of the code some users would receive an error message. The bug was determined to be from an error which needed an image, but there was no image to be found. But when the users didn’t get the bug, they found it easy to log in and sign up. They couldn’t really interact with other users, so we’ll start that in M3. But our landing pages and sign up pages did what they were supposed to do. Engage the user and have them use the website immediately. There should be a delete button for the job creation as well in case the job being posted isn’t correct. There also may need to be a filter for what jobs are legitimate or not as well, so that way spam can be avoided in job postings. The job postings can also be seen live as soon as they are posted by a user. 

### M3 Deployment
This launch of the app was slightly more successful, but it still had it's problems. The users that were asked to use the app were from the university, some were graduate students and others were graduates. Feedback was obtained via email and messenger. Users were able to leave a testimony and sign up, but due to a bug, there were no jobs posted and therefore no jobs were applied. In hindsight if we actually posted jobs to apply for in the beginning, as well as putting a "create job" button. Unfortunately we only used created profiles with jobs in them to do the initial testing. The overall attitude towards the potential of the job is the same. This would allow people to find help fairly quickly, but as well as allowing people to find a quick way to get cash without having to go through the lengthy process for a regular job.

## Future Development
*Connect UH Login
*Put in a payment system, online payment method
*Have the ability to post a profile picture
*When someone wants to apply for a job when they apply allow them to see a better description


## Developers Guide 
First [Install Meteor](https://www.meteor.com/install)

Second, go to [the Small Kine Jobs github repository](https://github.com/smallkinejobs/application) and clone it to your desktop

Third, go into the app/ directory and install the libraries with the:
```
$ meteor npm install
```
Fourth, run the app using 
```
$ meteor npm run start
```
If the installation is successful you will be able to run the app by navigating to [http://localhost:3000](http://localhost:3000) in your web browser

### Modifiying the Source Code

![Fork Repository Image](/images/fork_repo.png)
If you would like to contribute to the project, be sure to create a fork of the repository so that you have your own remote copy. The primary maintainers of the project utilize the github Pull request system for issuing commits to the base branch of the repository. 
![Pull Request Example Image](/images/pull_request_example.png)
If you would like to implement a new feature or bug fix, create a new branch on your local repository, implement the feature, push the changes to your fork, and then issue a pull request from the fork to the master branch at [the Small Kine Jobs github repository](https://github.com/smallkinejobs/application). Pull requests will be accepted and merged pending an approving code review from at least one of the primary maintainers of the site. The recommended development environment is the IntelliJ IDEA Ultimate IDE, which is the development environment utilized by the primary maintainers.

## Concept pages
<img height="50%" width="50%" src = "/images/Landing.jpeg">land
<img height="50%" width="50%" src = "/images/Profile.jpg">
<img height="50%" width="50%" src = "/images/Search.jpg">
<img height="50%" width="50%" src = "/images/SignIn.jpg">
<img height="50%" width="50%" src = "/images/UserEmployee.jpg">
<img height="50%" width="50%" src = "/images/UserEmployer.jpg">
<img height="50%" width="50%" src = "/images/UserEmployerEmployee.jpg">

## Application models
<img height="50%" width="50%" src = "/images/models.jpg">
