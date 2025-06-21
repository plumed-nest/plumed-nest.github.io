**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvmxyh4eaekms:07058] *** Process received signal ***
[pkrvmxyh4eaekms:07058] Signal: Aborted (6)
[pkrvmxyh4eaekms:07058] Signal code:  (-6)
[pkrvmxyh4eaekms:07058] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbe0d445330]
[pkrvmxyh4eaekms:07058] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbe0d49eb2c]
[pkrvmxyh4eaekms:07058] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbe0d44527e]
[pkrvmxyh4eaekms:07058] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbe0d4288ff]
[pkrvmxyh4eaekms:07058] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbe0d8a5ff5]
[pkrvmxyh4eaekms:07058] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbe0d8bb0da]
[pkrvmxyh4eaekms:07058] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbe0d8a5a55]
[pkrvmxyh4eaekms:07058] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbe0d8a5a6f]
[pkrvmxyh4eaekms:07058] [ 8] plumed(+0x146dd)[0x5586308766dd]
[pkrvmxyh4eaekms:07058] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbe0d42a1ca]
[pkrvmxyh4eaekms:07058] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbe0d42a28b]
[pkrvmxyh4eaekms:07058] [11] plumed(+0x15365)[0x558630877365]
[pkrvmxyh4eaekms:07058] *** End of error message ***
</pre>
{% endraw %}
