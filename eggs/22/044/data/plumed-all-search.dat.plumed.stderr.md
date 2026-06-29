**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[runnervmmklqx:06093] *** Process received signal ***
[runnervmmklqx:06093] Signal: Aborted (6)
[runnervmmklqx:06093] Signal code:  (-6)
[runnervmmklqx:06093] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f076c645330]
[runnervmmklqx:06093] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f076c69eb2c]
[runnervmmklqx:06093] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f076c64527e]
[runnervmmklqx:06093] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f076c6288ff]
[runnervmmklqx:06093] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f076caa5ff5]
[runnervmmklqx:06093] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f076cabb0da]
[runnervmmklqx:06093] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f076caa5a55]
[runnervmmklqx:06093] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f076caa5a6f]
[runnervmmklqx:06093] [ 8] plumed(+0x146dd)[0x55abac38a6dd]
[runnervmmklqx:06093] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f076c62a1ca]
[runnervmmklqx:06093] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f076c62a28b]
[runnervmmklqx:06093] [11] plumed(+0x15365)[0x55abac38b365]
[runnervmmklqx:06093] *** End of error message ***
</pre>
{% endraw %}
