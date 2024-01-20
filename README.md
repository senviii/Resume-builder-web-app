<h2> Resume Builder Web Application, providing users with a user-friendly platform to craft, customize, and share compelling resumes.</h2>
<h3>Traditional resume-building methods often lack modern features and accessibility, making it challenging for users to create, manage, and present their resumes efficiently. To address this need, our goal is to develop a Resume Builder Web Application, providing users with a user-friendly platform to craft, customize, and share compelling resumes</h3>
<h2>Introduction</h2>
<h3>Involved in utilizing Django, Python, HTML, CSS, and Bootstrap to create a robust web application. The procedure included implementing a user signup/login system, a profile form for information input, integrating Django Summernote for customization, and rendering the entered data into a predefined CV template</h3>
<h2>Procedure</h2>
<h3>Procedure involved utilizing Django, Python, HTML, CSS, and Bootstrap to create a robust web application.:
1. Add Resume
  - Handle the POST request to add a resume.
   - Read resume fields from the request object.
   - Create a Profile object with the resume fields.
   - Save the Profile object in the database.
   - Redirect to the addResume page with a success message.
2. List Resumes
               - Read the current user's username from the request object.
              - Check if any profiles exist for the current user.
              - If profiles exist, retrieve and pass them to the ListResume.html template for rendering.
3. View Resume
               - Retrieve a user's profile using their ID from the database.
               - Pass the profile data to the viewResume.html template for rendering.</h3>
