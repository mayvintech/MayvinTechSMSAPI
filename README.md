# MayvinTech SMS HTTP API
Sending Bulk SMS using HTTP API from your existing code

# Single SMS

	sms.mayvintech.com/api/mt/SendSMS?APIKey=yourapicode&senderid=TESTIN&channel=2&DCS=0&flashsms=0&number=91989xxxxxxx&text=test 		message&route=clickhere

	Response : {"ErrorCode":"000","ErrorMessage":"Success","JobId":"20047","MessageData":					[{"Number":"91989xxxxxxx","MessageId":"mvHdpSyS7UOs9hjxixQLvw"},{"Number":"91989xxxxxxx","MessageId":"PfivClgH20iG6G5R3usHwA"}]}


# Unicode SMS

	sms.mayvintech.com/api/mt/SendSMS?APIKey=yourapicode&senderid=TESTIN&channel=2&DCS=8&flashsms=0&number=91989xxxxxxx&text=परीक्षण सन्देश&route=clickhere

	Response : {"ErrorCode":"000","ErrorMessage":"Success","JobId":"20047","MessageData":[{"Number":"91989xxxxxxx","MessageId":"mvHdpSyS7UOs9hjxixQLvw"},{"Number":"91989xxxxxxx","MessageId":"PfivClgH20iG6G5R3usHwA"}]}

# Multiple SMS

	sms.mayvintech.com/api/mt/SendSMS?APIKey=yourapicode&senderid=TESTIN&channel=2&DCS=0&flashsms=0&number=91989xxxxxxx,91999xxxxxxx&text=test message&route=clickhere

	Response : {"ErrorCode":"000","ErrorMessage":"Success","JobId":"20047","MessageData":[{"Number":"91989xxxxxxx","MessageId":"mvHdpSyS7UOs9hjxixQLvw"},{"Number":"91999xxxxxxx","MessageId":"PfivClgH20iG6G5R3usHwA"}]}

# Schedule SMS
	
	sms.mayvintech.com/api/mt/SendSMS?APIKey=yourapicode&senderid=TESTIN&channel=2&DCS=0&flashsms=0&number=91989xxxxxxx&text=test message&schedtime=2015/12/31 22:35:00 PM&route=clickhere

	Response : {"ErrorCode":"000","ErrorMessage":"Success","JobId":"20047","MessageData":[{"Number":"91989xxxxxxx","MessageId":"BqTiw66A2UGLFV3DnwHFLQ"}]}

# Group SMS

	sms.mayvintech.com/api/mt/SendSMS?APIKey=yourapicode&senderid=TESTIN&channel=2&DCS=0&flashsms=0&number=91989xxxxxxx&text=test message&groupid=###&route=clickhere

	Response : {"ErrorCode":"000","ErrorMessage":"Success","JobId":"20047","MessageData":[{"Number":"91989xxxxxxx","MessageId":"mvHdpSyS7UOs9hjxixQLvw"},{"Number":"91999xxxxxxx","MessageId":"PfivClgH20iG6G5R3usHwA"}]}
