**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w0.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w0.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w0.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervmmklqx:04499] *** Process received signal ***
[runnervmmklqx:04499] Signal: Aborted (6)
[runnervmmklqx:04499] Signal code:  (-6)
[runnervmmklqx:04499] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f496e045330]
[runnervmmklqx:04499] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f496e09eb2c]
[runnervmmklqx:04499] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f496e04527e]
[runnervmmklqx:04499] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f496e0288ff]
[runnervmmklqx:04499] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f496e4a5ff5]
[runnervmmklqx:04499] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f496e4bb0da]
[runnervmmklqx:04499] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f496e4a5a55]
[runnervmmklqx:04499] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f496e4a5a6f]
[runnervmmklqx:04499] [ 8] plumed_master(+0x146dd)[0x56220eaaa6dd]
[runnervmmklqx:04499] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f496e02a1ca]
[runnervmmklqx:04499] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f496e02a28b]
[runnervmmklqx:04499] [11] plumed_master(+0x15365)[0x56220eaab365]
[runnervmmklqx:04499] *** End of error message ***
</pre>
{% endraw %}
