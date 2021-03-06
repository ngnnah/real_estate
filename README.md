# BT Real Estate site, a mobile-friendly Django app
## This is a fully functional website that any real estate company can use out of the box.
* Additional features: `pagination`, `search` and `filter` and `sort` on house listings.
* Databases using PostgreSQL & pdAdmin: Realtor db, Listing db, Account db, and Admin: Staff Access and Management.
### Pages:
- #### / Homepage
- #### Form: Search for available listing: search filters are: keyword, location, price, home feature.
- #### /about Realtors info. Can add more realtors in Admin area
- #### /listings Thumbnails display, Pagination, contain individual listing pages. 
- #### Individual listing: url /listings/int#  Has an assigned realtor (foreign key), home photos display in light box (Lightbox 2), 
- #### Form: Inquiry pre-populated form (based on users’ info): can send actual emails via django.core.mail
- ### User: urls /accounts/register, and /accounts/login, and accounts/dashboard
  + dashboard shows all housing inquiries a user has made
- ### Admin area: url /admin Implement many staff-only operations: can login, manage listings (add, publish, assign realtors, …), realtors (seller of the month, assign listings), and client inquiries.

After cloning this repo and install dependencies (specified in requirements.txt):
* Django==3.0.2
* Pillow==7.0.0
* psycopg2==2.8.4
* psycopg2-binary==2.8.4
* pytz==2019.3

You also need PostgreSQL. Start PostgreSQL server, then run this on your local machine's terminal:
`$ python3 manage.py runserver`

## DEMO:
<img src='show1.png' height='300px' />
<img src='show2.png' height='300px' />
<img src='show3.png' height='300px' />
<img src='show4.png' height='300px' />


