# Survey_formCSS
<!DOCTYPE HTML>
<html lang="en">
<head>
  <title>Galgoteya University Student Survey Form</title>
<meta charset="UTF-8" />
  <link href="https://fonts.googleapis.com/css?family=Handlee" rel="stylesheet" type="text/css"/>
  <style>
    body 
		{background-color: peachpuff;
      text-align: center;
      font-family: 'Handlee', cursive;
      color: royalblue;}
    h2{
	padding: 30px;
	background-color: royalblue;
	color: white;}
    label {
display: block;
 margin-top: 10px;
}
    input[type="radio"],
    input[type="checkbox"] 
    {margin-right: 5px;}
    textarea {width: 100%;
	height: 100px;
}
    input[type="submit"] {
background-color: royalblue;
color: white;
border: none;
	padding: 10px 20px;
 cursor: pointer;
    }
  </style>
</head>
<body>
  <h2>Galgoteya University Student Survey Form</h2>
  <h4>Thank you for taking time to help us improve Sololearn</h4>
  <form action="url" autocomplete="off">
    <label>Name</label>
    <input type="text" name="Name" placeholder="First Name, Last Name" required/><br/><br/>
    <label>Email</label>
    <input type="email" name="email" placeholder="example@gmail.com" required/><br/><br/>
    <label>Age (optional)</label>
    <input type="number" name="age"/><br/><br/>
    <label>Gender</label><br>
    <input type="radio" name="gender" value="male"/>male
    <input type="radio" name="gender" value="female"/>female<br/><hr><br/>
    <label>Would you recommend Sololearn to a friend? </label><br>
    <input type="radio" name="recommend" value="yes"/>yes
    <input type="radio" name="recommend" value="no"/>no
    <input type="radio" name="recommend" value="maybe"/>maybe<br><br>
    <fieldset>
      <legend>Which option best describes your current role?</legend>
      <label>Option</label>
      <select id="myList" name="role">
        <option value="1">employed</option>
        <option value="2">student</option>
        <option value="3">unemployed</option>
        <option value="4">others</option>
      </select>
    </fieldset>
    <br>
    <label>What would you like to see improved on Sololearn? (select all that apply)</label><br>
    <input type="checkbox" name="improvement" value="Front-end projects"/>
    Front-end projects
    <input type="checkbox" name="improvement" value="Back-end projects"/>
    Back-end projects
    <input type="checkbox" name="improvement" value="Data visualization"/>Data visualization
    <input type="checkbox" name="improvement" value="Challenges"/>Challenges
    <input type="checkbox" name="improvement" value="Chat room"/>Chat room
    <input type="checkbox" name="improvement" value="Additional courses"/>Additional courses<br><br>
    <label>Any comment or suggestion</label><br>
    <textarea name="comment"></textarea><br><br>
    <input type="submit" value="Submit"><br><br>
  </form>
</body>
</html>
