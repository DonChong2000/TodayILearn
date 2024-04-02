latest Standard [Speedometer 3.0](Speedometer%203.0.md)

ref: > [The ultimate guide to web performance - YouTube](https://www.youtube.com/watch?v=0fONene3OIA)
# Measuring Matrixs
## LCP - Largest Contentful paint
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
- Visual stability of a page as it loads, or simply saying Element should not jumping around in the page
- Good <0.1, mid < 0.25, poor > 0.25
- Improve ways
	- Image should always have width and height / CSS aspect-ration
	- Handle Ads injection



# Tools
- Web Vitals (It can pinpoint to the problem)
-  Unlighthouse (Benchmark all site performance)