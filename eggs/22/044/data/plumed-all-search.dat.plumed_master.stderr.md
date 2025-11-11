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
[runnervmw9dnm:08693] *** Process received signal ***
[runnervmw9dnm:08693] Signal: Aborted (6)
[runnervmw9dnm:08693] Signal code:  (-6)
[runnervmw9dnm:08693] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3fffa45330]
[runnervmw9dnm:08693] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3fffa9eb2c]
[runnervmw9dnm:08693] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3fffa4527e]
[runnervmw9dnm:08693] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3fffa288ff]
[runnervmw9dnm:08693] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3fffea5ff5]
[runnervmw9dnm:08693] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3fffebb0da]
[runnervmw9dnm:08693] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3fffea5a55]
[runnervmw9dnm:08693] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3fffea5a6f]
[runnervmw9dnm:08693] [ 8] plumed_master(+0x146dd)[0x55ea7d4d96dd]
[runnervmw9dnm:08693] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3fffa2a1ca]
[runnervmw9dnm:08693] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3fffa2a28b]
[runnervmw9dnm:08693] [11] plumed_master(+0x15365)[0x55ea7d4da365]
[runnervmw9dnm:08693] *** End of error message ***
</pre>
{% endraw %}
