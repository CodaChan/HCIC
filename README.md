HCIC( Human-Computer interaction, Chinese ) is a dataset for natural language human-machine interaction, containing natural language instructions with their corresponding structured logical forms.

The IoT platform human-computer interaction dataset marked by Wang Yongmei's team in Anhui Beidou Precision Agricultural Information Engineering Laboratory is used for the scientific research and teaching tasks of Anhui Beidou Precision Agricultural Information Engineering Laboratory, as well as for the team to carry out the application projects of IoT platform human-computer interaction. All copyrights of the dataset belong to Anhui Beidou Precision Agricultural Information Engineering Laboratory. The laboratory is open source free of charge for domestic and foreign universities, research institutes, enterprises and individual researchers, and the dataset here is open source for the basic part. If any institution or individual intends to use HCIC for commercial purposes, please send an email to negotiate the license agreement (xuchen21@stu.ahau.edu.cn ).

Our dataset is presented in the following format

```json
{
    "text": "请帮我把客房和主卧的电风扇的电源关闭",
    "spo_list": [
        {
            "predicate": "地点与设备",
            "object_type": "设备",
            "subject_type": "地点",
            "object": "电风扇",
            "subject": "客房"
        },
        {
            "predicate": "设备与属性",
            "object_type": "属性",
            "subject_type": "设备",
            "object": "电源",
            "subject": "电风扇"
        },
        {
            "predicate": "属性与属性值",
            "object_type": "属性值",
            "subject_type": "属性",
            "object": "关闭",
            "subject": "电源"
        },
        {
            "predicate": "地点与设备",
            "object_type": "设备",
            "subject_type": "地点",
            "object": "电风扇",
            "subject": "主卧"
        }
    ]
}
```

Users are also welcome to send any feedback to the above email address, and our staff will reply promptly.

Authors: Xu Chen, Hao Wu, Zhipeng Xu (members of Wang Yongmei's team at Beidou Precision Agricultural Information Engineering Laboratory, Anhui Province) Thanks to our supervisor, Prof. Wang Yongmei, for her guidance!