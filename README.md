/* the code is to develop a to-do list*/
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>To-Do List</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <section class="container">
      <div class="heading">
        <img class="heading__img" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/756881/laptop.svg">
        <h1 class="heading__title">To-Do List</h1>
      </div>
      <form class="form">
        <div>
          <label class="form__label" for="todo">~ Today I need to ~</label>
          <input class="form__input"
               type="text" 
               id="todo" 
               name="to-do"
               size="30"
               required>
          <button class="button"><span>Submit</span></button>
        </div>
      </form>
      <div>
        <ul class="toDoList">
        </ul>
      </div>
    </section>
    <script src="script.js"></script>
  </body>
</html>
