<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=4000&pause=1000&color=00FFAA&center=true&vCenter=true&width=600&lines=Hello%2C+I'm+Daniel+%F0%9F%91%8B;Full-Stack+Developer+%40+Zone01+Kisumu;Go+%26+Python+Enthusiast;Building+Scalable+Systems+%26+Real-Time+Apps" alt="Typing SVG" />

  <br/>

  <!-- Optional: Add a cool banner or profile picture effect -->
  <!-- You can generate one at https://github-profile-header-generator or use your own -->
  <!-- <img src="YOUR_BANNER_LINK_HERE" width="800" alt="Banner"/> -->

  <h3>🚀 About Me</h3>

  ```go
  package main

  import "fmt"

  type Developer struct {
      Name           string
      Role           string
      Location       string
      Focus          string
      Currently      string
      FunFact        string
      Languages      []string
      Tools          []string
  }

  func main() {
      daniel := Developer{
          Name:      "Daniel (keyadaniel56 / danikeya)",
          Role:      "Full-Stack Developer @ Zone01 Kisumu",
          Location:  "Kisumu, Kenya",
          Focus:     "Building scalable backend systems & real-time applications",
          Currently: "Mastering advanced concurrency patterns in Go 🐹",
          FunFact:   "I'm 20h behind, but always ahead in code 🕒😎",
          Languages: []string{"Go", "Python", "JavaScript", "HTML/CSS"},
          Tools:     []string{"Gin", "PostgreSQL + pgxpool", "Docker", "Git"},
      }

      fmt.Printf("%+v\n", daniel)
  }
