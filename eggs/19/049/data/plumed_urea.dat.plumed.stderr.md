**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[pkrvmpptgkbjq6m:11135] *** Process received signal ***
[pkrvmpptgkbjq6m:11135] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11135] Signal code:  (-6)
[pkrvmpptgkbjq6m:11135] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb29da45330]
[pkrvmpptgkbjq6m:11135] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb29da9eb2c]
[pkrvmpptgkbjq6m:11135] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb29da4527e]
[pkrvmpptgkbjq6m:11135] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb29da288ff]
[pkrvmpptgkbjq6m:11135] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb29dea5ff5]
[pkrvmpptgkbjq6m:11135] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb29debb0da]
[pkrvmpptgkbjq6m:11135] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb29dea5a55]
[pkrvmpptgkbjq6m:11135] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb29dea5a6f]
[pkrvmpptgkbjq6m:11135] [ 8] plumed(+0x146dd)[0x5654e297e6dd]
[pkrvmpptgkbjq6m:11135] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb29da2a1ca]
[pkrvmpptgkbjq6m:11135] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb29da2a28b]
[pkrvmpptgkbjq6m:11135] [11] plumed(+0x15365)[0x5654e297f365]
[pkrvmpptgkbjq6m:11135] *** End of error message ***
</pre>
{% endraw %}
