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
[fv-az1269-668:04760] *** Process received signal ***
[fv-az1269-668:04760] Signal: Aborted (6)
[fv-az1269-668:04760] Signal code:  (-6)
[fv-az1269-668:04760] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe94da42520]
[fv-az1269-668:04760] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe94da969fc]
[fv-az1269-668:04760] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe94da42476]
[fv-az1269-668:04760] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe94da287f3]
[fv-az1269-668:04760] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe94dea2b9e]
[fv-az1269-668:04760] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe94deae20c]
[fv-az1269-668:04760] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe94deae277]
[fv-az1269-668:04760] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe94deae52b]
[fv-az1269-668:04760] [ 8] plumed_master(+0x14274)[0x55ec5946a274]
[fv-az1269-668:04760] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe94da29d90]
[fv-az1269-668:04760] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe94da29e40]
[fv-az1269-668:04760] [11] plumed_master(+0x14ed5)[0x55ec5946aed5]
[fv-az1269-668:04760] *** End of error message ***
</pre>
{% endraw %}
