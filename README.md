<h2> Add Some cool foss apps to your rom during build time </h2>
<br />
Current Apps that we have in defualt branch :- <br />
SimpleGallery - Replaces Gallery2 <br />
OpenCamera - Replaces Snap <br />
FossBrowser - Replaces Jelly and Browser2 <br />

<br />
To use this vendor :-
<br />
1. In your android build root run following command
<br />
 
git clone https://github.com/clhexftw/vendor_foss ./vendor/foss
<br />
2. Than pick this commit in your dt or vendor :- 
https://github.com/clhexftw/android_device_xiaomi_vayu/commit/4487a7e9631c2b30b681acc347a59fd418176548
<br />
3. Build Android