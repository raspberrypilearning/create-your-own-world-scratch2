## कॉइन एकत्र करना

जब आपका `प्लेयर` स्प्राइट दुनिया में गति करता है, तो वे कॉइन एकत्र कर सकते हैं।

+ अपने प्रोजेक्ट में `कॉइन`{:class="blockdata"} नामक नया वेरिएबल जोड़ें।

+ `कॉइन` स्प्राइट पर राइट-क्लिक करें और **दिखाएँ** चुनें।

![screenshot](images/world-coins.png)

+ अपने `कॉइन` स्प्राइट में कोड जोड़ें, ताकि यह केवल कक्ष 1 में दिखाई दे।

+ अपने `कॉइन` स्प्राइट में कोड जोड़ें, ताकि जब `प्लेयर` स्प्राइट `कॉइन` 'उठाने के लिए' इसे छुए, तो `कॉइन`{:class="blockdata"} वेरिएबल में `1` जुड़ जाए।

	```blocks
		जब ⚑ क्लिक किया गया हो
		<[प्लेयर v] को छू रहा है?> होने तक ठहरे
		[कॉइन v] से (1) बदले
		रोक दे [other scripts in sprite v]
		छुपाएँ
	```

	कोड `रोक दे other scripts in sprite`{:class="blockcontrol"} आवश्यक है, क्योंकि एकत्र होने पर `कॉइन` स्प्राइट कक्ष 1 में दिखाई न दे।

+ आपको गेम के आरंभ में अपने `कॉइन`{:class="blockdata"} वेरिएबल को `0` पर सेट करने के लिए, कोड भी जोड़ना होगा।

+ अपने प्रोजेक्ट का परीक्षण करें — कॉइन एकत्र करने से आपके `कॉइन` का स्कोर `1` में बदलना चाहिए।

--- challenge ---
### चुनौती: और कॉइन
क्या आप अपने गेम में और कॉइन जोड़ सकते हैं? वे भिन्न-भिन्न कक्षों में हो सकते हैं, और कुछ कॉइन की सुरक्षा गश्त लगाने वाले दुश्मनों द्वारा भी की जा सकती है!

--- /challenge ---
