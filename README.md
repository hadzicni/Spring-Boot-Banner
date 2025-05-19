# 🌱 Spring Boot Banner

A minimal repository to hold a custom `banner.txt` for use in **Spring Boot** applications. Perfect for developers who want a touch of branding, ASCII art or identity when their app starts up.

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-banner.txt-success?logo=springboot)
![License](https://img.shields.io/badge/license-MIT-green)
![ASCII](https://img.shields.io/badge/type-ASCII%20Art-yellow)

---

## ✨ What is this?

Spring Boot allows you to display a custom banner in the console at app startup.

By placing a `banner.txt` file in your app’s `/resources` directory, you can inject custom:

- ✅ ASCII text logos
- 🌐 Version or build info
- 💡 Fun messages or metadata
- 🧪 Developer signature

This repo contains a reusable and clean `banner.txt` template.

---

## ⚙️ How to use

### 🧩 Option 1: Copy manually

1. Copy the contents of `banner.txt`
2. Paste into your own Spring Boot project under:

```
src/main/resources/banner.txt
```

3. Run your Spring Boot app and enjoy the banner.

### ⚙️ Option 2: Automate via Maven/Gradle

You can include this file in your build process or store it in a company-wide resource directory for reuse.

---

## ✍️ Example Output

> Depending on your terminal, your output might look like:

```
 ___  ___  ________  ________  ________  ___  ________  ________   ___     
|\  \|\  \|\   __  \|\   ___ \|\_____  \|\  \|\   ____\|\   ___  \|\  \    
\ \  \\\  \ \  \|\  \ \  \_|\ \\|___/  /\ \  \ \  \___|\ \  \\ \  \ \  \   
 \ \   __  \ \   __  \ \  \ \\ \   /  / /\ \  \ \  \    \ \  \\ \  \ \  \  
  \ \  \ \  \ \  \ \  \ \  \_\\ \ /  /_/__\ \  \ \  \____\ \  \\ \  \ \  \ 
   \ \__\ \__\ \__\ \__\ \_______\\________\ \__\ \_______\ \__\\ \__\ \__\
    \|__|\|__|\|__|\|__|\|_______|\|_______|\|__|\|_______|\|__| \|__|\|__|                       
```

You can generate new ASCII banners using tools like:

- https://patorjk.com/software/taag/
- https://manytools.org/hacker-tools/ascii-banner/

---

## 👨‍💻 Author

Made by **Nikola Hadzic**  
GitHub: [@hadzicni](https://github.com/hadzicni)

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
