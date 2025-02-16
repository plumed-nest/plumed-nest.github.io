**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[fv-az1937-158:63895] *** Process received signal ***
[fv-az1937-158:63895] Signal: Aborted (6)
[fv-az1937-158:63895] Signal code:  (-6)
[fv-az1937-158:63895] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb7e7a45330]
[fv-az1937-158:63895] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb7e7a9eb2c]
[fv-az1937-158:63895] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb7e7a4527e]
[fv-az1937-158:63895] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7e7a288ff]
[fv-az1937-158:63895] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7e7ea5ff5]
[fv-az1937-158:63895] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7e7ebb0da]
[fv-az1937-158:63895] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7e7ea5a55]
[fv-az1937-158:63895] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7e7ea5a6f]
[fv-az1937-158:63895] [ 8] plumed(+0x146dd)[0x55f5d694a6dd]
[fv-az1937-158:63895] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb7e7a2a1ca]
[fv-az1937-158:63895] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb7e7a2a28b]
[fv-az1937-158:63895] [11] plumed(+0x15365)[0x55f5d694b365]
[fv-az1937-158:63895] *** End of error message ***
</pre>
{% endraw %}
