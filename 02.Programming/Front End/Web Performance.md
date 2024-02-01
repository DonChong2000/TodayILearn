# LCP - Largest Contentful paint
- Time it takes to load the single largest visible element in the viewport.
- Good <2.5s, mid < 4s, poor >4s
- Improve ways
	-  Identify from network water fall (F12)
	- Reduce resources load time, compress image, use webp
	- Use a CDN
	- Prevent JS blocking load (prevent the need of running JS before rendering )
	- Preload, fetchpriority


## FIP - First Input Delay
- Time from user interact with the page till the browser process it
- Good <100ms, mid < 300ms, poor > 300ms
- Improve ways
	- Reduce JS Execution Time
		- webworker
		- lazy loading


## CLS - Cumulative layout shift
- Element should not jumping around in the page
- Good <0.1, mid < 250ms, poor > 250ms
- Improve ways
	- Image should always have width and height / CSS aspect-ration