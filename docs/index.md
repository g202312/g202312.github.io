<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Group 12</title>
    <style>

        .teammates {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }

        .teammate {
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 10px;
            margin: 10px;
            padding: 20px;
            max-width: 200px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }

        .teammate:hover {
            transform: translateY(-5px);
        }

        a {
            text-decoration: none;
            color: #007bff;
            font-weight: 600;
        }

        a:hover {
            text-decoration: underline;
        }
        .supervisor {
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 10px;
            margin: 0 auto; /* Center horizontally */
            padding: 20px;
            max-width: 200px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
            display: flex;
            flex-direction: column;
            align-items: center; /* Center vertically */
        }
    
        .supervisor:hover {
            transform: translateY(-5px);
        }    
    </style>
</head>
<body>
    <header>
        <h1>Group 12</h1>
    </header>
    
    <!-- Supervisor section -->
    <div class="supervisor">
        <h2>Supervisor Name</h2>
        <p>Role: Supervisor</p>
        <a href="https://example.com/supervisor-project">Explore me</a>
    </div>
    
    <!-- Teammates section -->
    <div class="teammates">
        <div class="teammate">
            <h2>Zi Yang</h2>
            <p>Role: Leader</p>
            <a href="https://example.com/project1">Explore me</a>
        </div>
        <div class="teammate">
            <h2>Bin Jia</h2>
            <p>Role: Leader</p>
            <a href="https://example.com/project2">Explore me</a>
        </div>
        <div class="teammate">
            <h2>Jianxu Shangguan</h2>
            <p>Role: Project Manager</p>
            <a href="https://example.com/project3">Explore me</a>
        </div>
        <div class="teammate">
            <h2>Eajun</h2>
            <p>Role: Learner</p>
            <a href="https://example.com/project4">Explore me</a>
        </div>
        <div class="teammate">
            <h2>asfasfasf</h2>
            <p>Role: Learner</p>
            <a href="https://example.com/project1">Explore me</a>
        </div>
    </div>
    
    <div class="project-link">
        <a href="https://example.com/current-project">Check Out Our Current Project</a>
    </div>
</body>
</html>
