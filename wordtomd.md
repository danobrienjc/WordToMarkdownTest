![Shape1](RackMultipart20220506-1-bmkzw1_html_f12af8036636a541.gif) ![](RackMultipart20220506-1-bmkzw1_html_971af755b7b03aaa.png)

![Shape2](RackMultipart20220506-1-bmkzw1_html_b993623f926cc332.gif)

# 2022-04-13 - DK

# **Contents**

[**AC2000 Overview and Components** 6](#_Toc77778499)

[ Central Database Computer (CDC) 6](#_Toc77778500)

[ RTC Server (Real Time Computer) 6](#_Toc77778501)

[ CDC/RTC Combination Server 6](#_Toc77778502)

[ Transactions 6](#_Toc77778503)

[ Alarms 6](#_Toc77778504)

[The AC2000 API 8](#_Toc77778505)

[**1.**** Installation** 8](#_Toc77778506)

[**2.**** API Overview** 9](#_Toc77778507)

[**3.**** Using the REST interface to access the API** 10](#_Toc77778508)

[3.1. Request Messages 10](#_Toc77778509)

[3.2. Response Messages 10](#_Toc77778510)

[3.3. Status Codes 10](#_Toc77778511)

[3.4. Authorisation details 11](#_Toc77778512)

[3.5. Action Directives 11](#_Toc77778513)

[3.6. Error Responses 15](#_Toc77778514)

[**4.**** Using an ODBC connection to access the API** 16](#_Toc77778515)

[**5.**** Company functions** 17](#_Toc77778516)

[5.1. Add a Company record 17](#_Toc77778517)

[5.2. Update a Company record 19](#_Toc77778518)

[**6.**** Personnel Functions** 21](#_Toc77778519)

[6.1. Add a Personnel record 21](#_Toc77778520)

[6.2. Change a Personnel record 23](#_Toc77778521)

[6.3. Delete a Personnel record 25](#_Toc77778522)

[6.4. Add a Personnel Company record 26](#_Toc77778523)

[6.5. Remove a Personnel Company record 27](#_Toc77778524)

[6.6. Set or Change Personnel spare fields 28](#_Toc77778525)

[6.7. Clear Personnel spare fields 29](#_Toc77778526)

[6.8. Set or Change Personnel dynamic fields 30](#_Toc77778527)

[**7.**** ID Card Functions** 31](#_Toc77778528)

[7.1. Add an ID Card record 31](#_Toc77778529)

[7.2. Change an ID Card 33](#_Toc77778530)

[7.3. Validate an ID Card 35](#_Toc77778531)

[7.4. Return an ID Card 36](#_Toc77778532)

[7.5. Delete an ID Card 37](#_Toc77778533)

[7.6. Set or Change ID Card spare fields 38](#_Toc77778534)

[7.7. Clear ID Card spare fields 39](#_Toc77778535)

[**8.**** Access Level functions** 40](#_Toc77778536)

[8.1. Assign an Extra Access Level to a Cardholder 40](#_Toc77778537)

[8.2. Remove an Extra Access Level from an Cardholder 41](#_Toc77778538)

[8.3. Assign Temporary Access to an Cardholder 42](#_Toc77778539)

[8.4. Remove Temporary Access from an Cardholder 43](#_Toc77778540)

[8.5. Add Extra Access to a group of Cardholders 44](#_Toc77778541)

[8.6. Remove Extra Access from a group of Cardholders 45](#_Toc77778542)

[8.7. Determine if Extra Access is enabled for a group of Cardholders 46](#_Toc77778543)

[8.8. Add a new Access Level Description 47](#_Toc77778544)

[8.9. Change the Description of an Access Level 48](#_Toc77778545)

[**9.**** Visitor functions** 49](#_Toc77778546)

[9.1. Add a Visitor record 49](#_Toc77778547)

[9.2. Change a Visitor record 51](#_Toc77778548)

[9.3. Delete a Visitor record 53](#_Toc77778549)

[9.4. Clear Visitor spare fields 54](#_Toc77778550)

[9.5. Set or Change Visitor spare fields 55](#_Toc77778551)

[9.6. Set or Change Visitor dynamic fields 56](#_Toc77778552)

[9.7. Add a Visit record 57](#_Toc77778553)

[9.8. Change a Visit record 58](#_Toc77778554)

[9.9. Delete a Visit record 59](#_Toc77778555)

[9.10. Validate a Visit ID Card 60](#_Toc77778556)

[9.11. Return a Visit ID Card 61](#_Toc77778557)

[**10.**** Vehicle functions** 62](#_Toc77778558)

[10.1. Add a new Vehicle Make (Manufacturer) record 62](#_Toc77778559)

[10.2. Change a Vehicle Make (Manufacturer) record 63](#_Toc77778560)

[10.3. Delete a Vehicle Make (Manufacturer) record 64](#_Toc77778561)

[10.4. Add a new Vehicle Model record 65](#_Toc77778562)

[10.5. Change a Vehicle Model record 66](#_Toc77778563)

[10.6. Delete a Vehicle Model record 67](#_Toc77778564)

[10.7. Add a new Vehicle record 68](#_Toc77778565)

[10.8. Change a Vehicle record 71](#_Toc77778566)

[10.9. Set or Change Vehicle spare fields 74](#_Toc77778567)

[10.10. Clear Vehicle spare fields 76](#_Toc77778568)

[10.11. Set or Change Vehicle dynamic fields 77](#_Toc77778569)

[10.12. Delete a Vehicle record 78](#_Toc77778570)

[10.13. Validate a Vehicle ID Card 79](#_Toc77778571)

[10.14. Return a Vehicle ID Card 80](#_Toc77778572)

[10.15. Add an Approved Driver to a Vehicle 81](#_Toc77778573)

[10.16. Remove an Approved Driver from a Vehicle 82](#_Toc77778574)

[10.17. Find a Vehicle Make (Manufacturer) ID 83](#_Toc77778575)

[10.18. Find a Vehicle Model ID 84](#_Toc77778576)

[10.19. Find a Vehicle ID 85](#_Toc77778577)

[10.20. Find a Vehicle Registration 86](#_Toc77778578)

[10.21. Find a Vehicle Fuel ID 87](#_Toc77778579)

[**11.**** Image and Signature functions** 88](#_Toc77778580)

[11.1. Attach a photograph to a Personnel or Visitor record 88](#_Toc77778581)

[11.2. Attach a signature to a Personnel or Visitor Record 89](#_Toc77778582)

[**12.**** Threat Level functions** 90](#_Toc77778583)

[12.1. Set the System Threat Level 90](#_Toc77778584)

[12.2. Set the Threat Level for a Cardholder or Visitor 91](#_Toc77778585)

[**13.**** Device and Zone functions** 92](#_Toc77778586)

[13.1. Send an Open or Close broadcast request to a single device 93](#_Toc77778587)

[13.2. Send a Broadcast to a specific output on a single device 94](#_Toc77778588)

[13.3. Send an Open or Close broadcast request to multiple devices 95](#_Toc77778589)

[13.4. Wait for a multiple device broadcast request to complete 96](#_Toc77778590)

[13.5. Lock down Devices in a Lockdown Zone 97](#_Toc77778591)

[13.6. Unlock Devices in a Lockdown Zone 98](#_Toc77778592)

[13.7. Enable or Disable the keypad on Series 700E devices 99](#_Toc77778593)

[**14.**** Alarm functions** 100](#_Toc77778594)

[14.1. Acknowledge an alarm 100](#_Toc77778595)

[14.2. Cancel an alarm 101](#_Toc77778596)

[**15.**** Views and Read functions** 102](#_Toc77778597)

[15.1. Personnel and Card Status 102](#_Toc77778598)

[15.2. Cardholder Images 103](#_Toc77778599)

[15.3. Base64 Cardholder Images 104](#_Toc77778600)

[15.4. ID Cards 105](#_Toc77778601)

[15.5. Get Latest Card Swipe 106](#_Toc77778602)

[15.6. Get Total Card Swipes 107](#_Toc77778603)

[15.7. Card Swipes (All) 108](#_Toc77778604)

[15.8. Personnel Card Swipes 109](#_Toc77778605)

[15.9. Visitor Card Swipes 110](#_Toc77778606)

[15.10. Vehicle Card Swipes 111](#_Toc77778607)

[15.11. Access Levels 112](#_Toc77778608)

[15.12. RTC Controllers 113](#_Toc77778609)

[15.13. Alarm Types 114](#_Toc77778610)

[15.14. Devices 115](#_Toc77778611)

[15.15. Device Input Alarms 116](#_Toc77778612)

[15.16. Get Latest Alarm 117](#_Toc77778613)

[15.17. Get Total Active Alarms 118](#_Toc77778614)

[15.18. Active Alarms 119](#_Toc77778615)

[15.19. Cleared Alarms 120](#_Toc77778616)

[15.20. Get Total Alarms 121](#_Toc77778617)

[15.21. Broadcast Zones 122](#_Toc77778618)

[15.22. Broadcast Zone Devices 123](#_Toc77778619)

[15.23. Lockdown Zones 124](#_Toc77778620)

[15.24. Lockdown Zone Devices 125](#_Toc77778621)

[15.25. Victor Integration Information 126](#_Toc77778622)

[15.26. Emerald Reader responses 127](#_Toc77778623)

[15.27. Vehicle details 128](#_Toc77778624)

[15.28. Visitor details 130](#_Toc77778625)

[15.29. Device Outputs 131](#_Toc77778626)

[15.30. Swipe Outcomes 132](#_Toc77778627)

[15.31. Company details 133](#_Toc77778628)

[15.32. Timezone details 134](#_Toc77778629)

[15.33. GTZ Timezone details 135](#_Toc77778630)

[15.34. Card Type details 136](#_Toc77778631)

[15.35. Card Format details 137](#_Toc77778632)

[15.36. Device Output State details 138](#_Toc77778633)

[15.37. Partition details 139](#_Toc77778634)

[15.38. Manager details 140](#_Toc77778635)

[15.39. Personnel Access 141](#_Toc77778636)

[15.40. Visitor Access 142](#_Toc77778637)

[15.41. Access Level Devices 143](#_Toc77778638)

[15.42. Card Format Access Levels 144](#_Toc77778639)

[15.43. Card Type Formats 145](#_Toc77778640)

[15.44. Get Person ID from Payroll number 146](#_Toc77778641)

[**16.**** Enterprise Constraints** 147](#_Toc77778642)

[**17.**** Pseudocode Examples** 148](#_Toc77778643)

[17.1. Add a Cardholder and an ID card 149](#_Toc77778644)

[17.2. Cancel an ID card and issue a replacement 150](#_Toc77778645)

[17.3. Assign extra access to individuals and groups. 151](#_Toc77778646)

[17.4. Monitor alarms 152](#_Toc77778647)

[17.5. Monitor transactions 153](#_Toc77778648)

[17.6. Populate and broadcast devices and zones 154](#_Toc77778649)

[17.7. Acknowledge and cancel alarms 155](#_Toc77778650)

[**18.**** REST message examples** 156](#_Toc77778651)

[18.1. Query Request 156](#_Toc77778652)

[18.2. Query Response 156](#_Toc77778653)

[18.3. Fetch Request 156](#_Toc77778654)

[18.4. Fetch Response 157](#_Toc77778655)

[18.5. Visitor examples 158](#_Toc77778656)

[18.6. Example code in C with libcurl 161](#_Toc77778657)

# **AC2000 Overview and Components**

-
## Central Database Computer (CDC)

The Central Database Computer (CDC server) is one of the important components of the AC2000 client-server system architecture. The CDC serves each client workstation and reader controller. The CDC runs a Linux operating system; it processes and stores all the alarms, transactions, and other data occurring on the system.

-
## RTC Server (Real Time Computer)

The AC2000 RTC (Real-Time Computer) is a controller which can support up to 256 Ethernet-based CEM readers and devices. A CDC can support a maximum of 256 RTCs, therefore each CDC can support up to 65536 devices. The RTC is used with CEM Ethernet devices such as the S610e reader, S610f reader, S3020 portable reader range, all the eDCM 300 series (Ethernet door control modules), and the EIOC (Ethernet input/output controller). The RTC can also support serial devices when they are connected via an Ethernet Control Module (ECM).

An RTC can operate independently of the CDC if communications between them fail temporarily.

-
## CDC/RTC Combination Server

If the access control system (ACS) has less than 256 readers, the RTC software can be installed on the CDC server. If an ACS has more than 256 master readers/devices, the RTC software is installed on separate PCs/servers to handle system capacity.

_Key Features_

- An RTC controls up to 256 master card readers and devices. A single CDC server can use 256 RTCs to support up to 65,536 master card readers and doors.
- An RTC has a complete offline database offering an extra layer of redundancy to the AC2000 system.
- An RTC distributes database changes to connected Serial and Ethernet readers and devices.

_Please refer to the Server Installation Guide for further details about CDCs and RTCs._

-
## Transactions

Each time a card is used at a reader, a card swipe transaction is sent to the CDC from the RTC

Certain transactions can also result in alarms, e.g. when a card that has been marked as lost or stolen is used at a reader, a lost/stolen alarm is generated as well as the card swipe transaction.

-
## Alarms

These can be generated from several sources

1. Device alarms

These alarms are generated based on the results of user interaction at the device such as swiping a stolen card or entering the wrong pin (e.g. &quot;Lost/stolen card&quot;, &quot;PIN alarm&quot;, &quot;Duress&quot;) or as a result of error conditions such as device tamper or network loss (e.g. &quot;Tamper&quot;, &quot;Went Offline&quot;, &quot;Battery Low&quot;).

1. External Input Alarms

External sensors can be connected to a reader input and alarms can be generated when these inputs change state (e.g. &quot;break glass&quot;, &quot;Lock not engaged&quot;, &quot;Door forced&quot;, &quot;Power fail&quot;).

1. CDC Alarms

These are alarms which are the result of failures which directly affect the CDC, (e.g. &quot;Backup failure&quot;, &quot;System failed over&quot;). There is also a &quot;CDC went offline&quot; but as the name suggests the AC2000 system is not able to send this alarm to a 3rd party as the CDC is off-line, therefore 3rd party integrators should monitor their connection to the CDC and generate/display this alarm when the connection to the CDC is lost.

1. RTC Alarms

These are alarms which are the result of failures which directly affect the RTC, (e.g. &quot;RTC tamper&quot;, &quot;RTC went offline&quot;).

_It is important to note that alarms are not always the result of error conditions but can also be generated by recovery conditions e.g. &quot;Power restored&quot;, &quot;Lock engaged&quot;, &quot;Came online&quot;. These recovery conditions are often used to cancel initial alarms e.g. &quot;Power fail&quot;, &quot; __Lock not engaged&quot;, &quot;__ Went offline&quot;._

# The AC2000 API

1.
## **Installation**

Before using the AC2000 API it must first be licenced and enabled.

To activate the licence, from **AC2000 WEB** , clickSystem, click **AC2000 Setup** , and then click **Licensing****.**

Enter the API licence code in the fields provided and click **Add**.

![](RackMultipart20220506-1-bmkzw1_html_39618b1656f7d9fe.png)

To enable API:

1. Open an SSH terminal emulator connection, such as PuTTY, connect to the CDC.
2. Login as user: root
3. Type &#39;I&#39; at the prompt and press Return to display the Integrations menu.

![](RackMultipart20220506-1-bmkzw1_html_478f5fcf0735c4b2.gif)

**Figure 2:** Integrations menu in terminal emulator

1. Type the option number corresponding with API and press Return (for example, the number is 25 in Figure 2 above).
2. Press Return when prompted after the enabling script has run, to return to the integrations menu.
3. Type x and press Return to exit integrations menu.
4. Type L and press Return to log out of terminal emulator session.

1.
## **API Overview**

The A2000 API is implemented as a range of functions and views on the CDC.

There are a number of functions available to allow third-party integrators to create and maintain personnel and ID cards, and to dictate access to secured areas under the control of an AC2000 system.

There are a range of other functions available which can be used to monitor, acknowledge and cancel alarms, to retrieve information on card swipes and alarms and to administer visitor and vehicle access.

Please refer to the full API function definitions described in later sections for further details.

Before using the API it is recommended that a dedicated account is created solely for API use. This can be done via the &#39;User Options&#39; application from a connected AC2000 Desktop client. The account should have no applications assigned as it will not need to interface with a user desktop.

The API functions can be called and the views interrogated by issuing requests using either REST messages or by using a pre-established ODBC connection. Note however that the ability to use ODBC connections will be removed in a future software release so it is recommended that REST requests and responses are used to avoid redevelopment.

API functions return a negative value to indicate a failure of some kind. Positive return codes indicate success or are a calculated result e.g. the id of a newly created record.

Functions can return an error code of -999 if the API license has not been activated.

Date values are specified using Year-Month-Day (&#39;YYYY-MM-DD&#39;) format.

DateTime values are specified using &#39;Year-Month-Day Hour:Min:Sec&#39; (&#39;YYYY-MM-DD HH:mm:ss&#39;) format.

Some function parameters are mandatory, the others can be NULL.

API views return record sets appropriate to the request.

See [Using the REST interface to access the API](#Using_The_REST_Interface) section for REST request and response details.

See [Using an ODBC connection to access the API](#Using_The_ODBC_Interface) section for further odbc information .

**Certain restrictions apply when using API functions and views in an Enterprise environment. Please refer to** : [Enterprise Constraints](#Enterprise_constraints) **for further details**.

1.
## **Using the REST interface to access the API**

Interaction using the Rest interface is via standard HTTPS request and response messages.

Requests and response are stateless so each request message sent must include the necessary authorisation credentials.

Messages are sent to the address &#39;https://\&lt;a2000\_host\&gt;/api&#39; (where \&lt;a2000\_host\&gt; is the hostname or IP address of the A2000 CDC Server).

  1.
### Request Messages

Only HTTP &#39;POST&#39; requests are acceptable.

Request data must be encapsulated within an &#39;apirequest&#39; element and must include the authentication details, an action directive (see the [Action Directives](#_Action_Directives) section for further details) and any additional data required to complete the request.

The message data must be in JSON format.

  1.
### Response Messages

Response messages are encapsulated within an &#39;apiresponse&#39; element and include a HTTP status code (see the [Status Codes](#Rest_status_codes) section below for further details) and any other data returned by the API.

HTTP status codes are returned both in the HTTP headers and also the response message body.

Response data will be in JSON format.

  1.
### Status Codes

Possible HTTP status responses are as follows:-

200(_Success_) - included in the payload is the result of the API call (note that this might itself be a procedure error response indicating that the call succeeded but the operation failed (e.g. message data received is valid but doesn&#39;t conform to an acceptable range within an api function).

400(_Bad Request_) - request data cannot be interpreted or the API call has failed.

403 (_Access Denied_) - the authentication details are invalid or missing.

404 (_Not Found_) - the procedure or view doesn&#39;t exist.

405(_Method Not Allowed_) - only HTTP &#39;POST&#39; requests are acceptable.

406 (_Not Acceptable_) - the request data cannot be interpreted as valid JSON or it contains errors which have caused data parsing to fail.

  1.
### Authorisation details

Request messages must include the necessary authorisation credentials. These values should be contained within an &#39;auth&#39; section.

The &#39;auth&#39; section can optionally include a &#39;licence\_num&#39; tag which is used for licensing purposes. If the tag is omitted, it is assumed that a standard API license is present and internal licensing validation will check that the license exists. Other values can be provided which are issued by CEM and are integration-specific. If a licence\_num value is provided, license validation will check for the present of that license type instead.

Note: The &quot;licence\_num&quot; tag was previously named &quot;ecld\_type&quot;, either can be used.

_Example &#39;auth&#39; segment (formatted for readability)_

{

&quot;apirequest&quot;: {

&quot;auth&quot;: {

&quot;username&quot;: &quot;api\_user&quot;,

&quot;password&quot;: &quot;SuperSecret1=&quot;,

&quot;licence\_num&quot;: &quot;1234&quot;

},

... request specific values ...

}

}

  1.
### Action Directives

The following actions dictate what operation should be taken by the API. A REST request must contain one of these directives.

    1.
#### exec

This is used to execute an API procedure. The procedure must exist in the API. The data needed for the procedure call must be provided as a list of values, where the value name equates to the procedure field name. The values must adhere to the formats described in the [API Overview](#API_Overview) section.

_Example &#39;exec&#39; requests and responses (formatted for readability)_

_Request_

{

&quot;apirequest&quot;: {

&quot;auth&quot;: {

&quot;username&quot;: &quot;api\_user&quot;,

&quot;password&quot;: &quot; SuperSecret1=&quot;

},

&quot;action&quot;: &quot;exec&quot;,

&quot;procedure&quot;: &quot;api\_idc\_val&quot;,

&quot;values&quot;: {

&quot;id\_cards\_ser&quot;: &quot;1234&quot;,

&quot;hotstamp\_num&quot;: &quot;10001&quot;,

&quot;card\_num&quot;: &quot;0FC57A0C&quot;

}

}

}

_Response_

{

&quot;apiresponse&quot;: {

&quot;status\_code&quot;: 200,

&quot;status\_text&quot;: &quot;Success&quot;,

&quot;result&quot;: &quot;-1&quot;

}

}

See the [REST API message examples](#Rest_message_examples) for further requests and responses

    1.
#### fetch

This is used to read records from an API view. A SQL command is needed as part of the request but the following restrictions and considerations should be observed:-

- Only API Views can be read or joined to, no other database tables will be available.
- The SQL command must start with &#39;SELECT&#39;.
- Responses are atomic since REST interfaces do not maintain state information. In cases where a large number of records are to be returned, the complete result will be contained within a single response message. This can have a negative impact on response time and network traffic and may also affect the CDC server itself.

If necessary, splitting up a large response can be handled at the client end by at least one of the following ways

1. Only request the subset of records actually required by fine-tuning the sql statement
2. Issue a series of requests where each is tailored to fetch a smaller subset – one way is to use the &#39;offset&#39; and &#39;limit&#39; qualifiers within the sql statement

e.g. to fetch api\_person records in batches of 5000 using a series of requests

&quot;command&quot;: &quot;select \* from api\_person order by 1 offset 0 limit 5000&quot;

...

&quot;command&quot;: &quot;select \* from api\_person order by 1 offset 5000 limit 5000&quot;

...

&quot;command&quot;: &quot;select \* from api\_person order by 1 offset 10000 limit 5000&quot;

...

etc.

_Example &#39;fetch&#39; requests and responses_

_Request_

{

&quot;apirequest&quot;: {

&quot;auth&quot;: {

&quot;username&quot;: &quot;api\_user&quot;,

&quot;password&quot;: &quot;SuperSecret1=&quot;

},

&quot;action&quot;: &quot;fetch&quot;,

&quot;command&quot;: &quot;select \* from api\_device limit 2&quot;

}

}

_Response_

{

&quot;apiresponse&quot;: {

&quot;status\_code&quot;: 200,

&quot;status\_text&quot;: &quot;Success&quot;,

&quot;result&quot;: [

{

&quot;item&quot;: {

&quot;device\_addr&quot;: &quot;00000&quot;,

&quot;device\_description&quot;: &quot;reader00&quot;,

&quot;readhead\_num&quot;: &quot;1&quot;,

&quot;device\_type\_num&quot;: &quot;820&quot;,

&quot;device\_type\_name&quot;: &quot;700S&quot;,

&quot;site\_num&quot;: &quot;1&quot;

}

},

{

&quot;item&quot;: {

&quot;device\_addr&quot;: &quot;00100&quot;,

&quot;device\_description&quot;: &quot;liftcontroller00&quot;,

&quot;readhead\_num&quot;: &quot;1&quot;,

&quot;device\_type\_num&quot;: &quot;102&quot;,

&quot;device\_type\_name&quot;: &quot;Lift DCM&quot;,

&quot;site\_num&quot;: &quot;1&quot;

}

}

]

}

}

See the [REST API message examples](#Rest_message_examples) for further requests and responses

    1.
#### query

This can be used to fetch information about an API procedure or view. The result can be used as a way to determine the parameter names and data types required for a procedure call or the names and types of columns returned by a view.

Note that some procedures may return more than one result as they may be overloaded e.g. identical procedure names with different parameter types.

Additionally, one of the values _&#39;procedures&#39;_, &#39;_views_&#39; or &#39;_all_&#39; can be used instead of a procedure or view name – the returned results will contain details of all procedures, views or both respectively.

_Example &#39;query&#39; requests and responses_

_Request_

{

&quot;apirequest&quot;: {

&quot;auth&quot;: {

&quot;username&quot;: &quot;api\_user&quot;,

&quot;password&quot;: &quot;SuperSecret1=&quot;

},

&quot;action&quot;: &quot;query&quot;,

&quot;item&quot;: &quot;api\_alarm&quot;

}

}

_Response_

{

&quot;apiresponse&quot;: {

&quot;status\_code&quot;: 200,

&quot;status\_text&quot;: &quot;Success&quot;,

&quot;result&quot;: [

{

&quot;item&quot;: {

&quot;name&quot;: &quot;api\_alarm&quot;,

&quot;type&quot;: &quot;view&quot;,

&quot;returns&quot;: &quot;recordset&quot;,

&quot;columns&quot;: [

{

&quot;column&quot;: {

&quot;name&quot;: &quot;alarm\_type\_num&quot;,

&quot;type&quot;: &quot;integer&quot;

}

},

{

&quot;column&quot;: {

&quot;name&quot;: &quot;alarm\_description&quot;,

&quot;type&quot;: &quot;char(20)&quot;

}

},

{

&quot;column&quot;: {

&quot;name&quot;: &quot;auto\_or\_manual\_can&quot;,

&quot;type&quot;: &quot;char(80)&quot;

}

},

{

&quot;column&quot;: {

&quot;name&quot;: &quot;priority&quot;,

&quot;type&quot;: &quot;integer&quot;

}

}

]

}

}

]

}

}

See the [REST API message examples](#Rest_message_examples) for further requests and responses

  1.
### Error Responses

The following are examples of error responses which might be returned

_Response to bad credentials_

{

&quot;apiresponse&quot;: {

&quot;status\_code&quot;: 403,

&quot;status\_text&quot;: &quot;Invalid Credentials&quot;,

&quot;result&quot;: &quot;Access Denied&quot;

}

}

_Response to unknown procedure or view name (query,exec)_

{

&quot;apiresponse&quot;: {

&quot;status\_code&quot;: 404,

&quot;status\_text&quot;: &quot;Not Found&quot;,

&quot;result&quot;: &quot;&quot;

}

}

_Response to a &#39;fetch&#39; action containing an invalid SQL command_

_(command= &quot;update api\_device set device\_addr=&#39;12345&#39;&quot;)_

{

&quot;apiresponse&quot;: {

&quot;status\_code&quot;: 400,

&quot;status\_text&quot;: &quot;Bad Request&quot;,

&quot;result&quot;: &quot;&quot;,

&quot;errors&quot;: &quot;Invalid: &#39;UPDATE api\_device&#39;&quot;

}

}

1.
## **Using an ODBC connection to access the API**

Interaction via an ODBC connection will require the installation of a suitable Postgresql ODBC driver. This can be downloaded and installed separately e.g. from the [Postgresql Download Site](https://www.postgresql.org/download/).

An ODBC connection must be established to the &#39;a2000cdc&#39; database on the A2000 CDC Server.

When the connection has been made the API functions can be called using standard SQL commands e.g.

_select api\_function( value1, value2, … valueN );_

Character, Date and DateTime values supplied as parameters to API functions must be enclosed in single quotes (&#39;). If a single quote must be stored within a character field, 2 successive single quotes can be used e.g. _&#39;12 O&#39;&#39;clock&#39;_.

Integer values can be supplied with or without quotes

Other values must adhere to the formats described in the [API Overview](#API_Overview) section.

API views can be interrogated using standard SQL statements e.g.

_select \* from api\_view where val1=val2 order by column;_

An API license must be present before API functions will execute or views return any useful results. If a standard license has been installed it will be validated automatically. If a different, integration-specific license type is installed instead, the integrator must specific the license type in use (this only needs to be done once, typically after the connection is established and before any further api functions or views are used).

The **api\_set\_con\_type** function can be used to set the license type.

_api\_set\_con\_type( type );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| type | integer | The API license type in use |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| 0 | Invalid license type specified or license not present |
| \&gt;0 | Success, The license type applied |

For example to set the API license type in use to 1234:

_select api\_alm\_ack(1234);_

The ability to use ODBC connections will be removed in a future software release so it is recommended that REST requests and responses are used to interact with the API.

1.
## **Company functions**

  1.
### Add a Company record

The **api\_cmp\_add** function can be used to create a new Company record.

_api\_cmp\_add( comp\_id, comp\_name, address1, address2, address3,_

_address4, postcode, tel\_num, char1, char2, num1, num2, date1,_

_date2, fax\_num, tel\_ext, contact\_surname, contact\_fname, contact\_tel\_num, contact\_email);_

When a company has been successfully added, a unique company number (_comp\_num)_ value is returned.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **comp\_id** | char(8) | A unique code for the company (typically 3 chars e.g. &#39;CEM&#39;) |
| **comp\_name** | char(40) | Company name |
| **address1** | char(50) | Company address line 1 |
| address2 | char(50) | Company address line 2 |
| address3 | char(50) | Company address line 3 |
| address4 | char(50) | Company address line 4 |
| postcode | char(20) | Company postcode |
| tel\_num | char(20) | Telephone number |
| char1 | char(20) | Spare character field 7 (available for customer use) |
| char2 | char(20) | Spare character field 7 (available for customer use) |
| num1 | integer | Spare number field 1 (available for customer use) |
| num2 | integer | Spare number field 2 (available for customer use) |
| date1 | date | Spare date field 1 (available for customer use) |
| date2 | date | Spare date field 2 (available for customer use) |
| fax\_num | char(20) | Fax number |
| tel\_ext | char(10) | Telephone extension |
| contact\_surname | char(50) | Contact surname |
| contact\_fname | char(30) | Contact forename(s) |
| contact\_tel\_num | char(20) | Contact telephone number |
| contact\_email | char(75) | Contact email address |

**Highlighted** parameters are mandatory, the others can be _NULL._

The _comp\_id_ value must not already exist on the system.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid company id (_comp\_id_ is blank or null) |
| -2 | Duplicate _comp\_id_ |
| -3 | Invalid company name (_comp\_name_ value is blank or null) |
| -4 | Invalid _address1_ value (blank or null) |
| -5 | This is an Enterprise site – companies must be added at the controller site |
| -6 | Invalid telephone number - valid chars are 0-9, + - ( ) and space |
| -7 | Invalid fax number - valid chars are 0-9, + - ( ) and space |
| -8 | Invalid telephone extension - valid chars are 0-9, + - ( ) and space |
| -9 | Invalid contact telephone number - valid chars are 0-9, + - ( ) and space |
| -10 | Spare field &#39;char1&#39; is invalid |
| -11 | Spare field &#39;char2&#39; is invalid |
| -12 | Spare field &#39;num1&#39; is invalid |
| -13 | Spare field &#39;num2&#39; is invalid |
| -14 | Spare field &#39;date1&#39; is invalid |
| -15 | Spare field &#39;date2&#39; is invalid |
| \&gt;0 | Success, a numeric company number |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

  1.
### Update a Company record

The **api\_cmp\_upd** function can be used to update Company details.

_api\_cmp\_add( comp\_id, comp\_name, address1, address2, address3,_

_address4, postcode, tel\_num, char1, char2, num1, num2, date1,_

_date2, fax\_num, tel\_ext, contact\_surname, contact\_fname, contact\_tel\_num, contact\_email);_

When a company record has been successfully added, a _comp\_num_ value is returned. This company number is unique for this on the AC2000 system.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **comp\_id** | char(8) | A unique id for the company (a short code, typically 3 chars) |
| comp\_name | char(40) | Company name |
| address1 | char(50) | Company address line 1 |
| address2 | char(50) | Company address line 2 |
| address3 | char(50) | Company address line 3 |
| address4 | char(50) | Company address line 4 |
| Postcode | char(20) | Company postcode |
| tel\_num | char(20) | Telephone number |
| char1 | char(20) | Spare character field 7 (available for customer use) |
| char2 | char(20) | Spare character field 7 (available for customer use) |
| num1 | integer | Spare number field 1 (available for customer use) |
| num2 | integer | Spare number field 2 (available for customer use) |
| date1 | date | Spare date field 1 (available for customer use) |
| date2 | date | Spare date field 2 (available for customer use) |
| fax\_num | char(20) | Fax number |
| tel\_ext | char(10) | Telephone extension |
| contact\_surname | char(50) | Contact surname |
| contact\_fname | char(30) | Contact forename(s) |
| contact\_tel\_num | char(20) | Contact telephone number |
| contact\_email | char(75) | Contact email address |

**Highlighted** parameters are mandatory, the others can be _NULL._

If a value is NULL then the value previously stored in the company record will be used in its place, allowing the user to specify just the values to be changed instead of the complete list.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid _comp\_id_ (blank, null or not found) |
| -2 | Invalid _comp\_name_ (blank or null) |
| -3 | Invalid _address1_ value (blank or null) |
| -4 | This is an Enterprise site, companies must be updated at the controller site |
| -5 | Invalid telephone number - valid chars are 0-9, + - ( ) and space |
| -6 | Invalid fax number - valid chars are 0-9, + - ( ) and space |
| -7 | Invalid telephone extension - valid chars are 0-9, + - ( ) and space |
| -8 | Invalid contact telephone number - valid chars are 0-9, + - ( ) and space |
| -9 | Spare field &#39;char1&#39; is invalid |
| -10 | Spare field &#39;char2&#39; is invalid |
| -11 | Spare field &#39;num1&#39; is invalid |
| -12 | Spare field &#39;num2&#39; is invalid |
| -13 | Spare field &#39;date1&#39; is invalid |
| -14 | Spare field &#39;date2&#39; is invalid |
| \&gt;0 | Success, the numeric company number that was updated |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) the value for a unique field is both not null and not unique.

1.
## **Personnel Functions**

  1.
### Add a Personnel record

The **api\_per\_add** function can be used to create a new personnel record

_api\_per\_add( surname, forenames, badge\_name, gender, dateofbirth, address1, address2, address3, postcode, email\_addr, tel\_num, comp\_id, department, job\_title, payroll\_num, pin,_

_special, park\_exempt, exempt\_until, char1, char2,_

_char3, char4, num1, num2, date1, date2 [, manager\_ser] );_

When a personnel record has been successfully added, a _personnel\_ser_ value is returned. This is the unique identifier for this record on the AC2000 system and should be stored for future use.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **surname** | char(30) | Surname |
| forenames | char(30) | Forename(s) |
| badge\_name | char(61) | Badge name |
| gender | char(1) | Single letter gender code, &#39;M&#39;=Male, &#39;F&#39;=Female |
| dateofbirth | date | date of birth |
| address1 | char(20) | First line of address |
| address2 | char(20) | Second line of address |
| address3 | char(20) | Third line of address |
| postcode | char(10) | Postcode/Zip code |
| email\_addr | char(60) | Email address |
| tel\_num | char(20) | Telephone number |
| **comp\_id** | char(8) | Company code |
| department | char(20) | Department |
| job\_title | char(48) | Job Title |
| payroll\_num | char(20) | Payroll number |
| pin | char(9) | Pin code, digits 0-9 (cannot be all 0&#39;s or all 9&#39;s) |
| **special** | char(1) | Special processing required &#39;Y&#39;=yes, &#39;N&#39;=no |
| **park\_exempt** | char(1) | Person is exempt from having card parked due to lack of use, &#39;Y&#39;=yes, &#39;N&#39;=no |
| exempt\_until | date | Date when the card parking exemption expires |
| char1 | char(20) | Spare character field 1 (available for customer use) |
| char2 | char(20) | Spare character field 2 (available for customer use) |
| char3 | char(20) | Spare character field 3 (available for customer use) |
| char4 | char(20) | Spare character field 4 (available for customer use) |
| num1 | integer | Spare number field 1 (available for customer use) |
| num2 | integer | Spare number field 2 (available for customer use) |
| date1 | date | Spare date field 1 (available for customer use) |
| date2 | date | Spare date field 2 (available for customer use) |
| manager\_ser | integer | (Optional) the unique personnel\_ser of the persons manager |

**Highlighted** parameters are mandatory, the others can be _NULL._

The _comp\_id_ value must exactly match the value stored on the AC2000 system.

Spare field values must observe any constraints that have been configured for the fields.

The _job\_title_ value may be truncated if the configuration parameter _&#39;job\_title\_length_&#39; has been created to restrict it.

The _manager\_ser_ value can be omitted or set to NULL if the field is to be ignored.

The _pin_ value can be NULL in which case a random pin value will be generated.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | invalid surname |
| -2 | invalid gender |
| -3 | the company does not exist |
| -4 | Invalid pin code – e.g. empty, invalid character, all 0&#39;s or all 9&#39;s |
| -5 | &#39;special&#39; field not valid - must be &#39;Y&#39; or &#39;N&#39; |
| -6 | &#39;park\_exempt&#39; field is not valid - must be &#39;Y&#39; or &#39;N&#39; |
| -7 | &#39;tel\_num&#39; field is invalid - restricted to digits 0-9, &#39;-&#39;, &#39;(&#39; and &#39;)&#39; |
| -8 | Spare field &#39;char1&#39; is invalid |
| -9 | Spare field &#39;char2&#39; is invalid |
| -10 | Spare field &#39;char3&#39; is invalid |
| -11 | Spare field &#39;char4&#39; is invalid |
| -12 | Spare field &#39;num1&#39; is invalid |
| -13 | Spare field &#39;num2&#39; is invalid |
| -14 | Spare field &#39;date1&#39; is invalid |
| -15 | Spare field &#39;date2&#39; is invalid |
| -16 | Invalid or duplicate payroll\_num (when unique payroll number checks are enabled) |
| -17 | Invalid manager\_ser (not a manager for the specified company) |
| \&gt;0 | Success (the return value is the personnel\_ser of the new record) |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

The system can be configured to insist on mandatory unique payroll numbers by setting configuration option &#39;unique\_payroll\_num&#39; to &#39;Y&#39;.

This function will strip leading and trailing blank characters from each character string. If a resulting string is empty and it is possible to do so then NULL is stored instead.

  1.
### Change a Personnel record

The **api\_per\_upd** function can be used to change an existing personnel record

_api\_per\_upd( personnel __\___ ser__,_ _surname, forenames, badge\_name,_

_gender, dateofbirth, address1, address2, address3, postcode, email\_addr, tel\_num, comp\_id, department, job\_title, payroll\_num, pin, special, park\_exempt, exempt\_until, char1, char2,_

_char3, char4, num1, num2, date1, date2 [, manager\_ser] );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **personnel\_ser** | integer | The unique _personnel\_ser_ value for the personnel record |
| surname | char(30) | Surname |
| forenames | char(30) | Forename(s) |
| badge\_name | char(61) | Badge name |
| gender | char(1) | Single letter gender code, &#39;M&#39;=Male, &#39;F&#39;=Female |
| dateofbirth | date | date of birth |
| address1 | char(20) | First line of address |
| address2 | char(20) | Second line of address |
| address3 | char(20) | Third line of address |
| postcode | char(10) | Postcode/Zip code |
| email\_addr | char(60) | Email address |
| tel\_num | char(20) | Telephone number |
| comp\_id | char(8) | Company code |
| department | char(20) | Department |
| job\_title | char(48) | Job Title |
| payroll\_num | char(20) | Payroll number |
| pin | char(9) | Pin code, digits 0-9 (cannot be all 0&#39;s or all 9&#39;s) |
| special | char(1) | Special processing required &#39;Y&#39;=yes, &#39;N&#39;=no |
| park\_exempt | char(1) | Cardholder is exempt from having ID card parked due to lack of use, &#39;Y&#39;=yes, &#39;N&#39;=no |
| exempt\_until | date | Date when the card parking exemption expires |
| char1 | char(20) | Spare character field (available for customer use) |
| char2 | char(20) | Spare character field (available for customer use) |
| char3 | char(20) | Spare character field (available for customer use) |
| char4 | char(20) | Spare character field (available for customer use) |
| num1 | integer | Spare number field (available for customer use) |
| num2 | integer | Spare number field (available for customer use) |
| date1 | date | Spare date field (available for customer use) |
| date2 | date | Spare date field (available for customer use) |
| manager\_ser | integer | Optional – the unique personnel\_ser of the persons manager |

**Highlighted** parameters are mandatory, the others can be _NULL._

If a value is NULL then the value previously stored in the personnel record will be used in its place, allowing the user to specify just the values to be changed instead of the complete list.

A _comp\_id_ value must exactly match the value stored on the AC2000 system.

Spare field values must observe any constraints that have been configured for the fields.

The _job\_title_ value may be truncated if the configuration parameter &#39;_job\_title\_length_&#39; has been created to restrict it.

The manager\_ser value can be omitted or set to NULL which will indicate that no change will be required. To remove a manager\_ser value from a personnel record, set its value to 0.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser |
| -2 | Invalid surname |
| -3 | Invalid gender |
| -4 | The company does not exist |
| -5 | The company has not been assigned to the specified cardholder |
| -6 | Invalid pin code – e.g. blank, invalid character, all 0&#39;s or all 9&#39;s |
| -7 | &#39;special&#39; field not valid - must be &#39;Y&#39; or &#39;N&#39; |
| -8 | &#39;park\_exempt&#39; field is not valid - must be &#39;Y&#39; or &#39;N&#39; |
| -9 | &#39;tel\_num&#39; field is invalid - restricted to digits 0-9, &#39;-&#39;, &#39;(&#39; and &#39;)&#39; |
| -10 | Spare field &#39;char1&#39; is invalid (have constraints been observed?) |
| -11 | Spare field &#39;char2&#39; is invalid |
| -12 | Spare field &#39;char3&#39; is invalid |
| -13 | Spare field &#39;char4&#39; is invalid |
| -14 | Spare field &#39;num1&#39; is invalid |
| -15 | Spare field &#39;num2&#39; is invalid |
| -16 | Spare field &#39;date1&#39; is invalid |
| -17 | Spare field &#39;date2&#39; is invalid |
| -18 | Invalid or duplicate payroll\_num (when unique payroll number checks are enabled) |
|
 | -19 | Invalid manager\_ser (not a manager for the specified company) |
| 1 | Success |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

This function will strip leading and trailing blank characters from each character string. If a resulting string is empty and it is possible to do so then NULL is stored instead.

  1.
### Delete a Personnel record

The **api\_per\_del** function can be used to delete an existing personnel record

_api\_per\_del( personnel\_ser );_

The record cannot be deleted if an ID card record still exists for this personnel record; any ID card records must be deleted first.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the personnel record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser |
| 0 | No record found for the personnel\_ser |
| 1 | Success |

  1.
### Add a Personnel Company record

When a personnel record is created using the _ **api\_per\_add** _ function, a personnel company record is also created automatically, using the parameter values supplied (_comp\_id_, _job\_title_, and _department_).

Additional personnel company records can be created for cases where a person is employed in other companies within the same AC2000 environment (e.g. they have a second job in a sister company).

The **api\_per\_cmp\_add** function can be used to create an additional company record.

_**api\_per\_cmp\_add( personnel\_ser, comp\_id, job\_title, department );**_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **personnel\_ser** | integer | The unique _personnel\_ser_ value for the personnel record |
| **comp\_id** | char(8) | Company code |
| job\_title | char(48) | Job Title |
| department | char(20) | Department |

**Highlighted** parameters are mandatory, the others can be _NULL._

The _comp\_id_ value must exactly match the value stored on the AC2000 system.

The _job\_title_ value may be truncated if the configuration parameter &#39;_job\_title\_length_&#39; has been created to restrict it.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | No personnel record exists with this personnel\_ser or personnel\_ser belongs to a different site |
| -2 | No company found for the comp\_id |
| -3 | Company record already exists for this personnel\_ser |
| 1 | Success, company record added |

This function will strip leading and trailing blank characters from each character string. If a resulting string is empty and it is possible to do so then NULL is stored instead.

  1.
### Remove a Personnel Company record

The **api\_per\_cmp\_del** function can be used to delete a personnel company record. This will remove the company membership from the personnel record

_api\_per\_cmp\_del( personnel\_ser, comp\_id );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the personnel record |
| comp\_id | char(8) | Company code |

The _comp\_id_ value must exactly match the value stored on the AC2000 system.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | No personnel record exists with this personnel\_ser or personnel\_ser belongs to a different site |
| -2 | No company found for the comp\_id |
| -3 | Company cannot be deleted as this person has active ID cards for this company |
| -4 | Company cannot be deleted as this person is a manager for at least one other person for this company |
| 1 | Success, company record added |

  1.
### Set or Change Personnel spare fields

Personnel records contain a number of spare fields which are available for customer use. The **api\_per\_spareflds\_set** function can be used to set or change the spare fields for an existing personnel record.

_(Personnel spare fields can also be changed using the_ [_api\_per\_upd_](#Change_a_Personnel_record) _procedure)_

_api\_per\_spareflds\_set( personnel\_ser, char1, char2, char3, char4,_

_num1, num2, date1, date2 );_

Parameter values are checked against any constraints which might be in place. If a value is not NULL, it is validated and stored. If the value is NULL, the existing spare field value is not modified.

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the personnel record |
| char1 | char(20) | personnel record spare character field 1 |
| char2 | char(20) | personnel record spare character field 2 |
| char3 | char(20) | personnel record spare character field 3 |
| char4 | char(20) | personnel record spare character field 4 |
| num1 | integer | personnel record spare number field 1 |
| num2 | integer | personnel record spare number field 2 |
| date1 | date | personnel record spare date field 1 |
| date2 | date | personnel record spare date field 2 |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser |
| -2 | The value for &#39;char1&#39; is invalid |
| -3 | The value for &#39;char2&#39; is invalid |
| -4 | The value for &#39;char3&#39; is invalid |
| -5 | The value for &#39;char4&#39; is invalid |
| -6 | The value for &#39;num1&#39; is invalid |
| -7 | The value for &#39;num2&#39; is invalid |
| -8 | The value for &#39;date1&#39; is invalid |
| -9 | The value for &#39;date2&#39; is invalid |
| 1 | Success, any new values are stored |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

  1.
### Clear Personnel spare fields

Personnel records contain a number of spare fields which are available for customer use. The **api\_per\_spareflds\_clr** function can be used to wipe the spare field values for an existing personnel record.

_api\_per\_spareflds\_clr( personnel\_ser );_

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the personnel record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser |
| 0 | Data update error |
| 1 | Success |

  1.
### Set or Change Personnel dynamic fields

Customers can add additional dynamic fields for Personnel records using the AC2000 workstation interface. These fields can be a mixture of integers, strings (of 80, 40 or 20 characters in length), date fields, checkboxes and dropdown lists.

The **api\_per\_userfld\_set** function can be used to set or change the values of these fields.

_api\_per\_userfld\_set( personnel\_ser, field\_name, field\_value );_

The _field\_name_ value is the string value of the label associated with the field at creation time. Each dynamic field should have a unique label to avoid setting the value of more than one field when this function executes.

Values must adhere to any constraints that have been configured for the field e.g. maximum and minimum string lengths, maximum and minimum integer values and uniqueness.

For checkbox fields a value of either &#39;Y&#39; or 1 will set the checkbox, while a value of &#39;N&#39; or 0 will clear it.

For dropdown lists, any values provided must already exist in the list of available items that have been configured for that dropdown field.

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the personnel record |
| field\_name | char(32) | field name - the value of the **label** associated with the field |
| field\_value | (variable) | field value - this will vary depending on the field type of the dynamic field i.e. char(n), date, integer etc. |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser |
| -2 | The field name was not found |
| -3 | The field value is outside the acceptable range |
| -4 | The field value does not match the format specified for the field |
| -5 | The field is marked as unique and a duplicate value already exists |
| -6 | Failed to update the field value |
| 1 | Success, the field value was stored |

1.
## **ID Card Functions**

  1.
### Add an ID Card record

The **api\_idc\_add** function can be used to create a new ID Card record

_api\_idc\_add( personnel\_ser, card\_form\_desc, acc\_lev\_desc, gtz\_desc,_

_start\_time, expiry\_time, comp\_id, auth\_num, rf\_issue\_desc, charge,_

_char1, char2, char3, char4, num1, num2, datetime1, datetime2 );_

When an ID card record has been successfully added, an _id\_cards\_ser_ value is returned. This is the unique identifier for this record on the AC2000 system and should be stored for future use.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **personnel\_ser** | integer | The unique _personnel\_ser_ value for the personnel record |
| **card\_form\_desc** | char(20) | Card Format description |
| **acc\_lev\_desc** | char(30) | Access Level description |
| **gtz\_desc** | char(20) | Timezone description |
| **start\_time** | datetime | Card start datetime |
| **expiry\_time** | datetime | Card expiry datetime |
| **comp\_id** | char(8) | Company ID |
| auth\_num | integer | Authoriser number |
| rf\_issue\_desc | char(20) | Reason for Issue |
| charge | integer | Charge |
| char1 | char(20) | Spare character field (available for customer use) |
| char2 | char(20) | Spare character field (available for customer use) |
| char3 | char(20) | Spare character field (available for customer use) |
| char4 | char(20) | Spare character field (available for customer use) |
| num1 | integer | Spare number field (available for customer use) |
| num2 | integer | Spare number field (available for customer use) |
| datetime1 | datetime | Spare datetime field (available for customer use) |
| datetime2 | datetime | Spare datetime field (available for customer use) |

**Highlighted** parameters are mandatory, the others can be _NULL._

If authorisers are enabled on the system, the &#39;_auth\_num_&#39; field will also be mandatory.

If charging is enabled on the system, the &#39;_rf\_issue\_desc_&#39; and &#39;_charge_&#39; fields will also be mandatory.

Values for _comp\_id_, _card\_form\_desc_, _acc\_lev\_desc_, _gtz\_desc_ and _rf\_issue\_desc_ should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

Spare field values must observe any constraints that have been configured for the fields.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser |
| -2 | Invalid card format |
| -3 | Invalid access level |
| -4 | Invalid access level for the specified card format |
| -5 | Invalid time zone |
| -6 | Invalid start date |
| -7 | Invalid expiry date |
| -8 | Invalid authoriser |
| -9 | Invalid &#39;reason for issue&#39; |
| -10 | Invalid charge |
| -11 | Spare field &#39;char1&#39; is invalid (have constraints been observed?) |
| -12 | Spare field &#39;char2&#39; is invalid |
| -13 | Spare field &#39;char3&#39; is invalid |
| -14 | Spare field &#39;char4&#39; is invalid |
| -15 | Spare field &#39;num1&#39; is invalid |
| -16 | Spare field &#39;num2&#39; is invalid |
| -17 | Spare field &#39;datetime1&#39; is invalid |
| -18 | Spare field &#39;datetime2&#39; is invalid |
| -19 | Invalid company ID |
| -20 | The specified company has not been assigned to this cardholder. |
| \&gt;0 | Success (the return value is the id\_cards\_ser of the new ID card record) |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

  1.
### Change an ID Card

The **api\_idc\_upd** function can be used to change an existing ID Card record

_api\_idc\_upd( id\_cards\_ser, card\_form\_desc, acc\_lev\_desc, gtz\_desc,_

_start\_time, expiry\_time, status, auth\_num, rf\_issue\_desc, charge,_

_char1, char2, char3, char4, num1, num2, datetime1, datetime2 );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **id\_cards\_ser** | integer | The unique _id\_cards\_ser_ value for the ID card record |
| card\_form\_desc | char(20) | Card Format description |
| acc\_lev\_desc | char(30) | Access Level description |
| gtz\_desc | char(20) | Timezone description |
| start\_time | datetime | Card start datetime |
| expiry\_time | datetime | Card expiry datetime |
| status | char(1) | Card status |
| auth\_num | integer | Authoriser number |
| rf\_issue\_desc | char(20) | Reason for Issue |
| charge | integer | Charge |
| char1 | char(20) | Spare character field available for customer use |
| char2 | char(20) | Spare character field available for customer use |
| char3 | char(20) | Spare character field available for customer use |
| char4 | char(20) | Spare character field available for customer use |
| num1 | integer | Spare number field available for customer use |
| num2 | integer | Spare number field available for customer use |
| datetime1 | datetime | Spare datetime field available for customer use |
| datetime2 | datetime | Spare datetime field available for customer use |

**Highlighted** parameters are mandatory, the others can be _NULL._

If a value is NULL then the value previously stored in the card record will be used in its place, allowing the user to specify just the values to be changed instead of the complete list.

Any values for _comp\_id, __card\_form\_desc, acc\_lev\_desc, gtz\_desc,__ rf\_issue\_desc_ should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

Spare field values must observe any constraints that have been configured for the fields.

The card format for an ID card cannot be changed if the card has already been validated.

The Card Status can be one of the following

| **Code** | **Description** |
| --- | --- |
| A | The ID card is about to Expire |
| X | The ID Card has Expired |
| S | The ID Card has been Lost or Stolen |
| N | The ID Card is Not yet Operational |
| C | The ID Card is Currently active |
| P | The ID Card has been Purged from the system |

An ID card cannot be updated to have a valid status (&#39;N&#39;, &#39;C&#39; or &#39;A&#39;) unless the company is one of those assigned to the card holder.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid id\_cards\_ser |
| -2 | Status cannot be valid (&#39;N&#39;, &#39;C&#39; or &#39;A&#39;) as the ID card does not belong to one of the ID card owners current companies |
| -3 | Invalid card format |
| -4 | ID Card has already been validated |
| -5 | Invalid access level |
| -6 | Invalid access level for the specified card format |
| -7 | Invalid time zone |
| -8 | Invalid start date |
| -9 | Attempt to change the start date of a validated card |
| -10 | Invalid expiry date |
| -11 | Invalid status code |
| -12 | Invalid authoriser |
| -13 | Invalid &#39;reason for issue&#39; |
| -14 | Invalid charge |
| -15 | Spare field &#39;char1&#39; is invalid (have constraints been observed?) |
| -16 | Spare field &#39;char2&#39; is invalid |
| -17 | Spare field &#39;char3&#39; is invalid |
| -18 | Spare field &#39;char4&#39; is invalid |
| -19 | Spare field &#39;num1&#39; is invalid |
| -20 | Spare field &#39;num2&#39; is invalid |
| -21 | Spare field &#39;datetime1&#39; is invalid |
| -22 | Spare field &#39;datetime2&#39; is invalid |
| 1 | Success, ID card record was updated |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

  1.
### Validate an ID Card

The **api\_idc\_val** function can be used to validate an ID Card.

_api\_idc\_val( id\_cards\_ser, hotstamp\_num, card\_num );_

This function validates (activates) an ID card using the supplied hotstamp and card numbers. Note this can only be done for card formats which are readable and do not automatically generate card numbers.

If the _hotstamp\_num_ value is NULL, the function will attempt to use an existing hotstamp number for the card (e.g. an auto-generated hotstamp number).

If the _hotstamp\_num_ value is _not_ NULL and the hotstamp number has been auto-generated during _api\_idc\_add_ or _api\_idc\_upd_ function calls, the supplied value must match the previously auto-generated one.

Card numbers must be specified in hexadecimal format and their length must match the number of bits used in the system configuration. The hexadecimal values must be preceded by leading zeroes to fill the values to their expected length.

e.g. the decimal 32-bit card number **16519851** when converted to hex is &#39; **FC12AB&#39;**. When expanded to its full 32-bit value this will give a card\_num value of &#39; **00FC12AB&#39;.**

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| id\_cards\_ser | integer | The unique _id\_cards\_ser_ value for the ID card record |
| hotstamp\_num | integer | The ID cards hotstamp number |
| card\_num | char(64) | The ID card number (hexadecimal with leading zeros) |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid id\_cards\_ser |
| -2 | The card format is non-readable |
| -3 | The card format auto-generates card numbers |
| -4 | The hotstamp number is invalid or does not match the auto-generated value |
| -5 | The card number is invalid |
| -6 | The ID card has already been validated |
| 1 | Success |

  1.
### Return an ID Card

The **api\_idc\_ret** function can be used to return an ID Card.

_api\_idc\_ret( id\_cards\_ser );_

This function returns (deactivates) an ID card. Note this can only be done for _reusable_ card types.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| id\_cards\_ser | integer | The unique _id\_cards\_ser_ value for the ID card record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid id\_cards\_ser or the owners personnel\_ser belongs to a different site |
| -2 | The id card has not been validated |
| -3 | The id card type is not reusable |
| 1 | Success |

  1.
### Delete an ID Card

The **api\_idc\_del** function can be used to delete an ID Card.

_api\_idc\_del( id\_cards\_ser );_

Cards which have been validated cannot be deleted (even if they not currently active).

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| id\_cards\_ser | integer | The unique _id\_cards\_ser_ value for the personnel record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | The card has previously been validated so can&#39;t be deleted |
| 0 | Either (a) the id\_cards\_ser is invalid or (b) this is an enterprise system, the card was created on a different site than the current one (it must be deleted on the site where it was created). |
| 1 | Success |

  1.
### Set or Change ID Card spare fields

ID Card records contain a number of spare fields which are available for customer use. The **api\_idc\_spareflds\_set** function can be used to set or change the spare fields for an existing ID Cards record.

_(ID Card spare fields can also be changed using the_ [_api\_idc\_upd_](#Change_an_ID_card) _procedure)_

_api\_idc\_spareflds\_set( id\_cards\_ser, char1, char2, char3, char4,_

_num1, num2, datetime1, datetime2 );_

Parameter values are checked against any constraints which might be in place. If a value is not NULL, it is validated and stored. If the value is NULL, the existing spare field value is not modified.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| id\_cards\_ser | integer | The unique _id\_cards\_ser_ value for the ID Card record |
| char1 | char(20) | ID card record customer character field 1 |
| char2 | char(20) | ID card record customer character field 2 |
| char3 | char(20) | ID card record customer character field 3 |
| char4 | char(20) | ID card record customer character field 4 |
| num1 | integer | ID card record customer number field 1 |
| num2 | integer | ID card record customer number field 2 |
| datetime1 | datetime | ID card record customer datetime field 1 |
| datetime2 | datetime | ID card record customer datetime field 2 |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid id\_cards\_ser |
| -2 | The value for &#39;char1&#39; is invalid |
| -3 | The value for &#39;char2&#39; is invalid |
| -4 | The value for &#39;char3&#39; is invalid |
| -5 | The value for &#39;char4&#39; is invalid |
| -6 | The value for &#39;num1&#39; is invalid |
| -7 | The value for &#39;num2&#39; is invalid |
| -8 | The value for &#39;datetime1&#39; is invalid |
| -9 | The value for &#39;datetime2&#39; is invalid |
| 1 | Success, any new values are stored |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

  1.
### Clear ID Card spare fields

ID Card records contain a number of spare fields which are available for customer use. The **api\_idc\_spareflds\_clr** function can be used to wipe the spare field values for an existing ID Card record.

_api\_per\_spareflds\_clr( id\_cards\_ser );_

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| id\_cards\_ser | integer | The unique _id\_cards\_ser_ value for the ID Card record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid id\_cards\_ser |
| 0 | Data update error |
| 1 | Success |

  1.
### Set ID Card Access Level and Timezone

The **api\_al\_gtz\_set** function can be used to set the Access Level and Timezone for a given ID Card.

_api\_al\_gtz\_set( id\_cards\_ser, acc\_lev\_desc, gtz\_desc );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| id\_cards\_ser | integer | The unique _id\_cards\_ser_ value for the ID card record |
| acc\_lev\_desc | char(30) | Access Level description |
| gtz\_desc | char(20) | Timezone description |

If the value for _acc\_lev\_desc_ is NULL then no access level change will be made.

If the value for _gtz\_desc_ is NULL then no Timezone change will be made.

The values for _acc\_lev\_desc, gtz\_desc_ should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid id\_cards\_ser |
| -2 | Invalid Access Level |
| -3 | Access Level is not valid for the Card Format for the card |
| -4 | Invalid Timezone |
| 1 | Success, ID card record was updated |

1.
## **Access Level functions**

  1.
### Assign an Extra Access Level to a Cardholder

The **api\_ea\_add** function can be used to assign an additional access level to a cardholder.

_api\_ea\_add( personnel\_ser, acc\_lev\_desc, gtz\_desc );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the Personnel record |
| acc\_lev\_desc | char(30) | Access Level description |
| gtz\_desc | char(20) | Timezone description |

The extra access will not be assigned in the following circumstances

- The cardholder already has the extra access assigned.
- The access level has not been assigned to the cardholder&#39;s card format.
- The access level and timezone have already been granted to the cardholder via an existing manual temporary access assignment which has specific start and end times.
- The access level and timezone have already been granted to the cardholder via an existing swipe-invoked temporary access assignment which will be enabled when the cardholder swipes on an enabling reader (defined within a configured temporary access area).

Values for _acc\_lev\_desc_ and _gtz\_desc_ should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser |
| -2 | The Access Level does not exist |
| -3 | Invalid Access Level for the card format of the cardholder ID card |
| -4 | Invalid Timezone |
| -5 | The Access level and timezone assignment already exists for this cardholder (the assignment is a duplicate or exists as a temporary access assignment) |
| 1 | Success, any new values are stored |

  1.
### Remove an Extra Access Level from an Cardholder

The **api\_ea\_del** function can be used to remove an additional access level from a cardholder.

_api\_ea\_del(personnel\_ser, acc\_lev\_desc, gtz\_desc );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the Personnel record |
| acc\_lev\_desc | char(30) | Access Level description |
| gtz\_desc | char(20) | Timezone description |

Values for _acc\_lev\_desc_ and _gtz\_desc_ should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser |
| -2 | The Access Level does not exist |
| -3 | Invalid Timezone |
| -4 | The Extra Access record does not exist |
| 1 | Success, the Extra Access Level was removed |

  1.
### Assign Temporary Access to an Cardholder

The **api\_tea\_add** function can be used to temporarily assign an additional access level to a cardholder.

_api\_tea\_add( personnel\_ser, acc\_lev\_desc, gtz\_desc,_

_start\_time, end\_time );_

The Access level will be active between the start and end times.

When a temporary access record has been successfully added a _tea\_ser_ value is returned. This is the unique identifier for this record on the AC2000 system and must be stored for future use.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the Personnel record |
| acc\_lev\_desc | char(30) | Access Level description |
| gtz\_desc | char(20) | Timezone description |
| start\_time | datetime | Extra Access start time |
| end\_time | datetime | Extra Access end time |

The temporary extra access will not be assigned in the following circumstances

- The access level has not been assigned to the cardholder&#39;s card format.
- The access level and timezone have already been granted to the cardholder via an existing full extra access assignment (see the [api\_ea\_add](#Assign_extra_access) function).
- The access level and timezone have already been granted to the cardholder via an existing swipe-invoked temporary access assignment which will be enabled when the cardholder swipes on an enabling reader (defined within a configured temporary access area).
- The start or end time overlaps an already existing temporary extra access assignment.

Parameters _acc\_lev\_desc_ and _gtz\_desc_ should exactly match the value stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser |
| -2 | The Access Level does not exist |
| -3 | Invalid Access Level for the card format of the cardholders ID card |
| -4 | Invalid Timezone |
| -5 | Invalid Start time |
| -6 | Invalid End time (empty, earlier than Start time or in the past) |
| -7 | The Access level and Timezone assignment already exists for this cardholder as a full or swipe-invoked extra access assignment or the start or end time overlaps with an existing temporary access entry |
| 1 | Success, any new values are stored |

  1.
### Remove Temporary Access from an Cardholder

The **api\_tea\_del** function can be used to remove a temporarily assigned access level from a cardholder.

_api\_tea\_del( tea\_ser );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| tea\_ser | integer | The unique _tea\_ser_ value for the Temporary Access level record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| 0 | Failed to delete the temporary access |
| 1 | The temporary access was removed |

  1.
### Add Extra Access to a group of Cardholders

The **api\_group\_ea\_add** function can be used to assign an extra access level to a group of cardholders for a specific timezone.

_api\_group\_ea\_add( field\_name, field\_value, acc\_lev\_desc, gtz\_desc );_

The function looks for a specific value in a named field. All cardholders who have a matching value in that field will have the extra access assigned

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| field\_name | char(20) | The field name to check |
| field\_value | char(60) | The value to find in the field |
| acc\_lev\_desc | char(30) | Access Level description to be assigned |
| gtz\_desc | char(20) | Timezone description to be applied to the extra access |

The _field\_name_ value can be one of the following fields

| **Field\_name** | **Description** |
| --- | --- |
| job\_title | _job\_title_ from a cardholders company record |
| department | _department_ from a cardholders company record |
| pers\_char1 | Personnel record spare char1 (per text1) |
| pers\_char2 | Personnel record spare char1 (per text2) |
| pers\_char3 | Personnel record spare char1 (per text3) |
| pers\_char4 | Personnel record spare char1 (per text4) |
| pers\_num1 | Personnel record spare char1 (per num1) |
| pers\_num2 | Personnel record spare char1 (per num2) |
| pers\_date1 | Personnel record spare char1 (per date1) |
| pers\_date2 | Personnel record spare char1 (per date2) |

If the _gtz\_desc_ value is NULL or omitted, the default value used is &#39;ALL THE TIME&#39;.

The extra access will not be assigned in the following circumstances

- The cardholder already has the extra access assigned.
- The access level has not been assigned to cardholders card format.

Values for _acc\_lev\_desc_ and _gtz\_desc_ should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Field name is invalid (not in the allowed list) |
| -2 | Field value is invalid (NULL or blank) |
| -3 | The access level is invalid |
| -4 | The timezone is invalid |
| \&gt;=0 | Success, the number of cardholders who had the extra access level assigned |

  1.
### Remove Extra Access from a group of Cardholders

The **api\_group\_ea\_del** function can be used to remove an extra access level from a group of cardholders for a specific timezone.

_api\_group\_ea\_del( field\_name, field\_value, acc\_lev\_desc, gtz\_desc );_

The function looks for a specific value in a named field. All cardholders who have a matching value in that field will have the extra access level removed

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| field\_name | char(20) | The field name to check |
| field\_value | char(60) | The value to find in the field |
| acc\_lev\_desc | char(30) | Access Level description to be removed |
| gtz\_desc | char(20) | Timezone description for the extra access to be removed |

Refer to the [_api\_group\_ea\_add_](#Add_group_extra_access) function for a list of available _field\_name_ values.

If the _gtz\_desc_ value is NULL or omitted, the default value used is &#39;ALL THE TIME&#39;.

Values for _acc\_lev\_desc_ and _gtz\_desc_ should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Field name is invalid (not in the allowed list) |
| -2 | Field value is invalid (NULL or blank) |
| -3 | The access level is invalid |
| -4 | The timezone is invalid |
| \&gt;=0 | Success, the number of cardholders who had the extra access level removed |

  1.
### Determine if Extra Access is enabled for a group of Cardholders

The **api\_group\_ea\_active** function will attempt to determine if an extra access level group assignment is active or not.

_api\_group\_ea\_active( field\_name, field\_value, acc\_lev\_desc, gtz\_desc, percentage );_

The function looks for a specific value in a named field.

The function will calculate the number of cardholders who have a specific value in a named field. The number of matching extra access entries for the access level and timezone is also calculated. If the ratio of matching personnel to extra access entries is at least equal to the percentage value, the group extra access is deemed to be active.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| field\_name | char(20) | The field name to check |
| field\_value | char(60) | The value to find in the field |
| acc\_lev\_desc | char(30) | Access Level description to be checked for assignment |
| gtz\_desc | char(20) | Timezone description applied to the extra access |

Refer to the [_api\_group\_ea\_add_](#Add_group_extra_access) function for a list of available _field\_name_ values.

If the _gtz\_desc_ value is NULL or omitted, the default value used is &#39;ALL THE TIME&#39;.

If the _percentage_ value is NULL or omitted, the default value used is 75.

Values for _acc\_lev\_desc_ and _gtz\_desc_ should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Field name is invalid (not in the allowed list) |
| -2 | Field value is invalid (NULL or blank) |
| -3 | The access level is invalid |
| -4 | The timezone is invalid |
| -5 | The percentage value is invalid (less than 0 or more than 100) |
| 0 | Success, the group extra access assignment is assumed to be inactive |
| 1 | Success, the group extra access assignment is assumed to be active |

  1.
### Add a new Access Level Description

The **api\_al\_desc\_add** function can be used to add a new access level description.

_api\_al\_desc\_add( acc\_lev\_desc );_

Only the Access Level description can be created, the actual configuration of the Access Level must be performed using the AC2000 Workstation &#39;Access Level&#39; toolbar app.

The new description must not already exist on the system.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| acc\_lev\_desc | char(30) | Access Level description to be created |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid description (null or blank) |
| -2 | Duplicate description |
| \&gt;0 | The unique number of the newly created Access Llevel |

  1.
### Change the Description of an Access Level

The **api\_al\_desc\_chg** function can be used to change an access level description.

_api\_al\_desc\_chg( acc\_lev\_desc, new\_acc\_lev\_desc );_

Only the Access Level&#39;s Description can be changed, other configuration changes must be performed using the AC2000 Workstation &#39;Access Level&#39; toolbar app.

The new description must not already exist on the system.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| acc\_lev\_desc | char(30) | The description for the Access Level to be changed |
| new\_acc\_lev\_desc | char(30) | The new value for the Access Level description |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid valid for the current description (null, blank or not found) |
| -2 | Invalid valid for the new description (null or blank) |
| -3 | Duplicate value for the new description |
| \&gt;0 | The unique access level number of the changed access level |

1.
## **Visitor functions**

  1.
### Add a Visitor record

The **api\_vis\_add** function can be used to create a new visitor record.

_api\_vis\_add( surname, forenames, comp\_name, pin, threat\_level,_

_tel\_num, email\_addr, tel\_num, char1, char2, char3, char4,_

_char5, char6, char7, char8 );_

When a visitor record has been successfully added, a _visitor\_ser_ value is returned. This is the unique identifier for this record on the AC2000 system and should be stored for future use.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **surname** | char(34) | Visitor surname |
| **forenames** | char(34) | Visitor forenames(s) |
| **comp\_name** | char(30) | Visitor company name |
| pin | char(9) | Pin to be used for any card assigned to the visitor (digits 0-9) |
| threat\_level | integer | The threat level to be applied to the visitor |
| tel\_num | char(20) | Visitor telephone number |
| email\_addr | char(60) | Visitor email address |
| char1 | char(40) | Spare character field 1 (available for customer use) |
| char2 | char(40) | Spare character field 2 (available for customer use) |
| char3 | char(40) | Spare character field 3 (available for customer use) |
| char4 | char(40) | Spare character field 4 (available for customer use) |
| char5 | char(40) | Spare character field 5 (available for customer use) |
| char6 | char(40) | Spare character field 6 (available for customer use) |
| char7 | char(40) | Spare character field 7 (available for customer use) |
| char8 | char(40) | Spare character field 8 (available for customer use) |

**Highlighted** parameters are mandatory, the others can be _NULL._

Spare field values must observe any constraints that have been configured for the fields.

The _threat\_level_ value must be greater than zero to have the level applied to the visitor

The _pin_ value can be NULL in which case a random pin value will be generated.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid surname |
| -2 | Invalid forenames |
| -3 | Invalid company name |
| -4 | Invalid pin code – e.g. blank, invalid character, all 0&#39;s or all 9&#39;s |
| -5 | Failed to set the Threat Level |
| -6 | Spare field &#39;char1&#39; is invalid |
| -7 | Spare field &#39;char2&#39; is invalid |
| -8 | Spare field &#39;char3&#39; is invalid |
| -9 | Spare field &#39;char4&#39; is invalid |
| -10 | Spare field &#39;char5&#39; is invalid |
| -11 | Spare field &#39;char6&#39; is invalid |
| -12 | Spare field &#39;char7&#39; is invalid |
| -13 | Spare field &#39;char8&#39; is invalid |
| \&gt;0 | Success (the return value is the visitor\_ser of the new record) |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

This function will strip leading and trailing blank characters from each character string. If a resulting string is empty and it is possible to do so then NULL is stored instead.

  1.
### Change a Visitor record

The **api\_vis\_upd** function can be used to change an existing visitor record.

_api\_vis\_upd( visitor\_ser, surname, forenames, comp\_name, pin,_

_tel\_num, email\_addr, tel\_num, char1, char2, char3, char4,_

_char5, char6, char7, char8 );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **visitor\_ser** | integer | The unique _visitor\_ser_ value for the visitor record |
| surname | char(34) | Visitor surname |
| forenames | char(34) | Visitor forenames(s) |
| comp\_name | char(30) | Visitor company name |
| pin | char(9) | Pin to be used for any card assigned to the visitor (digits 0-9) |
| tel\_num | char(20) | Visitor telephone number |
| email\_addr | char(60) | Visitor email address |
| char1 | char(40) | Spare character field 1 (available for customer use) |
| char2 | char(40) | Spare character field 2 (available for customer use) |
| char3 | char(40) | Spare character field 3 (available for customer use) |
| char4 | char(40) | Spare character field 4 (available for customer use) |
| char5 | char(40) | Spare character field 5 (available for customer use) |
| char6 | char(40) | Spare character field 6 (available for customer use) |
| char7 | char(40) | Spare character field 7 (available for customer use) |
| char8 | char(40) | Spare character field 8 (available for customer use) |

**Highlighted** parameters are mandatory, the others can be _NULL._

If a value is NULL then the value previously stored in the visitor record will be used in its place, allowing the user to specify just the values to be changed instead of the complete list.

Spare field values must observe any constraints that have been configured for the fields.

The visitor threat level value can be changed using the [_api\_thl\_per\_set_](#Set_cardholder_threat_level) function.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid visitor\_ser |
| -2 | Invalid surname |
| -3 | Invalid forenames |
| -4 | Invalid company name |
| -5 | Invalid pin code – e.g. blank, invalid character, all 0&#39;s or all 9&#39;s |
| -6 | Spare field &#39;char1&#39; is invalid |
| -7 | Spare field &#39;char2&#39; is invalid |
| -8 | Spare field &#39;char3&#39; is invalid |
| -9 | Spare field &#39;char4&#39; is invalid |
| -10 | Spare field &#39;char5&#39; is invalid |
| -11 | Spare field &#39;char6&#39; is invalid |
| -12 | Spare field &#39;char7&#39; is invalid |
| -13 | Spare field &#39;char8&#39; is invalid |
| \&gt;0 | Success (the return value is the visitor\_ser of the new record) |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

This function will strip leading and trailing blank characters from each character string. If a resulting string is empty and it is possible to do so then NULL is stored instead.

  1.
### Delete a Visitor record

The **api\_vis\_del** function can be used to delete a visitor record. The visitor can only be deleted if no visit records exist for the visitor.

_api\_vis\_del( visitor\_ser );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visitor\_ser | integer | The unique _visitor\_ser_ value for the visitor record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid visitor\_ser |
| -2 | Visit records exist for this visitor |
| 1 | Success |

  1.
### Clear Visitor spare fields

Visitor records contain a number of spare fields which are available for customer use. The **api\_vis\_spareflds\_clr** function can be used to wipe the spare field values for an existing Visitor record.

_api\_vis\_spareflds\_clr( visitor\_ser );_

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visitor\_ser | integer | The unique _visitor\_ser_ value for the Visitor record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid visitor\_ser |
| 0 | Data update error |
| 1 | Success |

  1.
### Set or Change Visitor spare fields

Visitor records contain a number of spare fields which are available for customer use. The **api\_vis\_spareflds\_set** function can be used to set or change the spare fields for an existing visitor record.

_(Visitor spare fields can also be changed using the_ [api\_vis\_upd](#Change_visitor) _procedure.)_

_api\_vis\_spareflds\_set( visitor\_ser, char1, char2, char3, char4,_

_char5, char6, char7, char8);_

Parameter values are checked against any constraints which might be in place. If a value is not NULL, it is validated and stored. If the value is NULL, the existing spare field value is not modified.

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visitor\_ser | integer | The unique _visitor\_ser_ value for the visitor record |
| char1 | char(40) | visitor record spare character field 1 |
| char2 | char(40) | visitor record spare character field 2 |
| char3 | char(40) | visitor record spare character field 3 |
| char4 | char(40) | visitor record spare character field 4 |
| char5 | char(40) | visitor record spare character field 5 |
| char6 | char(40) | visitor record spare character field 6 |
| char7 | char(40) | visitor record spare character field 7 |
| char8 | char(40) | visitor record spare character field 8 |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid visitor\_ser |
| -2 | The value for &#39;char1&#39; is invalid |
| -3 | The value for &#39;char2&#39; is invalid |
| -4 | The value for &#39;char3&#39; is invalid |
| -5 | The value for &#39;char4&#39; is invalid |
| -6 | The value for &#39;char5&#39; is invalid |
| -7 | The value for &#39;char6&#39; is invalid |
| -8 | The value for &#39;char7&#39; is invalid |
| -9 | The value for &#39;char8&#39; is invalid |
| 1 | Success, any new values are stored |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

  1.
### Set or Change Visitor dynamic fields

Customers can add additional dynamic fields for Visitor records using the AC2000 workstation interface. These fields can be a mixture of integers, strings (of 80, 40 or 20 characters in length), date fields, checkboxes and dropdown lists.

The **api\_vis\_userfld\_set** function can be used to set or change the values of these fields.

_api\_vis\_userfld\_set( visitor\_ser, field\_name, field\_value );_

The _field\_name_ value is the string value of the label associated with the field at creation time. Each dynamic field should have a unique label to avoid setting the value of more than one field when this function executes.

Values must adhere to any constraints that have been configured for the field e.g. maximum and minimum string lengths, maximum and minimum integer values and uniqueness.

For checkbox fields a value of either &#39;Y&#39; or 1 will set the checkbox, while a value of &#39;N&#39; or 0 will clear it.

For dropdown lists, any values provided must already exist in the list of available items that have been configured for that dropdown field.

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visitor\_ser | integer | The unique _visitor\_ser_ value for the visitor record |
| field\_name | char(32) | field name - the value of the label associated with the field |
| field\_value | (variable) | field value - this will vary depending on the field type of the dynamic field i.e. char(), date, integer etc. |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid visitor\_ser |
| -2 | The field name was not found |
| -3 | The field value is outside the acceptable range |
| -4 | The field value does not match the format specified for the field |
| -5 | The field is marked as unique and a duplicate value already exists |
| -6 | Failed to update the field value |
| 1 | Success, the field value was stored |

  1.
### Add a Visit record

The **api\_vst\_add** function can be used to create a new visit record for a visitor.

_api\_vst\_add( visitor\_ser, personnel\_ser, reason,_

_card\_form\_desc, acc\_lev\_desc, gtz\_desc, start\_time, end\_time );_

When a visitor record has been successfully added, a _visit\_ser_ value is returned. This is the unique identifier for this record on the AC2000 system and should be stored for future use.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visitor\_ser | integer | The unique _visitor\_ser_ value for the visitor record |
| personnel\_ser | integer | The unique _personnel\_ser_ of the person sponsoring the visitor |
| reason | char(80) | The purpose of the visit |
| card\_form\_desc | char(20) | The format of the card which will be assigned to the visitor |
| acc\_lev\_desc | char(30) | The access level to be applied to the visitors card |
| gtz\_desc | char(20) | The timezone during which the visitors card is valid |
| start\_time | datetime | The start time for the visit |
| end\_time | datetime | The end time for the visit |

The _card\_form\_desc_, _access_\__level_ and _timezone_ values should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

The access level must be assigned to the card\_format

The start and end times must be valid for the card format.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid visitor\_ser |
| -2 | Invalid personnel\_ser |
| -3 | Reason is null |
| -4 | Invalid start time |
| -5 | Duplicate visit for this visitor (i.e. same start time) |
| -6 | Invalid end time (null or before start time) |
| -7 | Invalid card format |
| -8 | Invalid access level |
| -9 | Invalid access level for the specified card format |
| -10 | Invalid timezone |
| -11 | Invalid end time (exceeds limits for card format) |
| \&gt;0 | success (value=visit\_ser) |

  1.
### Change a Visit record

The **api\_vst\_upd** function can be used to change an existing visit record.

_api\_vst\_upd( visit\_ser, personnel\_ser, visit\_reason, card\_form\_desc, acc\_lev\_desc, gtz\_desc, start\_time, end\_time, status );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **visit\_ser** | integer | The unique _visit\_ser_ value for the visit record |
| personnel\_ser | integer | The unique _personnel\_ser_ of the person sponsoring the visitor |
| reason | char(80) | The purpose of the visit |
| card\_form\_desc | char(20) | The format of the card which will be assigned to the visitor |
| acc\_lev\_desc | char(30) | The access level to be applied to the visitors card |
| gtz\_desc | char(20) | The timezone during which the visitors card is valid |
| start\_time | datetime | The start time for the visit |
| end\_time | datetime | The end time for the visit |
| status | char(1) | The card status |

**Highlighted** parameters are mandatory, the others can be _NULL._

If a value is NULL then the value previously stored in the visit record will be used in its place, allowing the user to specify just the values to be changed instead of the complete list.

The _card\_form\_desc_, _access_\__level_ and _timezone_ values should exactly match the values stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

The access level value must be assigned to the card\_format.

The _start\_time_ and _end\_time_ values must be valid for the card format.

The card format value cannot be changed if a visit card has already been validated.

The _status_value must be valid – refer to the [_Card Status codes_](#Card_status_codes) list for possible status values.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid visitor\_ser |
| -2 | Invalid personnel\_ser |
| -3 | Reason is null |
| -4 | Invalid start time |
| -5 | Duplicate visit for this visitor (i.e. same start time) |
| -6 | Invalid end time (null or before start time) |
| -7 | Invalid card format |
| -8 | Invalid access level |
| -9 | Invalid access level for the card format |
| -10 | Invalid timezone |
| -11 | Invalid end time (exceeds limits for card format) |
| -12 | Invalid status value |
| \&gt;0 | success (value=visit\_ser) |

  1.
### Delete a Visit record

The **api\_vst\_del** function can be used to delete a visit record. A visit can only be deleted if a card has not been issued for it.

_api\_vst\_del( visit\_ser );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visit\_ser | integer | The unique _visitor\_ser_ value for the visit record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid visit\_ser or a card has been assigned for the visit |
| 1 | Success |

  1.
### Validate a Visit ID Card

The **api\_vst\_val** function can be used to validate an ID Card for a visit.

_api\_vst\_val( visit\_ser, hotstamp\_num, card\_num );_

This function validates (activates) a visit ID card using the supplied hotstamp and card number. Note this can only be done for card formats which are readable and do not automatically generate card numbers.

If the _hotstamp\_num_ value is NULL, the function will attempt to use an existing hotstamp number for the visit (e.g. an auto-generated hotstamp number).

If the _hotstamp\_num_ value is _not_ NULL and the hotstamp number has been auto-generated during _api\_vst\_add_ or _api\_vst\_upd_ function calls, the supplied value must match the previously auto-generated one.

Card numbers must be specified in hexadecimal format and their length must match the number of bits used in the system configuration. The hexadecimal values must be preceded by leading zeros to fill the values to their expected length.

E.g. the decimal 32-bit card number **16519851** when converted to hex is &#39; **FC12AB&#39;**. When expanded to its full 32-bit value this will give a card\_num value of &#39; **00FC12AB&#39;.**

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visit\_ser | integer | The unique _visit\_ser_ value for the visit record |
| hotstamp\_num | integer | The visit ID cards hotstamp number |
| card\_num | char(64) | The visit ID card number (hexadecimal with leading zeros) |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid visit\_ser |
| -2 | Invalid _visitor\_ser_ found for this visit record |
| -3 | The card format is non-readable |
| -4 | The card format auto-generates card numbers |
| -5 | The hotstamp number is invalid or does not match the auto-generated value |
| -6 | The card number is invalid |
| -7 | The visit ID card has already been validated |
| 1 | Success |

  1.
### Return a Visit ID Card

The **api\_vst\_ret** function can be used to return (deactivate) a Visit ID Card.

_api\_vst\_ret( visit\_ser, return\_code );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visit\_ser | integer | The unique _visit\_ser_ value for the visit record |
| return\_code | char(1) | Card return code |

The Card Return Code can be one of the following

| **Code** | **Description** |
| --- | --- |
| F | Faulty Card |
| L | Lost |
| S | Stolen |
| P | Replaced |
| R | Returned |
| X | Expired |
| C | Changed |
| N | Not Returned |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | The visit does not have a card assigned |
| -2 | The visit ID card has already been returned |
| -3 | Invalid card return code (see table above) |
| 1 | Success |

1.
## **Vehicle functions**

  1.
### Add a new Vehicle Make (Manufacturer) record

The **api\_veh\_make\_add** function can be used to create a new vehicle manufacturer record.

_api\_veh\_make\_add( make\_desc );_

When a vehicle manufacturer record has been successfully added, a _make\_num_ value is returned. This is the unique identifier for this vehicle make record on the AC2000 system.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| make\_desc | char(30) | The vehicle make (manufacturer) description |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid value for make description (NULL or blank) |
| -2 | Duplicate value for make description |
| -3 | Record creation failed |
| \&gt;0 | Success, the number of the new vehicle manufacturer record |

  1.
### Change a Vehicle Make (Manufacturer) record

The **api\_veh\_make\_upd** function can be used to change an existing vehicle manufacturer record.

_api\_veh\_make\_upd( cur\_make\_desc, new\_make\_desc );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| cur\_make\_desc | char(30) | The vehicle make (manufacturer) description |
| new\_make\_desc | char(30) | The new make description |

The _cur\_make\_desc_ value must exactly match the value stored on the AC2000 system (e.g. the value used when creating the record with the [_api\_veh\_make\_add_](#Add_vehicle_make) function).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid current make description |
| -2 | Invalid new make description (NULL or blank) |
| -3 | Duplicate – The new make description already exists |
| 1 | Success, the manufacturer record was changed |

  1.
### Delete a Vehicle Make (Manufacturer) record

The **api\_veh\_make\_del** function can be used to delete an existing vehicle manufacturer record.

_api\_veh\_make\_del( make\_desc );_

When deleting a vehicle manufacturer record, any model records associated with the make are also deleted.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| make\_desc | char(30) | The vehicle make (manufacturer) description |

The _make\_desc_ value must exactly match the value stored on the AC2000 system (e.g. the value used when creating the record with the [_api\_veh\_make\_add_](#Add_vehicle_make) function).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid value for make description (NULL, blank or not found) |
| -2 | Unable to delete records as Vehicle records still exist for this manufacturer |
| 1 | Success, the make record and associated model records were deleted |

  1.
### Add a new Vehicle Model record

The **api\_veh\_model\_add** function can be used to create a new vehicle model record for an existing manufacturer.

_api\_veh\_model\_add( make\_desc, model\_desc );_

When a vehicle make record has been successfully added, a _model\_num_ value is returned. This is the unique identifier for this vehicle model record on the AC2000 system.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| make\_desc | char(30) | The vehicle make (manufacturer) description |
| model\_desc | char(30) | The vehicle model description |

The _make\_desc_ value must exactly match the value stored on the AC2000 system (e.g. the value used when creating the record with the [_api\_veh\_make\_add_](#Add_vehicle_make) function).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid value for make description (NULL, blank or not found) |
| -2 | Invalid value for model description (NULL or blank) |
| -3 | Duplicate value for model description |
| -4 | Record creation failed |
| \&gt;0 | Success, the number of the new vehicle model record |

  1.
### Change a Vehicle Model record

The **api\_veh\_model\_upd** function can be used to change an existing vehicle model record.

_api\_veh\_model\_upd( make\_desc, cur\_model\_desc, new\_model\_desc );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| make\_desc | char(30) | The vehicle make description |
| cur\_model\_desc | char(30) | The current vehicle model description |
| new\_model\_desc | char(30) | The new model description |

The _make\_desc_ and _cur\_model\_desc_ values must exactly match the values stored on the AC2000 system (e.g. the values used when creating the record with the [_api\_veh\_model\_add_](#Add_vehicle_model) function).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid make description (NULL, blank or not found) |
| -2 | Invalid current model description (NULL, blank or not found) |
| -3 | Invalid new model description (NULL or blank) |
| -4 | Duplicate – The new model description already exists for this make |
| 1 | Success, the model record was changed for this make |

  1.
### Delete a Vehicle Model record

The **api\_veh\_model\_del** function can be used to delete an existing model record for a vehicle manufacturer.

_api\_veh\_model\_del( make\_desc, model\_desc );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| make\_desc | char(30) | The vehicle make (manufacturer) description |
| model\_desc | char(30) | The vehicle model description |

The _make\_desc_ and _cur\_model\_desc_ values must exactly match the values stored on the AC2000 system (e.g. the values used when creating the record with the [_api\_veh\_model\_add_](#Add_vehicle_model) function).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid value for make description |
| -2 | Invalid value for model description |
| -3 | Unable to delete as Vehicle records still exist for this make and model |
| 1 | Success, the model was deleted for this vehicle make |

  1.
### Add a new Vehicle record

The **api\_veh\_add** function can be used to create a new vehicle record.

_api\_veh\_add(reg\_num, make\_desc, model\_desc, colour,_

_veh\_desc, manu\_date, veh\_test\_date, curr\_miles,_

_fuel\_type\_desc, engine\_size, has\_obs\_lights, owner\_name,_

_comp\_id, address1, address2, postcode, tel\_num,_

_card\_form\_desc, auth\_num, rf\_issue\_desc, charge,_

_start\_date, expiry\_date, acc\_lev\_desc, gtz\_desc, pin,_

_char1, char2, char3, char4, char5, char6, char7, char8,_

_num1, num2, num3, num4, date1, date2, date3, date4 );_

When a vehicle record has been successfully added, a _vehicle\_ser_ value is returned. This is the unique identifier for this vehicle record on the AC2000 system.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| reg\_num | char(20) | Vehicle registration number |
| make\_desc | char(30) | The vehicle make (manufacturer) description |
| model\_desc | char(30) | The vehicle model description |
| colour | char(20) | Vehicle colour |
| veh\_desc | char(30) | Vehicle description |
| manu\_date | date | Manufacture date |
| veh\_test\_date | date | Vehicle test date |
| curr\_miles | integer | Current mileage |
| fuel\_type\_desc | char(30) | Fuel type description |
| engine\_size | char(30) | Engine size |
| has\_obs\_lights | char(1) | Has obstruction lights? |
| owner\_name | char(60) | Vehicle owner |
| comp\_id | char(8) | Company ID |
| address1 | char(60) | Address 1 |
| address2 | char(60) | Address 2 |
| postcode | char(20) | Postcode |
| tel\_num | char(20) | Contact telephone number |
| card\_form\_desc | char(20) | Card format description |
| auth\_num | integer | Authoriser |
| rf\_issue\_desc | char(20) | Reason-for-issue description |
| charge | integer | Issue charge |
| start\_date | date | Start date |
| expiry\_date | date | Expiry date |
| acc\_lev\_desc | char(30) | Access level description |
| gtz\_desc | char(20) | Timezone description |
| pin | char(9) | Pin code for the vehicle card (digits 0-9) |
| char1 | char(30) | Spare character field 1 (available for customer use) |
| char2 | char(30) | Spare character field 2 (available for customer use) |
| char2 | char(30) | Spare character field 3 (available for customer use) |
| char4 | char(30) | Spare character field 4 (available for customer use) |
| char5 | char(30) | Spare character field 5 (available for customer use) |
| char6 | char(30) | Spare character field 6 (available for customer use) |
| char7 | char(30) | Spare character field 7 (available for customer use) |
| char8 | char(30) | Spare character field 8 (available for customer use) |
| num1 | integer | Spare number field 1 (available for customer use) |
| num2 | integer | Spare number field 2 (available for customer use) |
| num3 | integer | Spare number field 3 (available for customer use) |
| num4 | integer | Spare number field 4 (available for customer use) |
| date1 | date | Spare date field 1 (available for customer use) |
| date2 | date | Spare date field 2 (available for customer use) |
| date3 | date | Spare date field 3 (available for customer use) |
| date4 | date | Spare date field 4 (available for customer use) |

The _make\_desc and model\_desc_ values should exactly match the values already stored on the AC2000 system_,_

_The comp\_id, card\_form\_desc, acc\_lev\_desc and gtz\_desc_ values should exactly match the values already stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

The _fuel\_type\_desc_ and _veh\_test\_date_ values are optional and may be set to NULL if not required.

The _start\_date_ and _expiry\_date_ values must be valid for the card format (_card\_form\_desc_)

If a _veh\_test\_date_ value is supplied and the system is configured to perform _mot\_checks_ then the _expiry\_date_ value supplied must be less than or equal to the _veh\_test\_date_ value.

The _auth\_num_ parameter can be null if the system is not configured for authorisers, otherwise it must be the number of a valid authoriser.

The _rf\_issue\_desc_ and _charge_ parameters can be NULL if charging is not enabled on the system, otherwise theymust exactly match values already configured on the AC2000 system.

The _has\_obs\_lights_ value default is &#39;_N_&#39; (No) if the value supplied is anything other than &#39;_Y_&#39; (Yes).

Spare field values must observe any constraints that have been configured for the fields.

The _pin_ value can be NULL in which case a random pin value will be generated.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid registration number |
| -2 | Duplicate registration number |
| -3 | Invalid value for make description (NULL, blank or not found) |
| -4 | Invalid value for model description (NULL or blank) |
| -5 | Invalid value for colour |
| -6 | Invalid fuel type |
| -7 | Invalid vehicle owner name |
| -8 | Invalid company id |
| -9 | Invalid card format description |
| -10 | Invalid access level description |
| -11 | Invalid access level for the specified card format |
| -12 | Invalid timezone description |
| -13 | Invalid pin code – e.g. blank, invalid character, all 0&#39;s or all 9&#39;s |
| -14 | Invalid start date (NULL or earlier than today) |
| -15 | Invalid expiry date when the vehicle test date (_veh\_test\_date_) is present, mot checks are enabled on the system and the expiry date is later than the vehicle test date |
| -16 | Invalid start or expiry date for the specified card format |
| -17 | Invalid authoriser (_auth\_num_) when authorisers are enabled on the system |
| -18 | Invalid reason for issue (_rf\_issue\_desc_) when charging is enabled on the system |
| -19 | Invalid charge amount (_charge_) when charging is enabled on the system |
| -20 | Spare field &#39;char1&#39; is invalid |
| -21 | Spare field &#39;char2&#39; is invalid |
| -22 | Spare field &#39;char3&#39; is invalid |
| -23 | Spare field &#39;char4&#39; is invalid |
| -24 | Spare field &#39;char5&#39; is invalid |
| -25 | Spare field &#39;char6&#39; is invalid |
| -26 | Spare field &#39;char7&#39; is invalid |
| -27 | Spare field &#39;char8&#39; is invalid |
| -28 | Spare field &#39;num1&#39; is invalid |
| -29 | Spare field &#39;num2&#39; is invalid |
| -30 | Spare field &#39;num3&#39; is invalid |
| -31 | Spare field &#39;num4&#39; is invalid |
| -32 | Spare field &#39;date1&#39; is invalid |
| -33 | Spare field &#39;date2&#39; is invalid |
| -34 | Spare field &#39;date3&#39; is invalid |
| -35 | Spare field &#39;date4&#39; is invalid |
| \&gt;0 | Success (the return value is vehicle\_ser of the new vehicle record |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

This function will strip leading and trailing blank characters from each character string. If a resulting string is empty and it is possible to do so then NULL is stored instead.

  1.
### Change a Vehicle record

The **api\_veh\_upd** function can be used to change an existing vehicle record.

_api\_veh\_upd(vehicle\_ser, reg\_num, make\_desc, model\_desc,_

_colour, veh\_desc, manu\_date, veh\_test\_date, curr\_miles, fuel\_type\_desc, engine\_size, has\_obs\_lights, owner\_name,_

_comp\_id, address1, address2, postcode, tel\_num,_

_card\_form\_desc, auth\_num, status, rf\_issue\_desc, charge,_

_start\_date, expiry\_date, acc\_lev\_desc, gtz\_desc, pin,_

_char1, char2, char3, char4, char5, char6, char7, char8,_

_num1, num2, num3, num4, date1, date2, date3, date4);_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| **vehicle\_ser** | integer | The unique vehicle\_ser for the vehicle record |
| reg\_num | char(20) | Vehicle registration number |
| make\_desc | char(30) | The vehicle make (manufacturer) description |
| model\_desc | char(30) | The vehicle model description |
| colour | char(20) | Vehicle colour |
| veh\_desc | char(30) | Vehicle description |
| manu\_date | date | Manufacture date |
| veh\_test\_date | date | Vehicle test date |
| curr\_miles | integer | Current mileage |
| fuel\_type\_desc | char(30) | Fuel type description |
| engine\_size | char(30) | Engine size |
| has\_obs\_lights | char(1) | Has obstruction lights? |
| owner\_name | char(60) | Vehicle owner |
| comp\_id | char(8) | Company ID |
| address1 | char(60) | Address 1 |
| address2 | char(60) | Address 2 |
| postcode | char(20) | Postcode |
| tel\_num | char(20) | Contact telephone number |
| card\_form\_desc | char(20) | Card format description |
| auth\_num | integer | Authoriser |
| status | char(1) | Card status |
| rf\_issue\_desc | char(20) | Reason-for-issue description |
| charge | integer | Issue charge |
| start\_date | date | Start date |
| expiry\_date | date | Expiry date |
| acc\_lev\_desc | char(30) | Access level description |
| gtz\_desc | char(20) | Timezone description |
| pin | char(9) | Pin code for the vehicle card (digits 0-9) |
| char1 | char(30) | Spare character field 1 (available for customer use) |
| char2 | char(30) | Spare character field 2 (available for customer use) |
| char2 | char(30) | Spare character field 3 (available for customer use) |
| char4 | char(30) | Spare character field 4 (available for customer use) |
| char5 | char(30) | Spare character field 5 (available for customer use) |
| char6 | char(30) | Spare character field 6 (available for customer use) |
| char7 | char(30) | Spare character field 7 (available for customer use) |
| char8 | char(30) | Spare character field 8 (available for customer use) |
| num1 | integer | Spare number field 1 (available for customer use) |
| num2 | integer | Spare number field 2 (available for customer use) |
| num3 | integer | Spare number field 3 (available for customer use) |
| num4 | integer | Spare number field 4 (available for customer use) |
| date1 | date | Spare date field 1 (available for customer use) |
| date2 | date | Spare date field 2 (available for customer use) |
| date3 | date | Spare date field 3 (available for customer use) |
| date4 | date | Spare date field 4 (available for customer use) |

**Highlighted** parameters are mandatory, the others can be _NULL._

Other than the mandatory parameters, if any of the values provided is NULL, the existing stored vehicle value will be used instead. This allows a single value or a subset of values to be supplied for the update operation instead of having to provide the full data set.

The _make\_desc and model\_desc_ values should exactly match the values stored on the AC2000 system.

The _comp\_id, card\_form\_desc, acc\_lev\_desc and gtz\_desc_ values should exactly match the values already stored on the AC2000 system however if the unique AC2000 numeric ids for these fields are known they can be used instead (they must be supplied as _numeric strings_).

The _fuel\_type\_desc_ and _veh\_test\_date_ values are optional and may be set to NULL if not required.

The _start\_date_ and _expiry\_date_ values must be valid for the card format (_card\_form\_desc_)

If a _veh\_test\_date_ value is supplied and the system is configured to perform _mot\_checks_ then the _expiry\_date_ value supplied must be less than or equal to the _veh\_test\_date_ value.

The _auth\_num_ parameter can be null if the system is not configured for authorisers, otherwise it must be the number of a valid authoriser.

The _rf\_issue\_desc_ and _charge_ parameters can be NULL if charging is not enabled on the system, otherwise theymust exactly match values configured on the AC2000 system.

The _has\_obs\_lights_ value default is &#39;_N_&#39; (No) if the value supplied is anything other than &#39;_Y_&#39; (Yes).

Spare field values must observe any constraints that have been configured for the fields.

Refer to the [_Card Status codes_](#Card_status_codes) list for possible Card status values.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid vehicle id (vehicle\_ser) |
| -2 | Invalid registration number (blank or duplicate) |
| -3 | Invalid value for make description (NULL, blank or not found) |
| -4 | Invalid value for model description (NULL or blank) |
| -5 | Invalid value for colour |
| -6 | Invalid fuel type |
| -7 | Invalid vehicle owner name |
| -8 | Invalid company id |
| -9 | Invalid card format description |
| -10 | Invalid access level description |
| -11 | Invalid access level for the specified card format |
| -12 | Invalid timezone description |
| -13 | Invalid pin code – e.g. blank, invalid character, all 0&#39;s or all 9&#39;s |
| -14 | Invalid start date (NULL or earlier than today) |
| -15 | Invalid expiry date when the vehicle test date (_veh\_test\_date_) is present, mot checks are enabled on the system and the expiry date is later than the vehicle test date |
| -16 | Invalid start or expiry date for the vehicles card format |
| -17 | Invalid authoriser (_auth\_num_) when authorisers are enabled on the system |
| -18 | Invalid reason for issue (_rf\_issue\_desc_) when charging is enabled on the system |
| -19 | Invalid charge amount (_charge_) when charging is enabled on the system |
| -20 | Spare field &#39;char1&#39; is invalid |
| -21 | Spare field &#39;char2&#39; is invalid |
| -22 | Spare field &#39;char3&#39; is invalid |
| -23 | Spare field &#39;char4&#39; is invalid |
| -24 | Spare field &#39;char5&#39; is invalid |
| -25 | Spare field &#39;char6&#39; is invalid |
| -26 | Spare field &#39;char7&#39; is invalid |
| -27 | Spare field &#39;char8&#39; is invalid |
| -28 | Spare field &#39;num1&#39; is invalid |
| -29 | Spare field &#39;num2&#39; is invalid |
| -30 | Spare field &#39;num3&#39; is invalid |
| -31 | Spare field &#39;num4&#39; is invalid |
| -32 | Spare field &#39;date1&#39; is invalid |
| -33 | Spare field &#39;date2&#39; is invalid |
| -34 | Spare field &#39;date3&#39; is invalid |
| -35 | Spare field &#39;date4&#39; is invalid |
| -36 | Invalid value for &#39;status&#39; |
| 0 | Record update failure |
| 1 | Success, the record was changed |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

This function will strip leading and trailing blank characters from each character string. If a resulting string is empty and it is possible to do so then NULL is stored instead.

  1.
### Set or Change Vehicle spare fields

Visitor records contain a number of spare fields which are available for customer use. The **api\_veh\_spareflds\_set** function can be used to set or change the spare fields for an existing vehicle record.

_(Vehicle spare fields can also be changed using the_ [_api\_veh\_upd_](#Change_vehicle) _procedure.)_

_api\_veh\_spareflds\_set( vehicle\_ser, char1, char2, char3, char4,_

_char5, char6, char7, char8, num1, num2, num3, num4, date1,_

_date2, date3, date4);_

Parameter values are checked against any constraints which might be in place. If a value is not NULL, it is validated and stored. If the value is NULL, the existing spare field value is not modified.

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique _vehicle\_ser_ value for the vehicle record |
| char1 | char(30) | vehicle record spare character field 1 |
| char2 | char(30) | vehicle record spare character field 2 |
| char3 | char(30) | vehicle record spare character field 3 |
| char4 | char(30) | vehicle record spare character field 4 |
| char5 | char(30) | vehicle record spare character field 1 |
| char6 | char(30) | vehicle record spare character field 2 |
| char7 | char(30) | vehicle record spare character field 3 |
| char8 | char(30) | vehicle record spare character field 4 |
| num1 | integer | vehicle record spare number field 1 |
| num2 | integer | vehicle record spare number field 2 |
| num3 | integer | vehicle record spare number field 1 |
| num4 | integer | vehicle record spare number field 2 |
| date1 | date | vehicle record spare date field 1 |
| date2 | date | vehicle record spare date field 2 |
| date3 | date | vehicle record spare date field 2 |
| date4 | date | vehicle record spare date field 2 |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid vehicle\_ser |
| -2 | The value for &#39;char1&#39; is invalid |
| -3 | The value for &#39;char2&#39; is invalid |
| -4 | The value for &#39;char3&#39; is invalid |
| -5 | The value for &#39;char4&#39; is invalid |
| -6 | The value for &#39;char5&#39; is invalid |
| -7 | The value for &#39;char6&#39; is invalid |
| -8 | The value for &#39;char7&#39; is invalid |
| -9 | The value for &#39;char8&#39; is invalid |
| -10 | The value for &#39;num1&#39; is invalid |
| -11 | The value for &#39;num2&#39; is invalid |
| -12 | The value for &#39;num3&#39; is invalid |
| -13 | The value for &#39;num4&#39; is invalid |
| -14 | The value for &#39;date1&#39; is invalid |
| -15 | The value for &#39;date2&#39; is invalid |
| -16 | The value for &#39;date3&#39; is invalid |
| -17 | The value for &#39;date4&#39; is invalid |
| 0 | Record update error |
| 1 | Success, any new values are stored |

Spare fields may be marked as mandatory and/or unique. An invalid spare field result may occur if either (a) the value for a mandatory field is blank or null, or (b) a non-null value for a unique field is not unique.

  1.
### Clear Vehicle spare fields

Vehicle records contain a number of spare fields which are available for customer use. The **api\_veh\_spareflds\_clr** function can be used to wipe the spare field values for an existing Vehicle record.

_api\_veh\_spareflds\_clr( vehicle\_ser );_

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique _vehicle\_ser_ value for the Vehicle record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid vehicle\_ser |
| 0 | Data update error |
| 1 | Success |

  1.
### Set or Change Vehicle dynamic fields

Customers can add additional dynamic fields for Vehicle records using the AC2000 workstation interface. These fields can be a mixture of integers, strings (of 80, 40 or 20 characters in length), date fields, checkboxes and dropdown lists.

The **api\_veh\_userfld\_set** function can be used to set or change the values of these fields.

_api\_veh\_userfld\_set( vehicle\_ser, field\_name, field\_value );_

The _field\_name_ value is the string value of the label associated with the field at creation time. Each dynamic field should have a unique label to avoid setting the value of more than one field when this function executes.

Values must adhere to any constraints that have been configured for the field e.g. maximum and minimum string lengths, maximum and minimum integer values and uniqueness.

For checkbox fields a value of either &#39;Y&#39; or 1 will set the checkbox, while a value of &#39;N&#39; or 0 will clear it.

For dropdown lists, any values provided must already exist in the list of available items that have been configured for that dropdown field.

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique _vehicle\_ser_ value for the vehicle record |
| field\_name | char(32) | field name - the value of the label associated with the field |
| field\_value | (variable) | field value - this will vary depending on the field type of the dynamic field i.e. char(), date, integer etc |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid vehicle\_ser |
| -2 | The field name was not found |
| -3 | The field value is outside the acceptable range |
| -4 | The field value does not match the format specified for the field |
| -5 | The field is marked as unique and a duplicate value already exists |
| -6 | Failed to update the field value |
| 1 | Success, the field value was stored |

  1.
### Delete a Vehicle record

The **api\_veh\_del** function can be used to delete an existing vehicle record. The vehicle can only be deleted if no card has been issued for it.

_api\_veh\_del( vehicle\_ser );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique _vehicle\_ser_ value for the vehicle record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| 0 | Invalid vehicle\_ser, either not found or a card has been issued for the vehicle |
| 1 | Success, the vehicle was deleted |

  1.
###

  1.
### Validate a Vehicle ID Card

The **api\_veh\_val** function can be used to validate an ID Card for a vehicle.

_api\_veh\_val( vehicle\_ser, hotstamp\_num, card\_num );_

This function validates (activates) a vehicle ID card using the supplied hotstamp and card number. Note this can only be done for card formats which are readable and do not automatically generate card numbers.

If the _hotstamp\_num_ value is NULL, the function will attempt to use an existing hotstamp number for the vehicle (e.g. an auto-generated hotstamp number).

If the _hotstamp\_num_ value is _not_ NULL and the hotstamp number has been auto-generated during _api\_veh\_add_ or _api\_veh\_upd_ function calls, the supplied value must match the previously auto-generated one.

Card numbers must be specified in hexadecimal format and their length must match the number of bits used in the system configuration. The hexadecimal values must be preceded by leading zeros to fill the values to their expected length.

e.g. the decimal 32-bit card number **16519851** when converted to hex is &#39; **FC12AB&#39;**. When expanded to its full 32-bit value this will give a card\_num value of &#39; **00FC12AB&#39;.**

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique _vehicle\_ser_ value for the vehicle record |
| hotstamp\_num | integer | The vehicle ID cards hotstamp number |
| card\_num | char(64) | The vehicle ID card number (hexadecimal with leading zeros) |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | The vehicle\_ser was not found |
| -2 | The card format is non-readable |
| -3 | The card format auto-generates card numbers |
| -4 | The hotstamp number is invalid or does not match the auto-generated value |
| -5 | The card number is invalid |
| -6 | The vehicle already has a card assigned |
| 1 | Success |

  1.
### Return a Vehicle ID Card

The **api\_veh\_ret** function can be used to return (deactivate) a Vehicle ID Card.

_api\_veh\_ret( vehicle\_ser, return\_code );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique _vehicle\_ser_ value for the vehicle record |
| return\_code | char(1) | Card return code |

The Card Return Code can be one of the following

| **Code** | **Description** |
| --- | --- |
| F | Faulty Card |
| L | Lost |
| S | Stolen |
| P | Replaced |
| R | Returned |
| X | Expired |
| C | Changed |
| N | Not Returned |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid vehicle\_ser |
| -2 | The vehicle does not have an ID card issued |
| -3 | Invalid card return code (see table above) |
| 1 | Success |

  1.
### Add an Approved Driver to a Vehicle

The **api\_veh\_driver\_add** function can be used to assign an existing cardholder as an approved driver to an existing vehicle.

_api\_veh\_driver\_add( vehicle\_ser, personnel\_ser );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique _vehicle\_ser_ for the vehicle record |
| personnel\_ser | integer | The unique _personnel\_ser_ for the personnel record |

The _vehicle\_ser_ and _personnel\_ser_ values will be those value returned following successful calls to the [_api\_per\_add_](#Add_a_Personnel_record) and [_api\_veh\_add_](#Add_vehicle) functions.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid vehicle\_ser value |
| -2 | Invalid personnel\_ser value |
| -3 | Duplicated, the personnel\_ser has already been approved as a driver to this vehicle |
| -4 | Data write error |
| 1 | Success, the driver was approved for the vehicle |

  1.
### Remove an Approved Driver from a Vehicle

The **api\_veh\_driver\_del** function can be used to remove a cardholder as an approved driver for an existing vehicle.

_api\_veh\_driver\_del( vehicle\_ser, personnel\_ser );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique _vehicle\_ser_ for the vehicle record |
| personnel\_ser | integer | The unique _personnel\_ser_ for the personnel record |

The _vehicle\_ser_ and _personnel\_ser_ values will be those value returned following successful calls to the [_api\_per\_add_](#Add_a_Personnel_record) and [_api\_veh\_add_](#Add_vehicle) functions.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid vehicle\_ser value |
| -2 | Invalid personnel\_ser value |
| -3 | The personnel\_ser is not an approved driver for this vehicle |
| 1 | Success, the driver approval was removed |

  1.
### Find a Vehicle Make (Manufacturer) ID

The **api\_veh\_get\_make** function can be used to determine a vehicle manufacturers unique ID.

_api\_veh\_get\_make( make\_desc );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| make\_desc | char(30) | The vehicle make (manufacturer) description |

The _make\_desc_ value must exactly match the value stored on the AC2000 system (e.g. the value used when creating the record with the [_api\_veh\_make\_add_](#Add_vehicle_make) function).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid value for make description (NULL or blank) |
| -2 | Vehicle make not found |
| \&gt;0 | The unique vehicle _make\_num_ value |

  1.
### Find a Vehicle Model ID

The **api\_veh\_get\_model** function can be used to determine a vehicle models unique ID.

_api\_veh\_get\_model( make\_num, model\_desc );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| make\_num | integer | The unique vehicle _make\_num_ value |
| model\_desc | char(30) | The vehicle model description |

The _model\_desc_ value must exactly match the value stored on the AC2000 system (e.g. the value used when creating the record with the [_api\_veh\_model\_add_](#Add_vehicle_model) function).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid value for make\_num description (NULL or blank) |
| -2 | Invalid value for model\_desc (NULL or blank) |
| -3 | Vehicle model not found |
| \&gt;0 | The unique vehicle _model\_num_ value |

  1.
### Find a Vehicle ID

The **api\_veh\_get\_ser** function can be used to determine a vehicles unique vehicle\_ser value based on its registration number.

_api\_veh\_get\_ser( reg\_num );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| reg\_num | char(30) | The unique vehicle registration number |

The _reg\_num_ value must exactly match the value stored on the AC2000 system (e.g. the value used when creating the record with the [_api\_veh\_add_](#Add_vehicle) function).

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid value for vehicle registration (NULL or blank) |
| -2 | Vehicle registration not found |
| \&gt;0 | The unique vehicle ID value |

  1.
### Find a Vehicle Registration

The **api\_veh\_get\_reg** function can be used to determine a vehicles unique registration number based on its unique vehicle\_ser value.

_api\_veh\_get\_reg( vehicle\_ser );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique _vehicle\_ser_ for the vehicle record |

The vehicle\_ser value will be the value returning following a successful call to the [_api\_veh\_add_](#Add_vehicle) function.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| NULL | The vehicle\_ser was not found |
| Value | A char(30) value representing the vehicle registration |

  1.
### Find a Vehicle Fuel ID

The **api\_veh\_get\_fuel** function can be used to determine the ID for a vehicle fuel description.

_api\_veh\_get\_fuel( fuel\_desc );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| fuel\_desc | char(30) | The vehicle fuel description |

The _fuel\_desc_ value must exactly match the value stored on the AC2000 system.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid value for fuel\_desc (NULL or blank) |
| -2 | Fuel description not found |
| \&gt;0 | The unique fuel id |

1.
## **Image and Signature functions**

  1.
### Attach a photograph to a Personnel or Visitor record

The **api\_img\_create** function can be used to store a photo image for either a personnel or a visitor record.

_api\_img\_create( personnel\_ser, b64data );_

The function accepts a complete base64-encoded JPEG image as data, converts it to back to jpeg format and saves the result against the personnel or visitor record.

Parameter list

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ or _visitor\_ser_ value for the record |
| b64data | char(n) | base64-encoded jpeg signature data |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser or visitor\_ser |
| -2 | Photo image creation failed (no privilege or base64 conversion failed) |
| -3 | Failed to attach the photo image to the personnel or visitor record |
| 0 | Invalid jpeg photo image created – too small or empty |
| 1 | Success |

When creating a photo image, any existing image will be deleted first. If creation fails then the record will have no associated photograph. You can use this to remove a photo by calling the function and supplying an empty string as its data.

  1.
### Attach a signature to a Personnel or Visitor Record

The **api\_sig\_create** function can be used to store a signature image for a personnel or visitor record.

_api\_sig\_create( personnel\_ser, b64data );_

The function accepts a complete base64-encoded JPEG image as data, converts it to back to jpeg format and saves the result against the personnel record.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ or _visitor\_ser_ value for the record |
| b64data | char(n) | base64-encoded jpeg signature data |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser or visitor\_ser |
| -2 | Signature image creation failed (no privilege or base64 conversion failed) |
| -3 | Failed to attach the signature image to the personnel or visitor record |
| 0 | Invalid jpeg image created – too small or empty |
| 1 | Success |

When creating a signature, any existing one will be deleted first. If creation fails then the record will have no associated signature. You can use this to remove a signature by calling the function and supplying an empty string as its data.

1.
## **Threat Level functions**

  1.
### Set the System Threat Level

The **api\_thl\_set** function can be used to set the overall threat level for the system.

_api\_thl\_set( threat\_level );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| threat\_level | integer | The threat level value which should be set for the system |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| 0 | Failed to set the system threat level |
| 1 | The threat level was successfully set |

  1.
### Set the Threat Level for a Cardholder or Visitor

The **api\_thl\_per\_set** function can be used to set a threat level value for either a personnel or a visitor record.

_api\_thl\_per\_set( unique\_ser, threat\_level );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| unique\_ser | integer | The unique _personnel\_ser_ or visitor\_ser for the record |
| threat\_level | integer | The threat level value to be assigned |

The _unique\_ser_ value will be the value returned following a successful call to the [_api\_per\_add_](#Add_a_Personnel_record) or [_api\_vis\_add_](#Add_visitor) functions.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid personnel\_ser or visitor\_ser value |
| -2 | Invalid threat level value |
| -3 | Failed to update the threat level for the cardholder or visitor |
| -4 | Failed to create a new threat level record (e.g. for instances where a threat level value was not previously assigned to the cardholder/visitor) |
| 1 | Success, the threat level was changed |

  1.
###

1.
## **Device and Zone functions**

Broadcasts (open/close requests) can be issued to single devices or a range of devices. To broadcast to a range of devices, the devices must be grouped together into Broadcast Zones.

The A2000 system does not maintain any device state information other than the fact that at some point a broadcast was requested for a given device or broadcast zone. If notifications of open and close events are required this can be achieved by wiring up separate inputs (e.g. door contact switches) into the device inputs and configuring open/close event alarms to be triggered by them. It is the responsibility of 3rd party integrators to maintain the persistence of input events.

  1.
### Send an Open or Close broadcast request to a single device

The api\_bc\_req function can be used to broadcast an open or close request to specific device.

_api\_bc\_req( device\_addr, bc\_type, site\_num );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address of the device |
| bc\_type | char(1) | The broadcast type (see below) |
| site\_num | integer | The AC2000 site number |

The device address must be the 5-digit hexadecimal address of a valid device while the operation code is a single character code which dictates the action taken.

The broadcast type (bc\_type) can be one of the following

| **Code** | **Description** |
| --- | --- |
| S | Oneshot a device – momentarily open the device, then close it |
| O | Broadcast Open – send an open request for the lock output, on completion the output remains open |
| C | Broadcast Close – send an close request for the lock output, on completion the output remains closed |

The _site\_num_ value is the site to which the device belongs and is only relevant for multi-site systems. If the value is NULL or omitted, the local site number is implied. A site number other than the local site is only valid for Enterprise Controllers..

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid device address |
| -2 | Invalid broadcast type |
| -3 | User does not have &#39;_Oneshot_&#39; permission for this device |
| -4 | User does not have &#39;_Broadcast_&#39; permission for the device |
| -5 | _site\_num_ is not the local site and the local site is not an Enterprise controller |
| 1 | Success |

For example, to send a momentary open the lock on device 00100.

_select api\_bc\_req( &#39;00100&#39;, &#39;S&#39; );_

To open the lock on device 00200 and have it remain open.

_select api\_bc\_req(&#39;00200,&#39;O&#39;);_

To close the lock on device 00200.

_select api\_bc\_req(&#39;00200&#39;,&#39;C&#39;);_

When oneshot history is enabled, a oneshot history entry is created. When broadcast history is enabled, a single device broadcast entry is created.

  1.
### Send a Broadcast to a specific output on a single device

The **api\_bc\_output** function can be used to send a broadcast open or close request to a specific output on a device.

_api\_bc\_output( device\_addr, bc\_type, output\_num [, site\_num] );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address of the device |
| bc\_type | char(1) | The broadcast type (see below) |
| output\_num | integer | The output number on the device to be triggered |
| site\_num | integer | (Optional) The AC2000 site number |

The device address must be the 5-digit hexadecimal address of a valid device while the operation code is a single character code which dictates the action taken.

The broadcast type (_bc\_type_) can be one of the following

| **Code** | **Description** |
| --- | --- |
| o | Broadcast Open – send an open request for the specified output, on completion the output remains open |
| c | Broadcast Close – send an close request for the specified output, on completion the output remains closed |

The output must exist on the device otherwise the request is ignored.

The _site\_num_ value is the site to which the device zone belongs and is only relevant for multi-site systems. If the value is NULL or omitted, the local site number is implied. A site number other than the local site is only valid for Enterprise Controllers.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid device address |
| -2 | Invalid broadcast type |
| -3 | Invalid output number |
| -4 | The user does not have &#39;_Broadcast_&#39; permission for the device |
| -5 | _site\_num_ is not the local site and the local site is not an Enterprise controller |
| 1 | Success |

For example to open output 4 on device 00100.

_select api\_bc\_output( &#39;00100&#39;, &#39;o&#39;, 4 );_

When broadcast history is enabled, a single device broadcast history entry is created.

  1.
### Send an Open or Close broadcast request to multiple devices

A number of AC2000 devices can be grouped together into &#39;Broadcast Zones&#39;. A single device can be a member of more than one zone.

The **api\_bc\_zone\_send** function can be used to broadcast an open or close request to all devices which are members of a zone.

_api\_bc\_zone\_send( bc\_zone\_num, bc\_action [, site\_num] );_

When a broadcast request has been successfully issued, a _bc\_req\_num_ value is returned. This is the unique identifier for this broadcast request on the AC2000 system.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| bc\_zone\_num | integer | The unique broadcast zone number |
| bc\_action | char(1) | The broadcast action (see below) |
| site\_num | integer | (Optional) The AC2000 site number |

Broadcast zone information can be retrieved using the [api\_bc\_zones](#view_broadcast_zones) view.Broadcast zone member devices can be retrieved using the[api\_bc\_zone\_devices](#view_broadcast_zone_devices)view.

The broadcast type (bc\_action) can be one of the following

| **Code** | **Description** |
| --- | --- |
| O | Broadcast Open – send an open request for the lock output to all devices in the zone, on completion the output remains open |
| C | Broadcast Close – send an close request for the lock output to all devices in the zone, on completion the output remains closed |

The _site\_num_ value is the site to which the broadcast zone belongs and is only relevant for multi-site systems. If the value is NULL or omitted, the local site number is implied. A site number other than the local site is only valid for Enterprise Controllers.

The outputs of the various member devices may be different per device, depending on how each device in the zone has been configured on the AC2000 system.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid broadcast zone number |
| -2 | Invalid broadcast action |
| -3 | Failed to create broadcast request |
| -4 | Unable to use function as data partitioning is enabled |
| -5 | _site\_num_ is not the local site and the local site is not an Enterprise controller |
| \&gt;0 | Success, the unique broadcast request number |

For example to open the broadcast zone with a zone\_num of 2

_select api\_bc\_zone\_send( 2, &#39;O&#39; );_

  1.
### Wait for a multiple device broadcast request to complete

The **api\_bc\_zone\_wait** function waits until a broadcast zone request is complete. The function will time out after a predetermined interval.

_api\_bc\_zone\_wait( bc\_req\_num );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| bc\_req\_num | integer | The unique broadcast request number |

The _bc\_req\_num_ value must exactly match the value stored on the AC2000 system (e.g. the value used when creating the request using the [_api\_bc\_zone\_send_](#Broadcast_multiple_devices) function).

Wait timeout is determined by the configuration option &#39;_BROADCASTTIMEOUT&#39;._

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid broadcast request number |
| 0 | Failed (Timed out) |
| 1 | Success |

For example, to wait for the completion of a broadcast to zone 112

_select api\_bc\_zone\_wait(112);_

  1.
### Lock down Devices in a Lockdown Zone

A number of AC2000 devices can be grouped together into &#39;Lockdown Zones&#39;. A single device can be a member of more than one zone. When a Lockdown zone is activated, access devices in the zone will deny ID card access.

Not all device types can participate in Lockdown zones.

The **api\_ldz\_lock** function will lock down a Lockdown zone.

_api\_ldz\_lock( ld\_zone\_name, reason );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| ld\_zone\_name | char(40) | The unique lockdown zone number |
| reason | char(60) | The reason for locking the zone |

The _zone\_name_ value must exactly match the value stored on the AC2000 system. Lockdown zone information can be retrieved using the [_api\_ld\_zones_](#view_lockdown_zones)view. Zone member devices can be retrieved using the [_api\_ld\_zone\_devices_](#view_lockdown_zone_devices) view.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid lockdown zone name |
| 1 | Success, the lockdown zone lock request was sent |

  1.
### Unlock Devices in a Lockdown Zone

The **api\_ldz\_unlock** function will unlock the devices in a Lockdown zone.

_api\_ldz\_unlock( ld\_zone\_name, reason );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| ld\_zone\_name | char(40) | The unique lockdown zone name |
| reason | char(60) | The reason for unlocking the zone |

The _ldz\_num_ value must exactly match the value stored on the AC2000 system. Lockdown zone information can be retrieved using the [_api\_ld\_zones_](#view_lockdown_zones)view. Zone member devices can be retrieved using the [_api\_ld\_zone\_devices_](#view_lockdown_zone_devices) view.

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Invalid lockdown zone name |
| 1 | Success, the lockdown zone unlock request was sent |

  1.
### Enable or Disable the keypad on Series 700E devices

The **api\_700e\_keypad** function can be used to show or hide the on-screen keyboard for Series 700E Reader devices. This will not work for any other devices.

_api\_700e\_keypad( device\_addr, keypad );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address of the device |
| keypad | char(1) | &#39;Y&#39;=Show the keypad, &#39;N&#39;=Hide it |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | Device is not a Series 700E device |
| -2 | User has no privilege to change the device |
| -3 | Invalid value for _keypad_ – only &#39;Y&#39; or &#39;N&#39; are accepted |
| 1 | Success |

1.
## **Alarm functions**

  1.
### Acknowledge an alarm

The **api\_alm\_ack** function can be used to acknowledge a specific alarm

_api\_alm\_ack( alarm\_num, site\_num, user\_id );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| alarm\_num | integer | The unique alarm number |
| site\_num | integer | The AC2000 site number |
| user\_id | char(30) | The name of the user acknowledging the alarm |

Existing alarms information can be retrieved using the [api\_alarmlog](#view_active_alarms)view.

The _site\_num_ value is the site to which the alarm belongs and is only relevant for multi-site systems. If the value is NULL or omitted, the local site number is implied. A site number other than the local site is only valid for Enterprise Controllers.

The _user\_id_ value is the user who is acknowledging the alarm. If the value is NULL or omitted, the current user is implied

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | The alarm does not exist or has already been acknowledged |
| -2 | The current user does not have &#39;_alarm_&#39; permission for the alarm device |
| -3 | _site\_num_ is not the local site and the local site is not an Enterprise controller |
| 1 | Success, the alarm has been acknowledged |

The function accepts one of the alarm numbers which are present in the results of the [_api\_alarmlog_](#view_active_alarms) view

For example an alarm with an alarm\_num of 100 can be acknowledged as:

_select api\_alm\_ack(100);_

  1.
### Cancel an alarm

The _ **api\_alm\_can** _ function can be used to cancel a specific alarm

_api\_alm\_can( alarm\_num [, site\_num [, user\_id]] );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| alarm\_num | integer | The unique alarm number |
| site\_num | integer | (Optional) The AC2000 site number |
| user\_id | char(30) | (Optional) The name of the user cancelling the alarm |

Existing alarms information can be retrieved using the [api\_alarmlog](#view_active_alarms)view.

The _site\_num_ value is the site to which the alarm belongs and is only relevant for multi-site systems. If the value is NULL or omitted, the local site number is implied. A site number other than the local site is only valid for Enterprise Controllers.

The _user\_id_ value is the user who is cancelling the alarm. If the value is NULL or omitted, the current user is implied

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | The alarm does not exist or has already been cancelled |
| -2 | The current user does not have &#39;_alarm_&#39; permission for the alarm device |
| -3 | _site\_num_ is not the local site and the local site is not an Enterprise controller |
| 1 | Success, the alarm has been cancelled |

The function accepts one of the alarm numbers which are present in the results of the [_api\_alarmlog_](#view_active_alarms) view

For example an alarm with an alarm\_num of 100 can be cancelled as follows:

_select api\_alm\_can(100);_

1.
## **Views and Read functions**

  1.
### Personnel and Card Status

The **api\_person** view returns certain details relating to personnel and includes the ID card status and expiry datetime fields (more comprehensive ID card details can be found in the [api\_id\_cards](#view_id_cards) view).

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique personnel serial number |
| hotstamp\_num | integer | ID Card hotstamp number |
| forename | char(30) | Forename |
| surname | char(30) | Surname |
| payroll\_num | char(20) | Payroll number |
| job\_title | char(48) | Job title |
| expiry\_time | datetime | ID Card Expiry datetime |
| cardstatus | char(1) | ID Card status |
| contact\_num | char(20) | Telephone Number |
| dateofbirth | date | Date of birth |
| site\_num | integer | The home site for this person |
| company\_name | char(40) | The name of the company for person/card combination |
| char1 | char(20) | Spare character field 1 |
| char2 | char(20) | Spare character field 2 |
| char3 | char(20) | Spare character field 3 |
| char4 | char(20) | Spare character field 4 |
| num1 | integer | Spare number field 1 |
| num2 | integer | Spare number field 2 |
| date1 | date | Spare date field 1 |
| date2 | date | Spare date field 2 |
| email\_addr | char(60) | email address |

The _site\_num_ column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

The _job\_title_ value may be truncated if the configuration parameter &#39;_job\_title\_length_&#39; has been created to restrict it.

Refer to the [_Card Status codes_](#Card_status_codes) table for a list of possible Card status values.

The view can be used to get the personnel details for a specified card holder as follows:

_select \* from api\_person_

_where personnel\_ser = 123_

_and hotstamp\_num = 456;_

**Since an individual can have multiple ID Cards for multiple companies, there may be more than one record returned for them.**

  1.
### Cardholder Images

The **api\_get\_face** function can be used to retrieve the facial image for a cardholder if it has been captured and attached to their personnel record.

_api\_get\_face( personnel\_ser );_

This function returns NULL if the image doesn&#39;t exist. Otherwise the facial image is returned in bytea &quot;hex&quot; format. The image&#39;s binary data is returned encoded as 2 hexadecimal digits per byte with the most significant nibble first. The entire data string is preceded by the sequence &#39;\x&#39;.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the personnel record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| NULL | Image not found (Invalid personnel\_ser or image not captured) |
| Image | The personnel image in &#39;bytea&#39; format |

For example the image for personnel\_ser 123 can be requested as follows:

_select api\_get\_face(123);_

If the integration application is unable to handle bytea data, the &#39;_ **encode** _&#39; function can be used to convert the data to either &#39;hex&#39; or &#39;base64&#39; first e.g.

_select encode( api\_get\_face(1), &#39;base64&#39; );_

_select encode( api\_get\_face(1), &#39;hex&#39; );_

**When using the Restful interface, the bytea result can&#39;t be transferred as a json element and must be converted first. The alternative function** [**api\_get\_image**](#Get_image_base64) **can be used with an &#39;exec&#39; operation as it returns the pre-encoded base64 image. Otherwise a &#39;fetch&#39; operation will require a command such as:-**

_select encode( api\_get\_face(123), &#39;base64&#39; );_

  1.
### Base64 Cardholder Images

The **api\_get\_image** function can be used to retrieve the facial image for a cardholder if it has been captured and attached to their personnel record. The Jpeg image is returned as a string in Base64-encoded format.

_api\_get\_image( personnel\_ser );_

This function returns an empty string if the image doesn&#39;t exist.

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique _personnel\_ser_ value for the personnel record |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| NULL | Image not found (Invalid personnel\_ser or image not captured) |
| Image | The Base64-encoded personnel jpeg image |

For example the image for personnel\_ser 123 can be requested as follows:

_select api\_get\_image(123);_

  1.
### ID Cards

The **api\_id\_cards** view returns details related to ID cards configured on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| id\_cards\_ser | integer | The unique card serial number |
| personnel\_ser | integer | The unique personnel serial number |
| comp\_id | char(8) | Company ID |
| card\_format | char(20) | Card format |
| hotstamp\_num | integer | Card Hotstamp number |
| start\_time | datetime | Start time |
| expiry\_time | datetime | Expiry time |
| access\_level | char(30) | Access level |
| timezone | char(20) | Timezone |
| card\_num | char(8) | Card number |
| cardstatus | char(1) | Card status |
| char1 | char(20) | Spare character field 1 |
| char2 | char(20) | Spare character field 2 |
| char3 | char(20) | Spare character field 3 |
| char4 | char(20) | Spare character field 4 |
| num1 | integer | Spare number field 1 |
| num2 | integer | Spare number field 2 |
| time1 | datetime | Spare datetime field 1 |
| time2 | datetime | Spare datetime field 2 |

If a card has not yet been validated, the _card\_num_ and _cardstatus_ values will be null

For returnable cards, cards that have been returned will have a null _card\_num_ value and the _cardstatus_ value will be set to &#39;P&#39;.

Refer to the [_Card Status codes_](#Card_status_codes) list for the possible Card status values.

  1.
### Get Latest Card Swipe

The **api\_get\_last\_swipe** function can be used to determine the _marker\_seq_ value for the most recent card swipe on the system.

This function utilises table indices so is faster than using a statement such as &#39;select max(marker\_seq)&#39; from a swipe view (see below), which may become increasingly slow as the number of records increases.

_api\_get\_last\_swipe();_

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| \&gt;0 | The highest swipe _marker\_seq_ value on the system as a 64-bit integer |

  1.
### Get Total Card Swipes

The **api\_get\_swipe\_count** function can be used to determine the total number of card swipes present on the system.

This function utilises table indices so is faster than using a statement such as &#39;select count(\*)&#39; from a swipe view (see below), which may become increasingly slow as the number of records increases.

_api\_get\_swipe\_count( [type] );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| type | char(3) | (Optional) value for the type of swipe required |

The &#39;_type_&#39; value can be one of the following

| **Value** | **Description** |
| --- | --- |
| &#39;per&#39; | Only Personnel swipes should be included |
| &#39;vis&#39; | Only Visitor swipes should be included |
| &#39;veh&#39; | Only Vehicle swipes should be included |
| &#39;unk&#39; | Only Unknown (&#39;Not-In-System&#39;) swipes should be included |

If &#39;_type_&#39; is omitted or any other value supplied, a total of _all_ available swipes is returned.

Function Return Values

| **Code** | **Description** |
| --- | --- |
| \&gt;=0 | An integer indicating the total number of swipe records available on the system (or of the specified _type_, if a value was provided) |

  1.
### Card Swipes (All)

The **api\_swipe** view returns details of card swipes which have been recorded on the system. This includes Personnel, Visitor and Vehicle swipes as well as those for unrecognised cards (&#39;Not-In-System&#39;)

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| hotstamp\_num | integer | The unique card hotstamp number |
| swipe\_ser | integer | The unique cardholder serial number |
| swipe\_time | datetime | The date and time when the swipe occurred |
| device\_addr | char(5) | The device on which the swipe occurred |
| outcome\_num | integer | The result of the card swipe |
| outcome\_name | char(25) | A brief description of the outcome |
| site\_num | integer | The site where the swipe occurred |
| home\_site | integer | The home site of the card holder |
| marker\_seq | biginteger | The swipe sequence number ( **64-bit integer** ) |

The _site\_num_ and _home\_site_ columns are only relevant for multi-site systems; they will typically have a value of 1 otherwise.

This view is provided so that an integrator can poll for the latest card swipe information. Please do not poll more frequently than once a second as this would have a negative impact on the performance of the AC2000 system. The _swipe\_ser_ field is the cardholder&#39;s unique identifier on AC2000.

This view should be used to pick up card swipes that occur after the 3rd party integration has been started. On start-up the 3rd party software should query and store the latest _marker\_seq_ value, i.e.

_select_ [_api\_get\_last\_swipe()_](#find_latest_swipe)_;_

It should then poll the view periodically, querying for card swipe records where the marker\_seq is greater than that previously recorded max, storing the highest seen marker\_seq value each time, e.g.

_select \* from api\_swipe_

_where marker\_seq \&gt; last\_max\_marker\_seq_

_order by marker\_seq;_

See the [Swipe Outcomes](#view_swipe_outcomes) view for all possible outcomes.

Note:_ **Not-In-System** _ swipes will have a _personnel\_ser_ value of NULL.

  1.
### Personnel Card Swipes

The **api\_per\_swipe** view returns details of card swipes which have been recorded on the system for Personnel. The view can also be read using the alias **api\_card\_swipe** (provided for backwards compatibility). See the [api\_swipe](#view_api_swipes) view for usage details.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| hotstamp\_num | integer | The unique card hotstamp number |
| personnel\_ser | integer | The unique Personnel record serial number |
| swipe\_time | datetime | The date and time when the swipe occurred |
| device\_addr | char(5) | The device on which the swipe occurred |
| outcome\_num | integer | The result of the card swipe |
| outcome\_name | char(25) | A brief description of the outcome |
| site\_num | integer | The site where the swipe occurred |
| home\_site | integer | The home site of the card holder |
| marker\_seq | biginteger | The swipe sequence number ( **64-bit integer** ) |

Note:_ **Not-In-System** _ swipes will have a _personnel\_ser_ value of NULL.

  1.
### Personnel Card Swipes (Detailed)

The **api\_per\_swipe\_detail** view returns the same Personnel card swipe values as those in the **api\_per\_swipe** view along with additional details.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| hotstamp\_num | integer | The unique card hotstamp number |
| personnel\_ser | integer | The unique Personnel record serial number |
| swipe\_time | datetime | The date and time when the swipe occurred |
| device\_addr | char(5) | The device on which the swipe occurred |
| outcome\_num | integer | The result of the card swipe |
| outcome\_name | char(25) | A brief description of the outcome |
| site\_num | integer | The site where the swipe occurred |
| home\_site | integer | The home site of the card holder |
| device\_location | char(80) | Device location |
| forenames | char(30) | Forename(s) |
| surname | char(30) | Surname |
| payroll\_num | char(20) | Payroll number |
| job\_title | char(48) | Job title |
| department | char(20) | Department |
| comp\_id | char(8) | Company code |
| comp\_name | char(40) | Company name |
| marker\_seq | biginteger | The swipe sequence number ( **64-bit integer** ) |

Note:_ **Not-In-System** _ swipes will have a _personnel\_ser_ value of NULL.

  1.
### Visitor Card Swipes

The **api\_vis\_swipe** view returns details of card swipes which have been recorded on the system for Visitors. See the [api\_swipe](#view_api_swipes) view for usage details.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| hotstamp\_num | integer | The unique card hotstamp number |
| visitor\_ser | integer | The unique Visitor record serial number |
| swipe\_time | datetime | The date and time when the swipe occurred |
| device\_addr | char(5) | The device on which the swipe occurred |
| outcome\_num | integer | The result of the card swipe |
| outcome\_name | char(25) | A brief description of the outcome |
| site\_num | integer | The site where the swipe occurred |
| home\_site | integer | The home site of the card holder |
| marker\_seq | biginteger | The swipe sequence number ( **64-bit integer** ) |

  1.
### Vehicle Card Swipes

The **api\_veh\_swipe** view returns details of card swipes which have been recorded on the system for Vehicles. See the [api\_swipe](#view_api_swipes) view for usage details.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| hotstamp\_num | integer | The unique card hotstamp number |
| vehicle\_ser | integer | The unique Vehicle record serial number |
| swipe\_time | datetime | The date and time when the swipe occurred |
| device\_addr | char(5) | The device on which the swipe occurred |
| outcome\_num | integer | The result of the card swipe |
| outcome\_name | char(25) | A brief description of the outcome |
| site\_num | integer | The site where the swipe occurred |
| home\_site | integer | The home site of the card holder |
| marker\_seq | biginteger | The swipe sequence number ( **64-bit integer** ) |

  1.
### Access Levels

The **api\_access\_levels** view returns details related to Access Levels which have been configured on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| access\_level\_num | integer | The unique Access Level number |
| access\_level\_desc | char(30) | The Access Level description |
| part\_num | integer | The partition to which the Access Level belongs |

The _part\_num_ column is only relevant to partitioned systems; it will normally have a value of 1 otherwise (AC2000 system partitioning is outside the scope of this document).

  1.
### RTC Controllers

The **api\_rtc** view returns details related to the RTCs which have been configured on the system. See the [_RTC Server_](#_RTC_Server_(Real) section for a brief description of RTCs.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| rtc\_num | char(2) | The unique RTC number as a hexadecimal string |
| rtc\_description | char(80) | The RTC description |
| site\_num | integer | The site where the RTC is installed |

The _site\_num_ column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

  1.
### Alarm Types

The **api\_alarm** view returns a list of available alarm types.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| alarm\_type\_num | integer | The unique alarm type number |
| alarm\_description | char(20) | A brief description of the alarm |
| auto\_or\_manual\_can | char(1) | Cancellation type (see below) |
| priority | integer | The alarms priority |
| source\_type | char(3) | The source type (originator) of the alarm |

The cancellation type (auto\_or\_manual\_can) can be one of the following

| **Code** | **Description** |
| --- | --- |
| M | Manual cancellation |
| A | Automatic cancellation |

The alarm originator (source\_type) can be one of the following

| **Type** | **Description** |
| --- | --- |
| DEV | Device |
| CDC | The CDC controller |
| RTC | An RTC controller |
| EXT | An external device |
| NCN | An NCN controller |

This view can be used to get a full list of all alarm types as follows:

_select \* from api\_alarm order by alarm\_type\_num;_

Alternatively the view can be used to get details of one specified alarm type as follows:

_select \* from api\_alarm where alarm\_type\_num=6;_

Manual cancellation (M) alarms should be cancelled by the 3rd party integration.

Automatic cancellation (A) alarms should be cancelled by a real-world event

(e.g. &quot;door held&quot; alarms are cancelled when the door is closed).

  1.
### Devices

The **api\_device** view returns details related to the devices which have been configured on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| device\_description | char(80) | The device description |
| readhead\_num | integer | The devices read-head number |
| device\_type\_num | Integer | Device type code |
| device\_type\_name | char(20) | Device type name |
| site\_num | integer | The site where the device is installed |

The _site\_num_ column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

  1.
### Device Input Alarms

The **api\_input** view returns details of the alarms configured on external inputs for devices on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| input\_num | integer | The Input number on the device |
| input\_state | char(1) | The Input state (&#39;O&#39;=Open, &#39;C&#39;=Closed, &#39;T&#39;=Tamper) |
| alarm\_type\_num | integer | Alarm type triggered by the input |
| site\_num | integer | The site where the device is installed |

The _site\_num_ column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

This view can be used to get a full list of all device inputs as follows:

_select \* from api\_input_

_order by device\_addr, input\_num, input\_state;_

Alternatively the view can be used to get details of one specified device input state as follows:

_select \* from api\_alarm where device\_addr=&#39;00F10&#39;_

_and input\_num=0 and input\_state=&#39;O&#39;;_

Device alarms (see [_Alarms overview_](#Alarms_overview)) which are linked directly to a reader outcome rather than an input (e.g. &quot;Lost/Stolen card&quot;) are assumed, so are not present in this view.

A different alarm type (see [_Alarm Types_](#view_alarm_types)) can be configured for each state of an input (Open, Closed, Tamper). For example if input 0 is connected to a door position switch then typically input 0 open would be configured with the &#39;Door forced&#39; alarm and input 0 closed would be configured with the &#39;Door close&#39; alarm.

See the [Swipe Outcomes](#view_swipe_outcomes) view for a list of all possible outcomes.

  1.
### Get Latest Alarm

The **api\_get\_last\_alarm** function can be used to determine the _marker\_seq_ value for the most recent alarm on the system.

This function utilises table indices so is faster than using a statement such as &#39;select max(marker\_seq)&#39; from the alarmlog view (see below), which may become increasingly slow as the number of alarm records increases.

_api\_get\_last\_alarm();_

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| \&gt;0 | The highest alarm _marker\_seq_ value on the system as a 64-bit integer |

  1.
### Get Total Active Alarms

The **api\_get\_active\_alarm\_count** function can be used to determine the total number of active alarms present on the system. Active alarms are the outstanding alarms which have not yet been both acknowledged and cancelled

This function utilises table indices so is faster than using a statement such as statement such as &#39;select count(\*)&#39; from the alarmlog view (see below), which may become increasingly slow as the number of alarm records increases.

_api\_get\_active\_alarm\_count();_

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| \&gt;=0 | An integer total of the number of outstanding alarm records available on the system. |

  1.
### Active Alarms

The **api\_alarmlog** view returns a list of the current outstanding alarms.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| alarm\_num | integer | The unique alarm id for this site |
| alarm\_type\_num | integer | The unique alarm type number |
| alarm\_time | datetime | The time the alarm occurred |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| input\_num | integer | The input which triggered the alarm |
| input\_state | char(1) | The input state (&#39;O&#39;=Open, &#39;C&#39;=Closed, &#39;T&#39;=Tamper) |
| ack\_id | char(30) | The user who acknowledged the alarm |
| ack\_time | datetime | Acknowledgement time |
| can\_id | char(30) | The user who cancelled the alarm |
| can\_time | datetime | Time of cancellation |
| ack\_can\_state | integer | Current alarm Ack/Can state (see below) |
| site\_num | integer | The site number of the alarm |
| marker\_seq | biginteger | Unique alarm sequence ( **64-bit integer** ) |

The Alarm state can be one of the following

| **State** | **Description** |
| --- | --- |
| 0 | Both Acknowledged and Cancelled |
| 1 | Cancelled but not Acknowledged |
| 2 | Acknowledged but not Cancelled |
| 3 | Neither Acknowledged nor Cancelled |

The site\_num column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

This view only displays active alarms, therefore it will not show those with an _ack\_can\_state_ of 0 (both acknowledged and cancelled).

At startup, the view can be queried to build the active alarm list, storing the MAX value of _marker\_seq_ e.g.

_select \* from api\_alarmlog order by marker\_seq;_

Alternatively the highest _marker\_seq_ value can be read directly if preferred e.g.

_select_ [_api\_get\_last\_alarm()_](#Find_latest_alarm)_;_

The view can then be polled periodically to find the details of any new alarms or alarm updates, querying for records which have a _marker\_seq_ greater than that previously recorded max, storing the highest seen _marker\_seq_ value each time e.g.

_select \* from api\_alarmlog_

_where marker\_seq \&gt; last\_max\_marker\_seq_

_order by marker\_seq;_

The view should NOT be polled more than once per second and records must be processed in marker\_seq order.

**Important Note:** A device with the address &#39;00000&#39; must exist on the system for any non-device alarms to be visible (e.g. &#39;CDC Failed Over&#39; etc.)

  1.
### Cleared Alarms

The **api\_alarmlog\_archive** view returns a list of alarms which have been both acknowledged and cancelled.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| alarm\_num | integer | The unique alarm id for this site |
| alarm\_type\_num | integer | The unique alarm type number |
| alarm\_time | datetime | The time the alarm occurred |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| input\_num | integer | The input which triggered the alarm |
| input\_state | char(1) | The input state (&#39;O&#39;=Open, &#39;C&#39;=Closed, &#39;T&#39;=Tamper) |
| ack\_id | char(30) | The user who acknowledged the alarm |
| ack\_time | datetime | Acknowledgement time |
| can\_id | char(30) | The user who cancelled the alarm |
| can\_time | datetime | Time of cancellation |
| ack\_can\_state | integer | Current alarm Ack/Can state (see below) |
| site\_num | integer | The site number of the alarm |
| marker\_seq | biginteger | Unique alarm sequence ( **64-bit integer** ) |

See the [Active Alarms view](#view_active_alarms) for possible Alarm states and other concerns.

The site\_num column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

This view only displays alarms with an _ack\_can\_state_ of 0 (both acknowledged and cancelled).

**Important Note:**

This view can potentially return a very large number of rows so care should be taken to use appropriate selection clauses to ensure that only the required archived alarms are returned. It is recommended that the _marker\_seq_ field is used to search for recently cleared alarms.

  1.
### Get Total Alarms

The **api\_get\_alarm\_count** function can be used to determine the total number of alarms present on the system (both outstanding and cleared).

_api\_get\_alarm\_count();_

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| \&gt;=0 | An integer indicating the total number of alarms currently recorded on the system. |

  1.
### Broadcast Zones

The **api\_bc\_zones** view returns details related to the Broadcast Zones defined on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| bc\_zone\_num | integer | Unique identifier for the broadcast zone |
| bc\_zone\_desc | char(30) | Description of the broadcast zone |
| bc\_zone\_state | char(1) | Current state of the zone (&#39;C&#39;=Closed, &#39;O&#39;=Open) |
| site\_num | integer | The site where the zone resides |

The _site\_num_ column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

This view can be used to get a full list of broadcast zones as follows:

_select \* from api\_bc\_zones order by bc\_zone\_num;_

Alternatively the view can be used to get details of one specified broadcast zone as follows:

_select \* from api\_bc\_zones where bc\_zone\_num = 7;_

  1.
### Broadcast Zone Devices

The **api\_bc\_zone\_devices** view returns details related to the devices which are members of the Broadcast Zones which have been configured on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| bc\_zone\_num | integer | Unique identifier for the broadcast zone |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| output\_num | integer | The device output number |

The _output\_num_ column identifies the device out which will be manipulated during a broadcast operation.

This view can be used to get a full list of broadcast zone devices as follows:

_select \* from api\_bc\_zone\_devices_

_order by bc\_zone\_num, device\_addr, output\_num;_

Alternatively this view can be used to get details of devices in one specified broadcast zone, as follows:

_select \* from api\_bc\_zone\_devices where bc\_zone\_num=7;_

  1.
### Lockdown Zones

The **api\_ld\_zones** view returns details related to the Lockdown Zones defined on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| ld\_zone\_num | integer | Unique identifier for the lockdown zone |
| ld\_zone\_name | char(40) | Description of the lockdown zone |
| ld\_zone\_state | char(1) | Current state of the zone (1=Locked, 0=Unlocked) |

  1.
### Lockdown Zone Devices

The **api\_ld\_zone\_devices** view returns details related to the devices which are members of the Lockdown Zones configured on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| ld\_zone\_num | integer | Unique identifier for the lockdown zone |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |

  1.
### Victor Integration Information

The **api\_vic\_actions** view can be used for American Dynamics Victor Integrations. It filters external actions, returning only those that are of interest to the Victor system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| alarm\_type | integer | The unique alarm type number |
| input\_num | integer | The device input number of interest |
| input\_state | char(1) | The Input state (&#39;O&#39;=Open, &#39;C&#39;=Closed, &#39;T&#39;=Tamper) |
| site\_num | integer | The site where the device is installed |
| access\_device | char(1) | &#39;Y&#39; if an access device (i.e. card reader) otherwise &#39;N |
| device\_type | char(20) | A brief description of the device type |
| setstr | char(200) | The value of the &#39;set&#39; action string |

The _alarm\_type_ column is equivalent to the _alarm\_type\_num_ column of the [Alarm Types](#view_alarm_types) view.

The _site\_num_ column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

  1.
### Emerald Reader responses

CEM Emerald readers can operate in various special modes such as &#39;Flight&#39; mode and &#39;Time and Attendance&#39; mode. These modes often require additional actions to be taken during card swipe operations e.g. a question must be answered or a single item must be selected from a list. The responses to these actions are reported back to the CDC for further processing.

The **api\_emerald\_data** view can be used to examine the responses.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique personnel serial number |
| rpt\_start | datetime | The date and time when the action began |
| rpt\_end | datetime | The date and time when the swipe ended |
| hotstamp\_num | integer | The unique card hotstamp number |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| rpt\_type | char(15) | Report type |
| rpt\_status | char(30) | Report status |
| rpt\_data | char(500) | Report data |

  1.
### Vehicle details

The **api\_vehicle** view returns certain details of existing vehicles

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| vehicle\_ser | integer | The unique vehicle serial number |
| reg\_num | char(20) | Vehicle registration number |
| make\_desc | char(30) | The vehicle make (manufacturer) description |
| model\_desc | char(30) | The vehicle model description |
| colour | char(20) | Vehicle colour |
| veh\_desc | char(30) | Vehicle description |
| manu\_date | date | Manufacture date |
| veh\_test\_date | date | Vehicle test date |
| curr\_miles | integer | Current mileage |
| fuel\_type\_desc | char(30) | Fuel type description |
| engine\_size | char(30) | Engine size |
| has\_obs\_lights | char(1) | Has obstruction lights? |
| owner\_name | char(60) | Vehicle owner |
| comp\_id | char(8) | Company ID |
| address1 | char(60) | Address 1 |
| address2 | char(60) | Address 2 |
| postcode | char(20) | Postcode |
| tel\_num | char(20) | Contact telephone number |
| card\_format\_desc | char(20) | Card format description |
| auth\_num | integer | Authoriser |
| rf\_issue\_desc | char(20) | Reason-for-issue description |
| charge | integer | Issue charge |
| remark\_num | integer | Remark number |
| remarks | char(40) | Remarks |
| issue\_date | date | Date of card issue |
| start\_date | date | Start date |
| expiry\_date | date | Expiry date |
| cardstatus | char(1) | Card Status |
| acc\_level\_desc | char(30) | Access level description |
| gtz\_desc | char(20) | Timezone description |
| pin | char(4) | Pin code for card |
| hotstamp\_num | integer | Card hotstamp number |
| card\_num | char(8) | Card number |
| added\_by | char(30) | Added by |
| creation\_date | date | Creation date |
| site\_num | integer | Site number |
| part\_num | integer | The partition in which the vehicle was created |
| char1 | char(30) | Spare character field 1 (customer use) |
| char2 | char(30) | Spare character field 2 (customer use) |
| char3 | char(30) | Spare character field 3 (customer use) |
| char4 | char(30) | Spare character field 4 (customer use) |
| char5 | char(30) | Spare character field 5 (customer use) |
| char6 | char(30) | Spare character field 6 (customer use) |
| char7 | char(30) | Spare character field 7 (customer use) |
| char8 | char(30) | Spare character field 8 (customer use) |
| num1 | integer | Spare number field 1 (customer use) |
| num2 | integer | Spare number field 2 (customer use) |
| num3 | integer | Spare number field 3 (customer use) |
| num4 | integer | Spare number field 4 (customer use) |
| date1 | date | Spare date field 1 (customer use) |
| date2 | date | Spare date field 2 (customer use) |
| date3 | date | Spare date field 3 (customer use) |
| date4 | date | Spare date field 4 (customer use) |

The _site\_num_ column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

The _part\_num_ column is only relevant to partitioned systems; it will normally have a value of 1 otherwise (AC2000 system partitioning is outside the scope of this document).

  1.
### Visitor details

The **api\_visitor** view returns details of existing visitors

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visitor\_ser | integer | The unique visitor serial number |
| surname | char(34) | Visitor surname |
| forenames | char(34) | Visitor forename(s) |
| company\_name | char(30) | The Visitors company name |
| hotstamp\_num | integer | The Visitors current hotstamp number |
| expiry\_time | datetime | The expiry datetime of the Visitors current card |
| cardstatus | char(1) | The Visitors current card status |
| tel\_num | char(20) | The Visitors telephone number |
| email\_addr | char(60) | email address |

The [_Card Status codes_](#Card_status_codes) list contains possible cardstatus values.

  1.
### Device Outputs

The **api\_output** view returns details of the outputs available on configured devices

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| output\_num | integer | The device output number |
| output\_desc | char(20) | Description of the device output |

  1.
### Swipe Outcomes

The **api\_outcome** view lists the possible outcomes as a result of swipe actions on reader devices

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| outcome\_num | integer | The unique outcome number |
| outcome\_desc | char(25) | Description of the outcome |

  1.
### Company details

The **api\_company** view returns details of the companies currently configured on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| company\_num | integer | The unique Company number |
| company\_id | char(8) | The Company short code |
| comp\_name | char(40) | The full Company name |

  1.
### Timezone details

The **api\_timezone** view returns details of the time zones currently configured on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| timezone\_num | integer | The unique Timezone number |
| timezone\_desc | char(20) | The Timezone description |

  1.
### GTZ Timezone details

The **api\_gtzinfo** view returns details of the time zones currently configured on the system. It is identical to the api\_timezone view except for column names.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| gtz\_num | integer | The unique Timezone number |
| gtz\_desc | char(20) | The Timezone description |

  1.
### Card Type details

The **api\_card\_type** view returns details of the currently configured card types

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| card\_type\_num | integer | The unique Card Type number |
| card\_type\_desc | char(20) | The Card Type description |
| readable | char(1) | Is the card type readable, &#39;Y&#39; or &#39;N&#39; |
| exportable | char(1) | Is the card type exportable, &#39;Y&#39; or &#39;N&#39; |
| gen\_hsn | char(1) | Does the Card Type generate hotstamps, &#39;Y&#39; or &#39;N&#39; |
| gen\_card\_num | char(1) | Does the Card Type generate card numbers, &#39;Y&#39; or &#39;N&#39; |
| min\_hsn | integer | The minimum hotstamp number for the Card Type |
| max\_hsn | integer | The maximum hotstamp number for the Card Type |
| part\_num | integer | The partition to which the Card Type belongs |

  1.
### Card Format details

The **api\_card\_format** view returns details of the currently configured card types

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| card\_form\_num | integer | The unique Card Format number |
| card\_form\_desc | char(20) | The Card Format description |
| reusable | char(1) | Does the Card Format use reusable cards, &#39;Y&#39; or &#39;N&#39; |
| card\_type\_num | integer | The number of the Card Type associated with the format |
| part\_num | integer | The partition to which the Card Format belongs |

  1.
### Device Output State details

The **api\_bc\_dev\_state** view returns details of the _expected_ state of device outputs following broadcast operations.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| output\_num | integer | The device output number |
| bc\_state | char(1) | The expected current state of the zone (&#39;C&#39;=Closed, &#39;O&#39;=Open) |
| last\_update | datetime | The date and time of the last broadcast action to the device |

**Important Notes** :

As devices do not report state information, the _bc\_zone\_state_ value is only the **expected** state of the device following a broadcast to it. It is possible that a broadcast failed due to the device being offline or the state was changed due to some other action.

_ **The bc\_zone\_state value cannot be used as a definitive indicator of current state.** _

If a device has never had a broadcast issued to it, there will be no records for it therefore its state is unknown.

A given device may have more than one entry. If broadcasts have been sent to different outputs on the same device, there will be one record per output number. There will only be a single entry for each _device\_addr_, _output\_num_ combination.

  1.
### Partition details

The **api\_partition** view returns details of the partitions currently configured on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| part\_num | integer | The unique Partition number |
| part\_desc | char(20) | The Partition description |

For normal (non-partitioned systems) only partition 1, the default partition will be present.

  1.
### Manager details

The **api\_manager** view returns details of the managers currently defined on the system.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| manager\_ser | integer | The managers unique personnel\_ser value |
| surname | char(30) | Surname from the managers Personnel record |
| forenames | char(30) | Forenames from the managers Personnel record |
| comp\_id | char(8) | The Company short code |
| part\_num | integer | The partition to which the manager belongs |

For normal (non-partitioned systems) only partition 1, the default partition will be present.

  1.
### Personnel Access

The **api\_per\_access** view returns details of the current access levels assigned to cardholders.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| personnel\_ser | integer | The unique Personnel record serial number |
| access\_type | char(14) | Access type description (see below) |
| access\_level\_desc | char(30) | Access level description |
| start\_time | datetime | Start time for access (if time-constrained) |
| end\_time | datetime | End time for access (if time-constrained) |
| gtz\_desc | char(20) | Timezone description |
| active | char(1) | &#39;Y&#39; if access is currently active, otherwise &#39;N&#39; |
| extra\_access\_ser | integer | The unique access id of the access assignment |
| tea\_ser | integer | The unique id of the temporary access assignment |

Access type can contain one of the following values:-

&#39;Primary&#39; - The Primary access for the person, assigned via an ID card..

&#39;Manual&#39; – Manually assigned Extra Access (EA)

&#39;Temporary&#39; – Time-constrained Temporary Extra Access (TEA)

&#39;Swipe Invoked&#39;- Time-constrained Access initiated by a card swipe

A value for _extra\_access\_ser_ will only be present for access types which are _not_ Primary and which are currently active.

If a cardholder has more than one active card multiple Primary access rows may be returned for them.

  1.
### Visitor Access

The **api\_vis\_access** view returns details of the current access levels assigned to visitors.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| visitor\_ser | integer | The unique Visitor record serial number |
| access\_type | char(14) | Access type description (see below) |
| access\_level\_desc | char(30) | Access level description |
| start\_time | datetime | Start time for access (if time-constrained) |
| end\_time | datetime | End time for access (if time-constrained) |
| gtz\_desc | char(20) | Timezone description |
| active | char(1) | &#39;Y&#39; if access is currently active, otherwise &#39;N&#39; |
| extra\_access\_ser | integer | The unique id of the access assignment |
| tea\_ser | integer | The unique id of the temporary access assignment |

Access type can contain one of the following values:-

&#39;Primary&#39; - The Primary access for the visitor.

&#39;Manual&#39; – Manually assigned Extra Access (EA)

&#39;Temporary – Time-constrained Temporary Extra Access (TEA)

&#39;Swipe Invoked&#39;- Time-constrained Access initiated by a card swipe

A value for _extra\_access\_ser_ will only be present for access types which are _not_ Primary and which are currently active.

  1.
### Access Level Devices

The **api\_access\_devices** view returns details of the devices assigned to each access level.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| access\_level\_num | integer | The unique Access level number |
| access\_level\_desc | char(30) | Access level description |
| device\_addr | char(5) | The unique 5-digit hexadecimal Device address |
| device\_location | char(80) | Device location |
| site\_num | integer | The site where the device is installed |
| part\_num | integer | The partition to which the access level and device belong |

The site\_num column is only relevant for multi-site systems; it will typically have a value of 1 otherwise.

For normal (non-partitioned systems) only partition 1, the default partition will be present.

  1.
### Card Format Access Levels

The **api\_card\_format\_access** view returns the access levels which are available to each card format.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| card\_form\_num | integer | The unique Card Format number |
| card\_form\_desc | char(20) | Card Format description |
| access\_level\_num | integer | The unique Access level number |
| access\_level\_desc | char(30) | Access level description |
| part\_num | integer | The partition to which the device and access level belong |

For normal (non-partitioned systems) only partition 1, the default partition will be present.

  1.
### Card Type Formats

The **api\_card\_type\_formats** view returns details of the card formats which are available to each card type.

Column definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| card\_type\_num | integer | Unique Card Type number |
| card\_type\_desc | char(20) | Card Type description |
| card\_form\_num | integer | Unique Card Format number |
| card\_form\_desc | char(20) | Card Format description |
| application | char(10) | Application, either &#39;Personnel&#39;, &#39;Visitors&#39; or &#39;Vehicles&#39; |
| part\_num | integer | The partition to which the card type belongs |

For normal (non-partitioned systems) only partition 1, the default partition will be present.

  1.
### Get Person ID from Payroll number

The **api\_get\_pser\_from\_payroll** function can be used to find a cardholders unique ID (personnel\_ser) using their payroll number.

The system should be configured to insist on mandatory unique payroll numbers when adding or updating personnel, by setting configuration option &#39;unique\_payroll\_num&#39;.

_api\_get\_pser\_from\_payroll( payroll\_num );_

Parameter definitions

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| payroll\_num | char(20) | The cardholders unique payroll number |

Function Return Codes

| **Code** | **Description** |
| --- | --- |
| -1 | The Payroll number was not found |
| -2 | More than one record was found for this Payroll number |
| \&gt;0 | Success, the personnel\_ser for the cardholder with this Payroll number |

1.
## **Enterprise Constraints**

An Enterprise system comprises an Enterprise Controller (GDC) and one or more Site Controllers (CDCs in Enterprise mode).

Each Controller is identified by a unique site number.

Some of the API functions above accept a site number as an argument, allowing actions to be taken on behalf of that site when the function is called on a GDC. Attempting to perform these actions on a non-GDC site will generate an error if the site number provided is not the local site.

At present, there are restrictions on the ability of a GDC to manipulate certain CDC data. As a result the following API functionality is either unusable or not installed.

- Functions:

[Assign Temporary Access to an Cardholder](#Assign_tea_access)

[Remove Temporary Access from an Cardholder](#Remove_tea_access)

[Add Extra Access to a group of Cardholders](#Add_group_extra_access)

[Remove Extra Access from a group of Cardholders](#Remove_group_extra_access)

[Determine if Extra Access is enabled for a group of Cardholders](#Check_group_extra_access)

[Locking Devices in a Lockdown Zone](#Lock_lockdown_zone)

[UnLocking Devices in a Lockdown Zone](#Unlock_lockdown_zone)

All of the [Threat Level](#Threat_Level_functions) functions

All of the [Visitor](#Visitor_functions) functions

All of the [Vehicle](#Vehicle_functions) functions

- Views:

[Broadcast Zone Devices](#view_broadcast_zone_devices)

[Lockdown Zones](#view_lockdown_zones)

[Lockdown Zone Devices](#view_lockdown_zone_devices)

[Emerald Reader responses](#view_emerald_responses)

[Vehicle](#view_vehicles)details

[Visitor](#view_visitors) details

1.
## **Pseudocode Examples**

The following are simple pseudocode examples to demonstrate API function usage

These data values will be used for the examples

**Access Levels**

&#39;ALL&#39;

&#39;SERVER ROOM&#39;

&#39;OFFICE BLOCK&#39;

&#39;MAIN BUILDING&#39;

**Timezones**

&#39;ALL THE TIME&#39;

&#39;9-5 WEEKDAYS&#39;

**Card Formats**

&#39;BLUE OFFICE&#39;

&#39;RED ALL AREAS&#39;

&#39;GREEN SERVER RM&#39;

**Companies (id,name)**

&#39;ACM&#39;, &#39;ACME&#39;

&#39;CEM&#39;, &#39;CEM SYSTEMS&#39;

  1.
### Add a Cardholder and an ID card

- Add a new cardholder
- Add and activate an ID card for a cardholder
- Change the ID card access level
- Change the ID card status and expiry

// perform any initialisation, log on to A2000 etc

// create a new cardholder

personnel\_ser = select api\_per\_add( &#39;BROWN&#39;, &#39;SAM&#39;, &#39;Mr Sam Brown&#39;, &#39;M&#39;, &#39;1970-12-31&#39;,

&#39;10 MAIN STREET&#39;, &#39;SOME TOWN&#39;, &#39;SOME AREA&#39;, &#39;AB1 1BA&#39;, &#39;sbrown@my\_email.com&#39;,

&#39;(01234) 567890&#39;, &#39;CEM&#39;, &#39;SOFTWARE DEPT&#39;, &#39;PROGRAMMER&#39;, &#39;PAY1234&#39;, &#39;8797&#39;, &#39;N&#39;, &#39;N&#39;, NULL,

NULL, &#39;Spare Text 2&#39;, NULL, NULL, NULL, 22, NULL, &#39;1999-12-31&#39;);

if ( personnel\_ser \&lt;= 0 )

return &quot;personnel create failure&quot;;

// add a photo of the cardholder to the system

my\_jpeg\_file = &#39;MyPhoto.jpg&#39;;

b64data = convert\_to\_base64( my\_jpeg\_file );

select api\_img\_create( personnel\_ser, b64data );

// create a new id card for the cardholder

id\_cards\_ser = select api\_idc\_add( personnel\_ser, &#39;RED ALL AREAS&#39;, &#39;MAIN BUILDING&#39;,&#39;9-5 WEEKDAYS&#39;,

&#39;2018-01-01&#39;, &#39;2018-12-31&#39;, &#39;CEM&#39;, NULL, NULL, NULL,

NULL, NULL, &#39;Spare Text 3&#39;, NULL, NULL, 11, NULL, &#39;2001-11-30&#39;);

if ( id\_cards\_ser \&lt;= 0 )

return &quot;id card create failure&quot;;

// validate (activate) the id card

status = select api\_idc\_val( id\_cards\_ser, 3, &#39;32345678&#39; );

if ( status \&lt; 0 )

return &quot;id card validation failure&quot;;

// change the main access level

status = select api\_idc\_upd( id\_cards\_ser, &#39;RED ALL AREAS&#39;, &#39; **OFFICE BLOCK**&#39;,&#39;9-5 WEEKDAYS&#39;,

&#39;2018-01-01&#39;, &#39;2018-12-31&#39;, NULL, NULL, NULL, NULL,

NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL);

if ( status \&lt; 0 )

return &quot;id card access level change failure&quot;;

return &quot;success&quot;;

  1.
### Cancel an ID card and issue a replacement

- Cancel an existing card
- Add a new card
- Activate the new card

// perform any initialisation, log on to A2000 etc

// find the correct person

pers\_ser = select personnel\_ser from api\_person

where forename=&#39;JOHN&#39; and surname=&#39;SMITH&#39;;

if ( pers\_ser is NULL)

return &quot;unable to find personnel record&quot;;

// find the correct id card – we are only interested in valid cards - i.e. card status is &#39;C&#39; (current),

// &#39;A&#39; (about to expire) or &#39;N&#39; (not yet operational).

// note there may be more than one id card for this person so the selection may need to be refined

cur\_id\_ser = select id\_card\_ser from api\_id\_cards

where personnel\_ser = pers\_ser

and card\_status in (&#39;C&#39;,&#39;A&#39;,&#39;N&#39;) ;

if ( cur\_id\_ser is NULL)

return &quot;unable to find id card record&quot;;

// change the card expiry date to todays date (5th January 2018) and set the status to &#39;E&#39; (Expired)

status = select api\_idc\_upd( cur\_id\_ser, NULL, NULL,NULL,

&#39;2018-01-01&#39;, &#39; **2018-01-05**&#39;, &#39; **E**&#39;, NULL, NULL, NULL,

NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL);

if ( status \&lt; 0 )

return &quot;failed to expire the current id card&quot;;

// create a new id card for the cardholder

new\_id\_ser = select api\_idc\_add( pers\_ser, &#39;RED ALL AREAS&#39;, &#39;MAIN BUILDING&#39;,&#39;9-5 WEEKDAYS&#39;,

&#39;2018-01-05&#39;, &#39;2018-12-31&#39;, &#39;CEM&#39;, NULL, NULL, NULL,

NULL, NULL, NULL, NULL, NULL, NULL, NULL, NULL);

if ( new\_id\_ser \&lt;= 0 )

return &quot;failed to create new id card&quot;;

// validate (activate) the new id card with hotstamp number = 100, card number = &#39;3F12344F&#39;

status = select api\_idc\_val( new\_id\_ser, 100, &#39;3F12344F &#39; );

if ( status \&lt; 0 )

return &quot;id card validation failure&quot;;

return &quot;success&quot;;

  1.
### Assign extra access to individuals and groups.

- Assign an Extra Access level to a cardholder
- Remove an Extra Access assignment from a cardholder
- Assign an Extra Access level to a group of cardholders
- Remove an Extra Access level assignment from a group of cardholders

// perform any initialisation, log on to A2000 etc

// find the correct person

pers\_ser = select personnel\_ser from api\_person

where forename=&#39;JOHN&#39; and surname=&#39;SMITH&#39;;

if ( pers\_ser is NULL)

return &quot;unable to find personnel record&quot;;

// assign additional access level

status = select api\_ea\_add( pers\_ser, &#39;SERVER ROOM&#39;, &#39;ALL THE TIME&#39; );

if ( status \&lt; 0 )

return &quot;extra access level assignment failure&quot;;

// remove the additional access level

status = select api\_ea\_del(pers\_ser, &#39;SERVER ROOM&#39;, &#39;ALL THE TIME&#39; );

if ( status \&lt; 0 )

return &quot;extra access level removal failure&quot;;

// assign an extra access level to members of the hardware department

record\_count = select api\_group\_ea\_add( &#39;department&#39;, &#39;HARDWARE&#39;, &#39;MAIN BUILDING&#39;, &#39;9-5 WEEKDAYS&#39; );

if ( record\_count \&lt; 0 )

return &quot;group extra access assignment failure&quot;;

// remove an extra access level assignment from cleaners

record\_count = select api\_group\_ea\_del( &#39;job\_title&#39;, &#39;CLEANER&#39;, &#39;SERVER ROOM&#39;, &#39;ALL THE TIME&#39; );

if ( record\_count \&lt; 0 )

return &quot;group extra access removal failure&quot;;

return &quot;success&quot;;

  1.
### Monitor alarms

- Populate alarm list
- Monitor alarms

// perform any initialisation, log on to A2000 etc

// store details of AC2000 alarm types

while ( select \* from api\_alarm )

{

add alarm\_type details to alarm\_type\_list;

}

// get list of active alarms

while ( select \* from api\_alarmlog order by marker\_seq )

{

add alarm details to alarm\_list;

}

// fetch value of highest marker\_seq to use for polling loop

last\_marker\_seq = select api\_get\_last\_alarm();

// loop and watch for new alarms

while ( true )

{

// get new and updated alarms

while ( select \* from api\_alarmlog where marker\_seq \&gt; last\_marker\_seq

order by marker\_seq )

{

if ( new alarm )

{

add alarm details to alarm\_list;

}

else if ( existing alarm )

{

update alarm details in the alarm\_list;

}

// save the highest marker\_seq value to use for the next pass

last\_marker\_seq = marker\_seq;

}

sleep for 1 second;

}

  1.
### Monitor transactions

- Monitor transactions
- Retrieve personnel details for the transactions

// perform any initialisation, log on to A2000 etc

//get list of the last 15 minutes transactions

while ( select \* from api\_per\_swipe where swipe\_time\&gt;(current\_time–15 minutes) order by marker\_seq )

{

add swipe details to swipe\_list;

// store value of highest marker\_seq to use for polling loop

last\_marker\_seq = marker\_seq;

}

// loop, fetching and processing transactions

while ( true )

{

// get most recent card swipes

while ( select \* from api\_per\_swipe where marker\_seq\&gt;last\_marker\_seq) order by marker\_seq )

{

if ( new card swipe )

{

add swipe\_details to swipe list;

// use the personnel\_ser value from the swipe details to retrieve the persons details

user\_details = select \* from api\_person where personnel\_ser = swipe\_details.personnel\_ser;

display user\_details ( hotstamp, forename, surname, job\_title );

// use the personnel\_ser value from the swipe details to retrieve the persons photo

// read as base64 and convert the result back to jpg

user\_photo = select encode( api\_get\_face( swipe\_details.personnel\_ser ), &#39;base64&#39; );

jpeg\_image = base64\_decode( user\_photo );

display jpeg\_image;

}

// save the highest marker\_seq value to use during the next pass

last\_marker\_seq = marker\_seq;

}

}

  1.
### Populate and broadcast devices and zones

- Populate device and broadcast zone lists
- Broadcast to a single device
- Broadcast to a zone

// perform any initialisation, log on to A2000 etc

// store details of AC2000 devices

while ( select \* from api\_device )

{

add device details to device\_list;

}

// store details of broadcast zones

while ( select \* from api\_bc\_zones )

{

add bc\_zone details to broadcast\_zone\_list;

}

// send single device broadcasts to all devices

for each ( device in device\_list )

{

// send a oneshot to each device

select api\_bc\_req( device.device\_addr, &#39;S&#39; );

// send broadcast open to output 4 on each device

select api\_bc\_output( device.device\_addr, &#39;o&#39;, &#39;4&#39; );

}

// multiple device broadcasts – open and close all zones

for each ( zone in broadcast\_zone\_list )

{

// send an open request to a broadcast zone

broadcast\_id = select api\_bc\_request( zone. bc\_zone\_num, &#39;O&#39; );

// wait for the broadcast to complete

select api\_zone\_wait( broadcast\_id );

// send a close request to a broadcast zone without waiting on completion

broadcast\_id = select api\_bc\_request( zone. bc\_zone\_num, &#39;C&#39; );

}

  1.
### Acknowledge and cancel alarms

- Populate alarm list
- Acknowledge and cancel alarms

// perform any initialisation, log on to A2000 etc

// store details of AC2000 alarm types

while ( select \* from api\_alarm )

{

add alarm\_type details to alarm\_type\_list;

}

// get list of active alarms

while ( select \* from api\_alarmlog order by marker\_seq )

{

add alarm details to alarm\_list;

}

// to acknowledge and cancel all &#39;tamper&#39; alarms

tamper\_alarm\_num = find &#39;Tamper&#39; value in alarm\_type\_list;

for each ( alarm in alarm\_list )

{

if ( alarm. alarm\_type\_num == tamper\_alarm\_num)

{

select api\_alm\_ack( alarm.alarm\_num );

select api\_alm\_can( alarm.alarm\_num );

}

} 

1.
## **REST message examples**

The following are simple examples of REST requests and responses to and from the API.

  1.
### Query Request

{

&quot;apirequest&quot;: {

&quot;auth&quot;: {

&quot;username&quot;: &quot;api\_user&quot;,

&quot;password&quot;: &quot;SuperSecret1=&quot;

},

&quot;action&quot;: &quot;query&quot;,

&quot;item&quot;: &quot;api\_alarm&quot;

}

}

  1.
### Query Response

{

&quot;apiresponse&quot;: {

&quot;status\_code&quot;: 200,

&quot;status\_text&quot;: &quot;Success&quot;,

&quot;result&quot;: [

{

&quot;item&quot;: {

&quot;name&quot;: &quot;api\_alarm&quot;,

&quot;type&quot;: &quot;view&quot;,

&quot;returns&quot;: &quot;recordset&quot;,

&quot;columns&quot;: [

{

&quot;column&quot;: {

&quot;name&quot;: &quot;alarm\_type\_num&quot;,

&quot;type&quot;: &quot;integer&quot;

}

},

{

&quot;column&quot;: {

&quot;name&quot;: &quot;alarm\_description&quot;,

&quot;type&quot;: &quot;char(20)&quot;

}

},

{

&quot;column&quot;: {

&quot;name&quot;: &quot;auto\_or\_manual\_can&quot;,

&quot;type&quot;: &quot;char(1)&quot;

}

},

{

&quot;column&quot;: {

&quot;name&quot;: &quot;priority&quot;,

&quot;type&quot;: &quot;integer&quot;

}

}

]

}

}

]

}

}

  1.
### Fetch Request

{

&quot;apirequest&quot;: {

&quot;auth&quot;: {

&quot;username&quot;: &quot;api\_user&quot;,

&quot;password&quot;: &quot;SuperSecret1=&quot;

},

&quot;action&quot;: &quot;fetch&quot;,

&quot;command&quot;: &quot;select \* from api\_alarm where alarm\_type\_num \&gt; 10 limit 2&quot;

}

}

  1.
### Fetch Response

&quot;apiresponse&quot;: {

&quot;status\_code&quot;: 200,

&quot;status\_text&quot;: &quot;Success&quot;,

&quot;result&quot;: [

{

&quot;item&quot;: {

&quot;alarm\_type\_num&quot;: &quot;12&quot;,

&quot;alarm\_description&quot;: &quot;Lock not engaged&quot;,

&quot;auto\_or\_manual\_can&quot;: &quot;A&quot;,

&quot;priority&quot;: &quot;0&quot;,

&quot;source\_type&quot;: &quot;EXT&quot;

}

},

{

&quot;item&quot;: {

&quot;alarm\_type\_num&quot;: &quot;13&quot;,

&quot;alarm\_description&quot;: &quot;Panic&quot;,

&quot;auto\_or\_manual\_can&quot;: &quot;M&quot;,

&quot;priority&quot;: &quot;0&quot;,

&quot;source\_type&quot;: &quot;EXT&quot;

}

}

]

}

}

  1.
### Visitor examples

1.
#### Add a new Visitor

_Request_

{

  &quot;apirequest&quot;: {

    &quot;auth&quot;: {

      &quot;username&quot;: &quot;api\_user&quot;,

      &quot;password&quot;: &quot;SuperSecret1=&quot;

    },

    &quot;action&quot;: &quot;exec&quot;,

    &quot;procedure&quot;: &quot;api\_vis\_add&quot;,

    &quot;values&quot;: {

      &quot;surname&quot;: &quot;Smith&quot;,

      &quot;forenames&quot;: &quot;John&quot;,

      &quot;comp\_name&quot;: &quot;Acme Inc.&quot;,

      &quot;pin&quot;: &quot;3746&quot;

    }

  }

}

_Response_

{

  &quot;apiresponse&quot;: {

    &quot;status\_code&quot;: 200,

    &quot;status\_text&quot;: &quot;Success&quot;,

    &quot;result&quot;: &quot;100000008&quot;

  }

}

1.
#### Add a Visit for the Visitor

_Request_

{

  &quot;apirequest&quot;: {

    &quot;auth&quot;: {

      &quot;username&quot;: &quot;api\_user&quot;,

      &quot;password&quot;: &quot;SuperSecret1=&quot;

    },

    &quot;action&quot;: &quot;exec&quot;,

    &quot;procedure&quot;: &quot;api\_vst\_add&quot;,

    &quot;values&quot;: {

      &quot;visitor\_ser&quot;: &quot;100000008&quot;,

      &quot;personnel\_ser&quot;: &quot;13&quot;,

      &quot;reason&quot;: &quot;Sales meeting&quot;,

      &quot;card\_form\_desc&quot;: &quot;Visitors&quot;,

      &quot;acc\_lev\_desc&quot;: &quot;OFFICE BLOCK&quot;,

      &quot;gtz\_desc&quot;: &quot;ALL THE TIME&quot;,

      &quot;start\_time&quot;: &quot;2021-02-03 09:00:00&quot;,

      &quot;end\_time&quot;: &quot;2021-02-03 17:00:00&quot;

    }

  }

}

_Response_

{

  &quot;apiresponse&quot;: {

    &quot;status\_code&quot;: 200,

    &quot;status\_text&quot;: &quot;Success&quot;,

    &quot;result&quot;: &quot;9&quot;

  }

}

1.
#### Assign a Card for the Visit

_Request_

{

  &quot;apirequest&quot;: {

    &quot;auth&quot;: {

      &quot;username&quot;: &quot;api\_user&quot;,

      &quot;password&quot;: &quot;SuperSecret1=&quot;

    },

    &quot;action&quot;: &quot;exec&quot;,

    &quot;procedure&quot;: &quot;api\_vst\_val&quot;,

    &quot;values&quot;: {

      &quot;visit\_ser&quot;: &quot;9&quot;,

      &quot;hotstamp\_num&quot;: &quot;84707&quot;,

      &quot;card\_num&quot;: &quot;C2333505&quot;

    }

  }

}

_Response_

{

  &quot;apiresponse&quot;: {

    &quot;status\_code&quot;: 200,

    &quot;status\_text&quot;: &quot;Success&quot;,

    &quot;result&quot;: &quot;1&quot;

  }

}

1.
#### Return the Visit Card

_Request_

{

  &quot;apirequest&quot;: {

    &quot;auth&quot;: {

      &quot;username&quot;: &quot;api\_user&quot;,

      &quot;password&quot;: &quot;SuperSecret1=&quot;

    },

    &quot;action&quot;: &quot;exec&quot;,

    &quot;procedure&quot;: &quot;api\_vst\_ret&quot;,

    &quot;values&quot;: {

      &quot;visit\_ser&quot;: &quot;9&quot;,

      &quot;return\_code&quot;: &quot;R&quot;

    }

  }

}

_Response_

{

  &quot;apiresponse&quot;: {

    &quot;status\_code&quot;: 200,

    &quot;status\_text&quot;: &quot;Success&quot;,

    &quot;result&quot;: &quot;1&quot;

  }

}

  1.
### Example code in C with libcurl

The following code is based on the examples available from the libcurl site at

[https://curl.haxx.se/libcurl/c/libcurl.html](https://curl.haxx.se/libcurl/c/libcurl.html)

(built on Linux using: gcc -o cem\_example cem\_example.c –lcurl)

#include \&lt;stdio.h\&gt;

#include \&lt;stdlib.h\&gt;

#include \&lt;string.h\&gt;

#include \&lt;curl/curl.h\&gt;

struct curl\_receipt

{

char \*data;

size\_t size;

};

static size\_t data\_received(void \*contents,

size\_t size,size\_t nmemb,void \*userp)

{

size\_t realsize=size\*nmemb;

struct curl\_receipt \*rcvd=(struct curl\_receipt \*)userp;

/\* expand as needed \*/

rcvd-\&gt;data=realloc(rcvd-\&gt;data,rcvd-\&gt;size+realsize+1);

if(rcvd-\&gt;data==NULL)

{

printf(&quot;not enough memory (realloc returned NULL)\n&quot;);

return 0;

}

/\* append new data to any existing \*/

memcpy(&amp;(rcvd-\&gt;data[rcvd-\&gt;size]),contents,realsize);

rcvd-\&gt;size+=realsize;

rcvd-\&gt;data[rcvd-\&gt;size]=0;

return realsize;

}

int curl\_send(CURL \*curl\_handle,char \*req)

{

CURLcode res;

struct curl\_receipt rsp;

rsp.data=malloc(1); /\* grown as needed by realloc above \*/

rsp.size=0; /\* no data at this point \*/

/\* pass rsp struct to the callback function \*/

curl\_easy\_setopt(curl\_handle,CURLOPT\_WRITEDATA,(void \*)&amp;rsp);

/\* specify the request data \*/

curl\_easy\_setopt( curl\_handle,CURLOPT\_POSTFIELDS,req);

/\* send the request and read the response \*/

res=curl\_easy\_perform(curl\_handle);

if(res!=CURLE\_OK)

fprintf(stderr,&quot;Failed: %s\n&quot;,curl\_easy\_strerror(res));

else

fprintf(stdout,&quot;%s\n&quot;,(char \*)rsp.data );

free(rsp.data);

return rsp.size;

}

int main(void)

{

CURL \*curl\_handle;

curl\_global\_init(CURL\_GLOBAL\_ALL);

/\* get a curl handle \*/

curl\_handle=curl\_easy\_init();

if(curl\_handle)

{

/\* read function for api response \*/

curl\_easy\_setopt(curl\_handle,CURLOPT\_WRITEFUNCTION,data\_received);

/\* destination URL (must be https:// for CEM API ) \*/

curl\_easy\_setopt(curl\_handle,CURLOPT\_URL,&quot;https://127.0.0.1/api&quot;);

/\* CEM CDC has a self-signed cert, need to omit the cert check \*/

curl\_easy\_setopt(curl\_handle,CURLOPT\_SSL\_VERIFYPEER,0);

/\* QUERY \*/

curl\_send(curl\_handle,

&quot;{ \&quot;apirequest\&quot; : { \

\&quot;auth\&quot; : { \

\&quot;username\&quot; : \&quot;api\_user\&quot;, \

\&quot;password\&quot; : \&quot;SuperSecret1=\&quot; \

}, \

\&quot;action\&quot; : \&quot;query\&quot;, \

\&quot;item\&quot; : \&quot;api\_per\_add\&quot; \

} \

}&quot;

);

/\* EXEC \*/

curl\_send(curl\_handle,

&quot;{ \&quot;apirequest\&quot; : { \

\&quot;auth\&quot; : { \

\&quot;username\&quot; : \&quot;api\_user\&quot;, \

\&quot;password\&quot; : \&quot;SuperSecret1=\&quot; \

}, \

\&quot;action\&quot; : \&quot;exec\&quot;, \

\&quot;procedure\&quot; : \&quot;api\_per\_add\&quot;, \

\&quot;values\&quot; : { \

\&quot;surname\&quot; : \&quot;SMITH\&quot;, \

\&quot;forenames\&quot; : \&quot;JOHN\&quot;, \

\&quot;badge\_name\&quot; : \&quot;Mr John Smith\&quot;, \

\&quot;gender\&quot; : \&quot;M\&quot;, \

\&quot;dateofbirth\&quot; : \&quot;2000-01-01\&quot;, \

\&quot;address1\&quot; : \&quot;195 AIRPORT RD WEST\&quot;, \

\&quot;address2\&quot; : \&quot;BELFAST\&quot;, \

\&quot;address3\&quot; : \&quot;N.IRELAND\&quot;, \

\&quot;postcode\&quot; : \&quot;BT3 9ED\&quot;, \

\&quot;email\_addr\&quot; : \&quot;jsmith@cem.com\&quot;, \

\&quot;tel\_num\&quot; : \&quot;02890456767\&quot;, \

\&quot;comp\_id\&quot; : \&quot;001\&quot;, \

\&quot;department\&quot; : \&quot;SOFTWARE\&quot;, \

\&quot;job\_title\&quot; : \&quot;PROGRAMER\&quot;, \

\&quot;payroll\_num\&quot; : \&quot;5001\&quot;, \

\&quot;pin\&quot; : \&quot;1234\&quot;, \

\&quot;special\&quot; : \&quot;N\&quot;, \

\&quot;park\_exempt\&quot; : \&quot;N\&quot;, \

\&quot;exempt\_until\&quot; : \&quot;NULL\&quot; \

} \

} \

}&quot;

);

/\* FETCH \*/

curl\_send(curl\_handle,

&quot;{\&quot;apirequest\&quot;: { \

\&quot;auth\&quot;: { \

\&quot;username\&quot;: \&quot;api\_user\&quot;, \

\&quot;password\&quot;: \&quot;SuperSecret1=\&quot; \

}, \

\&quot;action\&quot;: \&quot;fetch\&quot;, \

\&quot;command\&quot;: \

\&quot;select \* from api\_person where surname=&#39;SMITH&#39; limit 1\&quot; \

} \

}&quot;

);

/\* cleanup \*/

curl\_easy\_cleanup(curl\_handle);

}

curl\_global\_cleanup();

return 0;

}
