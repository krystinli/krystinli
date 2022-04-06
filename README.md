### Hi there 👋

```py
from typing import List

class Krystin:

    def __init__(self):
        self.username: str = "krystinli"
        self.name: str = "Krystin Li"
        self.location: str = "Toronto, ON"
        self.languages: List[str] = ["English", "Mandarin", "Cantonese", "Python"]
        self.hobbies: List[str] = ["🏃‍♀️", "🏓", "🧑‍🍳", "🛫", "🖼️", "🧋", "☕"]
        self.workplace: str = "Meta 🪐" :
        self.job: str = "Data Scientist"
        self.contact: str = "likrystin@gmail.com"

    def __str__(self):
        return self.name

if __name__ == "__main__":
    me = Krystin()
```

