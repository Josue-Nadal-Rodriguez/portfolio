+++
title = "Portfolio"
tags = ["work-experience"]
date = "2023-06-05"
+++

# Build and maintain my own custom Linux Distro (using Linux From Scratch) | *02/xx/2024*

- *Compiling from source, Cross-compilation, Linux Kernel Configuration, Linux Package Config*

Seeking to learn more about linux distributions I dicided to take on building Linux From Scratch. It was challenging, but also straight forward and enjoyable; it's all there if you read carefully. I followed the standard System V Init Build and use my system as a home server. I'm currently in the process of completing the Beyond Linux From Scratch Book to build up my system to something more feature packed. I found the LFS book to be a good source of documentation for many linux related configuration and package info.

---

# FirstBank Software Developer - *ITDG Consultant* | *02/01/2023 - Present*

- *C#, .NET, Powershell, REGEX*

Following my initial work-experience at FirstBank and due to the suite of tools I built to aid in the migration I was brought back to design an ETL application. This application acted as a middleware between report generation, printing and data warehousing. For this round I decided to do a whole re-design, with a shared-library at the center that allowed me to build more tools into the ecosystem and functionality into the program in a consistent manner. This is a regex heavy application with many continous file operations like merging, splitting, extracting data, masking and sorting. 

---

# Puerto Rico Department of Housing Wordpress/Web Developer - *ITDG Consultant* | *02/01/2023 - Present*

- *Wordpress, HTML, JavaScript, Firefox API, Python, BeautifulSoup4*

Due to my past experience hosting web pages for a non-profit entity I was assigned in assisting the Department Of Housing developers on their CDBG-DR/MIT Funds Program. Work mostly consisted of designing, creating and editing web pages on their [recuperacion.pr.gov](https://recuperacion.pr.gov) domain. The site was split into spanish and english versions and we were strictly required to follow ADA Web Accesibility guidelines. We also kept static versions of the most visisted webpages to curb resource usage by wordpress. Some tools I developed to aid me were: a firefox browser extensions to facilitate repetitive operations and a scraping tool that generated basic reports for accesibility, deadlink detection as well as html element search for design standardization purposes.

---

# FirstBank Migration Specialist - *ITDG Consultant* | *02/01/2022 - 12/31/2022*

- *C#, .NET, Powershell, REGEX*

I got hired to help migrate financial data onto a new document management system. We worked on VMs and used propietary scripting language to instruct the client to dump all of its records. This worked well for small reports, but for larger reports the client would disconnect and for PDF reports it would only ever spit out a single page. I was tasked with solving this. For larger reports I had to completely automate client processes. I created a powershell script to check if the client had disconnected and restart, and to check for completion by looking for a special character that denoted the end of a page. For PDFs a similar, but more complex solution was needed. The client ever only gave you a single PDF page at a time and had to be reconnected, we found no way around this. So I had powershell run the client, wait for a page, rename that page with the run number, edit the script to ask for next apge, and do this over and over again till the client timed out a specified number of times. We took this to mean the client had no more pages to give. At the end it would look at all the page numebrs and detect any skipped pages ask for the missing pages again. After that the script itself would merge all the pages into a single PDF document.

---

# Ponce School of Medicine Full Stack Dev Internship | *02/01/2020 - 12/01/2020*

- *C#, .NET, Razor, Bootstrap, HTML, CSS, Javascript, PDFsharp, MigraDoc*

I interned at the Ponce School of Medicine with the Systems Department. The first part of the internship was dedicated to Software Development and the second to Networking. So:

- For software development the team wanted to trial an idea handed to them by management. They wanted to try out a system that could register the number of students in a class room during a certain period. A class room attendance auditing program. This was to be done by security guards during their rounds, the guards were issued IPads for monitoring purposes so the application was to be fully compatible with IPads. The system I created had interacitve maps made of svg images with clickable areas overlaid on building floor plan images. And I also created custom authorization schemes for the guards so as to streamline application usage. The custom authorization required users to log in with their email and password **if** the user was inactive for more than 1.5 hours, else the user could log in with a simple 4+ digit pin. I also had to use external libraries for generating PDF reports of the data entered. The reports were fully customizable allowing for time period, building and classroom filtering and sorting.


- The networking/IT part of the internship consisted of a lot of computer maintenance/connectivity troubleshooting, application installation, I also had to lay ethernet cables above ceiling panels (dusty) and oversaw drive wiping, fresh OS installations, CCTV connecting and troubleshooting. 

---

# Bachelors Degree in Comp Sci with a Concentration in Database Administration from the University of Puerto Rico in Ponce | *08/01/2015 - 12/01/2020*

I got my Bachelors in Comp. Sci. in 2020. During my time there I participated in several ACM International Collegiate Programming Competitions and in 2018 I made it into the Regional Finals in the Dominican Republic, but my team couldnt fund their stay so we gave up our spot. I also helped out at Alpha Computer Association, a student organization where we organized community tournaments and programming workshops. For a year I acted as student representative for my department. Through out all of this I did work-study, initially in a computer lab, then I moved to working with the Systems Administrator doing work throughout the campus and later I was trusted enough to work on the campus website (wordpress, html, js). During this period I also won a portable computer at a hackathon I attended.

