
<div align="center">
  <h1>Shell Scripts</h1>
</div>

A collection of shell scripts I've written or use regularly for automation, system management, and personal productivity.

These scripts are primarily developed for Unix-like systems (e.g. Linux). Compatibility with macOS, WSL, or BSD variants is not guaranteed.

---

## Installation & Usage

Clone the repository and move the scripts into a directory listed in your `PATH` (e.g. `~/.local/bin`) to make them globally accessible.

### Quick Setup

```sh
git clone https://github.com/s4nj1th/shell-scripts.git
cd shell-scripts

# Make all non-Markdown files executable
chmod +x $(find . -maxdepth 1 -type f ! -name "*.md")

# (Optional) Move them to a directory in your PATH
mkdir -p ~/.local/bin
cp -t ~/.local/bin $(find . -maxdepth 1 -type f -executable)
````

---

## License

This project is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute the code. See the LICENSE file for full details.


---

## Notes

* These scripts may assume certain tools, shells, or environments. Review before use.
* Feel free to fork or adapt anything here to suit your workflow.
* Contributions are welcome, but this repository is primarily maintained for personal use.
