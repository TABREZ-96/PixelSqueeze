# Image Compressor

Image Compressor is a command line tool that allows you to easily compress and optimize images to reduce their file size without losing quality. The tool supports multiple image formats such as JPEG, PNG, GIF, etc.

## Installation

To install Image Compressor, you will need to have Python 3 installed on your machine. You can download the latest version of Python from the official website (https://www.python.org/downloads/).

Once you have Python installed, you can use pip to install the following libraries: 
pip install pillow
pip install numpy


## Usage

To compress an image, use the following command:
python imagecompress.py -i [image_path] -o [output_path] -q [quality]
For example, to compress a file called "example.jpg" to a quality of 75 and save it as "compressed_example.jpg" you would use the following command:
python imagecompress.py -i example.jpg -o compressed_example.jpg -q 75


## Supported Formats
- JPEG
- PNG
- GIF
- BMP
- TIFF

## Licensing

Image Compressor is released under the [MIT License](https://opensource.org/licenses/MIT).

## Contribution

If you would like to contribute to this project, feel free to submit a pull request. We welcome all contributions.

