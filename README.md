<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE suite SYSTEM "http://testng.org/testng-1.0.dtd">
<suite name="DemoBalze Automation Test Suite">

	<listeners>
		<listener class-name="com.demoblaze.util.Reporting" />
	</listeners>
	

	<test name="DemoBlaze Automation">
		<classes>
			<class name="com.demoblaze.testcases.SignUpPageTest"></class>
			<class name="com.demoblaze.testcases.LoginPageTest"></class>
			<class name="com.demoblaze.testcases.ProductInfoPageTest"></class>
			<class name="com.demoblaze.testcases.CartPageTest"></class>
			<class name="com.demoblaze.testcases.PaymentInfoPageTest"></class>
			 

		</classes>
	</test>
</suite>
