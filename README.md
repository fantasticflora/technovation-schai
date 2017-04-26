<div id="Page1" class="page" style="">
  <div style="background-color:white; padding:10px;">
    <h1 style="font-family:verdana; text-align:center; font-size:280%;">SCHAI</h1>
    <h2 style="font-family:courier; text-align:center;">Safe, Clean, Health, Activity Installment</h2>
    <h4 style="text-align:center;">Have you ever experienced sudden changes in temperaure?<br> We all have(don't worry)</h4>
    <h4 style="text-align:center;">This is the Answer! </h4>
    <div style="background-color:aqua;color:black;padding:25px;">
      <p style="text-align:center;">Our app informs you about any possible allegens in the air and plan your activites accordingly. </p>
    </div>
    <h4 style="text-align:center;">Why struggle in horrible weather if you can</h4>
    <h3 style="text-align:center;">choose SCHAI?</h3>
    <h2 style="text-align:center; background-color:aqua;color:black;padding:25px;">This is the solution you've been waiting for! </h2>
    <p style="text-align: center;">To continue, click <span onclick="show('Page2');">here!</span>
    </p>
  </div>
</div>
<div id="Page2" class="page" style="display:none">
  <div style="font-family:verdana; background-color:white; padding:10px;">
    <div style="text-align: center;">
      <h1>
     SCHAI
     </h1>
      <h3>
     Today's Weather
     </h3>
    </div>
  </div>
  <norm>
    <div style="font-family:verdana; font-size:100%; background-color:white; padding:15px;">
      <iframe
  style="width: 100%; height: 300px"
  src="https://openweathermap.org/api/pollution/co/embedded/">
</iframe>
      <p>
        If today is sunny...
      </p>
      <p>
        Pollen Count is about 10ppm
      </p>
      <p>
        This means that unless you have severe asthma or allergies, you will blossom today in the sun. Also, stay hydrated to avoid heat stroke. 
      </p>
      <p>
        This was updated on
      </p>
      <p id="date"></p>
      <p>
        Some activities: play a sport, have a picnic, go to a beach, drink a cold smoothie!
      </p>
      <p>
       Doesn't seem right?
      </p>
    </div>
  </norm>
  <p style="text-align: center; background-color:silver;color:black;padding:25px;"><span onclick="show('Page3');">Click here</span>
  </p>
  <script>
    document.getElementById("date").innerHTML = Date();

  </script>
</div>
<div id="Page3" class="page" style="display:none">
  <div style="background-color:white; padding:10px;">
    <h1 style="font-family:verdana; text-align:center; ">Today's Weather </h1>
    <div style="font-family:verdana; font-size:90%; background-color:white; padding:15px;">
    <h2 style="font-family:verdana; text-align:center; ">Raining</h2>
     <p>
        Today is raining, so be sure to take an umbrella or a raincoat! People with asthma should watch careful today as well as people with pollen allergies, as it increases with humidity. 
      </p>
      <p>
        If it's particularly cold, be sure to keep warm with a jacket or coat to avoid getting hypothermia. If you happen to have Seasonal Affected Disorder, find enjoyable activites to do, such as aerobic exercises. 
      </p>
      <p>
        Some activites to try: baking, watching movies, indoor exercises, and build a fort. 
      </p>
      <p>
        Please click 'continue' if today's weather is different 
      </p>
    </div>
    <span style="text-align:center" onclick="show('Page4');">Continue</span>
  </div>
</div>
<div id="Page4" class="page" style="display:none">
  <h1 style="font-family:verdana; text-align:center; font-size:280%;">Today's weather: Cloudy and cold</h1>
  <p>
    Make sure to bring a hat or ear muffs to cover your ears! Also remember to bundle up to avoid frostbites and the flu. 
  </p>
  <p>
  Activities to try: Go for a run to warm up, go for a hike, cook an elaborate, warm dinner. 
  </p>
  <span onclick="show('Page5');">Continue</span>
</div>

<div id="Page5" class="page" style="display:none">
  <div style="background-color:white; padding:10px;">
    <h1 style="font-family:verdana; text-align:center; font-size:280%;">If it's snowing...</h1>
    <p>
      Asthma and pollen tends to increase with snowy weather. Arthritis pains also increase with colder weather. Remember to stay hydrated, as not many people think about it.  
    </p>
    <p>
      Activities: skiing, tubing, snowboarding, ice-skating, building a snowman, lighting the fireplace, make a cup of cocoa. 
    </p>
    
   
  
  </div>
  <div style="background-color:aqua; padding:15px; text-align:center">
    <span onclick="show('Page6');">Continue</span>
  </div>
</div>

<div id="Page6" class="page" style="display:none">
  <h1 style="font-family:verdana; text-align:center; font-size:280%;">SCHAI</h1>
  <p>
    Thanks for using SCHAI. We hope you had a wonderful experience that helped you through any weather changes. If not, we will work on improving.
  </p>
  <p>
    If you wish to give us feedback or have questions, fill out the following form.
  </p>
  <br> Email:
  <br>
  <input type="text" name="email">
  <br> Comments:
  <br>
 <input type="text" name="comments">
  <p>
  Come back soon!
  <p>
 </div>
  <div style="background-color:silver; padding:15px; text-align:center">
    <span onclick="show('Page8');">Finish Up</span>
  </div>

<div id="Page8" class="page" style="display:none">
  <h1 style="font-family:verdana; text-align:center; font-size:280%;">Bye!</h1>
 
