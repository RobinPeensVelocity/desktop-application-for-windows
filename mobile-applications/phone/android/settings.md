# Settings

A user can access the "Settings" tab from the application’s "More" menu in order to manage "Defaults" and "Confirmations".

## Defaults

![](<../../../.gitbook/assets/4 (70).png>)

In "Defaults" settings section you can adjust the following:

* Order quantity – displays amount of lots for opening an order;
* Validity – allows specifying order validity by selecting among the following time frames: Day, GTC, IOC, GTD, FOK;
* Order type – allows to select one of the following orders: Market, Limit, Stop, Stop limit, Tr. Stop;
* Quantity in lots - if checked, quantity is displayed in lots, if unchecked – in units;
* Set SL/TP values in offset – if checked, the SL/TP prices are in offset, if unchecked they are in absolute values;
* Show offset in – allows to select one of the available modes for offset displaying: Ticks, Points;
* Use stop limit instead of stop – check to place stop limit orders instead of stop orders. When checked, \_\*\*\_it activates the "Limit offset, ticks" field.

## **Confirmations**

![](../../../.gitbook/assets/fdb0c8d1-933c-48fb-ad1a-c46d27c587d7.jpg)

"Confirmations" settings section allows to enable double-checking of the following actions by marking them as checked, after what the application will ask you to confirm these actions:

* Order sending;
* Order modifying;
* Order executing;
* Order cancelling;
* Position modifying;
* Position closing;
* Alert removing.

## Other

![](<../../../.gitbook/assets/2 (120).png>)

The **"**Other" settings section cannot be displayed in the application settings if the biometric authentication is not checked in the system settings of the device or it is blocked.

Biometric authentication enables a user to log in to the mobile application more securely by using the Fingerprint or FaceID features.

![](<../../../.gitbook/assets/4 (66).png>)

To apply Fingerprint in the application for subsequent logins, a user should put his finger on the sensor.

![](../../../.gitbook/assets/simulator-screen-shot-iphone-8-2020-09-08-at-16.00.37.png)

After this, the checkbox More -> Settings -> Other -> Biometric authentication becomes True.

A user should enter his password to confirm biometrics:

![](../../../.gitbook/assets/1617805462129.jpeg)

On subsequent calls of the Login screen form, if the Biometric authentication setting is checked in the application, then the following dialog box is automatically displayed:

![](<../../../.gitbook/assets/3 (96).png>)

The user authentication occurs after putting a finger on the sensor and successful fingerprint recognition.

In case the FaceID feature is available and activated on the user device, it can be used as an additional application login option instead of the Fingerprint:

![](../../../.gitbook/assets/feis.jpg)

To deactivate Biometric authentication, uncheck the corresponding setting and then tap the "OK" button on the undermentioned screen:

![](../../../.gitbook/assets/1617805462578.jpeg)

## Push notifications

VelocityTrader app provides the ability to receive push notifications on numerous events such as the daily loss limit warning, margin warning, receiving a new trading idea, etc. Upon receiving a push notification, the user can tap on it and thus open the application. Sending push notifications to the device is regulated by your broker, i.e. you cannot activate this function by yourself. If the user wants to disable receiving push notifications, he can do it in the settings of his device.

## Alerts

This section allows to configure the alerts, the following settings are available:

![](../../../.gitbook/assets/f626729e-1a6f-4c08-8def-712790d32e6d.jpg)

* Notification – combobox for selecting the type of notification after alert triggering, multiselect is available:
*
  * Email – an alert containing the text from the ‘Alert message’ field will be sent to the user by email;
  * Push notification – an alert containing the text from the ‘Alert message’ field will be sent to the user via push notification;
  * Pop-up – an alert containing the text from the ‘Alert message’ field will be sent to the user in pop-up message;
  * Sound – a musical alert will be played to the user in the client.
* Alert type – allows to set an alert type. Available options are: Default by symbol, Ask, Bid, Last, Change%, Volume;
* Condition – allows to set an alert condition. Available values are: >,<,>=,<=;
* Importance – allows to define the alert importance, the following options are available: High, Medium, Low;
* After execute – allows to select alert behavior after execution. Available options are ‘Stop’ - alert is not active but stored in the list of alerts, and ‘Remove’ - alert is removed after execution.
