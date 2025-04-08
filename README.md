<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="E-Content for IoT, MEMS, Virtual Instrumentation, and Industry 4.0 courses">
    <title>EIE E-Learning Courses</title>
    <link rel="stylesheet" href="css/style.css">
    <!-- Bootstrap Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
    <style>
        /* Embedded CSS for simplicity */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        .navbar {
            background-color: #2c3e50;
            padding: 1rem;
            color: white;
        }
        .navbar h1 {
            margin: 0;
            text-align: center;
        }
        .course-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2rem;
        }
        .course-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin: 1rem;
            padding: 1.5rem;
            width: 300px;
            transition: transform 0.3s;
        }
        .course-card:hover {
            transform: translateY(-5px);
        }
        .course-card h2 {
            color: #2c3e50;
            font-size: 1.5rem;
        }
        .course-code {
            color: #e74c3c;
            font-weight: bold;
        }
        .btn {
            display: inline-block;
            padding: 0.5rem 1rem;
            background: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
        }
        .btn:hover {
            background: #2980b9;
        }
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar">
        <h1>Department of Electronics and Instrumentation Engineering</h1>
    </nav>

    <!-- Course Grid -->
    <div class="course-container">
        <!-- Course 1: IoT -->
        <div class="course-card">
            <h2>IoT & Applications</h2>
            <p class="course-code">BTEI-T-PE-043</p>
            <p>Explore Internet of Things fundamentals, protocols, and real-world applications.</p>
            <a href="courses/iot/" class="btn">
                <i class="bi bi-file-earmark-ppt"></i> Access Content
            </a>
        </div>

        <!-- Course 2: MEMS -->
        <div class="course-card">
            <h2>MEMS & Sensor Design</h2>
            <p class="course-code">BTEI-T-PE-023</p>
            <p>Learn Micro-Electro-Mechanical Systems (MEMS) and sensor technologies.</p>
            <a href="courses/mems/" class="btn">
                <i class="bi bi-journal-bookmark"></i> Access Content
            </a>
        </div>

        <!-- Course 3: Virtual Instrumentation -->
        <div class="course-card">
            <h2>Virtual Instrumentation</h2>
            <p class="course-code">BTEI-T-OE-021 / BTEI-T-PE-017</p>
            <p>LabVIEW-based virtual instrumentation and data acquisition systems.</p>
            <a href="courses/virtual-instrumentation/" class="btn">
                <i class="bi bi-code-square"></i> Access Content
            </a>
        </div>

        <!-- Course 4: Industry 4.0 -->
        <div class="course-card">
            <h2>Industry 4.0</h2>
            <p class="course-code">BTEI-T-PE-026</p>
            <p>Smart manufacturing, IIoT, and cyber-physical systems.</p>
            <a href="courses/industry-4.0/" class="btn">
                <i class="bi bi-building-gear"></i> Access Content
            </a>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>© 2024 EIE Department | Developed by Dr. Ambarish G. Mohapatra</p>
        <p>Hosted on <a href="https://github.com/yourusername/your-repo" style="color: #3498db;">GitHub</a></p>
    </footer>

    <!-- Simple JavaScript for interactivity -->
    <script>
        // Add hover effect to course cards
        document.querySelectorAll('.course-card').forEach(card => {
            card.addEventListener('mouseover', () => {
                card.style.transform = 'translateY(-5px)';
            });
            card.addEventListener('mouseout', () => {
                card.style.transform = 'translateY(0)';
            });
        });
    </script>
</body>
</html>
