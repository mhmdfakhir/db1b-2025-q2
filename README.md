
## BACKGROUND
The data contained in the compressed file has been extracted from the DB1BMarket data table of the "Origin and Destination Survey" database from the TranStats data library. The time period is indicated in the name of the compressed file; for example, XXX_XXXXX_2001_1 contains data of the first quarter of the year 2001.
 
## RECORD LAYOUT

Below are fields in the order that they appear on the records:

**ItinID**	Itinerary ID

**MktID**	Market ID

**MktCoupons**	Number of Coupons in the Market

**Year**	Year

**Quarter**	Quarter (1-4)

**OriginAirportID**	Origin Airport, Airport ID. An identification number assigned by US DOT to identify a unique airport. Use this field for airport analysis across a range of years because an airport can change its airport code and airport codes can be reused.

**OriginAirportSeqID**	Origin Airport, Airport Sequence ID. An identification number assigned by US DOT to identify a unique airport at a given point of time. Airport attributes, such as airport name or coordinates, may change over time.

**OriginCityMarketID**	Origin Airport, City Market ID. City Market ID is an identification number assigned by US DOT to identify a city market. Use this field to consolidate airports serving the same city market.

**Origin**	Origin Airport Code

**OriginCountry**	Origin Airport, Country Code

**OriginStateFips**	Origin Airport, State FIPS Code

**OriginState**	Origin Airport, State Code

**OriginStateName**	Origin State Name

**OriginWac**	Origin Airport, World Area Code

**DestAirportID**	Destination Airport, Airport ID. An identification number assigned by US DOT to identify a unique airport. Use this field for airport analysis across 
a range of years because an airport can change its airport code and airport codes can be reused.

**DestAirportSeqID**	Destination Airport, Airport Sequence ID. An identification number assigned by US DOT to identify a unique airport at a given point of time. Airport attributes, such as airport name or coordinates, may change over time.

**DestCityMarketID**	Destination Airport, City Market ID. City Market ID is an identification number assigned by US DOT to identify a city market. Use this field to consolidate airports serving the same city market.

**Dest**	Destination Airport Code

**DestCountry**	Destination Airport, Country Code

**DestStateFips**	Destination Airport, State FIPS Code

**DestState**	Destination Airport, State Code

**DestStateName**	Destination State Name

**DestWac**	Destination Airport, World Area Code

**AirportGroup**	Airport Group

**WacGroup**	World Area Code Group

**TkCarrierChange**	Ticketing Carrier Change Indicator (1=Yes)

**TkCarrierGroup**	Ticketing Carrier Group

**OpCarrierChange**	Operating Carrier Change Indicator (1=Yes)

**OpCarrierGroup**	Operating Carrier Group

**RPCarrier**	Reporting Carrier Code

**TkCarrier**	Ticketing Carrier Code for On-line Itineraries (otherwise equal to 99)

**OpCarrier**	Operating Carrier Code for On-line Itineraries (otherwise equals to 99)

**BulkFare**	Bulk Fare Indicator (1=Yes)

**Passengers**	Number of Passengers

**MktFare**	Market Fare (ItinYield*MktMilesFlown)

**MktDistance**	Market Distance (Including Ground Transport)

**MktDistanceGroup**	Distance Group, in 500 Mile Intervals

**MktMilesFlown**	Market Miles Flown (Track Miles)

**NonStopMiles**	Non-Stop Market Miles (Using Radian Measure)

**ItinGeoType**	Itinerary Geography Type

**MktGeoType**	Market Geography Type