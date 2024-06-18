**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[fv-az883-206:04883] *** Process received signal ***
[fv-az883-206:04883] Signal: Aborted (6)
[fv-az883-206:04883] Signal code:  (-6)
[fv-az883-206:04883] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd218642520]
[fv-az883-206:04883] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd2186969fc]
[fv-az883-206:04883] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd218642476]
[fv-az883-206:04883] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd2186287f3]
[fv-az883-206:04883] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd218aa2b9e]
[fv-az883-206:04883] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd218aae20c]
[fv-az883-206:04883] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd218aae277]
[fv-az883-206:04883] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd218aae52b]
[fv-az883-206:04883] [ 8] plumed_master(+0x14274)[0x556c1043b274]
[fv-az883-206:04883] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd218629d90]
[fv-az883-206:04883] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd218629e40]
[fv-az883-206:04883] [11] plumed_master(+0x14ed5)[0x556c1043bed5]
[fv-az883-206:04883] *** End of error message ***
</pre>
{% endraw %}
