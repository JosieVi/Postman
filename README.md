# Postman
## Homework-1
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/20886873-f1c19402-edc5-42ba-8595-0ec0424e5b67?action=collection%2Ffork&collection-url=entityId%3D20886873-f1c19402-edc5-42ba-8595-0ec0424e5b67%26entityType%3Dcollection%26workspaceId%3D315e35ce-b3bf-4782-a712-4581ae1690dc#?env%5BPostman-HW-1%5D=W3sia2V5IjoibmFtZSIsInZhbHVlIjoiT2xnYSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkiLCJzZXNzaW9uVmFsdWUiOiJPbGdhIiwic2Vzc2lvbkluZGV4IjowfSx7ImtleSI6ImFnZSIsInZhbHVlIjoiMzYiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiYW55Iiwic2Vzc2lvblZhbHVlIjoiMzYiLCJzZXNzaW9uSW5kZXgiOjF9LHsia2V5Ijoic2FsYXJ5IiwidmFsdWUiOiIzMDAwIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImFueSIsInNlc3Npb25WYWx1ZSI6IjMwMDAiLCJzZXNzaW9uSW5kZXgiOjJ9LHsia2V5Ijoid2VpZ2h0IiwidmFsdWUiOiI2NSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiNjUiLCJzZXNzaW9uSW5kZXgiOjN9XQ==)

### Task 1. Create requests in Postman.
* Protocol: http
* IP: 162.55.220.72
* Port: 5005

### EP_1
Method: GET\
EndPoint: /get_method\
request url params: 
* name: str
* age: int

response: \
[\
    “Str”,\
    “Str”\
    ]

==================

### EP_2
Method: POST\
EndPoint: /user_info_3\
request form data:
* name: str
* age: int
* salary: int

response: \
{'name': name,\
'age': age,\
'salary': salary,\
'family': {'children': [['Alex', 24], ['Kate', 12]],\
&emsp;&emsp;&emsp;'u_salary_1_5_year': salary * 4}}

==================

### EP_3
Method: GET\
EndPoint: /object_info_1\
request url params: 
* name: str
* age: int
* weight: int

response:\
{'name': name,\
'age': age,\
'daily_food': weight * 0.012,\
'daily_sleep': weight * 2.5\
}

==================

### EP_4
Method: GET
EndPoint: /object_info_2
request url params: 
* name: str
* age: int
* salary: int

response: \
{'start_qa_salary': salary,\
'qa_salary_after_6_months': salary * 2,\
'qa_salary_after_12_months': salary * 2.7,\
'qa_salary_after_1.5_year': salary * 3.3,\
'qa_salary_after_3.5_years': salary * 3.8,\
'person': {'u_name': [user_name, salary, age],\
&emsp;&emsp;&emsp;'u_age': age,\
&emsp;&emsp;&emsp;'u_salary_5_years': salary * 4.2}\
}

==================

### EP_5
Method: GET
EndPoint: /object_info_3
request url params: 
* name: str
* age: int
* salary: int

response: \
{'name': name,\
'age': age,\
'salary': salary,\
'family': {'children': [['Alex', 24], ['Kate', 12]],\
&emsp;&emsp;&emsp;'pets': {'cat': {'name':'Sunny',\
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;'age': 3},\
&emsp;&emsp;&emsp;'dog': {'name':'Luky',\
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;'age': 4}},\
'u_salary_1_5_year': salary * 4}\
}

==================

### EP_6
Method: GET
EndPoint: /object_info_4
request url params: 
* name: str
* age: int
* salary: int

response: \
{'name': name,\
'age': int(age),\
'salary': [salary, str(salary * 2), str(salary * 3)]\
}

==================

### EP_7
Method: POST
EndPoint: /user_info_2
request form data: 
* name: str
* age: int
* salary: int

response: \
{'start_qa_salary': salary,\
'qa_salary_after_6_months': salary * 2,\
'qa_salary_after_12_months': salary * 2.7,\
'qa_salary_after_1.5_year': salary * 3.3,\
'qa_salary_after_3.5_years': salary * 3.8,\
'person': {'u_name': [user_name, salary, age],\
&emsp;&emsp;&emsp;
'u_age': age,\
&emsp;&emsp;&emsp;
                     'u_salary_5_years': salary * 4.2}\
          }