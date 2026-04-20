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
[runnervmeorf1:07894] *** Process received signal ***
[runnervmeorf1:07894] Signal: Aborted (6)
[runnervmeorf1:07894] Signal code:  (-6)
[runnervmeorf1:07894] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2586645330]
[runnervmeorf1:07894] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f258669eb2c]
[runnervmeorf1:07894] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f258664527e]
[runnervmeorf1:07894] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f25866288ff]
[runnervmeorf1:07894] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2586aa5ff5]
[runnervmeorf1:07894] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2586abb0da]
[runnervmeorf1:07894] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2586aa5a55]
[runnervmeorf1:07894] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2586aa5a6f]
[runnervmeorf1:07894] [ 8] plumed(+0x146dd)[0x55781693d6dd]
[runnervmeorf1:07894] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f258662a1ca]
[runnervmeorf1:07894] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f258662a28b]
[runnervmeorf1:07894] [11] plumed(+0x15365)[0x55781693e365]
[runnervmeorf1:07894] *** End of error message ***
</pre>
{% endraw %}
