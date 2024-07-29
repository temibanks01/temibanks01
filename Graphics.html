<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JavaScript Graphics Mastery Example</title>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    background-color: #f0f0f0;
  }

  canvas {
    border: 1px solid #000;
    background-color: #fff;
    cursor: pointer;
  }
</style>
</head>
<body>
<canvas id="myCanvas" width="400" height="400"></canvas>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const canvas = document.getElementById('myCanvas');
  const ctx = canvas.getContext('2d');

  // Circle properties
  let circles = []; // Array to hold circle objects
  const numCircles = 5; // Number of circles
  const minRadius = 10;
  const maxRadius = 30;

  // Initialize circles with random positions and velocities
  for (let i = 0; i < numCircles; i++) {
    circles.push({
      x: Math.random() * (canvas.width - maxRadius * 2) + maxRadius,
      y: Math.random() * (canvas.height - maxRadius * 2) + maxRadius,
      dx: (Math.random() - 0.5) * 4, // Random velocity
      dy: (Math.random() - 0.5) * 4, // Random velocity
      radius: Math.random() * (maxRadius - minRadius) + minRadius,
      color: `rgb(${Math.random() * 255}, ${Math.random() * 255}, ${Math.random() * 255})`
    });
  }

  function drawCircle(circle) {
    ctx.beginPath();
    ctx.arc(circle.x, circle.y, circle.radius, 0, Math.PI * 2);
    ctx.fillStyle = circle.color;
    ctx.fill();
    ctx.closePath();
  }

  function clearCanvas() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
  }

  function update() {
    clearCanvas();

    circles.forEach(circle => {
      drawCircle(circle);

      // Boundary detection for bouncing effect
      if (circle.x + circle.radius > canvas.width || circle.x - circle.radius < 0) {
        circle.dx = -circle.dx;
      }
      if (circle.y + circle.radius > canvas.height || circle.y - circle.radius < 0) {
        circle.dy = -circle.dy;
      }

      // Update position
      circle.x += circle.dx;
      circle.y += circle.dy;
    });
  }

  function animate() {
    update();
    requestAnimationFrame(animate);
  }

  animate();

  // Interactive: Click to add a new circle at the clicked position
  canvas.addEventListener('click', function(event) {
    const rect = canvas.getBoundingClientRect();
    const mouseX = event.clientX - rect.left;
    const mouseY = event.clientY - rect.top;

    const newCircle = {
      x: mouseX,
      y: mouseY,
      dx: (Math.random() - 0.5) * 4,
      dy: (Math.random() - 0.5) * 4,
      radius: Math.random() * (maxRadius - minRadius) + minRadius,
      color: `rgb(${Math.random() * 255}, ${Math.random() * 255}, ${Math.random() * 255})`
    };

    circles.push(newCircle);
  });
});
</script>

</body>
</html>
