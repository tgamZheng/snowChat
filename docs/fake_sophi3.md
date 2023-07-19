**Table 3: SNOWCHAT.DEV.FAKE_SOPHI3** (Stores user web clickstream information)

This table contains information about web browsing events made by customers when they browse our website to read news and articles, including the timestamp, page name they visited, devices they use and region, etc.

- ACCOUNT_TYPE: VARCHAR(16777216) - What type of account that customer use, there are 3 different types "Anonymous","Subscribed" and "Registered"
- ACTIVE_TIME: Number (38,0) - How long does it take for customer to browse a single page in seconds
- APP_ID: VARCHAR(16777216) - Type of platform that customers access, there are two platforms: "website", "app" and "website-nojs"
- ARTICLE_BYLINE: VARCHAR(16777216) - Author who writes the article
- ARTICLE_COLOUR: VARCHAR(16777216) - The colour of the article
- COUNTRY: VARCHAR(16777216) - The country where the customer is located at
- DEVICE_BRAND: VARCHAR(16777216) - Device brand
- EVENT_DATE_EST: DATE - Date that cusomer access our website
- EVENT_NAME STRING: VARCHAR(16777216) - Event type such as "page_view", "ab_tests", "link_click"
- REGION: STRING - Region that customers come from
- SECTION: STRING - Category of the article such as "homepage","investing" and "realestate"
- TIMESTAMP_EST: TIMESTAMP format - Timestamp that customer access the website and read articles