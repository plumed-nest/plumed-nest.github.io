**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmi13qx:34022] *** Process received signal ***
[runnervmi13qx:34022] Signal: Aborted (6)
[runnervmi13qx:34022] Signal code:  (-6)
[runnervmi13qx:34022] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3412245330]
[runnervmi13qx:34022] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f341229eb2c]
[runnervmi13qx:34022] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f341224527e]
[runnervmi13qx:34022] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34122288ff]
[runnervmi13qx:34022] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34126a5ff5]
[runnervmi13qx:34022] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34126bb0da]
[runnervmi13qx:34022] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34126a5a55]
[runnervmi13qx:34022] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34126a5a6f]
[runnervmi13qx:34022] [ 8] plumed_master(+0x146dd)[0x555b1ff196dd]
[runnervmi13qx:34022] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f341222a1ca]
[runnervmi13qx:34022] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f341222a28b]
[runnervmi13qx:34022] [11] plumed_master(+0x15365)[0x555b1ff1a365]
[runnervmi13qx:34022] *** End of error message ***
</pre>
{% endraw %}
