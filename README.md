# Movie-Recommendation-System
About The Project
-  Project Build during Microsoft Intern Engage 2022
-  This is a Movie Recommendation Web Streaming Engine Based on Content Based Recommendation System.
Salient Features
It makes use of keywords and Movie ID to recommend 5 movies as per user's choice.
Compatible Platforms
Laptops, Desktops and Tablet PCs
Built With
- Jupyter Notebook ( Anaconda 3)
-  PyCharm
Project Flow:
Jupyter Notebook ---> Dataset ---> Data Preprocessing ---> Vectorisation ---> Function Implementation in PyCharm ---> Frontend / Streamlit
- For generating Local URL Type streamlit run app.py and press enter. Local URL will be generated which will direct to the webpage

<img width="937" alt="Screenshot 2022-05-27 223647" src="https://user-images.githubusercontent.com/81379083/170854896-dfae9e4e-e740-49ba-95c2-fba8222f185d.png">

<img width="955" alt="Screenshot 2022-05-29 114356" src="https://user-images.githubusercontent.com/81379083/170854906-23d2ecfa-5d78-4ebe-a10e-a01eb47739bf.png">
 Functions Used
 1. Merging of Data Sets is done. Data is then Modified according to user's needs. <img width="867" alt="Screenshot 2022-05-29 114843" src="https://user-images.githubusercontent.com/81379083/170855009-ebbc4f87-7645-450f-b760-b65b8595cb37.png">
2. For Vectorisation, Count Vectoriser Function is used. It is a Class which combines most Similar Words and remove Stop Words.<img width="875" alt="Screenshot 2022-05-29 115345" src="https://user-images.githubusercontent.com/81379083/170855193-599cf95a-13a7-4371-ab84-dd5ac6c4778b.png">
3. I have used Movie Recommend in Jupyter. Movie is Chosen, Index is Found, it goes into Similarity Matrix, Index is found and sorting is done and result is returned.<img width="856" alt="Screenshot 2022-05-29 115815" src="https://user-images.githubusercontent.com/81379083/170855331-ee11dcb2-0bfd-4084-bc93-c9850dfc7484.png">
4. PyCharm is used as an IDE for Python Development. Streamlit is uploaded as a Package in PyCharm to run the application. Fetch_Poster traces path of Poster by movie id in Jupyter and Keywords. Finally, 5 movies are returned as output.<img width="939" alt="Screenshot 2022-05-29 120252" src="https://user-images.githubusercontent.com/81379083/170855445-4496266c-0915-437b-aca3-719341830ce8.png">
<img width="945" alt="Screenshot 2022-05-29 120409" src="https://user-images.githubusercontent.com/81379083/170855474-3819c922-8c8e-42a6-95eb-6625c7900274.png">
