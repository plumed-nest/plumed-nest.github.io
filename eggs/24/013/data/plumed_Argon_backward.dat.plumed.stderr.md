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
[pkrvmpptgkbjq6m:06725] *** Process received signal ***
[pkrvmpptgkbjq6m:06725] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06725] Signal code:  (-6)
[pkrvmpptgkbjq6m:06725] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa92645330]
[pkrvmpptgkbjq6m:06725] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa9269eb2c]
[pkrvmpptgkbjq6m:06725] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa9264527e]
[pkrvmpptgkbjq6m:06725] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa926288ff]
[pkrvmpptgkbjq6m:06725] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa92aa5ff5]
[pkrvmpptgkbjq6m:06725] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa92abb0da]
[pkrvmpptgkbjq6m:06725] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa92aa5a55]
[pkrvmpptgkbjq6m:06725] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa92aa5a6f]
[pkrvmpptgkbjq6m:06725] [ 8] plumed(+0x146dd)[0x5559053af6dd]
[pkrvmpptgkbjq6m:06725] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa9262a1ca]
[pkrvmpptgkbjq6m:06725] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa9262a28b]
[pkrvmpptgkbjq6m:06725] [11] plumed(+0x15365)[0x5559053b0365]
[pkrvmpptgkbjq6m:06725] *** End of error message ***
</pre>
{% endraw %}
