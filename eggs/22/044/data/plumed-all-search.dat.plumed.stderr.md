**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvmq0rgcvqdmg:09544] *** Process received signal ***
[pkrvmq0rgcvqdmg:09544] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09544] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09544] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4597845330]
[pkrvmq0rgcvqdmg:09544] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f459789eb2c]
[pkrvmq0rgcvqdmg:09544] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f459784527e]
[pkrvmq0rgcvqdmg:09544] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45978288ff]
[pkrvmq0rgcvqdmg:09544] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4597ca5ff5]
[pkrvmq0rgcvqdmg:09544] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4597cbb0da]
[pkrvmq0rgcvqdmg:09544] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4597ca5a55]
[pkrvmq0rgcvqdmg:09544] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4597ca5a6f]
[pkrvmq0rgcvqdmg:09544] [ 8] plumed(+0x146dd)[0x560e6983f6dd]
[pkrvmq0rgcvqdmg:09544] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f459782a1ca]
[pkrvmq0rgcvqdmg:09544] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f459782a28b]
[pkrvmq0rgcvqdmg:09544] [11] plumed(+0x15365)[0x560e69840365]
[pkrvmq0rgcvqdmg:09544] *** End of error message ***
</pre>
{% endraw %}
