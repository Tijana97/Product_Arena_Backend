# Product_Arena_Backend
<br>
Backend logic and database for doctors app, login and logout
<br>
<br>
I have created a database with doctors and appointments. I have also created a logic on how to verify username and password that comes in a POST request and
if they are valid, it returns a JSON object with data from that doctor and all his appointments. Since I wasn't sure how the logic on frontend will work, I
decided that it is the best to just return a JSON object, while in reality, we would redirect to another page which doesn't exist, since we don't have a frontend.
I also haven't hashed the password, although that should be done, since we don't have a login form, and I wouldn't be able to know how the password looks like after
hashing and wouldn't be able to test it on postman. Ideally, once the doctor makes an account, we would hash his/her password and save that hashed version in the
database. Once the doctor tries to log in, we would take the password he/she has sent in a login form, hash it and check if it matches the hashed password for that 
email address in the database.
