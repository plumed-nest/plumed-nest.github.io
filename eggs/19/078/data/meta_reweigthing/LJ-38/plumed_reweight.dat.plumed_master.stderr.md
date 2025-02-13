**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action COLLECT with label cc_ns : missing TYPE keyword.  TYPE should specify whether data is to be stored as a vector or a matrix
[fv-az2035-366:11414] *** Process received signal ***
[fv-az2035-366:11414] Signal: Aborted (6)
[fv-az2035-366:11414] Signal code:  (-6)
[fv-az2035-366:11414] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0094645330]
[fv-az2035-366:11414] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f009469eb2c]
[fv-az2035-366:11414] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f009464527e]
[fv-az2035-366:11414] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f00946288ff]
[fv-az2035-366:11414] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0094aa5ff5]
[fv-az2035-366:11414] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0094abb0da]
[fv-az2035-366:11414] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0094aa5a55]
[fv-az2035-366:11414] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0094aa5a6f]
[fv-az2035-366:11414] [ 8] plumed_master(+0x146dd)[0x56528f4046dd]
[fv-az2035-366:11414] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f009462a1ca]
[fv-az2035-366:11414] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f009462a28b]
[fv-az2035-366:11414] [11] plumed_master(+0x15365)[0x56528f405365]
[fv-az2035-366:11414] *** End of error message ***
</pre>
{% endraw %}
