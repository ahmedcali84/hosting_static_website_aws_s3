# How I Hosted a Static Website on Amazon S3

**Author:** Ahmed Ali  
**Organization:** NextWork.org  
**LinkedIn:** [Ahmed Ali](https://www.linkedin.com/in/ahmed-ali-99055728b/)  
**Website:** [NextWork.org](http://www.nextwork.org/)

## Introduction

Amazon S3 is a storage service that offers data availability and security. In this project, I used Amazon S3 to host a static website.

## Project Overview

This project took me about 6 hours to complete.

### Steps Involved

1. **Creating an S3 Bucket**
   - Time taken: ~7 minutes
   - Configuration steps:
     - **Region:** US East (N. Virginia) (us-east-1)
     - **Access Control Lists (ACLs):** Enabled
     - **Bucket versioning:** Enabled
     - **Public Access:** Cleared the block public access checkboxes

   S3 bucket names must be globally unique.

2. **Uploading Website Files to S3**
   - Uploaded `index.html` and the extracted zipped folder containing static files (e.g., JavaScript files).

3. **Static Web Hosting on S3**
   - Enabled static website hosting via the properties tab in the S3 bucket settings.
   - Set `index.html` as the index document.
   - S3 generated a bucket endpoint URL for the website.

4. **Resolving Access Errors**
   - Encountered `403 Forbidden` errors due to private access settings.
   - Resolved by making the images and HTML files public.

5. **Final Outcome**
   - The website was successfully up and running after addressing the access issues.

## Key Learnings

1. **Static Website Hosting:**
   - Involves displaying HTML and webpage files stored on a web server.
   
2. **Public Access Settings:**
   - Enabled ACL public access to make the website available to the public.
   
3. **Error Resolution:**
   - Initially, the bucket endpoint URL returned errors due to private webpage content. Resolved by making files public.
   
4. **S3 Usefulness:**
   - Found Amazon S3 to be a useful tool for hosting websites and plan to use it for future projects.

## Conclusion

Hosting a static website on Amazon S3 is straightforward and provides a reliable and secure way to make websites publicly accessible.

## Contact

For more information, visit [NextWork.org](http://www.nextwork.org/) or check out my [LinkedIn](https://www.linkedin.com/in/ahmed-ali-99055728b/).

Everyone should be in a job they love. Check out [community.nextwork.org](http://community.nextwork.org/) for more free projects.

---

Feel free to reach out if you have any questions or need further assistance!
