#PLIVO Assignment

## This is a sample app for contact api's high scale

### Run the project 
```
python3 manage.py migrate
python3 manage.py testserver
```
### OR Buid using Docker image
Using Docker file
```
docker build -t django-to_do_app .
docker run --name=Django -td django-to_do_app
```

## Specs and feature

1. GET ALL

![get_all](images/getall.png)

2.  POST
![post](images/post.png)

3. Search by name
![byName](images/searchby_name.png)

4. Search by email
![byEmail](images/searchby_email.png)

5. Email unique index
![emailIndex](images/post_twice_email_index.png)

6. Delete
![byEmail](images/delete.png)

7. Search by email
![byEmail](images/searchby_email.png)

8. Basic Auth
![auth](images/basic_auth.png)

