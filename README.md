# distributed-video-processing

1. **For Front_End Folder:**
   a. Navigate to the Front_End directory and install the necessary Node packages by running `npm install`.
   b. Move to the Front_End/React subdirectory and initiate the React app using the `npm start` command.

2. **NodeJs Server:**
   a. Enter the nodeJs directory and activate the server using the `node server.js` command.

3. **Environmental File:**
   a. Ensure there is a .env file present, containing the path to the shared folder.

4. **For Face_Detection_System:**
   a. Ensure the installation of needed libraries by running `pip install -r requirements.txt` within the Face_Detection_System directory.
   b. In the Face_Detection_System directory, initiate the producer (master node) with the `python3 producer.py` command.
   c. Subsequently, launch both consumer (worker nodes) using `python3 consumer1.py & python3 consumer2.py`.

5. **Environmental Variables:**
   a. Confirm the existence of a .env file with the necessary username and password for the Postgres database, along with the path to the shared folder.

6. **Docker Container Creation:**
   a. If you intend to generate Docker containers, consult the dockerfiles directory located within the Face_Detection_System.

Remember to adjust your paths, usernames, and passwords in the .env files as per your setup, and ensure all the mentioned files and folders are in the correct location.
