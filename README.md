## Hi I'm Jimmy 👋

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
![visitors](https://komarev.com/ghpvc/?username=Lily-404&label=Profile%20views&color=0e75b6&style=flat)

```go
package main

import "fmt"

type Developer struct {
	name        string
	role        string
	languages   []string
	prevExp     string
	currentFocus string
}

func (d Developer) sayHi() {
	fmt.Printf("Hi, I'm %s! I specialize in %s and have experience in %s. "+
		"I'm currently focusing on %s while exploring how applied design, distributed systems and developer tools can improve engineering workflows. "+
		"Thanks for visiting my GitHub!\n",
		d.name, d.role, d.prevExp, d.currentFocus)
}

func main() {
	dev := Developer{
		name:        "Jimmy",
		role:        "Software Development",
		languages:   []string{"JavaScript", "Go", "Java"},
		prevExp:     "Backend Development (Spring Boot, Gin)",
		currentFocus: "Generative AI, Go",
	}
	dev.sayHi()
}
```

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Lily-404&show_icons=true&theme=default" width="50%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lily-404&layout=compact&theme=default" width="38%" />
</p>
