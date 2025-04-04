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
[fv-az1360-658:06830] *** Process received signal ***
[fv-az1360-658:06830] Signal: Aborted (6)
[fv-az1360-658:06830] Signal code:  (-6)
[fv-az1360-658:06830] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda3ca45330]
[fv-az1360-658:06830] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda3ca9eb2c]
[fv-az1360-658:06830] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda3ca4527e]
[fv-az1360-658:06830] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda3ca288ff]
[fv-az1360-658:06830] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda3cea5ff5]
[fv-az1360-658:06830] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda3cebb0da]
[fv-az1360-658:06830] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda3cea5a55]
[fv-az1360-658:06830] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda3cea5a6f]
[fv-az1360-658:06830] [ 8] plumed(+0x146dd)[0x55b4da6ad6dd]
[fv-az1360-658:06830] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda3ca2a1ca]
[fv-az1360-658:06830] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda3ca2a28b]
[fv-az1360-658:06830] [11] plumed(+0x15365)[0x55b4da6ae365]
[fv-az1360-658:06830] *** End of error message ***
</pre>
{% endraw %}
