**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[fv-az985-228:68417] *** Process received signal ***
[fv-az985-228:68417] Signal: Aborted (6)
[fv-az985-228:68417] Signal code:  (-6)
[fv-az985-228:68417] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f20d3642520]
[fv-az985-228:68417] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f20d36969fc]
[fv-az985-228:68417] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f20d3642476]
[fv-az985-228:68417] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f20d36287f3]
[fv-az985-228:68417] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f20d3aa4f26]
[fv-az985-228:68417] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f20d3ab6d9c]
[fv-az985-228:68417] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f20d3ab6e07]
[fv-az985-228:68417] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f20d3ab70bb]
[fv-az985-228:68417] [ 8] plumed_master(+0x12e7f)[0x56143a7d4e7f]
[fv-az985-228:68417] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f20d3629d90]
[fv-az985-228:68417] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f20d3629e40]
[fv-az985-228:68417] [11] plumed_master(+0x13115)[0x56143a7d5115]
[fv-az985-228:68417] *** End of error message ***
</pre>
{% endraw %}
