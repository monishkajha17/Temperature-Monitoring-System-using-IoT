# Temperature-Monitoring-System-using-IoT
<h2>AGENDA<h2>
  <p>Temperature plays a crucial role in our day-to-day life for maintaining our health as well as in various dominant industries. Fluctuation or change in temperature can cause various physical and chemical effects on substances.That's why we need to maintain temperature for many vital processes to ensure consistency and safety.In many industries it is very important to maintain temperature in the threshold range and to inform the owner if the temperature is about to go beyond the set threshold value,by avoiding damaging to lots of product before the temperature reaches beyond set threshold value set. The Temperature monitoring system can be used in Pharmaeutical industry, in Laboratories, Food Safety Compliances and remote Warehouses.

</p>
<h2>Introduction</h2>
  <img align = "right" src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVdVSFLhVXxNibetevRfxOsEKuu1Fzt_oFhy1QuB6llxUUrwv-7RCbXcadt34YwZy04W8&usqp=CAU" alt ="IOT" height = "300" width = "400">
<p>The Internet of Things (IoT) describes the network of physical objects—“things”—that are embedded with sensors, software, and other technologies for the purpose of connecting and exchanging data with other devices and systems over the internet. The Internet of Things technology has been growing rapidly and has already bypassed conventional systems in terms of features and functionalities.By means of low-cost computing, the cloud, big data, analytics, and mobile technologies, physical things can share and collect data with minimal human intervention. In this hyperconnected world, digital systems can record, monitor, and adjust each interaction between connected things. The physical world meets the digital world—and they cooperate.</p>
  
  <div>
  <p>
 IoT applications use machine learning algorithms to analyze massive amounts of connected sensor data in the cloud. Using real-time IoT dashboards and alerts, you gain visibility into key performance indicators, statistics for mean time between failures, and other information. Machine learning–based algorithms can identify equipment anomalies and send alerts to users and even trigger automated fixes or proactive counter measures.
 </p>
 </div>
 <div>
 <p>
Its applications in the field of remote monitoring and advanced analytics are revolutionizing businesses and are offering exemplary benefits to them.One such application of IoT is <b>temperature monitoring</b>. A <b>temperature monitoring</b> solution is immensely beneficial to industries where temperature plays a crucial role in defining the quality of the products. Moreover, in a cold chain, a temperature monitoring solution allow a logistic manager to monitor the temperature of the item  real-time.The implementation of this solution is really helpful for goods that are temperature-sensitive. It is convenient to use and help in confirming the quality of the products during warehousing, manufacturing, storing and shipping processes.
  </p>
 </div>

  <p>The places where Temperature Monitoring System can be used:
  <ol>
   <li><b>Digital temperature monitoring in laboratories:</b>Temperature plays a crucial role in defining the chemical composition or integrity of volatile compounds and biological samples respectively. They can render useless and affect experimental conclusions or even worse, the user's health, if not kept under a strict temperature range. It is, therefore, vital for laboratories and test clinics to maintain a controlled environment for successful testing on these samples.      </li>
   <li><b>Food Safety Compliances:</b>The food industry  uses heater/freezer fitted chambers to develop a controllable environment for their goods. IoT temperature monitoring solution allows the food industry to monitor the temperature of these chambers allowing them to ensure that the regulatory compliances are met. They can remotely monitor the temperature of the items and confirm the quality of their products.</li>
   <li><b>Warehouse and Inventory Management:</b>Some products can be sensitive to humidity & temperature. Storing them in a normal warehouse can result in their corrosion and are thus required to be stored in a temperature-controlled environment. By using heaters/freezers, the temperature and humidity of the warehouses can be maintained to ensure the quality of a specific type of product. By using IoT based temperature monitoring solution, a warehousing and inventory manager can track and remotely change the temperature of the warehouse. This reduces inspection costs and helps companies to ensure the quality of their products.</li>
    <li><b>Temperature Monitoring in Medicine Mnaufacturing:</b>In pharmaceutical industry; because certain medicines need a definite temperature to be manufactured if the temperature fluctuates the medicine can be poisonous. So it will sense the fluctuation of temperature and will report it to the user by message.</li>
 
  
  <div>
  <h3>Building of Project</h3>
    <p>In this Project I will be building a Temperature monitoring system to collect the data and send it over to the cloud, where I'll be creating graphs to visualize the data. This project will be extended to Predict the future sensor values via machine learning over the  Cloud.It's working will be like the sensor(LM35)will sense the temperature of the sorrounding and will ensure the temperature is in set threshold range if the temperature fluctuates or changes to go beyond the threshold range it will give security notifications via SMS, Whatsapp message.</p>
    
  </div>
  <div>
    <h3>Hardware Components</h3>
    <p>The hardware components that we will be required to set up the circuit:
    <ol>
      <li><b>Arduino Uno</b></li>
      <img align ="center" src= "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTELOL3O3nBIIOK5wrPXE-B8br_Tfwd5c9-gQ&usqp=CAU" height ="400" width = "600">
      <li><b>LM35 IC (Temperature sensor)</b></li>
      <img align = "center" src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRIe7MenSVxwMzhWFQQQrqyw2DPxo9dAJT5wQ&usqp=CAU" height = "400" width="600">
      <li><b>ESP01 (esp8266 family)</b></li>
      <img align ="center" src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRifwL0wro68Rmx45OHOS-ycavab384Z2Dquw&usqp=CAU" height = "400" width="600">
      <li><b>2*16 LCD Display</b></li>
      <img align ="center" src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLrmLr2ttFymzoW6n07udkSsTW8f4gmR9kPQ&usqp=CAU" height = "400" width="600">
      <li><b>Battery and Arduino Connector</b></li> 
      <img align = "center" src = "https://rukminim1.flixcart.com/image/416/416/jykfxjk0/electronic-hobby-kit/f/j/d/hw-battery-9v-with-connector-for-arduino-robotics-sunrobotics-original-imafgqz5dyaby58z.jpeg?q=70" height = "300" width="400">
      <li><b>Connecting wires </b></li>
      <img align = "center" src = "https://static-01.daraz.pk/p/2d353f94bbfe5ad50852c553b93ed96a.jpg" height = "400" width="600">
    
  </ol>
  </p>
  </div>
  
  <div>
    <h3>Assembling of circuit</h3>
  </div>
  



