```python
class Wojtek:
	def __init__(self):
		self.hobbies = ['horse riding', 'rock climbing']
		self.smart = random.choice([False, True])
		self.languages = ['Python', 'CSS', 'HTML', 'Java']
		self.contact = {"Discord": "OhFoxies#7805",
						"Email": "dcswzium@gmail.com",
						"Wanna play?": "https://steamcommunity.com/id/OhFoxies"}
		self.skills = None

	def getbetter(self):
		raise SystemError

	def code(self):
		if self.smart:
			self.startproject()
		else:
			self.sleep()

	@staticmethod
	def startproject():
		time.sleep(random.randint(5, 10))
		print("Ok I've got bored I don't do this any more.")
```
