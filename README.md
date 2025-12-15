<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>All HTML Tags Example</title>
</head>
<body>
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
  <p>This is a <b>bold</b>, <i>italic</i>, <u>underlined</u>, <mark>highlighted</mark>, 
     <del>deleted</del>, <ins>inserted</ins>, <sub>subscript</sub>, and <sup>superscript</sup> text.</p>
  <h3>Unordered List</h3>
  <ul>
    <li>Apple</li>
    <li>Banana</li>
    <li>Mango</li>
  </ul>

  <h3>Ordered List</h3>
   <ol>
    <li>First</li>
    <li>Second</li>
    <li>Third</li>
  </ol>
  <h3>Definition List</h3>
  <dl>
    <dt>HTML</dt>
    <dd>Hypertext Markup Language</dd>
    <dt>CSS</dt>
    <dd>Cascading Style Sheets</dd>
  </dl>
  <hr>
  <table border="1">
    <caption>Sample Table</caption>
    <thead>
      <tr>
        <th>Name</th>
        <th>Age</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>shamia</td>
        <td>23</td>
      </tr>
      <tr>
        <td>sultana</td>
        <td>25</td>
      </tr>
    </tbody>
  </table>
  <hr>
  <form>
    <label for="name">Name:</label>
    <input type="text" id="name" placeholder="Enter your name"><br><br>
    <label>Password:</label>
    <input type="password"><br><br>
    <label>Email:</label>
    <input type="email"><br><br>
    <label>Gender:</label>
    <input type="radio" name="gender"> Male
    <input type="radio" name="gender"> Female <br><br>
    <label>Hobbies:</label>
    <input type="checkbox"> Reading
    <input type="checkbox"> Traveling
    <input type="checkbox"> Sports <br><br>

    <label for="cars">Choose a car:</label>
    <select id="cars">
      <option>BMW</option>
      <option>Audi</option>
      <option>Tesla</option>
    </select><br><br>
    <textarea rows="4" cols="30">Write something...</textarea><br><br>
    <button type="submit">Submit</button>
    <input type="reset" value="Reset">
  </form>
  <hr>
  <h3>Audio</h3>
  <audio controls>
    <source src="sample.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
  <h3>Video</h3>
  <video width="320" height="240" controls>
    <source src="sample.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
<hr>
  <header><h2>Header Section</h2></header>
  <nav>
    <a href="#">Home</a> |
    <a href="#">About</a> |
    <a href="#">Contact</a>
  </nav>
  <main>
    <article>
      <h3>Article Title</h3>
      <p>This is an article section inside <code>&lt;article&gt;</code>.</p>
    </article>
    <section>
      <h3>Section Title</h3>
      <p>This is a section inside <code>&lt;section&gt;</code>.</p>
    </section>
    <aside>
      <h4>Aside</h4>
      <p>Side information in <code>&lt;aside&gt;</code>.</p>
    </aside>
  </main>
  <hr>
  <blockquote cite="https://www.example.com">This is a blockquote example.</blockquote>
  <pre>
    function hello() {
      console.log("Hello World");
    }
  </pre>
  <code>console.log("Inline code example");</code>
  <br>
  <abbr title="Hypertext Markup Language">HTML</abbr>
  <address>123 Street, City, Country</address>
  <progress value="70" max="100"></progress>
  <br>
  <meter value="0.6">60%</meter>

</body>
</html>

