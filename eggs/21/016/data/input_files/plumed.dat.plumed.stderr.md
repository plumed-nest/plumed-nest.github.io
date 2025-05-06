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
[fv-az2209-645:65049] *** Process received signal ***
[fv-az2209-645:65049] Signal: Aborted (6)
[fv-az2209-645:65049] Signal code:  (-6)
[fv-az2209-645:65049] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a06c45330]
[fv-az2209-645:65049] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a06c9eb2c]
[fv-az2209-645:65049] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a06c4527e]
[fv-az2209-645:65049] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a06c288ff]
[fv-az2209-645:65049] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a070a5ff5]
[fv-az2209-645:65049] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a070bb0da]
[fv-az2209-645:65049] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a070a5a55]
[fv-az2209-645:65049] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a070a5a6f]
[fv-az2209-645:65049] [ 8] plumed(+0x146dd)[0x558b15c1a6dd]
[fv-az2209-645:65049] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a06c2a1ca]
[fv-az2209-645:65049] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a06c2a28b]
[fv-az2209-645:65049] [11] plumed(+0x15365)[0x558b15c1b365]
[fv-az2209-645:65049] *** End of error message ***
</pre>
{% endraw %}
