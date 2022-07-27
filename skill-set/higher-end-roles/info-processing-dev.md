#	Skill Sets for Information Processing


This document includes skill sets for information processing, including:
+ signal processing
	- categories:
		* analog signal processing
		* continuous-time signal processing
		* discrete-time signal processing
		* digital signal processing
		* nonlinear signal processing
			+ perform in the time, frequency, or spatio-temporal domains.
			+ nonlinear ***system identification***
				- Volterra series models,
				- Block-structured models,
				- Neural network models,
				- NARMAX models, and
				- State-space models.
		* statistical signal processing
		* polynomial signal processing
		* algebraic signal processing
	- applications:
		* array processing
			+ for signals from arrays of sensors
		* audio signal processing
		* financial signal processing
		* genomic signal processing
		* seismology
		* wireless communication
	- circuit realizations, and system realizations:
		* filter design
			+ analog filters
				- passive filters
				- acive filters
			+ digital filters
				- FIR filters, finite impulse response filters
				- IIR filters, infinite impulse response filters
				- stochastic filters
		* samplers
			+ for signal acquisition
		* analog-to-digital converters, ADCs
			+ for signal reconstruction
		* digital-to-analog converters, DACs
			+ for signal reconstruction
		* signal compressors
		* digital signal processors, DSPs, or DSP processors.
			+ ISA:
				- saturation arithmetic
				- fixed-point arithmetic
			+ microarchitecture, or processor architecture:
				- deep pipelines that can be exploited by the use of single-cycle instructions.
				- support for:
					* multiply-accumulates (MACs) operations
						+ includes fused multiply-add (FMA) operations
						+ mathematical applications:
							- convolution for filtering
							- dot product
							- polynomial evaluation
						+ engineering applications:
							- FIR filters
							- Fast Fourier Transforms, FFT
					* modulo operations
						+ ring buffers
						+ bit-reversed addressing mode for FFT cross-referencing
					* time-stationary encoding
						+ to simplify VLSI design
						+ to improve software development efficiency
				- VLIW architecture
				- SIMD architecture
	- adaptive filters
	- compressive sensing
		* compressive sensing for distributed systems
		* VLSI/hardware implementations
	- multi-scale signal analysis
+ ***stream processing***, event stream processing, data stream processing, or distributed stream processing
	- Characteristics of target applications:
		* ***compute intensity***, or number of arithmetic operations per I/O or global memory reference
		* ***data parallelism***
			+ exists in a kernel if the same function is applied to all records of an input stream and a number of records can be processed simultaneously without waiting for results from previous records
		* ***data locality***
			+ limited temporal locality in signal and media processing applications where data is produced once, read once or twice later in the application, and never read again
			+ Intermediate streams passed between kernels as well as intermediate data within kernel functions can capture this locality directly using the stream processing programming model.
+ visual computing
	- image processing
		* affine transformations
			+ identity
			+ reflection
			+ rotate
			+ scale
			+ shear
		* blob detection and extraction
		* color analysis
		* edge detection
		* feature extraction
			+ image understanding
		* ***filtering***
			+ morphological filtering
		* gauging/metrology
		* graphical projection
			+ 3-D projection
		* image denoising
			+ using mathematical morphology
				- dilation
				- erosion
				- opening
				- closing
			+ improvement methods
				- smoothing method
				- historgram equalization
		* image editing
		* image restoration
		* image search engines
		* optical character recognition
		* parallel image processing
		* pixel counting
		* pixelation
		* point feature matching
		* quality improvement
			+ echo cancellation
			+ image enhancement
			+ noise reduction
		* reading:
			+ barcode
			+ data matrix
			+ 2-D barcode
				- QR code
		* segmentation
		* self-organizing maps
		* stitching/registration
		* thresholding
	- video processing
		* aspect ratio control
		* block noise reduction
		* brightness/contrast/hue/saturation/sharpness/gamma adjustments
		* color calibration
			+ primary and secondary color calibration (including hue/saturation/luminance controls independently for each)
		* color grading
		* color point conversion (601 to 709 or 709 to 601)
		* color space conversion (YPBPR/YCBCR to RGB or RGB to YPBPR/YCBCR)
		* deblocking
		* deflicking
		* deinterlacing
		* denoising
		* detail enhancement
		* digital zoom and pan
		* edge enhancement
		* film colorization
			+ tinting
		* film look
		* frame rate conversion and inverse-telecine
		* mosquito noise reduction
		* motion compensation
		* pixel art scaling
		* resizing
			+ comparison
		* super-resolution imaging
		* video matting
	- computer vision
		* see notes for "EDA & Machine Learning & AI"
	- computer graphics
		* image synthesis
			+ computer-generated imagery
			+ digital compositing
		* human-image synthesis
		* programming language -based computer graphics
		* ***extended reality***, XR
			+ span the ***reality-vrtuality continuum***
			+ computer-mediated reality
				- modulated reality
					* diminished reality
				- mixed reality
					* augmented reality
					* virtual reality
				- organic user interface, OUI
					* user interface, UI, with non-flat display
			+ ***mixed reality***, MR, ***cross reality***, or XR
				- ***augmented reality***, AR
				- augmented virtuality
				- blended spaces
					* integrated physical environments with virtual environments
					* integrated physical space with digital space
				- ***virtual reality***, VR
					* immersion into VR
						+ types:
							- narrative immersion
							- strategic immersion
							- tactical immersion
			+ ***modulated reality***
				- diminished reality
				- modified reality
			+ multimodal interaction
				- multimodal input
				- multimodal fusion
					* multimodal input
					* multimodal output
				- multimodal output
				- multimodal sentiment analysis
				- multisensory extended reality
	- visual and spatial reasoning
+ ***data compression***, source coding, bit-rate reduction
	- ["Lossless compression reduces bits by identifying and eliminating statistical redundancy. No information is lost in lossless compression."](https://en.wikipedia.org/wiki/Data_compression)
	- ["Lossy compression reduces bits by removing unnecessary or less important information."](https://en.wikipedia.org/wiki/Data_compression)
	- Can be considered as a subset of data differencing (or differential compression).
	- audio data compression, or audio compression
		* audio coding, audio coding formats, audio compression formats
			+ vocoders
				- for the following:
					* analyzes and synthesizes the human voice signal for audio data compression
					* multiplexing
					* voice encryption
					* voice transformation
				- channel vocoders
				- formant coding
				- linear predictive coding, LPC
			+ waveform coders
				- time-domain waveform coders:
					* adaptive differential pulse-code modulation, ADPCM
					* pulse-code modulation, PCM
				- frequency-domain waveform coders:
					* adaptive transform acoustic coding, ATRAC
					* sub-band coding, SBC
			+ narrowband audio coding
			+ wideband audio coding
		* [dynamic range compression](https://en.wikipedia.org/wiki/Dynamic_range_compression)
			+ downward compression
			+ upward compression
			+ downward expansion
			+ upward expansion
		* speech coding
		* speech encoding
	- image compression
	- video compression
		* uncompressing/decompressing the (compressed) video
		* video codec
			+ software or hardware that compresses and decompresses digital video
			+ codec is a portmanteau of encoder and decoder
		* video coding format, video compression format
			+ video coding specification
			+ video coding standard
+ content analysis
+ noise reduction
	- de-noising
+ semantic Web
+ event processing






This does not include speech processing, which is categorized under natural language processing.
+ It include:
	- feature extraction
		* speech recognition




##	Signal Processing


+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.



##	Stream Processing



+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.




##	Visual Computing





###	Image Processing



+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.




###	Video Processing



+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.







###	Computer Vision



+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.







###	Computer Graphics



+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.






###	Extended Reality, Augmented Reality, Cross Reality, Mixed Reality, Virtual Reality, Extended Intelligence, & Augmented Virtuality


These skill sets for extended reality, includes skill sets for the following:
+ ***augmented reality***
+ augmented virtuality
+ ***cross reality***
+ ***extended intelligence***
+ ***mixed reality***
+ ***virtual reality***


+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.








##	Data Compression



+ skill set:
	- Excellent understanding of video compression. Extensive experience with compression standards such as H.264/AVC, HEVC and VP9.
	- Strong background in image and signal processing, both algorithm design and implementation.
	- Implemented a video codec from scratch
	- Background in video quality metrics, video understanding, computer vision or machine learning
	- Experience with large-scale distributed systems and cloud-computing
	- Involvement in open-source multimedia projects (such as ffmpeg, x264, webm, VLC)
	- Design and prototype algorithms for improving the quality and performance in our cloud-based video ingest and encoding pipeline
	- Study current codec implementations and find areas for improvement in quality and speed
	- Conduct research on next-generation image and video coding and propose technology for industry standards
	- Participate in research conferences and standardization meetings
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.







##	Noise Reduction	



+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.







##	Semantic Web


+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
+ skill set:
	- BLAH.
