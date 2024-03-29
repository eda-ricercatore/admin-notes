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
	- We are looking for a Senior Signal Processing Scientist to join our acoustic team in Paris and help us differentiate the end-to-end Sonos experience for customers.
	- You will be responsible for the audio signal processing stage that plays a fundamental role across all of our acoustic engines including wake word detection, speaker identification, and speech-to-text. Data augmentation and speech enhancement are crucial to ensure the robustness of the speech processing modules (in the presence of external noise, reverberation etc). As a Senior Signal Processing Scientist, you will work at the intersection of machine learning and digital signal processing. You will help our machine learning scientists improve the generalization ability of their models by developing state-of-the-art acoustic data augmentation techniques to enhance the size of our training datasets. Additionally, you will be in close contact with the DSP engineers to help them develop processing techniques specifically tailored to speech processing.
	- 2+ years experience in acoustic data augmentation (pitch and gain control, noise and room simulation etc) within the context of speech recognition.
	- Experience with Python and with version control.
	- MS / PhD in Computer Science, Electrical Engineering or related technical field.
	- Ability to formalize, analyze and solve complex problems.
	- Excellent verbal and written communications skills in English.
	- Track record of published papers in peer-reviewed journals or conferences
	- Experience with other general purpose programming languages (C++, Rust etc) and Docker
	- Knowledge of acoustic DSP techniques for speech enhancement (noise control, dereverberation, echo cancellation, beamforming etc)
	- Knowledge of Machine Learning, Deep Learning, and related frameworks (TensorFlow or PyTorch)
+ skill set for SENIOR SYSTEM/DSP ALGORITHM ARCHITECT
	- We are looking for experienced system architect who can design algorithms for the whole system and product, optimize algorithm and system design with realist constraints, define system specification for Hardware and ASIC, define fixed point specification for algorithm and hardware.
	- Investigate AI and deep learning algorithms and extract the computation and logic operations for hardware implementation.
	- Define fixed point specification for hardware implementation while balancing the hardware cost and algorithm performance.
	- Work together with hardware team and software team to define the hardware architecture for the chip and for the accelerator core.
	- Work together with hardware team and algorithm team to define the system specification for the accelerator core including fixed point specifications.  
	- Improve AI and deep learning algorithms considering fixed point process and hardware implementation.
	- Develop a C/C++ based system simulator to model the behavior of the accelerator core. The system simulator and the hardware implementation should achieve bit true match.
	- Drive the system level bit true match for hardware verification and provide test vectors.
	- Drive system level chip debug and isolate the bug location.
	- Drive technical debug and resolution of issues encountered at the complete system level. Propose creative workarounds and implement solutions to complex problems.
	- Effectively present technical information to teams of engineers. Educate Field Application Engineers (FAEs) on new product features and operation
	- Work with the Technical Publications group on engineering notes, data sheets, and architectural manuals
	- Minimum 5 years industry experience with master’s degree in Electrical/Computer Engineering field or minimum 7 years industry experience with Bachelor’s Degree in Electrical Engineering/Computer Engineering
	- Industry experience on fixed point algorithm design and system specification design such as digital communication systems are desired.
	- Strong math skills and problem solving skills.
	- Industry experience on SoC level system specification design such as software/hardware partition is preferred.
	- Experience developing/debugging C/C++ based code is a must.
	- Practical experience in system level debug
	- Excellent problem solving skills
	- Ability to work independently with little or no supervision under tight schedules
	- Ability to quickly learn new technologies
	- Strong communication skills, including verbal, presentation, and documentation
	- Excellent teamwork skills
	- Location: Taipei/Hsinchu/USA_San Diego/Shenzhen/Zhuhai
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



+ Experience with CoreAudio, Audio Unit, ASIO and VST APIs.
+ skill set for research in Binaural 3D audio:
	- advanced technical research, architecture evolution design and strategic technical planning
	- Audiovisual Technology Lab in Huawei Munich Research Center is developing innovative technologies on spatial audio processing and rendering. You will contribute to these activities being inserted into an international and experienced team of researchers.
	- To support our research activities, we are looking for enthusiastic and highly motivated PhD candidate (m/f/d) who will contribute to the research and development of binaural 3D audio technologies.
	- There are still many problems to be solved to provide great 3D audio experience with headphone. Individual measured HRTF filters could be used for accurate audio rendering, but this is not practical and time consuming. Moreover, a mismatching of virtual sound objects to real-world room acoustics might destroy the plausible impression of externalization and distance/depth perception. The rendering system should provide good spatial effect but also preserve timbral quality. This is still a very challenge task.
	- Research on innovative algorithms in the field of binaural 3D audio technologies;
	- Research on innovative algorithms in the field of HRTF customization;
	- Research on innovative algorithms in the field of virtual acoustic environment;
	- Implement the innovative algorithms on a reference software;
	- Generate papers and technical reports if possible;
	- To commit adequate time and effort to the project;
	- To display initiative in identifying and resolving problems relating to the research;
	- To manage their work efficiently so as not to place unreasonable demands on supervisors.
	- Topic of interest include (but are not limited to): Binaural 3D audio
	- You have recently completed or will soon complete your master studies in electronic and electrical engineering, information technology, computer science, mathematics or physics
	- You enjoy working in a team and you like to collaborate with researchers to develop creative solutions
	- You are fluent in English (written and spoken)
	- Excellent software skills
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
+ skill set for SENIOR AUDIO SIGNAL PROCESSING ENGINEER
	- Develop advanced audio signal processing algorithm for real product.
	- Develop audio signal processing pipeline from microphone digital row data to optimized audio signal including but not limited to noise reduction, beamforming, direction of arrival detection.
	- Develop fixed point image processing algorithm for hardware implementation. Able to implement audio signal pipeline in embedded system.
	- Apply deep learning technology to improve audio signal processing algorithm such as noise reduction.
	- Resolve real product problems in variety of environments.
	- M.S. in Electrical Engineering, Computer Science, Robotics or similar field (Ph.D. is preferred).
	- Solid understanding on audio signal processing, signal processing.
	- Solid understanding on fixed point algorithm design.
	- Real product experience on audio signal processing algorithm development.
	- Strong experience in C/C++ programming.
	- Ability to quickly adapt to new situations, learn new technologies, and collaborate and communicate effectively.
	- 3+ years of industry experience with audio signal processing algorithm development and optimization.
	- Location: Taipei/Hsinchu/USA_San Diego/Shenzhen/Zhuhai
+ skill set:
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
	- You have a deep knowledge of ASR (Automatic Speech Recognition) technologies such as acoustic modeling, language modeling, neural networks, HMM, WFST, and feature extraction
	- You possess hands-on experience in ASR tool kits such as Sphinx, Kaldi, HTK, and Julius
	- You have experience with deep learning frameworks such as Caffe, TensorFlow, Torch, PyTorch, and MxNet
+ skill set:
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





+ technologies from The Khronos Group Inc.:
	- [ ] 3DCommerce
		* 3D Commerce, universal guidelines, standards and certifications for 3D content creation and distribution in e-commerce
	- [x] ANARI
		* ANARI, Analytic Rendering Interface for Data Visualization
	- [x] Kamaros - Embedded Camera API
		* Camera, working on interoperable camera API standards for embedded systems, a cooperation with the European Machine Vision Association (EMVA)
	- [x] glTF & KTX
		* glTF, a file format specification for 3D scenes and models
		* KTX, a container file format for storing GPU-ready texture data
	- [x] OpenCL
		* OpenCL, a cross-platform computation API
	- [x] OpenGL & OpenGL ES
		* OpenGL, a cross-platform computer graphics API
		* OpenGL ES, a derivative of OpenGL for use on mobile and embedded systems, such as cell phones, portable gaming devices, and more
	- [x] OpenVG
		* OpenVG, an API for accelerating processing of 2D vector graphics
	- [x] OpenVX & NNEF
		* OpenVX, Hardware acceleration API for Computer Vision applications and libraries
		* NNEF reduces machine learning deployment fragmentation by enabling a rich mix of neural network training tools and inference engines to be used by applications across a diverse range of devices and platforms
	- [x] OpenXR
		* OpenXR, an open and royalty-free standard for virtual reality and augmented reality applications and devices
	- [x] Safety Critical (OpenGL & Vulkan)
		* OpenGL SC, a safety critical profile of OpenGL ES designed to meet the needs of the safety-critical market
		* Vulkan SC, based on the existing Vulkan API specification to enable safety critical industries
	- [x] SPIR
		* SPIR, an intermediate compiler target for OpenCL and Vulkan
	- [x] SYCL
		* SYCL, a single-source C++ DSEL for heterogeneous computing
	- [x] Vulkan
		* Vulkan, a low-overhead computer graphics API
	- [ ] WebGL
		* WebGL, a JavaScript binding to OpenGL ES within a browser on any platform supporting the OpenGL or OpenGL ES graphics standards
+ file formats, libraries, and frameworks:
	- NetCDF 3\*
	- NetCDF 4\*
	- Zarr\*
	- GRIB\*
	- GeoTIFF\*
	- PythonPickle\*
	- HDF 4/5\*
	- Other image format: PNG, JPG, TIFF, etc.
	- video: MP4
	- database: MongoDB
	- Tensors: PyTorch, TensorFlow, NumPy













###	Image Processing






+ skill set:
	- PIL/Pillow: https://pillow.readthedocs.io/
	- Scikit-Image: https://scikit-image.org
	- OpenCV
+ Strong knowledge of image theory, design experience of algorithm modules such as super_resoulution/HDR/noise_reduction/frame_compression/ISP is preferred.
+ skill set:
	- 2-4 years of experience in C/C++ development
	- Object oriented programming experience
	- Experience with applications design and implementation
	- Experience in multi-threaded programming
	- Proven track record of finding bottlenecks and delivering optimized, high-quality code
	- Knowledge in algorithms development and implementation
	- Fast learner, team player, reliable, motivated, hard worker
	- Experience in Android NDK development
	- Experience in image processing algorithms
	- Experience in runtime optimizations on embedded accelerators (e.g. Neon, DSP, GPU).
	- Experience in writing OpenCL kernels
	- Experience in Matlab
+ skill set:
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





+ Understanding of uncompressed video formats and codecs (e.g. HLS, MPEG-DASH)
+ skill set:
	- Familiar with the use of multimedia architecture such as FFmpeg / directshow / AVFoundation;
	- Experience with graphics libraries such as OpenGL/Metal/Vulkan and mobile operation systems such as Android iOS
+ skill set:
	- Proven research and practical experience in one or more areas of image and video processing, including but not limited to (preferring candidates with publications in top-tier venues such as CVPR, ICCV and ECCV):
		* Optical flow
		* Image and video enhancement
		* Noise reduction
		* Image and video super-resolution
		* Image and video de-blur
		* HDR
		* Artifact removal (rain, haze, reflection)
		* Intrinsic images
		* Image and video editing
+ Experience in V4L2, ALSA, OpenMax, G-Streamer, or FFMPEG, etc.
	- "Video4Linux (V4L) is a collection of device drivers and an API for supporting realtime video capture on Linux systems"
	- ALSA:
		* Advanced Linux Sound Architecture, a Linux kernel component
		* Advanced Linux Sound Architecture (ALSA) is a software framework and part of the Linux kernel that provides an application programming interface (API) for sound card device drivers.
	- OpenMAX (Open Media Acceleration), often shortened as "OMX", is a non-proprietary and royalty-free cross-platform set of C-language programming interfaces.
		* OpenMAX provides three layers of interfaces: application layer (AL), integration layer (IL) and development layer (DL). OpenMAX is managed by the non-profit technology consortium Khronos Group.
		* OpenMAX AL is the interface between multimedia applications, such as a media player, and the platform media framework. It allows companies that develop applications to easily migrate their applications to different platforms (customers) that support the OpenMAX AL application programming interface (API).
		* OpenMAX IL is the interface between media framework, (such as StageFright or MediaCodec API on Android, DirectShow on Windows, FFmpeg or GStreamer on Linux), and a set of multimedia components (such as an audio or video codecs). It allows companies that build platforms (e.g. allowing an implementation of an MP3 player) to easily change components like MP3 decoders and Equalizer effects and buy components for their platform from different vendors.
		* OpenMAX DL is the interface between physical hardware, such as digital signal processor (DSP) chips, CPUs, GPUs, and software, like video codecs and 3D engines. It allows companies to easily integrate new hardware that supports OpenMAX DL without reoptimizing their low level software.
		* OpenMAX™ is a royalty-free, cross-platform API that provides comprehensive streaming media codec and application portability by enabling accelerated multimedia components to be developed, integrated and programmed across multiple operating systems and silicon platforms. The OpenMAX API will be shipped with processors to enable library and codec implementers to rapidly and effectively make use of the full acceleration potential of new silicon - regardless of the underlying hardware architecture.
	- GStreamer is a pipeline-based multimedia framework that links together a wide variety of media processing systems to complete complex workflows
	- FFmpeg: A complete, cross-platform solution to record, convert and stream audio and video.
	- FFmpeg is a free and open-source software project consisting of a suite of libraries and programs for handling video, audio, and other multimedia files and streams.
+ Experience in one of the following video in/out related drivers: MIPI, LCD, image sensor, framebuffer，etc.
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
+ system hardware tools:
	- MFT
		* Managed file transfer (MFT) is a technology platform that allows organizations to reliably exchange electronic data between systems and people in a secure way to meet compliance needs.
		* Or, Master File Table (Microsoft NTFS).
			+ New Technology File System (NTFS)
	- Video Toolbox
	- MediaCodec
		* access low-level media codecs, i.e. encoder/decoder components
	- VA-API
		* Video Acceleration API (VA-API) is an open source application programming interface that allows applications such as VLC media player or GStreamer to use hardware video acceleration capabilities, usually provided by the graphics processing unit (GPU).
		* The main motivation for VA-API (Video Acceleration API) is to enable hardware accelerated video decode and encode at various entry-points (VLD, IDCT, Motion Compensation etc.) for the prevailing coding standards today (MPEG-2, MPEG-4 ASP/H.263, MPEG-4 AVC/H.264, VC-1/VMW3, and JPEG, HEVC/H265, VP8, VP9) and video pre/post processing
			+ https://intel.github.io/libva/
+ experience working with OpenCV and FFMPEG libraries
	- FFmpeg is a free and open-source software project consisting of a suite of libraries and programs for handling video, audio, and other multimedia files and streams
+ skill set for SENIOR IMAGE AND VIDEO SIGNAL PROCESSING ENGINEER
	- Develop advanced image processing and video processing algorithm for real product.
	- Develop camera image processing pipeline from camera row data to optimized RGB including but not limited to noise reduction, interpolation, 3A, gamma correction.
	- Develop fixed point image processing algorithm for hardware implementation.
	- Research and develop advanced image processing algorithm such as noise cancellation, motion detection, edge detection.
	- Research and develop advanced computer vision algorithm such as real-time robotic SLAM (Simultaneous Localization and Mapping) solutions including 3D sensing, position tracking, 3D mapping / reconstruction, and sensor fusion.
	- Research and develop practical solutions for 3D scene understanding (e.g., object detection) using state-of-the-art deep learning (DL) and machine learning (ML) methods.
	- M.S. in Electrical Engineering, Computer Science, Robotics or similar field (Ph.D. is preferred).
	- Solid understanding on image processing, signal processing, camera pipeline.
	- Solid understanding on fixed point algorithm design.
	- Understanding on 3D geometry such as SLAM, SfM, and 3D reconstruction is a big plus.
	- Understanding and experience of applying deep learning to real problems in the fields of computer vision and robotics is a big plus.
	- Strong experience in C/C++ programing.
	- Hands-on experience in computer vision and deep learning frameworks is a big plus, e.g., OpenCV, Tensorflow, Keras, Pytorch, and Caffe.
	- Ability to quickly adapt to new situations, learn new technologies, and collaborate and communicate effectively.
	- 3+ years of industry experience with image processing and camera pipeline algorithm development and optimization.
	- Location: Taipei/Hsinchu/USA_San Diego/Shenzhen/Zhuhai
+ skill set:
	- Design and verification of the Image/Video processing algorithm
	- AI based pattern recognition, video scaling, video frame interpolation, video enhancement algorithm design.
	- Knowledge in deep learning theory
	- Experience building system based on deep-learning framework
	- Familiar with at least one of AI platforms, such as TensorFlow, PyTorch, Caffee, Keras, etc.
	- Solid mathematics fundamentals
	- Knowledge in image/video processing algorithm (preferred)
	- Knowledge in c/c++ and python; Master degree or Ph.D.
+ skill set:
	- Co-work with Architect team and Algorithm team to launch Image/Video processing product
	- Design and verification of the Image/Video processing engine
	- Image/Video Algorithm integrating, optimization, analysis
	- Familiar with ffmpeg, x264,x265,vp8/vp9
	- Experience of developing product with ffmpeg
	- linux c/c++ environment programming
	- parallel programming
	- Basic understanding about video codec and post-processing
+ skill set:
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
+ Experience with low-level Graphics APIs (D3D12/Vulkan)
+ Familiarity with one or more of the following software: Unreal Engine, Unity, Maya, Houdini
+ skill set:
	- Achieve scaling, cropping, effects, filters and other pre & post processing functions based on OpenGLES and other graphics libraries;
	- Experience with the use of FFmpeg/OpenGL
	- Participated in NOI/ACM/TopCoder competition will be a big plus.
+ skill set:
	- Familiar with graphics APIs (OpenGL, DirectX, Metal, or Vulkan) and GPU architectures.
	- Knowledge of one or more UI frameworks (Qt, DirectUI, Electron, etc...)
+ C++ and OpenGL/DirectX experience
+ C++/CX, Qt
+ skill set:
	- Experience developing virtual world environment for games, such as Lumberyard, Unity3d, Unreal, CryEngine and/or other world simulation environments
	- Experience with graphics APIs and frameworks such as OpenGL, DirectX, or Vulkan
	- Experience with physics engines (e.g. Bullet, Havok, PhysX)
	- Experience developing agent behaviors, physics, gameplay, tools, or GUIs
+ Experience of Unity, C# and 3D application development.
	- Unity
		* Unity is a cross-platform game engine developed by Unity Technologies, first announced and released in June 2005 at Apple Worldwide Developers Conference as a Mac OS X game engine. The engine has since been gradually extended to support a variety of desktop, mobile, console and virtual reality platforms.
+ Experience with Maya, Blender, Adobe Creative Suite/Creative Cloud.
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
+ Familiar with Android SurfaceFlinger or Linux Weston/Wayland is preferred
	* SurfaceFlinger can accept buffers in two ways: through BufferQueue and SurfaceControl, or through ASurfaceControl.
	* Wayland is a communication protocol that specifies the communication between a display server and its clients, as well as a C library implementation of that protocol.
	* Wayland is the language (protocol) that applications can use to talk to a display server in order to make themselves visible and get input from the user (a person). A Wayland server is called a "compositor". Applications are Wayland clients.
	* Wayland is a protocol for communication between a display server and its clients. A Wayland server uses the Wayland protocol to communicate with a GUI program, which is a Wayland client. A Wayland server is also called a Wayland compositor, as it also acts as a compositing window manager.
	* The Weston server, usually just called Weston, is the reference implementation of a Wayland compositor. It manages the displays, including composition of their contents, support for their input device events (touch screen, mouse, keyboard, etc.), and their settings (wallpapers, resolution, multi-monitor display, etc.).
	* Weston is lightweight compared to X11, and is fast as a compositor. It is suitable for many embedded and mobile use cases.
	* A Wayland server and a set of Weston libraries are collectively known as Weston/Wayland. This diagram describes the Weston/Wayland architecture.
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
+ Graphics programming (OpenGL, Metal, Vulkan, WebGL, WebGPU).
	- https://developer.apple.com/metal/
		* Metal powers hardware-accelerated graphics on Apple platforms by providing a low-overhead API, rich shading language, tight integration between graphics and compute, and an unparalleled suite of GPU profiling and debugging tools.
	- Vulkan is a low-overhead, cross-platform API, open standard for 3D graphics and computing.
	- WebGL is a JavaScript API for rendering interactive 2D and 3D graphics within any compatible web browser without the use of plug-ins. WebGL is fully integrated with other web standards, allowing GPU-accelerated usage of physics, image processing, and effects in the HTML canvas.
	- WebGPU is the working name for a potential web standard and JavaScript API for accelerated graphics and compute, aiming to provide "modern 3D graphics and computation capabilities". 
	- WebGPU is the successor to WebGL bringing the advancements of this new class of modern APIs to the Web. WebGPU unlocks a lot of new GPU programming possibilities in the browser. It better reflects how modern GPU hardware works, while also laying a foundation for more advanced GPU capabilities in the future.
+ skill set:
	- Futurewei focuses research on advanced information and communications technology (ICT) domains that will benefit an intelligent and digital society. By focusing on open innovation, we aim to advance these technologies into real world solutions through standardization, open source collaboration and partnering with industrial ecosystems. Over the next 5 to 10 years, these new technologies can truly digitize our traditional industries and rapidly advance us towards the future.
	- The candidate will join the Graphics team to explore and define the next-generation 2D/3D graphics framework for future OS and application development platforms. The work may also include collaboration with the open source community on architecture and implementation.
	- The candidate will help improve, design and implement the architecture of a modern graphics framework, touch the full graphic stack from UI to driver, and tackle challenging open problems in the computer graphics domain.
	- Master/Ph.D. on Computer Graphics/Computer Vision/Image Processing/Computational Photography
	- Experiences in GPU/GPGPU programming, proficient in at least one of the major GPU APIs (Vulkan, DirectX 11-12, Metal, OpenGL)
	- Experiences in C/C++ programing language
	- Good communications skills and a team player
	- Strong programming skills, and strong problem-solving skills.
	- Experiences in GPU driver programming
	- Publications in top graphics/vision conferences and journals
	- Knowledge on rendering engine architectures
	- Experiences in application frameworks on different OS (Windows, Mac, iOS, Android)
	- Strong mathematical background
+ GPU APIs: OpenGL, DirectX, ...
+ At least one graphics API (OpenGL, Direct 3D, Vulkan)
	- Vulkan:
		* low-overhead, cross-platform API, open standard for 3-D graphics and computing
		* high-performance real-time 3-D computer graphics applications, such as:
			+ video games
			+ interactive media
			+ highly parallelized computing
+ skill set:
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


+ Working knowledge of HMD (ie Oculus, HTC Vive, Hololens)
	- head-mounted display
+ Experience with Hololens, HTC Vive, Oculus, Google Cardboard and other leading AR/VR platforms
+ skill set:
	- 2+ years of experience with C/C++/C#/Objective C or Java
	- Intermediate-level expertise and experience working in Maya, Blender, or 3ds Max
	- Intermediate-level expertise and experience working in Adobe Creative Cloud applications.
	- Programming and/or scripting experience
	- Experience with the latest mixed reality hardware (HoloLens, Leap Motion, Vive/Rift/PSVR/Daydream) a plus
	- Amazing attention to detail, self-motivated and collaborative
	- Passion for creating new, innovative, and ground-breaking user experiences
	- Excellent communication skills (written and verbal)
	- User interface and rapid prototyping experience
	- Understanding of computer vision algorithms, spatial mapping, shaders
	- Possess new technology curiosity and a history of self-technical education
+ skill set:
	- Research Scientist Intern, AI-Driven Neural Interfaces for AR/VR (PhD)
	- Meta Reality Labs is looking for Research Scientist Intern to help us unleash human potential by eliminating the bottlenecks between intent and action. To achieve this, we're building a practical neural interface drawing on the rich neuromotor signals that can be measured non-invasively using electromyography (EMG).
	- Our research lies at the intersection of computational neuroscience, machine learning, signal processing, statistics, biophysics, motor learning, perceptual psychophysics, 3D interfaces, AR/VR and human-computer interaction.
	- We're looking for people who want to shape the future of this technology and are excited about joining our collaborative research team that has grown out of the acquisition of CTRL-labs.
	- As a Research Scientist Intern working at the Reality Labs, you will be responsible for the implementation and acceleration of our EMG machine learning platform; create new AI models, tools, and infrastructure that unlock the capabilities of our technology; productionize our research results, and work with scientists, software engineers, hardware engineers and designers to advance the company's AI-driven AR/VR agenda.
	- Our internships are twelve (12) to twenty four (24) weeks long, and we have various start dates throughout the year.
	- Research and develop Deep Learning or other computational models at the intersection of Computer Vision, Natural Language Processing and EMG signal processing.
	- Design methods, tools and infrastructure to analyze and leverage rich multimodal data sets.
	- Collaborate with research scientists and research engineers to develop innovative deep learning models that define the next generation EMG-based AR/VR interaction techniques.
	- Work side-by-side with research scientists to integrate core science goals to the deliverables.
	- Define short term research goals, informed by practical engineering concerns.
	- Help transition and deliver our work from research into product.
	- Minimum Qualifications
		* Currently has, or is in the process of obtaining a PhD, in one or more of the following fields: machine learning, speech and language technologies, signal processing, electrical engineering, computer science, statistics, physics, or related fields.
		* Research experience in machine learning, deep learning, computer vision and/or natural language processing.
		* Programming experience in Python and hands-on experience with frameworks such as PyTorch.
	- Preferred Qualifications
		* Intent to return to degree program after the completion of the internship.
		* Demonstrated software engineering experience via an internship, work experience, coding competitions, open source contributions, or research.
		* Working in research environments where rapid iteration and flexibility is prioritized.
		* Experience with productizing new research results.
		* Experience in neuroscience, EMG, brain-machine interfaces, or human-computer interactions.
+ skill set:
	- Research Scientist, Novel View Synthesis and Neural Rendering, Live Telepresence
	- Reality Labs (RL) Research is dedicated to the research and development required to bring virtual and augmented reality to billions of people around the world. In our Codec Avatars lab, we aspire to a vision of social VR and AR, where people are able to interact with each other across distances in a way that is indistinguishable from in-person interactions. 
	- We are looking for an exceptional researcher with a proven track record in using machine learning for solving computer vision and graphics problems (e.g., neural rendering, view synthesis, generative models for images and videos) as well as an outstanding software engineer who can prototype invented algorithms.
	- As a Research Scientist at RLR, you will pursue research, and work with other Computer Vision and Machine Learning Researchers and Engineers to solve challenges at the forefront of computer vision and graphics that transform virtual reality from dream to reality. We are looking for a creative researcher to usher in the next era of efficient view synthesis and neural rendering approaches for avatars.
	- Participating in cutting edge research in neural rendering, computer vision, and graphics
	- Developing efficient deep neural network models for 3D content generation and tracking
	- Publish research results in top-tier journals and at leading international conferences
	- Contributing research that can be applied to Meta VR/AR product development
	- Minimum Qualifications
		* Prior experience with Meta can be considered to supplement an applicant’s prior years of experience or types of prior experience to meet the minimum qualifications of the position.
		* Bachelor's degree in Computer Science, Computer Engineering, relevant technical field, or equivalent practical experience.
		* Currently has, or is in the process of obtaining, a PhD and/or postdoctoral assignment in the field of computer vision, computer graphics, machine learning or a related field.
		* Proven track record in using machine learning and computer vision.
		* Experience with neural rendering, view synthesis, or 3D reconstruction.
		* Interpersonal experience: cross-group and cross-culture collaboration.
		* Must obtain work authorization in the country of employment at the time of hire, and maintain ongoing work authorization during employment.
	- Preferred Qualifications
		* Proven track record of achieving significant results as demonstrated by grants, fellowships, patents, as well as first-authored publications at leading conferences (e.g., SIGGRAPH, CVPR, ECCV, ICCV, NeurIPS, ICLR, ICML) or journals (e.g., PAMI, IJCV, JMLR, ToG).
		* 3+ years experience designing and developing computer vision or machine learning algorithms in C++.
		* 3+ years of experience with prototyping algorithms in Python.
		* Experience with neural rendering approaches such as NeRF.
		* Experience in 3D computer vision, graphics, and deep learning models for this domain.
		* Demonstrated software engineer experience via an internship, work experience, coding competitions, or widely used contributions in open source repositories (e.g. GitHub)
		* Experience with data-parallel (e.g., CUDA) or graphics (e.g., OpenGL, Vulcan) programming.
	- $143,000/year to $204,000/year + bonus + equity + benefits
+ skill set:
	- Research Scientist Intern, Photorealistic Telepresence (PhD)
	- Pittsburgh, PA
	- Meta’s mission is to give people the power to build community and bring the world closer together. Through our family of apps and services, we're building a different kind of company that connects billions of people around the world, gives them ways to share what matters most to them, and helps bring people closer together. Whether we're creating new products or helping a small business expand its reach, people at Meta are builders at heart. Our global teams are constantly iterating, solving problems, and working together to empower people around the world to build community and connect in meaningful ways. Together, we can help people build stronger communities — we're just getting started.
	- Reality Labs (RL) in Pittsburgh is looking for exceptional interns to help us create a revolution in virtual reality: achieving true photorealistic telepresence, where you can be with anyone, anywhere, at any time. We have made some important advances, but it will take a diverse team with a wide spectrum of skills to accomplish this future. If you have expertise in computer vision, machine learning, and computer graphics, we expect you will find the work here highly intriguing. We are looking for motivated software, electrical, and mechanical engineers; and strong math skills are always a huge plus. We publish our work at leading conferences and journals.
	- Come join us as we make photorealistic telepresence in VR happen!
	- Available projects may include, but are not limited to:
		* Neural Rendering
		* 3D Audio Reconstruction from Multiple Microphones
		* Speech Synthesis
		* High Fidelity Face Model Reconstruction and Tracking
		* High Fidelity Hand Model Reconstruction and Tracking
		* High Fidelity Body Model Reconstruction and Tracking
		* High Fidelity Hair Model Reconstruction and Tracking
		* Neural Architecture Search and Optimization
	- Our internships are twelve (12) to sixteen (16) to twenty four (24) weeks long and we have various start dates throughout the year.
	- Solve real problems in enabling Photorealistic Telepresence.
	- Collaboration with and support of other researchers across various disciplines.
	- Communication of research agenda, progress, and results.
	- Minimum Qualifications
		* Prior experience with Meta can be considered to supplement an applicant’s prior years of experience or types of prior experience to meet the minimum qualifications of the position.
		* Currently has, or is in the process of obtaining, a PhD in Audio Processing, Computer Science, Computer Vision, Computer Graphics, Robotics, Machine Learning, or related field.
		* Interpersonal skills: cross-group and cross-culture collaboration.
		* Must obtain work authorization in country of employment at the time of hire, and maintain ongoing work authorization during employment.
		* Experience with solving inverse problems in imaging emphasizing modeling, algorithm development, and hardware prototyping.
		* 2+ years of experience with Machine Learning for solving computer vision, computer graphics, or audio synthesis problems.
		* Experience with deep learning frameworks such as Pytorch and TensorBoard.
		* Experience with scientific programming languages such as Matlab or Python.
	- Preferred Qualifications
		* Proven track record of achieving significant results as demonstrated by patents and first-authored publications at leading workshops or conferences such as ICCV, CVPR, NeurIPS, SIGGRAPH, ICASSP, or similar.
		* Intent to return to a degree-program after the completion of the internship.
		* Experience with systems building in Python or C++.
		* Experience with Machine Learning for 3D Data (such as meshes, point clouds, and voxels).
		* Experience with Machine Learning for Visual Synthesis or Audio Synthesis.
		* Demonstrated engineering experience via an internship, work experience, coding competitions, or widely used contributions in open source repositories (e.g., GitHub).
	- $7,650/month to $11,333/month + benefits
+ skill set:
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
+ Experience with applied ontology development (RDF(S)/OWL, SPARQL, the Semantic Web or Frame based KR systems).
+ skill set:
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
