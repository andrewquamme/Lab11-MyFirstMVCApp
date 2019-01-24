# Lab11-My First MVC App

## Directions
- Today you will be creating your first ASP.NET Core MVC web application. Provided is a csv file of all the "Time" Persons of the year from 1927 - 2016. Create a web app that will allow a user to put in a span of 2 different years, and a list of all the winners will be returned.
- Your web app should originate from an empty Web App template, with all controllers and views manually created, do not scaffold. If you are having trouble remembering the process to create a basic MVC app, refer to the Resources section below for assistance.

## Usage

## API
A model class named `TimePerson` that contains the following properties(these are the headers of the csv file):
```
	public int Year { get; set; }
	public string Honor { get; set; }
	public string Name { get; set; }
	public string Country { get; set; }
	public int BirthYear { get; set; }
	public int DeathYear { get; set; }
	public string Title { get; set; }
	public string Category { get; set; }
	public string Context { get; set; }
```

