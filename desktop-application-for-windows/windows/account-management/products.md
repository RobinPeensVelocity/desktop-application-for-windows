# Products

The Products panel lists all products currently available to the User, products the User has subscribed to, and requests that he has submitted. In order to open the panel select it from the Account drop-down list that is located in the main menu of the terminal. The panel contains three tabs:

* Active – this tab contains a list of Products to which the user has already subscribed i.e. those subscription requests which are confirmed by the Admin or automatically;
* Catalogue – contains a list of Products that are available to the User for subscription;
* Requests – contains subscribe/unsubscribe requests sent by the user.

## **Catalogue tab**

![](<../../../.gitbook/assets/4 (11) (2).jpg>)

This tab displays cards of products available to the User for subscription. Please note that Product cards are grouped into specific categories, which are assigned by the Admin in the Product settings. Each Product card contains the name of the Product, its logo, price, and the ‘Subscribe’ button. In case the logo was not received from the server,![](<../../../.gitbook/assets/image (111).png>)will be displayed instead. In the upper right corner of each Product card there is the ![](https://lh4.googleusercontent.com/wEkGlYW5qSeJGHTfyYQ96E205vVVvX6eswwVSDiOvyIqiCWYDMiZO2C1vohXpdkVT2EocJhTeZqUkXKP588MgCx4qBNH7unwz8yPzCq6tFHxD6setKlOMPpkztGfxpuJlrM5ko-t) button, upon hovering on which the information about the Product is displayed:

![](<../../../.gitbook/assets/image (85).png>)

Subscription to the Product of interest is carried out by clicking the "Subscribe" button. If the Product already has an active request awaiting processing by the admin, the "Processing..." button is displayed instead of the "Subscribe" button.

{% hint style="info" %}
If the User does not have enough funds to pay the fee, or if there are no available User accounts to be charged for using the Product, then the corresponding reject will be displayed. This is only valid in the case of automatic request confirmation/charging.
{% endhint %}

The reject comes in the form of deal ticket and has the following view:

![](<../../../.gitbook/assets/image (101).png>)

There are two subscription options - if the User does not need to sign additional documents or if there is a need to sign them.

If the documents are not required to be signed, then the subscription request will be created immediately after clicking the appropriate button. This request will await verification by the admin and after its confirming the User will be subscribed to the Product.

In case it is required to sign documents in order to subscribe to the Product, then an additional screen that allows to take the necessary actions will be shown to the User:

![](<../../../.gitbook/assets/new5 (1).jpg>)

This screen contains the following elements:

* The name of the document, which is displayed in the upper part of the screen;
* The content of the document displayed in the main part of the screen;
* When acquaintance with the documents is finished, the ‘Done’ button will become active;
* Progress bar, which is utilized to indicate the progress made when signing documents.
* In case the required fields are missing on the current page, the system will display a corresponding message and will not allow the User to move to the next page.

## **Active tab**

![](<../../../.gitbook/assets/3 (17) (2).jpg>)

This tab looks the same as the Catalogue tab, with the only difference that it displays Products that the User has already subscribed to. Each Product сard in this tab has a ‘Subscribed’ button, but when hovering over, it changes the appearance to ‘Unsubscribe’ and respectively serves to unsubscribe from the required Product. After clicking the button, the User will be asked to confirm his unsubscription which looks as follows:

![](<../../../.gitbook/assets/screenshot\_2 (41).jpg>)

{% hint style="warning" %}
Please note that after confirmation, the User will be immediately unsubscribed, without waiting for the end of the period for which the fee was charged.
{% endhint %}

If the Product already has an active request awaiting processing by the admin, the "Processing..." button is displayed instead of the "Subscribed" button.

Depending on the state of the Market data subscriber status setting at the user level, the product card displays the Pro price or Non-pro price respectively. If this setting is disabled, then the product is free for the user, so the inscription FREE is displayed on the product card. If Market data subscriber status is not defined, then both prices separated by a slash are displayed at once on the product card, the display format is \<non-pro price> / \<pro price> \<currency>.

## **Requests tab**

This tab displays all requests sent by the user for subscribing/unsubscribing to the Products for the selected period:

![](<../../../.gitbook/assets/new6 (3) (2).jpg>)

The Requests tab contains the following elements:

* Period selector located in the upper part of the tab contains the Daily (set by default) and Range options, the latter enables the calendar for selecting the required time range for Product requests displaying;
* Product name column – displays the Product name;
* Request type column – displays the request type. For the User convenience Subscription requests are colored blue and Unsubscription requests are colored white;
* Request status column – displays the status of each request, statuses are also appear in different colors, namely Processing (colored white), Approved (colored green), Rejected (colored red), Canceled (colored gray);
* Date/Time column – contains the date and time when the request status was changed;
* Cancel buttons – buttons for canceling the sent request, available only for the ‘Processing’ status, provided that the request has not yet been processed by the admin, otherwise the button is not displayed.

Pressing the ‘Cancel’ button will bring up the confirmation screen of the following look:

![](<../../../.gitbook/assets/image (84).png>)
