<h1 align="center"> DBMS-Hospital-Management-System </h1>

<h4 align="center"> This is a typical representation of a hospital where there are a number of job
profiles like doctors, nurses, ward boys, dispensaries and many more. It is a
lucid structure to give a pragmatic view of all the individual entities, and how
well they are related with each other and on what parameters. What we plan
to implement is specializing a hospital class into subclasses, so that it gets easy
to manage all the individuals who are a part of this eco system.
The entire structure which manifests a hospital will be having several
departments like orthopaedic, neurology, cardiology and many more. Each department in
turn will have several doctors with different points of specializations. Under every doctor there will be some nurses to manage patients. There needs
to be separate categorization of patients and which particular doctor they
want to consult, and on which date. <h4>

  
#Working Hierarchy
* Hospital has several departments, all the departments in a particular
hospital will be in the department entity.
* Hospital has further relations with dispensary table which will keep
record of all the medicines allocated for a particular department along
with the disease name. Department table also shares a one to many
relationship with doctor table.
* Doctor entity consists of entities describing details about the doctors
and the department which they belong to.
* Then there are patient and patient history entities to store details about
the patients and their medical
