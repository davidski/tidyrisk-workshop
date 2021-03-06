Hello everyone!

Some important information for the upcoming Tidyrisk workshop at SIRAcon2019. 
Please let me know (david@severski.net) if you have any questions. I'm looking 
forward to meeting all of you!

Regards,

David

# Information for Tidyrisk Workshop

# Schedule

The course will run from 4 PM to 5:30 PM.

# Instructors

This workshop is taught by David Severski.

We'll also have teaching assistants in the room to help out if you get stuck or 
have questions.

# Recommended Reading

If you're not already familiar with the basics of OpenFAIR, please 
skim these documents from The Open Group:

* O-RT Risk Taxonomy Standard, https://www2.opengroup.org/ogsys/catalog/C13K 
* O-RA Risk Analysis Standard, https://www2.opengroup.org/ogsys/catalog/C13G

For a more in depth read, these books are highly recommended: 

* The Failure of Risk Management: Why It's Broken and How to Fix It, 
  by Douglas Hubbard, https://www.amazon.com/gp/product/0470387955
* How to Measure Anything in Cybersecurity Risk, by Douglas Hubbard and 
  Richard Seiersen, https://www.amazon.com/How-Measure-Anything-Cybersecurity-Risk/dp/1119085292
* Measuring and Managing Information Risk: A FAIR Approach, by Jack Freund and 
  Jack Jones, https://www.amazon.com/Measuring-Managing-Information-Risk-Approach/dp/0124202314  

# R Setup

The is a hands-on workshop, so you'll need a **laptop with a recent version of R**. 
Version 3.5 or greater (R 3.5.3 is current as of April 2019) is recommended. You 
can obtain R from https://cloud.r-project.org/.

Once you have R installed, run the following commands to get the required 
packages:

```r
install.packages("tidyverse")
install.packages("evaluator", dependencies = TRUE)
```

Using RStudio is strongly encouraged. Please make sure you have a current
version. RStudio 1.2 is current release as of April 2019. You 
can download from https://www.rstudio.com/products/rstudio/download/#download.
  
If you often work on a network drive, it is worth verifying you can load the 
above packages when you are not connected to the internet, just in case 
there are wifi problems on the day of the workshop.

If you have any problems with the setup, please come a little early and 
we'll help you get configured. The workshop instructors will be around from 
8 AM. We'll have an [RStudio Cloud](https://rstudio.cloud) project set up as a 
backup with all the materials and required packages, so you'll be able to 
follow along even if something goes wrong, as long as you have internet access.

**Don't forget your power cable!**
