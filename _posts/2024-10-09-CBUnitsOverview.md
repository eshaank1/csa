---
comments: true
layout: post
title: College Board Units Overview
courses: { compsci: {week: 7} }
type: hacks 
---

<head>
    <title>AP CSA Study Guide</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
            color: black; /* Set text color to black */
        }

        .container {
            max-width: 800px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        .unit {
            margin-bottom: 20px;
            padding: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .unit h2 {
            color: #007BFF;
        }

        /* Set color of list items to black */
        .unit ul li {
            color: black; /* Change list item text color to black */
        }

        .info-btn {
            background-color: #007BFF;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        .info-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>AP CSA Study Guide</h1>
        
        <div class="unit" id="unit1">
            <h2>Unit 1: Primitive Types</h2>
            <ul>
                <li>Data Types: Understand primitive data types (int, double, char, boolean) and their characteristics.</li>
                <li>Variable Declaration: Learn to initialize variables of different primitive types.</li>
                <li>Type Conversion: Implicit and explicit type conversion.</li>
            </ul>
            <button class="info-btn" data-link="https://eshaank1.github.io/csa/csa/unit1/intro">More Info</button>
        </div>

        <div class="unit" id="unit2">
            <h2>Unit 2: Using Objects</h2>
            <ul>
                <li>Object Creation: Understand how to create and use objects, including calling methods.</li>
                <li>Method Return Types: Learn about void and non-void return types in method definitions.</li>
                <li>Wrapper Classes: Explore wrapper classes for primitive types (e.g., Integer, Double).</li>
            </ul>
            <button class="info-btn" data-link="https://eshaank1.github.io/csa/csa/unit2/period3/home/">More Info</button>
        </div>

        <div class="unit" id="unit3">
            <h2>Unit 3: Boolean Expressions and if Statements</h2>
            <ul>
                <li>Boolean Logic: Understand boolean expressions and their evaluation.</li>
                <li>Conditional Statements: Implement if, else if, and switch statements to control program flow.</li>
                <li>Loops: Use while and for loops to handle repetitive tasks in code.</li>
            </ul>
            <button class="info-btn" data-link="https://eshaank1.github.io/csa/csa/unit3-p1/unit3-1">More Info</button>
        </div>

        <div class="unit" id="unit5">
            <h2>Unit 5: Writing Classes</h2>
            <ul>
                <li>Class Definition: Learn how to define classes, including fields and methods.</li>
                <li>Encapsulation: Understand the principles of encapsulation and data hiding using access modifiers.</li>
                <li>Constructors: Explore how to create and use constructors for initializing objects.</li>
            </ul>
            <button class="info-btn" data-link="https://eshaank1.github.io/csa/csa/period1/unit5/intro">More Info</button>
        </div>

        <div class="unit" id="unit6">
            <h2>Unit 6: Arrays</h2>
            <ul>
                <li>Array Declaration and Initialization: Learn how to declare and initialize arrays.</li>
                <li>Array Manipulation: Explore techniques for accessing and modifying array elements.</li>
                <li>Multi-Dimensional Arrays: Understand the use of 2D arrays and their applications.</li>
            </ul>
            <button class="info-btn" data-link="https://eshaank1.github.io/csa/csa/unit6-p1/">More Info</button>
        </div>

        <div class="unit" id="unit7">
            <h2>Unit 7: ArrayLists</h2>
            <ul>
                <li>ArrayList Basics: Understand how to use ArrayLists for dynamic data storage.</li>
                <li>Common Methods: Learn about common ArrayList methods (add, remove, get, size).</li>
                <li>Iteration: Use loops and enhanced for loops to iterate through ArrayLists.</li>
            </ul>
            <button class="info-btn" data-link="https://eshaank1.github.io/csa/csa/unit7-p1/unit7-homepage">More Info</button>
        </div>

        <div class="unit" id="unit8">
            <h2>Unit 8: 2D Arrays</h2>
            <ul>
                <li>2D Array Usage: Explore the creation and manipulation of two-dimensional arrays.</li>
                <li>ArrayList of Objects: Learn how to create and manage ArrayLists containing objects.</li>
                <li>Nested Loops: Understand the use of nested loops for working with 2D arrays and ArrayLists of objects.</li>
            </ul>
            <button class="info-btn" data-link="https://eshaank1.github.io/csa/unit8lesson-p1">More Info</button>
        </div>

        <div class="unit" id="unit9">
            <h2>Unit 9: Inheritance</h2>
            <ul>
                <li>Inheritance Basics: Understand the concept of inheritance and its purpose in object-oriented programming.</li>
                <li>Super and Subclass Relationships: Learn how to create subclasses and use the super keyword.</li>
                <li>Method Overriding: Explore method overriding and its significance in polymorphism.</li>
            </ul>
            <button class="info-btn" data-link="https://eshaank1.github.io/csa/inheritance">More Info</button>
        </div>
    </div>

    <script>
        document.querySelectorAll('.info-btn').forEach(button => {
            button.addEventListener('click', function() {
                const link = this.getAttribute('data-link'); // Get the link from the data-link attribute
                if (link) {
                    window.location.href = link; // Redirect to the link
                } else {
                    const unitTitle = this.parentElement.querySelector('h2').innerText;
                    alert(`More information about ${unitTitle} will go here!`);
                }
            });
        });
    </script>
</body>

<style> 
@import url('https://fonts.googleapis.com/css2?family=Roboto');
h1 { text-align: center; font-size: 50px; color: #0352fc; font-family: 'Roboto', serif; }
h2 { text-align: left; font-size: 18px; color: #0352fc; }
body { text-align: left; font-size: 15px; font-family: 'Roboto', serif; background: black; color: black; } /* Set body text color to black */
</style>