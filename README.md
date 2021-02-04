# My_First_iOS_App

<h1><i> To build My First iOS app </i></h1>

<h3> Contents : </h3>
<h4> 1. Identifying mac version </h4>
<h4> 2. Installation of XCode </h4>
<h4> 3. Creating App </h4>
<h4> 4. Useful Definition </h4>

<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------- -->

<h1><b> 1. Identifying mac Version </b></h1>

  <h3> 1.1 From anywhere on the Mac, look in the upper left corner for the Apple menu and click that </h3>
  	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/1.jpg" width="700" height="400">

  <h3> 1.2 From the Apple menu choose “About This Mac” </h3>
  	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/2.jpg" width="700" height="400">

  <h3> 1.3 The Mac system overview panel will appear on screen, showing what Mac OS release and version is installed on the computer </h3>
  	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.jpg" width="700" height="400">

<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------- -->

<h1><b> 2. Installation of XCode </b></h1>

  <h3> 2.1 Download via the App Store for the latest version </h3>
  	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/2.1.jpg" width="700" height="400">

  <h3> 2.2 Steps :  </h3>
  <h3> 2.2.1 Click on More in the top-right of the page, next to Beta and Release </h3>
  <h3> 2.2.2 In the search field on the left, type “xcode” and press Enter </h3>
  <h3> 2.2.3 Locate and click the appropriate version of Xcode in the list </h3>
  <h3> 2.2.4 In the panel slides out, click the .xip filename, i.e. Xcode 12.xip and save/download that file onto your Mac </h3>
  
  <h4> This will download a .xip file, which includes Xcode. The download size is currently about 7 gigabyte (GB). You’ll need at least twice that size of free storage on your Mac to install Xcode with this approach. Downloading Xcode this way is often faster than through the Mac App Store. </h4>
  	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/2.2.jpg" width="700" height="400">

  <h3> 2.3 Once you’ve downloaded Xcode, open and unzip the .xip file. This may take a while. You can then drag-and-drop the Xcode.app file to your ~/Applications folder. Finally, start the Xcode app. You’ll be greeted with the following prompt: </h3>
  	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/2.3.jpg" width="700" height="400">

  <h3> Click Install in this prompt. Xcode will now attempt to install the Xcode Command Line Tools on your Mac. They are CLI tools used to compile apps with Xcode, among other things. You often need these tools to work with other programming languages on Mac, as well. </h3>
  
  <h2> Having successfully installed the Xcode, the next step is to launch it. </h2>
  
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------- -->

<h1><b> 3. Creating App </b></h1>

  <h3> 3.1 Start 'Xcode' or menu: File | New | Project  </h3>
  	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.1.PNG" width="700" height="400">

  <h3> 3.2 Creates a basic template for an application containing a single view and corresponding view controller. </h3>
  	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.2.jpg" width="700" height="400">

  <h3> 3.3 We are going to use the Single View Application template so select this option from the new project window and click Next to configure some more project options </h3>
    	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.3.jpg" width="700" height="400">

  <h3> 3.4 Now let’s make it interactive so our app does something
Drag and drop the Label on to the screen.Once it is in position release the mouse button to drop it at that location.
 </h3>
    	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.6.jpg" width="700" height="400">

  <h3> 3.5 Click on the button and then hold down the control key.
Then click and drag from the button over to screen. </h3>
    	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.7.jpg" width="700" height="400">

  <h3> 3.6 Let's look at a ViewController.swift file </h3>
    	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.8.jpg" width="700" height="400">
	<br>
    	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.9.jpg" width="700" height="400">
  
  <h3> 3.7 Before an app can be run it must first be compiled. Once successfully compiled it may be run either within a simulator or on a physical iPhone. </h3>
  	<h2> Click on the Run toolbar button to compile the code and run the app in the simulator. The small panel in the center of the Xcode toolbar will report the progress of the build process together with any problems or errors that cause the build process to fail. Once the app is built, the simulator will start. </h2>
    	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.13.jpg" width="700" height="400">

  <h3> 3.8  Initially “Label” is displayed. </h3>
    	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.11.jpg" width="700" height="400">

  <h3> 3.9 Once is click on the button “Button”, it will change to “Hello World” as shown below. </h3>
    	<img src="https://github.com/kinjal-147/My_First_iOS_App/blob/main/Screenshots/3.12.jpg" width="700" height="400">

  <h3>  </h3>
  <h3>  </h3>
  <h3>  </h3>
  <h3>  </h3>
  <h3>  </h3>

<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------- -->

<h1><b> 4. Useful Definition </b></h1>

<h2> 4.1 IB Outlet :</h2>
  	<h4> 
      		When you connect your storyboard to your code Xcode inserts two special markers: @IBAction and @IBOutlet. Both of these effectively do nothing when you build your app, but they are still important because Xcode uses them to understand which of your properties and methods are relevant to Interface Builder.
	</h4>
	<h4>
	In the case of @IBOutlet , this is a connection from an Interface Builder user interface component – e.g. a UIButton – to a property in a view controller or other piece of Swift code. To the left of the code you should see a black circle with a ring around it, which is Xcode’s visual confirmation that a given @IBOutlet has an active connection.   
	</h4>

  <h2> 4.2 IB Outlet :</h2>
  <h4> 
      When you connect your storyboard to your code Xcode inserts two special markers: @IBAction and @IBOutlet. Both of these effectively do nothing when you build your app, but they are still important because Xcode uses them to understand which of your properties and methods are relevant to Interface Builder.
  </h4>
  <h4>
@IBAction is a way of making storyboard layouts trigger code.  
</h4>

<h2> 4.3 UILabel </h2>
	<h4> A view that displays one or more lines of informational text. </h4>
	<h4> class UILabel : UIView </h4>
	
	
