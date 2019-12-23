# ABAP_EMPLOYEE_CREATE
SAP/ABAP - Create Employee infotypes 


If you want afterward to insert more infotype with FM: HR_INFOTYPE_OPERATION after create the employee
i used to add this enhancement :

* Don't initial the Buffer
  cl_hrpa_masterdata_factory=>set_initial( abap_false ).   "Class enhanced with method set_initial to attribute a_is_initialized
