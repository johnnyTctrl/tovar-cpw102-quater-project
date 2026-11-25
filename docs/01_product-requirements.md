# Product Requirements Document


## Problem

People who exercise regularly may have difficuty
remembering their previous workouts, weight,
sets, and repetitions.

## Desired outcome

Users will be able to record their workouts,
view their workout history, and track their
fitness progress over time 

## Scope

The application will be Pyton terminal-based
workout tracker for individual users.

## Out of Scope

- Online accounts
- Nutrition and calorie tracking
- Mobile applications
- Personalized workout reccommendations


## Requirements


### The product must

- Allow users to enter an exercise name.
- Record sets, repetitions, and weight lifted.
- Automatically record the workout date.
- Save workout information to a CSV file.
- Display previously saved workouts.
- Reject invalid user inputs. 

### The product should

- Provide an easy-to-use menu.
- Allow users to record multiple exercises
- Display clear error messgages

### The product could

- Search workout history by exercise name.
- Display personal weightlifting records.

### Assumptions and constraints 
- The application will use python 3.12 or newer.
- Workout information will be stored locally.
- Weight will be measured in pounds.
- The application will work without internet.
- Only one user will use the application at a time.

### Non-functional requirments
- The menu must be easy to understand
- Saved workouts must remain available after
  closing and reopening the program
- Invalid inputs must not crash the program 
