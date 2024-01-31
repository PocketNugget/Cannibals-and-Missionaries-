# Missionaries and Cannibals Problem in Prolog

A Prolog implementation of the classic Missionaries and Cannibals problem, designed to explore problem-solving techniques using state-space search.

## Description

The Missionaries and Cannibals puzzle involves transporting three missionaries and three cannibals from the left side of a river to the right side using a boat. The rules state that at any point on either side of the river, the number of cannibals cannot exceed the number of missionaries, or the cannibals will overpower the missionaries. The objective is to find a sequence of moves that successfully transports all individuals from the left to the right side of the river.

## Prerequisites

To run this Prolog program, you need:

- [SWI-Prolog](http://www.swi-prolog.org/Download.html)

## Getting Started

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/YourUsername/Missionaries-and-Cannibals-Prolog.git
    ```

2. Load the Prolog program.

    ```bash
    swipl -s missionaries_and_cannibals.pl
    ```

3. Run the `find` query to initiate the search for a solution.

    ```prolog
    ?- find.
    ```

## Rules

- Two players: Missionaries (`M`) and Cannibals (`C`).
- The boat can carry at most two individuals at a time.
- The left side starts with 3 Missionaries (`MMM`) and 3 Cannibals (`CCC`).
- The goal is to transport all individuals to the right side.
- Constraints: At any point, the number of Cannibals cannot exceed the number of Missionaries on either side.

## Built With

- SWI-Prolog - [Download here](http://www.swi-prolog.org/Download.html)

## Authors

- **Your Name** - [Your GitHub Profile](https://github.com/YourUsername)

## License

This project is licensed under the [MIT License](LICENSE.md) - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Special thanks to Prolog and its community.
- Inspired by classic AI problems and state-space search techniques.
