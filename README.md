# Blink API (PHP)
A simple books API

## Models
- Book
  - title
  - published_at
    
- Genre
  - title
    
- Author
    - name

## Relationships
- `Book` belongs to a `Genre` : `Genre` has many `Book`
- `Book` has many `Author` : `Author` has many `Book`

## Ingredients
- Laravel 8
