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
[runnervmkj6or:07438] *** Process received signal ***
[runnervmkj6or:07438] Signal: Aborted (6)
[runnervmkj6or:07438] Signal code:  (-6)
[runnervmkj6or:07438] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f583da45330]
[runnervmkj6or:07438] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f583da9eb2c]
[runnervmkj6or:07438] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f583da4527e]
[runnervmkj6or:07438] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f583da288ff]
[runnervmkj6or:07438] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f583dea5ff5]
[runnervmkj6or:07438] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f583debb0da]
[runnervmkj6or:07438] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f583dea5a55]
[runnervmkj6or:07438] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f583dea5a6f]
[runnervmkj6or:07438] [ 8] plumed(+0x146dd)[0x5639555886dd]
[runnervmkj6or:07438] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f583da2a1ca]
[runnervmkj6or:07438] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f583da2a28b]
[runnervmkj6or:07438] [11] plumed(+0x15365)[0x563955589365]
[runnervmkj6or:07438] *** End of error message ***
</pre>
{% endraw %}
