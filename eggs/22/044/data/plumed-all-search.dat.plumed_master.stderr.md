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
[runnervmvrwv9:07428] *** Process received signal ***
[runnervmvrwv9:07428] Signal: Aborted (6)
[runnervmvrwv9:07428] Signal code:  (-6)
[runnervmvrwv9:07428] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7a07445330]
[runnervmvrwv9:07428] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7a0749eb2c]
[runnervmvrwv9:07428] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7a0744527e]
[runnervmvrwv9:07428] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7a074288ff]
[runnervmvrwv9:07428] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7a078a5ff5]
[runnervmvrwv9:07428] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7a078bb0da]
[runnervmvrwv9:07428] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7a078a5a55]
[runnervmvrwv9:07428] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7a078a5a6f]
[runnervmvrwv9:07428] [ 8] plumed_master(+0x146dd)[0x55a61314b6dd]
[runnervmvrwv9:07428] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7a0742a1ca]
[runnervmvrwv9:07428] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7a0742a28b]
[runnervmvrwv9:07428] [11] plumed_master(+0x15365)[0x55a61314c365]
[runnervmvrwv9:07428] *** End of error message ***
</pre>
{% endraw %}
