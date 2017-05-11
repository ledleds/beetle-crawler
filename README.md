# Eureka Crawler


Final project (weeks 11 & 12) at Makers Academy. Tasked with working on a project of our choice in languages and testing frameworks of our choice.

Team:
- [Clem Capel-Bird](https://github.com/ClemCB)
- [Nicholas Leacock](https://github.com/marudine)
- [Vicky Ledsom](https://github.com/ledleds)
- [Rory McGuinness](https://github.com/rorymcgit)

## Installation

- If you don't already have Python 3 installed run ``` brew install python3 ```
- To install dependencies, in the project root run ``` pip3 install -r requirements.txt ```

To create your test and development databases and relevant tables:

- Run ```./db-config.sh```
- If you get an error regarding permissions, you'll need to run ```chmod +x db-config.sh```, then run the above again.

To crawl:

- Open /initiate_crawl.py
- Enter a website to begin crawling
- Run ``` python3 initiate_crawl.py ```

## Tests

- To run the tests, in the root of the project run ``` python3 -m unittest discover -s test -p "*_tests.py" ```

## Screenshot

This screenshot shows part of the terminal output mid crawl:

![alt text](/Screenshots/crawler.jpg?raw=true "Crawling")
