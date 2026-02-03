**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[runnervmkj6or:07454] *** Process received signal ***
[runnervmkj6or:07454] Signal: Aborted (6)
[runnervmkj6or:07454] Signal code:  (-6)
[runnervmkj6or:07454] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3fbea45330]
[runnervmkj6or:07454] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3fbea9eb2c]
[runnervmkj6or:07454] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3fbea4527e]
[runnervmkj6or:07454] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3fbea288ff]
[runnervmkj6or:07454] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3fbeea5ff5]
[runnervmkj6or:07454] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3fbeebb0da]
[runnervmkj6or:07454] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3fbeea5a55]
[runnervmkj6or:07454] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3fbeea5a6f]
[runnervmkj6or:07454] [ 8] plumed_master(+0x146dd)[0x555d323d16dd]
[runnervmkj6or:07454] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3fbea2a1ca]
[runnervmkj6or:07454] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3fbea2a28b]
[runnervmkj6or:07454] [11] plumed_master(+0x15365)[0x555d323d2365]
[runnervmkj6or:07454] *** End of error message ***
</pre>
{% endraw %}
