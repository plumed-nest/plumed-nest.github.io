**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[pkrvmxyh4eaekms:10532] *** Process received signal ***
[pkrvmxyh4eaekms:10532] Signal: Aborted (6)
[pkrvmxyh4eaekms:10532] Signal code:  (-6)
[pkrvmxyh4eaekms:10532] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7698045330]
[pkrvmxyh4eaekms:10532] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f769809eb2c]
[pkrvmxyh4eaekms:10532] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f769804527e]
[pkrvmxyh4eaekms:10532] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76980288ff]
[pkrvmxyh4eaekms:10532] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76984a5ff5]
[pkrvmxyh4eaekms:10532] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76984bb0da]
[pkrvmxyh4eaekms:10532] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76984a5a55]
[pkrvmxyh4eaekms:10532] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76984a5a6f]
[pkrvmxyh4eaekms:10532] [ 8] plumed_master(+0x146dd)[0x56003f3fa6dd]
[pkrvmxyh4eaekms:10532] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f769802a1ca]
[pkrvmxyh4eaekms:10532] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f769802a28b]
[pkrvmxyh4eaekms:10532] [11] plumed_master(+0x15365)[0x56003f3fb365]
[pkrvmxyh4eaekms:10532] *** End of error message ***
</pre>
{% endraw %}
