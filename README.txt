The dataset consists of feature vectors belonging to 12,330 sessions.
The dataset was formed so that each session would belong to a different user in a 1-year period.
This is done to avoid any tendency to a specific campaign, special day, user profile, or period.

Origin: UCI Machine Learning Repository
File Type: CSV
File Size: 1.2 MB
Modeling Problem: Classification
Missing Values: Yes

Attributes:
"Administrative", This is the number of pages of this type (administrative) that the user visited.
"Administrative Duration", the amount of time spent in this category of pages.
"Informational", This is the number of pages of this type (informational) that the user visited.
"Informational Duration", the amount of time spent in this category of pages.
"Product Related", This is the number of pages of this type (product related) that the user visited.
"Product Related Duration" the amount of time spent in this category of pages.
The above variables represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories.
The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another.

The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site.
The value of "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session.
The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session.
The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction.

The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother???s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction.
The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date.
For example, for Valentine???s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8.

The dataset also includes operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.
The "Revenue" is a binary field and dependent variable, indicating TRUE for a sale taking place and FALSE for no sale.