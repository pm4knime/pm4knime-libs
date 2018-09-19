# pm4knime-libs
wrapper project for ProM based libraries (jars specifically)

# here are some instructions from kefang during her installation way
TO make it work, you should make sure these conditions satisfied:
<1> install jdk,
try javac in a terminal, if javac doesn't exist, 
 --if not with jdk, then install it by ubuntu suggestion
 --with jre, then its effect is, java works in terminal but javac not, refering this link to fix problem
  https://stackoverflow.com/questions/16267894/javac-does-not-work-in-ubuntu-terminal/16267941 
   Step 1: check which jre in the terminal 
   refering this link https://stackoverflow.com/questions/16931327/where-is-the-java-sdk-folder-in-my-computer-ubuntu-12-04
   or 
  update-alternatives --list java 
  to find the location of jdk folder
  
  Step 2:
  apt-get install java-XXXX [which is the same version like jre]
  
  Step 3:
  if javac doesn't appear, then follow this link 
  https://askubuntu.com/questions/117189/apt-get-install-openjdk-7-jdk-doesnt-install-javac-why 
  TO add javac to the search path
  
  <2> Install ivy
  Always make sure that ivy is installed, so the dependency can be resolved automatically by ivy. 
  Always check the installed state from changing eclipse
  
  <3> Go to build.xml and right click to choose Ant building
  
  <4> Refresh to get the generated jar file, then we can add it to another project
   


