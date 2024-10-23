# The Go Programming Language

Go is an open source programming language that makes it easy to build simple,
reliable, and efficient software.

![Gopher image](https://golang.org/doc/gopher/fiveyears.jpg)
*Gopher image by [Renee French][rf], licensed under [Creative Commons 4.0 Attribution license][cc4-by].*

Our canonical Git repository is located at https://go.googlesource.com/go.
There is a mirror of the repository at https://github.com/golang/go.

Unless otherwise noted, the Go source files are distributed under the
BSD-style license found in the LICENSE file.

### Download and Install

#### Binary Distributions

Official binary distributions are available at https://go.dev/dl/.

After downloading a binary release, visit https://go.dev/doc/install
for installation instructions.

#### Install From Source

If a binary distribution is not available for your combination of
operating system and architecture, visit
https://go.dev/doc/install/source
for source installation instructions.

### Contributing

Go is the work of thousands of contributors. We appreciate your help!

To contribute, please read the contribution guidelines at https://go.dev/doc/contribute.

Note that the Go project uses the issue tracker for bug reports and
proposals only. See https://go.dev/wiki/Questions for a list of
places to ask questions about the Go language.

[rf]: https://reneefrench.blogspot.com/
[cc4-by]: https://creativecommons.org/licenses/by/4.0/

## Booking App

In this Go project we are assigned to make a booking app for a Go conference. 

The booking app stores a certain amount of tickets and it will immediately update the amount of tickets remaining once users have booked it. The protocols for entering data to book the ticket are enforced strictly in the booking app as failure in compiling to input the correct form of first name, last name, email, and number of tickets would result in the user being unable to book the tickets. If all of the protocols for the ticket booking are fulfilled, the booking app will display the list of bookings, a confirmation message, the remaining amount of tickets for the conference, and the first names of the bookings. Once all of that is displayed, after 30 seconds the app will send the amount of tickets booked to the user through the email used for booking.

![Screenshot 2024-10-19 151245](https://github.com/user-attachments/assets/d97eefef-6861-4065-a39c-d693997d9320)
