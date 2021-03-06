
 <!DOCTYPE html>
  <html>
    <head>
      <!--Import Google Icon Font-->
      <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
      <!--Import materialize.css-->
      <!--<link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/>-->
	  <!-- Compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

      <!--Let browser know website is optimized for mobile-->
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
	  <style>
		body{
			font-size:large;
		}
	  .para-bold{
		font-weight: bold;
	  }
	  .sub-heading{
		font-weight: bold;
		color:#3498DB;
	  }
	  .collapsible-header{
		font-weight: bold;
		color:#52BE80 ;
	  }
	  .positive-text{
		font-size:x-large;
		color:#28B463  ;
	  }
	  .remember-text{
	  color:#E67E22  ;
	  font-size:x-large;
	  }
	  .step-text{
	  color:#566573 ;
	  font-weight: bold;
	  }
	  </style>
    </head>

    <body>
	
		<div class="container">
        <!-- Navbar goes here -->

			<!-- Page Layout here -->
			<div class="row">

			  <div class="col s12 m4 l3"> <!-- Note that "m4 l3" was added -->
				<!-- Grey navigation panel

					  This content will be:
				  3-columns-wide on large screens,
				  4-columns-wide on medium screens,
				  12-columns-wide on small screens  -->

			  </div>

			  <div class="col s12 m8 l9"> <!-- Note that "m8 l9" was added -->
				<!-- Teal page content-->
				
				
				<h4 style="color: #3498DB">2.2	&nbsp;AC Electric Circuit Analysis </h4>
				<p class = "para-bold">
				By the end of this section you should be able to analyze an electric AC system consisting of passive components with the help of complex values of different quantities.
				</p>
				<p>
				<span class="sub-heading">Things you need to know:</span>
					<ul style="margin-left: 5%;">
						<li>&bull;&nbsp;&nbsp;EET 2301 Electricity Network Theory Knowledge.</li>
						<li>&bull;&nbsp;&nbsp;Sinusoidal wave representation (relevant mathematical knowledge)</li>
						
								<li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Phase	</li>
								<li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Initial Phase	</li>
								<li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Amplitude vs R.M.S value	</li>
								<li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;o	Frequency vs Periodic Time	</li>
						
						<li>&bull;&nbsp;&nbsp;A little bit of complex number theory</li>
						<li>&bull;&nbsp;&nbsp;Electricity Basics</li>
						<li>&bull;&nbsp;&nbsp;In addition, I highly recommend you to read 'Class Note 03' and previous material</li>
						<li style="font-weight:bold;">&bull;&nbsp;&nbsp;All the things coming here are from the things I have already covered in lectures. So consider this as a review.</li>
					</ul>
				</p>
				<p>
				<span class="sub-heading">At the end of this lesson:</span><br /> 
				You should be able to,
					<ul style="margin-left: 5%;">
						<li>&bull;&nbsp;&nbsp;Analyse an AC electric circuit using complex forms of currents, voltages and impedances with the help of a scientific calculator.
						</li>
					</ul>
				</p>
				<h5 style="color: #3498DB">2.2.1	&nbsp;AC Electric Circuit Analysis Using Complex Numbers </h5>
					<p>
						Let's try to apply the theory coming under class note 03 in the following problems and solve them.
					</p>
					
					  <!-- <ul class="collapsible">
						<li>
						  <div class="collapsible-header"><i class="material-icons">edit</i>Sample Problem 2.2.1.a</div>
						  <div class="collapsible-body"><span>Lorem ipsum dolor sit amet.</span></div>
						</li>
						<li>
						  <div class="collapsible-header"><i class="material-icons">edit</i>Sample Problem 2.2.1.b</div>
						  <div class="collapsible-body"><span>Lorem ipsum dolor sit amet.</span></div>
						</li>
					  </ul> -->
					  <ul class="collapsible">
						<li>
						  <div class="collapsible-header"><i class="material-icons">edit</i>Sample Problem 2.2.1.a</div>
						  <div class="collapsible-body"><p><span>Consider the following simple circuit:</span><br/>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image16.png" ></span> <br/>
						  As you may be already aware,<br/>
						  <ul style="margin-left: 5%;">
							<li>V - an AC voltage source with constant R.M.S value and Constant frequency</li>
							<li>VR, VL - the voltage drop components through each element.</li>
							<li>ZR, ZL - the impedance of each element.</li>
							<li>I - Current through circuit.</li>
						  </ul>
						Now, If you know some of the values, <br/>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image43.png" ></span> <br/>  
						Can you find the unknown components?<br/>
						<span class="positive-text">Don’t worry!</span>&nbsp;All you need to know is <span class = "remember-text">electricity network theory</span>. And, if you can analyze any DC circuit, then you can analyze any AC circuit.
						  </p>
							  <ul class="collapsible">
							<li>
							  <div class="collapsible-header"><i class="material-icons">info</i>Did you know?</div>
							  <div class="collapsible-body">
							  <p>
								Here the values are given in the complex polar form. <br/>
							  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image15.png" ></span> <br/>  
							  Complex numbers are one way to represent AC quantities such as currents, voltages and even impedances.<br/>
								Here the Angle theta given in degrees is called the Argument while the number in front is called as the magnitude of the number. Argument can be any real value either in degrees or radians and the magnitude is preferred to be positive when not equal to zero.<br/>
								The same number may re-written using Cartesian coordinates as,
								<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image8.png" ></span> <br/>  
								And it can be proved that,<br/>
								<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image12.png" ></span> <br/>  
								
							  </p>
							  </div>
							</li>  
							<li>
							  <div class="collapsible-header"><i class="material-icons">question_answer</i>Answer</div>
							  <div class="collapsible-body"><span>Considering the analogy to DC circuits write the needed equations to solve the problem.</span>
							  <p>
							  <span class="step-text">Step1: Analogy to DC circuit.</span><br/>
							  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image5.png" ></span> <br/>  
							  Here, <br/>
							  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image4.png" ></span> <br/> 
							  <span class="remember-text">You know how to solve this problem. Right? </span>
							  While you may solve this problem in different ways, one method is,<br/>
							  
							  <ul style="margin-left: 5%;">
								<li>&bull;&nbsp;&nbsp;Find resultant resistance </li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image36.png" ></span> </li>
								<li>&bull;&nbsp;&nbsp;Then Current I</li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image14.png" ></span> </li>
								<li>&bull;&nbsp;&nbsp;Then Voltage drop across each component.</li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image18.png" ></span> </li>
							  
							  </ul>
							  <span class="step-text">Step2: similarly write equation for your AC Circuit. i.e. replace the values</span><br/>
							  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image4.png" ></span> <br/> 
							  <ul style="margin-left: 5%;">
								<li>&bull;&nbsp;&nbsp;Find resultant impedance </li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image25.png" ></span> </li>
								<li>&bull;&nbsp;&nbsp;Then Current I</li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image44.png" ></span> </li>
								<li>&bull;&nbsp;&nbsp;Then Voltage drop across each component.</li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image7.png" ></span> </li>
							  
							  </ul>
							   <span class="step-text">Step3: Now ! all you need to do is substitute the known values and find unknowns.</span>
							    <ul style="margin-left: 5%;">
								<li>&bull;&nbsp;&nbsp;Calculate resultant impedance. </li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image1.png" ></span> </li>
								<li>To simplify  you would need complex number theory knowledge. If you are not doing well with complex numbers, <span class="positive-text">don’t worry !</span> A scientific calculator may help you.<span class="remember-text">CASIO – fx – 991 ES is preferred.</span> </li>
								<li>&bull;&nbsp;&nbsp;The calculator should tell you:</li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image26.png" ></span> </li>
								<li>&bull;&nbsp;&nbsp;Then using the calculator, you can calculate:</li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image13.png" ></span> </li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image41.png" ></span> </li>
								<li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image50.png" ></span> </li>
							  
							  </ul>

							  </p>
							  </div>
							</li>
							<li>
							  <div class="collapsible-header"><i class="material-icons">info_outline</i>Discussion</div>
							  <div class="collapsible-body"><span>Now we have calculated the unknown quantities of our circuit.  So, we should be able to prove these quantities are correct. Now we’ll apply the Kirchhoff’s voltage law for the circuit and check if it proves the same relationship.</span>
							  <p>
							  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image6.png" ></span><br/>
							  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image32.png" ></span><br/>
							  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image9.png" ></span><br/>
							  Therefore, it is certain that the answers we found are correct.
							  </p></div>
							</li>
						  </ul>
						  </div>
						</li>
						<li>
						  <div class="collapsible-header"><i class="material-icons">edit</i>Sample Problem 2.2.1.b</div>
						  <div class="collapsible-body"><span>Try to solve the following problem by using a calculator.</span>
						  <p>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image38.png" ></span><br/>
						  Here,<br/>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image42.png" ></span><br/>
						  Calculate current I and voltage drop across each component. Also calculate the current through the capacitor.
						  <!-- <ul class="collapsible">
						<li>
						  <div class="collapsible-header"><i class="material-icons">question_answer</i>Answer</div>
						  <div class="collapsible-body"><span>Lorem ipsum dolor sit amet.</span></div>
						</li>
						<li>
						  <div class="collapsible-header"><i class="material-icons">info_outline</i>Discussion</div>
						  <div class="collapsible-body"><span>Lorem ipsum dolor sit amet.</span></div>
						</li>
					  </ul> -->
					  <ul class="collapsible">
						<li>
						  <div class="collapsible-header"><i class="material-icons">question_answer</i>Answer</div>
						  <div class="collapsible-body"><span>Again depending on your knowledge about electricity network theory, this problem can be solved by having few different approaches.<br/>

						Here one such approach is explained.<br/>

						<span class="step-text">Calculate resultant impedance:<br/></span>
						</span>
						<p>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image17.png" ></span><br/>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image45.png" ></span><br/>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image2.png" ></span><br/>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image30.png" ></span><br/>
						<span class="step-text">Then the current I:<br/></span>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image47.png" ></span><br/>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image28.png" ></span><br/>
						<span class="step-text">Voltage through capacitor:<br/></span>
						The capacitor is directly connected to the conductors coming from voltage source.
						Therefore, the voltage would be the same.
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image46.png" ></span><br/>
						<span class="step-text">Current through capacitor:<br/></span>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image10.png" ></span><br/>
						<span class="step-text">Current through resistor inductor branch:<br/></span>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image37.png" ></span><br/>
						<span class="step-text">Voltage drop across resistor:<br/></span>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image29.png" ></span><br/>
						<span class="step-text">Voltage drop across inductor:<br/></span>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image31.png" ></span><br/>

						</p>
						</div>
						</li>
						<li>
						  <div class="collapsible-header"><i class="material-icons">info_outline</i>Discussion</div>
						  <div class="collapsible-body"><span>Here as well, the voltage summation through resistor and inductor should be equal to supply voltage.</span>
						  <p>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image33.png" ></span><br/>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image27.png" ></span><br/>
						  Therefore, it is certain that the answers are correct.
							Likewise, you can check any relationship between any components.

						  </p>
						  </div>
						</li>
					  </ul>
						  
						  
						  </p>
						  </div>
						</li>
					  </ul>
					<h5 style="color: #3498DB">2.2.2	&nbsp;Calculating the Impedance Values </h5>
					<p>
						In AC systems, the ratio between current and voltage across any passive component is known as impedance. In the above example impedance of each component was given to you. But in reality, you have to calculate these values in certain situations. The following is a guide to calculate impdances of different components.
					</p>
					<ul class="collapsible">
						<li>
						  <div class="collapsible-header"><i class="material-icons">info</i>Resistors (Purely Resistive Component)</div>
						  <div class="collapsible-body"><span>Impedance value of any resistor or purely resistive component would be a real number and is considered to be equal to its DC resistance.</span>
						  <p>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image23.png" ></span><br/>
						  But in reality AC resistance would be different from DC resistance due to a phenomenon called ‘Skin Effect’ and other material specific characteristics.<br/>
							e.g.:<br/>
							AC impedance of 47 kilo Ohm resistor is,<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image40.png" ></span><br/>

						  </p> 
						  </div>
						</li>
						<li>
						  <div class="collapsible-header"><i class="material-icons">info</i>Inductors (Purely Inductive Component)</div>
						  <div class="collapsible-body"><span>Impedance value of any inductor or purely inductive component would be a positive imaginary number called ‘inductive reactance’ and is given by following equation.</span>
						  <p>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image22.png" ></span><br/>
						  e.g.:
						AC impedance of 100 mH inductor is,<br/>
						<span class="remember-text">Remember!!! </span>Impedance of an inductor cannot be calculated unless you know the supply power frequency. (f has to be given.)<br/>
						In this case let’s assume the power frequency to be 50 Hz. Then,
																						<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image20.png" ></span><br/>

						  </p> 
						  </div>
						</li>
						<li>
						  <div class="collapsible-header"><i class="material-icons">info</i>Capacitors (Purely Capacitive Component)</div>
						  <div class="collapsible-body"><span>Impedance value of any capacitor or purely capacitive component would be a negative imaginary number called ‘capacitive reactance’ and is given by following equation.</span>
						  <p>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image19.png" ></span><br/>
						  e.g.:
AC impedance of 100 micro Farad capacitor is,
<br/>
						<span class="remember-text">Remember!!! </span>Impedance of a capacitance cannot be calculated unless you know the supply power frequency. (f has to be given.)<br/>
In this case let’s assume the power frequency to be 50 Hz. Then,

																						<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image39.png" ></span><br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image34.png" ></span><br/>

						  </p> 
						  </div>
						</li>
						<li>
						  <div class="collapsible-header"><i class="material-icons">info</i>Combinations of resistors, inductors and capacitors</div>
						  <div class="collapsible-body"><span>Above we discussed purely capacitive components. it was not associated with any resistor or inductor. But in real world such components do not exist. Mostly the devices are combinations of the three.</span>
						  <p>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image21.png" ></span><br/>
						  Depending on the values this would result in a complex value,<br/>
						   <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image35.png" ></span><br/>
						   X is the resistance<br/>
						Y is the reactance<br/>
						If X is 0 and Y is positive, then this component would be purely inductive.<br/>
						If both X and Y are positive, then this component would be both resistive and inductive. Likewise, all possible combinations are given below.<br/>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image24.png" ></span><br/>
						There are few things you should notice here,<br/>
						<ul style="margin-left: 5%;">
						<li>•	Usually resistance (X) won’t be negative for passive components</li>
						<li>•	If either X is zero, then the component would be purely inductive or capacitive</li>
						<li>•	If reactance (Y) is negative component would be capacitive else, it would be inductive.</li>						
						</ul>
						<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image3.png" ></span><br/>





						  
						  </p>
						  </div>
						</li>
					  </ul>
					  
					<h5 style="color: #3498DB">2.2.3	&nbsp;Analysing with Phasor Diagrams</h5>
					<p>
						In certain situations, phasor diagrams are the simplest way to analyze AC electric circuits. On the other hand, it is a great way to elaborate parameters related to a circuit. Therefore, phasor diagrams can be considered as another way to denote AC quantities after complex numbers and sinusoidal functions. 
					</p>
					
					  <ul class="collapsible">
						<li>
						  <div class="collapsible-header"><i class="material-icons">edit</i>Sample Problem 2.2.3.a ( a review of Sample Problem 2.2.1.a)</div>
						  <div class="collapsible-body"><span>Let’s try to re state above sample problem 2.1.1.a using phasor diagrams as below.</span>
						  <p>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image16.png" ></span> <br/>
						  Now the same given values in the problem can be restate using a phasor diagram as below.(The diagram is not to the scale.)<br/>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture1.PNG" ></span> <br/>
						  Drawing  a phasor diagram is very easy.All you need to do is following.<br/>
						  <ul style="margin-left: 5%;">
						  <li>•	Draw two perpendicular axes (Real and Imaginary)</li>
						  <li>•	Convert all your AC quantities into complex form.</li>
						  <li>•	If your quantities are in polar form, draw an arrow with an angle to the positive of real axis which is equal to ‘Argument’ of your complex number.Make the length of the arrows proportional to the ‘Magnitude’. 
							</li>
						  <li>•	If the quantities are in Cartesian form, simply mark the point on the complex plane and then draw an arrow running from root to your point.
							</li>
						  <li>•	These arrows we call the phasors representing your quantities.
							</li>
						  </ul>
						  You can go through the ‘Class Note 03’ for more information on phasor diagrams.<br/><br/>
						  
							<ul class="collapsible">
							<li>
							  <div class="collapsible-header"><i class="material-icons">question_answer</i>Answer</div>
							  <div class="collapsible-body"><span>Let's follow the same steps as we did in problem 2.1.1.a</span>
							  <p>
									  <span class="step-text">Resultant Impedance:</span><br/>
								  Now using the same phasor diagram let’s find out the resultant impedance. All we need to do is vector summation.<br/>
								   <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture2.PNG" ></span> <br/>
								   By using your mathematical knowledge, you can find the ‘magnitude’ and ‘argument’ of resultant impedance.<br/>
								   <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq1.png" ></span> <br/>
								   <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture3.PNG" ></span> <br/>
								  Now we need to divide voltage by the resultant impedance to find the current.<br/><br/>
								  <span class="step-text">Current:</span><br/>
								  If you can <span class="remember-text">remember</span> the complex number theory. You know how to divide and multiply any two complex numbers which are in polar form.<br/>
									<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq2.png" ></span> <br/>
									<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture4.PNG" ></span> <br/>
									The lengths are not to the scale.<br/><br/>
									<span class="step-text">Voltage drop across each component:</span><br/>
									Now using your knowledge explained about complex number multiplication,
									<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq3.png" ></span> <br/>
									Similarly,<br/>
									<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq4.png" ></span> <br/>
									<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture5.PNG" ></span> <br/>
							  </p>
							  </div>
							</li>
							<li>
							  <div class="collapsible-header"><i class="material-icons">info_outline</i>Discussion</div>
							  <div class="collapsible-body"><span>There are few important things we should notice here,</span>
							  <p>
							  <ul style="margin-left: 5%;">
							  <li>1.  If you notice it carefully, you can see the angle of resultant impedance and current is the same in size. But opposite in angle [(+63.435) and (-63.435)].This is because their addition should be equal to the angle of voltage which is zero.</li>
							  <li>2.  The voltage drops through Resistor and Inductor <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq5.png" ></span>are perpendicular to each other. (Look green and orange arrows.) This is because they are in series. For passive components which are in series, despite the magnitude of voltage drop their angles would be perpendicular depending on their resistance and reactance value.</li>
							  <li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture5b.PNG" ></span> <br/></li>
							  <li>3.  Summation of voltage drops through Resistor and Inductor <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq5.png" ></span> can be proved to be equal to supply voltage through vector summation.
							  </li>
							  <li><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture6.PNG" ></span> <br/></li>
							  </ul>
							  	
	

							  </p>
							  </div>
							</li>
						  </ul>
							
							




						  </p>
						  </div>
						</li>
						<li>
						  <div class="collapsible-header"><i class="material-icons">edit</i>Sample Problem 2.2.3.b ( a review of Sample Problem 2.2.1.b)</div>
						  <div class="collapsible-body"><span>Let’s try to re state above sample problem 2.1.1.b using phasor diagrams as below.</span>
						  <p>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/image38.png" ></span><br/>
						  Now the same given values in the problem can be restate using a phasor diagram as below.<br/>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture7.PNG" ></span> <br/>
						  The lengths of the diagram are not to the scale.<br/><br/>
						  
							  <ul class="collapsible">
						<li>
						  <div class="collapsible-header"><i class="material-icons">question_answer</i>Answer</div>
						  <div class="collapsible-body"><span>We'll have the following approach.</span>
						  <p>
						  <span class="step-text">Resultant Impedance:</span><br/>Through vector summation, can we find the resultant impedance?<br/>
						   <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture8.PNG" ></span> <br/>
						  does the green arrow in above figure give the resultant impedance?<br/><br/><br/>
						  The answer is <span class="remember-text">NO</span>. Green arrow is the resultant impedance of series connection of given components. In our case, it is really complicated as there is a parallel connection in this circuit. Therefore, being stick to complex numbers and calculator would be much easy. So we’ll borrow the calculated value from sample 2.1.1.b.<br/>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq6.png" ></span> <br/><br/>
						  <span class="step-text">Current I:</span><br/>
						  <span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture9.PNG" ></span> <br/>
						  In above figure green arrow represents the resultant impedance.<br/>
							Now from the experience of previous knowledge, can you draw the current phasor?	Since the relationship is, <br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq7.png" ></span> <br/><br/>
							The summation of angles in current and impedance should be zero. (according to the discussion of above problem)Therefore,<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq8.png" ></span> <br/><br/>
							Magnitude is simply the division of voltage magnitude divided by impedance magnitude.<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq9.png" ></span> <br/><br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture10.PNG" ></span> <br/><br/>
							<span class="step-text">Voltage drop through capacitor:</span><br/>It is equal to supply voltage and we can denote as below.<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture11.PNG" ></span> <br/><br/>
							<span class="step-text">Current through capacitor:</span><br/>
							Here the relationship is,<br/><span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq10.png" ></span> <br/>Magnitude is simply the division of voltage magnitude divided by impedance magnitude.<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq11.png" ></span> <br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture11b.png" ></span> <br/><br/>
							<span class="step-text">Current through resistor inductor branch:</span><br/>
							Here relationship is,<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq12.png" ></span> <br/>
							Therefore, we should be able to solve this using vector subtraction. <br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture12.PNG" ></span> <br/><br/>
							We can also calculate the magnitude and angle through vector summation rules,<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq13.png" ></span> <br/> <br/>
							<span class="step-text">Voltage through inductor and resistor:</span><br/>The relationship is,<br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq14.png" ></span> <br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/capture13.PNG" ></span> <br/>
							<span style="overflow: hidden; display: inline-block;"><img alt="image missing" src="images/eq15.png" ></span> <br/>
						  </p>
						  
						  </div>
						</li>
						<li>
						  <div class="collapsible-header"><i class="material-icons">info_outline</i>Discussion</div>
						  <div class="collapsible-body"><span>Lorem ipsum dolor sit amet.</span></div>
						</li>
					  </ul>
							

						  </p>
						  
						  </div>
						</li>
					  </ul>

					<!-- <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 282.00px; height: 219.00px;"><img alt="" src="images/image3.png" style="width: 282.00px; height: 219.00px; margin-left: 0.00px; margin-top: 0.00px; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px);" title=""></span>  -->
					

			  </div>

			</div>
			  
	
	
	
	
	
		</div>
      <!--JavaScript at end of body for optimized loading-->
      <!-- <script type="text/javascript" src="js/materialize.min.js"></script> -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
	  <script>
			 document.addEventListener('DOMContentLoaded', function() {
				var elems = document.querySelectorAll('.collapsible');
				var instances = M.Collapsible.init(elems);
			  });
	  </script>
	  


    </body>
  </html>
