# Flight Booking
A simple flight booking platform built as part of our DevOps course.

## Cloning
To clone the repository along with all its submodules, use the following command:
```
	git clone https://github.com/TheL0L/Flight_Booking.git --recursive
```

## Updating
To pull updates for all submodules, run:
```
	git submodule foreach git pull origin master
```

## Usage
1. use `docker-compose` to build and run the containers for the backend, frontend, and database:
```
	docker-compose up --build
```

2. Navigate to the locally hosted* [Flight Booking](https://localhost:3000/) website.
