---
layout:     post
title:      "Automating Data Processing and Quality Assurance with Python and Dataiku for +2M Monthly Distribution Items"
date:       2021-05-02 
author:     "TarepSH"
header-img: "img/in-post/4_6033079297277694135-min.jpg"
lang: en
tags:
  - Data
  - Tech
---

As a tech enthusiast with a passion for data-driven solutions, I am thrilled to share my personal journey of revolutionizing warehousing and distribution processes using Dataiku. In this blog post, I will take you through the challenges I faced, the discovery of Dataiku, and the remarkable results I achieved. Join me on this exciting journey and learn how data can transform traditional operations. I automated the work for over 100 warehouses and facilitated the distribution of over 2 million items to benefit more than 3.5 million people in Syria

In my role at the Syrian Arab Red Crescent (SARC), a humanitarian organization, I encountered significant hurdles in managing inventory, tracking distribution, and ensuring accuracy in our warehousing processes. With a diverse range of items and multiple locations to oversee, I knew we needed a solution that could streamline operations, minimize errors, and provide real-time visibility into our inventory and distribution processes.

## Discovering Dataiku:
Determined to find a cutting-edge tool that could automate our warehousing and distribution processes, I embarked on an extensive research and testing phase. After countless hours exploring different options, I stumbled upon Dataiku—an open-source data platform that promised the flexibility and functionality I was seeking. Intrigued by its potential, I decided to delve deeper.

## Implementation:
The implementation of Dataiku at SARC was a game-changer. Over the course of one month, I dedicated myself to researching and experimenting with various tools and approaches. Although I explored open-source programs and attempted to build a solution from scratch, it was the discovery of Dataiku that transformed everything.

With Dataiku, I was able to develop a comprehensive solution tailored to our specific needs. I started by automating our warehousing processes, focusing on inventory management, transaction processing, and quality assurance. Dataiku seamlessly integrated data from diverse sources, such as Excel files and email attachments, streamlining the entire process.

## The Results:
The results of implementing Dataiku were beyond my expectations. The automation of our warehousing and distribution processes significantly reduced errors, improved accuracy, and enhanced overall efficiency. By synchronizing data from different departments and sources, we could identify discrepancies and flag inconsistencies in real-time, enabling swift resolution.

One of the highlights of our implementation was the creation of a comprehensive dashboard using Dataiku's capabilities. This dashboard provided invaluable insights and real-time information about our inventory and distribution activities. It empowered SARC's management and strategic decision-makers to have a holistic view of our operations and make data-driven decisions promptly.

## Beyond Warehousing and Distribution:
Inspired by the success of our implementation, I realized that Dataiku held immense potential beyond warehousing and distribution. I am now exploring the platform's capabilities for predictive analytics, harnessing machine learning models to forecast demand, optimize inventory levels, and identify trends and patterns. The possibilities seem endless.

My journey with Dataiku exemplifies the transformative power of data-driven solutions. By leveraging an open-source platform, I was able to automate and optimize our warehousing and distribution operations, resulting in improved efficiency, reduced errors, and enhanced decision-making capabilities.

If you're a tech enthusiast or a data aficionado, I urge you to explore the world of data platforms like Dataiku. Embracing the power of data can unlock new opportunities, streamline operations, and drive innovation. Join me on this exhilarating path of using technology to shape a data-powered future.


## How I do this as code
The Python code snippet here ["https://github.com/Syrian-Arab-Red-Crescent-SARC/Dataiku-auto-warehousing-and-distribution/blob/master/recipes/compute_test.py"] presented in this blog leverages various libraries and frameworks to automate data processing and quality assurance tasks. Let's delve into the code and understand its key components and functionalities.

1. Importing Necessary Packages
   - The code starts by importing the required packages, including `dataiku`, `pandas`, `numpy`, `logging`, `time`, `os`, `schedule`, `smtplib`, `ssl`, and more. These packages provide functionalities for data manipulation, file handling, email communication, and scheduling.

2. Defining Variables and Configuration
   - Next, the code defines variables such as the Dataiku client, project details, file paths, email credentials, and result placeholders. These variables are crucial for accessing the project, handling folders, storing data, and sending emails.

3. Getting Email and Processing Attachments
   - The code includes a function, `get_email()`, which connects to the email server using IMAP and retrieves emails from the INBOX folder. It searches for specific attachments related to warehouse and distribution data. Once found, the attachments are saved in the appropriate project folders for further processing.

4. Data Processing and Quality Assurance
   - To ensure data accuracy and quality, the code incorporates multiple functions that perform various checks and validations on the warehouse and distribution data.
   - Warehouse Data Processing:
     - The `war_check_build()` function clears and rebuilds datasets related to warehouse data.
     - The `old_open_balance_check()` function calculates the total sum of the closing balance for the previous month and compares it with the total sum of the opening balance for the current month.
     - The `old_war_check()` function checks for discrepancies in the warehouse data, including opening balance, closing balance, and empty values. It generates a styled and sorted Excel report of the results.
   - Distribution Data Processing:
     - The `dis_check_build()` function clears and rebuilds datasets related to distribution data.
     - The `dis_check()` function checks for inconsistencies in the distribution data, including quantity discrepancies, empty values, and overall distribution accuracy. It also generates a styled and sorted Excel report.

5. Building Final Datasets
   - Once the data processing and quality assurance checks are completed, the code builds the final datasets required for analysis and reporting. This ensures that the processed data is ready for further analysis and decision-making.

6. Sending Email Notifications
   - Finally, the code includes a function, `sending_email()`, which sends email notifications to the relevant stakeholders. The email includes a summary of the results and details of any discrepancies or errors found during the data processing and quality assurance checks. The email also attaches the styled and sorted Excel reports for reference.

Automating data processing and quality assurance tasks is essential for organizations dealing with large volumes of data. The Python code snippet presented in this blog demonstrates how automation can be achieved using various libraries and frameworks. By automating these tasks, SARC HQ2 can save time, reduce errors, and ensure data accuracy for better decision-making.

Please note that this is a high-level overview of your code. You can check more about from here: 
["https://github.com/Syrian-Arab-Red-Crescent-SARC/Dataiku-auto-warehousing-and-distribution/blob/master/recipes/compute_test.py"]


<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/v=epRLY7Npf9Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe src="//www.slideshare.net/slideshow/embed_code/key/MAIsiD18fUBTxx" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/tarepsh/sarc-data-wearhouse-automated-the-collection-and-process-monthly-data-for-100-sarc-warehouses-2m-distribution-items" title="SARC Data Wearhouse - Automated the collection and process monthly data for +100 SARC warehouses &amp; +2M distribution items" target="_blank">SARC Data Wearhouse - Automated the collection and process monthly data for +100 SARC warehouses &amp; +2M distribution items</a> </strong> from <strong><a href="https://www.slideshare.net/tarepsh" target="_blank">Tarek Sheikh AL-Shbab</a></strong> </div>