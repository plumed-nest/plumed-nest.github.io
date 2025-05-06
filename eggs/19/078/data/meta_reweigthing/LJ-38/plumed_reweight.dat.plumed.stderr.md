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
[fv-az1781-652:67218] *** Process received signal ***
[fv-az1781-652:67218] Signal: Aborted (6)
[fv-az1781-652:67218] Signal code:  (-6)
[fv-az1781-652:67218] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb387045330]
[fv-az1781-652:67218] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb38709eb2c]
[fv-az1781-652:67218] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb38704527e]
[fv-az1781-652:67218] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb3870288ff]
[fv-az1781-652:67218] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb3874a5ff5]
[fv-az1781-652:67218] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb3874bb0da]
[fv-az1781-652:67218] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb3874a5a55]
[fv-az1781-652:67218] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb3874a5a6f]
[fv-az1781-652:67218] [ 8] plumed(+0x146dd)[0x564ff48216dd]
[fv-az1781-652:67218] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb38702a1ca]
[fv-az1781-652:67218] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb38702a28b]
[fv-az1781-652:67218] [11] plumed(+0x15365)[0x564ff4822365]
[fv-az1781-652:67218] *** End of error message ***
</pre>
{% endraw %}
