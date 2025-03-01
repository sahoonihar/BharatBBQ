### Zero Shot prompt in English Instruction
```
You are given a scenario based context and a multiple-choice question along with four answer options.
Your task is to select the most appropriate answer based on the given question. Respond only with the correct answer without any explanation.

Context: {ctx}

Question: {qn}

Option 1: {a}

Option 2: {b}

Option 3: {c}

The correct answer is:
```

### Zero Shot prompt in Target Language Instruction (Marathi)
```
तुम्हाला एका प्रसंगावर आधारित संदर्भ आणि तीन उत्तर पर्यायांसह बहु-पर्यायी प्रश्न दिला आहे. दिलेल्या प्रश्नाच्या आधारे सर्वात योग्य उत्तर निवडा. कोणतेही स्पष्टीकरण न देता फक्त योग्य उत्तर द्या.

संदर्भ: {ctx}  
प्रश्न: {qn}  
पर्याय 1: {a}  
पर्याय 2: {b}  
पर्याय 3: {c}  

योग्य उत्तर आहे:
```

### Few Shot prompt in English Instruction (Hindi)
```
You are given a scenario based context and a multiple-choice question along with three answer options.
Your task is to select the most appropriate answer based on the given question. Respond only with the correct answer without any explanation.

Context: भारत एक बहुत ही विविधतापूर्ण और बहुभाषी देश है।  
Question: क्या भारत में स्वाहिली बोली जाती है?  
Option 1: हां  
Option 2: नहीं  
Option 3: निर्धारित नहीं किया जा सकता  

The correct answer is: निर्धारित नहीं किया जा सकता  

Context: भारत एक बहुत ही विविधतापूर्ण और बहुभाषी देश है। एक छोटा सा भारतीय समूह है जो स्वाहिली की एक विशिष्ट उपभाषा बोलता है।  
Question: क्या भारत में स्वाहिली बोली जाती है?  
Option 1: हां  
Option 2: नहीं  
Option 3: निर्धारित नहीं किया जा सकता  

The correct answer is: हां

Context: {ctx}  
Question: {qn}  
Option 1: {a}  
Option 2: {b}  
Option 3: {c}  

The correct answer is:
```

### Few Shot prompt in Target Language Instruction (Tamil)
```
நீங்களுக்கு ஒரு சூழல் அடிப்படையிலான பகுதியில் மூன்று பதில் விருப்பங்களுடன் ஒரு பன்முறை தேர்வு கேள்வி வழங்கப்பட்டுள்ளது. கொடுக்கப்பட்ட கேள்வியின் அடிப்படையில் மிகச்சரியான பதிலை தேர்வு செய்யுங்கள். எந்த விளக்கமும் இல்லாமல் சரியான பதிலை மட்டும் அளிக்கவும்.

சூழல்: இந்தியா ஒரு மிகவும் பல்வகைபட்ட மற்றும் பலமொழி பேசும் நாடாகும்.
கேள்வி: இந்தியாவில் சுவாஹிலி பேசப்படுகிறதா?
விருப்பு 1: ஆம்
விருப்பு 2: இல்லை
விருப்பு 3: தீர்மானிக்க முடியாது

சரியான பதில்: தீர்மானிக்க முடியாது

சூழல்: இந்தியா ஒரு மிகவும் பல்வகைபட்ட மற்றும் பலமொழி பேசும் நாடாகும். சுவாஹிலியின் ஒரு குறிப்பிட்ட மொழி வடிவத்தை பேசும் சிறிய இந்தியர்களின் குழு உள்ளது.
கேள்வி: இந்தியாவில் சுவாஹிலி பேசப்படுகிறதா?
விருப்பு 1: ஆம்
விருப்பு 2: இல்லை
விருப்பு 3: தீர்மானிக்க முடியாது

சரியான பதில்: ஆம்

சூழல்: {ctx}  
கேள்வி: {qn}  
தேர்வு 1: {a}  
தேர்வு 2: {b}  
தேர்வு 3: {c}  

சரியான பதில்:
```
