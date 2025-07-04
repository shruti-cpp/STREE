<a name="readme-top"></a>


<!-- PROJECT LOGO -->
<br />
<div align="center">
<!--     <img src="https://media.discordapp.net/attachments/794519160746541108/1061560277168029756/valky.png" alt="Logo" width="80" height="80"> -->
  </a>

  <h3 align="center" >Stree - Empowering Women's Safety and Growth</h3>
<hr/>
<hr/>

  <!-- <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p> -->
</div>

<br>
<br>
<br>


<!-- TABLE OF CONTENTS -->
<details align="center">
  <summary><h2>Table of Contents</h2></summary>
  <br/>
  <ol align="left">
    <li>
      <a href="#about-the-project">About The Project And Our Motivation</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <!-- <li><a href="#license">License</a></li> -->
    <li><a href="#contact">Contact</a></li>
    <!-- <li><a href="#acknowledgments">Acknowledgments</a></li> -->
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project And Our Motivation
![Screenshot 2024-09-01 140429](https://github.com/user-attachments/assets/6dfe5973-6268-4c9c-9d12-9620aff816fc)
![Screenshot 2024-09-01 140457](https://github.com/user-attachments/assets/23593768-3dd0-4ec0-8150-5d58ea2edefe)
![f5deba14-507b-4560-9efb-ad277085036d](https://github.com/user-attachments/assets/5a332933-9256-4bb2-9902-fb98e791ca93)
![Screenshot 2024-09-01 140820](https://github.com/user-attachments/assets/fbb0f040-b22f-461b-9270-7e12f40671e3)
![Screenshot 2024-09-01 140947](https://github.com/user-attachments/assets/8858c2b3-7c7f-4aa9-9d3f-cbe31ce40b7b)
![Screenshot 2024-09-01 141134](https://github.com/user-attachments/assets/fa77b0ed-0570-45e0-a2f3-7c7f8438b555)





Stree is a platform designed to enhance women's safety by enabling them to anonymously report crimes and providing them with guidance on tech communities and resources. Our mission is to empower women to take charge of their personal safety while also offering them opportunities to explore and grow in the tech industry.

Through Stree, women can connect with others in their community, report crimes without fear, and access valuable resources related to technology. This creates a supportive environment where women feel secure and informed.

One of Stree's standout features is an interactive map that allows users to pinpoint and report crime incidents. By visualizing these incidences on the map, women can easily identify which areas are safe or unsafe, helping them make informed decisions to avoid potential dangers and stay protected. Stree is committed to fostering a safer and more inclusive environment for all women.

<br>




<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Technologies Used

### Frontend

- **React**: Used for building the user interface.
- **React Router**: For client-side routing.
- **Recoil**: State management for React.
- **Leaflet & React-Leaflet**: Used for mapping and location-based services.
- **Axios**: For making HTTP requests.
- **Tailwind CSS**: For styling the application.

### Backend

- **Node.js & Express**: Backend framework for handling requests and routing.
- **MongoDB & Mongoose**: Database and ORM for storing and managing data.
- **JWT (jsonwebtoken)**: For handling user authentication and security.
- **Zod**: For schema validation.
- **bcryptjs**: For hashing passwords.

## Installation

### Prerequisites

- **Node.js**: Ensure you have Node.js installed on your system.


### Steps

1. **Fork the Repository**

2. **Clone the Repository**:
   ```bash
   git clone ${url_of_your_forked_repo}
   cd stree
   ```

3. **Setup the Client**:

    ```bash
    cd client
    npm install
    ```
  
  
4. **Setup the Server**:
    ```bash
    cd ../server
    npm install
    ```



5. **Create a `.env` File**:

   - In the `client` and `server` directories, create a `.env` file and add the necessary environment variables.

   - **Example for `server/.env`**:
     ```plaintext
     MONGO_URI=your_mongodb_uri
     JWT_SECRET_KEY=your_jwt_secret_key
     FRONTEND_URL=http://localhost:your_local_port
     ```

   - **Example for `client/.env`**:
     ```plaintext
     VITE_BACKEND_URL=http://localhost:your_backend_port
     ```
   
   Make sure to replace `your_mongodb_uri`, `your_jwt_secret_key`, `localhost:xyxy`, and `localhost:your_backend_port` with the appropriate values based on your local setup.

## Run the Application

1. **Start the backend**

    ```bash
    cd server
    npm run start:dev
    ```
2. **Start the frontend**

    ```bash
    cd ../client
    npm run dev
   ```

## Access the application

- Open your browser and go to http://localhost:your_local_port to view the application.

### Built With

* [![React][React.js]][React-url]
* [![Node][Node.js]][Node-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing
## Ways to Contribute


- Open a issue ticket for any gap in documentation or bug or feature requests that you have, opening up issue tickets is always a good way to contribute.

- You can help review open PRs for best backend and devops realted code practices and help the contributors out.

- Lastly and the most obvious one feel free to pick up open issue tickets and raise a PR for it resolving the bug, feature or documentation request.


Contributions are vital to the open-source community, helping it grow, inspire, and create new possibilities. Any contributions you make are sincerely appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
<!-- ## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
 -->


<!-- CONTACT -->



### Contact Info
<br>

Shruti Jha - [Shruti Jha](https://www.linkedin.com/in/shruti-jha-793248249/)

Profile Link: [https://github.com/hruti-cpp](https://github.com/shruti-cpp)




<br>
<br>




## Licence

This project is licensed under the MIT License.
