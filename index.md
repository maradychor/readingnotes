<!DOCTYPE html>
<html>
  <head>
    <title>Welcome to Seattle!</title>
    <style>
      h1 {
        background-color: green;
        color: white;
      }
      p {
        background-color: red;
        color: white;
      }
      body {
        padding: 150px;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>
        Class Lab 1
      </h1>
    </header>
    <main>
      <p>
        Have you been to Pike Place Market?
      </p>
    </main>
    <script>
      let count = 1;
      let question = 'Do you like the rain?';
      let answer = prompt(question); // ask the user something, and return what they type.

      let userLovessea = confirm("Do you want to see the Space Needle"); // ask the user something they can yes / no

      let answerString = "Answer to question 1: " + answer + " " + "Answer to question 2: " + userLovessea;

      if (userLovessea) {
        alert('Great, me too!');
      } else {
        alert('Aww maybe next time!');
      }

      alert(answerString);

      document.write(answer); // outputs something the actual website;
    </script>
  </body>
</html>