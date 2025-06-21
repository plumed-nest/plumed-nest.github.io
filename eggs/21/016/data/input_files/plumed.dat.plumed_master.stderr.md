**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmxyh4eaekms:09861] *** Process received signal ***
[pkrvmxyh4eaekms:09861] Signal: Aborted (6)
[pkrvmxyh4eaekms:09861] Signal code:  (-6)
[pkrvmxyh4eaekms:09861] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6bf9845330]
[pkrvmxyh4eaekms:09861] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6bf989eb2c]
[pkrvmxyh4eaekms:09861] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6bf984527e]
[pkrvmxyh4eaekms:09861] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6bf98288ff]
[pkrvmxyh4eaekms:09861] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6bf9ca5ff5]
[pkrvmxyh4eaekms:09861] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6bf9cbb0da]
[pkrvmxyh4eaekms:09861] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6bf9ca5a55]
[pkrvmxyh4eaekms:09861] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6bf9ca5a6f]
[pkrvmxyh4eaekms:09861] [ 8] plumed_master(+0x146dd)[0x55ae28d5d6dd]
[pkrvmxyh4eaekms:09861] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6bf982a1ca]
[pkrvmxyh4eaekms:09861] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6bf982a28b]
[pkrvmxyh4eaekms:09861] [11] plumed_master(+0x15365)[0x55ae28d5e365]
[pkrvmxyh4eaekms:09861] *** End of error message ***
</pre>
{% endraw %}
