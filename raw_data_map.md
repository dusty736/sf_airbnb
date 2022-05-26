# Summary
This is a data map that has definitions for each of the variables contained in the raw data.

## Dataset: Calendar
| file path   |      Variable Name      |  Definition |
|----------|:-------------:|------:|
| data/raw/calendar.csv | listing_id  | Unique ID to identify a listing.  Maps to reviews.listing_id, listings.id. |
| data/raw/calendar.csv | date  | Date of a listing. |
| data/raw/calendar.csv | available  | "t" or "f" indicating whether the listing was available on a given date. |
| data/raw/calendar.csv | price  | Price of listing on a given night in american dollars. |
| data/raw/calendar.csv | adjusted_price  | Adjusted price of listing on a given night in american dollars. |
| data/raw/calendar.csv | minimum_nights  | Minimum nights available for a listing |
| data/raw/calendar.csv | maximum_nights  | Maximum nights available for a listing |

## Dataset: Reviews
| file path   |      Variable Name      |  Definition |
|----------|:-------------:|------:|
| data/raw/reviews.csv | listing_id  | Unique ID to identify a listing.  Maps to calendar.listing_id, listings.id. |
| data/raw/reviews.csv | id  | Unique ID to identify a review. |
| data/raw/reviews.csv | date  | Date of review. |
| data/raw/reviews.csv | reviewer_id  | Unique ID to identify a reviewer. |
| data/raw/reviews.csv | reviewer_name  | Unidentifiable name of reviewer. |
| data/raw/reviews.csv | comments  | Text field of review comment. |

## Dataset: Listings
| file path   |      Variable Name      |  Definition |
|----------|:-------------:|------:|
| data/raw/listings.csv | id  | Unique ID to identify a listing.  Maps to calendar.listing_id, reviews.listing_id. |
| data/raw/listings.csv | listing_url  | Listing URL. |
| data/raw/listings.csv | scrape_id  | Unique ID to identify the scrape. |
| data/raw/listings.csv | name  | Listing name. |
| data/raw/listings.csv | description  | Listing description. |
| data/raw/listings.csv | neighborhood_overview  | Description of neighborhood. |
| data/raw/listings.csv | picture_url  | URL to listing picture. |
| data/raw/listings.csv | host_id  | Unique ID to host. |
| data/raw/listings.csv | host_url  | URL to listing. |
| data/raw/listings.csv | host_name  | Unidentifiable first name of host. |
| data/raw/listings.csv | host_since  | Date host joined AirBnB. |
| data/raw/listings.csv | host_location  | Location city of host. |
| data/raw/listings.csv | host_about  | Description of host. |
| data/raw/listings.csv | host_response_time  | Response host time. |
| data/raw/listings.csv | host_response_rate  | Host response rate. |
| data/raw/listings.csv | host_acceptance_rate	  | Host acceptance rate. |
| data/raw/listings.csv | host_is_superhost  | "t" or "f" indicating superhost status. |
| data/raw/listings.csv | host_thumbnail_url  | Host thumbnail URL. |
| data/raw/listings.csv | host_picture_url  | Host picture URl. |
| data/raw/listings.csv | host_neighbourhood  | Neighborhood of host. |
| data/raw/listings.csv | host_listings_count  | Number of listings the host manages. |
| data/raw/listings.csv | host_total_listings_count  | Number of listings the host manages. |
| data/raw/listings.csv | host_verifications  | List of methods for host verification. |
| data/raw/listings.csv | host_has_profile_pic  | "t" or "f" for if a host has a profile picture. |
| data/raw/listings.csv | host_identity_verified  | "t" or "f" for if a host is verified. |
| data/raw/listings.csv | neighbourhood  | City name. |
| data/raw/listings.csv | neighbourhood_cleansed  | Neighborhood name in San Francisco. |
| data/raw/listings.csv | neighbourhood_group_cleansed  | Neighborhood group name. |
| data/raw/listings.csv | latitude  | Listing latitude. |
| data/raw/listings.csv | longitude  | Listing longitude. |
| data/raw/listings.csv | property_type  | Property type. |
| data/raw/listings.csv | room_type  | Roome type. |
| data/raw/listings.csv | accommodates  | Number of people the listing will accommodate. |
| data/raw/listings.csv | bathrooms  | Number of bathrooms. |
| data/raw/listings.csv | bathrooms_text  | Number of bathrooms text. |
| data/raw/listings.csv | bedrooms  | Number of bedrooms. |
| data/raw/listings.csv | beds  | Number of beds. |
| data/raw/listings.csv | amenities  | List of amenities in the listing. |
| data/raw/listings.csv | price  | Price of listing in American dollars. |
| data/raw/listings.csv | minimum_nights  | minimum number of night stay for the listing (calendar rules may be different) |
| data/raw/listings.csv | maximum_nights  | maximum number of night stay for the listing (calendar rules may be different) |
| data/raw/listings.csv | minimum_minimum_nights  | the smallest minimum_night value from the calender (looking 365 nights in the future) |
| data/raw/listings.csv | maximum_minimum_nights  | the largest minimum_night value from the calender (looking 365 nights in the future) |
| data/raw/listings.csv | minimum_maximum_nights  | the smallest maximum_night value from the calender (looking 365 nights in the future) |
| data/raw/listings.csv | maximum_maximum_nights  | the largest maximum_night value from the calender (looking 365 nights in the future) |
| data/raw/listings.csv | minimum_nights_avg_ntm  | the average minimum_night value from the calender (looking 365 nights in the future) |
| data/raw/listings.csv | maximum_nights_avg_ntm  | the average maximum_night value from the calender (looking 365 nights in the future) |
| data/raw/listings.csv | calendar_updated  | Calendar updated. |
| data/raw/listings.csv | has_availability  | Listing has availability. |
| data/raw/listings.csv | availability_30  | The availability of the listing 30 days in the future as determined by the calendar. |
| data/raw/listings.csv | availability_60  | The availability of the listing 60 days in the future as determined by the calendar. |
| data/raw/listings.csv | availability_90  | The availability of the listing 90 days in the future as determined by the calendar. |
| data/raw/listings.csv | availability_365  | The availability of the listing 120 days in the future as determined by the calendar. |
| data/raw/listings.csv | calendar_last_scraped  | Date calendar scraped. |
| data/raw/listings.csv | number_of_reviews  | Number of reviews for listing. |
| data/raw/listings.csv | number_of_reviews_ltm  | The number of reviews the listing has in the last 12 months. |
| data/raw/listings.csv | number_of_reviews_l30d  | The number of reviews the listing has in the last 30 days. |
| data/raw/listings.csv | first_review  | Date of first review. |
| data/raw/listings.csv | last_review  | Date of last review. |
| data/raw/listings.csv | review_scores_rating  | Average score rating out of 5. |
| data/raw/listings.csv | review_scores_accuracy  | Average score for accuracy out of 5. |
| data/raw/listings.csv | review_scores_cleanliness  | Average score for cleanliness out of 5. |
| data/raw/listings.csv | review_scores_checkin  | Average score for checkin out of 5. |
| data/raw/listings.csv | review_scores_communication  | Average score for communication out of 5. |
| data/raw/listings.csv | review_scores_location  | Average score for location out of 5. |
| data/raw/listings.csv | review_scores_value  | Average score for value out of 5. |
| data/raw/listings.csv | license  | Host license number. |
| data/raw/listings.csv | instant_bookable  | "t" or "f" for if property is instant bookable. |
| data/raw/listings.csv | calculated_host_listings_count  | The number of listings the host has in the current scrape, in the city/region geography. |
| data/raw/listings.csv | calculated_host_listings_count_entire_homes  | The number of Entire home/apt listings the host has in the current scrape, in the city/region geography |
| data/raw/listings.csv | calculated_host_listings_count_private_rooms  | The number of Private room listings the host has in the current scrape, in the city/region geography |
| data/raw/listings.csv | calculated_host_listings_count_shared_rooms  | The number of Shared room listings the host has in the current scrape, in the city/region geography |
| data/raw/listings.csv | reviews_per_month  | The number of reviews the listing has over the lifetime of the listing |


## Dataset: Neighborhood
| file path   |      Variable Name      |  Definition |
|----------|:-------------:|------:|
| data/raw/neighborhoods.csv | neighborhood_group  | Neighborhood group. |
| data/raw/neighborhoods.csv | neighborhood  | Neighborhood name. |
