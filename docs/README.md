<!DOCTYPE html>
<html>
<head>
  <title>GitHub Page HTML Roadmap</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f2f2f2;
    }

    h1 {
      color: #333;
      text-align: center;
    }

    .roadmap {
      margin-top: 20px;
      border: 1px solid #ccc;
      background-color: #fff;
      padding: 20px;
    }

    .step {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
    }

    .step img {
      width: 30px;
      height: 30px;
      margin-right: 10px;
    }

    .step p {
      margin: 0;
      font-weight: bold;
    }

    .completed {
      color: green;
    }
  </style>
</head>
<body>
  <h1>GitHub Page HTML Roadmap</h1>
  <div class="roadmap">
    <div class="step">
      <img src="checkmark.png" alt="Checkmark">
      <p class="completed">Learn HTML</p>
    </div>
    <div class="step">
      <img src="checkmark.png" alt="Checkmark">
      <p class="completed">Learn CSS</p>
    </div>
    <div class="step">
      <img src="inprogress.png" alt="In Progress">
      <p>Learn JavaScript</p>
    </div>
    <div class="step">
      <img src="notstarted.png" alt="Not Started">
      <p>Build GitHub Page</p>
    </div>
  </div>

  <script>
    // Add event listener to each step to toggle completion
    const steps = document.querySelectorAll('.step');

    steps.forEach((step) => {
      step.addEventListener('click', () => {
        step.classList.toggle('completed');
      });
    });
  </script>
</body>
</html>
