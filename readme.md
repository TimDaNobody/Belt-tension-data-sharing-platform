# Belt tension data sharing platform

## Table of content:

### [Introduction](#introduction-1)

### [How to find exsisting results](#how-to-find-exsisting-results-1)

### [How to perform the test](#how-to-perform-the-test-1)

### [How to submit your test results](#how-to-submit-your-test-results-1)

###

## Introduction:

This repository serves as a timing belt tension data sharing platform for all 3D printing enthusiasts. Since there are too many different models and types of 3D printers for us to test them all. We decided to create this platform for everyone to share their test results, and to make it easier for everyone to find the most suitable timing belt tension for their printers.

## How to find exsisting results:

-You can use your printer model number to search in the [tension_summary](./summary) file

## How to perform the test:

- Get the [tension_data_template](./templates)

- Follow the Guide [here](https://prorifi3d.com/pages/how-to-tune-your-timing-belt)

## How to submit your test results:

- Test result should be submitted via the form of "Pull request"

- To do this, fork the repo first

- Navigate to the folder of your machine. If it is not created yet, created the folder following the [rules]()

- Fill the tension data template, rename it with [Model]-[Optimum tension]-[Provider]

- Start a "Pull request"

## Rules and orgnizations for data

- The data is sorted in the following order

|-- data
	|-- Brand
		|-- Model
			|-- Modded
				|-- [Model]-[Optimum tension]-[Provider].csv
				|-- ...
			|-- Stock
				|-- [Model]-[Optimum tension]-[Provider].csv
				|-- ...