**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az1937-158:61086] *** Process received signal ***
[fv-az1937-158:61086] Signal: Aborted (6)
[fv-az1937-158:61086] Signal code:  (-6)
[fv-az1937-158:61086] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4f9c45330]
[fv-az1937-158:61086] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4f9c9eb2c]
[fv-az1937-158:61086] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4f9c4527e]
[fv-az1937-158:61086] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4f9c288ff]
[fv-az1937-158:61086] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4fa0a5ff5]
[fv-az1937-158:61086] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4fa0bb0da]
[fv-az1937-158:61086] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4fa0a5a55]
[fv-az1937-158:61086] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4fa0a5a6f]
[fv-az1937-158:61086] [ 8] plumed(+0x146dd)[0x5608dccc06dd]
[fv-az1937-158:61086] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4f9c2a1ca]
[fv-az1937-158:61086] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4f9c2a28b]
[fv-az1937-158:61086] [11] plumed(+0x15365)[0x5608dccc1365]
[fv-az1937-158:61086] *** End of error message ***
</pre>
{% endraw %}
