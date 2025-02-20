**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az1372-996:07525] *** Process received signal ***
[fv-az1372-996:07525] Signal: Aborted (6)
[fv-az1372-996:07525] Signal code:  (-6)
[fv-az1372-996:07525] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0080245330]
[fv-az1372-996:07525] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f008029eb2c]
[fv-az1372-996:07525] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f008024527e]
[fv-az1372-996:07525] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f00802288ff]
[fv-az1372-996:07525] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f00806a5ff5]
[fv-az1372-996:07525] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f00806bb0da]
[fv-az1372-996:07525] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f00806a5a55]
[fv-az1372-996:07525] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f00806a5a6f]
[fv-az1372-996:07525] [ 8] plumed(+0x146dd)[0x558d6bb646dd]
[fv-az1372-996:07525] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f008022a1ca]
[fv-az1372-996:07525] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f008022a28b]
[fv-az1372-996:07525] [11] plumed(+0x15365)[0x558d6bb65365]
[fv-az1372-996:07525] *** End of error message ***
</pre>
{% endraw %}
