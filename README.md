# Static Site Generator

Static site generator built with Python & OOP.

<h2><a id="table-of-contents">📚 Table of Contents</a></h2>

- [Requirements](#requirements)
- [Running the app](#running-the-app)
- [Running tests](#running-tests)

<h3><a id="requirements">📦 Requirements</a></h3>

- Python 3
- Bash shell or similar

<h3><a id="running-the-app">🚀 Running the app</a></h3>

[Chmod](https://en.wikipedia.org/wiki/Chmod) main.sh & run it. This will generate a `/public` folder based on the markdown content in the `content` folder and serve it through python http server. See the result on http://localhost:8888

```bash
chmod +x ./main.sh
./main.sh
```

<h3><a id="running-tests">🏗️ Running unit tests</a></h3>

[Chmod](https://en.wikipedia.org/wiki/Chmod) test.sh & run it. This will run all test files in src with the `test_` prefix.

```bash
chmod +x ./test.sh
./test.sh
```
