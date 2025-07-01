# input

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lists Demonstration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        h2 {
            color: #2980b9;
            margin-top: 30px;
        }
        ul, ol {
            margin-left: 20px;
        }
        dt {
            font-weight: bold;
            margin-top: 10px;
        }
        dd {
            margin-left: 20px;
            margin-bottom: 10px;
        }
    </style>
    </head>
    <body>
    <h1>HTML Lists Demonstration</h1>
    
    <section>
        <h2>1. Unordered List (Shopping List)</h2>
        <ul>
            <li>Milk</li>
            <li>Eggs</li>
            <li>Bread
                <ul>
                    <li>Whole wheat</li>
                    <li>Multigrain</li>
                </ul>
            </li>
            <li>Fruits
                <ul>
                    <li>Apples</li>
                    <li>Bananas</li>
                    <li>Oranges</li>
                </ul>
            </li>
            <li>Vegetables</li>
        </ul>
    </section>
    
    <section>
        <h2>2. Ordered List (Recipe Steps)</h2>
        <ol>
            <li>Preheat oven to 350°F (175°C)</li>
            <li>Grease a 9x13 inch baking pan</li>
            <li>Mix dry ingredients:
                <ol type="a">
                    <li>2 cups flour</li>
                    <li>1 cup sugar</li>
                    <li>1 tsp baking soda</li>
                </ol>
            </li>
            <li>Add wet ingredients:
                <ol type="i">
                    <li>1 cup milk</li>
                    <li>2 eggs</li>
                    <li>1/2 cup oil</li>
                </ol>
            </li>
            <li>Mix until smooth</li>
            <li>Pour into prepared pan</li>
            <li>Bake for 30-35 minutes</li>
        </ol>
    </section>
    
    <section>
        <h2>3. Definition List (Web Development Terms)</h2>
        <dl>
            <dt>HTML</dt>
            <dd>HyperText Markup Language - the standard markup language for creating web pages.</dd>
            
            <dt>CSS</dt>
            <dd>Cascading Style Sheets - used for describing the presentation of a document written in HTML.</dd>
            
            <dt>JavaScript</dt>
            <dd>A programming language that enables interactive web pages and is an essential part of web applications.</dd>
            
            <dt>Responsive Design</dt>
            <dd>An approach to web design that makes web pages render well on a variety of devices and window or screen sizes.</dd>
        </dl>
    </section>
    
    <section>
        <h2>Combination Example</h2>
        <dl>
            <dt>Programming Languages</dt>
            <dd>
                <ul>
                    <li>Web Development
                        <ol>
                            <li>JavaScript</li>
                            <li>TypeScript</li>
                        </ol>
                    </li>
                    <li>Mobile Development
                        <ol>
                            <li>Swift (iOS)</li>
                            <li>Kotlin (Android)</li>
                        </ol>
                    </li>
                </ul>
            </dd>
        </dl>
    </section>
    </body>
    </html>
# output

![html1](https://github.com/user-attachments/assets/3cc8baf4-16a0-47de-a255-77413ad1643c)

![html 2](https://github.com/user-attachments/assets/e3fe7460-8359-4a63-beb5-54098c101862)
