# Felucca — Sail when the wind says yes.

**BINF 301 Information \& Communication Architecture — GIU — Team \[11]**

Felucca is a web app for booking traditional Nile felucca rides in Cairo, Luxor and Aswan at fixed prices. Each time slot gets a sailing score from the live wind forecast, so customers book a time when the boat will actually sail.

## The problem

* Prices are bargained on the riverbank, so tourists get overcharged.
* With no wind the boat can't sail, and customers only find out after paying.
* There is no way to check a captain's license, a boat's safety equipment or reviews.
* Booking for groups and occasions takes many phone calls.
* Captains have no online presence and sit idle on slow days.

## Target users

Tourists, Egyptian locals (couples, friends, families), student and company groups, and felucca captains.

## Features and owners

|#|Feature|Owner (full name — ID)|
|-|-|-|
|F1|Ride Search \& Wind-Based Slots|\[Malak Sakr — 19005116]|
|F2|Boat \& Captain Profiles|\[Ahmed Hany — 19004657]|
|F3|Booking \& Checkout|\[Mohamed Sherif — 19007729]|
|F4|Sunset \& Occasion Packages|\[Lujayne Baddour — 19005902]|
|F5|Group Booking \& Cost Split|\[Sama Hisham — 19004376]|
|F6|My Trips|\[Hafsa Amr — 19006324]|
|F7|Captain Dashboard|\[Roqaya Aboshawaly — 19003666]|
|F8|Reviews \& Ratings|\[Ahmed Attia — 19002221]|

## Deliverables

* **PD1:** concept, 16 user stories (2 per feature, 3 acceptance criteria each) and wireframes of the Home page and every feature page. See `PD1\_Felucca.pdf`.
* **Live API (PD3):** [Open-Meteo](https://open-meteo.com/) forecast API (free, no key), providing hourly wind speed and daily sunset times.

