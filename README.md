# Technical-Documentation-Page
A HTML project to Build a Technical Documentation Page
** start of undefined **

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Python Technical Documentation</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <nav id="navbar">
    <header>Python Documentation</header>
    <a class="nav-link" href="#Introduction">Introduction</a>
    <a class="nav-link" href="#Syntax_and_Structure">Syntax and Structure</a>
    <a class="nav-link" href="#Data_Types">Data Types</a>
    <a class="nav-link" href="#Control_Flow">Control Flow</a>
    <a class="nav-link" href="#Functions_and_Modules">Functions and Modules</a>
  </nav>

  <main id="main-doc">
    <section class="main-section" id="Introduction">
      <header>Introduction</header>
      <p>Python is a high-level, interpreted programming language known for its readability and simplicity.</p>
      <p>It is widely used in web development, data analysis, artificial intelligence, and more.</p>
      <p>Created by Guido van Rossum, Python emphasizes code readability with its use of significant indentation.</p>
      <code>print("Hello, World!")</code>
      <ul>
        <li>Easy to learn</li>
        <li>Open-source</li>
        <li>Extensive libraries</li>
      </ul>
    </section>

    <section class="main-section" id="Syntax_and_Structure">
      <header>Syntax and Structure</header>
      <p>Python uses indentation to define blocks of code instead of braces.</p>
      <p>Statements end with a newline, not a semicolon (although semicolons are allowed).</p>
      <p>Functions are defined using the <code>def</code> keyword.</p>
      <code>if x > 0:</code>
      <code>    print("Positive")</code>
      <ul>
        <li>Indentation is critical</li>
        <li>Whitespace matters</li>
      </ul>
    </section>

    <section class="main-section" id="Data_Types">
      <header>Data Types</header>
      <p>Python supports various built-in data types such as integers, floats, strings, and booleans.</p>
      <p>Collections include lists, tuples, sets, and dictionaries.</p>
      <p>Dynamic typing allows variables to change types.</p>
      <code>x = 42</code>
      <code>y = "Python"</code>
      <ul>
        <li>int</li>
        <li>float</li>
        <li>list</li>
        <li>dict</li>
      </ul>
    </section>

    <section class="main-section" id="Control_Flow">
      <header>Control Flow</header>
      <p>Python provides if-elif-else statements for conditional branching.</p>
      <p>Loops include for and while, with optional else clauses.</p>
      <p>Break and continue modify loop execution.</p>
      <code>for i in range(5):</code>
      <code>    print(i)</code>
      <ul>
        <li>if</li>
        <li>for</li>
        <li>while</li>
        <li>break</li>
        <li>continue</li>
      </ul>
    </section>

    <section class="main-section" id="Functions_and_Modules">
      <header>Functions and Modules</header>
      <p>Functions help organize code into reusable blocks.</p>
      <p>Modules group related functions and variables into files.</p>
      <p>Standard and third-party modules can be imported using the import statement.</p>
      <code>def greet(name):</code>
      <code>    return "Hello " + name</code>
      <ul>
        <li>def</li>
        <li>import</li>
        <li>return</li>
      </ul>
    </section>
  </main>
</body>
</html>


** end of undefined **

** start of undefined **

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

body {
  display: flex;
  min-height: 100vh;
  line-height: 1.6;
}

#navbar {
  width: 250px;
  background-color: #f4f4f4;
  padding: 1rem;
  border-right: 2px solid #ccc;
  position: fixed;
  height: 100vh;
  overflow-y: auto;
}

#navbar header {
  font-size: 1.5rem;
  margin-bottom: 1rem;
  font-weight: bold;
}

.nav-link {
  display: block;
  margin: 0.5rem 0;
  color: #333;
  text-decoration: none;
}

.nav-link:hover {
  color: #007bff;
}

#main-doc {
  margin-left: 270px;
  padding: 2rem;
  flex: 1;
}

.main-section {
  margin-bottom: 2rem;
}

.main-section header {
  font-size: 1.25rem;
  margin-bottom: 1rem;
  font-weight: bold;
}

code {
  background: #eee;
  padding: 0.2rem 0.5rem;
  display: block;
  margin: 0.5rem 0;
  border-left: 3px solid #007bff;
  white-space: pre-wrap;
}

ul {
  margin: 1rem 0;
  padding-left: 2rem;
}

li {
  margin-bottom: 0.5rem;
}

/* Media Query for smaller screens */
@media (max-width: 768px) {
  body {
    flex-direction: column;
  }

  #navbar {
    position: relative;
    width: 100%;
    height: auto;
    border-right: none;
    border-bottom: 2px solid #ccc;
  }

  #main-doc {
    margin-left: 0;
    padding: 1rem;
  }
}


** end of undefined **

