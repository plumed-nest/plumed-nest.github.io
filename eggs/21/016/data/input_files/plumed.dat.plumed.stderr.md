**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[runnervmmklqx:09591] *** Process received signal ***
[runnervmmklqx:09591] Signal: Aborted (6)
[runnervmmklqx:09591] Signal code:  (-6)
[runnervmmklqx:09591] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2fadc45330]
[runnervmmklqx:09591] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2fadc9eb2c]
[runnervmmklqx:09591] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2fadc4527e]
[runnervmmklqx:09591] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2fadc288ff]
[runnervmmklqx:09591] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2fae0a5ff5]
[runnervmmklqx:09591] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2fae0bb0da]
[runnervmmklqx:09591] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2fae0a5a55]
[runnervmmklqx:09591] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2fae0a5a6f]
[runnervmmklqx:09591] [ 8] plumed(+0x146dd)[0x55c71a4626dd]
[runnervmmklqx:09591] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2fadc2a1ca]
[runnervmmklqx:09591] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2fadc2a28b]
[runnervmmklqx:09591] [11] plumed(+0x15365)[0x55c71a463365]
[runnervmmklqx:09591] *** End of error message ***
</pre>
{% endraw %}
