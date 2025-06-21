**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmxyh4eaekms:06298] *** Process received signal ***
[pkrvmxyh4eaekms:06298] Signal: Aborted (6)
[pkrvmxyh4eaekms:06298] Signal code:  (-6)
[pkrvmxyh4eaekms:06298] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d9c845330]
[pkrvmxyh4eaekms:06298] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d9c89eb2c]
[pkrvmxyh4eaekms:06298] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d9c84527e]
[pkrvmxyh4eaekms:06298] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d9c8288ff]
[pkrvmxyh4eaekms:06298] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d9cca5ff5]
[pkrvmxyh4eaekms:06298] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d9ccbb0da]
[pkrvmxyh4eaekms:06298] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d9cca5a55]
[pkrvmxyh4eaekms:06298] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d9cca5a6f]
[pkrvmxyh4eaekms:06298] [ 8] plumed_master(+0x146dd)[0x55b88915c6dd]
[pkrvmxyh4eaekms:06298] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d9c82a1ca]
[pkrvmxyh4eaekms:06298] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d9c82a28b]
[pkrvmxyh4eaekms:06298] [11] plumed_master(+0x15365)[0x55b88915d365]
[pkrvmxyh4eaekms:06298] *** End of error message ***
</pre>
{% endraw %}
