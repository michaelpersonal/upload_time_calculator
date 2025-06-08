<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Upload Time Calculator</title>
</head>
<body>
  <h1>Upload Time Calculator</h1>
  <label for="fileSize">File Size:</label>
  <input type="number" id="fileSize" placeholder="e.g., 14">

  <label for="fileUnit">Unit:</label>
  <select id="fileUnit">
    <option value="GB">GB</option>
    <option value="MB">MB</option>
  </select>

  <label for="speed">Speed (MB/s):</label>
  <input type="number" id="speed" placeholder="e.g., 4">

  <button onclick="calculate()">Calculate</button>

  <h2 id="result"></h2>

  <script>
    function calculateUploadTime(fileSize, fileUnit, speedMBps) {
      let fileSizeMB;
      if (fileUnit.toLowerCase() === 'gb') {
        fileSizeMB = fileSize * 1024;
      } else if (fileUnit.toLowerCase() === 'mb') {
        fileSizeMB = fileSize;
      } else {
        throw new Error('Unsupported file size unit. Use "GB" or "MB".');
      }

      const timeSeconds = fileSizeMB / speedMBps;
      const hours = Math.floor(timeSeconds / 3600);
      const minutes = Math.floor((timeSeconds % 3600) / 60);
      const seconds = Math.floor(timeSeconds % 60);

      return `${hours}h ${minutes}m ${seconds}s`;
    }

    function calculate() {
      const fileSize = parseFloat(document.getElementById('fileSize').value);
      const fileUnit = document.getElementById('fileUnit').value;
      const speedMBps = parseFloat(document.getElementById('speed').value);

      if (isNaN(fileSize) || isNaN(speedMBps)) {
        document.getElementById('result').innerText = "Please enter valid numbers.";
        return;
      }

      const result = calculateUploadTime(fileSize, fileUnit, speedMBps);
      document.getElementById('result').innerText = `Upload time: ${result}`;
    }
  </script>
</body>
</html>
