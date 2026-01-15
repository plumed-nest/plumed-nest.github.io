**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @70 : keyword ARG is compulsory for this action
[runnervmi13qx:35142] *** Process received signal ***
[runnervmi13qx:35142] Signal: Aborted (6)
[runnervmi13qx:35142] Signal code:  (-6)
[runnervmi13qx:35142] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b40645330]
[runnervmi13qx:35142] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b4069eb2c]
[runnervmi13qx:35142] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b4064527e]
[runnervmi13qx:35142] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b406288ff]
[runnervmi13qx:35142] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b40aa5ff5]
[runnervmi13qx:35142] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b40abb0da]
[runnervmi13qx:35142] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b40aa5a55]
[runnervmi13qx:35142] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b40aa5a6f]
[runnervmi13qx:35142] [ 8] plumed_master(+0x146dd)[0x55e8dc6236dd]
[runnervmi13qx:35142] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b4062a1ca]
[runnervmi13qx:35142] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b4062a28b]
[runnervmi13qx:35142] [11] plumed_master(+0x15365)[0x55e8dc624365]
[runnervmi13qx:35142] *** End of error message ***
</pre>
{% endraw %}
