
@snap[text-center]

# S.O.L.I.D.
---

Single Responsibility Principle
---

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