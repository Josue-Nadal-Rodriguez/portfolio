+++
title = "Portfolio"
tags = ["work-experience"]
date = "2023-06-05"
+++

# Build and Maintain my own custom Linux Distro (using Linux From Scratch)

*02/xx/2024*

*Compiling from source, Cross-compilation, Linux Kernel Configuration, Linux Package Config*

I've always wanted to know more about how Linux works so I decided to follow the LFS book. It was challenging, but also straight forward and enjoyable; it's all there if you read carefully. I followed the standard System V Init Build and use my system as a home server. I'm currently in the process of completing the Beyond Linux From Scratch Book to build up my system to something more feature packed. The LFS book also served as a good source of documentation for many linux related configuration and package info.

# FirstBank Software Developer - *ITDG*

*02/01/2023 - Present*

*C#, .NET, Powershell, REGEX*

Following my initial work-experience at FirstBank and due to the suite of tools i built to aid in the migration I was brought back to design an ETL application. This application acted as a middleware between their massive printers and data warehousing. For this round i decided to do a whole re-design, with a shared-library at the center that allowed me to build more tools into the ecosystem and functionality into the program in a consistent manner.

# Puerto Rico Department of Housing Wordpress/Web Developer - *ITDG*

*02/01/2023 - Present*

*Wordpress, HTML, JavaScript, Firefox API*

Due to my past experience hosting web pages for a non-profit entity i was assigned to work with the Department Of Housing on their CDBG-DR/MIT Funds Program. Work mostly consisted of designing, creating and editing web pages on their [recuperacion.pr.gov](https://recuperacion.pr.gov) domain. The site was split into spanish and english versions and we were strictly required to follow ADA Web Accesibility guidelines. We also kept static versions of the most visisted webpages to curve resource usage by wordpress. I also created a browser extensions to facilitate repetitive operations.

# FirstBank Migration Specialist - *ITDG*

*02/01/2022 - 12/31/2022*

*C#, .NET, Powershell, REGEX*

I got hired to help migrate financial data onto a new document management system. We worked on VMs and used propietary scripting language to instruct the client to dump all of its records. This worked well for small reports, but for larger reports the client would disconnect and for PDF reports it would only ever spit out a single page. I was tasked with solving this. For larger reports i created a powershell script to check if the client and check if the report it had been dumping ended with a special character that denoted the end of a page. For PDFs i had to craft something morecomplex. The client ever only gave you a single PDF page at a time and had to be reconnected. So i had powershell run the client itself, edit the client script to ask for the next page, rename that page with the page number, and do this over and over a[Ogain till the client would stop giving pages. If ever it skipped a page the script would detect this and go back and ask for the missing page. At the end it would merge all the pages into a single PDF document.

# Ponce School of Medicine Full Stack Dev Internship

*02/01/2020 - 12/01/2020*

*C#, .NET, Razor, Bootstrap, HTML, CSS, Javascript, PDFsharp, MigraDoc*

I interned at the Ponce School of Medicine with the Systems Department. The first part of the internship was dedicated to Software Development and the second to Networking Skills. So:

- For software development the team wanted to trial an idea handed to them by management. They wanted to try out a system that could register the number of students in a class room during a certain period. Like class room attendance auditing. This was to be done by security guards during their rounds, the guards were issued I Pads for monitoring purposes so the application was to be fully compatible with I Pads. The system i implemented made use of svg maps with clickable areas overlaid on floor plan images. And i also created custom authorization schemes for the guards so as to streamline application usage. The custom authorization required users to log in with their email and password **if** the user was inactive for more than 1.5 hours, else the user could log in with a simple 4+ digit pin. I also had to use external libraries for generating PDF reports of the data entered. The reports were fully customizable allowing for time period, building and classroom filtering and sorting.

- For the networking/IT part of the internship it was a lot of computer maintenance/connectivity troubleshooting, program installation, i also had to lay ethernet cables above the rafters (dusty) and do new OS installations.

# Bachelors Degree in Comp Sci with a Concentration in Database Administration from the University of Puerto Rico in Ponce

*08/01/2015 - 12/01/2020*

I got my Bachelors in CompSci from UPRP, cool, small university. Our department was even smaller, but i think it made the education better. All the proffessors were great, student-centric and knew their stuff. During my time there I participated in several ACM Collegiate programming competitions and in 2018 i made it into the Regional Finals in the Dominican Republic, but my team couldnt fund their stay so we forfeited our spot. I also helped out at Alpha Computer Association, a student organization where we organized community tournaments and programming workshop. I was also the student representative for my department for a year. Through out all of this i was also doing work-study. Initially work-study was in a lab, then i moved in with the Systems Administrator doing work throughout the campus and later i was trusteed enough to work on the campus website (wordpress, html, js).  During this time some of my personal projects were: blog software written entirely in PHP
