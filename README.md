# PartiesApplication

This repository contains a JavaFX application that visualizes the relative support of various political parties over time using a line chart. This project showcases my abilities in JavaFX, data visualization, and file handling in Java.

## Features

- **Data Visualization**: Displays a line chart of party support from 1968 to 2008.
- **File Handling**: Reads data from a TSV file.
- **JavaFX**: Utilizes JavaFX for creating the graphical user interface.

## Application Overview

The `PartiesApplication` class extends the `Application` class from JavaFX. It reads data from a `partiesdata.tsv` file, processes the data, and displays it in a line chart. Each line represents the relative support of a different political party over a range of years.

### Main Components

- **NumberAxis**: Defines the X and Y axes of the line chart.
- **LineChart**: The chart that displays the data.
- **XYChart.Series**: Represents a single series of data in the chart.
