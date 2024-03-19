# CSS-Assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Header Styling */
        header {
            background-color: #333;
            padding: 20px;
            color: white;
            text-align: center;
        }
        
        /* Introduction Section */
        #introduction {
            background-color: #f0f0f0;
            padding: 20px;
            margin-top: 20px;
            margin-bottom: 20px;
        }
        
        /* Skills Display */
        #skills {
            background-color: #eaeaea;
            padding: 20px;
            margin-top: 20px;
            margin-bottom: 20px;
        }
        
        #skills ul {
            list-style: none;
            padding: 0;
        }
        
        #skills ul li {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 10px;
        }
        
        /* Contact Information */
        #contact {
            background-color: #333;
            padding: 20px;
            color: white;
            text-align: center;
            margin-top: 20px;
            margin-bottom: 20px;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            header, #introduction, #skills, #contact {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>John Doe</h1>
    </header>

    <section id="introduction">
        <h2>Introduction</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ut libero nec nulla tincidunt feugiat. Aliquam erat volutpat.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Responsive Design</li>
        </ul>
    </section>

    <footer id="contact">
        <h2>Contact Information</h2>
        <p>Email: john@example.com</p>
        <p>Social Media: @johndoe</p>
    </footer>
</body>
</html>
