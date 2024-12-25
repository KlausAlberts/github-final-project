# github-final-project

simple-interest.sh is a Linux shell script that calculates simple interest given principal,
annual rate of interest and time period in years.

## Installation

Log in to your Linux user account. Then open a terminal and create a new directory with the 
command 
```bash 
mkdir /home/<your_username>/git_repos
```.
Replace <your_username> with your user name.
Then change to the directory /home/<your_username>/git_repos and clone the repository 
https://github.com/KlausAlberts/github-final-project.git into this directory.

To make the shell script executable, change the file attribute with

```bash
chmod +x simple-interest.sh
```.

## Run

Run the script using 
```bash 
./simple-interest.sh
```.

## Usage
```bash
Input:
   p, principal amount
   t, time period in years
   r, annual rate of interest
Output
   simple interest = p*t*r
```
## Contributing   

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)
