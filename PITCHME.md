
@snap[west span-40 text-center]

# S.O.L.I.D.
---
@snap [west span-60 text-center]

Single REsposibility Principle
---
@snap[west span - 20 text-origin]
Bad Example

	class WorkingStaffSchedule{
		private Long id;

		private String name, lastname, title;

		private dateOfWork;

		private startsWork;

		prviate finishesWork;

	
	//Getters & setters
		....


		Employee employee = new Employee;
		.....


		employeeRepository.save(employee);
		void workSchedule(){};
		void workingHours(){};
		void salary(){};
		
}