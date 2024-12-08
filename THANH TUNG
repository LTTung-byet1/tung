<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sensor Data</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .sensor-data {
            text-align: center;
            margin-bottom: 20px;
        }
        .sensor-data h1 {
            font-size: 24px;
            font-weight: bold;
        }
        .sensor-data p {
            font-size: 18px;
            margin: 5px 0;
        }
        .sensor-data .timestamp {
            font-size: 16px;
            color: gray;
        }
    </style>
</head>
<body>
    <div class="sensor-data">
        <h1>Sensor Data (Updates Every 7 Seconds)</h1>
        <p><strong>Temperature:</strong> <span id="temperature">--</span> °C</p>
        <p><strong>Humidity:</strong> <span id="humidity">--</span> %</p>
        <p class="timestamp"><strong>Timestamp (GMT+7):</strong> <span id="timestamp">--</span></p>
    </div>
    <div class="sensor-data">
        <h1>Sensor Data (Updates Every 7 Seconds)</h1>
        <p><strong>Temperature:</strong> <span id="temperature2">--</span> °C</p>
        <p><strong>Humidity:</strong> <span id="humidity2">--</span> %</p>
        <p class="timestamp"><strong>Timestamp (GMT+7):</strong> <span id="timestamp2">--</span></p>
    </div>

    <script>
        function updateSensorData() {
            const temperature = 28.6; // Giả sử giá trị này lấy từ cảm biến
            const humidity = 47; // Giá trị độ ẩm
            const timestamp = new Date().toLocaleString("en-US", { timeZone: "Asia/Bangkok" });

            document.getElementById("temperature").textContent = temperature;
            document.getElementById("humidity").textContent = humidity;
            document.getElementById("timestamp").textContent = timestamp;

            document.getElementById("temperature2").textContent = temperature;
            document.getElementById("humidity2").textContent = humidity;
            document.getElementById("timestamp2").textContent = timestamp;
        }

        // Cập nhật dữ liệu mỗi 7 giây
        setInterval(updateSensorData, 7000);

        // Cập nhật lần đầu khi tải trang
        updateSensorData();
    </script>
</body>
</html>
