**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:09257] *** Process received signal ***
[pkrvmxyh4eaekms:09257] Signal: Aborted (6)
[pkrvmxyh4eaekms:09257] Signal code:  (-6)
[pkrvmxyh4eaekms:09257] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f955b645330]
[pkrvmxyh4eaekms:09257] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f955b69eb2c]
[pkrvmxyh4eaekms:09257] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f955b64527e]
[pkrvmxyh4eaekms:09257] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f955b6288ff]
[pkrvmxyh4eaekms:09257] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f955baa5ff5]
[pkrvmxyh4eaekms:09257] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f955babb0da]
[pkrvmxyh4eaekms:09257] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f955baa5a55]
[pkrvmxyh4eaekms:09257] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f955baa5a6f]
[pkrvmxyh4eaekms:09257] [ 8] plumed_master(+0x146dd)[0x55a3abc726dd]
[pkrvmxyh4eaekms:09257] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f955b62a1ca]
[pkrvmxyh4eaekms:09257] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f955b62a28b]
[pkrvmxyh4eaekms:09257] [11] plumed_master(+0x15365)[0x55a3abc73365]
[pkrvmxyh4eaekms:09257] *** End of error message ***
</pre>
{% endraw %}
