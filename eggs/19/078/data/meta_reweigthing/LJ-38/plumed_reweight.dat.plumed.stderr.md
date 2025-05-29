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
[pkrvmf6wy0o8zjz:68279] *** Process received signal ***
[pkrvmf6wy0o8zjz:68279] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:68279] Signal code:  (-6)
[pkrvmf6wy0o8zjz:68279] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d04245330]
[pkrvmf6wy0o8zjz:68279] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d0429eb2c]
[pkrvmf6wy0o8zjz:68279] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d0424527e]
[pkrvmf6wy0o8zjz:68279] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d042288ff]
[pkrvmf6wy0o8zjz:68279] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d046a5ff5]
[pkrvmf6wy0o8zjz:68279] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d046bb0da]
[pkrvmf6wy0o8zjz:68279] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d046a5a55]
[pkrvmf6wy0o8zjz:68279] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d046a5a6f]
[pkrvmf6wy0o8zjz:68279] [ 8] plumed(+0x146dd)[0x559cee5716dd]
[pkrvmf6wy0o8zjz:68279] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d0422a1ca]
[pkrvmf6wy0o8zjz:68279] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d0422a28b]
[pkrvmf6wy0o8zjz:68279] [11] plumed(+0x15365)[0x559cee572365]
[pkrvmf6wy0o8zjz:68279] *** End of error message ***
</pre>
{% endraw %}
