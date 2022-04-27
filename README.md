# Flights back-end recruitment test

Thanks for taking the time to do our back-end coding test. The challenge has two parts:

1) A [task](#task) to create a flights REST API.

2) A [task](#task) to display basic flights results in the Django Administration Site.

----

## Tasks

**REST API**

  - Fetch flight results from the provided `flights.json` (https://raw.githubusercontent.com/Skyscanner/full-stack-recruitment-test/main/public/flights.json) and save them into a SQLite database. The models created and their relationships are up to you.
  - Create an endpoint to LIST all of the flights with at least one query param to filter. The choice of the filter/filters is to be decided by your own criteria.

**Django Administration**

- Use the returned data to display a page of the fetched results in a user-friendly manner in the Django Administration. The format, columns, and all of the display details are up to you.

## Flight results

The provided (https://raw.githubusercontent.com/Skyscanner/full-stack-recruitment-test/main/public/flights.json) will return two collections of different items:

* **Itineraries** - These are the containers for your trips, tying together **Legs**, and **prices**. Prices are offered by an **agent** - an airline or travel agent.

* **Legs** - These are journeys (outbound, return) with **duration**, **stops** and **airlines**.

## Submission Guidelines

* A fork of this repository should be submitted to antonio@auxo.co with the implemented tasks in no less than 6h of the start of the assesment. However, the assesment is expected to take about 5h. The amount of time you take to take the assesment has no effect in the results.

## Evaluation Criteria

* Your implementation works as described in the [task](#task).
* Quality of the implemented code
* Design decisions (models, JSON structure, relationships between entities, etc)
* Videocall to explain the implemented code


----

Inspiration for the test format taken with ❤️ from [JustEat's recruitment test](https://github.com/justeat/JustEat.RecruitmentTest).
