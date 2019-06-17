# TheatreServerBooking
Create Theatre Server Booking system from TBSServer to be used in support for Client side. <br>
The Objective: To develop an implementation to the Server system of a Theatre Booking System where: “A theatre booking system has to manage performances of acts performed by artists in different theatres. Theatres have seats. Tickets are issued for seats for a performance. Any act has a single artist (which may be a group), but an artist can put on many acts, and each act can have multiple performances”. <br>

Given that: <br>

public interface TBSServer<br>
Provides the interface to a server for a theatre booking system (TBS). The server manages acts held in theatres. An act is put on by an artist (e.g. "Greta Van Fleet"), and has a duration. An act has a series of performances (e.g., "Friday night at 6pm", "Saturday matinee at 2pm", and "Saturday night at 8pm") Performances take place in a theatre. Tickets are issued for seats. Seats in theatres are arranged as a square block, with as many seats in a row as there are rows. A seat is identified by the row number it is in and its position in the row. About half the seats are considered "premium" seating. These are the lowest numbered rows.
