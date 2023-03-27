

<h1 align="center"> Hi, I'm Monica :grin: :coffee: </h1>

- 👀 I’m interested in code and coffee <3 
- 🌱 I'm currently always learning
- 📫 How to reach me  -> +55 (19) 998468664

### Backend Developer :briefcase:
### Data Analytics :briefcase:
### Recruit Web Developer :briefcase:


✔️ Python | Django
✔️ Java
✔️ Docker | Kubernetes


package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "An Engineer who deeps down into cosmology. Founder and Author at Divulge - https://divulge.in",
		"- 🔭 I’m currently working on":      "Divulge, a blog site which makes you question how much are you willing to divulge?",
		"- 🌱 I’m currently learning":        "Golang, MongoDB, RabbitMQ, GCP (For my personal growth) --- Sharpening my Front End Skills with Gatsby, Prismic.io (Personal goal)",
		"- 👯 I’m looking to collaborate on": "JavaScript, Python, Gatsby and Hugo related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 📫 How to reach me:":              "https://akashpawara.com",
	}
}

