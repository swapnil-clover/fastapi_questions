What is an API?
What is a path operation?
What is the difference between a URL path and an HTTP method?
What does @app.get("/") do?
What is the purpose of pyproject.toml?
Why do we have uv.lock?
Why are we using uv?
What is /docs?
What is /redoc?
Why shouldn’t a growing application keep everything inside one file?
What is a route?
What is a path parameter?
What is a query parameter?
How do you declare a path parameter?
How does FastAPI know whether a parameter belongs to the path?
How does FastAPI know whether a parameter belongs to the query string?
What does book_id: int accomplish?
Why is a path parameter always required?
How do you make a query parameter optional?
What does q: str | None = None mean?
How do default query parameters work?
What are skip and limit commonly used for?
Why does route ordering matter?
What is the difference between 200 and 404?
Why are HTTP status codes important?
Why is returning all database records at once potentially problematic?
Why are we currently using in-memory data?
Why will we eventually replace it with a database?
What is a request body?
Why is POST commonly used for creating resources?
What is Pydantic?
What does BaseModel provide?
How does FastAPI know a parameter is a request body?
What makes a model field required?
How do you make a field optional?
What does Field do?
What does Field(gt=0) mean?
What does Field(ge=1000, le=2100) mean?
What is model_dump() used for?
What is response_model?
Why should input and output models often be separate?
Why is 201 Created appropriate for successful creation?
What happens when invalid request data reaches a Pydantic model?
Why should validation happen near the API boundary?
Why shouldn’t internal database data automatically become an API response?
Why are we still using an in-memory collection instead of a database?

Question 1

What is a request body?
Question 2

Why do we use Pydantic models?
Question 3

What does this mean?

product: ProductCreate

Question 4

What is the difference between:

gt=0

and:

ge=0

Question 5

Why do we use:

Annotated

Question 6

Where should business logic live?

main.py
route
schema
service

Question 7

What happens when invalid request data is submitted?
Question 8

How can FastAPI know whether a parameter comes from:

Path
Query
Body
