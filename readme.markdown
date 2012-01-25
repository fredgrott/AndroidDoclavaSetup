AndroidDoclavaSetup
===================

The idea in agile is be fast at prototyping as well as long term projects. But Google keeps goofing up
the ant build scripts with every sdk version release. Thus, reroute around the problem and have IDE execute stuff
instead of ant.

This is the basic setup for doclava for an android project. If you  have project libraries than 
you will have to edit the javadoc.xml file ot include them in the ant javadoc declaration.

This is what it looks like before you customize the assets templates part of doclava:

![FirstPass](https://github.com/shareme/AndroidDoclavaSetup/raw/master/readme.assets/firstpass.png)



To Use
======

Edit the javadoc.xml file to set it ot your paths isntead of mine.
Than in your IDE do right click file and run as.

To customize look and feel you will be cusomtizing the files in the 
doclet.assets/assets sunfolder, see doclava docs for the howtos.



Resources
=========

[Apache ANT Javadoc Task](http://ant.apache.org/manual/Tasks/javadoc.html)

[Javadoc Reference-Oracle](http://www.oracle.com/technetwork/java/javase/documentation/index-jsp-135444.html)

[Doclava Site and docs](http://code.google.com/p/doclava/)

[My Blog](http://fredgrott.wordpress.com)


License
========

Apache 2.0 License