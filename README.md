<div align="center">

# simple-book-api

A simple book API written in Go

![GitHub repo size](https://img.shields.io/github/repo-size/AucaCoyan/simple-book-api)
![Lines of code](https://img.shields.io/tokei/lines/github/AucaCoyan/simple-book-api)

![GitHub last commit](https://img.shields.io/github/last-commit/AucaCoyan/simple-book-api)
![GitHub issues](https://img.shields.io/github/issues/AucaCoyan/simple-book-api)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AucaCoyan/simple-book-api)
![GitHub](https://img.shields.io/github/license/AucaCoyan/simple-book-api)
![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/AucaCoyan/simple-book-api)

<!-- template badges
-->

[Features](#features) •
[Installation](#installation) •
[Contributing](#contributing)

</div>

---

# Features

- [x] GET all books at `localhost:8080/books`
- [x] GET book by id at `localhost:8080/books/:id`
- [x] POST add book at `localhost:8080/books`
- [x] PATCH checkout book by id=N at `localhost:8080/checkout?id=N`
- [x] PATCH return book by id=N at `localhost:8080/return?id=N`
- [ ] Save file

---

# Installation

1. Clone the repo

```
git clone https://github.com/AucaCoyan/simple-book-api
```

2. Install dependencies

```
pipenv install
```

3. Run main.go

```
go run main.go
```

---

# Contributing

I'm open to suggestions or PRs!

Please feel free to contribute as you wish

<!--- template

# Section 1

Text lore ipsum It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

---

# Installation

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

---

# Configuration

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

---

# Contributing

I'm open to suggestions or PRs!
Please feel free to contribute as you wish

<details>
<summary>Linux (tree 1)</summary>

To install zoxide, run this command in your terminal:

```sh
curl -sS https://webinstall.dev/zoxide | bash
```

Alternatively, you can use a package manager:

| Distribution  | Repository            | Instructions             |
| ------------- | --------------------- | ------------------------ |
| Ubuntu 21.04+ | [Ubuntu Packages]     | `apt install zoxide`     |
| Void Linux    | [Void Linux Packages] | `xbps-install -S zoxide` |

</details>

<details>
<summary>macOS (tree 2)</summary>

To install zoxide, use a package manager:

| Repository | Instructions          |
| ---------- | --------------------- |
| [Homebrew] | `brew install zoxide` |
| [MacPorts] | `port install zoxide` |

</details>

<details>
<summary>Windows (tree 3)</summary>

To install zoxide, run this command in your command prompt:

```sh
curl.exe -A "MS" https://webinstall.dev/zoxide | powershell
```

Alternatively, you can use a package manager:

| Repository      | Instructions                    |
| --------------- | ------------------------------- |
| **[crates.io]** | `cargo install zoxide --locked` |
| [Chocolatey]    | `choco install zoxide`          |

</details>

--->
