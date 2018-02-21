# colorfil
Generate 16 color for Xresources colorscheme from one-color

# Installation

Download the script :

    wget https://github.com/yuune/colorfil/raw/master/colorfil
Make the script executable :

    $ chmod +x colorfil

Then move it to somewhere in your $PATH (/usr/bin, /usr/local/bin, etc)

# Usage

    $ colorfil -c [#hexcolor] [-o output_file]

Available options:

     -c, --color [#HEXCOLOR]    define your color in hex
     -o, --outfile [FILE]       send output to the file
 
 if no -o or --outfile, the result is printed directly to stdout.  

## Example

    $ colorfil -c #ff8899

    ... or with `-o

    $ colorfil -c #ff8899 -o ~/.Xresources-temp
 

## License

The code is available under the [MIT license](LICENSE.md).
