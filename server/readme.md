# Server

A monolithic server offering a numvger of discrete services (in real wortls these might be micro services)

IdentityService (used for managing loigins)
PatientService (Used for obtaining patient information )
AppointmentService (This manages the priority queue and assigns patients to correct doctor logged in )
EmployeeService (managaes staff information)

Each Service has its own Port(s)