How to get text from speech?
Note: for Chinese language 


It's important to normalize the audio. 

"speechrecognition" package has low performance for Chinese.

https://blog.csdn.net/devid008/article/details/129656356

Baidu API requries registeration 


def preprocess_audio(file_path):
    audio = AudioSegment.from_file(file_path)
    audio = normalize(audio)  # 正规化音频，平衡音量水平
    return audio
    
This code be helpful.


Google Cloud 
You need to get the API and pay for longer aduio 
create a json file 
download it 
Google API has much better performance than speechrecognization  
It has problems with long audio. 


public-education focused API 


How to calculate the 

