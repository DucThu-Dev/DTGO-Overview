<br />
<div align="center">
<img  src="Assets/dtgo_icon_w500.png" alt="DTGO Logo"  width="160"  height="80">
<br />
<br />
<p  align="center">
Real-time booking vehicle service, includes server, passenger and driver mobile app.
</p>  
</div>

## Google Play Store Release

- [DTGO](https://play.google.com/store/apps/details?id=com.ducthu.datn.client_dt_go) application for passengers.

- [DTGO Driver](https://play.google.com/store/apps/details?id=com.ducthu.datn.driver_dt_go) application for drivers.

## About The Project

This project is inspired and cloned base on some other modern booking car/bike with real-time tracking driver position like Grab, Gojek, Uber,...

### Key features:

- Server is available to receive request from both passenger and driver and create an environment for them to communicate with each other.

- Driver register to receive trip with server, so when there are a new trip nearby available, he should accept and pick up passenger to the desire destination.

- Passenger book a vehicle to move to a destination, with current positon and destination data.

### Built With

This project use these framework and runtime environment:

- [Nodejs](https://nodejs.org/en/) for server side.

- [Flutter](https://flutter.dev/) for mobile app side.

The most important package of this project so that devices can communicate with each other almost real-time is [Socket.io](https://socket.io/) for Server - Nodejs and [Socket.io Client](https://pub.dev/packages/socket_io_client) for Mobile - Dart/Flutter.

## DEMO

### Regular trip

<img src="Assets/Demo gif/regular_trip_1.gif" height="480px"> <img src="Assets/Demo gif/regular_trip_2.gif" height="480px"> <img src="Assets/Demo gif/regular_trip_3.gif" height="480px"> <img src="Assets/Demo gif/regular_trip_4.gif" height="480px">

### Register User

<img src="Assets/Demo gif/register_user_1.gif" height="480px"> <img src="Assets/Demo gif/register_user_2.gif" height="480px"> <img src="Assets/Demo gif/register_user_3.gif" height="480px">

### No Driver available

<img src="Assets/Demo gif/no_driver_available_1.gif" height="480px">

### Driver accepts trip but passenger canceled trip just before.

<img src="Assets/Demo gif/driver_accept_passenger_cancel_1.gif" height="480px"> <img src="Assets/Demo gif/driver_accept_passenger_cancel_2.gif" height="480px">

### Passenger cancel in trip

<img src="Assets/Demo gif/passenger_cancel_in_trip_1.gif" height="480px"> <img src="Assets/Demo gif/passenger_cancel_in_trip_2.gif" height="480px">

### 1 Passenger register trip, 2 Driver waiting for trip

<img src="Assets/Demo gif/1_passenger_2_driver_1.gif" height="480px"> <img src="Assets/Demo gif/1_passenger_2_driver_2.gif" height="480px"> <img src="Assets/Demo gif/1_passenger_2_driver_3.gif" height="480px">

### 1 Driver waiting for trip, 2 Passenger register trip

<img src="Assets/Demo gif/2_passenger_1_driver_1.gif" height="480px"> <img src="Assets/Demo gif/2_passenger_1_driver_2.gif" height="480px"> <img src="Assets/Demo gif/2_passenger_1_driver_3.gif" height="480px">

## Screenshots

### DTGO

<img src="Assets/DTGO/launch_screen_w250.jpg" height="480px"><img src="Assets/DTGO/input_info_screen_w250.jpg" height="480px"><img src="Assets/DTGO/home_screen_w250.jpg" height="480px"><img src="Assets/DTGO/history_screen_w250.jpg" height="480px"><img src="Assets/DTGO/input_destination_screen_w250.jpg" height="480px"><img src="Assets/DTGO/pick_up_screen_w250.jpg" height="480px"><img src="Assets/DTGO/trip_info_screen_w250.jpg" height="480px"><img src="Assets/DTGO/waiting_screen_w250.jpg" height="480px"><img src="Assets/DTGO/trip_info_dialog_w250.jpg" height="480px"><img src="Assets/DTGO/driver_reach_screen_w250.jpg" height="480px"><img src="Assets/DTGO/driver_info_screen_w250.jpg" height="480px"><img src="Assets/DTGO/pay_screen_w250.jpg" height="480px"><img src="Assets/DTGO/no_driver_screen_w250.jpg" height="480px"><img src="Assets/DTGO/loading_screen_w250.jpg" height="480px"><img src="Assets/DTGO/user_screen_w250.jpg" height="480px">

### DTGO Driver

<img src="Assets/DTGO Driver/launch_screen_w250.jpg" height="480px"> <img src="Assets/DTGO Driver/input_info_screen_w250.jpg" height="480px"> <img src="Assets/DTGO Driver/home_screen_w250.jpg" height="480px"> <img src="Assets/DTGO Driver/cancel_sceen_w250.jpg" height="480px"> <img src="Assets/DTGO Driver/receive_new_trip_w250.jpg" height="480px"> <img src="Assets/DTGO Driver/head_to_pickup_screen_w250.jpg" height="480px"> <img src="Assets/DTGO Driver/reach_destination_screen_w250.jpg" height="480px"> <img src="Assets/DTGO Driver/pay_sceen_w250.jpg" height="480px"> <img src="Assets/DTGO Driver/user_screen_w250.jpg" height="480px">

## Author

👤 **DucThu-Dev**

- Website: https://github.com/DucThu-Dev

- Github: [@DucThu-Dev](https://github.com/DucThu-Dev)

- LinkedIn: [@Trần Đức Thư](https://linkedin.com/in/Trần Đức Thư)
