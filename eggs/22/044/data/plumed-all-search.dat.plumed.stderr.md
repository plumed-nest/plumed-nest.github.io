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
[runnervmvrwv9:07413] *** Process received signal ***
[runnervmvrwv9:07413] Signal: Aborted (6)
[runnervmvrwv9:07413] Signal code:  (-6)
[runnervmvrwv9:07413] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6a0445330]
[runnervmvrwv9:07413] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6a049eb2c]
[runnervmvrwv9:07413] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6a044527e]
[runnervmvrwv9:07413] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6a04288ff]
[runnervmvrwv9:07413] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6a08a5ff5]
[runnervmvrwv9:07413] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6a08bb0da]
[runnervmvrwv9:07413] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6a08a5a55]
[runnervmvrwv9:07413] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6a08a5a6f]
[runnervmvrwv9:07413] [ 8] plumed(+0x146dd)[0x564a51b366dd]
[runnervmvrwv9:07413] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6a042a1ca]
[runnervmvrwv9:07413] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6a042a28b]
[runnervmvrwv9:07413] [11] plumed(+0x15365)[0x564a51b37365]
[runnervmvrwv9:07413] *** End of error message ***
</pre>
{% endraw %}
