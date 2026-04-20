**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[runnervmeorf1:06485] *** Process received signal ***
[runnervmeorf1:06485] Signal: Aborted (6)
[runnervmeorf1:06485] Signal code:  (-6)
[runnervmeorf1:06485] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa7c245330]
[runnervmeorf1:06485] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa7c29eb2c]
[runnervmeorf1:06485] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa7c24527e]
[runnervmeorf1:06485] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa7c2288ff]
[runnervmeorf1:06485] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa7c6a5ff5]
[runnervmeorf1:06485] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa7c6bb0da]
[runnervmeorf1:06485] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa7c6a5a55]
[runnervmeorf1:06485] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa7c6a5a6f]
[runnervmeorf1:06485] [ 8] plumed(+0x146dd)[0x5583c08366dd]
[runnervmeorf1:06485] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa7c22a1ca]
[runnervmeorf1:06485] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa7c22a28b]
[runnervmeorf1:06485] [11] plumed(+0x15365)[0x5583c0837365]
[runnervmeorf1:06485] *** End of error message ***
</pre>
{% endraw %}
