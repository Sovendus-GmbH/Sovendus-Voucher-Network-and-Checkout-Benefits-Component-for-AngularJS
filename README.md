# Sovendus Voucher Network & Checkout Benefits Component for AngularJS

> [!WARNING]
> This component is built for the deprecated Angularjs, the component for Angular can be found [here](https://developer-hub.sovendus.com/Voucher-Network-Checkout-Benefits/Web-Integration/AngularJS-Component)

## Integrate into your AngularJS app
1. Download the Sovendus component from [here](https://raw.githubusercontent.com/Sovendus-GmbH/Sovendus-Voucher-Network-and-Checkout-Benefits-Component-for-AngularJS/main/sovendus-banner.component.js) and add it into your AngularJS project / app folder
2. In the component replace myAppModuleName with your AngularJS app name
3. Import the component in your AngularJS app:
    ```html
    <script src="path/to/sovendus-banner.component.js"></script>
    ```
2. You can then use the component like with the following example:
   
   [Click here for detailed information on the parameters and which ones are required.](https://developer-hub.sovendus.com/Voucher-Network-Checkout-Benefits/Parameter)
   
    ```html
    <sovendus-banner
        traffic_source_number="YOUR_TRAFFIC_SOURCE_NUMBER"
        traffic_medium_number="YOUR_TRAFFIC_MEDIUM_NUMBER"
        session_id="session-1321"
        timestamp="1707132442"
        order_id="order-1234"
        order_value="12.6"
        order_currency="EUR"
        used_coupon_code="coupon-code-from-order"
        consumer_salutation="Mrs."
        consumer_first_name="Test"
        consumer_last_name="Tester"
        consumer_email="test@123.de"
        consumer_street="Street"
        consumer_street_number="12"
        consumer_city="City"
        consumer_country="DE"
        consumer_zipcode="45646"
        consumer_year_of_birth="1991"
    />
    ```
