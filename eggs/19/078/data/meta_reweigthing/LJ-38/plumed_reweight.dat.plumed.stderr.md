**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COLLECT with label cc_ns : missing TYPE keyword.  TYPE should specify whether data is to be stored as a vector or a matrix
[fv-az1370-99:65762] *** Process received signal ***
[fv-az1370-99:65762] Signal: Aborted (6)
[fv-az1370-99:65762] Signal code:  (-6)
[fv-az1370-99:65762] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d60a45330]
[fv-az1370-99:65762] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d60a9eb2c]
[fv-az1370-99:65762] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d60a4527e]
[fv-az1370-99:65762] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d60a288ff]
[fv-az1370-99:65762] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d60ea5ff5]
[fv-az1370-99:65762] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d60ebb0da]
[fv-az1370-99:65762] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d60ea5a55]
[fv-az1370-99:65762] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d60ea5a6f]
[fv-az1370-99:65762] [ 8] plumed(+0x146dd)[0x55b1b88556dd]
[fv-az1370-99:65762] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d60a2a1ca]
[fv-az1370-99:65762] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d60a2a28b]
[fv-az1370-99:65762] [11] plumed(+0x15365)[0x55b1b8856365]
[fv-az1370-99:65762] *** End of error message ***
</pre>
{% endraw %}
