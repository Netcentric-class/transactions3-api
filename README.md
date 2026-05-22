# transactions3-api

1=App: Write the Heroku URL to your app.
https://csc3221-transactions3-demo-f485be8e8a79.herokuapp.com


2=Running my App (Postman): screenshots of using Postman to do the operations as requested in the instructions
<img width="2940" height="1912" alt="FBF0DF0A-7344-4B1E-B9EA-D16E3CBA7A40" src="https://github.com/user-attachments/assets/5be02197-02db-487a-b8c5-962b9c4464cd" />
<img width="2940" height="1912" alt="D825AC75-9CF9-416E-8B59-A2B68216E70E" src="https://github.com/user-attachments/assets/40c4cf11-5c87-4b5a-a107-c2f7e902fa05" />
<img width="2940" height="1912" alt="45284BF9-3B8B-4711-B598-A275B4AF7C8A" src="https://github.com/user-attachments/assets/bf2ff64f-abf8-4bd7-978f-cbd9a2b55a91" />
<img width="2940" height="1912" alt="FBA93991-6653-4F1C-BB80-6A6CF896D0D9" src="https://github.com/user-attachments/assets/d2c76381-eab0-4938-9d75-82ab584be7be" />
<img width="2940" height="1912" alt="7D6B7209-9DB8-4C55-B2F7-21D16F9A3304" src="https://github.com/user-attachments/assets/abd658bf-a1b1-4580-bd15-ea992c89924c" />
<img width="2940" height="1912" alt="0F742580-DDB4-4E22-A134-AFC1D952B0FC" src="https://github.com/user-attachments/assets/3d7bbb15-1313-4152-8a86-57b8d45b9a70" />
<img width="2940" height="1912" alt="E5B8B3F0-512D-44D2-9EA0-D908B8565D3B" src="https://github.com/user-attachments/assets/774eaa95-c296-40a1-bb6c-fbc467593b1c" />
<img width="2940" height="1912" alt="B59D6464-31E4-4BDC-B02E-F90F03FD962D" src="https://github.com/user-attachments/assets/f5ac6331-1a19-41b5-ba35-faf7545c4b2e" />
<img width="2940" height="1912" alt="22ED5B88-767E-47CA-8961-FA73CEC6D880" src="https://github.com/user-attachments/assets/23b7051d-e625-402a-87d5-61c88fe0d89e" />
<img width="2940" height="1912" alt="AC5024F9-DDD7-45E1-B135-75B0464E4E17" src="https://github.com/user-attachments/assets/b4defbd9-33af-4251-8e5e-ea173afb11fe" />
<img width="2940" height="1912" alt="3174DAD4-16C1-4190-9B43-2A874740DDE8" src="https://github.com/user-attachments/assets/e9209f02-064c-473f-a51c-a132380af583" />
<img width="2940" height="1912" alt="641C8AE3-3B2B-4B29-88C5-B75969938A0E" src="https://github.com/user-attachments/assets/abc80e36-c7d6-4d65-a441-b6c1250de2b9" />
<img width="2940" height="1912" alt="3D12DE80-54C4-4408-9D1A-3905CA660688" src="https://github.com/user-attachments/assets/4cfb5faa-50ab-4b84-8941-5e085978fbed" />
<img width="2940" height="1912" alt="27873CF0-1E17-4576-AE83-BA2BBBBD1D38" src="https://github.com/user-attachments/assets/0e458694-b70a-46be-9906-52db5bf02c8f" />


3=Running my App (Browser): screenshots of using the Browser to use your app (Experiment this, if you are unable, write something in challenges below)
<img width="2940" height="1912" alt="EC77C881-53BA-4448-BCAA-955F4647E674" src="https://github.com/user-attachments/assets/aa62e1e0-f862-4967-82b1-7f178fa897e8" />
<img width="2940" height="1912" alt="5E815A81-90AA-4FA0-9934-C3764A34ED8F" src="https://github.com/user-attachments/assets/dab3c2b3-272b-4217-a487-860b3163dd00" />

4=Differences: What differences did you note from deploy-app-02-s26 and deploy-app-03-s26?
One major difference between deploy-app-02-s26 and deploy-app-03-s26 was the addition of authentication and security features using JWT (JSON Web Tokens). In deploy-app-03-s26, users now have to register and log in before accessing protected transaction routes. This made the application more realistic and secure compared to the previous assignment. Another difference was the use of authentication middleware to verify tokens before allowing access to certain API endpoints. Passwords were also hashed before being stored in MongoDB, which improved security significantly

5=Models: What model code do you prefer, 02's or 03's? (See models and controllers)

I prefer the model code from deploy-app-03-s26 because it is more secure and structured. The addition of authentication, JWT handling, password hashing, and protected routes made the application feel more complete and realistic. I also liked how the controllers and middleware worked together to separate responsibilities clearly. Even though deploy-app-03-s26 was more complex and required more debugging, it helped me better understand how real backend applications manage users and secure data.


6=Challenges: Write the challenges you faced during this exercise and how you solved them
One challenge I faced during this exercise was working with MongoDB Atlas and the database connection setup. At first, I thought I was not allowed to reuse the free cluster I had already created for a previous class assignment, so I assumed I needed to create a completely new cluster. I was worried because some MongoDB Atlas options looked like they required payment, and I thought creating another cluster might cost money. After troubleshooting and researching more, I realized that I could safely reuse my existing free cluster by simply creating a different database for this project. Another challenge I faced was debugging deployment and environment variable issues on Heroku, especially when the application could not connect to MongoDB correctly.

7=Questions: Write any questions you still have after this exercise about the code that was here
