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
[fv-az789-879:66326] *** Process received signal ***
[fv-az789-879:66326] Signal: Aborted (6)
[fv-az789-879:66326] Signal code:  (-6)
[fv-az789-879:66326] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb23c845330]
[fv-az789-879:66326] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb23c89eb2c]
[fv-az789-879:66326] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb23c84527e]
[fv-az789-879:66326] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb23c8288ff]
[fv-az789-879:66326] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb23cca5ff5]
[fv-az789-879:66326] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb23ccbb0da]
[fv-az789-879:66326] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb23cca5a55]
[fv-az789-879:66326] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb23cca5a6f]
[fv-az789-879:66326] [ 8] plumed_master(+0x146dd)[0x563e6c5536dd]
[fv-az789-879:66326] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb23c82a1ca]
[fv-az789-879:66326] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb23c82a28b]
[fv-az789-879:66326] [11] plumed_master(+0x15365)[0x563e6c554365]
[fv-az789-879:66326] *** End of error message ***
</pre>
{% endraw %}
