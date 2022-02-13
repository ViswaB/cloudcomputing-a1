<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#project-link">Project Link</a></li>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#instructions">Instructions</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## Project Link
http://d2515v51pc8j0d.cloudfront.net/

<!-- ABOUT THE PROJECT -->
## About The Project

This purose of this project is to demonstrate the knowledge of building a website and deploying it to the 
cloud using AWS service of S3, securing it with IAM policies, and using CloudFront to speed up the content delivery globally. The website itself is very simple with a main page
that displays my name, and has links to 5 other pages, one of which includes some images, and another which includes a 30 sec video


<p align="right">(<a href="#top">back to top</a>)</p>


### Built With
 
* HTML, CSS
* [AWS S3](https://aws.amazon.com/s3/)
* [AWS CloudFront](https://aws.amazon.com/cloudfront/)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

1. Create an account in AWS for free using Free Tier-> https://aws.amazon.com/.
![image](https://user-images.githubusercontent.com/68451169/153737463-07b67189-4ebf-48c1-94a8-a78ab0022f9c.png)

#### IAM
2. Once you have created a Free Tier account, and verified it, search for the service of IAM (Identity and Access Management Service) in the search bar of AWS.
   What is IAM?
    IAM is a service of AWS has for multiple users and group users of same account 
    because the root account should not used or shares for security purposes. IAM is a global service therefore does not need region selection, and in the service users, who are     people within an organization, can be grouped into not just one but miltiple groups, although not required to. 
    
3. Create an IAM user and provide admin access. 
      a. Once you click on IAM from search results, you'll be on the IAM service page. On the left there is a menu, labeled Dashboard. In this dashboard the first category is
      Access management under it find the option "Users" and click on it, where you'll be taken to a page to create users. Click on Add users on top right. 
      b. Provide a username, and next select "Password" under Select AWS access type, where you'll be provided with a few options. Either choose to autogenerate password, or
      provide custom password, and choose whether or not to require a reset of password when IAM user login for the first time. For the purpose of this project it is required to       create an IAM user for yourself, so you can choose custome password and not require to reset it. Click next.
      ![image](https://user-images.githubusercontent.com/68451169/153738844-6859c8a4-a214-429d-b33d-50f7cb769dd0.png)

      c. Add user to group, by creating a group and including with policy "AdministratorAccess" as shown below. Click next. This takes you to add tags, which is not required.
      Click next for review. Create user. The next page you'll see a confirmation for successfully creating user, and option to send email instructions. You can close this page
      now. 
      ![image](https://user-images.githubusercontent.com/68451169/153738972-5aae80ce-9163-44bb-aa60-0e772452958d.png)

      d. Take note of the Account ID from your root account by clicking on your username on top right of root account. Then Sign out of root account. Sign into console using IAM
      user. IAM sign in requires the Account ID, along with username and password of the IAM user provided during creation of the user. Now we have secured the project using IAM
      policies. 

### Installation
1. Install VScode -> https://code.visualstudio.com/, inorder to code in html and css, which will then be uploaded to the S3 bucket.

  
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- Instructions -->
## Instructions
### S3
WHAT is S3:
Amazon S3 allows the storage of objects (files) in forms of buckets.
Buckets must have a name that is globally unique are defined at the region level.
The Naming convention requires the following: No uppercase, No underscore, 3-63 characters long, Not an IP.
![image](https://user-images.githubusercontent.com/68451169/153739240-f9087722-3563-4084-8aed-1f6569479581.png)

1. Create an S3 bucket.
    a. Search for S3 on AWS search and go to S3 page. This pag shows all your S3 buckets that you have created
    ![image](https://user-images.githubusercontent.com/68451169/153739102-33a3d2a3-fc2e-478a-827f-fe5e5eedcfdb.png)
    
    b. In this step, click on create bucket, and provide a globally unique name to the bucket. All other settings for creating a
    bucket can be left as default.
    Once this is done, click create at the bottom of the page.
    ![image](https://user-images.githubusercontent.com/68451169/153739117-f437a099-253a-4b55-8f4d-ce1b14c49a29.png)
 
    
    c. You will now see the bucket you created in the main S3 page. click on it. Here you'll see an option to upload your files. For the purpose project I uploaded 5 html pages,        2 image file, one video, and 1 css styling sheet. S3 is very useful when creating a webpage using HTML, CSS and Javascript.
2. dfghgfhg
3. ffhfgh
4. 
### CloudFront   
    

   

  
<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Viswa Bhargavi - viswa.bhargavi.2000@gmail.com

Project Link: https://github.com/ViswaB/cloudcomputing-a1

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [GitHub Readme.md reference](https://github.com/othneildrew/Best-README-Template/blob/master/README.md)

<p align="right">(<a href="#top">back to top</a>)</p>
