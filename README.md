# t
t

//This is a practice code in JavaScript using Constructors


function  EmployeesInfo(firstName, lastName, salary, id, jobPost) 
{
this.firstName = firstName;
this.lastName = lastName;
this.salary = salary;
this.id = id;
this.jobPost = jobPost;
let employee1, employee2 ,employee3,employee4, employee5, employee6;
}
employee1 = new EmployeesInfo(`John`, `Stuart`, 45000, 73763, `Electrical Engineer`);
employee2 = new EmployeesInfo(`Smith`, `Andrew`, 43200, 73764, `Mechanical Engineer`);
employee3 = new EmployeesInfo(`Anthony`, `Gregory`,45500, 74393, `HR Manager`);
employee4 = new EmployeesInfo(`Isablla`, `Luke`, 34000, 76987, `Assistent HR`);
employee5 = new EmployeesInfo(`Mariah`, `McDonald`, 30000, 78654, `Sessioned Intern`);
employee6 = new EmployeesInfo(`Reynolds`, `Justin`, 23000, 76543, `Third Party`);

console.log(`________________________________________________________`);
console.log(`First Name  Last Name  Salary    ID       Job Post`);

console.log(`________________________________________________________`);
console.log(employee1.firstName+`          `+ employee1.lastName+`   `+ employee1.salary+`  `+employee1.id+`  `+employee1.jobPost);

console.log(`________________________________________________________`);
console.log(employee2.firstName+`         `+ employee2.lastName+`  `+ employee2.salary+`  `+employee2.id+`  `+employee2.jobPost);

console.log(`________________________________________________________`);
console.log(employee3.firstName+`       `+ employee3.lastName+`   `+ employee3.salary+`  `+employee3.id+`  `+employee3.jobPost);

console.log(`________________________________________________________`);
console.log(employee4.firstName+`         `+ employee4.lastName+`  `+ employee4.salary+`  `+employee4.id+`  `+employee4.jobPost);

console.log(`________________________________________________________`);
console.log(employee5.firstName+`         `+ employee5.lastName+`  `+ employee5.salary+`  `+employee5.id+`  `+employee5.jobPost);

console.log(`________________________________________________________`);
console.log(employee6.firstName+`         `+ employee6.lastName+`  `+ employee6.salary+`  `+employee6.id+`  `+employee6.jobPost);
console.log(`________________________________________________________`);

   
