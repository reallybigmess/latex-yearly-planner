Custom fork of latex-yearly-planner with some changes:
1. Default branch is rubify
2. Created a custom light configuration, based on one from wolfallein in discussion # 158


==========

# Latex Yearly Planner

A tool to generate a yearly planner for E-Ink and tablet devices.

The planner is generated in Typst (haha) and compiled to PDF.

Go to [discussions][3] to find and download the planner.

## Installation
### Dependencies

1. [Ruby][1] >= 3.1.3
2. [Typst][2]
3. [Ghostscript][4] (optional; gs binary)

## Installation

1. Clone the repository.
2. Run `bundle`.

## Usage

```shell
bundle exec exe/latex_yearly_planner generate <config_file>
```
## Configuration

Check out existing configs in `config` directory.

## How it works

1. Ruby code generates a Typst file.
2. Typst compiles the file to PDF.
3. (Optional) Ghostscript is used to compress the PDF.


[1]: https://www.ruby-lang.org/
[2]: https://typst.app/
[3]: https://github.com/kudrykv/latex-yearly-planner/discussions
[4]: https://ghostscript.com/
