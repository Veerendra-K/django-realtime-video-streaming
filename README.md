## django-realtime-video-streaming:

<h4>Developed a real-time video streaming application using Django and Websockets that allows users to stream their webcam video to the backend. It will then be sent back to the frontend and displayed on the same page.</h4>

## Prerequisites:

- Python 3.6 or above
- Django 3.0 or above
- Django Channels 3.0 or above
- daphne

## Setting Up the Environment:

<strong>1. Create a new virtual environment for the project by running the following command:</strong>
```
python3 -m venv venv

```

<strong>2. Activate the virtual environment by running the following command:</strong>
```
venv\Scripts\activate

```

<strong>3. Install the required packages using the following command:</strong>
```
pip install Django Django-Channels daphne

```


## Running the Application:

<strong>1. Clone the repository:</strong>
```
git clone https://github.com/Veerendra-K/django-realtime-video-streaming.git

```

<strong>2. Go to the project directory:</strong>
```
cd your-repository

```

<strong>3. Run the Django migrations:</strong>
```
python manage.py migrate

```

<strong>4. Start the Django development server:</strong>
```
python manage.py runserver

```

<strong>5. Start the Websocket server using daphne:</strong>
```
daphne -p 8001 myproject.asgi:application

```

<strong>6. Open the application in your web browser at http://localhost:8000.</strong><br/>
<strong>7. Click on the "Start Streaming" button to start streaming your webcam video.</strong><br/>
<strong>8. When prompted by your browser, grant the application permission to access your webcam.</strong><br/>
<strong>9. The application will now display your webcam video in the first video element on the page.</strong><br/>
<strong>10. The application will automatically establish a WebSocket connection to the backend when the webcam stream starts.</strong><br/>
<strong>11. The application will capture the webcam video frames and send them to the backend via the established WebSocket connection.</strong><br/>
<strong>12. The backend will receive the video frames from the frontend through the WebSocket connection.</strong><br/>
<strong>13. The backend will perform any desired processing on the video frames (optional).</strong><br/>
<strong>14. The backend will send the processed video frames back to the frontend through the same WebSocket connection.</strong><br/>
<strong>15. The frontend will update the second video element's source with the received frames in real time.</strong><br/>
<strong>16. Click on the "Stop Streaming" button to close the WebSocket connection and stop the webcam stream.</strong><br/>

## Conclusion:
<strong>Congratulations! You have successfully set up and run the real-time video streaming application using Django and Websockets. You can now customize the application as per your requirements.</strong>

## Credits: 
<h6>This project was created by,</h6><strong><h5>Veerendra K</h5></strong>
