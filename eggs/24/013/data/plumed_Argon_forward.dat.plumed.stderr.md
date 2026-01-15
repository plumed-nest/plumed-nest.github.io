**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmi13qx:34006] *** Process received signal ***
[runnervmi13qx:34006] Signal: Aborted (6)
[runnervmi13qx:34006] Signal code:  (-6)
[runnervmi13qx:34006] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f70bbc45330]
[runnervmi13qx:34006] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f70bbc9eb2c]
[runnervmi13qx:34006] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f70bbc4527e]
[runnervmi13qx:34006] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f70bbc288ff]
[runnervmi13qx:34006] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f70bc0a5ff5]
[runnervmi13qx:34006] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f70bc0bb0da]
[runnervmi13qx:34006] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f70bc0a5a55]
[runnervmi13qx:34006] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f70bc0a5a6f]
[runnervmi13qx:34006] [ 8] plumed(+0x146dd)[0x56198346b6dd]
[runnervmi13qx:34006] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f70bbc2a1ca]
[runnervmi13qx:34006] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f70bbc2a28b]
[runnervmi13qx:34006] [11] plumed(+0x15365)[0x56198346c365]
[runnervmi13qx:34006] *** End of error message ***
</pre>
{% endraw %}
