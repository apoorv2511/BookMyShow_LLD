# BookMyShow_LLD
LLD Design for BookMyShow

Requirements

1. Customer/Client
    1. Should be able to view and select city.
    2. Should be able to view and select theatres in selected city.
    3. Should be able to view and select movie shows in selected theatre.
    4. Should be able to search movie by theatre or search theatre by movie.
    5. User should be able to select x number of vacant seats in selected theatre.
    6. User should be able to select add-ons once seats are selected (like popcorn, coke, etc.)
    7. User should be able to make payment through a list a various payment options.
    8. User should be able to redeem points through voucher/coupon.

2. Theatre System
    1. Should be able to perform add/update/delete any movie show.
    2. Should be able to add/modify/delete movie details.
    3. Should be able to add/modify/delete from theatre’s seating arrangement.
    4. Should be able to add discount codes.
    5. Should be able to provide functionality to confirm booking, once payment confirmation is received.
    6. Should be able to provide functionality to hold seats (for x minutes), once the seat is selected and until the payment is not made.


3. BookMyShow System
    1. Should be able to generate receipt and confirmation QR, once payment is confirmed.
    2. Should be able to provide receipt of confirmation on WhatsApp, mail, sms, and on the app.
    3. Notifications from recommendation system.
    4. Cron/Scheduler for Reconciliation and Settlement with theatre vendors of all the payments made throughout the day on BookMyShow.
