<p>Did you receive a video with those annoying black bars on the side? Do you wonder how you could change the orientation and remove those black bars? Or maybe you want to create a montage of your favorite pictures and make a music video. You can do all that for free when you install <a href="https://ffmpeg.org/" target="_blank" rel="noreferrer noopener nofollow">FFmpeg</a>.</p>



Not a reader? Watch this related video tutorial! 
<div class="adthrive-video-player in-post" itemscope itemtype="https://schema.org/VideoObject" data-video-id="Wh5FU6wT" data-player-type="default" override-embed="default">
			<meta itemprop="uploadDate" content="2022-09-24T15:00:55.000Z" />
		<meta itemprop="name" content="Back to the Basics: Use and Install FFmpeg" />
		<meta itemprop="description" content="Learn how to install and use FFmpeg from the command-line and use in everyday IT operations crucial to business operations." />
		<meta itemprop="thumbnailUrl" content="https://content.jwplatform.com/thumbs/Wh5FU6wT-720.jpg" />
		<meta itemprop="contentUrl" content="https://content.jwplatform.com/videos/Wh5FU6wT.mp4" />
	</div>
 <b><em>Not seeing the video? Make sure your ad blocker is disabled.</em></b>



<p>In this guide, you will learn to install FFmpeg and how to use it by following many examples. By the end, you’ll have acquired the foundation to start converting and altering media files!</p>



<div id="ez-toc-container" class="ez-toc-v2_0_38 counter-hierarchy ez-toc-counter ez-toc-transparent ez-toc-container-direction">
<div class="ez-toc-title-container">
<p class="ez-toc-title">Table of Contents</p>
<span class="ez-toc-title-toggle"></span></div>
<nav><ul class='ez-toc-list ez-toc-list-level-1' ><li class='ez-toc-page-1 ez-toc-heading-level-2'><a class="ez-toc-link ez-toc-heading-1" href="#Prerequisites" title="Prerequisites">Prerequisites</a></li><li class='ez-toc-page-1 ez-toc-heading-level-2'><a class="ez-toc-link ez-toc-heading-2" href="#Installing_FFmpeg_on_Ubuntu" title="Installing FFmpeg on Ubuntu">Installing FFmpeg on Ubuntu</a></li><li class='ez-toc-page-1 ez-toc-heading-level-2'><a class="ez-toc-link ez-toc-heading-3" href="#Installing_FFmpeg_on_Windows_10" title="Installing FFmpeg on Windows 10">Installing FFmpeg on Windows 10</a><ul class='ez-toc-list-level-3'><li class='ez-toc-heading-level-3'><a class="ez-toc-link ez-toc-heading-4" href="#Method_1_Install_FFmpeg_via_PowerShell" title="Method 1: Install FFmpeg via PowerShell">Method 1: Install FFmpeg via PowerShell</a></li><li class='ez-toc-page-1 ez-toc-heading-level-3'><a class="ez-toc-link ez-toc-heading-5" href="#Method_2_Install_FFmpeg_via_Chocolatey" title="Method 2: Install FFmpeg via Chocolatey">Method 2: Install FFmpeg via Chocolatey</a></li></ul></li><li class='ez-toc-page-1 ez-toc-heading-level-2'><a class="ez-toc-link ez-toc-heading-6" href="#Installing_FFmpeg_on_macOS" title="Installing FFmpeg on macOS">Installing FFmpeg on macOS</a></li><li class='ez-toc-page-1 ez-toc-heading-level-2'><a class="ez-toc-link ez-toc-heading-7" href="#Listing_Available_Encoders_and_Decoders" title="Listing Available Encoders and Decoders">Listing Available Encoders and Decoders</a></li><li class='ez-toc-page-1 ez-toc-heading-level-2'><a class="ez-toc-link ez-toc-heading-8" href="#Extracting_Media_File_Information" title="Extracting Media File Information">Extracting Media File Information</a></li><li class='ez-toc-page-1 ez-toc-heading-level-2'><a class="ez-toc-link ez-toc-heading-9" href="#Converting_Media_Files_with_FFmpeg_Examples" title="Converting Media Files with FFmpeg (Examples)">Converting Media Files with FFmpeg (Examples)</a><ul class='ez-toc-list-level-3'><li class='ez-toc-heading-level-3'><a class="ez-toc-link ez-toc-heading-10" href="#Example_1_Basic_Conversion_with_Automatic_Codec_Selection" title="Example 1: Basic Conversion with Automatic Codec Selection">Example 1: Basic Conversion with Automatic Codec Selection</a></li><li class='ez-toc-page-1 ez-toc-heading-level-3'><a class="ez-toc-link ez-toc-heading-11" href="#Example_2_Changing_the_Container_without_Encoding" title="Example 2: Changing the Container without Encoding">Example 2: Changing the Container without Encoding</a></li><li class='ez-toc-page-1 ez-toc-heading-level-3'><a class="ez-toc-link ez-toc-heading-12" href="#Example_3_Changing_the_Video_Resolution" title="Example 3: Changing the Video Resolution">Example 3: Changing the Video Resolution</a></li><li class='ez-toc-page-1 ez-toc-heading-level-3'><a class="ez-toc-link ez-toc-heading-13" href="#Example_4_Extracting_Audio_from_a_Video_File" title="Example 4: Extracting Audio from a Video File">Example 4: Extracting Audio from a Video File</a></li></ul></li><li class='ez-toc-page-1 ez-toc-heading-level-2'><a class="ez-toc-link ez-toc-heading-14" href="#Conclusion" title="Conclusion">Conclusion</a></li></ul></nav></div>
<h2><span class="ez-toc-section" id="Prerequisites"></span>Prerequisites<span class="ez-toc-section-end"></span></h2>



<p>This tutorial will be a hands-on demonstration. If you’d like to follow along, be sure you have the following.</p>



<ul><li>You’ll need a computer running on a compatible operating system, such as Windows, Linux (RHEL-based, Debian-based, or Ubuntu-based), and macOS. This tutorial will be using Ubuntu 20.04, Windows 10, and macOS Big Sur for the installation.</li></ul>


<p class="related-links"><span class="related-links__text">Related:</span><a class="related-links__link" href="https://adamtheautomator.com/install-ubuntu/">How to Install Ubuntu 20.04 [Step-by-Step]</a></p>



<blockquote class="wp-block-quote"><p><em>While the installation method varies, FFmpeg usage should be the same across different operating systems.</em></p></blockquote>



<ul><li>Your computer must have at least 4GB of RAM and a two-core CPU. Multimedia processing is generally a resource-intensive task. As such, your computer must have decent hardware capacity.</li></ul>



<h2><span class="ez-toc-section" id="Installing_FFmpeg_on_Ubuntu"></span>Installing FFmpeg on Ubuntu<span class="ez-toc-section-end"></span></h2>



<p>FFmpeg is available in the default repositories of most Linux distributions. Conveniently, you can install FFmpeg through your distro’s package manager, such as <code>apt</code> in Ubuntu.</p>



<p>To install FFmpeg on Ubuntu, follow these steps:</p>



<p>1. SSH into your Ubuntu server and update the apt package index.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="bash" class="language-bash">sudo apt update -y</code></pre>
</div>

<p class="related-links"><span class="related-links__text">Related:</span><a class="related-links__link" href="https://adamtheautomator.com/pageant-putty/">Using Pageant Putty Agent to Unleash Your SSH Key Use</a></p>



<p>2. Next, install FFmpeg and all the necessary libraries.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="bash" class="language-bash">apt install ffmpeg -y</code></pre>
</div>


<p>3. Finally, check the FFmpeg version you installed.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="bash" class="language-bash">ffmpeg -version</code></pre>
</div>


<p>You will see an output similar to the following screenshot. Your version may be different.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="715" height="448" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-696.png" alt="Viewing the FFmpeg version" class="wp-image-16702" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-696.png 715w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-696-300x188.png 300w" sizes="(max-width: 715px) 100vw, 715px" /><figcaption>Viewing the FFmpeg version</figcaption></figure></div>


<h2><span class="ez-toc-section" id="Installing_FFmpeg_on_Windows_10"></span>Installing FFmpeg on Windows 10<span class="ez-toc-section-end"></span></h2>



<p>So far, you have learned how to install FFmpeg on Ubuntu. Now, know two ways to install FFmpeg on Windows 10 in this section.</p>



<h3><span class="ez-toc-section" id="Method_1_Install_FFmpeg_via_PowerShell"></span>Method 1: Install FFmpeg via PowerShell<span class="ez-toc-section-end"></span></h3>



<p>This method gives you more control over where to download and install FFmpeg on your computer. Best of all, you’ll perform everything within PowerShell.</p>



<p>To install FFmpeg on Windows 10, follow these steps.</p>



<p>1. Open a PowerShell as administrator on your computer.</p>


<p class="related-links"><span class="related-links__text">Related:</span><a class="related-links__link" href="https://adamtheautomator.com/powershell-run-as-administrator/">How to Run PowerShell as Administrator</a></p>



<p>2. Create the folder where you’ll download and install FFmpeg. This command creates the folder C:\ffmpeg.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">New-Item -Type Directory -Path C:\ffmpeg ; Set-Location C:\ffmpeg</code></pre>
</div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="673" height="212" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-697.png" alt="Creating the install location" class="wp-image-16703" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-697.png 673w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-697-300x95.png 300w" sizes="(max-width: 673px) 100vw, 673px" /><figcaption>Creating the install location</figcaption></figure></div>


<p>3. Run the below command to download the latest FFmpeg release for Windows. This command saves the file as ffmpeg.zip.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">curl.exe -L 'https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-essentials.zip' -o 'ffmpeg.zip'</code></pre>
</div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="949" height="150" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-698.png" alt="Downloading FFmpeg for Windows" class="wp-image-16704" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-698.png 949w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-698-300x47.png 300w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-698-768x121.png 768w" sizes="(max-width: 949px) 100vw, 949px" /><figcaption>Downloading FFmpeg for Windows</figcaption></figure></div>


<p>4. After downloading, extract the ffmpeg.zip file to the current directory. To do so, run the Expand-Archive command below.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell"># Expand the Zip
Expand-Archive .\ffmpeg.zip -Force -Verbose</code></pre>
</div>


<p>As you can see, the command extracted all files from the zip file. The only files you’ll need are the executable files.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="870" height="217" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-699.png" alt="Extracting the FFmpeg archive" class="wp-image-16705" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-699.png 870w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-699-300x75.png 300w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-699-768x192.png 768w" sizes="(max-width: 870px) 100vw, 870px" /><figcaption>Extracting the FFmpeg archive</figcaption></figure></div>


<p>5. Move the executable files to the top folder for simplicity and quick access.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell"># Move the executable (*.exe) files to the top folder
Get-ChildItem -Recurse `
    -Path .\ffmpeg\ -Filter *.exe |
    ForEach-Object {
        Move-Item $_ -Destination .\ -Verbose
    }</code></pre>
</div>


<figure class="wp-block-image size-full"><img decoding="async" loading="lazy" width="770" height="279" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-700.png" alt="Moving the essential executable files to the top folder" class="wp-image-16706" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-700.png 770w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-700-300x109.png 300w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-700-768x278.png 768w" sizes="(max-width: 770px) 100vw, 770px" /><figcaption>Moving the essential executable files to the top folder</figcaption></figure>



<p>6. Now, clean up the FFmpeg directory by deleting the unnecessary files and folder.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell"># Clean up
Remove-Item .\ffmpeg\ -Recurse
Remove-Item .\ffmpeg.zip
# List the directory contents
Get-ChildItem</code></pre>
</div>


<p>At this point, only the executable files remain</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="583" height="245" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-701.png" alt="Cleanup unnecessary files and folders" class="wp-image-16707" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-701.png 583w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-701-300x126.png 300w" sizes="(max-width: 583px) 100vw, 583px" /><figcaption>Cleanup unnecessary files and folders</figcaption></figure></div>


<p>7. Now, prepend the C:\ffmpeg folder to the system path environment variable. This step ensures that you can run the ffmpeg.exe command from any directory without specifying the full path.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell"># Prepend the FFmpeg folder path to the system path variable
[System.Environment]::SetEnvironmentVariable(
    "PATH",
    "C:\ffmpeg\;$([System.Environment]::GetEnvironmentVariable('PATH','MACHINE'))",
    "Machine"
)</code></pre>
</div>


<p>8. For the new system variables to take effect, perform either one of the two options below.</p>



<blockquote class="wp-block-quote"><p><em>Note: You only need to do either option once. Every subsequent PowerShell or CMD session will pick up the environment variables automatically.</em></p></blockquote>



<p>Option 1: Close your current PowerShell session and open a new one.</p>



<p>Option 2: Run the below command in the current PowerShell session to import the machine’s PATH variable into the current session.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">$env:Path = [System.Environment]::GetEnvironmentVariable("Path","Machine")</code></pre>
</div>


<p>9. Finally, check the FFmpeg version by running the below command.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">ffmpeg -version</code></pre>
</div>


<p>As you can see, you don’t need to specify the full path of the ffmpeg.exe executable file due to what you did in steps 5 and 6.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="677" height="62" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-702.png" alt="Displaying the FFmpeg version" class="wp-image-16708" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-702.png 677w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-702-300x27.png 300w" sizes="(max-width: 677px) 100vw, 677px" /><figcaption>Displaying the FFmpeg version</figcaption></figure></div>


<h3><span class="ez-toc-section" id="Method_2_Install_FFmpeg_via_Chocolatey"></span>Method 2: Install FFmpeg via Chocolatey<span class="ez-toc-section-end"></span></h3>



<p>Since Windows 10 does not have a default package manager like Ubuntu’s apt, an excellent alternative is to use <a href="https://chocolatey.org/" target="_blank" rel="noreferrer noopener">Chocolatey</a>.</p>


<p class="related-links"><span class="related-links__text">Related:</span><a class="related-links__link" href="https://adamtheautomator.com/install-chocolatey/">How to Install Chocolatey and Get Started in No Time</a></p>



<p>Follow the steps below to install FFmpeg via Chocolatey.</p>



<p>1. If you don’t have Chocolatey yet, open an elevated PowerShell terminal and run the following code to install.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))</code></pre>
</div>


<p>2. After installing Chocolatey, close your current PowerShell window and reopen a new one. On your new PowerShell window, run the following command to install FFmpeg.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">choco install ffmpeg</code></pre>
</div>


<p>Type Y and press Enter at the confirmation prompt.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="769" height="595" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-703.png" alt="Install FFmpeg from Chocolatey" class="wp-image-16709" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-703.png 769w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-703-300x232.png 300w" sizes="(max-width: 769px) 100vw, 769px" /><figcaption>Install FFmpeg from Chocolatey</figcaption></figure></div>


<p>3. Finally, check the FFmpeg version you installed.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">ffmpeg -version</code></pre>
</div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="677" height="62" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-704.png" alt="Displaying the FFmpeg version on Windows" class="wp-image-16710" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-704.png 677w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-704-300x27.png 300w" sizes="(max-width: 677px) 100vw, 677px" /><figcaption>Displaying the FFmpeg version on Windows</figcaption></figure></div>


<h2><span class="ez-toc-section" id="Installing_FFmpeg_on_macOS"></span>Installing FFmpeg on macOS<span class="ez-toc-section-end"></span></h2>



<p>If you’re using a macOS computer, the most convenient way to install FFmpeg is through Homebrew. Homebrew is a package manager for macOS but does not come out of the box.</p>



<p>1. Open a terminal window on your macOS computer.</p>



<p>2. If you don’t have Homebrew yet, run the below command to install it on your computer.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"</code></pre>
</div>


<p>3. Once you’ve installed Homebrew, run the below command in the terminal to install FFmpeg.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">brew install ffmpeg</code></pre>
</div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="696" height="257" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-705.png" alt="Install FFmpeg via Homebrew" class="wp-image-16711" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-705.png 696w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-705-300x111.png 300w" sizes="(max-width: 696px) 100vw, 696px" /><figcaption>Install FFmpeg via Homebrew</figcaption></figure></div>


<p>As you can see below, Homebrew automatically detects and installs every FFmpeg dependency.</p>



<blockquote class="wp-block-quote"><p><em>Installing FFmpeg on macOS could take several minutes, especially when many dependencies are missing. Be patient.</em></p></blockquote>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="504" height="415" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-706.png" alt="Homebrew installing FFmpeg dependencies" class="wp-image-16712" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-706.png 504w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-706-300x247.png 300w" sizes="(max-width: 504px) 100vw, 504px" /><figcaption>Homebrew installing FFmpeg dependencies</figcaption></figure></div>


<p>4. Finally, check your version of FFmpeg by running the below command.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">ffmpeg -version</code></pre>
</div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="545" height="69" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-707.png" alt="Displaying the FFmpeg version on macOS" class="wp-image-16713" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-707.png 545w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-707-300x38.png 300w" sizes="(max-width: 545px) 100vw, 545px" /><figcaption>Displaying the FFmpeg version on macOS</figcaption></figure></div>


<h2><span class="ez-toc-section" id="Listing_Available_Encoders_and_Decoders"></span>Listing Available Encoders and Decoders<span class="ez-toc-section-end"></span></h2>



<p>FFmpeg is known for its media processing capabilities, especially in converting media formats. Converting media files between different formats involves encoding and decoding. What enables FFmpeg to convert media files are the encoders and decoders.</p>



<p>These encoders and decoders determine which media file formats FFmpeg can process. How do you know which encoders and decoders come with FFmpeg?</p>



<p>To display the list of encoders or decoders, run the commands below.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell"># Show encoders
ffmpeg -encoders
# Show decoders
ffmpeg -decoders
</code></pre>
</div>


<p>The below screenshots show only a portion of the available encoders and decoders. The legend at the beginning indicates whether the encoder supports video, audio, subtitles, etc.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="563" height="349" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-708.png" alt="FFmpeg encoders" class="wp-image-16714" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-708.png 563w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-708-300x186.png 300w" sizes="(max-width: 563px) 100vw, 563px" /><figcaption>FFmpeg encoders</figcaption></figure></div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="563" height="395" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-709.png" alt="FFmpeg decoders" class="wp-image-16715" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-709.png 563w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-709-300x210.png 300w" sizes="(max-width: 563px) 100vw, 563px" /><figcaption>FFmpeg decoders</figcaption></figure></div>


<h2><span class="ez-toc-section" id="Extracting_Media_File_Information"></span>Extracting Media File Information<span class="ez-toc-section-end"></span></h2>



<p>After installing FFmpeg, the first thing you will want to do is to get the essential information about a media file. This information includes the duration of a video or which codecs were used during an audio file encoding.</p>



<p>To get a file’s media information, run the below command. Ensure to provide the correct filename after the -i option. The -f null &#8211; flag prevents FFmpeg from encoding the output to a file, where null means no file format and &#8211; means no filename.</p>



<blockquote class="wp-block-quote"><p><em>This example uses a sample MP3 file named file_example_MP3_5MG.mp3 downloaded from this <a href="https://file-examples.com/wp-content/uploads/2017/11/file_example_MP3_5MG.mp3" target="_blank" rel="noreferrer noopener nofollow">link</a>.</em></p></blockquote>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">ffmpeg -i .\\file_example_MP3_5MG.mp3 -f null -
</code></pre>
</div>


<p>As you can see, the input file information shows the metadata, bitrate, duration, and container format, among others.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="580" height="257" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-710.png" alt="Extracting an mp3 file’s media information" class="wp-image-16716" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-710.png 580w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-710-300x133.png 300w" sizes="(max-width: 580px) 100vw, 580px" /><figcaption>Extracting an mp3 file’s media information</figcaption></figure></div>


<h2><span class="ez-toc-section" id="Converting_Media_Files_with_FFmpeg_Examples"></span>Converting Media Files with FFmpeg (Examples)<span class="ez-toc-section-end"></span></h2>



<p>Suppose you have a WEBM video file that you want to watch on your smart TV. But your TV does not support the WEBM format. You can use FFmpeg to convert the WEBM file to a format that your TV supports, such as MP4.</p>



<blockquote class="wp-block-quote"><p><em>This example uses a sample video file called file_example_WEBM_1920_3_7MB.webm downloaded from this <a href="https://file-examples.com/wp-content/uploads/2020/03/file_example_WEBM_1920_3_7MB.webm" target="_blank" rel="noreferrer noopener">link</a>.</em></p></blockquote>



<h3><span class="ez-toc-section" id="Example_1_Basic_Conversion_with_Automatic_Codec_Selection"></span>Example 1: Basic Conversion with Automatic Codec Selection<span class="ez-toc-section-end"></span></h3>



<p>The command is as follows to perform a basic conversion of a video format. This command takes file_example_WEBM_1920_3_7MB.webm as the input, converts it, and saves the output file file_example_MP4_1920_3_7MB.mp4.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">ffmpeg -i file_example_WEBM_1920_3_7MB.webm file_example_MP4_1920_3_7MB.mp4
</code></pre>
</div>


<p>Notice that you didn’t have to specify the output format? Because FFmpeg recognized the format since MP4 is well-known and uses the correct codecs and encoders.</p>



<h3><span class="ez-toc-section" id="Example_2_Changing_the_Container_without_Encoding"></span>Example 2: Changing the Container without Encoding<span class="ez-toc-section-end"></span></h3>



<p>In some cases, you may want to change a file container into another without re-encoding the video or audio streams. One reason could be that you’ve already encoded the streams correctly but chose the wrong container in the first place.</p>



<p>To change contains without transcoding, run the below command. This command uses the -c:a copy and -c:v copy options to copy the audio and video streams from a WEBM into an MKV container.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">ffmpeg -i file_example_WEBM_1920_3_7MB.webm -c:v copy -c:a copy file_example_MKV.mkv
</code></pre>
</div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="899" height="554" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-711.png" alt="Changing the Container without Encoding" class="wp-image-16717" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-711.png 899w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-711-300x185.png 300w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-711-768x473.png 768w" sizes="(max-width: 899px) 100vw, 899px" /><figcaption>Changing the Container without Encoding</figcaption></figure></div>


<h3><span class="ez-toc-section" id="Example_3_Changing_the_Video_Resolution"></span>Example 3: Changing the Video Resolution<span class="ez-toc-section-end"></span></h3>



<p>What you are mainly playing videos on a small screen, perhaps on a mobile phone. Smaller screens may have fewer benefits with higher video resolutions, such as 1920&#215;1080, and bigger file sizes.</p>



<p>In such cases, FFmpeg can resize a video to a smaller resolution, like 1280&#215;720. To do so, run the following command. This command uses the -c:a copy option to copy the audio stream (without conversion), and the -s 1280&#215;720 option specifies the output video resolution.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="powershell" class="language-powershell">ffmpeg -i file_example_WEBM_1920_3_7MB.webm -c:a copy -s 1280x720 file_example_1280x720.webm
</code></pre>
</div>

<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="904" height="488" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-712.png" alt="Changing a video resolution" class="wp-image-16718" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-712.png 904w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-712-300x162.png 300w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-712-768x415.png 768w" sizes="(max-width: 904px) 100vw, 904px" /><figcaption>Changing a video resolution</figcaption></figure></div>


<h3><span class="ez-toc-section" id="Example_4_Extracting_Audio_from_a_Video_File"></span>Example 4: <strong>Extracting Audio from a Video File</strong><span class="ez-toc-section-end"></span></h3>



<p>You can also use FFmpeg to extract the audio from a video file. This FFmpeg usage is widespread for converting music videos or instructional videos to audio files like MP3 and OGG.</p>



<p>To extract the audio from a video file, run the below command. This command uses the <code>-vn</code> option to disable the video stream and save the output to an MP3 file.</p>


<div class="not-prose">
<pre class="wp-block-code"><code lang="bash" class="language-bash">ffmpeg -i file_example_WEBM_1920_3_7MB.webm -vn file_example_WEBM.mp3
</code></pre>
</div>


<p>As you can see below, the input file had two streams; <code>Stream#0:0</code> for video and <code>Stream#0:1</code> for audio.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="615" height="429" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-713.png" alt="Video file input streams" class="wp-image-16719" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-713.png 615w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-713-300x209.png 300w" sizes="(max-width: 615px) 100vw, 615px" /><figcaption>Video file input streams</figcaption></figure></div>


<p>But the output only contains one stream, which is the audio-only since you’ve disabled the video stream.</p>


<div class="wp-block-image">
<figure class="aligncenter size-full"><img decoding="async" loading="lazy" width="571" height="301" src="https://adamtheautomator.com/wp-content/uploads/2022/06/image-714.png" alt="FFmpeg audio-only output stream" class="wp-image-16720" srcset="https://adamtheautomator.com/wp-content/uploads/2022/06/image-714.png 571w, https://adamtheautomator.com/wp-content/uploads/2022/06/image-714-300x158.png 300w" sizes="(max-width: 571px) 100vw, 571px" /><figcaption>FFmpeg audio-only output stream</figcaption></figure></div>


<h2><span class="ez-toc-section" id="Conclusion"></span>Conclusion<span class="ez-toc-section-end"></span></h2>



<p>FFmpeg is a powerful multimedia tool for converting media files between different formats and extracting audio from video files. This guide taught you how to install FFmpeg and used its command with several real-life examples.</p>



<p>With FFmpeg, you can make your media files work on any device or platform. So don&#8217;t be afraid to give it a try. Don&#8217;t stop here! There&#8217;s a lot more you can do with FFmpeg, like how to <a href="https://www.linuxjournal.com/content/how-decrease-video-sizes-using-ffmpeg-linux" target="_blank" rel="noreferrer noopener nofollow">compress a large video file</a> to save space or <a href="https://gist.github.com/loretoparisi/a9277b2eb4425809066c380fed395ab3" target="_blank" rel="noreferrer noopener">extract all the images from a movie</a> to create a photo gallery.</p>



<p>For more ideas, check out the FFmpeg <a href="https://ffmpeg.org/ffmpeg.html" target="_blank" rel="noreferrer noopener nofollow">documentation</a>. Thanks for reading, and happy learning!</p>
      </div>
