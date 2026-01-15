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
[runnervmi13qx:33953] *** Process received signal ***
[runnervmi13qx:33953] Signal: Aborted (6)
[runnervmi13qx:33953] Signal code:  (-6)
[runnervmi13qx:33953] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0d00c45330]
[runnervmi13qx:33953] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0d00c9eb2c]
[runnervmi13qx:33953] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0d00c4527e]
[runnervmi13qx:33953] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0d00c288ff]
[runnervmi13qx:33953] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0d010a5ff5]
[runnervmi13qx:33953] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0d010bb0da]
[runnervmi13qx:33953] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0d010a5a55]
[runnervmi13qx:33953] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0d010a5a6f]
[runnervmi13qx:33953] [ 8] plumed(+0x146dd)[0x5585f792b6dd]
[runnervmi13qx:33953] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0d00c2a1ca]
[runnervmi13qx:33953] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0d00c2a28b]
[runnervmi13qx:33953] [11] plumed(+0x15365)[0x5585f792c365]
[runnervmi13qx:33953] *** End of error message ***
</pre>
{% endraw %}
