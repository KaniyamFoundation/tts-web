வணக்கம்,

இன்று http://tts.kaniyam.com என்ற இணைய வழி தமிழ் உரை ஒலி மாற்றியை வெளியிடுவதில் பெருமகிழ்ச்சி கொள்கிறோம்.

இது ஒரு கட்டற்ற மென்பொருள்.
மூலநிரல் - https://github.com/KaniyamFoundation/tts-web
Ubuntu/Linux, Python, Django, Celery, MySQL, ஆகியவை கொண்டு உருவாக்கப்பட்டது.

## அறிமுகம்

இந்த மென்பொருள் உங்கள் தமிழ் உரைக்கோப்புகளை (text file) ஒலிக்கோப்புகளாக (MP3) மாற்ற உதவுகிறது. (TTS Text-To-Speech)
எப்படி மாற்றுவது?

*  இதில், நீங்கள் ஒரு கணக்கு உருவாக்கவும். http://tts.kaniyam.com/signup/
* உங்கள் மின்னஞ்சலுக்கு, புது கணக்கை உறுதி செய்ய, ஒரு இணைப்பு வரும். அதை சொடுக்கவும்.
* புகுபதிகை செய்யவும். (Login)
* http://tts.kaniyam.com/upload/ பக்கத்துக்கு சென்று, ஒரு தமிழ் உரைகள் கொண்ட கோப்பை பதிவேற்றம் செய்யவும்.
* இப்போது, பின்புலத்தில் உங்கள் உரைக்கோப்பு, ஒலிக்கோப்பாக மாற்றம் செய்யப்படும். இதற்கு சற்று கால அவகாசம் ஆகும். சில நிமிடங்கள் முதல் சில மணி நேரங்கள் கூட ஆகலாம். இந்த காத்திருப்பு காலம், உங்கள் கோப்பின் அளவையும், மொத்தமாக அனைவரும் ஏற்றியுள்ள கோப்புகளின் எண்ணிக்கை, அவற்றின் வரிசைகளைப் பொறுத்து மாறும்.
* MP3 ஆக மாற்றியபின், உங்கள் மின்னஞ்சலுக்கு பதிவிறக்கம் செய்வதற்கான இணைப்பு வந்து சேரும். உங்களுக்கான http://tts.kaniyam.com/ முகப்பு பக்கத்தில் காட்டப்படும் உங்கள் கோப்புகளின் பட்டியலிலும் பதிவிறக்க இணைப்பு இருக்கும்.
* இணைப்பை சொடுக்கி, நீங்கள் ஒலிக்கோப்பை பதிவிறக்கம் செய்து கொள்ளலாம்.

## அடிக்கடி கேட்கப்படும் வினாக்கள்

### எந்த வகை கோப்புகளை பதிவேற்றலாம்?
ஒருங்குறி (Unicode) எழுத்துருவில் உள்ள, txt வகைக் கோப்புகளை மட்டுமே ஏற்றலாம். அதிக பட்சம் 100 MB இருக்கலாம்.

### எனது தனிப்பட்ட கோப்புகளை ஏற்றலாமா? 
அதி இரகசியம் காக்கப்பட வேண்டியவை எனில் வேண்டாம். எந்த இணைய வழி தளத்தையும் நம்பாதீர். இது கட்டற்ற மென்பொருள்தானே. நீங்களே உங்கள் குனு/லினக்சு கணினியில் நிறுவி விடலாம். மற்றபடி, பொதுவான கோப்புகளை ஏற்றலாம். உங்கள் உரைக்கோப்புகளையும், ஒலிக்கோப்புகளையும் உங்களைத் தவிர, பிற பயனர் எவரும் அணுகாதபடியே கடும் கட்டுப்பாட்டு அமைப்புகளை சேர்த்துள்ளோம்.

### ஏன் பயனர்கள் பதிவு செய்ய வேண்டும்? பதிவு செய்யாமல் பயன்படுத்த இயலாதா?
இப்போது உள்ள TTS ஆனது, உரையை ஒலியாக மாற்ற அதிக நேரம் எடுத்துக் கொள்கிறது. சில நிமிடங்கள் முதல், சில மணி நேரங்கள், நாட்கள் கூட ஆகலாம். அவ்வளவு நேரமும் ஒரு பயனர், உலாவியை திறந்து வைத்திருக்க முடியாது. எனவே, பதிவு செய்யப்பட்ட மின்னஞ்சலுக்கு, பதிவிறக்க இணைப்பு அனுப்புகிறோம். இதை விட வேறு சிறந்த யோசனைகள் இருந்தால், எமக்கு எழுதுங்கள். அவற்றை செயல்படுத்துவோம்.

### எத்தனை நாட்கள் MP3 கோப்புகள் சர்வரில் இருக்கும்? 
இப்போதைக்கு சோதனை முறையில் 3 நாட்கள் வைத்திருப்போம். பிறகு அவை தானாகவே அழிந்துவிடும்.

### ஏன் ஆண் குரல் மட்டும்? பெண் குரல் இல்லையா? 
பெண் குரல் சோதனையில் உள்ளது. விரைவில் சேர்ப்போம்

### ஏன் தமிழ் மட்டும்? பிற மொழிகள்? 
பிற மொழிகளுக்கான கட்டற்ற உரை ஒலி மாற்றிகளை ஆய்ந்து வருகிறோம். தக்கனவற்றை சேர்ப்போம்.

### இந்த மென்பொருள் பாதுகாப்பனதா? 
ஓரளவுதான். இது ஒரு கட்டற்ற மென்பொருள். இதன் மூல நிரலை இங்கே ( https://github.com/KaniyamFoundation/tts-web )பெற்று, நீங்களே சோதித்துக் கொள்ளுங்கள். மேலும் பல்வேறு பாதுகாப்புக்கான பல்வேறு செயல்கள் செய்யப்பட உள்ளன. உதாரணமாக SSL சேர்த்தல், கோப்புகளை மறைகுறியாக்கம் Encrypt) செய்தல் போன்றவை.

### இதை விண்டோசில் நிறுவலாமா? 
முடியாது.

### ஏன்? 
உங்களிடம் இரு சக்கர வாகனம்தான் இருக்கிறது என்றால், அதில் கார் சீட்டை பொறுத்தி ஓட்ட முயலமாட்டீர்கள் தானே.

## பங்களித்தோர் -
ஊர் கூடி தேர் இழுக்கும் பெரும் பணி இது.
### IndicTTS
IndicTTS (https://www.iitm.ac.in/donlab/tts/index.php) எனும் திட்டம் வழியாக IIT Madras ம் SSN College of Engineering ம் இணைந்து, தமிழுக்கு ஒரு உரை ஒலி மாற்றி உருவாக்கி, கட்டற்ற மென்பொருளாக வெளியிட்டுள்ளனர். ( பிற மொழிகளுக்கும் ஆய்வுகள் நடந்து வருகின்றன ).

**இதில் பங்களிப்போர்**

* ஹேமா - hema@cse.iitm.ac.in
* அஞ்சு - anjuthomas95@gmail.com
* நாகராஜன் - nagarajant@ssn.edu.in

### இம்மென்பொருளை, உபுண்டு லினக்சு கணினியில் எளிதில் நிறுவும் வகையில் நிரல் எழுதியோர்

* மோகன் - mohan43u@gmail.com
* பத்மகுமார் - padmakumar.rajan@gmail.com
* சீனிவாசன் - tshrinivasan@gmail.com

நிரல் இங்கே - http://github.com/tshrinivasan/tamil-tts-install

### பலவகைகளில் சோதனைகள் செய்தவர்

கலீல் ஜாகீர் - jskcse4@gmail.com

### இதை இணைய வழி மென்பொருளாக எழுதி, நிறுவி, பராமரிப்பவர்

பாலாஜி - fossbalaji@gmail.com 

### இதற்கான சர்வரை நன்கொடையாக அளித்தவர்கள் -

E2E Networks, www.e2enetworks.com

### இதற்கான யோசனைகள், திட்டங்கள், ஆலோசனைகளை அளித்தோர்

இந்திய லினக்சு பயனர் குழு, சென்னை - Indian Linux Users Group, Chennai http://ilugc.in

கட்டற்ற மென்பொருள் அறக்கட்டளை, தமிழ்நாடு - Free Software Foundation, TamilNadu http://fsftn.org

### ஒருங்கிணைப்பு  
கணியம் அறக்கட்டளை - http://kaniyam.com/foundation

தொடர்புக்கு kaniyamfoundation@gmail.com

### பின் வரும் மாற்றங்களை விரைவில் எதிர் பார்க்கலாம்

* பெண் குரல்
* இன்னும் தரமான உரை ஒலி மாற்றம்
* பிற மொழிகளுக்கான உரை ஒலி மாற்றம்
* REST API வசதிகள்

## எப்படி பிழைகளை புகார் செய்வது?
Github.com ல் ஒரு கணக்கு உருவாக்கி, https://github.com/KaniyamFoundation/tts-web/issues இங்கு உங்கள் புகார்கள், பிழைகள், யோசனைகள், ஆலோசனைகளைத் தெரிவிக்கலாம்.


## நீங்களும் பங்களிக்கலாமே

* கட்டற்ற மென்பொருட்களைப் பயன்படுத்துவதும், அவற்றை பிறருக்கு அறிமுகம் செய்வதுமே பெரும் பங்களிப்பு.
* இதை பயன்படுத்தி, பிழைகளையும், மேம்படுத்துவதற்கான யோசனைகளையும் எங்களுக்கு எழுதுங்கள்
* இது பற்றிய பரப்புரைகளை ஊடகங்கள், செய்தித்தாள்கள், சமூக வலைதளங்களில் எழுதுங்கள்.
* நன்கொடை அளியுங்கள் - இது போன்ற பல கட்டற்ற மென்பொருட்களையும், வளங்களையும் உருவாக்க ஆவன செய்து வரும் கணியம் அறக்கட்டளைக்கு நன்கொடை அளியுங்கள்

## வங்கிக் கணக்கு விவரங்கள்
```
Kaniyam Foundation
Account Number : 606 1010 100 502 79
Union Bank Of India
West Tambaram, Chennai
IFSC – UBIN0560618
```
நன்கொடை விவரங்களை kaniyamfoundation@gmail.com க்கு மின்னஞ்சல் அனுப்புங்கள்.




We are happy to release the Online Tamil Text to Speech conversion software at http://tts.kaniyam.com

This is a Free Software.
Get the source code here  - https://github.com/KaniyamFoundation/tts-web
This is made with Ubuntu/Linux, Python, Django, Celery, MySQL etc.


## Introduction

This online software can convert your Tamil text files to audio files in MP3 format. (TTS = Text To Speech)

## How to Convert?

1. Create an Account here http://tts.kaniyam.com/signup/
2. You will receive an email with account activation link. Click that link.
3. Do login
4. Goto http://tts.kaniyam.com/upload/ Upload a file with tamil unicode text.
5. Now, that text file will be converted as audio file (mp3) in background. It may take some time for this. From few minutes to few hours too. This wait time depends on your file size, Total number files being uploaded, and queue order of your file etc.
6. Once it is converted as MP3, you will receive an email with download link. It will be displayed on your home page too. http://tts.kaniyam.com/
7. Click the link and Download the MP3 file.


## Frequently Asked Questions

### **What types of files can be uploaded?**
Only Tamil Unicode text files are supported. File can be upto 100 MB.

### **Why do I have to register? Can I upload files without registering?**
The TTS conversion is slow process. It may take few hours to complete. Waiting with browser tab open for few hours is not possible. To notify the user, after the file conversion, sending email is one simple way. Thats why we ask for registering. Tell us if there are even better ways.

### **Shall I upload my private files?**
If you have more private, secret files, dont upload here. Dont upload to any of the online applications.
Anyhow, this is Free/Open Source Software. you can install this in your home ubuntu/linux computer. 

You can upload here general files, which are not too private to you. We have made essential settings so that you only can access your files. No other can access your files. (Except admins and server providers).

### **How long the MP3 files will be there on the server?**
For now, we keep them for 3 days as testing. After three days, they will be deleted automatically.

### **Why there is only male voice? Why cant we have female voice?**
Female voice is in testing. Will add soon.

### **Why there is only Tamil TTS? We need for other languages too.**
Other languages TTS are in our action items. We are yet to find suitable TTS and how to use them. If you know about them, let us know.

### **Is this software a safer one?**
Not 100%. As this is Free/Open source software, you can check its code at https://github.com/KaniyamFoundation/tts-web There are many security related things to do like adding SSL. Encrypting the files and hard disks etc. We will do them soon.

### **How to install this on Windows?**
No. Not possible.

### **Why?**
When you have only two wheeler vehicle, we hope, you wont try to fit a car seat on it and ride.

## Contributors 

This is done with the awesome contributions of many.

### IndicTTS
**IndicTTS** (https://www.iitm.ac.in/donlab/tts/index.php) is a project driven by IIT Madras. SSN College of Engineering and IIT Madras jointly developed TTS for Tamil and released as Free/Open Source Software. Research works for other languages are going on.


**Contributors**

* Hema - hema@cse.iitm.ac.in
* Anju - anjuthomas95@gmail.com
* Nagarajan - nagarajant@ssn.edu.in

### The following friends, made the tamil tts installation simple as running a shell script.

* Mohan - mohan43u@gmail.com
* Padmakumar  - padmakumar.rajan@gmail.com
* Shrinivasan - tshrinivasan@gmail.com

Script is here - http://github.com/tshrinivasan/tamil-tts-install

### Testing and improvements are done by

Khaleel Jageer - jskcse4@gmail.com

### Djaango web application written and maintained by 

Balaji - fossbalaji@gmail.com


### The Server is donated by 

E2E Networks, www.e2enetworks.com

### All the plans, ideas, requirements, action items are provided by

Indian Linux Users Group, Chennai http://ilugc.in
Free Software Foundation, TamilNadu http://fsftn.org

### Organized by 
Kaniyam Foundation - http://kaniyam.com/foundation

**Contact**
kaniyamfoundation@gmail.com

### **The below updates will be provided soon.**

1. Female Voice
2. Better TTS
3. TTS for other languages
4. Rest API


## How to report issues?

* Create an account in Github.com 
* Create an issue here https://github.com/KaniyamFoundation/tts-web/issues 
* Write all the errors, issues, new ideas etc

## You can Contribute

1. Using the Free/Open Source Software and introducing them to others itself a great contribution.
2. Use this. Report us on any bugs and required features, ideas etc.
3. Spread the news about this in Social media, Print media etc.
4. Donate us. Kaniyam Foundation is working on building such open source software and open digital resources. Your donations will help us do to more.


## Bank account details
```
Kaniyam Foundation
Account Number : 606 1010 100 502 79
Union Bank Of India
West Tambaram, Chennai
IFSC - UBIN0560618
```


* Send your name, donation details to kaniyamfoundation@gmail.com 


