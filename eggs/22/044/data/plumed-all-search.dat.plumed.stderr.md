**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[fv-az801-114:06499] *** Process received signal ***
[fv-az801-114:06499] Signal: Aborted (6)
[fv-az801-114:06499] Signal code:  (-6)
[fv-az801-114:06499] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd170642520]
[fv-az801-114:06499] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd1706969fc]
[fv-az801-114:06499] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd170642476]
[fv-az801-114:06499] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd1706287f3]
[fv-az801-114:06499] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd170aa2b9e]
[fv-az801-114:06499] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd170aae20c]
[fv-az801-114:06499] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd170aae277]
[fv-az801-114:06499] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd170aae52b]
[fv-az801-114:06499] [ 8] plumed(+0x14254)[0x55f92c477254]
[fv-az801-114:06499] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd170629d90]
[fv-az801-114:06499] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd170629e40]
[fv-az801-114:06499] [11] plumed(+0x14eb5)[0x55f92c477eb5]
[fv-az801-114:06499] *** End of error message ***
</pre>
{% endraw %}
