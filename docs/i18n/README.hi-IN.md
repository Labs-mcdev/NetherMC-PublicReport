# NetherMC खिलाड़ी रिपोर्ट और दंड की अपील

[English](../../README.md) · [中文](README.zh.md) · [日本語](README.ja-JP.md) · **हिन्दी**

> भाषा संस्करणों में अंतर या अस्पष्टता होने पर NetherMC के नियमों के लिए अंग्रेज़ी संस्करण मान्य होगा। नियमों की भाषा या अनुवाद की समस्या [Security and quality](https://github.com/SchemaFoxLabs/NetherMC/security) में **Report a vulnerability** से बताएँ।

## रिपॉज़िटरी का उद्देश्य

Staff के ऑफ़लाइन होने पर खिलाड़ी की रिपोर्ट करने या गलत लगाए गए प्रतिबंध की अपील करने के लिए इस रिपॉज़िटरी का उपयोग करें। Staff ऑनलाइन हों तो पहले गेम में रिपोर्ट करें। Skin की रिपोर्ट केवल गेम में स्वीकार होती है।

सर्वर／वेबसाइट के bug, प्रश्न और feature request [मुख्य रिपॉज़िटरी](https://github.com/SchemaFoxLabs/NetherMC/issues/new/choose) में भेजें। Vulnerability मुख्य रिपॉज़िटरी के [निजी security route](https://github.com/SchemaFoxLabs/NetherMC/security) में रिपोर्ट करें।

## त्वरित लिंक

- **[सर्वर और समुदाय के नियम](https://github.com/SchemaFoxLabs/NetherMC/blob/main/docs/i18n/SERVER_RULES.hi-IN.md)**
- **[खिलाड़ी रिपोर्ट जमा करें](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=player_report.yml)**
- **[मीडिया प्रमाण के बिना रिपोर्ट जमा करें](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=player_report_no_media.yml)** — CSAM Content या Illegal PlayerID
- **[दंड की अपील जमा करें](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=appeal.yml)**
- **[मुख्य रिपॉज़िटरी](https://github.com/SchemaFoxLabs/NetherMC)**

## खिलाड़ी रिपोर्ट

खिलाड़ी रिपोर्ट के लिए मान्य गेम **Report-ID** आवश्यक है। Staff संबंधित गेम रिकॉर्ड से रिपोर्टकर्ता और रिपोर्ट किए गए खिलाड़ी की जाँच करते हैं। केवल ID होना पहचान सत्यापन पूरा नहीं करता।

Streamer Mode चैट का संबंधित प्रदर्शन छिपाता है। रिपोर्ट रिकॉर्ड देखने के लिए:

```minecraft-command
/report-mylist
```

पुराने रिकॉर्ड नियमित रूप से हटाए जाते हैं। मूल ID उपलब्ध न हो तो घटना वाले सबसर्वर में नई ID प्राप्त करें:

```minecraft-command
/inforeport
```

मूल घटना का समय और घटनाक्रम सही दें। नई ID हटाए गए रिकॉर्ड वापस नहीं लाती।

सामग्री को **Report-ID → घटना का संदर्भ → confidence और उसका आधार → निजी जानकारी हटाया गया प्रमाण** के क्रम में दें। अधिक confidence के लिए अधिक स्पष्ट और पूर्ण प्रमाण चाहिए। Confidence रिपोर्टकर्ता का आकलन है और सीधे दंड तय नहीं करता।

CSAM Content या Illegal PlayerID के लिए बिना मीडिया वाला फ़ॉर्म उपयोग करें। CSAM को डाउनलोड, कॉपी, अपलोड, फ़ॉरवर्ड या लिंक न करें। केवल गैर-चित्रात्मक जानकारी दें जिससे रिकॉर्ड खोजा जा सके।

## दंड की अपील

### Join Block

प्रतिबंध सक्रिय होने पर मुख्य लॉबी या किसी सबसर्वर में प्रवेश नहीं कर सकते। अधिकृत `Author` इसे हटा सकता है। कनेक्शन स्क्रीन पर:

- `block reason`
- `block-ID`

### SubServer Block

प्रतिबंध सक्रिय होने पर संबंधित सबसर्वर में प्रवेश नहीं कर सकते। अधिकृत `Author`, `Staff` या `Admin` इसे हटा सकते हैं। चैट में:

- `block reason`
- `block-ID`
- `block-duration`

### Feature Block

प्रतिबंध सक्रिय होने पर Ranked, सार्वजनिक चैट, निजी संदेश या सबसर्वर के बीच चैट जैसी सुविधा का उपयोग नहीं कर सकते। अधिकृत `Author`, `Staff` या `Admin` इसे हटा सकते हैं। चैट में:

- `disable reason`
- `disable-duration`

दंड की अवधि [सर्वर और समुदाय के नियम](https://github.com/SchemaFoxLabs/NetherMC/blob/main/docs/i18n/SERVER_RULES.hi-IN.md) के अनुसार होती है।

अपील में प्रतिबंध का प्रकार, वैकल्पिक **Player ID**, प्रभावित सबसर्वर या सुविधा, अनुमानित समय (**UTC−8**), दिखाया गया कारण, अपील का आधार और उपलब्ध निजी जानकारी हटाई गई सामग्री दें। Player ID खाली छोड़ने पर सार्वजनिक Issue में निजी संपर्क विधि (यदि उपलब्ध हो तो PM) माँगें और ID केवल उसी निजी विधि से दें।

## गोपनीयता और कार्रवाई

वास्तविक नाम, निजी संपर्क, credentials, निजी account details, संवेदनशील identifiers या असंबंधित व्यक्तिगत जानकारी सार्वजनिक न करें। Screenshot में समीक्षा के लिए आवश्यक संदर्भ रखते हुए निजी जानकारी हटाएँ।

Staff उपलब्ध समय और प्रमाणों के अनुसार कार्रवाई करते हैं। सामान्य **1–7 दिन**, या व्यस्त समय में **8–30 दिन**, शुरुआती कार्रवाई या पहले उत्तर के अनुमान हैं।

अतिरिक्त सामग्री से पहले परामर्श: `mc-contact@schemafoxlabs.com`। संवेदनशील प्रमाण भेजने से पहले उपयुक्त तरीका पूछें। **20 MiB** से बड़े attachment प्राप्त न हो सकें।
