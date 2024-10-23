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
[fv-az801-114:06507] *** Process received signal ***
[fv-az801-114:06507] Signal: Aborted (6)
[fv-az801-114:06507] Signal code:  (-6)
[fv-az801-114:06507] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f494cc42520]
[fv-az801-114:06507] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f494cc969fc]
[fv-az801-114:06507] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f494cc42476]
[fv-az801-114:06507] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f494cc287f3]
[fv-az801-114:06507] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f494d0a2b9e]
[fv-az801-114:06507] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f494d0ae20c]
[fv-az801-114:06507] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f494d0ae277]
[fv-az801-114:06507] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f494d0ae52b]
[fv-az801-114:06507] [ 8] plumed_master(+0x14254)[0x55871b2ff254]
[fv-az801-114:06507] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f494cc29d90]
[fv-az801-114:06507] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f494cc29e40]
[fv-az801-114:06507] [11] plumed_master(+0x14eb5)[0x55871b2ffeb5]
[fv-az801-114:06507] *** End of error message ***
</pre>
{% endraw %}
