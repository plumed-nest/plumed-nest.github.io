**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COLLECT with label cc_ns : missing TYPE keyword.  TYPE should specify whether data is to be stored as a vector or a matrix
[pkrvmf6wy0o8zjz:68295] *** Process received signal ***
[pkrvmf6wy0o8zjz:68295] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:68295] Signal code:  (-6)
[pkrvmf6wy0o8zjz:68295] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6217a45330]
[pkrvmf6wy0o8zjz:68295] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6217a9eb2c]
[pkrvmf6wy0o8zjz:68295] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6217a4527e]
[pkrvmf6wy0o8zjz:68295] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6217a288ff]
[pkrvmf6wy0o8zjz:68295] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6217ea5ff5]
[pkrvmf6wy0o8zjz:68295] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6217ebb0da]
[pkrvmf6wy0o8zjz:68295] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6217ea5a55]
[pkrvmf6wy0o8zjz:68295] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6217ea5a6f]
[pkrvmf6wy0o8zjz:68295] [ 8] plumed_master(+0x146dd)[0x562e7294b6dd]
[pkrvmf6wy0o8zjz:68295] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6217a2a1ca]
[pkrvmf6wy0o8zjz:68295] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6217a2a28b]
[pkrvmf6wy0o8zjz:68295] [11] plumed_master(+0x15365)[0x562e7294c365]
[pkrvmf6wy0o8zjz:68295] *** End of error message ***
</pre>
{% endraw %}
