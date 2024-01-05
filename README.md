# Real-Time-Bus-Tracker

This page will show the real time bus movement of route 1 bus between MIT and Harvard campus.
Real-time bus data gathered from the MBTA API(obtained from [MBTA's V3 API developer portal](https://api-v3.mbta.com/).
From this API response we will get latitude, longitude and directions details of moving buses informations.
These details are integrating into the Google Maps API and displays the live location of the buses on a map. 

## How to Run

The google map page with map pins of real time bus movement rendeds when page loads.
To get real time bus data need to add MBTA url with filtered route 1 and trip details.
For accessing Google Map in the page one should to add their own API key. There are two icons used to indicate the direction of buses.
Red one shows that bus is moving towards Harvard and blue one away from Harvard.

## Roadmap

I am planning to add button and event listners so that after clicking button only can view the map pins movement
I will changes the appearence and will make more user interactivne in future.

## Support

If you have any queries or suggestions please do not hesitate to contact me jishithamp@gmail.com.

## License

MIT License
