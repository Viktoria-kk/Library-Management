# Django based  Library Management

## Installation 

## 6 . Run the server
```
  python manage.py runserver
```
## 7 . Go to localhost:8000
---

## Features of this project:

##### Anyone can

1. see all the books in homepage
2. search books based on author or name of the book or category of the book
3. sort books or author alphabetically

##### Student can

1.  login / signup ,
2.  can request book
3.  see their own issues and filter them based on 
4.  check their own fines
5.  can see

    - the days remaining to return a particular book
      **or**
    - the number of days passed the return date of a particular book in the my fines page

6.  Pay their fines online (powered by RazorPay)

##### Admin can

1.  login to admin dashboard
2.  check all issues :

    - see issues ,
    - delete issues ,
    - search issues by studentid
    - filter issues based on
3.  accept a issue :

    - from the dashboard where admin has to manually select return date
      **or**
    - from the Issue requests page where return date is automatically calculated

4.  add , delete search books and filter books based on author
5.  add , delete , search author
6.  calculate fine by clicking a button ,
7.  create, delete fine ,search fines for studentid
8.  toggle fine paid status (if paid in cash)
9.  search ,modify,add,delete students , filter them based on department and check all fines and issues of that student
10. can see the last-login , date joined & the student associated to a particular user
11. can change password for any user
