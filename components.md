# Data

## Data layer

- List of Gentlemen
  - id
  - name
  - profession
  - twitter
  - picture
  - alternativeText
  - selected

## Data modifications

- Toggle status of gentleman property "selected"
- Set status of every gentleman property "selected" as true
- Delete gentleman

# Components

## App

- Contains the gentlemen list ✅

- Contains the function toggleGentleman ✅
- Contains the function selectEveryGentleman ✅
- Contains the function deleteGentleman ✅

- Sends the function toggleGentleman to Gentleman
- Sends the function deleteGentleman to Gentleman
- Sends the function selectEveryGentleman to Button

- Sends the count of selected gentlemen to Info

## Info

- Receives the count of selected gentlemen from App
- Displays the count of selected gentlemen

## Button SelectAll

- Receives the function selectEveryGentleman

## Gentleman

- Receives the function toggleGentleman
- Receives the function to deleteGentleman
- Receives a Gentleman
