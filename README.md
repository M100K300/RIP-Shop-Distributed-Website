# REST in Peace web application

## Rules of the development and usage of this Git Repository

[1] - Create branches from clickup<br>
[2] - No pushing to `master`<br>
[3] - One to create the branch and commit shall merge it in the end<br>
[4] - No merging without an approval from another team member<br>
[5] - CLEAN YOUR CODE (no tones of comments, all `final` if it can be immutable, keep constants together for easier refactoring)<br>
[6] - Squash commits if prompted during merge

## Project details

This is a distributed system group project aimed to show an understanding of REST API and have some fun!

This project uses clickup and gitlab for tracking.

## Installation

To install tha application:

1. `cd` to the project directory
2. launch docker
3. run the `run.sh` script using following command

```shell
bash run.sh
```

4. navigate to `http://localhost:8081` in any browser

## Project Structure

- [Project structure and API specifications](../master/DIS_SYSTEM.drawio) can be opened using https://app.diagrams.net

## Ports

Rip Api `8080`<br>
Nginx `8081` <br>
User Api `8083` <br>
Coffin Api `8084` <br>
Image Api `8085` <br>
Clean Api <br>
Ui `8089`

## Notes

Please note, that a lot of the project was done with **pair programming**.
