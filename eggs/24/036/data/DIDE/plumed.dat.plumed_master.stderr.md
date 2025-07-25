**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:06383] *** Process received signal ***
[pkrvmpptgkbjq6m:06383] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06383] Signal code:  (-6)
[pkrvmpptgkbjq6m:06383] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc728045330]
[pkrvmpptgkbjq6m:06383] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc72809eb2c]
[pkrvmpptgkbjq6m:06383] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc72804527e]
[pkrvmpptgkbjq6m:06383] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7280288ff]
[pkrvmpptgkbjq6m:06383] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7284a5ff5]
[pkrvmpptgkbjq6m:06383] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7284bb0da]
[pkrvmpptgkbjq6m:06383] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7284a5a55]
[pkrvmpptgkbjq6m:06383] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7284a5a6f]
[pkrvmpptgkbjq6m:06383] [ 8] plumed_master(+0x146dd)[0x556ee7dca6dd]
[pkrvmpptgkbjq6m:06383] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc72802a1ca]
[pkrvmpptgkbjq6m:06383] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc72802a28b]
[pkrvmpptgkbjq6m:06383] [11] plumed_master(+0x15365)[0x556ee7dcb365]
[pkrvmpptgkbjq6m:06383] *** End of error message ***
</pre>
{% endraw %}
