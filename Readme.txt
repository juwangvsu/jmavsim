build env:
ub18, openjdk-8-jdk

	cd ~/Downloads/px4-1.5.5/Firmware/Tools/jMAVSim; ant create_run_jar copy_res
		if need to build jmavsim_run.jar
	sudo vim /etc/java-8-openjdk/accessibility.properties comment off that line
		if jmavsim error on "Assistive technology not found AWTError"

to build jMAVsim,

run "ant", not make

to build _jun.jar
ant create_run_jar copy_res
