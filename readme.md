# Bookings and Reservations

This is the repository for my bookings and reservations project, which is part of 
the Udemy course [Building modern web applications in Go](https://www.udemy.com/course/building-modern-web-applications-with-go/?referralCode=0415FB906223F10C6800).

- Built in Go version 1.15
  
Dependencies:

- [chi router](https://github.com/go-chi/chi)
- [alex edwards SCS](https://github.com/alexedwards/scs/v2) session management
- [nosurf](https://github.com/justinas/nosurf)
- [pgx](https://github.com/jackc/pgx/v4)
- [simple mail](https://github.com/xhit/go-simple-mail/v2)
- [Go validator](https://github.com/asaskevich/govalidator)

In order to build and run this application, it is necessary to 
install Soda (go install github.com/gobuffalo/pop/... ), create
a postgres database, fill in the correct values in database.yml, 
and then run soda migrate.

To build and run the application, from the root level of the project,
execute this command:
```
go build -o bookings ./cmd/web/ && ./bookings \
-dbname=bookings \
-dbuser=tcs
```
where you have the correct entires for your database name (dbName) 
and database user (dbUser)
For the full list of command flags, run ./bookings -h