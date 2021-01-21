<header>
      <h2>Welcome to Zhichao Liu's Page</h2>
      <link rel="stylesheet" href="mystyle.css">
      <style>
        .grid-container {
            display: grid;
            grid-template-columns: auto auto auto;
            background-color: #2196F3;
            padding: 10px;
       }
       .grid-item {
           background-color: rgba(255, 255, 255, 0.8);
           border: 1px solid rgba(0, 0, 0, 0.8);
           padding: 10px;
           font-size: 10px;
           text-align: center;
      }
   </style>
</header>
   
<nav class="menu">
  <ol>
    <li><a href="#">Home</a></li>
    <li><a href="#Introduction">Introduction</a></li>
    <li><a href="#Han-Dynasty">Han Dynasty</a></li>
    <li><a href="#Chelsea-FC">Chelsea FC</a></li>
    <li><a href="#J-Animation">Animation</a></li>
    <li><a href="#Contact">Contact</a></li>
  </ol>
</nav>
   
   <p> You can find the <span>course website</span> in <a href="https://canvas.ucsd.edu/courses/21783">UCSD 110 Canvas</a> </p>
   <p> You can edit this file by changing the <a href="./_config.yml">configure file</a> </p>
  
<section class="Introduction" id="Introduction">
    <header>
      <h2>Introduction to myself</h2>
    </header>
    <section class = "personal-statement">
         <h4> Myself </h4>
         <p> My name is Zhichao Liu, a international student from China. And in this user page, I will introduce some interests I have.</p>
         <p> First of all, my favirate language is Java </p>
         <code> System.out.println ("I love Java!"); </code>  
         <p></p>
         <label for="language">Choose the language you like the most:</label>   
         <select name="language" id="language">
               <option value="">--Please choose an option--</option>
               <option value="Java">Java</option>
               <option value="C++/C">C/C++</option>
               <option value="Python">Python</option>
               <option value="Js">Java Script</option>
               <option value="Go">Go</option>
               <option value="Others">Others</option>
        </select> <br>
        <label for="b">Rate the percentage you expert it:</label>
        <form oninput="result.value=parseInt(b.value)">
             <input type="range" id="b" name="b" value="50" /> =
             <output name="result" for="output">50</output>
        </form>
    </section>
    <section class = "interests">
         <h4> Interests </h4>
         <p> Then, I will list my interests as ordered list: </p>
             <ol>
                  <li> Chinese Ancient History  </li>
                  <li> Soccer  </li>
                  <li> Drawing </li>
                  <li> Writing  </li>
                  <li> Japanese Animation </li>
             </ol>
    </section>
</section>
   
<hr>
<section class="Han-Dynasty" id="Han-Dynasty">
    <header>
      <h2>Information of Western Han Dynasty</h2>
    </header>
          <p> the Han dynasty (Chinese: <code>漢朝</code>; pinyin: Hàncháo) was the second imperial dynasty of China <em class="time">(202 BC – 220 AD)</em>, established by the rebel leader <strong class="name">Liu Bang</strong> and ruled by the <b class="name">House of Liu</b>. Preceded by the short-lived Qin dynasty <em class="time">(221–206 BC)</em> and a warring interregnum known as the Chu–Han contention <em class="time">(206–202 BC)</em>, it was briefly interrupted by the Xin dynasty <em class="time">(9–23 AD)</em> established by the usurping regent <strong class="name">Wang Mang</strong>, and was separated into two periods—the Western Han <em class="time">(202 BC–9 AD)</em> and the Eastern Han <em class="time">(25–220 AD)</em>, before being succeeded by the Three Kingdoms period <em class="time">(220–280 AD)</em>. </p>
    <aside>
        <p> <strong> Han Dyasty is one of the flourishing and powerful period in Chinese Ancient History </strong> </p>
    </aside>
    <div class="Pic for Han">
    <img width="600" height="400" src="https://images.chinahighlights.com/allpicture/2017/04/easternhan.jpg"
         alt="Han pic">
    <p>The map for Han Dyasty</p>
    </div>
    <hr>
    <section class="people">
        <h3>Founder</h3>
        <p>Bang Liu (Han Gao Zu)</p>
        <figure>
            <img width="200" height="250" src="https://www.holoong.com/uploadculture/big/052104153120143615.jpg"
                 alt="Liu Bang's pic">
             <figcaption><em>Liu Bang</em></figcaption>
        </figure>
        <h3>Famous Emperors</h3>
            <ul>
            <li>Che Liu (Han Wu) </li> 
            <li>Xun Liu(Han Xuan) </li>
            </ul>
        <h3>Great Generals</h3>
            <ul>
            <li>Xin Han</li> 
            <li>Qing Wei</li>
            <li>Qubing Huo</li>
            </ul>
        <table>
            <caption>Comparsion to these three talented generals</caption>
           <colgroup>
              <col>
              <col span="1" class="Xian Han">
              <col span="1" class="Qing Wei">
              <col span="1" class="Qubing Huo">
           </colgroup>
            <tr>
               <td> </td>
               <th scope="col">Xin Han</th>
               <th scope="col">Qing Wei</th>
               <th scope="col">Qubing Huo</th>     
            </tr>
            <tr>
              <th scope="row">Features</th>
              <td>Talented, stratagem</td>
              <td>Experienced, tranning</td>
              <td>Youngest, blitz</td>
            </tr>
        </table>
    </section>   
   <p> <a href="https://en.wikipedia.org/wiki/Han_dynasty">The reference</a> </p>
</section>
 
<hr>

<section class="Chelsea-FC" id="Chelsea-FC">
       <header>
            <h2>Introduction to Chelsea FC</h2>
       </header>
         <p> <strong>Chelsea Football Club </strong> are an English professional football club based in Fulham, London. Founded in <em>1905</em>, the club competes in the Premier League, the top division of English football. Chelsea are among England's most successful clubs, having won over <strong>thirty competitive honours</strong>, including <strong>six league titles</strong> and <strong>six European trophies</strong>. Their home ground is Stamford Bridge </p>       
       <div class = "pic for Chelsea">
           <img width="400" height="400" src="https://upload.wikimedia.org/wikipedia/en/thumb/c/cc/Chelsea_FC.svg/360px-Chelsea_FC.svg.png" alt="">
           <p>The symbol of Chelsea</p>
       </div>   
       <iframe width="600" height="400" src="https://www.youtube.com/embed/BYdnj9delqw" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
       <label for="Choose-Champion">Choose the Team you think is Champion in Premier League: </label>
           <select name="Choose-Champion" id="Choose-Champion">
                <optgroup label="Teams">
                   <option>Chelsea</option>
                   <option>Manchester City</option>
                   <option>Manchester United</option>
                   <option>Spurs</option>
                   <option>Arsenal</option>
                   <option>Liverpool</option>
                   <option>Leichester City</option>
                   <option>Others</option>
               </optgroup>
          </select>
      <form>
          <fieldset>
               <legend>Choose the ranking Chelsea will be: </legend>
                  <input type="radio" id="1" name="rank">
                        <label for="1">1st (Champion!)</label><br>
                  <input type="radio" id="2" name="rank">
                       <label for="2">2nd</label><br>
                 <input type="radio" id="3" name="rank">
                       <label for="3">3rd</label><br>
                 <input type="radio" id="4" name="rank">
                       <label for="4">4th</label><br>
                 <input type="radio" id=">4" name="rank">
                       <label for=">4">>4 (Oh No!)</label><br>
         </fieldset>
     </form>  
     <label for="truth">Tell you the truth:</label><br>
        <textarea id="truth" name="truth"
            rows="5" cols="33">
            Chelsea plays like shit this season, and I don't really expect it can enter top 4... :(
        </textarea> <br>
     <label for="percentage">Percentage you already read:</label>
              <progress id="percentage" max="100" value="70"> 70% </progress>
</section>

<hr>

<section class="J-Animation" id="J-Animation">
         <header>
                  <h2>Japanese Animation</h2>
         </header>
        <p> My favirate Animations are <a href="https://en.wikipedia.org/wiki/Attack_on_Titan">Attack on Titan</a> and <a href="https://en.wikipedia.org/wiki/Fullmetal_Alchemist">Fullmetal Alchemist</a> </p>
         <video controls width="600" height="400">
              <source src="./Fullmetal-Alchemist.mp4"
                     type="video/mp4">
               Sorry, your browser doesn't support embedded videos.
          </video>
         <picture>
             <source srcset="https://hb.imgix.net/efc2778399ad3916e3d0ecdd52d2baf506fe41ae.jpg?auto=compress,format&fit=crop&h=353&w=616&s=725ab9c50a405a056f72d00e76ac04d4" media="(min-width: 600px)">
             <img width="600" height="400" src="https://cdn1.i-scmp.com/sites/default/files/2015/06/15/maxresdefault.jpg" alt="" />
        </picture>
        <figure>
            <figcaption>Here is my favirate music in the animation:</figcaption>
            <audio
               controls
                 src="./YouSeeBIGGIRL.mp3">
                 Your browser does not support the <code>audio</code> element.
            </audio>
       </figure>
        <canvas width="300" height="100">
                Canvas for White.
        </canvas>
        <details>
            <summary>More</summary>
            That is the BGM from Attack on Titan!
        </details>
         <p> Now the question is: Do you like <strong> Animation </strong>? <br>
             If the answer is <strong> YES </strong>, tell me your favirate animation! </p>
        <form method="get" class="enter_animation">
               <div class="enter_animation">
                   <label for="YN">Yes or No: </label>
                   <input type="text" name="YN" id="YN" required>
               </div>
               <div class="enter_animation">
                    <label for="Animation">If yes, enter your favirate animation: </label>
                    <input type="text" name="Animation" id="Animation" required>
               </div>
               <div class="enter_animation">
                    <input type="submit" value="Subscribe!">
               </div>
       </form>
</section>

<hr>

<section class="Contact" id="Contact">
     <header>
        <h2>Contact to me</h2>
    </header>
    <p> If you have any interest in my project, feel free to send me message through email: <strong> z5liu@ucsd.edu </strong> </p>
    <p> In the future, I will use <em>CSS</em> and <em>JavaScript</em> to make the page more beautiful and active! </p>
    <p> For example, I may use the following code to change color/size/style of text! </p>
    <pre> 
      body1 {                         body2 {                                  body3 {
          color: red;                    font-size: .7rem;                         margin: 0;
      }                               }                                        }
    </pre>    
    <button class="support" type="button">
           Click this button if you like my page!
    </button>
    <svg viewBox="0 0 300 100" xmlns="http://www.w3.org/2000/svg" stroke="red" fill="grey">
       <circle cx="50" cy="50" r="40" />
    </svg>
    <label for="rate">Choose the rate for my page:</label>
         <input list="rate_page" id="rate" name="rate" />
         <datalist id="rate_page">
             <option value="5">5</option>
             <option value="4">4</option>
             <option value="3">3</option>
             <option value="2">2</option>
             <option value="1">1</option>
         </datalist>
</section>

<hr>

<h3> Address: </h3>
<p> 
    19 Lambert Drive, <br>
    Princeton, NJ <br>
    08540 <br>
    U.S <br>
</p>
<table>
         <thead> <tr>
             <th colspan="2">Date</th>
         </tr> </thead>
      <tbody> <tr>
            <td>Jan 14</td>
            <td>2021</td>
      </tr> </tbody>
</table>
 <div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>
  <div class="grid-item">7</div>
  <div class="grid-item">8</div>
  <div class="grid-item">9</div>
</div> 
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>
  <div>4</div>
  <div>5</div>
</div> 
<template id="productrow">
  <tr>
    <td class="record"></td>
    <td></td>
  </tr>
</template>

<footer>
      @Author: Zhichao Liu   
</footer>


