**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[runnervmeorf1:10135] *** Process received signal ***
[runnervmeorf1:10135] Signal: Aborted (6)
[runnervmeorf1:10135] Signal code:  (-6)
[runnervmeorf1:10135] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc981645330]
[runnervmeorf1:10135] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc98169eb2c]
[runnervmeorf1:10135] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc98164527e]
[runnervmeorf1:10135] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9816288ff]
[runnervmeorf1:10135] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc981aa5ff5]
[runnervmeorf1:10135] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc981abb0da]
[runnervmeorf1:10135] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc981aa5a55]
[runnervmeorf1:10135] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc981aa5a6f]
[runnervmeorf1:10135] [ 8] plumed(+0x146dd)[0x559d6d2406dd]
[runnervmeorf1:10135] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc98162a1ca]
[runnervmeorf1:10135] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc98162a28b]
[runnervmeorf1:10135] [11] plumed(+0x15365)[0x559d6d241365]
[runnervmeorf1:10135] *** End of error message ***
</pre>
{% endraw %}
