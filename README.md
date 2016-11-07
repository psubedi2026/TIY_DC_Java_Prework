# TIY_DC_Java_Prework

Working with Git will be a huge part of this class. Familiarity with it is going to be a requirement almost anywhere you end up working. Its purpose is to store "snapshots" (called commits) of your code, so you can see your progress and revert your changes if necessary. It also makes it easy to push your changes to a server, which acts as a backup of your code and a way to collaborate with other programmers.


###Computer Setup

<h3 id="hardware">Hardware</h3>

<p>All students must bring their own MacBook laptop. Your MacBook should have a minimum of 4 GB of RAM and 128 GB of hard drive space. Those are minimum specs, but I <strong>strongly</strong> recommend getting 8 GB of RAM.</p>

<p>Here are the current <a href="http://www.apple.com/macbook-air/specs.html">MacBook Air models</a> and <a href="http://www.apple.com/macbook-pro/specs-retina/">MacBook Pro models</a>. Your MacBook MUST be running macOS <strong>Sierra</strong> which is a free upgrade from the mac AppStore.</p>

<p>Do not go with the new, skinny 12” Retina MacBooks. Their processor will be too sluggish in a year or two.</p>

<h3 id="operating-system">Operating System</h3>

<p>You’ll need to install macOS Sierra if your Mac didn’t have it pre-installed or you haven’t upgraded already.</p>

<ol>
  <li>Download the macOS Sierra upgrade from the Apple Store: <a href="https://itunes.apple.com/us/app/macos-sierra/id1127487414?mt=12">download here</a>.</li>
  <li>You’ll need to sign in to your Mac’s ‘App Store’ with your <a href="https://appleid.apple.com/">Apple ID</a>.</li>
  <li>Double-click “Install macOS Sierra” to begin installation.<br>
<em>WARNING</em>: The macOS upgrade can take a bit of time to complete and will require a restart. Plan on doing this in the evening or over a lunch break.</li>
</ol>

<blockquote>
  <p><strong>Note: macOS Sierra is still relatively new. If you are on El Capitan, the last major version, then you should be fine.</strong></p>
</blockquote>

<h3 id="additional-software">Additional Software</h3>

<p><em>There is no commercial software required for the class.</em> However, there are many open source software requirements.</p>

<p>As soon as possible after receiving your Mac, run through the following steps. If you’ve done a lot of your own configuration, some of these steps may have to change. If you run into <strong>any problems</strong>, send me an e-mail at: <a href="mailto:jordan.kasper@theironyard.com">jordan.kasper@theironyard.com</a> and I will try to help.</p>

<h4 id="install-a-code-editor-atom">Install a code editor (Atom)</h4>

<p>You will need a program specifically designed for software development. We typically call this an IDE (an Integrated Development Environment). We recommend using the Atom editor which is made by GitHub.</p>

<p>Atom is not necessarily the best editor, but it has great defaults. If you are already using an editor and are comfortable with it then you may continue to use it. However, there may be times in class when I suggest a shortcut or editor configuration option that may be different for you! Good alternatives include: Sublime Text, Textmate, and MacVim.</p>

<p>To install Atom:</p>

<ol>
  <li>Download Atom from <a href="https://atom.io/">the Atom website</a>.</li>
  <li>Install it. If you’re not familiar with Mac installations, <a href="http://www.howtogeek.com/177619/how-to-install-applications-on-a-mac-everything-you-need-to-know/">read more here</a>.</li>
  <li>Start Atom from your Applications folder.</li>
  <li>Click on the “Atom” option in your menu bar (all the way in the upper-left of your screen) and choose “Install Shell Commands.”</li>
</ol>

<h4 id="install-google-chrome">Install Google Chrome</h4>

<p>While the end users of our applications will use a variety of browsers, I have found that Google Chrome is currently the best option for developing (and testing) our front end applications.</p>

<ol>
  <li>Download Chrome from <a href="https://www.google.com/intl/en/chrome/browser/">the Chrome download page</a>.</li>
  <li>Install and run it.</li>
  <li>Optionally, you may want to set Chrome as your <a href="https://support.google.com/chrome/answer/95417?hl=en">default browser</a>.</li>
</ol>

<h4 id="install-iterm2">Install iTerm2</h4>

<p>The terminal is our text-based interface into the computer. It is much more powerful than graphical user interfaces (GUI’s) generally and will be more efficient for us in the long run. MacOS comes with a terminal built in, but many people prefer a program called iTerm2.</p>

<ol>
  <li>Download iTerm2 from <a href="https://www.iterm2.com/downloads.html">the iTerm2 website</a></li>
  <li>Unzip the downloaded file by double-clicking on it.</li>
  <li>Open your Applications directory by clicking on the Finder and selecting it from the left sidebar.</li>
  <li>Drag the unzipped iTerm application into the Applications folder.</li>
</ol>

<h4 id="install-homebrew">Install Homebrew</h4>

<p>Homebrew will make it easier for us to install other applications we will need during class.</p>

<ol>
  <li>Open up the iTerm2 application you installed previously.</li>
  <li>Go to this site: http://brew.sh/ and copy &amp; paste the install command into your terminal (it should be the first thing on that page(</li>
</ol>

<h4 id="install-git">Install git</h4>

<li>Open up the iTerm2 application</li>
  <li>Run:<br>
  <code class="highlighter-rouge">brew install git</code></li>
  <li>Run:<br>
  <code class="highlighter-rouge">git --version</code> to see that you have it installed (you should see a version number print out)</li>
  <li>Run:<br>
  <code class="highlighter-rouge">git config --global push.default simple</code></li>
  <li>Run:<br>
  <code class="highlighter-rouge">git config --global credential.helper osxkeychain</code></li>
</ol>


### Tasks:

* [Create a Github account](https://github.com/signup)
* Read the class policies in the campus path
* [Edit your Github profile](https://github.com/settings/profile) to provide:
  * A picture, so I can recognize your face.
  * Your full name, so I can recognize your name.
  * A valid public email address, so I can contact you if I need to.
* [Complete the Code School course _Try Git_](https://www.codeschool.com/courses/try-git)
  * Take a [screenshot](https://support.apple.com/en-us/HT201361) of the Try Git course when you complete it and add it to the hello world repo you will create in the next step.
* [Complete the "Hello World" Github guide](https://guides.github.com/activities/hello-world/)
  * Submit a link to the repo you just made below in the submission form for this assignment.
  * FYI You will use this repo in future pre-work assignments.

### Java Basics: 

  * Java will be the main language we work with during the class. 
  * Please work through parts one and two of [KTByte Interactive Textbook in Java](https://www.ktbyte.com/java-tutorial/book). Take screenshot of your success. 
  * Then work through the [Codecademy course on Java](https://www.codecademy.com/en/courses/learn-java).  Take screenshot of your success
  * Add screenshots to your Hello World GIT repository and submit. 

### HTML & CSS Basics: 

  * While not a focus of the course, we will need to do some front-end development when we get into web applications. 
  * Work through the [Codecademy course on HTML & CSS](https://www.codecademy.com/en/tracks/web) so you have a basic familiarity with them.    Take screen shot of your success.
  * Add screenshots to your Hello World GIT repository and submit. 
