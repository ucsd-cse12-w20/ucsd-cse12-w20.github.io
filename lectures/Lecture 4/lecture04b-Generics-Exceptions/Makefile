%.class: %.java List.java AList.java
	javac -cp hamcrest-core-1.3.jar:junit-4.12.jar:. $<

%: %.class
	java -cp hamcrest-core-1.3.jar:junit-4.12.jar:. org.junit.runner.JUnitCore $@
