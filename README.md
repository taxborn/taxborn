# :wave: Hi, I'm Braxton! - [taxborn.com](https://www.taxborn.com)
I'm a 21-year-old computer science student at [Minnesota State University, Mankato](https://mnsu.edu), 
interested in compilers and API development. I enjoy creating tools that make 
computer interaction more user-friendly for developers and the rest of the world. 
I believe it's important to make it easy to innovate. Currently, I'm working on 
research in [continuous mouse authentication using machine learning](https://github.com/taxborn/mauth-research-project). 
Outside of school, I like to hike the bluffs of southern Minnesota!

```py
class Human:
	name = "Braxton Fair"
	age = getAge("10-18-2001") # 21!
	hobbies = [
		"Working on my compiler",
		"Spending too much time configuring my editor (neovim)",
	]

	def getAge(birthdate: str):
		birthdate = datetime.strptime(birthdate, "%m-%d-%Y")
		today = datetime.today()
		age = today.year - birthdate.year - ((today.month, today.day) < (birthdate.month, birthdate.day))
		return age

	def goals():
		CreateAProgrammingLanguage() # Currently being worked on!
		Graduate() # May 2024
		GetMyFirstJob()
```

## Current Projects
- :coconut: [Coquito](https://github.com/taxborn/coquito), a programming language!
- :mouse: [mAuth Research Project](https://github.com/taxborn/mauth-research-project), a machine learning research project.
- Working on my DSA @ [Leetcode](https://leetcode.com/taxborn/)

### My Github Stats!
![taxborn's Github Stats](https://github-readme-stats.vercel.app/api?username=taxborn&count_private=true&hide=issues)
