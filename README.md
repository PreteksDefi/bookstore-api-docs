# Bookstore API Documentation

This API allows developers to manage a bookstore's inventory, customers, and orders.

## Base URL
```
https://api.fakebookstore.com/v1
```

## Authentication
- API Key via headers:
```
Authorization: Bearer YOUR_API_KEY
```

## Endpoints

### GET /books
Returns a list of available books.

### POST /books
Adds a new book to the inventory.

### GET /books/{id}
Gets details about a specific book.

## Example Request (GET /books)
```bash
curl -H "Authorization: Bearer YOUR_API_KEY" https://api.fakebookstore.com/v1/books
```
