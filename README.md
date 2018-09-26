# Notes
## Google Links on Further Reading
https://medium.com/google-cloud <br>
https://cloudplatform.googleblog.com/<br>
https://cloud.google.com/blog/products/data-analytics<br>
https://cloud.google.com/pubsub/<br>
https://cloud.google.com/dataflow/<br>
https://cloud.google.com/solutions/reliable-task-scheduling-compute-engine<br>
https://cloud.google.com/solutions/<br>
https://cloud.google.com/solutions/processing-logs-at-scale-using-dataflow<br>





Written Response



 



Question 1



A user reports the following issue: On the Billing tab, the
Invoices > Outstanding section lists 16 invoices as being 0-30 days past
due. Clicking through shows only 6 invoices.



 



You have identified the previous issue with the Billing
product after 3 users reported it. When trying to reproduce the issue you
confirm this is a bug. Include every step that you will incorporate on the bug report
that you will file with the Product Engineering team?  



 



Response 1



Report Title:  Billing Invoices - Conflicting Days Past
Due



Reporter: Xavier
Collantes (xcollantes@zagmail.gonzaga.edu)



Submit Date:  09/27/18



Summary:  Under the ‘Outstanding’ section, stated quantity
of invoices 0-30 days past due does not match quantity of invoices
displayed.  



 



Platform:  Billing Dashboard, Invoices



URL:  https://dashboard.stripe.com/test/invoices?closed=false&draft=false



Browser:  Version 69.0.3497.100 (Official Build)
(64-bit)



User-Agent:  Mozilla/5.0 (Windows NT 10.0; Win64; x64)
AppleWebKit/537.36 (KHTML, like Gecko) Chrome/69.0.3497.100 Safari/537.36



Operating System:  Windows 10 Pro; Version 1803



Device:  Microsoft Surface 4



 



Steps to reproduce:



Login to dashboard.stripe.com > ‘Billing’ on left-hand
menu > ‘Invoices’ > ‘Outstanding’ tab



 



Expected result:



 



Actual result:



 



 




 
 
  
  
  
  
  
  
  
  
  
  
  
  
 
 
 

 




 



 







 



Question 2



Context:



The Connect product provides a complete set of building
blocks to support virtually any type of business model, including on-demand businesses,
e-commerce, crowdfunding, and travel and events. The Express Connect account
type is for platforms looking to onboard recipients quickly and at scale, such
as an on demand marketplace. 



Stripe Connect Docs go into more details about this product:
https://stripe.com/docs/connect . 



You will also need to review the Stripe API Docs:
https://stripe.com/docs/api/curl .



 



Hello Support!



I have a website, PHP based, hoping to integrate Stripe
Connect (Express accounts). I've written code to create a login link, allowing
me to log into the dashboard – it works, until I hit "Logout" from
the dashboard. Once "Logout" is clicked from the dashboard. When
select the link again to access the dashboard, Stripe returns the message:
“Something went wrong. Our bad! Try reloading to get back to the Dashboard.” I
try reloading, no luck.



-Lawrence



 



Response 2



Hi Lawrence,



 



Thanks for reaching out, I understand this error can be frustrating
and we want to provide the best experience for our developers.  We love seeing people implement Stripe
Connect in code and hearing frustration such as this helps us improve Connect for
our company and the community we serve.  



 



From your description, it could likely be an error with calls
to the Stripe API.  Here is our documentation
on our API’s and how do deal with various errors.  



https://stripe.com/docs/api?&lang=php#errors



 



I’ve checked the status of our Dashboard API and it’s up and
running.  



You can check it at https://status.stripe.com/



 



After debugging and visiting the links above, I personally
use StackOverflow where a similar project may exist or you could ask a
community of developers.  



https://stackoverflow.com/search?q=stripe



 



We are always improving our products on a global scale and
your voice will help others.  If you have
any questions, please feel free to reach out. 




 



Thank you,



Xavier Collantes



 







 



Question 3



Context:



Multiple users have raised questions about processing in
foreign currencies. Our specialist team has been receiving these types of cases
escalated for the last few weeks. The following case describes the type of questions
our team is receiving: How does processing in foreign currencies work with
Stripe? I'm based in the UK and have a GBP bank account but would like to
accept all my payments in USD. Thanks in advance for your help.



-Catherine



 



How would you go about addressing this situation? If one of
the goals for the half is to reduce escalation rate, what strategy and plan of
action would you propose?



 



Response 3



Since there have been multiple users asking the same
questions on processing FX, either relevant information does not reach the user
effectively or the information is non-existent. 




 



First, I would gather known information on the users to find
a commonality; are the users working on the same project?  Which tools are the users utilizing?  Is there a language barrier?  Once I have a story on the users, I would review
https://stripe.com/docs/currencies/conversions
to make sure this page is current and up to date.   If I find
the page has relevant answers presented in detail, the next likely case is the
information is too hard to find.  



 



Next, I would propose we have a revised FAQ or a tooltip on
the application to present relevant information in the FX platform to
anticipate questions during a user’s experience.  



 



Alternatively, analysis can be done on which docs are least
frequently viewed and subject matters of questions.  If a particular docs page has relatively few
views and relatively high number of questions on that subject, we can suspect
either the page is not advertised enough or difficult to use.  



 



My solution takes into consideration the long-term goal of
reducing escalation in the future.  Once
the docs are effective, questions on the subject is more likely to decrease.  



