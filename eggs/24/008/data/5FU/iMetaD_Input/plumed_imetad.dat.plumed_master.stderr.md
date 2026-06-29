**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmmklqx:05173] *** Process received signal ***
[runnervmmklqx:05173] Signal: Aborted (6)
[runnervmmklqx:05173] Signal code:  (-6)
[runnervmmklqx:05173] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff19f445330]
[runnervmmklqx:05173] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff19f49eb2c]
[runnervmmklqx:05173] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff19f44527e]
[runnervmmklqx:05173] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff19f4288ff]
[runnervmmklqx:05173] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff19f8a5ff5]
[runnervmmklqx:05173] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff19f8bb0da]
[runnervmmklqx:05173] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff19f8a5a55]
[runnervmmklqx:05173] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff19f8a5a6f]
[runnervmmklqx:05173] [ 8] plumed_master(+0x146dd)[0x564181f7e6dd]
[runnervmmklqx:05173] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff19f42a1ca]
[runnervmmklqx:05173] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff19f42a28b]
[runnervmmklqx:05173] [11] plumed_master(+0x15365)[0x564181f7f365]
[runnervmmklqx:05173] *** End of error message ***
</pre>
{% endraw %}
