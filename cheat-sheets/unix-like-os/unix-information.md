#	Notes About *UNIX*-like Operating Systems



##	Data compression and File Archiving

###	"\*.tar.xz" Files

To compress/archive "\*.tar.xz" files, try:
- xz -z
- xz --compress
- xz -l
	+ Display information about the compressed files.
- xz --list
	+ Display information about the compressed files.
- xz -z -F auto
- xz -z -F xz
- xz -z -F lzma
- xz -z -F alone
- xz -z -F raw
- tar cvf --options *[xz:compression-level]* *[filename]* *[files or set(s) of file types]*




To uncompress/unarchive "*.tar.xz" files, try:
- xz --decompress
- unxz *[filename.tar.xz]* *[filename.tar]*
- unxz *[filename.tar.xz]*
- xz -dc *[filename.tar.xz]* *[filename.tar]*
- tar xvf *[filename]*





##	Making Files Executable

`chmod 744 *[filename]*` makes the file *[filename]* executable, via
	invoking its filename.
	That is, it enables the file *[filename]* to be executed as a
	computer program.


##	Notes on Using the GNU Build System / Autotools

Dr. Anders Franz{\'{e}}n (or Anders Franzen) suggested that I use "autoreconf --install" to generate the "./configure" executable if it is not available in my working directory (for a software project that uses the GNU Build System / Autotools).

Steps that I would use to build a software project that uses the GNU Build System (or Autotools):
+ autoreconf --install
+ ./configure
	-  I can use flags/options to configure different parameters to indicate where to install/place the software build.
+ make all




##	List of UNIX commands to find their man pages of

Check if I can access the man pages for the following UNIX commands in the "Terminal" application:
+ man clang
+ man java
+ man gfortran
+ man make
+ man rmdir
+ man chmod
+ man gcc
+ man g++
+ man chmod
+ man rmdir
+ man rm
+ man pwd
+ man ls
+ man wc









##	macOS

###	macOS Catalina


From [mkyong2017], it states that the following:
+ "On Mac OS X, the equivalent of *Linux*'s wget is curl -O"
+ "P.S Uppercase alphabet O, not number zero."


E.g., the command suggested is:

	curl -O http://www-us.apache.org/dist/tomcat/tomcat-8/v8.5.9/bin/apache-tomcat-8.5.9.tar.gz









##	Online *Linux* *Terminal*s


The following online *Terminal* applications, or online integrated development environments (IDEs), can also be used to execute the (a sequence/set of) *Linux/UNIX* commands.


You can use the online IDE of *LeetCode* to execute a sequence/set of *Linux/UNIX* commands, by selecting the language *Bash* to run the *Linux/UNIX* commands.

	@misc{LeetCodeStaff2022a,
		Address = {Palo Alto, {CA}},
		Author = {{LeetCode staff}},
		Howpublished = {Available online from {\it {LeetCode} -- The World's Leading Online Programming Learning Platform} at: \url{https://leetcode.com/playground/new/empty}; June 6, 2022 was the last accessed date},
		Publisher = {{LeetCode, LLC}},
		Title = {Untitled -- {LeetCode} Playground},
		Url = {https://leetcode.com/playground/new/empty},
		Year = {2022}}



In addition, you can use the online *Bash* shell *Terminal* and the online Linux *Terminal*, from *Tutorials Point India Private Limited*, to run a sequence/set of *Linux/UNIX* commands.


Online *Bash* shell interpreter, which effectively interprets/"compiles" *Linux/UNIX* shell scripts for the *Bash* shell and serve as the *Terminal* application, from *Tutorials Point India Private Limited*:

	@misc{TutorialsPointIndiaPrivateLimitedStaff2022a,
		Address = {Madhapur, Hyderabad, Telangana, India},
		Author = {{Tutorials Point India Private Limited staff}},
		Howpublished = {Available online from {\it Online Tutorials Library: Simply Easy Learning at your fingertips: Coding Ground For Developers -- Code, Edit, Run and Share: Online Compilers and Interpreters: Bash Shell} at: \url{https://www.tutorialspoint.com/execute_bash_online.php}; June 6, 2022 was the last accessed date},
		Publisher = {Tutorials Point India Private Limited},
		Title = {Online {BASH} Compiler},
		Url = {https://www.tutorialspoint.com/execute_bash_online.php},
		Year = {2022}}



Online *Linux* *Terminal* from *Tutorials Point India Private Limited*:

	@misc{TutorialsPointIndiaPrivateLimitedStaff2022b,
		Address = {Madhapur, Hyderabad, Telangana, India},
		Author = {{Tutorials Point India Private Limited staff}},
		Howpublished = {Available online from {\it Online Tutorials Library: Simply Easy Learning at your fingertips: Coding Ground For Developers -- Code, Edit, Run and Share: Online Terminals: Linux Terminal} at: \url{https://www.tutorialspoint.com/linux_terminal_online.php}; June 6, 2022 was the last accessed date},
		Publisher = {Tutorials Point India Private Limited},
		Title = {Online Linux Terminal},
		Url = {https://www.tutorialspoint.com/linux_terminal_online.php},
		Year = {2022}}





Besides, [Kumar2022a] provides a good environment to run *Linux/UNIX* shell scripts for the *Bash* shell and serve as the *Terminal* application.

	@misc{Kumar2022a,
		Address = {London, {U.K.}},
		Author = {Chandan Kumar},
		Howpublished = {Available online from {\it Geekflare -- Your trusted source for Technology Resources: Products: Compiler: Bash (5.0.0)} at: \url{https://geekflare.com/online-compiler/bash}; June 10, 2022 was the last accessed date},
		Publisher = {Geekflare {LTD}},
		Title = {Online Bash Compiler},
		Url = {https://geekflare.com/online-compiler/bash},
		Year = {2022}}



Likewise for the following resources/references provided in *BibTeX* format:
+ [ReplitStaff2022a]
+ [NutpanPtyLtdStaff2022a]
+ [TheRextesterTeam20XYa]
+ [GoogleCloudStaff20XYa] and [GoogleCloudStaff20XYb]
+ [SphereResearchLabsStaff2022]
+ [SphereResearchLabsStaff2022a]






The *BibTeX* entries.

	@misc{ReplitStaff2022a,
		Address = {San Francisco, {CA}},
		Author = {{Replit staff}},
		Howpublished = {Available online from {\it Replit -- Code, create, and learn together: languages: Bash} at: \url{https://replit.com/languages/bash}; June 10, 2022 was the last accessed date},
		Publisher = {{Replit, Inc.}},
		Title = {Replit: Code, create, and learn together},
		Url = {https://replit.com/languages/bash},
		Year = {2022}}


...

	@misc{NutpanPtyLtdStaff2022a,
		Author = {{Nutpan Pty Ltd staff}},
		Howpublished = {Available online from {\it {JDoodle}: Online Compiler And Editor: Bash} at: \url{https://www.jdoodle.com/test-bash-shell-script-online/}; June 10, 2022 was the last accessed date},
		Publisher = {Nutpan Pty Ltd},
		Title = {Online {Bash} Shell {IDE}},
		Url = {https://www.jdoodle.com/test-bash-shell-script-online/},
		Year = {2022}}


...

	@misc{TheRextesterTeam20XYa,
		Author = {{The Rextester Team}},
		Howpublished = {Available online from {\it The Rextester Team: compile c{\#}\ online: Language: Bash} at: \url{https://rextester.com/l/bash_online_compiler}; self-published; June 10, 2022 was the last accessed date},
		Title = {run bash online},
		Url = {https://rextester.com/l/bash_online_compiler}}


...

	@misc{GoogleCloudStaff20XYb,
		Address = {Mountain View, {CA}},
		Author = {{Google Cloud staff}},
		Howpublished = {Available online from {\it Google {LLC}: About: Featured products: Google Cloud: Products: Management Tools: Cloud Shell: Go to console}, {\it Google {LLC}: About: Products: For business: Google Cloud: Products: Management Tools: Cloud Shell: Go to console}, and {\it Google {LLC}: About: Products: For developers: Google Cloud: Products: Management Tools: Cloud Shell: Go to console} at: \url{https://console.cloud.google.com/projectselector2/home/dashboard?cloudshell=true&supportedpurview=project}; June 11, 2022 was the last accessed date},
		Publisher = {Google {LLC}},
		Title = {Dashboard -- Home -- Google Cloud Platform},
		Url = {https://console.cloud.google.com/projectselector2/home/dashboard?cloudshell=true&supportedpurview=project}}


...

	@misc{GoogleCloudStaff20XYa,
		Address = {Mountain View, {CA}},
		Author = {{Google Cloud staff}},
		Howpublished = {Available online from {\it Google {LLC}: About: Featured products: Google Cloud: Products: Management Tools: Cloud Shell}, {\it Google {LLC}: About: Products: For business: Google Cloud: Products: Management Tools: Cloud Shell}, and {\it Google {LLC}: About: Products: For developers: Google Cloud: Products: Management Tools: Cloud Shell} at: \url{https://cloud.google.com/shell/}; June 11, 2022 was the last accessed date},
		Publisher = {Google {LLC}},
		Title = {Cloud Shell},
		Url = {https://cloud.google.com/shell/}}


...

	@misc{SphereResearchLabsStaff2022,
		Address = {Gdynia, Pomeranian Voivodeship, Poland},
		Author = {{Sphere Research Labs staff}},
		Howpublished = {Available online at: \url{https://ideone.com/}; June 11, 2022 was the last accessed date},
		Publisher = {Sphere Research Labs {Sp. z o.o.} (Limited)},
		Title = {Ideone},
		Url = {https://ideone.com/},
		Year = {2022}}



...

	@misc{SphereResearchLabsStaff2022a,
		Address = {Gdynia, Pomeranian Voivodeship, Poland},
		Author = {{Sphere Research Labs staff}},
		Howpublished = {Available online from {\it Sphere Engine: Products: Compilers} at: \url{https://sphere-engine.com/compilers}; June 11, 2022 was the last accessed date},
		Publisher = {Sphere Research Labs {Sp. z o.o.} (Limited)},
		Title = {Sphere Engine Compilers},
		Url = {https://sphere-engine.com/compilers},
		Year = {2022}}

















*CoCalc*, via *SageMath, Inc.*, also provides access to an online *Linux* *Terminal*, via \\cite[from CoCalc -- Collaborative Computation and Data Science: Projects: Create New Project: New: Create new files in: Linux Terminal]{Stein2022}.

	@misc{Stein2022,
		Address = {Seattle, {WA}},
		Author = {William Arthur Stein and Harald Schilly},
		Howpublished = {Available online from {\it CoCalc -- Collaborative Computation and Data Science: Projects} at: \url{https://cocalc.com/projects?session=default}; June 8, 2022 was the last accessed date},
		Publisher = {{SageMath, Inc.}},
		Title = {Projects -- {CoCalc}},
		Url = {https://cocalc.com/projects?session=default},
		Year = {2022}}










With the *Codeanywhere Dashboard* [CodeanywhereStaff2022] platform, the Dashboard allows users to create containers to test, deploy, or share their (ongoing) work. It uses operating system (OS) -level virtualization to provide platform as a service products that enable users to test, deploy, or share their (ongoing) work, via containers. Each container allows users to create text editors to enter and edit their source code, and tools/features of an integrated development environment (IDE) to compile and run their computer programs or software. It also includes a *Terminal* feature to enable users to enter commands of *UNIX*-like OS, or *UNIX/Linux* commands. This *Terminal* feature allows people to copy and past a sequence of *UNIX*/*Linux* commands into the command prompt of the *Terminal*


	@misc{CodeanywhereStaff2022,
		Address = {San Francisco, {CA}},
		Author = {{Codeanywhere staff}},
		Howpublished = {Available online from {\it Codeanywhere: Dashboard} at: \url{https://dashboard.codeanywhere.com/}; June 11, 2022 was the last accessed date},
		Publisher = {{Codeanywhere, Inc.}},
		Title = {Codeanywhere Dashboard},
		Url = {https://dashboard.codeanywhere.com/},
		Year = {2022}}









###	Poor Online *Linux* *Terminal*s


[CanonicalGroupLimitedStaff2022] provides an online *Linux* *Terminal* with limited access to features, since we have limited storage space in this online Linux container that is accessible for only 30 minutes during each session.

	@misc{CanonicalGroupLimitedStaff2022,
		Address = {London, {U.K.}},
		Author = {{Canonical Group Limited staff}},
		Howpublished = {Available online {\it Linux Containers -- Container and virtualization tools: Active projects: {LXD}: Try it online: Start: Terminal} and {\it Linux Containers -- Container and virtualization tools: {LXD}: Try it online: Start: Terminal} at: \url{https://linuxcontainers.org/lxd/try-it/}; June 9, 2022 was the last accessed date},
		Month = {May 29},
		Publisher = {Canonical Group Limited},
		Title = {Linux Containers -- {LXD} -- Try it online},
		Url = {https://linuxcontainers.org/lxd/try-it/},
		Year = {2022}}



[Ganapathi20XY] also provides an online *Linux* *Terminal* with limited access to features, since we have limited storage space. Unfortunately, it does not allow users to copy and paste information to the command line.

	@misc{Ganapathi20XY,
		Author = {Lakshmipathi Ganapathi and Freston},
		Howpublished = {Available online from {\it Webminal: Terminal} at: \url{https://webminal.org/terminal/}; self-published; June 9, 2022 was the last accessed date},
		Title = {Webminal},
		Url = {https://webminal.org/terminal/}}



Select one of the "Startup Link"s in [Bellard2021] to use the online *Linux* *Terminal*. Unfortunately, it does not allow users/people to copy and paste text into the online *Linux* *Terminal*. In addition, it has limited access to features, since we have limited storage space.


	@misc{Bellard2021,
		Author = {Fabrice Bellard},
		Howpublished = {Available online from {\it Fabrice Bellard's Home Page: A {PC} emulator in {Javascript}: {JSLinux}} at: \url{https://bellard.org/jslinux/index.html}; self-published; June 9, 2022 was the last accessed date},
		Title = {{JSLinux}},
		Url = {https://bellard.org/jslinux/index.html},
		Year = {2021},
		Annote = {Select one of the ``Startup Link''s.
			Does not allow users to copy and paste text into the online Linux Terminal.}}





[OffiDocsGroupStaff2022] allows us to run a selected version of the *Ubuntu* distribution of the *Linux* operating system, and other *Linux* distributions such as *Debian* and *Fedora*. However, the online OS, which is an instance of *Ubuntu*, *Debian*, and *Fedora*, does not allow people to paste text (such as a sequence of *UNIX*/*Linux* commands) into the command line of the *Terminal* application.


	@misc{OffiDocsGroupStaff2022,
		Address = {Tallinn, Estonia},
		Author = {{OffiDocs Group staff}},
		Howpublished = {Available online from {\it {OnWorks}: Products {\rm \&}\ Features: Ubuntu servers} at: \url{https://www.onworks.net/os-distributions/ubuntu-based}; June 12, 2022 was the last accessed date},
		Publisher = {{OffiDocs Group OU}},
		Title = {Run Linux Ubuntu Distributions online -- Online in the Cloud},
		Url = {https://www.onworks.net/os-distributions/ubuntu-based},
		Year = {2022}}












###	Online *Linux* Emulation



The online *Linux* emulation by [Klemann2022] is very, very slow, and is only limited to 30 minutes.

	@misc{Klemann2022,
		Address = {Schiffweiler, Neunkirchen, Saarland, Germany},
		Author = {Andy Klemann},
		Howpublished = {Available online at: \url{https://distrotest.net/index.php}; June 10, 2022 was the last accessed date},
		Publisher = {Andy Klemann Group},
		Title = {{DistroTest.net} -- The first online operating system tester},
		Url = {https://distrotest.net/index.php},
		Year = {2022}}
















#	Additional Information

See the private [network-admin](https://github.com/eda-ricercatore/network-admin) repository for scripts that I use to automate network/system administration.












#	References


Citations/References that use the *LaTeX/BibTeX* notation are taken
	from my *BibTeX* database (set of *BibTeX* entries).


These references about *UNIX* are:
+ \cite{Adelstein2007}
+ \cite{AppleIncStaff2002}
+ \cite{Apple2011}
+ \cite{Bach1986}
+ \cite{Benvenuti2006}
+ \cite{Blum2008}
+ \cite{Bovet2006}
+ \cite{Chan1996}
+ \cite{Creary2003}
+ \cite{Dougherty1997}
+ \cite{Esteve2009}
+ \cite{Goyvaerts2009}
+ \cite{Hall2015}
+ \cite{Heard20XY}
+ \cite{Kernighan1984}
+ \cite{Kerrisk2010}
+ \cite{Love2005}
+ \cite{Matthew2008}
+ \cite{Mitchell2001}
+ \cite{Muster2003}
+ \cite{Negus2012}
+ \cite{Newham2005}
+ \cite{Ong2004a}
+ \cite{Parlante2001}
+ \cite{Petersen2008}
+ \cite{Powers2003}
+ \cite{Raymond2004}
+ \cite{Raymond2004a}
+ \cite{Riesbeck2009a}
+ \cite{Robbins2003}
+ \cite{Rochkind2004}
+ \cite{Rosen2007a}
+ \cite{Stallings2005}
+ \cite{StanfordUniversityStaff2006}
+ \cite{Stevens2013}
+ \cite{Storimer2012}
+ \cite{vanVugt2009}
+ \cite{VibrantPublishers2010a}
+ \cite{VibrantPublishers2011b}
+ \cite{VibrantPublishers2011c}
+ \cite{VibrantPublishers2011h}
+ \cite{Moth2020}





BibTeX entries for URLs pertinent to aforementioned topics.

	@misc{Moth2020,
		Author = {Jason Moth},
		Howpublished = {Available online from {\it Blackdown: Tutorials: Scripting} at: \url{https://www.blackdown.org/online-linux-terminals-and-bash-editors/}; June 10, 2022 was the last accessed date},
		Publisher = {Blackdown},
		Title = {Top 15 Best Online Linux Terminals and Bash Script Editors},
		Url = {https://www.blackdown.org/online-linux-terminals-and-bash-editors/},
		Year = {2020}}



##	References Not in My *BibTeX* Database 


+ [mkyong2017]
	- mkyong, "wget on Mac OS X", from mkyong's Web page: mac,
		no address, January 4, 2017.
		Available online from mkyong's Web page: mac at:
			https://mkyong.com/mac/wget-on-mac-os-x/;
			February 13, 2020 was the last accessed date.
		







#	Author Information

The MIT License (MIT)

Copyright (c) <2016> Zhiyang Ong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Email address: echo "cukj -wb- 23wU4X5M589 TROJANS cqkH wiuz2y 0f Mw Stanford" | awk '{ sub("23wU4X5M589","F.d_c_b. ") sub("Stanford","d0mA1n"); print $5, $2, $8; for (i=1; i<=1; i++) print "6\b"; print $9, $7, $6 }' | sed y/kqcbuHwM62z/gnotrzadqmC/ | tr 'q' ' ' | tr -d [:cntrl:] | tr -d 'ir' | tr y "\n"		Don't compromise my computing accounts. You have been warned.
