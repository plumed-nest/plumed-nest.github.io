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
[runnervmmklqx:06109] *** Process received signal ***
[runnervmmklqx:06109] Signal: Aborted (6)
[runnervmmklqx:06109] Signal code:  (-6)
[runnervmmklqx:06109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6b23245330]
[runnervmmklqx:06109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6b2329eb2c]
[runnervmmklqx:06109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6b2324527e]
[runnervmmklqx:06109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6b232288ff]
[runnervmmklqx:06109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6b236a5ff5]
[runnervmmklqx:06109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6b236bb0da]
[runnervmmklqx:06109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6b236a5a55]
[runnervmmklqx:06109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6b236a5a6f]
[runnervmmklqx:06109] [ 8] plumed_master(+0x146dd)[0x55790be5d6dd]
[runnervmmklqx:06109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6b2322a1ca]
[runnervmmklqx:06109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6b2322a28b]
[runnervmmklqx:06109] [11] plumed_master(+0x15365)[0x55790be5e365]
[runnervmmklqx:06109] *** End of error message ***
</pre>
{% endraw %}
