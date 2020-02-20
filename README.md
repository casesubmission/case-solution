# Image Classification Program

> Image classifier for Philips products.

---
## Table of Contents (Optional)

- [Installation](#installation)
- [Google Colab](#colab)
- [Presentation](#presentation)
- [Contact](#contact)
- [License](#license)

---

## Installation

- After cloning the repository, please remove README.md file in model/val-images
- Before building Docker image, please add test images into model/val-images folder.
- After cloning, please apply Docker command below in the /model/ directory of the project to prevent path errors:

### Clone

```shell
$ git clone https://github.com/BxCvd1LZVDCvW74I/model.git`
```
### Setup

```shell
$ docker build -t philips-case -f Dockerfile .
```
### Setup

- For this case, I prepared a presentation about my approach to establish an image classification model.

/link/to/pdf

## Google Colab

- In this Google Colab notebook, I reproduced the results due to possible errors from Docker Toolbox for Windows 10 Home edition:
- Please run the notebook until cloning the repository and delete README.md file in model/val-images folder from Files tab in left.
- After cloning this repository is done, please upload test images to model/val-images folder and run the other cells to reproduce results.

/link/to/colab

## Contact

I'll be checking my e-mail through the competition. Contact information:
- E-mail: <a href="mailto:mburakbozbey@outlook.com" target="_blank">`mburakbozbey@outlook.com`</a>
- Website at <a href="https://mburakbozbey.github.io/" target="_blank">`mburakbozbey.github.io`</a>
- Linkedin at <a href="https://www.linkedin.com/in/mburakbozbey/" target="_blank">`@mburakbozbey`</a>

---
## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**