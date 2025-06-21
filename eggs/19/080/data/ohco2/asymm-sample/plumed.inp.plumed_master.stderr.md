**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:09193] *** Process received signal ***
[pkrvmxyh4eaekms:09193] Signal: Aborted (6)
[pkrvmxyh4eaekms:09193] Signal code:  (-6)
[pkrvmxyh4eaekms:09193] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f15fbc45330]
[pkrvmxyh4eaekms:09193] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f15fbc9eb2c]
[pkrvmxyh4eaekms:09193] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f15fbc4527e]
[pkrvmxyh4eaekms:09193] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f15fbc288ff]
[pkrvmxyh4eaekms:09193] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f15fc0a5ff5]
[pkrvmxyh4eaekms:09193] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f15fc0bb0da]
[pkrvmxyh4eaekms:09193] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f15fc0a5a55]
[pkrvmxyh4eaekms:09193] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f15fc0a5a6f]
[pkrvmxyh4eaekms:09193] [ 8] plumed_master(+0x146dd)[0x563032b0e6dd]
[pkrvmxyh4eaekms:09193] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f15fbc2a1ca]
[pkrvmxyh4eaekms:09193] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f15fbc2a28b]
[pkrvmxyh4eaekms:09193] [11] plumed_master(+0x15365)[0x563032b0f365]
[pkrvmxyh4eaekms:09193] *** End of error message ***
</pre>
{% endraw %}
