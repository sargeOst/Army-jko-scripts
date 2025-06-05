# Army-jko-scripts
jko script


step 1 right click screen click inspect.
step 2 select console
step 3 next to console tab click on drop down menu (small grey triangle)
step 4 scroll to the top of selection menu click on TOP ( should have JKO URL next to it
step 5 insert script below and press enter note wait for the circle next to the lesson is half green before submitting.
step 6 after submitting code error paused in debugger will populate select the resume or play button next generally have to click twice, resume to next lesson, please note the debugger error will continue to pop up with every window refresh until the console window is closed .  Repeat then repeat steps 4-6 will only work on lessons not test or pretest.
    
 
API_1484_11.SetValue('cmi.completion_status','completed');
if (document.getElementsByName("courseheader").item(0).contentDocument.getElementById("c")) {
  document.getElementsByName("courseheader").item(0).contentDocument.getElementById("c").submit()
};



