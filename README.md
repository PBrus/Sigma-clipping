# Sigma-clipping [![GitHub release](http://www.astro.uni.wroc.pl/ludzie/brus/img/github/ver20170207.svg "download")](https://github.com/PBrus/Sigma-clipping/blob/master/good_points) ![Written in Bash](http://www.astro.uni.wroc.pl/ludzie/brus/img/github/Bash.svg "language") ![Written in AWK](http://www.astro.uni.wroc.pl/ludzie/brus/img/github/Awk.svg "language")

Perform sigma-clipping on the data from a text file. This is a useful Linux tool.

## Installation

Download the program from the repository to your working directory, then make the script executable. I recommend to download it to any catalog pointed by the `$PATH` variable.

## Usage

At the beginning call the script from the terminal window without any arguments. This will you give you a necessary description how the program works:
```bash
$ good_points
```
To start using the program you need to prepare some data. If you need to see the program in action immediately, please download `data.lst` file to the working directory and then type:
```bash
$ good_points data.lst
```
This call will run the program with default arguments. If you want to influence on these values, please add next arguments:
```bash
$ good_points data.lst 7 1.8 10 80
```
After all the script generates an additional file with results in the working directory. Moreover some statistical information are printed on the screen.

I encourage to visit my website to see more detailed description of this program. The current link can be found on my [GitHub profile](https://github.com/PBrus).

## License

**Sigma-clipping** is licensed under the [MIT license](http://opensource.org/licenses/MIT).
