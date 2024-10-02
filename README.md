#  who am I ?

```python
class WhoAmI():
    def personal_information(self):
        first_name = "Amir Mahdi"
        last_name = "Dehghani"
        age = "May 26, 2004"
        return f"first_name:{first_name}\nlast_name:{last_name}\nMay 26, 2004:{age}"

    def skill(self):
        expertise = "Python - Django - Django Rest Framework "
        to_know = "Git - Github - GitLab - Html - Css - Ajax ... "
        interest = "Web BackEnd - Network Security"
        courses_completed = "Python - Django - HtmlCss - Git - Network++ - Linux - CEH ... "
        return f"expertise: {expertise}\nto_know: {to_know}\ninterest: {interest}\ncourses_completed: {courses_completed}"


print(WhoAmI().personal_information())
print("-------------------------------")
print(WhoAmI().skill())
```
![]()
