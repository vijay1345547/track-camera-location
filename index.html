<!DOCTYPE html>
<html>
<head>
    <title>Location and Camera Access</title>
</head>
<body>
    <h1>Track Location and Access Camera</h1>
    <button onclick="getLocation()">Get Location</button>
    <p id="location"></p>
    <video id="video" width="320" height="240" autoplay></video>
    <script>
        // Function to get the user's location
        function getLocation() {
            if (navigator.geolocation) {
                navigator.geolocation.getCurrentPosition(showPosition, showError);
            } else {
                document.getElementById("location").innerHTML = "Geolocation is not supported by this browser.";
            }
        }

        // Function to display the user's location
        function showPosition(position) {
            document.getElementById("location").innerHTML = "Latitude: " + position.coords.latitude + 
            "<br>Longitude: " + position.coords.longitude;
        }

        // Function to handle errors in getting the location
        function showError(error) {
            switch(error.code) {
                case error.PERMISSION_DENIED:
                    document.getElementById("location").innerHTML = "User denied the request for Geolocation."
                    break;
                case error.POSITION_UNAVAILABLE:
                    document.getElementById("location").innerHTML = "Location information is unavailable."
                    break;
                case error.TIMEOUT:
                    document.getElementById("location").innerHTML = "The request to get user location timed out."
                    break;
                case error.UNKNOWN_ERROR:
                    document.getElementById("location").innerHTML = "An unknown error occurred."
                    break;
            }
        }

        // Function to access the camera
        function startCamera() {
            const video = document.getElementById('video');
            if (navigator.mediaDevices && navigator.mediaDevices.getUserMedia) {
                navigator.mediaDevices.getUserMedia({ video: true })
                .then(function(stream) {
                    video.srcObject = stream;
                    video.play();
                })
                .catch(function(error) {
                    console.log("Error accessing camera: ", error);
                });
            } else {
                alert("Camera access is not supported by this browser.");
            }
        }

        // Start the camera as soon as the page loads
        window.onload = startCamera;
    </script>
</body>
</html>
