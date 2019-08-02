# single_html5_generator
a solution to generate single html5 file from Cocos Creator

1. Build project with configuration:
![](http://www.mrsep18.com/wp-content/uploads/2019/07/EE86D84A-BAD5-45B0-ADC8-4B15EC860271.png)

Checklist: 
	- Select `Web Mobile` as Platform
	- Uncheck the option`Inline all SpriteFrames`.

2. copy `build-templates` and `html_generator` to the project root path.
	
3. `python3 integrate_res_in_html.py`
4. if the html file size exceeds the 2M limit, resource compress is required:
	- Images: [TinyPNG](https://tinypng.com/ "TinyPNG")
