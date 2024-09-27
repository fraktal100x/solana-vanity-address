# solana-vanity-address
create custom solana vanity wallet address 
//// first install the solana cli

sh -c "$(curl -sSfL https://release.solana.com/v1.16.2/install)"

After installing, set the Solana CLI path by adding the following line to your shell configuration file (.bashrc, .zshrc, etc.):
export PATH="/path/to/solana/cli:$PATH"


solana-keygen grind --help
/// if you want to see a list of all the commands

solana-keygen grind --starts-with customaddress:1 --ignore-case

solana-keygen grind --starts-with customaddress:1
solana-keygen grind --ends-with customaddress:1

try keeping it short, 3-4 characters, unless you want to wait forever
