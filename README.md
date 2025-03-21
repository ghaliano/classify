### Step-by-Step Guide to Running the Application

1. **Directory Structure**

```
/your-project
│
├── backend
│   ├── app.py               # Flask API backend
│   ├── text_classifier.py    # Text classification logic
│   ├── requirements.txt      # Python dependencies
│   ├── uploads               # Folder for uploaded files
│
├── frontend
│   ├── src
│   │   └── App.jsx           # React frontend code
│   ├── package.json          # React dependencies
│   ├── package-lock.json     # React lock file
│
├── Dockerfile (Backend)
├── Dockerfile (Frontend)
├── docker-compose.yml
```

2. **Setup**

- Install teh project

3. **Build and Run the Containers**

From the root of your project, run:
```bash
docker-compose up --build
```

4. **Access the Frontend**

Open your browser and go to:
```
http://localhost:3000
```

5. **Access the Backend (Optional Testing)**

The backend API can be accessed at:
```
http://localhost:5000
```

6. **Upload Dataset & Make Predictions**
- Use the frontend interface to upload your dataset JSON file.
- Test predictions by providing text descriptions or uploading files.

7. **Stopping the Application**

To stop the containers, press `Ctrl+C` in the terminal or run:
```bash
docker-compose down
```

### Your application is now fully containerized and ready to use!
