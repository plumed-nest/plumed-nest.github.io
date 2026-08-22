**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[runnervm76f27:08370] *** Process received signal ***
[runnervm76f27:08370] Signal: Aborted (6)
[runnervm76f27:08370] Signal code:  (-6)
[runnervm76f27:08370] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f35a2045330]
[runnervm76f27:08370] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f35a209ec0c]
[runnervm76f27:08370] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f35a204527e]
[runnervm76f27:08370] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f35a20288ff]
[runnervm76f27:08370] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35a24a5ff5]
[runnervm76f27:08370] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35a24bb0da]
[runnervm76f27:08370] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35a24a5a55]
[runnervm76f27:08370] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35a24a5a6f]
[runnervm76f27:08370] [ 8] plumed_master(+0x146dd)[0x5564407fd6dd]
[runnervm76f27:08370] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f35a202a1ca]
[runnervm76f27:08370] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f35a202a28b]
[runnervm76f27:08370] [11] plumed_master(+0x15365)[0x5564407fe365]
[runnervm76f27:08370] *** End of error message ***
</pre>
{% endraw %}
