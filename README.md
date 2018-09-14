# surveyform

<!DOCTYPE html>
<html>
  <head>
      <title>Survey Form</title>
      <link rel="stylesheet" type="text/css" href="surveyform.css">
      <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js">

      </script>
  </head>

    <body>
      <h1 id="title">Survey Form</h1>

      <p id="description">Let us know what you like</p>

      <form class="survey-form" action="index.html" method="post">
          <div class="survey-form">
            <label for="name" id="name-label">Name:</label>
            <input placeholder="Full Name" type="text" name="name" id="name" required>
          </div>

          <div class="survey-form">
            <label for="email" id="email-label">Email:</label>
            <input placeholder="Email Address" type="email" name="email" id="email" required>
          </div>

          <div class="survey-form">
            <label for="number" id="number-label">Age:</label>
            <input type="number" name="number" id="number" placeholder="Age" min="0" max="100" required>
          </div>

          <div class="survey-form">
            <label for="Which option best describes your current role?">Which option best describes your current role?</label>

            <select  class="dropdown">
              <option value="Student">Student</option>
              <option value="Full Time Job"> Full Time Job</option>
              <option value="Full Time Learner">Full Time Learner</option>
              <option value="Rather Not Say">Rather Not Say</option>
              <option value="Other">Other</option>
            </select>
          </div>

          <p>How likely is that you would recommend Us to a friend?</p>

          <div class="survey-form">
            <input type="radio" name="recommendation" value="Definitly" id="choice1">
            <label for="choice1"> Definitly</label>

            <input type="radio" name="recommendation" value="Maybe" id="choice2">
            <label for="choice2"> Maybe</label>

           <input type="radio" name="recommendation" value="Not sure" id="choice3">
           <label for="choice3"> Not sure</label>
          </div>

      </form>



    </body>
</html>
