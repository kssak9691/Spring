package com.cg.project.client;
import com.cg.project.services.GreetingServices;
import com.cg.project.services.GreetingServicesImpl;
public class MainClass {
	public static void main(String[] args) {
		GreetingServices greetingServices=new GreetingServicesImpl();
		greetingServices.sayHello("Abhi Kaush");

	}

}
