# FCC-Functional-Feedback-Form
Small simple form for getting feedback with checkboxes, and radios and a general comments box

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Survey Form</title>
  </head>
  <body>
    <h1 id='title'>Louis' Coding Feedback Form</h1>
      <p id='description'>This is just a short form to get feedback on FCC</p>
     <form id='survey-form'>
       <fieldset>
          <legend>Personal Information</legend>
          <label for="name" id='name-label'>Name (required):</label>
          <input 
          type="text" 
          id="name" 
          name="name" 
          placeholder="Ex. John Doe" 
          required size="20">
<label for="email" id='email-label'>Email address (required):</label>
           <input
            placeholder="example@email.com"
            required
            id="email"
            type="email"
            name="email"
            size="20"/>
<label for="number" id='number-label'>Age (required):</label>  
           <input 
           placeholder='15'
           type='number'
           name='number'
           id='number'
           min='15'
           max='100'>
</fieldset>
<fieldset>
  <label>How would you describe your current situation?</label>
<select id="dropdown">
 <option value="0">Select current role</option>
 <option value="1">Student</option>
 <option value="2">Full Time Job</option>
 <option value="3">Full Time Learner</option>
 <option value="4">Prefer not to say</option>
 <option value="5">Other</option>
 </select>
</fieldset>
<fieldset>
  <label>Would you reccomend Free Code Camp to a friend?</label>
<label>
<input 
type='radio' 
class='inline'
name='attribute'
value='1'
checked />Definitely</label>
<input 
type='radio' 
class='inline'
name='attribute'
value='2'/>Maybe</label>
<input 
type='radio' 
class='inline'
name='attribute'
value='3'/>No</label>
</fieldset>
<fieldset>
  <label>What would you like to see improved? <small>(Check all that apply)</small> </label>
 <label><input type="checkbox" class="inline"value="front-end-projects" /> Front-end Projects</label>
      <label><input type="checkbox" class="inline" value="back-end-projects" /> Back-end Projects</label>
        <label><input type="checkbox" class="inline" value="data-visualization" /> Data visualization</label>
        <label><input type="checkbox" class="inline" value="challenges" /> Challenges</label>
        <label><input type="checkbox" class="inline" value="open-source-community" /> Open Source Community</label>
        <label><input type="checkbox" class="inline" value="gitter-help-rooms" /> Gitter help rooms</label>
        <label><input type="checkbox" class="inline" value="videos" /> Videos</label>
        <label><input type="checkbox" class="inline" value="city-meetups" /> City Meetups</label>
        <label><input type="checkbox" class="inline" value="wiki" /> Wiki</label>
        <label><input type="checkbox" class="inline" value="forum" /> Forum</label>
        <label><input type="checkbox" class="inline" value="additional-courses" /> Additional Courses</label>
</fieldset>
<fieldset>
<label for="comments">Other Comments?</label>
        <textarea cols="30" rows="10" name="comments" id="comments"></textarea>
</fieldset>
<button id='submit'>Submit</button>
</form>
</body>
</html>
