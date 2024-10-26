# Updating the README content to remove links from the Table of Contents

readme_content_no_links = """
# Movie App - useEffect Project

This project is part of a Udemy course on React's `useEffect` hook. It covers data fetching, error handling, component lifecycle, and advanced effect management, using a movie application as the primary project.

## Project Overview

This app allows users to:
- Fetch and display a list of movies.
- View details for a selected movie.
- Add movies to a "watched" list.
- Dynamically update the document title.
- Listen to keyboard events for enhanced interactivity.

## Table of Contents

1. Component Lifecycle
2. Fetching Data
3. Using useEffect
   - Setting Up Effects
   - Async Data Fetching
   - Loading States
   - Handling Errors
   - Dependency Array
4. Advanced Features
   - Synchronizing Movie Queries
   - Selecting and Viewing Movie Details
   - Adding Watched Movies
   - Dynamic Page Title
   - Cleanup Functions
5. Final Lessons
   - Cleaning Up Data Fetching
   - Listening to Keypress Events
   - Challenge #1: Currency Converter
6. Conclusion

---

## Component Lifecycle

A foundational overview of how React components mount, update, and unmount, focusing on when and where to fetch data within lifecycle phases.

## Fetching Data

An examination of data-fetching pitfalls in React and how the `useEffect` hook resolves them.

## Using useEffect

### Setting Up Effects

Introduces `useEffect` and explains its main purpose in handling side effects in functional components.

### Async Data Fetching

Guides setting up asynchronous data fetching with `useEffect`, ensuring efficient and correct data retrieval.

### Loading States

Incorporates a loading state for a better user experience during data fetching.

### Handling Errors

Discusses error-handling techniques, ensuring users are informed if data-fetching issues arise.

### Dependency Array

Explains the `useEffect` dependency array, detailing how it controls effect re-runs and manages dependencies.

## Advanced Features

### Synchronizing Movie Queries

Synchronizes data between movie queries, ensuring correct data in response to user interactions.

### Selecting and Viewing Movie Details

Implements the functionality to select a movie and load detailed information.

### Adding Watched Movies

Allows users to add movies to a "watched" list, managed within the app’s state.

### Dynamic Page Title

Updates the page title based on the selected movie, demonstrating dynamic title management.

### Cleanup Functions

Explores `useEffect` cleanup functions, ensuring effects are properly removed on component unmount.

## Final Lessons

### Cleaning Up Data Fetching

Covers best practices for cleaning up data-fetching effects, including canceling requests when components unmount.

### Listening to Keypress Events

Introduces a new effect for listening to keypress events, enhancing app interactivity.

### Challenge #1: Currency Converter

A challenge to apply `useEffect` in building a currency converter, reinforcing async data fetching and cleanup concepts.

## Conclusion

This project provides a comprehensive understanding of `useEffect` and best practices for data fetching, error handling, and advanced lifecycle management in React.
"""
