# nextwork.org-projects-aws-host-a-website-on-s3
# Host a Website on Amazon S3


## project architecture diagram

<img width="1944" height="908" alt="s3-architecture" src="https://github.com/user-attachments/assets/2abcbdcf-92a5-4a52-88c8-f2f163db56ee" />



# Successful hosting of the website

<img width="1909" height="966" alt="successful website" src="https://github.com/user-attachments/assets/3fa40ef7-abf0-4903-bfb7-a251271a0d41" />


## Introducing Today's Project!

In this project, I will be using Amazon's S3(Amazon Simple Storage Service) to
host a website. Using Amazon's S3 will allow me to store and retrieve any
amount of data at any time from anywhere on the web.I will be creating a S3
bucket to demonstrate. 



## Tools and Concepts

The main AWS service I used was Amazon S3, which allowed me to create a bucket to host my static website and store or retrieve any amount of data directly from the web.
During this process, I learned key concepts such as Access Control Lists (ACLs) and object ownership, which are essential for managing permissions and controlling access to stored content.

## How I Set Up an S3 Bucket
Creating an S3 bucket took me took me about 15 minutes as I am following step
by step but if I wasnt I would have taken me less than 10 minutesThe Region I picked for my S3 bucket was Africa Cape Town af-south-1, because
it is the closet to me as I am in South Africa. This will reduce latency and costs.S3 bucket names are globally unique! This means that An S3 bucket name must
be globally unique across all AWS accounts to ensure that each bucket can be
uniquely identified and accessed.

<img width="1911" height="703" alt="General purpose buckets panel" src="https://github.com/user-attachments/assets/e92a88a2-1b9c-4b2a-a574-44ad268c030f" />



## Upload Website Files to S3 🌐

I uploaded two main files to my Amazon S3 bucket:

• index.html — the core file responsible for structuring and designing the web page.

• Images folder — containing all the image assets used throughout the website.

Both files work together to ensure the website is fully functional and visually complete. The HTML file defines the layout and interactive elements, while the images bring the design to life—ensuring buttons, visuals, and page sections appear exactly as intended.


<img width="1918" height="676" alt="Objects panel" src="https://github.com/user-attachments/assets/d6640c27-773a-41d7-96c7-1a8b2a9cd167" />


## Static Website Hosting on S3 ☁️ 

Website hosting means making your website publicly accessible on the internet. This involves configuring an Amazon S3 bucket to serve static website content.

In simple terms, it’s like saying:

“Hey, I have this website stored in my S3 bucket, and I want the world to see it.”

By enabling static website hosting, AWS provides a URL that anyone can use to access your web page and view your HTML file directly in their browser.

I also learned about Access Control Lists (ACLs) — a set of rules that define who can access specific resources and what actions they can perform. Enabling ACLs allowed me to have full control over who can view or modify the objects stored in my bucket.


<img width="1866" height="683" alt="Static website hosting setup" src="https://github.com/user-attachments/assets/31554ff7-f6a6-4f36-a924-b7c0d51613fd" />



## Bucket Endpoints 🔗

A bucket website endpoint is similar to a regular website URL — it allows users to access your S3 bucket’s files as a public website.

When static website hosting is enabled, Amazon S3 generates a unique endpoint that serves as the website’s address.

During setup, I received an error message indicating that my static website was being hosted correctly, but my HTML and image files were still private.
It was like having my bucket on display, but with the contents still locked away.

This helped me understand the importance of configuring public access settings and object-level ACLs to ensure all website files are visible to the public.

## Success! ✅ 

To resolve the 403 error, I first retraced my setup steps to find what I had missed. When I couldn’t figure it out, I took a short nap — and that moment of rest helped me realize the mistake!

The issue was that I hadn’t made my folder public using ACL settings.
Once I enabled public access through ACLs, my static website became fully accessible on the web.

This experience reminded me that debugging takes patience and attention to detail — and sometimes, stepping away for a short break can lead to the right solution.

<img width="1914" height="972" alt="Screenshot 2025-11-02 223530" src="https://github.com/user-attachments/assets/595797a4-2747-496f-91c2-37910fe848ce" />



## Project Reflection 💭 

This project took me approximately one day to complete.
While working through the errors and configurations, I gained a deeper understanding of how Amazon S3 handles website hosting, object permissions, and public access.

This hands-on experience boosted my confidence in using AWS S3 for web deployment and gave me valuable insight into cloud hosting best practices.

## Acknowledgments 🙌

A big thank you to NextWork for creating this engaging challenge and inspiring AWS learners to build, explore, and grow their cloud skills.

NextWork Challenge Link 🔗 

🏷️ Tags

#AWSCloud #AmazonS3 #AWSBeginnersChallenge #NextWork #CloudComputing #StaticWebsiteHosting #LearningInPublic
