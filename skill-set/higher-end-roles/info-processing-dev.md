#	Skill Sets for Information Processing


##	Notes for Information Processing



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
		* [algebraic signal processing](https://en.wikipedia.org/wiki/Algebraic_signal_processing)
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
				- [saturation arithmetic](https://en.wikipedia.org/wiki/Saturation_arithmetic)
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
			+ program flow:
				- hardware-controlled looping
			+ addressing and virtual memory
				- hardware modulo addressing
					* circular buffers that need not test for wrapping
				- bit-revered addressing, as a special addressing mode
					* needed for FFTs
				- avoids the need for memory management unit
				- address generation unit, AGU, address computation unit, or ACU
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







reactive programming = asynchronous dataflow programming
+ functional reactive programming, FRP, is based on the building blocks of functional programming
	- map
	- reduce
	- filter
	- applications of FRP, by simplifying problems via the explicit modeling of time, include:
		* graphical user interfaces, GUI, development
		* robotics
		* games
		* music




+ skill set:
	- image sensor and video interfaces
		* MIPI, for Mobile Industry Processor Interface from MIPI Alliance
		* Camera Link, from Automated Imaging Association or AIA
		* GigE, Gigabit Ethernet











##	Signal Processing



+ skill set:
	- Staff LiDAR Signal Processing Software Engineer at AEye, Inc
	- AEye creates high-performance, adaptive, AI-driven LiDAR systems for vehicle autonomy, advanced driver-assistance, and robotic vision applications. AEye’s software-driven system leverages deterministic AI to capture more intelligent information with less data, enabling faster, more accurate, and more reliable perception for everything that moves. The company is based in the San Francisco Bay Area, and backed by world-renowned investors including Kleiner Perkins, Taiwania Capital, GM Ventures, Intel Capital, Continental AG, Hella Ventures, LG Electronics, Aisin, Airbus Ventures, SK Hynix, Subaru-SBI, and Tyche Partners.
	- We are looking for a smart, experienced and highly-motivated software engineer to lead the signal processing and software development activities of our next-generation lidar systems. The candidate will be responsible for defining the software architecture of the system, for developing a simulation environment from photon-detection to 3D point-cloud generation, and for executing progressive software developments for prototype and pilot systems. 
	- The successful candidate will have a degree in computer science with a focus on statistical signal processing or image signal processing and have at least 7 years of industry work experience, with a strong preference for experience with lidar, radar, or complex imaging instruments. Experience in developing C/C++ applications with a focus on algorithm design and computationally-efficient implementation is required, as well as good knowledge of Matlab. The responsibilities of the job include close collaboration with the project’s hardware team, management of the development cycle, and presentations to the company’s various technical teams.
	- Tasks, Duties & Responsibilities:
		* Define the software architecture of the system, including low-level signal processing on FPGAs. 
		* Co-develop computationally-efficient, robust signal processing algorithms.
		* Develop and progressively release versions of the system’s simulation software.
		* Develop software requirement documents to meet functional and reliability requirements.
		* Progressively develop, validate, and release code versions, including control and synchronization of system modules, user interfaces, and efficient data pipelining.
		* Prepare and present code design reviews.
	- Essential Skills & Experience Requirements (required):
		* Experience defining system software architectures.
		* Experience developing computationally-intensive simulation environments and converting them for efficient implementation in FPGAs. 
		* Deep knowledge of C/C++ and formal software design methodologies.
		* Good knowledge of Matlab. 
	- Preferred Skills & Experience (useful):
		* LiDAR or radar experience highly desirable.
		* Experience in the automotive space.
		* Experience with statistical and/or image signal processing.
		* Independent, self-starter, while working in a team setting.
		* Excellent verbal and written communication skills.
		* Experience in a fast-paced and demanding start-up environment. 
+ skill set:
	- Senior System Modeling and Algorithm Development Engineer at AEye, Inc
	- Become a leader in building a safer future.
	- AEye is the premier provider of intelligent, next generation, adaptive LiDAR for advanced driver-assistance, vehicle autonomy, and industrial applications that save lives and propel the future of transportation and mobility. We are technology thought leaders who value innovation to create reliable products that save lives. The company's 4Sight™ Intelligent Sensing Platform focuses on what matters most: enabling faster, more accurate and reliable perception for dynamic applications ranging from autonomous driving to intelligent infrastructure, which require precise measurement imaging to ensure safety and performance. AEye was founded in 2013 and is based in the San Francisco Bay Area. We believe in a creative atmosphere, with open, collaborative idea-sharing, where all employees are empowered to achieve their potential. Come experience our flexible and collaborative work environment!
	- We are looking for a deep-thinking, highly-motivated System Modelling and Algorithms Development Engineer to work with the company’s Chief R&D Officer on numerical modeling, as well as signal processing algorithm development and optimization for the company’s future lidar generations. The candidate will develop Matlab behavioral models and simulate the performance of future systems in various operating conditions. They will also propose, simulate and validate algorithms to enable efficient and optimal performance of the systems. 
	- The successful candidate will have a PhD. in Physics, EE, CS or Applied Mathematics and have at least 5 years of industry work experience, with a strong preference for the imaging, radar or lidar . A strong background in statistical signal processing is required. The responsibilities of the job include both code writing (in Matlab), presentation to the company’s technical team, and data processing of real-life lidar data. A demonstrated ability to tackle open-ended problems, define an analytical methodology to address these challenges is necessary.
	- Tasks, Duties & Responsibilities:
		* Create numerical models of conceptualized systems and validate key metrics
		* Propose and validate, both numerically and experimentally, algorithms, to improve and optimize system performance
		* Present findings to engineering and management teams
		* Work with hardware and software engineers to implement proposed algorithms
	- Essential Skills & Experience Requirements (required):
		* Experience in statistical signal processing
		* Excellent Matlab skills
		* Deep understanding of noise sources in image sensors or radar
		* PhD. in Physics, EE, CS or Applied Mathematics
	- Preferred Skills & Experience (useful):
		* LiDAR or camera-development experience is highly desirable.
		* Experience in the automotive space is highly desirable.
		* Independent, self-starter, while working in a team setting.
		* Experience in a fast-paced and demanding start-up environment. 
		* 5 years of industry work experience
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
















###	Audio Processing


+ skill set:
	- Software Engineer, Backend (Audio Team)
	- We are looking for a backend engineer to be responsible for developing APIs, building application backends, and putting in place scalable backend infrastructure across our audio platform. You will be responsible for designing scalable server side applications and robust APIs to serve our audio ML models. The ideal candidate will have experience provisioning large compute clusters for machine learning workflows and will have a strong history of supporting teams to create best practices for reliability and scalability.
	- Design, develop, and maintain internal & external APIs and micro services
	- Build robust application backends to serve our audio products
	- Define comprehensive API specifications and documentation
	- Deliver customer-facing services, including account management, identity, single-sign-on, subscription billing, and self-service support tools, integrating with existing internal systems where necessary
	- Collaborate with the frontend team and product managers to implement new features
	- Lead system architecture design & decisions
	- Manage large compute clusters for ML inference and development
	- Deliver and manage our developer and researcher productivity tools, including CI/CD pipelines for deploying new machine learning models, orchestration, continuous/progressive deployments, test environments, feature flags, and GitHub
	- Own the orchestration, deployments, request middleware and any other micro services that are required to meet the needs of our API customers
	- 8+ years of experience in backend engineering
	- Experience building ML infrastructure and working with large GPU clusters
	- Distributed system architecture design knowledge or experience with high traffic, high concurrency system development
	- Well-versed in data structures, data modeling, and database management systems as well as object and file storage systems
	- Experience coding in Go and Python
	- Evidence of interest in music / audio projects is valued
+ skill set:
	- Full Stack Engineer
	- Stability AI is a community and mission driven, open-source artificial intelligence company that cares deeply about real-world implications and applications. Our most considerable advances grow from our diversity in working across multiple teams and disciplines. We generate breakthrough ideas and convert them into tangible solutions. Our vibrant communities consist of experts, leaders and partners across the globe who are developing cutting-edge open AI models for Image, Language, Audio, Video, 3D and Biology.
	- Clipdrop provides easy to use, AI based content generation and edition tools with an expertise on images. Those tools are available on the clipdrop.co & cleanup.pictures websites, the Clipdrop mobile apps and via external HTTP APIs.
	- We are looking for a Full Stack Engineer to design and implement the architecture of our websites and accelerate the launches within our product suite. The ideal candidate will be working on the frontend and backend functionality of the website, APIs and ML Services. We’re looking for people with a passion for AI.
	- Designing and implementing the server-side architecture of the websites and public APIs including data storage, and ML services to ensure that the website can handle large amounts of traffic and data.
	- Developing the back-end functionality of the website using programming languages like Python (for ML services) and TypeScript (for APIs).
	- Implementing security measures to protect user data and prevent unauthorized access or data breaches.
	- Improve the HTML and CSS code for the website, using frameworks like TailwindCSS to ensure that it is responsive and mobile-friendly.
	- Developing the front-end functionality of the website using Typescript and tools like React / NextJS to create interactive features.
	- Work closely with product management, design, and engineering teams to deliver high-quality and user-friendly products
	- Testing and debugging the website to ensure that it is free of errors and works as intended across multiple devices and browsers.
	- Collaborate with cross-functional teams, including product managers and frontend engineers, to develop and implement new features
	- 5+ years frontend and backend experience, working in a highly scalable environment with complex release workflows
	- Experience with Python, TypeScript, HTML, CSS
	- Ale to build comprehensive API specification and documentation 
	- Understanding of working with broad engineering and product teams
	- Experience working as a member of a small agile software development team (e.g. participating in planning sessions and interpreting user stories, doing code reviews, pair programming)
	- Personal projects will be valued
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





















###	Speech Processing


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
	- Software Engineer (Media Streaming) - Periscope
	- We are a small team that develops media streaming services and client libraries for Periscope and Twitter's professional live streams. The service ingests thousands of concurrent live video feeds and serves them to viewers in a way that scales to large audiences while maintaining low latency. The service also provides low-latency transcoding and stores live streams for on-demand viewing. On the client side, our cross-platform libraries power low-latency broadcasting and playback in Periscope and Twitter mobile apps. You can learn more about our techniques for low-latency streaming at scale here (https://medium.com/@periscopecode/introducing-lhls-media-streaming-eb6212948bef) and here (https://youtu.be/RbH_2l77Pm8).
	- The role of our service and client libraries is expanding beyond the Periscope use case to handle content from an ever-increasing set of professional broadcast sources and for increasingly high-profile events. We are growing the capabilities, reliability, and quality of our service libraries to power more and more of Twitter's live video.
	- We are looking for a generalist software developer. The ideal candidate has distributed systems experience but would also be comfortable contributing on the Android and iOS client side. While experience in developing media streaming systems is a plus, the position doesn't require domain knowledge in media codecs and streaming.
	- The majority of our server-side codebase is in Go. If you have never worked in Go but you are comfortable in C, C++, or Java, you'll pick it up quickly. Experience with AWS is a plus. Our service uses EC2, DynamoDb, S3, SQS, and Redis, for example. On the client side, our codebase is primarily in C++. Experience in Objective-C and Java would also be a plus. In your day-to-day work, you will encounter media technologies including RTMP, RTP, HLS, H.264, AAC, Opus, the WebRTC native stack, and CDN infrastructure.
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
	- Design video encoding and decoding driver architecture, and provide support for application libraries;
	- End-to-end intelligent video analysis software architecture design based on GStreamer, FFMPEG, OpenCV;
	- Work with the hardware team to define the video codec IP architecture and integrated software and hardware solutions;
	- Establish a driver development environment, including pre-silicon and post-silicon testing and debugging environments, and related driver testing tools.
	- Proficient in C/C++ programming, with experience in Linux programming;
	- Familiar with video and image coding and decoding standards, including H.264/MPEG-4 AVC, H.265/HEVC, JPEG, experience in chip video codec design is preferred;
	- Knowledge of one or more video encoding and decoding APIs and experience in architecture design, such as VDPAU, VA-API, OpenMax, FFMPEG, GSTREAMER, etc.;
	- Those with computer vision and IVA related knowledge and experience in architecture design are preferred, such as DeepStream, OpenCV, Visionworks, etc.;
	- Strong ability to analyze and solve problems, including stress test stability issue, E2E performance optimization;
	- Possess strong communication skills, independent working ability and team driving ability, and can coordinate all relevant teams to promote the completion of the plan;
	- Bachelor degree or master degree, computer related major;
	- At least 5 years of work experience.
+ skill set:
	- Video Codec Algorithm Engineer
	- We are looking for a highly ambitious and enthusiastic individual, who is able to excel in a technically meaningful environment, to fill in the position of video codec algorithm engineer. In this role you will work as an individual contributor in a small and dynamic team, developing video compression and processing algorithms for current and future Apple products!
	- Expert knowledge in video and image coding principles, algorithms, and techniques
	- Expert knowledge and experience in video compression standards, such as H.264, HEVC, VVC, VP9, AV1
	- Experienced in assessing visual quality using both objective metrics and subjective techniques
	- Excellent software design and debugging skills and solid programming skills in C/C++
	- Good written and oral communication skills
	- Familiarity with video processing algorithms such as scaling, noise reduction, tone mapping, etc would be a plus
	- Familiarity with the latest computer vision and deep learning technologies would be a plus
	- This position requires a highly self-directed individual with strong creative and analytic skills and passion for video coding and processing technologies. Your responsibilities include, but not limited to:
		* Invent and implement new video compression/processing algorithms that works well with existing hardware
		* Spearhead R&D in upcoming new media compression technologies and standards
		* Work with other hardware/software architects to define and implement media features and algorithms for future products
	- MS/Ph.D. in Computer Science, Computer Engineering, Electrical Engineering, or closely related fields
	- The base pay range for this role is between $138,900 and $256,500, and your base pay will depend on your skills, qualifications, experience, and location.
+ skill set:
	- Video Codec Algorithm Engineer
	- We are seeking a passionate Video Codec Algorithm Engineer to research and develop video compression algorithms/video encoder/decoder to improve real-time video quality and performance on Zoom video products.
	- Research and evaluate algorithms currently used in related applications.
	- Possess strong skills in the areas of development and real-time implementation of video encoder/decoder.
	- Participate in research and developing new video codec standard
	- Design and implement video compression algorithm to improve the quality
	- Design new algorithms to tackle new and existing problems.
	- Ph.D. or Master’s degree in Computer Science or Electrical Engineering or related field.
	- Prior industry experience is preferred but not required.
	- Proficient in C++ and C programming
	- Prior experience of x86/64 or arm assembly coding.
	- Solid research background in video codec.
	- Experienced in video coding standards such as VVC, AV1, HEVC, H.264/AVC, SVC, VPx.
	- Strong analytical and research skills.
	- Excellent written and verbal communication skills. Strong team player.
	- The candidate needs to be based in Singapore or willing to relocate to SIngapore.
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




+ 3-D interactive tools and libraries:
	- Unity
	- Unreal
	- OpenGL
	- WebGL
+ skill set:
	- OpenGL
	- Vulkan
	- OptiX
+ skill set:
	- build commercial-grade embedded systems
	- QNX and automotive grade Linux (AGL)
	- MISRA C++
	- AUTOSAR C++
	- trusted platform module (TPM) technology
	- standards for cybersecurity (ISO21434) and functional security (ISO26262)
+ SOTIF, safety of the intended functionality
+ Knowledge of Linux and/or Windows programming and computer graphics including OpenCL\*, OpenGL\*, DirectX\*
+ skill set:
	- Senior 3D Pipeline Engineer - Simulation
	- Apple’s Special Project Group is seeking a Senior 3D Pipeline Engineer to help advance innovative simulation for autonomous technologies. You will directly play a role developing and maintaining tooling for our 3D content creation pipeline core to our simulation efforts. Your work will advance our ability to develop, test, and verify mobile autonomous systems.
	- Strong experience with C++ and Python, software fundamentals and experience debugging complex software
	- 5+ years of experience working with 3D data in real time, animation, or visual effects film pipelines
	- Bonus points for familiarity with computer graphics systems and game engines (e.g. Unreal, Unity, etc); 3D design tools (Blender, Maya)
	- Proficient in software development practices including design, estimation, code reviews, and automated testing.
	- Excellent multi-functional collaboration skills: demonstrated ability to work across an organization with algorithm designs, verification engineers, and other technical departments.
	-  You’ll join a fantastic team of hardworking engineers and researchers with deep experience in robotics, machine learning, and software engineering. We hope you are passionate about the values that drive us:
	- Passion for the mission: We’re here to make something phenomenal. We seek whatever work is right for the product and strive for the best possible results.
	- Modesty: The right answer is more meaningful than being right. We search for solutions as a team and value clear-eyed feedback
	- Lean habits: You can’t grow without limits. Time constraints and big goals inspire us to sharpen our focus and learn to make extraordinary decisions.
+ skill set:
	- Graphics Rendering Software Engineer - Apple Vision Pro
	- Apple is where individual imaginations gather together, committing to the values that lead to great work. Every new product we build, service we create, or Apple Store experience we deliver is the result of us making each other’s ideas stronger. That happens because every one of us shares a belief that we can make something wonderful and share it with the world, changing lives for the better. It’s the diversity of our people and their thinking that inspires the innovation that runs through everything we do. When we bring everybody in, we can do the best work of our lives. Here, you’ll do more than join something — you’ll add something.
	- Apple Vision Pro is a revolutionary spatial computer that seamlessly blends digital content with your physical space. It will allow us to do the things we love in ways never before possible — all while staying connected to the people around us.
	- We are looking for a driven and dedicated Graphics Rendering Software Engineer to join our fast-paced team. As a member of the Face and Body technologies team, you have the unique and rewarding opportunity to work on upcoming releases of Apple products that delight and inspire millions of people every day. We invite you to contribute to our current spatial computing software platform and craft the future of this technology.
	- 2+ years of relevant industry experience with a track record of successful projects
	- Excellent coding skills in C/C++
	- Extensive experience with at least one of the current graphics APIs (Metal, Direct3D 12, Vulkan, etc.)
	- Experience with Shader Languages (HLSL/GLSL, Metal shaders) and writing custom shaders
	- Understanding of entire graphics pipeline, from CPU instructions to emitted photons
	- Knowledge of modern renderers and rendering techniques
	- 3D math skills (linear algebra)
	- Excellent software prototyping, problem solving and debugging skills with performance-oriented mindset
	- Basic knowledge and experience in 3D computer vision and image processing
	- Excellent communication and teamwork skills
	- Experience with AR/VR rendering technologies is a plus
	- Creativity and curiosity for solving highly complex problems
	- Apple's Vision Products Group (VPG) Face and Body technologies team is looking for a skilled Graphics Rendering Software Engineer to contribute to state-of-the-art real-time rendering techniques, in particular related to volumetric rendering.
	- Our team delivers algorithms that power Apple Vision Pro's Eyesight, Persona and other visionOS technologies. In this position, you will have the opportunity to be part of our extraordinary team of Computer Vision and Deep Learning researchers and engineers to discover and build solutions to previously-unsolved challenges and push the state of the art in Computer Vision / Machine Learning, 3D Reconstruction and Neural Rendering algorithms that will change the way people experience the world!
	- BS, MS or PhD in computer vision, machine learning, computer science, computer engineering or related fields
+ skill set:
	- 8+ years of professional experience shipping software with a specialization on Rendering and Graphics (2D or 3D), ideally with experience in C++/WebAssembly.
	- Experience working on game engines, client-side technologies and platforms, and rendering APIs like OpenGL, WebGL, WebGPU, Vulkan, Metal, or DirectX.
+ skill set for Senior Research Scientist, Hyperscale Graphics Systems:
	- NVIDIA is searching for outstanding senior researchers for the reinvention of interactive 3D systems for games, virtual film production, and beyond, using new ideas in cloud/distributed computing, ray tracing, and machine learning. The ideal candidate is an established thought leader in academic or industry with deep experience creating technology for 3D environments, publishing and presenting at industry and academic conferences, and hands-on implementation. This role requires high-level knowledge of multiple areas within production workflow and tools, physical simulation, networking, rendering, and character animation and AI. Datacenter experience with liveops, multiuser environments, and user created content is highly valued. Come join a diverse research group that works on hard and meaningful problems; that consistently publishes at top venues in graphics, computer vision, and artificial intelligence; and that values real impact on NVIDIA products and the industry at large.
	- Work independently on research projects and lead small teams as a principal investigator
	- Select and solve complex problems in a multi-year research agenda
	- Mentor graduate interns
	- Implement experiments and research prototypes in C++, Python, CUDA, and other domain-appropriate tools
	- Influence research initiatives across the company and in the field
	- Protect strategic inventions with patents
	- Publish and present findings in top-tier venues
	- Collaborate with leading experts outside of the company
	- Work with product groups to identify future research needs and transfer technology
	- Participate in top-tier conference and journals as reviewer, session chair, program committee member, or editor/chairperson 
	- A Ph.D. or comparable research experience or equivalent experience in Computer Science/Engineering or a related field.
	- 5+ years of relevant work experience.
	- Excellent knowledge of theory and practice in computer graphics, cloud/distributed computing, ray tracing, and machine learning
	- Expertise with programming systems such as C++, Python, CUDA, and deep learning frameworks such as TensorFlow and PyTorch. Very strong programming skills.
	- A track record of research excellence demonstrated in publications at leading conferences and journals and other research artifacts such as software projects
	- Great presentation and interpersonal skills.
+ skill set:
	- NVIDIA Research’s "Hyperscale Graphics Systems" research team is looking for a graphics software engineer. Our team's mission is to reinvent interactive 3D systems for a world where the graphics system is not one GPU, but the entire data center. We aim to reimagine metaverse simulations, virtual film production, game engines, and beyond using new ideas in cloud/distributed computing, ray tracing, and artificial intelligence. That innovation happens on top of rendering algorithms and software, AI frameworks, cloud and web development stacks, and NVIDIA's Omniverse platform. We need a skilled, creative, and self-starting graphics software engineer to help us build that future. Come join a diverse research group that works on hard and meaningful problems; that consistently publishes at top venues in graphics, computer vision, and artificial intelligence; and that values real impact on NVIDIA products and the industry at large.
	- Build research infrastructure on top of open-source rendering frameworks such as NVIDIA's Falcor, a physically-based rendering system and collection of software modules designed to maximize graphics R&D productivity
	- Help integrate research infrastructure, such as Falcor and hyperscale research systems, into NVIDIA Omniverse
	- Collaborate with researchers, product engineers, and architects across the company working on aspects of hyperscale graphics
	- Help implement and maintain modern full-stack cloud systems, working with technologies from GPU containerization to WebRTC
	- Participate in tech transfer with engineers around NVIDIA as ideas "graduate" from research to product
	- Extend and maintain continuous integration, nightly testing, and other professional software development systems to ensure robust and dependable infrastructure
	- B.S., M.S. or Ph.D. in computer science or equivalent experience
	- Strong programming skills in C++, Python, and HLSL/GLSL
	- 3+ years of experience with 3D graphics development
	- Experience with parallel programming on both CPUs and GPUs
	- Understanding of and experience with modern graphics APIs: Direct3D, Vulkan, and/or OptiX
	- A demonstrated passion for participating in collaborative interdisciplinary research teams.
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
	- Work in an agile, CI/CD based, test-driven development environment
	- Semantic Web (RDF/SPARQL)
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
