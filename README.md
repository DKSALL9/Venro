# Venro
The provided Perl script is a tool for extracting and identifying patterns (likely API endpoints or similar data) from JavaScript files. It uses multi-threading to process multiple URLs concurrently and offers several options for input and output management.

# Install
```
git clone https://github.com/DKSALL9/Venro.git
```

# Usage
```
 __     __                              
 \ \   / /   ___   _ __    _ __    ___  
  \ \ / /   / _ \ | '_ \  | '__|  / _ \ 
   \ V /   |  __/ | | | | | |    | (_) |
    \_/     \___| |_| |_| |_|     \___/ 
                                        
Usage: Venro.pl [options]
Options:
    -l <file>   .txt file containing JavaScript file URLs
    -u <url>    Single JavaScript file direct URL
    -o <file>   Output file to save endpoints
    -h          Display this help message

Please use one of -u for a single JS file URL or -l for a .txt file containing JS file URLs.
```
