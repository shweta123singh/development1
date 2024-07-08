# development1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MakeMyTrip - Your Travel Companion</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
        }

        header {
            background-color: #009688;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #009688;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }

        .search-form {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }

        .search-form input {
            flex: 1;
            padding: 10px;
            margin-right: 10px;
        }

        .search-form button {
            padding: 10px 20px;
            background-color: #009688;
            color: #fff;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <img src = ""

    <header>
        <h1>MakeMyTrip</h1>
        <p>Your Travel Companion</p>
    </header>

    <main>
        <div class="search-form">
            <input type="text" placeholder="Enter your destination">
            <button onclick="searchFlights()">Search Flights</button>
        </div>

        <h2>Top Destinations</h2>
        <p>Discover amazing places and plan your next adventure.</p>

        <!-- Add more content and sections as needed -->

    </main>

    <footer>
        <p>&copy; 2023 MakeMyTrip. All rights reserved.</p>
    </footer>

    <script>
        function searchFlights() {
            // Implement search functionality here
            alert('Searching for flights...');
        }
    </script>

</body>
</html>
