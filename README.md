# Ex08 CAMU Schedule using Bootstrap
## Date:16/03/2026

## AIM:
To design a responsive and visually appealing CAMU Schedule using Bootstrap.

## DESIGN STEPS:
### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Add the Bootstrap CDN link inside the <head> section.

### Step 5:
Insert a table element with Bootstrap table classes.

### Step 6:
Construct the complete table.

### Step 7:
Add a header/footer displaying copyright information.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM :
```html
<!doctype html>
<html lang="en">
  <head>
    <title>Document</title>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css"
    />
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  </head>
  <body>
    <div class="container-fluid">
      <br />
      <div class="row">
        <div class="col-xs-12 col-sm-6">
          <h3 class="text-primary">Exam Schedule List</h3>
        </div>
        <div class="col-xs-12 col-sm-6 text-right">
          <div class="btn-group">
            <button type="button" class="btn btn-info">
              Schedule Now <span class="caret"></span>
            </button>
            <button type="button" class="btn btn-success">
              More <span class="caret"></span>
            </button>
            <button type="button" class="btn btn-warning">
              Print <span class="caret"></span>
            </button>
            <button type="button" class="btn btn-primary">
              Add Exam <span class="glyphicon glyphicon-plus"></span>
            </button>
          </div>
        </div>
      </div>

      <hr />

      <div class="table-responsive">
        <table class="table table-hover">
          <thead>
            <tr class="active">
              <th>Examination</th>
              <th>Semester/Section</th>
              <th>Department ID</th>
              <th>Start date</th>
              <th>End Date</th>
              <th class="text-right">Action</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>IAPR - EXPERIMENT MARKS</td>
              <td>EVEN</td>
              <td>AI</td>
              <td>23-Feb-2026</td>
              <td>23-Feb-2026</td>
              <td class="text-right">
                <span class="glyphicon glyphicon-trash text-danger"></span>
              </td>
            </tr>
            <tr>
              <td>ML - MODEL PRACTICAL</td>
              <td>EVEN</td>
              <td>AI</td>
              <td>18-Feb-2026</td>
              <td>18-Feb-2026</td>
              <td class="text-right">
                <span class="glyphicon glyphicon-trash text-danger"></span>
              </td>
            </tr>
            <tr>
              <td>SA - SKILL ASSESSMENT</td>
              <td>EVEN</td>
              <td>AI</td>
              <td>16-Feb-2026</td>
              <td>16-Feb-2026</td>
              <td class="text-right">
                <span class="glyphicon glyphicon-trash text-danger"></span>
              </td>
            </tr>
            <tr>
              <td>CIA - INTERNAL ASSESSMENT</td>
              <td>EVEN</td>
              <td>AI</td>
              <td>14-Feb-2026</td>
              <td>14-Feb-2026</td>
              <td class="text-right">
                <span class="glyphicon glyphicon-trash text-danger"></span>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2026-03-16 115540.png>)
## RESULT:
A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
