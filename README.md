# DAG_from_Marc_Lamberty_Udemy

The described DAG has 5 tasks:  
Create table -> is_API_available -> extract_user -> process_user -> store_user

Notes:  

Providers help to interact with external dependencies like AWS, pgSQL etc.  

There are 3 types of operators:  
1/ execution (python or bash  
2/ transformation  
3/ sensor (keeps checking)  

Hooks are used to abstract complexity (of external tools) and get additional methods unavailable from operators  
