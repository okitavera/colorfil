# colorfil
Generate 16 color for Xresources colorscheme from one-color

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
