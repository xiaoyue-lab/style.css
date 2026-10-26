html {
  overflow-y: scroll;
  line-height: 1.6px;
  }

body {
  margin: 0;
  padding: 0;
  background-image: url(https://i.ibb.co/4wLzmLpd/568ae2b0de243f0545d9d2bf52d70ba4.jpg); 
  background-repeat: repeat;
  background: cover;
  background-position: center;
  width: 100%;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  color: #2c3e50;          
  line-height: 1.6;      
  position: relative;
  overflow-x: hidden;
  min-height: 100vh;
  }
body::before {
  content: "";
  position: fixed;
  top: 0; 
  left: 0; 
  right: 0; 
  bottom: 0;
  background-image: url(https://i.ibb.co/vC9VCZrq/peach-blossom-forest-park-spring-rainy-season-please-understand-video-animation-generated-ai-3977650.webp); /* Abstract flora node */
  background-size: cover;
  background-position: center;
  filter: blur(8px);        
  transform: scale(1.05);    
  z-index: -1;               
  opacity: 0.65;            
  }
/* PAGE WRAPPER*/
.page-wrapper {
  max-width: 1200px;        
  width: 100%;
  margin-left: auto;        
  margin-right: auto;        
  padding: 40px 20px;       
  box-sizing: border-box;
  }
header h1 {
  color: gold;
  font-style: italic;           
  margin-top: 0;
  font-weight: 700;

  text-shadow: 2px 2px 5px rgba(26, 37, 54, 0.15); 
  }

header h2 {
  color: lightskyblue;
  font-style: italic;           
  margin-top: 0;
  font-weight: 700;

  text-shadow: 2px 2px 5px rgba(26, 37, 54, 0.15); 
  }
p {
  margin-bottom: 1.5rem;
  font-weight: 500;       
  }
a {
  color: #8c3a5c;            
  text-decoration: none;
  font-weight: 600;
  border-bottom: 2px solid rgba(140, 58, 92, 0.2);
  transition: all 0.2s ease-in-out;
  }
a:hover {
  color: #1a2536;
  border-bottom-color: #276dd6;
  }
.intro header {
  text-align: center;
  margin-bottom: 40px;
  padding: 30px;
  background: rgba(255, 255, 255, 0.4); 
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.4);
  border-radius: 16px;
  }

.intro h1 {
  font-size: 3rem;
  margin-bottom: 10px;
  }
.intro h2 {
  font-size: 1.5rem;
  font-weight: 400;
  color: darkcyan;
  }

.summary {
  background-color: rgba(255, 255, 255, 0.7);
  padding: 30px;
  border-radius: 12px;
  margin-bottom: 30px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.02);
  font-style: italic;
  }
.preamble h3 {
    animation: blink 1s infinite;
	}
.preamble h3 {
    animation: fade-blink 1s infinite;
	}
@keyframes fade-blink {
	0%, 100% {opacity: 1;}
	50% {opacity: 0;}
    }
.preamble h3 {
    animation: fade-blink 1s  linear infinite;
	transition: color 0.2 ease;
	}	
.preamble h3:hover {
	cursor: pointer;
	color:#FFD700;
	}
.preamble {
  background-color: rgba(255, 255, 255, 0.7);
  padding: 30px;
  border-radius: 12px;
  margin-bottom: 30px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.02);      
  }
#zen-supporting {
  display: grid;
  grid-template-columns: repeat(2, 1fr); 
  gap: 30px;                            
  align-items: stretch;              
 }
.explanation h3, 
.participation h3, 
.benefits h3, 
.requirements h3 {
	color: brown;
	font-style: italic;
  }
/* Individual Content Grid  */
.explanation, 
.participation, 
.benefits, 
.requirements {
   background-color: rgba(255, 255, 255, 0.85); 
   padding: 35px;
   border-radius: 14px;
   box-sizing: border-box;
   box-shadow: 0 10px 25px rgba(44, 62, 80, 0.05); 
   border: 1px solid rgba(255, 255, 255, 0.6);
   transition: transform 0.3s ease;
   background-image: url(https://i.ibb.co/mr33jfHL/OIP-1.webp); 
   background-repeat: no-repeat;
   background-size: cover;
   }
.explanation, 
.participation, 
.benefits, 
.requirements {
   color: white;
   }


.explanation:hover, 
.participation:hover, 
.benefits:hover, 
.requirements:hover {
  transform: translateY(-4px);
	}
.explanation h3, 
.participation h3,
.benefits h3,
.requirements h3 {
  animation: blink 1s infinite;
	}
.explanation h3, 
.participation h3,
.benefits h3,
.requirements h3 {
  animation: fade-blink 1s infinite;
	}
@keyframes fade-blink {
	0%, 100% {opacity: 1;}
	50% {opacity: 0;}
	}
.explanation h3, 
.participation h3,
.benefits h3,
.requirements h3 {
  animation: fade-blink 1s linear infinite;
   transition: color 0.2 ease;
	}
.explanation h3:hover {
	cursor: pointer;
	color:gold;
	}
.participation h3:hover {
	cursor: pointer;
	color: purple;
	}
.benefits h3:hover {
	cursor: pointer;
	color: darkgreen;
	}
.requirements h3:hover {
	cursor: pointer;
	color: darkorange;
	}
footer {
	text-align: center;
	padding: 50px;	
	}
footer a {
	color: beige;
	border-bottom-color: #bd0e57;
	padding: 30px;
	}
.sidebar {
	background-color: rgba(255, 255, 255, 0.85); 
    padding: 35px;
 	border-radius: 14px;
    box-sizing: border-box;
    box-shadow: 0 10px 25px rgba(44, 62, 80, 0.05); 
    border: 1px solid rgba(255, 255, 255, 0.6);
    transition: transform 0.3s ease;
    background-image: url(https://i.ibb.co/mr33jfHL/OIP-1.webp); 
    background-repeat: no-repeat;
    background-size: cover;
	width: 300px;
	position: absolute;
	color: #E0E5EC;
	}
.select {
	color: #E0E5EC;
	font-style: italic;
	}
.design-name {
	color: #E6C687;
	}
.design-archives h3 {
	color: #F5F5DC;
  font-style: italic;
	}
.next,
.viewall {
	color: red;
	}
.next a,
.viewall a {
	color: #00FFFF;
  	font-style: italic;
	}
.zen-resources h3{	
	color: #FFD700;
  font-style: italic;
	}
.zen-resources li a{
	color: #A7F3D0;
	}






