**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmxyh4eaekms:06244] *** Process received signal ***
[pkrvmxyh4eaekms:06244] Signal: Aborted (6)
[pkrvmxyh4eaekms:06244] Signal code:  (-6)
[pkrvmxyh4eaekms:06244] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e1e045330]
[pkrvmxyh4eaekms:06244] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e1e09eb2c]
[pkrvmxyh4eaekms:06244] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e1e04527e]
[pkrvmxyh4eaekms:06244] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e1e0288ff]
[pkrvmxyh4eaekms:06244] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e1e4a5ff5]
[pkrvmxyh4eaekms:06244] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e1e4bb0da]
[pkrvmxyh4eaekms:06244] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e1e4a5a55]
[pkrvmxyh4eaekms:06244] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e1e4a5a6f]
[pkrvmxyh4eaekms:06244] [ 8] plumed_master(+0x146dd)[0x560a2bea26dd]
[pkrvmxyh4eaekms:06244] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e1e02a1ca]
[pkrvmxyh4eaekms:06244] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e1e02a28b]
[pkrvmxyh4eaekms:06244] [11] plumed_master(+0x15365)[0x560a2bea3365]
[pkrvmxyh4eaekms:06244] *** End of error message ***
</pre>
{% endraw %}
