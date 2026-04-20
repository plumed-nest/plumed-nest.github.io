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
[runnervmeorf1:07910] *** Process received signal ***
[runnervmeorf1:07910] Signal: Aborted (6)
[runnervmeorf1:07910] Signal code:  (-6)
[runnervmeorf1:07910] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd42f245330]
[runnervmeorf1:07910] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd42f29eb2c]
[runnervmeorf1:07910] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd42f24527e]
[runnervmeorf1:07910] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd42f2288ff]
[runnervmeorf1:07910] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd42f6a5ff5]
[runnervmeorf1:07910] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd42f6bb0da]
[runnervmeorf1:07910] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd42f6a5a55]
[runnervmeorf1:07910] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd42f6a5a6f]
[runnervmeorf1:07910] [ 8] plumed_master(+0x146dd)[0x556ca10696dd]
[runnervmeorf1:07910] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd42f22a1ca]
[runnervmeorf1:07910] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd42f22a28b]
[runnervmeorf1:07910] [11] plumed_master(+0x15365)[0x556ca106a365]
[runnervmeorf1:07910] *** End of error message ***
</pre>
{% endraw %}
