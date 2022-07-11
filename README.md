# 👋 Hello I'm wong or Wei

```py
from dataclasses import dataclass, field
from typing import List


@dataclass
class DataCraftsman:
    name: str = "Sahacha Inchai"
    pronouns: str = "he/him/his"
    current_role: str = "junior Software Engineer"
    passions: List[str] = field(
        default_factory=lambda: [
            "software-engineering",
            "Blockchian-engineering",
            "Back-End",
        ]
    )

    def say_hi(self):
        return "Hi! Thanks for dropping by. :-)"


me = Coffeeman()
print(me.say_hi())
```

💬 Ask me anything about software engineering, data engineering, data science, and Python! 🐍
💬 Cryptocurrency 2.0

## 📝 Blogs
<details>
- 
- 
- 
</details>

## ✍🏻 Active projects
<details>
-
-
-
</details>

## 🙇🏻‍♂️ Support

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/wsweiritone) 

---

<p align="center">This <i>README</i> file is generated <b>every day</b>!</br />
Last refresh: Monday, 11 July, 08:22 GMT+7<br />
This profile is inspired by <a href="https://medium.com/@th.guibert/how-to-create-a-self-updating-readme-md-for-your-github-profile-f8b05744ca91">Thomas Guibert</a></p>
